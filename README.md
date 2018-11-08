


 ##Project overview:

  This project is a web-based application that reads RSS feeds.
  Testing is an important part of the development process and 
  many organizations practice a standard of development known as "test-driven development".
  This is when developers write tests first, before they ever start developing their application.
  All the tests initially fail and then they start writing application code to make these tests pass.

  Thats why Jasmine tests are included in this project.

 
 ##To run this project locally:

    -Download or clone this repository and open in your favorite code editor
    -Run node -v on the terminal or command line. If nothing shows up or you get an error, Install Node.
    -Run npm install -g http-server
    -Then run http-server -o in the project directory



 
 ##The tests that are included in this project are:
 

    - a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.

    - a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.

    - a new test suite named `"The menu"`.
    - a test that ensures the menu element is hidden by default.

    - a test that ensures the menu changes visibility when the menu icon is clicked. This test have two expectations:
       (the menu display when clicked and it hide when clicked again)
    - a test suite named `"Initial Entries"`
    - a test that ensures when the `loadFeed` function is called and completes its work.
    - a test suite named `"New Feed Selection"`
    - a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

