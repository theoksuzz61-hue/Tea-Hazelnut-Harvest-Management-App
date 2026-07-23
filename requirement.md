# Tea and Hazelnut Harvest and Finance Management System

## 1. Overview

Tea and hazelnut producers generally track their daily harvest amounts, expenses, and earnings using notebooks, spreadsheets, or simple note-taking applications. This traditional approach often leads to data loss, calculation errors, and difficulties in analyzing overall production costs and profits at the end of the season.

The purpose of this project is to develop a mobile application that enables producers to record their harvest amounts in different units (such as sacks, kilograms, and grams), track transportation and operational expenses, and monitor their daily financial activities.

By analyzing the collected data, the application will provide daily, monthly, and seasonal reports to help producers manage their agricultural operations more efficiently and make better financial decisions.

---

## 2. Scope

This project focuses on developing a mobile application that enables tea and hazelnut producers to manage their daily agricultural activities, harvest records, expenses, and financial analyses more efficiently.

The application allows users to record harvest amounts using different measurement units such as sacks, kilograms, and grams. Users can also track transportation costs, fuel expenses, labor costs, market expenses, and other operational expenditures.

Based on the collected data, the system provides daily, monthly, and seasonal reports, including income, expense, and profit/loss analyses. The primary goal of the application is to help producers monitor their production processes, improve financial management, and make more informed decisions.

### In Scope

- Record daily tea and hazelnut harvest data.
- Support multiple measurement units (sacks, kilograms, grams, etc.).
- Record transportation, fuel, labor, market, and other operational expenses.
- Calculate daily income, expenses, and profit/loss.
- Generate daily, monthly, and seasonal reports.
- Display historical harvest and expense records.
- Provide summary dashboards and statistical analyses.
- Track estimated earnings based on current tea and hazelnut market prices.
- Provide a simple and user-friendly mobile interface for producers.

---

## 3. Users

This application is designed for tea and hazelnut producers who want to track their daily harvest amounts, expenses, and profit analyses.

Users can record production data using different measurement units and monitor their financial performance through detailed reports.

**Target Audience**

- Tea producers
- Hazelnut producers
- Producers aged **60+**

The interface is intentionally designed with:

- Large text
- Simple navigation
- Minimal user interaction
- No complex authentication process

to ensure accessibility for elderly users.

---

## 4. Functional Requirements

| ID | Title | Short Description |
|:---|:------|:------------------|
| FR-01 | Daily Harvest Management | The system shall allow users to create, view, edit, and delete daily tea and hazelnut harvest records. |
| FR-02 | Multiple Measurement Unit Support | Users can enter harvest amounts using sacks, kilograms, and grams. |
| FR-03 | Automatic Weight Calculation | The system can automatically calculate the total weight from sack count and individual sack weight, or accept a manually entered total. |
| FR-04 | Expense Management | The system shall allow users to create, view, edit, and delete operational expense records including labor, fertilizer, pesticide, fuel, and other expenses. |
| FR-05 | Revenue Calculation | The system can calculate revenue based on recorded sales (price per kg × quantity sold). |
| FR-06 | Profit and Loss Analysis | The system can analyze income and expenses to calculate net profit or loss. |
| FR-07 | Reporting / Dashboard | Users can view a summary dashboard per season showing total harvest, total expenses, total revenue, and net profit/loss. |
| FR-08 | Historical Record Viewing | Users can access and review previous harvest, expense, and sale records. |
| FR-09 | Product Price Management | The system shall allow users to manually enter product prices at the time of sale. |
| FR-10 | Season Definition | Users shall be able to create and manage harvest seasons by specifying a season name, product type, start date, and end date. |

---

## 5. Non-Functional Requirements

| ID | Title | Short Description |
|:---|:------|:------------------|
| NFR-01 | Usability | The application should provide a simple and user-friendly interface. |
| NFR-02 | Performance | The system should respond quickly to user actions and calculations. |
| NFR-03 | Offline Availability | Core features of the application should be accessible without an internet connection. |
| NFR-04 | Data Storage | User data should be securely stored on the device using local storage. |
| NFR-05 | Reliability | The application should operate without causing data loss or corruption. |
| NFR-06 | Scalability | The system should support future feature additions and enhancements. |
| NFR-07 | Compatibility | The application should function properly on different Android devices and screen sizes. |
| NFR-08 | Maintainability | The system should be easy to update, maintain, and improve. |
| NFR-09 | Simplicity | The application should minimize user interactions and avoid complex authentication processes to ensure accessibility for elderly users (60+). |

---

## 6. Acceptance Criteria

| Feature | Acceptance Criteria |
|:--------|:--------------------|
| Daily Harvest Management | Users should be able to successfully create, view, edit, and delete daily harvest records. |
| Multiple Measurement Unit Support | Users should be able to enter harvest amounts using sacks, kilograms, and grams. |
| Automatic Weight Calculation | The system should automatically calculate the total weight accurately in automatic mode and accept a direct total in manual mode. |
| Expense Management | Users should be able to successfully create, view, edit, and delete expense records. |
| Revenue Calculation | The system should estimate revenue using recorded price per kg and quantity sold. |
| Profit and Loss Analysis | The system should correctly display total income, total expenses, and net profit/loss. |
| Reporting / Dashboard | Users should be able to view a season summary dashboard successfully. |
| Historical Record Viewing | Users should be able to access and review previous harvest and expense records. |
| Product Price Management | Users should be able to manually enter tea and hazelnut prices, and the system should correctly use these values in revenue calculations. |
| Offline Availability | Core functionalities should remain accessible without an internet connection. |
| Input Validation | The system should prevent invalid inputs such as negative values, non-numeric entries, and inconsistent data. |
| Season Definition | Users should be able to create and manage harvest seasons by specifying a season name, product type, start date, and end date. |
