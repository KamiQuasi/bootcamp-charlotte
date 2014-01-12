Library Fundamentals and Notes
===============================

Core Module (angular.js)
-------------------------

* [Directives](http://docs.angularjs.org/api/ng#directive)
    
    * *[Normalization](http://docs.angularjs.org/guide/directive#creating-custom-directives_matching-directives)*
        
        1. Strip `x-` and `data-` from element/attributes
        2. Convert `:`,`-`, or `_` delimited name to `camelCase`
        3. Prefer _tag name_ or _attribute_
        
    * Notable Tags: a, form, input, select, textarea
    * Notable Attributes: ng-app, ng-bind, ng-change, ng-class(-even/-odd), 
        ng-click, ng-cloak, ng-controller, ng-hide, ng-href, ng-include, ng-init, 
        ng-model, ng-repeat, ng-selected, ng-show, ng-transclude, ng-value
        
* [Services/Factories](http://docs.angularjs.org/api/ng#service)

    * Notable: $animate, $compile, $filter, $http, $routeParams, $location, $rootScope, $templateCache
    
* [Filters](http://docs.angularjs.org/api/ng#filter)

    * Notable (angular object): .forEach, .is(Array, Date, Defined, Number), .module, .toJson
    * Notable (ng object): $controller, $filter, $http, limitTo, orderBy

* [Global APIs](http://docs.angularjs.org/api/ng#function)


Additional Modules
-------------------

* [ngRoute](http://docs.angularjs.org/api/ngRoute) (angular-route.js)
    
    * $routeParams
    * $route
    * $routeProvider
    * ng-view

* [ngResource](http://docs.angularjs.org/api/ngResource) (angular-resource.js)

    * $resource

* [ngAnimate](http://docs.angularjs.org/api/ngAnimate) (angular-animate.js)

    * $animate
    * CSS animations
    * JS animations

* [ngTouch](http://docs.angularjs.org/api/ngTouch) (angular-touch.js)
* [ngSanitize](http://docs.angularjs.org/api/ngSanitize) (angular-sanitize.js)
* [ngMock](http://docs.angularjs.org/api/ngMock) (angular-mocks.js)