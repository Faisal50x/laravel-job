

# This is my package laravel-job

[![Latest Version on Packagist](https://img.shields.io/packagist/v/faisal50x/laravel-job.svg?style=flat-square)](https://packagist.org/packages/faisal50x/laravel-job)
[![GitHub Tests Action Status](https://img.shields.io/github/workflow/status/faisal50x/laravel-job/run-tests?label=tests)](https://github.com/faisal50x/laravel-job/actions?query=workflow%3Arun-tests+branch%3Amain)
[![GitHub Code Style Action Status](https://img.shields.io/github/workflow/status/faisal50x/laravel-job/Check%20&%20fix%20styling?label=code%20style)](https://github.com/faisal50x/laravel-job/actions?query=workflow%3A"Check+%26+fix+styling"+branch%3Amain)
[![Total Downloads](https://img.shields.io/packagist/dt/faisal50x/laravel-job.svg?style=flat-square)](https://packagist.org/packages/faisal50x/laravel-job)

This is where your description should go. Limit it to a paragraph or two. Consider adding a small example.

## Installation

You can install the package via composer:

```bash
composer require faisal50x/laravel-job
```

You can publish and run the migrations with:

```bash
php artisan vendor:publish --tag="laravel-job-migrations"
php artisan migrate
```

You can publish the config file with:

```bash
php artisan vendor:publish --tag="laravel-job-config"
```

This is the contents of the published config file:

```php
return [
];
```

Optionally, you can publish the views using

```bash
php artisan vendor:publish --tag="laravel-job-views"
```

## Usage

```php
$laravelJob = new Faisal50x\LaravelJob();
echo $laravelJob->echoPhrase('Hello, Faisal50x!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](https://github.com/Faisal50x/.github/blob/main/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Faisal Ahmed](https://github.com/Faisal50x)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
