# HonestFoodCompany

Steps to configure:
1) Perform a maven build
2) Run the test in src/test/java -> com.qa.testSuites.ckMamacitaTestSuite -> validateCheckOut
3) Run as TestNG test
4) Check the mailable output for test output

Sample Output: 
P Navigating to https://clubkitchen.at/
P Cookies accepted
P Mamacita vendor chosen
P Address selection
P Address selection : SemperstraÃŸe 44, 1180 Wien, Austria
P Address selected and Confirmed
P Dish Selected : In den Einkaufswagen
P AddOn Selected : Knuspriger Halloumi
P Final Selection Submit
P Check out successful
P Closing driver instance

Project Deliverable:
1) Created a POM structure for test suites
2) Configured maven and TestNG
3) Getting inputs from properties and TestUtil (constants)
4) Easy to change the locators if its changed during builds
5) Assertion after every step and will stop executing if the condition is not met and also reporting for every step 
6) If given time, I will create common methods and increase the modularity. I can also create extension for .xlsx test data configuration using data provider
