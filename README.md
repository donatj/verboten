# Verboten

[![Latest Stable Version](https://poser.pugx.org/donatj/verboten/version)](https://packagist.org/packages/donatj/verboten)
[![License](https://poser.pugx.org/donatj/verboten/license)](https://packagist.org/packages/donatj/verboten)


Simple CI Tool That Forbids Files Matching Regexes

## Requirements

- **php**: >=5.4
- **symfony/polyfill-php80**: ^1.23

## Installing

Install the latest version with:

```bash
composer require --dev 'donatj/verboten'
```

## Usage

```bash
php vendor/bin/verboten '/overflow.*?:\s*scroll/' -- `find ~<folder> -name '*.scss'`
```