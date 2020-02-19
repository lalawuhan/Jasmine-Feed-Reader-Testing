# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development." This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

## Project Overview

In this project I was given a pre-existing application that reads RSS feeds. I had to write a test suits using Jasmine.


## Run the Application

In order to run the application you can:
* Download as .zip file, or
*Clone or fork this project:

`$ git clone https://github.com/stearruda/fend-feed-reader-testing.git`

After that, open the index.html and check the test results.

## Project Requirements / Features

1. The first test suite about the RSS feeds definitions contains a related set of tests.
  * Write a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
  * Write a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
2. Second test suite "The menu" tests menu functionality.
  * Write a test that ensures the menu element is hidden by default.
  * Write a test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
3. The third test suite "Initial Entries" ensures that when the loadFeed function is called and completes its work. Because loadFeed function is asynchronous, this test requires the use of Jasmine's beforeEach and asynchronous done() function.
  * Write a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
4.  The fourth test suite "New Feed Selection" ensures that each feed is different.
  * Write a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
5. Other requirements
  * No test should be dependent on the results of another.
  * Callbacks should be used to ensure that feeds are loaded before they are tested.
  * Implement error handling for undefined variables and out-of-bound array access.
  * When complete - all of the tests should pass.


## Code Dependencies
* [Project Feed Reader Testing - Starter Code](https://github.com/udacity/frontend-nanodegree-feedreader)
* [Google's JavaScript Loader API](https://www.google.com/jsapi)
* [Jasmine](https://jasmine.github.io/)
* Icon: [Icomoon](https://icomoon.io/)
* Fonts: [Google Fonts](https://fonts.google.com/)
* [jQuery](https://jquery.com/)
* [Normalize.css](https://necolas.github.io/normalize.css/)
* [Handlebars](https://handlebarsjs.com/)
