# PostEase Classic SDK "PecRpc" for PHP

[![Latest Stable Version](http://img.shields.io/badge/Latest%20Stable-1.1-blue.svg)](https://packagist.org/packages/postease-classic/pec)

PHP SDK that allows you to access the PostEase Classic located remotely from your PHP app.
This PHP SDK "PecRpc" is technically based on XML-RPC.

## Installation

The PostEase Classic PHP SDK can be installed with [Composer](https://getcomposer.org/). Run this command:

```sh
composer require postease-classic/sdk-rpc
```

Or simply download the component from this page and unzip it. <br>
Upload the **PecRpc** directly below the src to the appropriate location manually.

## Usage

> **Note:** PostEase Classic SDK for PHP requires PHP 5.1 or greater.

Simple example to get all posts.

#### when use composer

```php
require_once __DIR__ . '/vendor/autoload.php'; // change path as needed

$pe = new \PecRpc\Pec();

$posts = $pe->get_posts();

print_r($posts);

```


#### when upload manyally

```php


/* 
 * If you set your environment like this for example..
 *
 * root
 *  |
 *  |-- PecRpc
 *  |
 *  |-- index.php
 *
 */
 
require_once __DIR__ . '/PecRpc/Pec.php'; // change path as needed

$pe = new Pec();

$posts = $pe->get_posts();

print_r($posts);

```



## Documentation
Complete documentation, installation instructions, and examples are available [here](https://classic.postease.org).


