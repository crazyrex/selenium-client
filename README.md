# PHP Selenium client

[![Latest Version on Packagist](https://img.shields.io/packagist/v/spatie/selenium-client.svg?style=flat-square)](https://packagist.org/packages/spatie/selenium-client)
[![Build Status](https://img.shields.io/travis/spatie/selenium-client/master.svg?style=flat-square)](https://travis-ci.org/spatie/selenium-client)
[![Quality Score](https://img.shields.io/scrutinizer/g/spatie/selenium-client.svg?style=flat-square)](https://scrutinizer-ci.com/g/spatie/selenium-client)
[![Total Downloads](https://img.shields.io/packagist/dt/spatie/selenium-client.svg?style=flat-square)](https://packagist.org/packages/spatie/selenium-client)

Selenium is a great tool for testing. 
This package gives you a boilerplate setup to automate for example testing a legacy form.

## Installation

```bash
git clone git@github.com:spatie/selenium-client.git
```

## Usage

You can add your own scenarios in the `Scenarios` folder. 

Next, you'll need to start the Selenium server like so:

```bash
php client.php serve
```

Next you can run your scenarios like so:

```bash
php client.php execute dummy [--wait]
```

### Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email freek@spatie.be instead of using the issue tracker.

## Postcardware

You're free to use this package, but if it makes it to your production environment we highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using.

Our address is: Spatie, Samberstraat 69D, 2060 Antwerp, Belgium.

We publish all received postcards [on our company website](https://spatie.be/en/opensource/postcards).

## Credits

- [Brent Roose](https://github.com/brendt)
- [All Contributors](../../contributors)

## Support us

Spatie is a webdesign agency based in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

Does your business depend on our contributions? Reach out and support us on [Patreon](https://www.patreon.com/spatie). 
All pledges will be dedicated to allocating workforce on maintenance and new awesome stuff.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
