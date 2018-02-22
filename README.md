# # apiAutomationTest

_Very simple API Automation test to verify details at given endpoint_
 README and _believe me_ (my first API automation task...)

# QA - API Automation Assessment

*====================  -Before you start-  ====================*
This test has ben ran on Windows OS (32 bit)
* Download these files and install
[NodeJS (v8.9.4)](https://nodejs.org/en/download/)
[Python (v2.7.9)](https://www.python.org/downloads/release/python-279/)
* Install Newman using cmd: `npm install -g newman` with

Appedn Environment variable on your machine :
```sh
C:\Program Files\nodejs\
C:\Program Files\Python27\Lib
```

*====================  -Runing this test-  ====================*

**Note:** _To run this paramaterized test from command line (considering for CI/Jenkins run) use below command_

`newman run apiAirwallex_Collection.json -d ApiTestData.csv -e preview_environment.json
`

*====================  -File Details-  ====================*

Postman API Collection file: `apiAirwallex_Collection.json`  
Passing environemnt details through this file : `preview_environment.json`
Test data file (we can include as many as test cases we want) : `ApiTestData.csv`


**soft note:** _In case you face issues running this tests you can message me_

Click to view my [GitHub](gists@eaccmk) profile


[//]: # (Refered https://dillinger.io/  for this pretty formatting)
[//]: # ([gists@eaccmk] <https://github.com/eaccmk/>)