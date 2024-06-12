
# Project Title: Performance Testing of COVID-19 Global Statistics API

## Project Summary : 
This project focuses on performance testing of the COVID-19 Global Statistics API from disease.sh. The objective is to evaluate the API's response time, stability, and reliability under various load conditions. The tests are designed to simulate multiple scenarios, such as high traffic and sustained usage, to ensure the API can handle real-world demands.

## Prerequisites
- Java (Latest version)
- Apache JMeter (Latest version)

## How to Run Performance Tests?
###Execute the following commands:
- ```Step 1: Install JMeter
Download Apache JMeter from the official website.
Unzip the downloaded file to a preferred location on your system.
Add the JMeter bin directory to your system's PATH environment variable.  ```
- ```Step 2: Setup JMeter
Open the JMeter GUI by running the jmeter.bat (Windows) or jmeter.sh (Unix) script from the bin directory.```
- ```Step 3: Create a JMeter Test Plan
Add a Thread Group:
Right-click on the Test Plan and select Add > Threads (Users) > Thread Group.
Configure the number of threads (users), ramp-up period, and loop count as required.
Add an HTTP Request:

Right-click on the Thread Group and select Add > Sampler > HTTP Request.
Set the server name or IP to disease.sh and the path to /v3/covid-19/all.
Choose the HTTP method as GET.
Add Listeners:

Right-click on the Thread Group and select Add > Listener > View Results Tree.
Add other listeners like Summary Report, Aggregate Report, and Graph Results for detailed analysis.
Save the Test Plan:
Save the test plan to a preferred location.```
- ```Step 4: Run the Test Plan
Load the test plan in JMeter.
Click the green Start button to begin the test.
Monitor the results using the listeners added.``` 
- ```Step 5: Analyze the Results
Review the data in the listeners to analyze the API's performance.```



## Documentation:
https://documenter.getpostman.com/view/35122212/2sA3QwapS7

## Excel Files for Test Case and Bug Report

You can download the Excel files from the following links:
- [StandardTestCase.xlsx](https://docs.google.com/spreadsheets/d/1mdeZUak9MBJQspSHeXJPq9vIo4lyfQFn/edit?usp=sharing&ouid=106900521374584856661&rtpof=true&sd=true)
- [Bug-Report.xlsx](https://docs.google.com/spreadsheets/d/1OCxu2rrFV9g8ckNuLonuKW0Doz8oeF2d/edit?usp=sharing&ouid=106900521374584856661&rtpof=true&sd=true)


## Outputs:
![Screenshot (724)](https://github.com/ShuhanaRiya09/repo_for_demoney/assets/108625095/a5fa52d6-5a6b-47f1-8d5c-8189cf51bd9c)
