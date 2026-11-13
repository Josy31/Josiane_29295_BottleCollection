# Beverage Distribution Empty Bottle Collection and Reconciliation System

NAMES: Akimanizanye Kayondo Josiane  
ID: 29295  
Course: INSY 8311 – Database Development with PL/SQL  
Instructor:Eric Maniraguha  
Project Domain: Logistics and Supply Chain  
Academic Year: 2026–2027  
Database Technology: Oracle Database and PL/SQL

1. Project Overview

The Beverage Distribution Empty Bottle Collection and Reconciliation System is an Oracle PL/SQL database project designed to help beverage distributors manage empty bottle collections from retailers, compare collected quantities with distribution records, identify shortages, and generate accurate reconciliation reports.

The system aims to improve accountability, reduce manual recording errors, and strengthen the management of returnable beverage bottles.

2. Problem Statement

Beverage distributors often experience difficulties tracking empty bottles returned by retailers. Manual recordkeeping can result in inaccurate collection records, missing bottles, duplicate transactions, and unresolved discrepancies between distributed and collected quantities.

These challenges can lead to financial losses, inefficient inventory management, and difficulties monitoring retailer accountability.

3. Project Objectives

Main Objective

To develop an Oracle PL/SQL database system that automates empty bottle collection tracking and reconciliation for beverage distributors.

Specific Objectives

1. Record beverage bottle deliveries to retailers.
2. Track empty bottles collected from retailers.
3. Automatically calculate outstanding bottle quantities.
4. Identify shortages and discrepancies between delivered and collected bottles.
5. Prevent duplicate collection records and invalid transactions.
6. Generate retailer collection and reconciliation reports.

4. Proposed Solution

The proposed system will use an Oracle relational database to store and manage bottle delivery and collection transactions.

PL/SQL procedures, functions, triggers, cursors, and exception handling will automate collection processing, validate transactions, calculate outstanding quantities, and support accurate reconciliation.

5. Data Source

Data Source Status: To be confirmed.

The project requires a real dataset related to beverage distribution, reusable packaging, bottle collection, or reverse logistics.

Potential sources include Kaggle, Zenodo, and other open-data repositories.

The selected dataset must contain several hundred records, permit educational use, and exclude personally identifiable information.

Where necessary, additional simulated bottle delivery and collection transactions will be used for testing and clearly identified as simulated data.

Dataset Link: To be added after verification.

6. Planned Database Tables

| Table Name | Description |
|---|---|
| RETAILERS | Stores retailer identification and location information |
| BOTTLE_TYPES | Stores bottle categories and descriptions |
| DELIVERIES | Records bottles delivered to retailers |
| COLLECTIONS | Records empty bottles collected from retailers |
| RECONCILIATIONS | Stores reconciliation results and discrepancies |
| AUDIT_LOG | Records important database activities |

7. Planned PL/SQL Features

Stored Procedures
- Register bottle deliveries.
- Record empty bottle collections.
- Perform bottle reconciliation.

Functions
- Calculate outstanding bottle quantities.
- Calculate bottle shortages.
- Determine retailer collection performance.

Triggers
- Prevent invalid collection quantities.
- Record changes to important transactions.
- Support database auditing.

Cursors
- Process retailer collection records.
- Generate reconciliation summaries.

Packages
- Organize bottle delivery, collection, and reconciliation operations.

Exception Handling
- Handle invalid quantities.
- Prevent duplicate transaction entries.
- Detect missing retailer or bottle records.

8. Planned Innovation

Innovation Type: User Interface

Proposed Tool: Oracle APEX

The project will include a simple Oracle APEX interface connected to the Oracle database.

The interface will allow authorized users to register deliveries, record empty bottle collections, view outstanding quantities, and access reconciliation reports.

PL/SQL procedures and triggers will enforce the business rules, while Oracle APEX will provide an interactive interface for users.

9. Expected Results

The completed system is expected to:

- Improve the accuracy of bottle collection records.
- Reduce duplicate and invalid transactions.
- Automatically identify outstanding bottles and shortages.
- Improve reconciliation between deliveries and collections.
- Support accurate reporting and retailer accountability.

10. Future Improvements

Future improvements may include barcode scanning, automated shortage notifications, mobile collection recording, and integration with distributor inventory management systems.



