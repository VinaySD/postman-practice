# Postman API Testing Practice

A hands-on **API Testing practice repository using Postman**, created to build practical skills in REST API testing, test scripting, request chaining, variables, workflows, file uploads, and data-driven testing.

This repository is part of my preparation for **QA Automation / SDET roles**.

---

## 🛠️ Tools & Technologies

* **Postman**
* **REST APIs**
* **HTTP / HTTPS**
* **JSON**
* **JavaScript** — Postman test scripts
* **Excel** — Test cases & data-driven testing
* **Git & GitHub**

---

## 📚 Topics Practiced

### 1. HTTP Requests

Practiced the major HTTP methods:

* `GET`
* `POST`
* `PUT`
* `PATCH`
* `DELETE`

Covered request components such as:

* URL / Endpoint
* Query Parameters
* Path Parameters
* Headers
* Request Body
* JSON Payload

📁 Collection:

`collections/HTTP Requests.postman_collection.json`

📄 Documentation:

`documentation/HTTP Requests Variables.postman...`

---

### 2. Variables

Practiced using Postman variables to make API requests dynamic and reusable.

Examples include:

* Environment variables
* Collection variables
* Request variables
* Dynamic values

Example:

```text
{{baseUrl}}
{{userId}}
{{token}}
```

📁 Collection:

`collections/Variables.postman_collection.json`

---

### 3. Workflow Testing

Practiced organizing multiple API requests into a logical execution flow.

Example:

```text
Create User
     ↓
Get User
     ↓
Update User
     ↓
Delete User
```

📁 Collection:

`collections/Workflow.postman_collection.json`

---

### 4. Request Chaining

Practiced passing data from one API request to another.

Example:

```text
POST Create User
       ↓
Extract User ID
       ↓
GET User using User ID
       ↓
Update User
```

This helps simulate realistic API testing workflows where the output of one request becomes the input of another.

📁 Collection:

`collections/Chaining.postman_collection.json`

---

### 5. File Upload

Practiced testing APIs that accept file uploads using Postman's form-data functionality.

Covered:

* `multipart/form-data`
* File parameters
* Upload requests
* File upload validation

📁 Collection:

`collections/FileUpload.postman_collection.json`

📄 Documentation:

`documentation/FILE UPLOAD - COMMAND.txt`

---

### 6. Data-Driven API Testing

Practiced executing the same API test with multiple sets of test data.

Test data is maintained externally and used to execute API requests with different inputs.

📁 Collection:

`collections/Data Driven API Test.postman_collection.json`

📁 Test Data:

```text
test-data/
├── Data Driven API Test.xlsx
└── data_driven_api_test.json
```

---

### 7. Student API Testing

Created API test scenarios for Student APIs.

The repository also contains dedicated test cases for these APIs.

📁 Collection:

`collections/Student APIs.postman_collection.json`

📁 Test Cases:

`test-cases/Student API TestCases.xlsx`

📁 Test Data:

`test-data/students.json`

---

### 8. PetStore API Testing

Practiced API testing using the **PetStore API**, covering API requests and JSON-based user/model data.

📁 Collection:

`collections/PetStore_JSON_UserModel.postman_collection.json`

---

## 📂 Repository Structure

```text
postman-practice/
│
├── collections/
│   ├── Chaining.postman_collection.json
│   ├── Data Driven API Test.postman_collection.json
│   ├── FileUpload.postman_collection.json
│   ├── HTTP Requests.postman_collection.json
│   ├── PetStore_JSON_UserModel.postman_collection.json
│   ├── Student APIs.postman_collection.json
│   ├── Variables.postman_collection.json
│   └── Workflow.postman_collection.json
│
├── documentation/
│   ├── FILE UPLOAD - COMMAND.txt
│   └── HTTP Requests Variables.postman...
│
├── test-cases/
│   └── Student API TestCases.xlsx
│
├── test-data/
│   ├── Data Driven API Test.xlsx
│   ├── data_driven_api_test.json
│   └── students.json
│
├── .gitignore
└── README.md
```

---

## 🧪 Testing Areas

Through this project, I practiced:

* REST API testing
* HTTP methods
* Request and response handling
* JSON request/response validation
* Query parameters
* Path parameters
* Headers
* Variables
* Request chaining
* API workflows
* File upload testing
* Data-driven testing
* Test case design
* Test data management
* Postman collections
* API test organization

---

## 📊 Test Case Documentation

Test cases are maintained separately in Excel for structured test-case management.

Example:

```text
test-cases/
└── Student API TestCases.xlsx
```

This helps separate **test design** from **API execution**.

---

## 📦 Test Data

External test data is maintained separately from the Postman collections.

```text
test-data/
├── Data Driven API Test.xlsx
├── data_driven_api_test.json
└── students.json
```

This makes the test data easier to maintain and reuse.

---

## 🎯 Learning Progression

The repository follows a practical progression:

```text
HTTP Requests
      ↓
Variables
      ↓
Workflow
      ↓
Request Chaining
      ↓
File Upload
      ↓
Data-Driven Testing
      ↓
Real API Practice
      ↓
Test Case Documentation
```

---

## 🚀 Next Steps

The next stage of my API automation journey is:

```text
Postman
   ↓
Advanced JavaScript Assertions
   ↓
REST Assured
   ↓
Java API Automation
   ↓
Maven
   ↓
TestNG
   ↓
CI/CD
```

The goal is to transition from **API testing with Postman** to **automated API testing using Java + REST Assured**.

---

## 👨‍💻 About

**Vinay Chaudhari**

BE Computer Engineering | QA Automation / SDET Fresher

### Current QA Automation Stack

```text
Java
  ↓
Selenium
  ↓
TestNG
  ↓
API Testing
  ↓
Postman
  ↓
REST Assured
  ↓
Maven
  ↓
Git
  ↓
CI/CD
```

This repository represents my practical learning and hands-on work with **API testing using Postman**.
