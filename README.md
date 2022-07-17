# Testing [nopCommerce demo store](https://demo.nopcommerce.com/)  

Selenium, TestNG, and Cucumber frameworks were used to test the demo site of the nopCommerce platform.  
The Selenium  WebDriver was used to automate and control the site's testing, using the Page Object Model (POM) design pattern.
TestNG was used as the testing framework, it was used for assertions, annotations, and report generation.  
The Cucumber framework was used with Gherkin for the writing of test cases with BDD (Behaviour-Driven Development) in mind and for documenting the test cases.  
The test cases were used to test and verify various features of the platform like creating an account, logging in, searching, and adding items to the wish list.

## Used Software:  
**Java version:**  
openjdk version "1.8.0_332"  

**IntelliJ IDEA version:**  
 2022.1.3 (Community Edition)  with the following plugins:  
    gherkin (221.5921.12)  
    cucumber-java (221.5921.16)  

**Maven: version**  
Apache Maven 3.8.6 with the following packages:  
selenium-java: 4.3.0  
cucumber-java: 7.3.4  
webdrivermanager: 5.2.1  
maven-surefire-plugin: 3.0.0-M7  
maven-cucumber-reporting: 5.7.0  
