# TimeZone

[![Latest Version on Packagist][ico-version]][link-packagist]

Get time and timezone at specific coordinates. 

## Installation

Via Composer

``` bash
$ composer require alongal/timezone
```

## Usage
```php
TimeZone::createFromCoordinates(-38.1081, 145.306)->getTimezone()
```
```php
Example Result: Australia/Melbourne
```

<br>

```php
TimeZone::createFromCoordinates(-38.1081, 145.306)->getTime()
```
```php
Example Result: 2000-02-01 10:00:00
```

## Testing

``` bash
$ composer test
```

## Security

If you discover any security related issues, please email author email instead of using the issue tracker.

## Credits

- Alon Gal

## License

license: MIT
