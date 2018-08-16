# Dump and die function

Very useful for var_dump - like debuggind. Inspired by old school Laravel function. 
It is particularly convenient to debug console applications, there is no unnecessary HTML code in your terminal.

# Requrements

PHP >= 7.1. If you still use PHP 5.5, please use [^1.0 package version](https://github.com/maxbanton/dd/tree/legacy)

# Installation
Install latest version with command

```
composer require maxbanton/dd ^2.0
```

# Usage

```php
<?php
...
dd($arg1);
dd($arg1, $arg2);
...
```
