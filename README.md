# twig driver integration for twig vendor

## Requirements

* CodeIgniter 2+
* [CodeIgniter Sparks](http://getsparks.org/)

## Setup

1. [Install Sparks](http://getsparks.org/install) if you haven't done so already.
2. Install the twig_driver spark (see [here](http://getsparks.org/get-sparks) if you don't know how).

## Info

twig_driver is a spark that allows you to integrate twig template engine into your project.

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

#### incluede:

	config-> autoload.php
	config-> twig.php
	libraries->Twig.php
	libraries->Extensions.php
	libraries/extensions->ci_twig_extensions.php
