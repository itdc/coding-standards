ITDC Coding Standards
=======================

This repository includes the [ITDC](http://itdc.ge) coding standard definition for [PHP Codesniffer](https://github.com/squizlabs/PHP_CodeSniffer) along with a few other helpful resources.  The PHP_CodeSniffer standard will never be 100% accurate, but should be viewed as a strong set of guidelines while writing software for ITDC code.

See ITDC coding standards documentation at [http://itdc.github.io/coding-standards/](http://itdc.github.io/coding-standards/)

If you want to contribute and improve this documentation find the source files at [https://github.com/itdc/coding-standards/tree/gh-pages](https://github.com/itdc/coding-standards/tree/gh-pages)

## Requirements

* PHP 5.3+
* [PHP Codesniffer](https://github.com/squizlabs/PHP_CodeSniffer) 2.3+


## Installation

Installation is as easy as checking out the repository to the correct location within PHP_CodeSniffer's directory structure.

### Install PHP_CodeSniffer.

	composer global require "squizlabs/php_codesniffer=*"

### Install the ITDC standard.

	git clone https://github.com/itdc/coding-standards.git `pear config-get php_dir`/PHP/CodeSniffer/Standards/ITDC

## Running

You can use the installed ITDC standard like:

	phpcs --standard=ITDC code path/to/code

Alternatively if it isn't installed you can still reference it by path like:

	phpcs --standard=path/to/itdc/coding-standards path/to/code

## IDE autoformatters

There is further information on how to set up IDE auto formatters here:

	https://github.com/itdc/coding-standards/tree/master/IDE


## Credits


Created by [Avtandil Kikabidze][0] aka LONGMAN.

 [0]: mailto:akalongman@gmail.com