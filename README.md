# Hello World 

## Objectives

- Create a Controller
- Create an element for Controller binding
- Create a public $scope method
- Display the $scope value in the View

## Instructions

Update the Learn gem so that you're set up for all Angular tests. Run `gem update learn-test` in your command line. 

Setup the directory structure as follows:

- js/
  - app/
    - controllers/
  - angular.js
- index.html

You can find `index.html` and `angular.js` in this repo.

Create a new module in `js/app/app.js`, named `app`.

Create a controller named `MainController` inside `js/app/controllers/MainController.js` and attach it to a module named `app`. The function should take one parameter - `$scope`.

Don't forget to initiate our module `app` using `ng-app` on a HTML element - otherwise we won't see anything!

Initiate our controller `MainController` using `ng-controller` on a HTML element inside our previous one.
 
Inside `MainController`, assign some values to the `$scope` object. You could copy our previous example - create the properties `name`, `email` and `phone`.  

Now, we need to display these values inside our HTML. Using `{{ }}` (double curlys), display the values you created.

If you come across issues and don't see what you expect to see when you load index.html, it may be useful to open up your developer tools and click "console" to see if there are any (red) errors. The errors should show you the name of the file with errors and the line of code where the error takes place. For example:   MainController.js:5 Uncaught SyntaxError: Unexpected token ; tells us that on line 5 of MainController.js we have an extra semi-colon.
<p data-visibility='hidden'>View <a href='https://learn.co/lessons/angular-hello-world-lab'>Angular Hello World Lab</a> on Learn.co and start learning to code for free.</p>
