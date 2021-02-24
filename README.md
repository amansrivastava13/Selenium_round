# Selenium_round

Problem Statement:
We have to run two tests simultaneously using selenium.
TEST-1
1. Open https://www.amazon.in/ and search for lg washing machine
2. Use filter to get result only for lg brand
3. read name,price and print that value in descending order (do not use sort filter for price)
4. read and print output in console/file
TEST-2
1. Open https://www.amazon.in/ and search for samsung washing machine
2. Use filter to get result only for samsung brand
3. read name,price and print that value in descending order (do not use sort filter for price)
4. read and print output in console/file


HOW TO ACCESS THE CODE:
1. Create a new project in eclipse
2. Create a package in the project
3. Create a java class in that package
4. In above made java class copy and paste the code that we have commit in this repository
5. If TestNG plugin is not installed in your eclipse then first installed it.
6. To install TestNG, Go to help-> Eclipse Marketplace-> Install TestNG
7. Now add Referenced Libraries in your project
8. For installing referenced libraries, Right click on your project name-> Build path-> configure build path-> add external libraries-> add library selenium-server-standalone-3.141.59.jar file
9. Make a .xml file
10.Copy and paste the code having filename testng.xml

To run this project
Go to testng.xml file-> Right click on it-> Run as-> TestNg Suite
