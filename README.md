# Permitted

[![Latest Version on Packagist](https://img.shields.io/packagist/v/williamug/permitted.svg?style=flat-square)](https://packagist.org/packages/williamug/permitted)
[![GitHub Tests Action Status](https://img.shields.io/github/actions/workflow/status/williamug/permitted/run-tests.yml?branch=main&label=tests&style=flat-square)](https://github.com/williamug/permitted/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/actions/workflow/status/williamug/permitted/fix-php-code-style-issues.yml?branch=main&label=code%20style&style=flat-square)](https://github.com/williamug/permitted/actions?query=workflow%3A"Fix+PHP+code+style+issues"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/williamug/permitted.svg?style=flat-square)](https://packagist.org/packages/williamug/permitted)

This is a package that allow you to set permission in your application. It has support for multi-businesses and multi-branches using a single database approach.

## Installation

You can install the package via composer:

```bash
composer require williamug/permitted
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="permitted-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="permitted-config"
```

This is the contents of the published config file:

```php
return [
];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="permitted-views"
```

## Usage

```php
//
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Asaba William](https://github.com/williamug)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
