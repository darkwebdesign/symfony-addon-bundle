# Symfony Add-on Bundle

[![Latest Stable Version](https://poser.pugx.org/darkwebdesign/symfony-addon-bundle/v/stable?format=flat)](https://packagist.org/packages/darkwebdesign/symfony-addon-bundle)
[![Total Downloads](https://poser.pugx.org/darkwebdesign/symfony-addon-bundle/downloads?format=flat)](https://packagist.org/packages/darkwebdesign/symfony-addon-bundle)
[![License](https://poser.pugx.org/darkwebdesign/symfony-addon-bundle/license?format=flat)](https://packagist.org/packages/darkwebdesign/symfony-addon-bundle)

[![Build Status](https://travis-ci.org/darkwebdesign/symfony-addon-bundle.svg?branch=4.0)](https://travis-ci.org/darkwebdesign/symfony-addon-bundle?branch=4.0)
[![PHP Version](https://img.shields.io/badge/php-7.1%2B-777BB3.svg)](https://php.net/)
[![Symfony Version](https://img.shields.io/badge/symfony-4.0-93C74B.svg)](https://symfony.com/)

Symfony Add-on Bundle conveniently wraps the [Symfony Add-on Pack](https://github.com/darkwebdesign/symfony-addon-pack) with a Symfony Bundle that you can use
in your Symfony applications.

## Installing via Composer

```bash
composer require darkwebdesign/symfony-addon-bundle
```

```bash
composer install
```

## Enabling the bundle in Symfony

```php
// app/AppKernel.php
public function registerBundles()
{
    $bundles = array(
        // ...
        new DarkWebDesign\SymfonyAddonBundle\DarkWebDesignSymfonyAddonBundle(),
    );

    // ...
}
```


## License

Symfony Add-on Bundle is licensed under the MIT License - see the `LICENSE` file for details.
