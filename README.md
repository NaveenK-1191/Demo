# Checkoutflow test with credit card payment method
## For Browser invokation one Base Class is implemented, whatever Test cases are there, they will inherit this Base class to invoke the browser as per the requirement
 * Base.java
 
## For Global Variables declaration one properties file is implemented
 * globalVariables.properties
 
 global variables like Browser, URL, Username & Password can be provided as key-value pair in this properties file
## Totally we've to work on 3 WebPages for that i implemented PageObjectModel with 3 Page classes
 * AddressPage.java
 * LandingPage.java
 * OrderConfirmationPage.java
 
 Whatever the objects we are going to work with and methods for that objects are built in these pages
 ## "CheckOutFlowTest" is our actual TestClass which has our test steps
 * CheckOutFlowTest.java
 
 Here,the Test is built in such a way that Test will be executed with two sets of Test data with DataProvider concept
 ## Implemented pom.xml and testng.xml as per the requirement
 ## Test Results
 For Test results we will access the "index.html" file in "test-output" directory of the project 
 
 
