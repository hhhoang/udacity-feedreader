# Using Jasmine to test Page Feed Reader

## Table of Contents

* [Project Overview](#projectoverview)
* [How To Run the Javascript Application](#how-to-run-the-javascript-application)
* [Test Suites Demo](#test-suites-demo)
* [Dependencies](#dependencies)
* [Contributing](#contributing)

# Project Overview

In this project as an Udacity-Learner I were given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where I come in.

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass. Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.



## How To run the Javascript Application
* Clone ```https://github.com/hhhoang/udacity-feedreader.git``` or download the ZIP file.
* Open up `index.html` on browser
* Wait abit for the page to  load new feeds
* Scroll down to the bottom to see the test spec
* If they are all green, they pass
* If they are red, they did not pass
* If you want to do further test, open `feedreader.js` to explore the Jasmin spec

## Test Suites Demo
Using Jasmine I have written a number of tests against a pre-existing application. These test the underlying business logic of the application as well as the event handling and DOM manipulation. All tests are independent on one another.

The page has an hamburger button/menu on the top left corner, which contains (for now) 4 feed channels. For each feed channel when chosen/clicked, the header will display the name of the channel and the content of the page will list some entries found in this channel.

<img src="/jasmine.png" alt="Testing specs with Jasmine" width="50%">

1. We want to make sure that the **RSS Feeds**

* have defined URL
* have defined name 
2. We want to make sure that the elements inside the **menu icon** is by default hidden and when it is clicked it changes accordingly. The menu displays itself when clicked and hides itself when clicked again.

3. The **initial entries** should display at least one entry in the feed container

4. When we change the feed channel the content should change 



# Dependencies
* jQuery
* Google Fonts
* Icomoon Icons
* Normalize.css
* Handlebars
* Google Feed Reader API 

# Contributing

This repository is using the starter code for Udacity students. If you have any improvements for the code, I am happy to accept the great pull request and merge to the project.
