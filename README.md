looking-glass code challange
automationpractice.com is an end-end e-commerce website. It covers the complete online shopping workflow.

Tools and Language Utilized:


• Selenium Web Driver

• Java

• TestNG

• Maven

• Allure Reporting Framework

Tested Functionalities via Automated Scripts:


• Logged in as an existing account that was previously created

• Click on 'Dresses' tab

• Click on 'List' to 'List View' all 5 dresses

• Add all dresses in shopping cart

• Click on shopping cart icon

• In Cart Summary Page - Verify all 5 dresses are listed, total price of each dress is correct and and total product price is the sum of the total price of each dress

NOTES:

Test can be run using testng.xml as testNG suite
Test can be run using Chrome, Firefox, Headless which can be configured in testng.xml

Error: (If you encounter this below error after cloning the project in local, please check the solution provided also below)

Error running '/Users/nafismac/Downloads/lgautomation/testng.xml': Cannot start process, the working directory 'C:\MyDevelopments\LG-Shafi-001\%MODULE_WORKING_DIR%' does not exist

Solution : click Run option from the menu and select edit configuration then update working directory and add $MODULE_DIR$.Click Apply and Ok button
