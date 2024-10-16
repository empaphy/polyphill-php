# polyphill-php

A metapackage for PHP that installs the polyfills you need, and removes those
that are redundant.

## How do I use this?

Add the `polyphill-php` to your project like this:

```bash
composer require 'empaphy/polyphill-php:^1'
```

## How does this work?

This metapackage makes clever use of composer dependencies to ensure that
the Symfony polyfill packages are installed only for the exact PHP versions
that you need. This reduces the footprint of your vendor directory.

Since polyphill is a metapackage it doesn't take up any actual space in your
vendor directory itself.
