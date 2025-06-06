## Simple Books API Automation – Postman + Newman

This project shows complete API test coverage for the [Simple Books API](https://simple-books-api.glitch.me/) with Postman, environment variables, JavaScript tests, and Newman CLI automation. This approach ensures that all endpoints have been thoroughly tested for functionality, performance, and security. We can easily manage environment variables and implement JavaScript tests using Postman's powerful features, while Newman allows for seamless integration into our continuous integration pipeline.

----

## Project Objective

The objective of this project is to demonstrate how to perform **comprehensive API testing** using industry-standard tools and techniques. This comprises:

- Developing a modular and reusable Postman Collection 
- Utilizing environment variables for flexibility
- Automating test execution with Newman.
- Creating visual test reports in HTML and PDF.
- Practicing real-world scenarios, including authorization, edge cases, and failures.
- API Monitoring for scheduled health checks.

---

## Features Included

- **Verification of Response Body, Headers, Time, and Size** 
- **Assertions on Data Types and Required Fields** 
- **Automated Test Reports via Newman HTML Reporter** 
- **PDF Export of Test Results for Reporting and Sharing** 
- **Randomized Test Data to Improve Coverage**
- **Active Postman Monitors for scheduled health testing**
- **Automated reports via Newman HTML Reporter**

---

## Test Coverage Breakdown

| Area                          |  Description                                  |
|-------------------------------|-----------------------------------------------|
| Status Code                   |  Validates HTTP status codes                  |
| Response Headers              |  Checks Content-Type, Caching, etc.           | 
| Response Body Structure       |  Validates required keys and format           |  
| Data Types                    |  Validates string, boolean, number types      |
| Authentication Token          |  Generated and reused across requests         |
| Random Data Testing           |  Dynamic client names and request bodies      |
| Response Time & Size          |  Checks performance thresholds                | 
| Token Storage in Env Var      |  Postman script extracts & saves token        | 
| Monitors                      |  Scheduled auto-test runs with alerts         |

---

## Monitor Setup

- A monitor has been set up in Postman to run key test cases every day.
- Alerts are shown for any failed test.
- Response time, size, and status are validated in scheduled runs.

---

##  Technologies Used

- **Postman** – For API requests, environments, and testing
- **Newman** – For CLI-based test automation
- **Postman Monitors** – For continuous monitoring and alerting
- **HTML Reporter** – For visual test result reports
- **JavaScript** – For assertions, scripting and chaining


---

 ## How to Run
 
- Import simplebooks_collection.json into Postman
- Set base URL variable: BooksURL = [https://simple-books-api.glitch.me]
- Run requests step-by-step or as a collection
- Open Console to view logs

---

## Author & Learning Goals

This project is built by Ranum Khan as part of her API Testing Practice Portfolio while learning automation from scratch.

---

## Feedback

I'm a passionate Software QA Engineer with 4+ years of experience in manual testing. I'm currently transitioning into advanced API automation and sharing my learning publicly. If you like this collection, if this helped or inspired you, do give a ⭐ star or fork it! and connect via LinkedIn. PRs and suggestions are welcome! 

- https://www.linkedin.com/in/ranum-khan-qaengineer
- https://github.com/Ranumkhan123
- ranumkhan123@gmail.com
