# Rob Interviewing Kuban (11/14/2022)

## 1: Describe an Angular component and its three main parts.
- a part of a webpage, not sidebar or specific card
- Created in angular via GUI or ng command
- contains 4 files, app.html, app.css, 2 .ts files (one of them spec)
- *Corrections*: components are building blocks of angular apps;  three parts: html template, css selector, & typescript class

## 2: What are some Angular directives?
- structural: add/remove thigns from dom
- attribute: manipulating the dom
- *Corrections*: the three are component, structural, attribute; 
- Component directives alter the details of how the component should be processed, instantiated, and used at runtime.
- Structural directives are used to manipulate and change the structure of the DOM elements. (ngIf, ngFor, ngSwitch)
- Attribute directives are used to change the look and behavior of the DOM elements. (ngClass, ngStyle)

## 3: What is external css and how can you make use of it?
- creating new file (.css) used for style sheet
- go to header of doc, link with ref href to css file
- *Addition*:  <head><link rel="stylesheet" href="mystyle.css"></head>

## 4: How would you compose a CSS style rule which applies to multiple element types? 
- several ways
- easiest is use id tag (# + name of id); in curly brackets, you can enter attributes you want element to have
- *Corrections*: grouping: h1,h2 {...} 

## 5: What are template literals and how can they be used?
- allow you to insert things like ngmodel or allow for 2way binding
- also 1way binding
- *Corrections*: template literals provide an easy way to create multiline strings and perform string interpolation; they are made with back ticks 


## 6: What are promises?
- used to achieve asynchronous functions
- you basically call a function, it's not multithreaded but waits for results to come back and inserts it
- you can only get back one thing (as compared to observables)
- *Corrections*:

## 7: What are HTML forms used for, and what are some of their primary attributes?
- forms used mainly to gather input from user, e.g. user creation, filling out a form
- from frontend to backend, some event specified will happen
- *Corrections*: some attributes are action, target, and method
- The action attribute indicates where the form data will be processed. Typically the value is a URL of a server. 
- The target attribute is used to specify whether the submitted result will open in the current window, a new tab or on a new frame. The default value used is "self" which results in the form submission in the same window. To make the result display in a new browser tab, the value should be set to "blank".
- The method attribute is used to specify the HTTP method used to send data while submitting the form. There are only two options available: GET and POST.

## 8: What are the two types of HTML5 validation?
- required, make sure that it's not empty- 
- *Corrections*: 
- Built-in form validation - It uses HTML5 form validation features.
- JavaScript validation - It is coded using JavaScript. This validation is completely customizable.


## 9: What are the datatypes in Typescript?
- bigint, any, object, boolean, null, number, array
- *Additions*: - string, undefined, void, tuples, enum, never

## 10: What are var, let, and const?
- you declare var within globally or in functions (not block scope)
- all allow to assign values
- let can be used anywhere, usually within block scope
- const (also in block scope) is used to assign an unchangeable value
- *Corrections*: 







