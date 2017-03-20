# Localiser

Localiser is an extensible, featherweight PHP library for localisation of projects.

## Requirements

* PHP 5.3+

## Usage

### Installation

This is a [Composer](https://getcomposer.org) package.

Run `composer require andrewmontagne/localiser`

This package has no non-dev dependencies.

### Basic Use

```
TODO: Basic Example
```

### Documentation

See the [GitHub wiki](https://github.com/AndrewMontagne/localiser/wiki) for more comprehensive documentation.

## Development

### Standards

This project follows the [PSR-1](http://www.php-fig.org/psr/psr-1/) and [PSR-2](http://www.php-fig.org/psr/psr-2/) standards for code style. Unit test coverage below 80% counts as a failed build.

The intent of this project is to make it as lean and fast as possible.

### Dependencies

For development, this project uses [`phpunit/phpunit`](https://packagist.org/packages/phpunit/phpunit) for unit and integration testing, and [`friendsofphp/php-cs-fixer`](https://packagist.org/packages/friendsofphp/php-cs-fixer) for code style enforcement.

### Building

To execute a build, execute `make` in the project root. This will run all the quality checks and tests that Travis CI performs. 
