# Bank-Transfer-SQL
This project implements a simple banking database schema that simulates money transfers between two accounts. It demonstrates SQL skills such as table creation, primary/foreign keys, identity columns, default values, and transaction logging.

## Features 
Structured banking schema built with SQL Server.

Two account tables (account_1, account_2) representing separate bank accounts with balances.

Transfer logging system using bank_from and bank_to tables to record outgoing and incoming transactions.

Identity-based primary keys to automatically generate unique IDs for all records.

Foreign key constraints ensuring valid relationships between accounts and transfers.

Automatic timestamps for each transaction using GETDATE().

Support for balance history tracking, allowing use of logs to reconstruct all money movements.

Demonstrates use of INSERT, SELECT, identity functions (@@identity, ident_current), and table relationships.
