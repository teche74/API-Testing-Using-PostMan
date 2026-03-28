# 🧪 API Testing Project using Postman (Petstore)

## 📌 Overview

This project demonstrates **API testing using Postman** on the Swagger Petstore API.
It covers end-to-end testing scenarios including user management and store operations with proper validations and test scripts.

---

## 🛠 Tools & Technologies

* Postman
* JavaScript (Postman test scripts)
* Git & GitHub

---

## 🌐 API Under Test

Swagger Petstore API
Base URL: `{{BaseUrl}}/v2`

---

## 📂 Project Structure

```
API-Testing-Postman/
│
├── collections/
│   └── petstore_collection.json
│
├── environments/
│   └── dev_environment.json
│
├── test-data/
│   ├── users.csv
│   └── invalid_users.csv
│
├── screenshots/
│
└── README.md
```

---

## 🔍 Test Scenarios Covered

### 👤 User APIs

* Create Single User
* Create Multiple Users
* Get User
* Update User
* Delete User
* User Login
* User Logout

### 🛒 Store APIs

* Get Inventory
* Place Order
* Find Purchase Order

---

## ✅ Validations Implemented

* Status code validation
* Response body validation
* Field-level assertions
* Data type validation
* Dynamic value validation
* Response time checks (where applicable)

---

## 🔄 Key Features

* ✅ Environment variables (`BaseUrl`, `userName`, `petOrderId`)
* ✅ Request chaining (passing username & orderId)
* ✅ Data-driven testing using CSV
* ✅ Negative test scenarios
* ✅ Dynamic assertions using request data

---

## ▶️ How to Run

1. Import the **Postman Collection**
2. Import the **Environment file**
3. Set `BaseUrl`
4. Run APIs individually or via **Collection Runner**
5. (Optional) Upload CSV for data-driven execution

---

## 📊 Test Data

Located in:

```
test-data/
```
