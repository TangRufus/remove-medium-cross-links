# Remove Medium Cross Links

[![WordPress plugin](https://img.shields.io/wordpress/plugin/v/remove-medium-cross-links.svg)](https://wordpress.org/plugins/remove-medium-cross-links/)
[![WordPress](https://img.shields.io/wordpress/plugin/dt/remove-medium-cross-links.svg)](https://wordpress.org/plugins/remove-medium-cross-links/)
[![WordPress rating](https://img.shields.io/wordpress/plugin/r/remove-medium-cross-links.svg)](https://wordpress.org/plugins/remove-medium-cross-links/)
[![WordPress](https://img.shields.io/wordpress/v/remove-medium-cross-links.svg)](https://wordpress.org/plugins/remove-medium-cross-links/)
[![Build Status](https://travis-ci.org/TypistTech/remove-medium-cross-links.svg?branch=master)](https://travis-ci.org/TypistTech/remove-medium-cross-links)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/TypistTech/remove-medium-cross-links/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/TypistTech/remove-medium-cross-links/?branch=master)
[![PHP Versions Tested](http://php-eye.com/badge/typisttech/remove-medium-cross-links/tested.svg)](https://travis-ci.org/TypistTech/remove-medium-cross-links)
[![StyleCI](https://styleci.io/repos/77471719/shield?branch=master)](https://styleci.io/repos/77471719)
[![License](https://poser.pugx.org/typisttech/remove-medium-cross-links/license)](https://packagist.org/packages/typisttech/remove-medium-cross-links)
[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://typist.tech/donate/remove-medium-cross-links/)
[![Hire Typist Tech](https://img.shields.io/badge/Hire-Typist%20Tech-ff69b4.svg)](https://typist.tech/contact/)

Remove Medium cross links footer from WordPress posts.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Installation Instructions](#installation-instructions)
  - [Via Manually Upload](#via-manually-upload)
  - [Via WP CLI](#via-wp-cli)
- [Developing](#developing)
- [Build from Source](#build-from-source)
- [Branches](#branches)
  - [Master](#master)
  - [Nightly](#nightly)
- [Support!](#support)
  - [Donate via PayPal *](#donate-via-paypal-)
  - [Why don't you hire me?](#why-dont-you-hire-me)
  - [Want to help in other way? Want to be a sponsor?](#want-to-help-in-other-way-want-to-be-a-sponsor)
- [Running the Tests](#running-the-tests)
- [Feedback](#feedback)
- [Change log](#change-log)
- [Security](#security)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

This repository is a development version of [Remove Medium Cross Links](https://wordpress.org/plugins/remove-medium-cross-links/) intended to facilitate communication with developers. It is not stable and not intended for installation on production sites.

Bug reports and pull requests are welcome.

If you are not a developer or you'd like to receive the stable release version and automatic updates, install it via [WordPress.org](https://wordpress.org/plugins/remove-medium-cross-links/) instead.



## Installation Instructions

If you are not a developer or you'd like to receive the stable release version and automatic updates, install it via [WordPress.org](https://wordpress.org/plugins/remove-medium-cross-links/) instead.



The `master` branch is not installable. Use the `nightly` branch instead. See [branches](#branches).

### Via Manually Upload

1. Download the built archive from [nightly branch](https://github.com/TypistTech/remove-medium-cross-links/archive/nightly.zip)

2. Unzip it

3. Upload it to `wp-content/plugins/`

4. Go to the WordPress plugin menu and activate it



### Via WP CLI

1. `$ wp plugin install https://github.com/TypistTech/remove-medium-cross-links/archive/nightly.zip --activate`




## Developing

Before start hacking, you need `composer ` and `yarn` installed. See:

- [getcomposer.org](https://getcomposer.org/doc/00-intro.md)
- [yarnpkg.com](https://yarnpkg.com/en/docs/install)



To setup a developer workable version you should run these commands:

```bash
$ composer create-project --keep-vcs --no-install typisttech/remove-medium-cross-links:dev-master
$ cd remove-medium-cross-links
$ composer install
```



## Build from Source

This command build the plugin into `release/remove-medium-cross-links.zip`.

```bash
$ composer build
```

Note: You need both `composer ` and `yarn` installed.




## Branches

### Master

The `master` branch is the main branch where the source code of `HEAD` always reflects a state with the latest delivered development changes for the next release. This is where the `nightly` branch is built from. Since we built this plugin with `composer` and `grunt`, this branch is not installable.

### Nightly

The `nightly` branch is built by TravisCI whenever the `master` branch is updated. Anything in the `nightly` branch is installable. See [installation instructions](#installation-instructions).



## Support!

### Donate via PayPal [![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://typist.tech/donate/remove-medium-cross-links/)

Love Remove Medium Cross Links? Help me maintain Remove Medium Cross Links, a [donation here](https://typist.tech/donate/remove-medium-cross-links/) can help with it.

### Why don't you hire me?

Ready to take freelance WordPress jobs. Contact me via the contact form [here](https://typist.tech/contact/) or, via email [info@typist.tech](mailto:info@typist.tech)

### Want to help in other way? Want to be a sponsor?

Contact: [Tang Rufus](mailto:tangrufus@gmail.com)



## Running the Tests

[Remove Medium Cross Links](https://github.com/TypistTech/remove-medium-cross-links) run tests on [Codeception](http://codeception.com/) and relies [wp-browser](https://github.com/lucatume/wp-browser) to provide WordPress integration.
Before testing, you have to install WordPress locally and add a [codeception.yml](http://codeception.com/docs/reference/Configuration) file.

See [codeception.example.yml](codeception.example.yml) for a [Varying Vagrant Vagrants](https://varyingvagrantvagrants.org/) configuration example.

Actually run the tests:

``` bash
$ composer test
```

We also test all PHP files against [PSR-2: Coding Style Guide](http://www.php-fig.org/psr/psr-2/) and part of the [WordPress coding standard](https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards).

Check the code style with ``$ composer check-style``.



## Feedback

**Please provide feedback!** We want to make this library useful in as many projects as possible.
Please submit an [issue](https://github.com/TypistTech/remove-medium-cross-links/issues/new) and point out what you do and don't like, or fork the project and make suggestions.
**No issue is too small.**



## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.



## Security

If you discover any security related issues, please email remove-medium-cross-links@typist.tech instead of using the issue tracker.



## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) and [CONDUCT](.github/CONDUCT.md) for details.



## Credits

[Remove Medium Cross Links](https://github.com/TypistTech/remove-medium-cross-links) is a [Typist Tech](https://typist.tech) project and maintained by [Tang Rufus](https://twitter.com/Tangrufus), freelance developer for [hire](https://typist.tech/contact/).

Full list of contributors can be found [here](https://github.com/TypistTech/remove-medium-cross-links/graphs/contributors).



## License

[Remove Medium Cross Links](https://wordpress.org/plugins/remove-medium-cross-links/) is licensed under the GPLv2 (or later) from the [Free Software Foundation](http://www.fsf.org/).
Please see [License File](./LICENSE) for more information.
