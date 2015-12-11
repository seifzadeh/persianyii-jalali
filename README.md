jalali callendar for yii2
=========================
jalali callendar for yii2

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist persianyii/jalali "dev-master"
```

or add

```
"persianyii/jalali": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \persianyii\jalali::jdate('Y/m/d H:i',time()) ?>```
