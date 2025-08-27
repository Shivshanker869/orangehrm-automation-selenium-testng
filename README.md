# **OrangeHRM End-to-End Automation Testing**  

![Selenium](https://img.shields.io/badge/Tool-Selenium-brightgreen?style=for-the-badge)  
![TestNG](https://img.shields.io/badge/Framework-TestNG-blue?style=for-the-badge)  
![Java](https://img.shields.io/badge/Language-Java-red?style=for-the-badge)  
![REST Assured](https://img.shields.io/badge/API-REST%20Assured-orange?style=for-the-badge)  
![Extent Reports](https://img.shields.io/badge/Reporting-Extent%20Reports-yellow?style=for-the-badge)  
![Cucumber](https://img.shields.io/badge/BDD-Cucumber-green?style=for-the-badge)  

## **📌 Project Overview**
This project demonstrates an **Enterprise-Grade End-to-End Automation Framework** for the **OrangeHRM Demo Application**.  
It covers **UI Automation, API Testing, and BDD Integration**, making it a comprehensive QA solution that aligns with **real-world industry practices**.  

The goal is to create a **robust, maintainable, and scalable test framework** that can be showcased as a **professional portfolio piece**.

---

## **🚀 Key Features**
- **UI Test Automation (Selenium & TestNG)**  
  - Modular **Page Object Model (POM)**  
  - **Data-driven tests** using `@DataProvider`  
  - Covers **Login, Add, Search, Edit & Delete Employee Workflows**  

- **Behavior-Driven Development (BDD)**  
  - **Gherkin-based Feature files**  
  - Lean **Step Definitions** integrated with POM  
  - **TestNG Runner** for seamless execution  

- **API Test Automation (REST Assured)**  
  - **GET /employees** – Fetch Employee Data  
  - **POST /create** – Add Employee  
  - **DELETE /delete/{id}** – Remove Employee  

- **Advanced Reporting**  
  - **Extent HTML Reports** with logs & screenshots on failure  
  - Integrated **listeners** for automatic reporting  

- **Non-Functional Testing Plans (Documentation)**  
  - **Performance Testing Strategy (Load under concurrent users)**  
  - **Security Testing Plan (IDOR vulnerability checks)**  

---

## **🛠️ Tech Stack**
- **Programming Language**: Java  
- **UI Automation**: Selenium WebDriver  
- **Test Framework**: TestNG  
- **BDD Framework**: Cucumber (Gherkin Syntax)  
- **API Testing**: REST Assured  
- **Build Tool**: Maven  
- **Reporting**: Extent Reports  
- **Version Control**: Git & GitHub  

---

## **📂 Project Structure**

automation-framework/
├─ src/test/java/
│  ├─ uiTests/
│  │   ├─ pageObjects/
│  │   ├─ stepDefinitions/
│  │   ├─ features/
│  │   ├─ testRunners/
│  │
│  ├─ apiTests/
│  │   ├─ tests/
│  │   ├─ utils/
│
├─ reports/
├─ pom.xml

## **⚡ Getting Started**
### **1. Clone the Repository**
```bash
git clone https://github.com/YourUsername/OrangeHRM-EndToEnd-Automation.git
