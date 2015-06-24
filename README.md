* Support discontinued!
* It is better to use it - https://github.com/francoispluchino/composer-asset-plugin

AngularJS and set of usefull thirdparty libs
===============================================

Symfony2 bundled & composer packaged

https://github.com/sunra/angularjs-symfony2-bundle


Contents
--------
AngularJS 
- 1.3.3 
- 1.3.2
- 1.2.27
- 1.2.26

Thirdparty
-------

|lib|ver|github|
|----|---|----|
| angular-local-storage              | master   | https://github.com/grevory/angular-local-storage      | 
| begriffs/angular-paginate-anything | master   | https://github.com/begriffs/angular-paginate-anything |  
| jirikavi/AngularJS-Toaster         | master   | https://github.com/jirikavi/AngularJS-Toaster         |
| angular-ui/bootstrap               | gh-pages | https://github.com/angular-ui/bootstrap/tree/gh-pages |
| Animate.css | | https://github.com/daneden/animate.css |

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
```html
 <script src="{{ asset('bundles/sunraangular/js/angular/angular-1.2.0/angular.min.js') }}"></script> 
 <script src="{{ asset('bundles/sunraangular/js/thirdparty/bindonce/bindonce.js') }}"></script>
 <script src="{{ asset('bundles/sunraangular/js/thirdparty/angular-local-storage/angular-local-storage.js') }}"></script>
 <script src="{{ asset('bundles/sunraangular/js/thirdparty/angular-ui/bootstrap/bootstrap-gh-pages/ui-bootstrap-0.11.0.min.js') }}"></script>

 




```
