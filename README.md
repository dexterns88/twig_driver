# twig driver integration for twig vendor

## Requirements

* CodeIgniter 2+
* [CodeIgniter Sparks](http://getsparks.org/)

## Setup

1. [Install Sparks](http://getsparks.org/install)
2. Install the twig_driver spark (see [here](http://getsparks.org/get-sparks) if you don't know how).
3. Get twig via composer and load to project [twig_composer](https://packagist.org/packages/twig/twig)

## Composer to CI

Load composer into your CI project [composer and ci](http://codesamplez.com/development/composer-with-codeigniter)


## Info

twig_driver is a spark that allows you to integrate twig template engine into your project.

## How to in

## Usage

call spark twig_driver into your project.

## $this->load->spark('twig_driver/x.x.x');


use:

 $data['print'] = $this->twig->render('template.twig', $data );
 Render have return value;

 or

 $this->twig->display('template.twig', $data );
 For display main template with data into page.


## twig_driver 1.

#### include:

	config-> autoload.php
	config-> twig.php
	libraries->Twig.php
	libraries->Extensions.php
	libraries/extensions->ci_twig_extensions.php
