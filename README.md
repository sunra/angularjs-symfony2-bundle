AngularJS and set of usefull thirdparty libs
===============================================

Symfony2 bundled & composer packaged

https://github.com/sunra/angularjs-symfony2-bundle


Contents
--------
AngularJS 
- 1.2.0-rc.3

Thirdparty
-------
- bindonce  v0.2.1  https://github.com/Pasvaz/bindonce



Installation
------------

1. Add to composer.json into "require" section
```
"sunra/angularjs-symfony2-bundle": "dev-master"
```
and run 
```
composer.phar update
```

1. Add to app/AppKernel.php
```
new Sunra\AngularBundle\SunraAngularBundle()
```

2. run :
```
app/console assets:install
```


Usage
-----
```

<script src="{{ asset('bundles/sunrajqueryset/js/jquery/jquery-1.9.1.min.js') }}"></script>
<script src="{{ asset('bundles/sunrajqueryset/js/jquery/jquery-migrate-1.1.0.min.js') }}"></script>

<script src="{{ asset('bundles/sunrajqueryset/js/jquery-plugin/jQueryTimers/jquery.timers.js') }}"></script>

<link href="{{ asset('bundles/sunrajqueryset/js/jquery-plugin/jQuery-Tags-Input/jquery.tagsinput.css') }}" rel="stylesheet">
<script src="{{ asset('bundles/sunrajqueryset/js/jquery-plugin/jQuery-Tags-Input/jquery.tagsinput.min.js') }}"></script>

<script src="{{ asset('bundles/sunrajqueryset/js/jquery-plugin/jqBootstrapValidation/jqBootstrapValidation-1.3.6.min.js') }}"></script>
```