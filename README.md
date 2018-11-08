


**Project overview:**

  _This project is a web-based application that reads RSS feeds. Jasmine tests are included in this project._

 
**To run this project locally**

    -Download or clone this repository and open in your favorite code editor
    -Run node -v on the terminal or command line. If nothing shows up or you get an error, Install Node.
    -Run npm install -g http-server
    -Then run http-server -o in the project directory



 
 **Tests that included in this project:**
 

    -Test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
    -Test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
    -New test suite named `"The menu"`.
    -Test that ensures the menu element is hidden by default.
    -Test that ensures the menu changes visibility when the menu icon is clicked. This test have two expectations:
       (the menu display when clicked and it hide when clicked again)
    -Test suite named `"Initial Entries"`
    -Test that ensures when the `loadFeed` function is called and completes its work.
    -Test suite named `"New Feed Selection"`
    -Test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

