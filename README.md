# dmoney-api-jmx

## Tools and Technologies used
- Java
- Apache Jmeter 5.5

## Scenario of this project
- Admin will login to the system
- Admin will see the user list
- A new user will be created
- The newly created user will be searched by id
- The newly created user will be searched by phone number
- The newly created user will be searched by email
- The newly created user's phone number will be updated
- The user will be deleted

## How to run this project
- clone this project
- open the jmx file in jmeter and run the test plan
- for generating report hit following command
```jmeter -n -t [jmx file name] -l [generated csv file name] -e -o Reports```

## Prerequisites
- Java LTS version(8 or 11)
- Apache Jmeter 5.5(must set as environment variable for generating reports from command line)

## Report
![Apache-JMeter-Dashboard](https://user-images.githubusercontent.com/82231014/193440385-24d8462a-b521-49a6-86c1-5b31a42c25cc.png)
