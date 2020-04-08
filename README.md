# Checkoutflow Test with Credit Card Payment Method
## Base Class
 * Base.java
 
 For Browser invokation one Base class is implemented, whatever test cases are there, they will inherit this Base class to invoke the browser as per the requirement
## properties File
 * globalVariables.properties
 
 For Global Variables declaration one properties file is implemented
 global variables like Browser, URL, Username & Password can be provided as key-value pair in this properties file
## PageObjectModel with Page Classes
 * AddressPage.java
 * LandingPage.java
 * OrderConfirmationPage.java
 
 Totally we've to work on 3 webpages for that pageobjectmodel with 3 Page classes is implemented
 Whatever the objects we are going to work with and methods for that objects are built in these pages
 ## TestCase
 * CheckOutFlowTest.java
 
 "CheckOutFlowTest" is our actual testclass which has our test steps
 Here,the test is built in such a way that test will be executed with two sets of Test data with dataprovider concept
 ## pom.xml & testng.xml
 pom.xml and testng.xml are implemented as per the requirement
 ## Test Results
 For test results we will access the "index.html" file in "test-output" directory of the project 
 
 
