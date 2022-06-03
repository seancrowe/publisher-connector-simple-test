# publisher-connector-simple-test

This is a simple test for https://github.com/chili-publish/publisher-connector

This small tests exist because writing an automatic test for publisher-connector is difficult due to requiring access to CHILI publisher software which is both commericial and private.

Internally automated tests may be written, but for now, this what I use for manual testing.

This test covers:
* setProperty
* addListener
* getObject
* executeFunction
* setVariableIsLocked
* getPageSnapshot


You must have Node installed for this test to work.


## Instructions
Clone or download this repo. `git clone https://github.com/seancrowe/publisher-connector-simple-test.git`

Update your CHILI server with the latest version of the wrapper.

Run `npm install`

Run `node test.js`

Open your browser to http://localhost:8080/
(If you need to use another port, you can modify the test.js file)

Fill in the input values on the page
(If you want to use a local JS file, you should add it to the project folder and you can reference it relatively with ./)

Press Launch Test. 
(If all test succeeds you will get an alert. You will see test results at the top of the page)



