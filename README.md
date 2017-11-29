# :zap: Templater
> WordPress module to create custom ( page and post type ) templates with plugins.

[![Build Status](https://travis-ci.com/mohamdio/wp-templater.svg?token=bRxzrnGmzUbSj8ogmJVZ&branch=master)](https://travis-ci.com/mohamdio/wp-templater) [![License: GPL-2.0+](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)

## Installation

#### :heavy_exclamation_mark: Minimum requirements

**PHP:** 5.6

**WordPress:** 4.6

#### :heavy_minus_sign: Install with composer

Run the following in your terminal to install **wp-templater** with [Composer](https://getcomposer.org/).

```
composer require jozoor/wp-templater
```

As **wp-templater** uses [PSR-4](http://www.php-fig.org/psr/psr-4/) autoloading you will need to use Composers autoloader. Below is a basic example of getting started with the class, though your setup maybe different depending on how you are using composer, this example below show you simple usage of create new post type:

```php
require_once __DIR__ . '/vendor/autoload.php';

use JO\Module\Templater\Templater;
```

See Composers [basic usage](https://getcomposer.org/doc/01-basic-usage.md#autoloading) guide for details on working Composer and autoloading.

#### :heavy_minus_sign: Download the module and include it manually

If you don't using composer and want to to include the library manually, you can do that, this example below show you simple usage of create new post type:

```php
/**
 * load main file
 */

require_once __DIR__ . '/wp-templater/src/Templater.php';

use JO\Module\Templater\Templater;
```

## Usage



## Author

**Mohamed Abd Elhalim**

- [site](https://mohamd.io/)
- [twitter](https://twitter.com/mohamdio)
