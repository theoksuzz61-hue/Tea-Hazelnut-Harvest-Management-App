# Overwiew
  Tea and hazelnut producers generally track their daily harvest amounts, expenses, and earnings using notebooks, spreadsheets, or simple note-taking applications. This traditional approach often leads to data loss, calculation errors, and difficulties in analyzing overall production costs and profits at the end of the season.
  The purpose of this project is to develop a mobile application that enables producers to record their harvest amounts in different units (such as sacks, kilograms, and grams), track transportation and operational expenses, and monitor their daily financial activities. By analyzing the collected data, the application will provide daily, monthly, and seasonal reports to help producers manage their agricultural operations more efficiently and make better financial decisions.

# Scope
This project focuses on developing a mobile application that enables tea and hazelnut producers to manage their daily agricultural activities, harvest records, expenses, and financial analyses more efficiently.

The application will allow users to record harvest amounts using different measurement units such as sacks, kilograms, and grams. Users will also be able to track transportation costs, fuel expenses, labor costs, market expenses, and other operational expenditures.

Based on the collected data, the system will provide daily, monthly, and seasonal reports, including income, expense, and profit/loss analyses. The primary goal of the application is to help producers monitor their production processes, improve financial management, and make more informed decisions.

## In Scope

-   Recording daily tea and hazelnut harvest data.   
-   Supporting multiple measurement units (sacks, kilograms, grams, etc.)  
-   Recording transportation, fuel, labor, market, and other operational expenses. 
-   Calculating daily income, expenses, and profit/loss analyses.
-   Generating daily, monthly, and seasonal reports.
-   Displaying historical harvest and expense records.  
-   Providing summary dashboards and statistical analyses based on recorded data. 
-   Tracking estimated earnings based on current tea and hazelnut market prices.
-   Providing a simple and user-friendly mobile interface for producers.

# Users
This application is designed for tea and hazelnut producers who want to track their daily harvest amounts, expenses, and profit analyses. Users will be able to record production data using different measurement units and monitor their financial performance through detailed reports.

# Functional Requirements
               Title|Short Description|

|1-Daily Harvest Management        |The system shall allow users to create, view, edit, and delete daily tea and hazelnut harvest records.            |
|2-Multiple Measurement Unit Support         |`Users can enter harvest amounts using sacks, kilograms, and grams.          
|3-Automatic Weight Calculation         |The system can automatically calculate the total weight from different measurement units.|
|4-Expense Management         |The system shall allow users to create, view, edit, and delete operational expense records, including transportation, fuel, labor, market, and other expenses.
|5-Transportation Cost Calculation |The system can calculate transportation costs based on traveled distance and cost per kilometer.
|6-Revenue Calculation |The system can estimate revenue based on harvest amounts and current product prices.
|7-Profit and Loss Analysis |The system can analyze income and expenses to calculate net profit or loss.
|8-Reporting System | Users can view daily, monthly, and seasonal reports.
|9-Historical Record Viewing |Users can access and review previous harvest and expense records.
|10-Product Price Management |The system shall allow users to manually enter product prices and support automatic price updates when external market data is available.
|11-Dashboard |The system shall display key statistics and summary information, including total profit for the current month, total harvest amount, average harvest per day, and the most productive day.
|12-Input Validation |The system shall validate user inputs and prevent invalid data entries.
|13-Season Definition |Users should be able to define custom harvest seasons by specifying season names and date ranges.
|14-Record Management |The system shall allow users to edit and delete previously entered harvest and expense records.
|

#  Non-Functional Requirements
|                Title                          |Short Description|
|----------------|-------------------------------|-----------------------------|
|  Usability |The application should provide a simple and user-friendly interface.  |
|Performance|`The system should respond quickly to user actions and calculations.            |"Isn't this fun?"            |
|Offline Availability|Core features of the application should be accessible without an internet connection.| 
|Data Storage |User data should be securely stored on the device.
|Reliability | The application should operate without causing data loss or corruption. 
|Scalability |The system should support future feature additions and enhancements.
|Compatibility |The application should function properly on different Android devices and screen sizes.
|Maintainability |The system should be easy to update, maintain, and improve.
|Simplicity |The application should minimize user interactions and avoid complex authentication processes to ensure accessibility for elderly users. 
|

# Acceptance Criteria
|                Feature|Acceptance Criteria|
|----------------|-------------------------------|-----------------------------|
|1-Daily Harvest management|`Users should be able to successfully create, view, edit, and delete daily harvest records.            |'Isn't this fun?'            |
|2-Multiple Measurement Unit Support|Users should be able to enter harvest amounts using sacks, kilograms, and grams.                       |
|3-Automatic Weight Calculation|The system should automatically calculate the total weight from different measurement units accurately.|
|4-Expense Management |Users should be able to successfully create, view, edit, and delete expense records.
|5-Transportation Cost Calculation |The system should correctly calculate transportation costs based on traveled distance and cost per kilometer.
|6-Revenue Calculation |The system should estimate revenue using harvest amounts and current product prices.
|7-Profit and Loss Analysis |The system should correctly display total income, total expenses, and net profit/loss.
|8-Reporting System|Users should be able to view daily, monthly, and seasonal reports successfully.
|9-Historical Record Viewing |Users should be able to access and review previous harvest and expense records.
|10-Product Price Management |Users should be able to manually enter tea and hazelnut prices, and the system should correctly use these values in revenue and profit/loss calculations.
|11-Dashboard |Users should be able to view summary statistics such as total profit, total harvest amount, average daily harvest, and the most productive day on the dashboard.
|12-Offline Availability |Core functionalities should remain accessible without an internet connection.
|13-Input Validation |The system should prevent invalid inputs such as negative values, non-numeric entries, and inconsistent data.
|14-Season Definition |Users should be able to create and manage harvest seasons by specifying a season name, start date, and end date.
|





