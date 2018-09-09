# Custom PHPCS ruleset

This is a standalone composer package for Custom [WPCS](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards) ruleset.

## Requirements

* PHP 5.6+ (preferably 7+).
* [Composer](https://getcomposer.org/) for managing PHP dependencies.

## Installation

Open your command line tool and change directories to your WordPress theme folder.

```bash
cd path/to/wp-content/themes/<your-theme-name>
```

Then, use Composer to install the package.

```bash
composer require --dev samikeijonen/phpcs-composer:dev-master
```

## Usage

Lint your PHP files with the following command:

```bash
$ ./vendor/bin/phpcs .
```
