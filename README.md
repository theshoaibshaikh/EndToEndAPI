# EndToEndAPI Test Automation

A complete **API test automation framework** using Java, Rest Assured, and TestNG. This project tests a sample E-Commerce API hosted on [https://rahulshettyacademy.com](https://rahulshettyacademy.com), covering user login, product creation, order placement, and product deletion.

---

## 🚀 Project Overview

This project simulates a real-world E2E flow:
1. Authenticate the user
2. Add a new product with an image
3. Create an order using the added product
4. Delete the product
5. Validate responses using assertions

---

## 🛠️ Tools & Technologies Used

| Tool/Library       | Purpose                          |
|--------------------|----------------------------------|
| **Java 21**        | Programming language             |
| **Maven**          | Build & dependency management    |
| **Rest Assured**   | API testing framework            |
| **TestNG**         | Test framework (execution, assertions) |
| **Jackson**        | JSON serialization/deserialization |
| **SLF4J**          | Logging (via Rest Assured)       |

---

## 🗂️ Project Structure

```bash
EndToEndAPI/
├── pom.xml
├── testng.xml
├── README.md
├── src/
│   ├── main/
│   │   └── java/
│   │       └── pojo/
│   │           ├── LoginRequest.java
│   │           ├── LoginResponse.java
│   │           ├── OrderDetail.java
│   │           └── Orders.java
│   └── test/
│       ├── java/
│       │   └── demo/
│       │       └── ECommerceAPITest.java
│       └── resources/
│           └── images/
│               └── test.png
