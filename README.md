# Project Overview


 this project is a web-based application that reads RSS feeds.

 Testing is an important part of the development process and 
 many organizations practice a standard of development known as "test-driven development".
 This is when developers write tests first, before they ever start developing their application.
 All the tests initially fail and then they start writing application code to make these tests pass.


  Thats why Jasmine tests are included in this project.
 
   The tests that are included in this project are:
 

    1- a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.

    2- a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

    3- a new test suite named `"The menu"`.
    4- a test that ensures the menu element is hidden by default.

    5- a test that ensures the menu changes visibility when the menu icon is clicked. This test have two expectations:
       (the menu display when clicked and it hide when clicked again)
    6- a test suite named `"Initial Entries"`
    7- a test that ensures when the `loadFeed` function is called and completes its work.
    8- a test suite named `"New Feed Selection"`
    9- a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.



 To run this application successfully:

- each feed in the `allFeeds` object has a URL defined and is not empty as well as has a name defined
 and that the name is not empty.

- the menu element should be hidden by default.


-the menu changes visibility when the menu icon is clicked (toggle on and off).

-the `loadFeed` function is called and completes its work.

-the new feed is loaded by the `loadFeed` function and the content changes.

