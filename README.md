Download any number of images from Google image search.

- run as 

`python image_download.py <query> <number of images>`

where:

`<query>` is the the query to search for.

`<number of images>` min(`<number of images>`, total google results) will be downloaded.

All the images are downloaded from Google image search. These should be used for educational purposes only. Copyright is owned by the respective websites.

PREREQUISITES:
easy_install selenium

(brew install selenium-server-standalone)

pip install selenium, pyvirtualdisplay

**The Seven Basic Steps of Selenium Tests**
There are seven basic steps in creating a Selenium test script, which apply to any test case and any application under test (AUT):
1. Create a WebDriver instance.
2. Navigate to a Web page.
3. Locate an HTML element on the Web page.
4. Perform an action on an HTML element.
5. Anticipate the browser response to the action.
6. Run tests and record test results using a test framework.
7. Conclude the test.
