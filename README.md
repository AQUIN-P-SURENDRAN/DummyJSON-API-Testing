DummyJSON API Testing

---Project Overview---

This project demonstrates API testing using Postman and Newman with the DummyJSON API.
The project focuses on functional API testing, user data response validation, status code verification as per assertion, response time validation, and automated test execution using Newman.

---Tools & Technologies--
Postman – API request creation and functional testing
Newman – Command-line execution of Postman collections
JavaScript – Postman test scripts
DummyJSON API – API under test
Git & GitHub – Version control and project management

---Users Module---
The Users module contains API request and test cases for:
* Get All Users
* Get Single User
* Search Users
* Create New User
->The test scripts validate:
* HTTP response status code
* Response time
* Required response fields
* User data
* Response structure
* Error messages

---Product Module
Test performed:
* Retrieved all available products by removing the default pagination limit
* Verified the total product count
* Validated the product response structure
* Verified the response time was below 1000 ms
* Retrieved a single product
* verified the single product is same as the request got
* Verified the single product structure
*Retrieved a single specific product
*Verified the single specific product structure
*verified the error massages
*verifed the error responsed code
*Verfied the Product ID generated
*Verifed the created Title matches what we sent
*Verifed the Price matches the created product
*Verifed the Response structure of the Created product




---Test Report For users module---
The API test collection was executed using Newman.
->[View Live Newman Test Report](https://aquin-p-surendran.github.io/DummyJSON-API-Testing/Users-Module/Newman-Users-Report.html)

---Test Report For Product module---
The API test collection was executed using Newman.
->[View Live Newman Test Report](https://aquin-p-surendran.github.io/DummyJSON-API-Testing/Product-module/Newman-Products-Report.html)


Test Results:
- Total Requests: 9
- Total Assertions: 25
- Passed Assertions: 24
- Failed Tests: 1
- Skipped Tests: 0
- Average Response Time: 366 ms

---Project Status---

Module Status

Users API: Completed

Products API: Completed

Other Modules: Planned

---Tester---
Aquin P Surendran
Software Testing / QA Engineer

  
