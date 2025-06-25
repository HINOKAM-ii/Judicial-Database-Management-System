# 🏛️ Judicial Database Management System (JDBMS)

A comprehensive **relational database system** built with **PostgreSQL** to efficiently manage judicial information such as case records, court schedules, user roles, evidence, FIRs, hearings, and verdicts.

## 📘 Overview

This project is a robust back-end database schema designed to support operations within a judicial environment. It enables efficient data storage and querying of:

- **Citizen information**
- **Court and judge data**
- **Lawyers and law firms**
- **FIRs and parties involved**
- **Legal cases and verdicts**
- **Evidences and testimonies**
- **Hearing schedules**

## 🛠️ Technologies Used

- **PostgreSQL**: Core relational database
- **SQL (DDL + DML)**: Complex query logic for inserting, tracking, and summarizing case data

## 🧩 Schema Design Highlights

- Fully **normalized** database to reduce redundancy and ensure data consistency.
- Implemented **foreign key constraints** and **check conditions** for referential and logical integrity.
- Modular table design allows extensibility (e.g., adding new types of users or legal entities).

## 🔍 Key Features

- **Case Tracking**: Track case status, hearings, and associated parties
- **FIR Handling**: Link FIRs to involved citizens and cases
- **Legal Summary Generation**: Aggregate data for reports and summaries
- **Scheduling**: Manage hearing calendars and judge assignments
- **Role-Based Entries**: Citizens, lawyers, judges, law firms are all managed with clean role separation

## 📂 Directory Structure

```plaintext
📁 Root of your repo
 ┣ 📄 DDL Script.txt             ← Schema creation (DDL)
 ┣ 📄 JDBMS_ER_and_Normalization.pdf ← ER diagram + BCNF + minimal cover
 ┣ 📄 Queries.txt                ← SQL queries (DML/DDL)
 ┣ 📄 README.md                  ← Project overview and usage guide

