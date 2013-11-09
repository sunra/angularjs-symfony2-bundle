AngularJS and set of usefull thirdparty libs
===============================================

Symfony2 bundled & composer packaged

https://github.com/sunra/angularjs-symfony2-bundle


Contents
--------
AngularJS 
- 1.2.0

Thirdparty
-------
- bindonce              v0.2.1  https://github.com/Pasvaz/bindonce
- angular-local-storage master  https://github.com/grevory/angular-local-storage


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
 <script src="{{ asset('bundles/sunraangular/js/angular/angular-1.2.0/angular.min.js') }}"></script> 
 <script src="{{ asset('bundles/sunraangular/js/thirdparty/bindonce/bindonce.js') }}"></script>
 <script src="{{ asset('bundles/sunraangular/js/thirdparty/angular-local-storage/angular-local-storage.js') }}"></script>






```