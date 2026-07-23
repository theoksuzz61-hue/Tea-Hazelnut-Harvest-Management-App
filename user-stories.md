# Tea and Hazelnut Harvest and Finance Management System

## 1. Overview

Tea and hazelnut producers generally track their daily harvest amounts, expenses, and earnings using notebooks, spreadsheets, or simple note-taking applications. This traditional approach often leads to data loss, calculation errors, and difficulties in analyzing overall production costs and profits at the end of the season.

The purpose of this project is to develop a mobile application that enables producers to record their harvest amounts in different units (such as sacks, kilograms, and grams), track transportation and operational expenses, and monitor their daily financial activities. By analyzing the collected data, the application will provide daily, monthly, and seasonal reports to help producers manage their agricultural operations more efficiently and make better financial decisions.

## 2. Scope

This project focuses on developing a mobile application that enables tea and hazelnut producers to manage their daily agricultural activities, harvest records, expenses, and financial analyses more efficiently.

The application allows users to record harvest amounts using different measurement units such as sacks, kilograms, and grams. Users can also track transportation costs, fuel expenses, labor costs, market expenses, and other operational expenditures.

Based on the collected data, the system provides daily, monthly, and seasonal reports, including income, expense, and profit/loss analyses. The primary goal of the application is to help producers monitor their production processes, improve financial management, and make more informed decisions.

### In Scope

- Recording daily tea and hazelnut harvest data.
- Supporting multiple measurement units (sacks, kilograms, grams, etc.).
- Recording transportation, fuel, labor, market, and other operational expenses.
- Calculating daily income, expenses, and profit/loss analyses.
- Generating daily, monthly, and seasonal reports.
- Displaying historical harvest and expense records.
- Providing summary dashboards and statistical analyses based on recorded data.
- Tracking estimated earnings based on current tea and hazelnut market prices.
- Providing a simple and user-friendly mobile interface for producers.

> **Design note (updated):** predefined/customizable sack type definitions were removed from the final design in favor of direct sack weight and count entry at the time of each harvest record, to keep data entry simpler for the target audience.

## 3. Users

This application is designed for tea and hazelnut producers who want to track their daily harvest amounts, expenses, and profit analyses. Users can record production data using different measurement units and monitor their financial performance through detailed reports.

**Target audience:** producers aged 60+. The interface is intentionally kept simple, with large text and no complex authentication process, to ensure accessibility for this age group.

## 4. Functional Requirements

| # | Title | Short Description |
|---|-------|--------------------|
| 1 | Daily Harvest Management | The system shall allow users to create, view, edit, and delete daily tea and hazelnut harvest records. |
| 2 | Multiple Measurement Unit Support | Users can enter harvest amounts using sacks, kilograms, and grams. |
| 3 | Automatic Weight Calculation | The system can automatically calculate the total weight from sack count and individual sack weight, or accept a manually entered total. |
| 4 | Expense Management | The system shall allow users to create, view, edit, and delete operational expense records, including labor, fertilizer, pesticide, fuel, and other expenses. |
| 5 | Revenue Calculation | The system can calculate revenue based on recorded sales (price per kg × quantity sold). |
| 6 | Profit and Loss Analysis | The system can analyze income and expenses to calculate net profit or loss. |
| 7 | Reporting / Dashboard | Users can view a summary dashboard per season: total harvest, total expenses, total revenue, and net profit/loss. |
| 8 | Historical Record Viewing | Users can access and review previous harvest, expense, and sale records. |
| 9 | Product Price Management | The system shall allow users to manually enter product prices at the time of sale. |
| 10 | Season Definition | Users shall be able to create and manage harvest seasons by specifying a season name, product type, start date, and end date. |

## 5. Non-Functional Requirements

| # | Title | Short Description |
|---|-------|--------------------|
| 1 | Usability | The application should provide a simple and user-friendly interface. |
| 2 | Performance | The system should respond quickly to user actions and calculations. |
| 3 | Offline Availability | Core features of the application should be accessible without an internet connection. |
| 4 | Data Storage | User data should be securely stored on the device (local storage). |
| 5 | Reliability | The application should operate without causing data loss or corruption. |
| 6 | Scalability | The system should support future feature additions and enhancements. |
| 7 | Compatibility | The application should function properly on different Android devices and screen sizes. |
| 8 | Maintainability | The system should be easy to update, maintain, and improve. |
| 9 | Simplicity | The application should minimize user interactions and avoid complex authentication processes to ensure accessibility for elderly users (60+). |

## 6. Acceptance Criteria

| Feature | Acceptance Criteria |
|---------|----------------------|
| Daily Harvest Management | Users should be able to successfully create, view, edit, and delete daily harvest records. |
| Multiple Measurement Unit Support | Users should be able to enter harvest amounts using sacks, kilograms, and grams. |
| Automatic Weight Calculation | The system should automatically calculate the total weight accurately in automatic mode, and accept a direct total in manual mode. |
| Expense Management | Users should be able to successfully create, view, edit, and delete expense records. |
| Revenue Calculation | The system should estimate revenue using recorded price per kg and quantity sold. |
| Profit and Loss Analysis | The system should correctly display total income, total expenses, and net profit/loss. |
| Reporting / Dashboard | Users should be able to view a season summary dashboard successfully. |
| Historical Record Viewing | Users should be able to access and review previous harvest and expense records. |
| Product Price Management | Users should be able to manually enter tea and hazelnut prices, and the system should correctly use these values in revenue calculations. |
| Offline Availability | Core functionalities should remain accessible without an internet connection. |
| Input Validation | The system should prevent invalid inputs such as negative values, non-numeric entries, and inconsistent data. |
| Season Definition | Users should be able to create and manage harvest seasons by specifying a season name, product type, start date, and end date. |

---

## User Stories

1. **As a Producer**, I want to create harvest seasons so that I can organize my records by season.
   - The user shall be able to create a new season with a name, product type, start date, and optional end date.
   - The created season shall be displayed in the season list.

2. **As a Producer**, I want to record tea and hazelnut harvests separately so that I can analyze each product individually.
   - The user shall be able to select tea or hazelnut as the product type for each harvest record.
   - Reports shall display tea and hazelnut data separately.

3. **As a Producer**, I want to add daily harvest records so that I can track my production amounts.
   - The user shall be able to enter the harvest date and amount, and save the record.

4. **As a Producer**, I want to choose between automatic and manual weight calculation so that I can record harvests in the way that suits me.
   - In automatic mode, the user enters individual sack weight and sack count, and the system calculates the total.
   - In manual mode, the user enters the total weight directly; sack count is optional.

5. **As a Producer**, I want to record transportation, fuel, labor, and other expenses so that I can monitor my operational costs.
   - The user shall be able to select an expense type, enter an amount, an optional description, and save the record.
   - Expenses shall appear in reports.

6. **As a Producer**, I want to record sales and have the system calculate my revenue automatically so that I can monitor my earnings.
   - The user shall be able to enter sale date, product type, price per kg, and quantity sold.
   - The system shall calculate total revenue automatically.

7. **As a Producer**, I want to view a dashboard so that I can quickly access important statistics and summary information.
   - The dashboard shall display total harvest amount, total expenses, total revenue, and net profit/loss for the selected season.

8. **As a Producer**, I want to review historical records so that I can compare previous seasons and performances.
   - The user shall be able to access and filter previous harvest, expense, and sale records by season.
