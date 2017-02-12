# Symfony Add-on Bundle

[![Latest Stable Version](https://poser.pugx.org/darkwebdesign/symfony-addon-bundle/v/stable?format=flat)](https://packagist.org/packages/darkwebdesign/symfony-addon-bundle)
[![Total Downloads](https://poser.pugx.org/darkwebdesign/symfony-addon-bundle/downloads?format=flat)](https://packagist.org/packages/darkwebdesign/symfony-addon-bundle)
[![License](https://poser.pugx.org/darkwebdesign/symfony-addon-bundle/license?format=flat)](https://packagist.org/packages/darkwebdesign/symfony-addon-bundle)

[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%205.3-blue.svg)](https://php.net/)
[![Minimum Symfony Version](https://img.shields.io/badge/symfony-%3E%3D%202.3-green.svg)](https://symfony.com/)

Symfony Add-on Bundle conveniently wraps the [Symfony Add-on Pack](https://github.com/darkwebdesign/symfony-addon-pack) with a Symfony Bundle that you can use
in your Symfony applications.

Learn more about it in its [documentation](https://github.com/darkwebdesign/symfony-addon-bundle/blob/2.4/doc/index.md).

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
