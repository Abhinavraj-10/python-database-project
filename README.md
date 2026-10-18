# python-database-project
# Bank Management System

A Python-based application integrated with a MySQL database to manage day-to-day banking workflows. This system handles customer account generation, deposits, withdrawals, real-time transaction history logs, and administrative record management.

## Technical Stack
* **Language:** Python
* **Database:** MySQL
* **Library:** `mysql.connector`

## Core Capabilities
* **Account Creation:** Generates a secure, unique 10-digit account number utilizing the customer's phone number strings.
* **Transaction Engine:** Allows users to execute real-time deposits and withdrawals while automatically checking balance thresholds to block account overdrafts.
* **Database Verification:** Connects dynamically to backend database relations (`cust_bank` and `cust_tran_details`) to securely insert, select, or modify customer records.
* **Transaction Tracking:** Logs transaction history dates alongside payment modes (Deposit/Withdrawal) for compliance audits.
* **Administrative Operations:** Allows authorized clearing tools to completely remove outdated active accounts or associated transaction tables upon request.
