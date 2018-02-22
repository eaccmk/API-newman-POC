# apiAutomationTest
Very simple API Automation test to verify details at given endpoint

README and believe me (my first API automation task...)

*** QA API Automation Assessment ***

============================ Prerequisites ============================

This test has ben ran on Windows OS (32 bit)

NodeJS (v8.9.4) Ref: https://nodejs.org/en/download/
Python (v2.7.9) Ref: https://www.python.org/downloads/release/python-279/

Appedn Environment variable on your system :
C:\Program Files\nodejs\
C:\Program Files\Python27\Lib

Install Newman using cmd: npm install -g newman

============================ Runing this test ============================

Note: To run this paramaterized test from command line (considering for CI/Jenkins run) use below command:

Open cmd prompt (windows)


Run for preview env: newman run apiAirwallex_Collection.json -d ApiTestData.csv -e preview_environment.json

- apiAirwallex_Collection.json : Postman API Collection file
- ApiTestData.csv : test data file (we can include as many as test cases we want)
- preview_environment.json : passing environemnt details through this file


As this 
I decided to use this assignment as an opportunity to learn something, and have a go with Postman Collections and Newman.

The test cases are all contained within the data.csv file; the columns ‘status’ and ‘response’ represent the expected values.

Please see bugs.doc for a list of all the issues I found.

At the moment I don’t think it’s very obvious how to match assertion errors in the command line output to the equivalent test cases in the data file, so would definitely want to improve on that (sorry).

In case you face issues running this basic tests you can message me or or raise a request via this readme file