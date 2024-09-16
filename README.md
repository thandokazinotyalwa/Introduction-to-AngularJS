# Introduction-to-AngularJS
AngularJS is a JavaScript framework written in JavaScript. It can be added to an HTML page with a script </> tag.
AngularJS extends HTML attributes with Directives, and binds data to HTML with Expressions.
AngularJS is distributed as a JavaScript file, and can be added to a web page with a script tag

AngularJS Extends HTML
AngularJS extends HTML with ng-directives.
The ng-app directive defines an AngularJS application.
The ng-model directive binds the value of HTML controls (input, select, textarea) to application data.
The ng-bind directive binds application data to the HTML view.

Example :

AngularJS starts automatically when the web page has loaded.

The ng-app directive tells AngularJS that the <div> element is the "owner" of an AngularJS application.
The ng-model directive binds the value of the input field to the application variable name.
The ng-bind directive binds the content of the <p> element to the application variable name.

AngularJS Expressions

AngularJS expressions can be written inside double braces: {{ expression }}.
AngularJS expressions can also be written inside a directive: ng-bind="expression".
AngularJS will resolve the expression, and return the result exactly where the expression is written.
AngularJS expressions are much like JavaScript expressions: They can contain literals, operators, and variables.
Example {{ 5 + 5 }} or {{ firstName + " " + lastName }}

AngularJS Modules

An AngularJS module defines an application.
The module is a container for the different parts of an application.
The module is a container for the application controllers.
Controllers always belong to a module.

