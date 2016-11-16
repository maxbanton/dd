#Dump and die function

Very useful for var_dump - like debuggind. Inspired by old school Laravel function. 
It is particularly convenient to debug console applications, there is no unnecessary HTML code in your terminal.

#Installation
Install latest version with command

```
composer require maxbanton/dd
```

#Usage

```php
<?php
...
dd($arg1);
dd($arg1, $arg2);
...
```
