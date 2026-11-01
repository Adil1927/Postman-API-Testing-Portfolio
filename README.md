Postman API Testing Portfolio

Project Overview

This repository contains my API testing practice projects using Postman and Newman. It includes API collections, test cases, environment configurations (where safe to share), and HTML execution reports.

Tools & Technologies

- Postman
- Newman
- JavaScript (Postman test scripts)
- REST API
- JSON
- Git and GitHub

Projects Included

1. GitHub API Testing

Tested GitHub API operations:

- POST – Create a repository
- PATCH – Update a repository
- GET – Retrieve a repository
- DELETE – Delete a repository

2. GitHub API Testing – Four Projects

A collection containing GitHub API requests organized for multiple project scenarios.

3. GitHub API Testing – Test Cases

A collection containing additional API test cases for validating GitHub API operations.

4. Employee API Testing

Tested employee-related API scenarios:

- Retrieve multiple employees
- Retrieve a single employee
- Validate invalid employee data
- Create employees
- Update employee details
- Delete an employee

Also includes registration and login scenarios.

Newman Execution Reports

Executed Postman collections using Newman through the Command Prompt and generated HTML reports.

The reports include:

- Total requests
- Total assertions
- Passed and failed tests
- Skipped tests
- Execution duration
- Detailed failure information

Note: The committed sample reports include failed assertions. These results are retained for review and debugging.

How to Run the Collections

1. Install Postman.

2. Install Node.js.

3. Install Newman:
   
   "npm install -g newman"

4. Install the HTML reporter:
   
   "npm install -g newman-reporter-htmlextra"

5. Run a collection:
   
   "newman run collection.json -e environment.json -r htmlextra"

Replace the filenames with the appropriate collection and environment files.

Learning Objectives

- Understand REST API testing.
- Practice HTTP methods.
- Validate API responses.
- Write Postman test scripts.
- Execute collections using Newman.
- Analyze HTML execution reports.

Author

Adil

GitHub: https://github.com/Adil1927