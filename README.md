# Laravel GIT Commit Checker

<p align="center">
    <img src="/art/overview.png" alt="Overview Git Commit Checker" style="width:70%;">
</p>

<p align="center">
    <a href="https://packagist.org/packages/guestcms/git-commit-checker"><img src="https://img.shields.io/packagist/v/guestcms/git-commit-checker.svg?style=flat-square" alt="Latest Version"></a>
    <a href="/LICENSE"><img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License"></a>
    <a href="https://packagist.org/packages/guestcms/git-commit-checker"><img src="https://img.shields.io/packagist/dt/guestcms/git-commit-checker.svg?style=flat-square" alt="Total Downloads"></a>
    <a href="https://codeclimate.com/github/guestcms/git-commit-checker/maintainability"><img src="https://api.codeclimate.com/v1/badges/a6e4612307e3b3bf8252/maintainability" alt="Maintainability"></a>
</p>

## Requirement

- Laravel 9.32 or later
- If you're using Laravel 8.0 or earlier, please use version 1.x

## Installation

You can install the package via composer:

```shell
composer require guestcms/git-commit-checker
```

Publish the configuration:

```bash
php artisan vendor:publish --tag=git-commit-checker-config
```

### Install GIT hooks

Run this command to install:

```shell
php artisan git-commit-checker:install
```

Run test manually (made sure you've added all changed files to git stage):

```shell
php artisan git-commit-checker:pre-commit-hook
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email support@coastalmediabrand.com instead of using the issue tracker.

## Credits

- [Justin Malonson](https://justinmalonson.com)
- [Coastal Media Brand](https://coastalmediabrand.com)


## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
