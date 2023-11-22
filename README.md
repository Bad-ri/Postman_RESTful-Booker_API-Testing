## Don't forget to give a :star:
This is example code for an automation testing project of booker API using postman
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
  - RUN ```newman run coll.json -e env.json -r htmlextra```
- Chai Library: for Assertion.
![Postman logo](https://assets.getpostman.com/common-share/postman-github-logo.png "Postman logo")
