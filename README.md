lms
===
Logos Management System

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist revasion/yii2-lms "*"
```

or add

```
"revasion/yii2-lms": "*"
```

to the require section of your `composer.json` file.

Configuration
-----

1) In your config/web.php

 'modules' => [
        ...
    'lms' => [
            'class' => 'revasion\lms\Lms',
        ],
        ....
  ]

Usage
-----

Once the extension is installed, simply use it in your code by  :

```php


