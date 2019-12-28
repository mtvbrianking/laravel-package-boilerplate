## Laravel Package Boilerplate.

[![Build Status](https://travis-ci.org/mtvbrianking/laravel-package-boilerplate.svg?branch=master)](https://travis-ci.org/mtvbrianking/laravel-package-boilerplate)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/mtvbrianking/laravel-package-boilerplate/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/mtvbrianking/laravel-package-boilerplate/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/mtvbrianking/laravel-package-boilerplate/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/mtvbrianking/laravel-package-boilerplate/?branch=master)
[![StyleCI](https://github.styleci.io/repos/230489612/shield?branch=master)](https://github.styleci.io/repos/230489612)
[![Documentation](https://img.shields.io/badge/Documentation-Blue)](https://mtvbrianking.github.io/laravel-package-boilerplate)

### [Installation](https://packagist.org/packages/bmatovu/laravel-package-boilerplate)

Install via Composer package manager:

```bash
composer create-project --prefer-dist bmatovu/laravel-package-boilerplate my-package
```

### Step #1: Own the package

Update the `composer.json` file to match your credentials.

Update the namespaces to match those you've set via composer.

```bash
composer dump-autoload
```

### Step #2: Documentation

You need to download [sami](https://github.com/FriendsOfPHP/Sami) for document generation.

If you need auto document generation remotely, uncomment the documentation step in `travis.yml`.

And add a `Github token` for authorization.

```
curl -O http://get.sensiolabs.org/sami.phar
```

### Step #3: Code Style & Quality

We've added [Style CI](https://styleci.io) configurations with the Laravel present to get you starter.

Also added [Scrutinizer CI](https://scrutinizer-ci.com) configurations for code quality, test coverage inspection.

Locally, you can restort to [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer).

```
$ php-cs-fixer fix
```

### Step #4: Sharing the package

You may publish your package via [Packagist](#)

## Useful resource

- [Laravel Package Development](https://laravel.com/docs/master/packages)

## Testing

We've defaulted to [Orchestra's testbench](https://github.com/orchestral/testbench)
