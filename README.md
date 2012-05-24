# Plist

A Plist parser for PHP.


## Requirements
### Required
The following software is **required** for Plist to run:

* [PHP](http://php.net) 5.3.2+

## Examples

{Fill-in: Example usage of this code.}


## Installation
Depending on your needs, there are a few different ways you can install Plist:

### Bundle with Composer
To add Plist as a [Composer](https://github.com/composer/composer) dependency in your `composer.json` file:

	{
		"require": {
			"skyzyx/plist": ">=1.0"
		}
	}

### Install source from GitHub
To install the source code for Plist:

	git clone git://github.com/skyzyx/plist.git

And include it in your scripts:

	require_once '/path/to/plist/src/Plist.php';

### Install source from zip/tarball
Alternatively, you can fetch a [tarball](https://github.com/skyzyx/plist/tarball/master) or [zipball](https://github.com/skyzyx/plist/zipball/master):

    $ curl https://github.com/skyzyx/plist/tarball/master | tar xzv
    (or)
    $ wget https://github.com/skyzyx/plist/tarball/master -O - | tar xzv

And include it in your scripts:

	require_once '/path/to/plist/src/Plist.php';

### Using a Class Loader
If you're using a class loader (e.g., [Symfony Class Loader](https://github.com/symfony/ClassLoader)) for [PSR-0](https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md)-style class loading:

	$loader->registerNamespace('Skyzyx\\Components\\Plist', 'path/to/vendor/skyzyx/plist/src');


## Contributing
To view the list of existing [contributors](/skyzyx/plist/contributors), run the following command from the Terminal:

	git shortlog -sne --no-merges

### How?
Here's the process for contributing:

1. Fork Plist to your GitHub account.
2. Clone your GitHub copy of the repository into your local workspace.
3. Write code, fix bugs, and add tests with 100% code coverage.
4. Commit your changes to your local workspace and push them up to your GitHub copy.
5. You submit a GitHub pull request with a description of what the change is.
6. The contribution is reviewed. Maybe there will be some banter back-and-forth in the comments.
7. If all goes well, your pull request will be accepted and your changes are merged in.
8. You will become "Internet famous" with anybody who runs `git shortlog` from the Terminal. :)

To simplify many aspects of development, we also have a `build.xml` for Phing. The easiest way to install Phing and any other dependencies is to install [Phix](http://phix-project.org/#install).


## Authors, Copyright & Licensing

* Copyright (c) 2008-2009 [Jeremy Johnstone](https://github.com/jsjohnst).
* Copyright (c) 2009 [Jonty Wareing](https://github.com/Jonty).
* Copyright (c) 2012 [Ryan Parman](http://ryanparman.com).

See also the list of [contributors](/skyzyx/plist/contributors) who participated in this project.

Licensed for use under the terms of the [MIT license](http://www.opensource.org/licenses/mit-license.php).
