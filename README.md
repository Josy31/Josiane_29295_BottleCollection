. Reusable Crate Return and Deposit Tracking System

NAMES:Akimanizanye Kayondo Josiane
ID: 29295  
Course:INSY 8311 – Database Development with PL/SQL  
Instructor:Eric Maniraguha  
Project Domain: Logistics and Supply Chain  
Database: Oracle Database / PL/SQL

1. Project Overview
The Reusable Crate Return and Deposit Tracking System is an Oracle PL/SQL database project designed to help beverage distributors manage reusable crates issued to customers, track returned quantities, calculate deposit refunds, and monitor outstanding crates.

2. Problem Statement

Beverage distributors frequently issue reusable crates to retailers and customers in exchange for refundable deposits. Tracking partial returns manually can lead to inaccurate balances, incorrect refunds, lost crates, and difficulties identifying overdue returns.

3. Project Objectives

Main Objective: Develop an Oracle PL/SQL system that accurately manages reusable crate issues, returns, deposits, and refunds.

Specific Objectives:

1. Record reusable crates issued to customers.
2. Track full and partial crate returns.
3. Automatically calculate refundable deposits.
4. Prevent returns exceeding outstanding quantities.
5. Identify overdue crates and outstanding balances.
6. Generate transaction and deposit reports.

4. Proposed Solution

The system will use a relational Oracle database to manage customers, crate types, crate issues, returns, deposits, and refunds. PL/SQL procedures and functions will automate transaction processing, while triggers and exception handling will enforce business rules.

5. Data Source

Proposed external research dataset: R3PACK WP3 Dataset D3.4 – Decision-support model for reuse logistic network design.

Source: https://zenodo.org/records/21391977

This dataset provides reusable-packaging and reverse-logistics network information. Its suitability, record count, and licence will be verified before final selection.

Crate issue transactions, customer deposits, and partial returns not available in the source data will be separately identified as simulated test data.

6. Planned Database Tables

| Table | Purpose |
|---|---|
| CUSTOMERS | Stores customer information |
| CRATE_TYPES | Stores reusable crate categories and deposit rates |
| CRATE_ISSUES | Records quantities issued to customers |
| CRATE_RETURNS | Records full and partial returns |
| DEPOSIT_TRANSACTIONS | Records deposits collected and refunded |
| AUDIT_LOG | Tracks important database operations |

7. Planned PL/SQL Features

- Stored Procedures: Issue crates, record returns, and process deposit refunds.
- Functions: Calculate outstanding crates, refundable deposits, and overdue balances.
- Triggers: Enforce transaction restrictions and record audit events.
- Cursors: Generate customer-level transaction summaries.
- Packages: Organize related procedures and functions.
- Exception Handling: Prevent invalid returns, duplicate transactions, and incorrect quantities.

8. Planned Innovation

The proposed innovation is an Oracle APEX interface connected to the Oracle database. Users will be able to record crate transactions, view outstanding balances, and monitor overdue returns.

The interface will call PL/SQL procedures to process transactions and enforce the required business rules.

9. Expected Results

The completed system is expected to improve crate accountability, reduce deposit calculation errors, prevent over-returns, and support accurate reporting of outstanding crates and refunds.
