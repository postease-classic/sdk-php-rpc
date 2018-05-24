# PostEase Classic SDK for PHP RPC (v1)

[![Latest Stable Version](http://img.shields.io/badge/Latest%20Stable-1.1-blue.svg)](https://packagist.org/packages/postease-classic/pec)

This repository contains the open source PHP SDK that allows you to access the PostEase Classic from your PHP app.

## Installation

The PostEase Classic PHP SDK can be installed with [Composer](https://getcomposer.org/). Run this command:

```sh
composer require postease-classic/sdk
```



## Usage

> **Note:** PostEase Classic SDK for PHP requires PHP 5.1 or greater.

Simple example to get all posts.

```php
require_once __DIR__ . '/vendor/autoload.php'; // change path as needed

$pe = new \Pec\Pec();

$posts = $pe->get_posts();

print_r($posts);

```


## Documentation
Complete documentation, installation instructions, and examples are available [here](https://classic.postease.org).


