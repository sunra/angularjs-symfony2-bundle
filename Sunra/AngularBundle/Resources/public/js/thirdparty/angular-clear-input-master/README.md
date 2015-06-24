Angular Clear Input
===================

A simple AngularJS plugin that adds a clear button to input boxes

## Installation
1. Download and import the plugin script.<br />
`<script type="text/javascript" src="lib/angular-clear-input/angular.dcb-clear-input.min.js"></script>`
2. Add `dcbClearInput` to your angular app module dependencies list.<br />
`angular.module('myAngularApp', ['dcbClearInput']);`
3. Add the `clear-input` attribute to yout input<br />
`<input type="text" ng-model="myModel" clear-input />`


## Usage
- Simple usage:<br />
`<input type="text" ng-model="myModel" clear-input />`

- Using on a textarea:<br />
`<textarea ng-model="myModel" clear-input></textarea>`

- Expression:<br />
`<input type="text" ng-model="myModel" clear-input="myModel = 'newVal'" />`

- Function Call:<br />
`<input type="text" ng-model="myModel" clear-input="doSomething()" />`


## Advanced options
- Add a class to the appended button, Defaults to: 'clear-btn'.<br />
`<input type="text" ng-model="myModel" clear-input clear-btn-class="custom-class" />`

- Replace the button HTML markup with a custom one, Defaults to: '<span>X</span>'.<br />
`<input type="text" ng-model="myModel" clear-input clear-btn-markup="<img src='clear.png' />" />`

- Prevant the automatic toggling of the css visibilty property for the clear button<br />
`<input type="text" ng-model="myModel" clear-input clear-disable-visibility="true" />`
