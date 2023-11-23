## Don't forget to give a :star:
This is example code for an automation testing project of booker API using postman
all testcases are written and documented using excel sheet you can access them from this link [Manual TestCases](https://github.com/Bad-ri/Postman_RESTful-Booker_API-Testing/blob/Readme/TestCases.xlsx)
## Test cases
- Verify API Response Status Code.
- Verify That the Response is in JSON format.
- Validate That the Response time is Within Acceptable limits.
- Verify That the Return Values Are as Expected.
## Tools
- postman
- newman
  - Install Newman globally ```npm install -g newman```
  - Install the Newman HTML Extra reporter ```npm install -g newman-reporter-htmlextra```
  - RUN ```newman run Booking.postman_collection.json -e Beta.postman_environment.json -r htmlextra```
- Chai Library: for Assertion.
![Postman logo](https://assets.getpostman.com/common-share/postman-github-logo.png "Postman logo")
