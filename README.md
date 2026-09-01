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

---Product Module---
Test performed:
- Retrieved all available products by removing the default pagination limit
- Verified the total product count
- Validated the product response structure
- Verified the response time was below 1000 ms
- Retrieved a single product
- Verified the requested product matches the returned product
- Validated the single product response structure
- Retrieved a specific product
- Validated the specific product response structure
- Verified error messages for invalid requests
- Verified the error response status code
- Verified the Product ID generated for the created product
- Verified the created product title matches the request
- Verified the created product price matches the request
- Validated the response structure of the created product


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

  
