# Dmoney_Load_test_byFarzana

## Technology and tool used
- JMeter

## Scenario of this project
- Created a jmx file from Dmoney api collection (https://www.getpostman.com/collections/a8f908e0ee1d77cb6f85)
- Created all the requests and assert every response
- Generated load test report 
- Generated jmeter html dashboard report for this load test result

## How to run this project
- Clone this project
- Import the jmx file into jmeter folder directory
- Start jmeter
- Open the sample jmx file
- Adjust thread properties according to your need
- Start load test and observe report
- To generate jmeter html dashboard report do the following
    1) Open cmd and navigate to bin folder
    2) For Windows, run the command
       jmeter -n -t path/test_name -l path/file_name.csv -e -o path/file_name
## Prerequisites
*** You must have installed java to your system ***

## Output
![Dmoney_Load_test_report](https://user-images.githubusercontent.com/47137266/193413757-843cd6fb-f099-4483-905d-21a2478a496e.png)
