# PHP-Dump-Die
Simple Laravel style dump and die (dd) command.

Usage:

Install via composer

```"composer require vajiral/php-dumpdie"```

In your PHP file

```php
<?php

require __DIR__ . "/vendor/autoload.php";

$dummyObject = new DummyObject();
dd($dummyObject);
```
