# Dump and die function

Very useful for var_dump - like debuggind. Inspired by old school Laravel function. 
It is particularly convenient to debug console applications, there is no unnecessary HTML code in your terminal.

# Requirements

PHP >=5.5.9. If your PHP version > 7.1, please use [^2.0 package version](https://github.com/maxbanton/dd/tree/master)

# Installation
Install latest version with command

```
composer require maxbanton/dd ^1.0
```

# Usage

```php
<?php
...
dd($arg1);
dd($arg1, $arg2);
...
```

