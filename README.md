AngularJS and set of usefull thirdparty libs
===============================================

Symfony2 bundled & in composer packaged

https://github.com/sunra/angularjs-symfony2-bundle


Contents
--------
jQuery 1.8.3, 1.9.0, 1.9.1, 2.0.2, 1.10.1
jQuery Migrate 1.1.0, 1.2.1

Plugins
-------
- jQuery.Timers            n/a      http://jquery.offput.ca/timers/
- jQuery-Tags-Input        1.3.3    https://github.com/xoxco/jQuery-Tags-Input
- jqBootstrapValidation    1.3.6    https://github.com/ReactiveRaven/jqBootstrapValidation


Installation
------------

1. Add to composer.json into "require" section
```
"sunra/jquery-set-symfony2-bundle": "dev-master"
```
and run 
```
composer.phar update
```

1. Add to app/AppKernel.php
```
new Sunra\jQuerySetBundle\SunrajQuerySetBundle()
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