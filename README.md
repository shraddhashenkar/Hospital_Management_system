# 🏥 Hospital Management System (SQL Project)

## 📌 Overview

This project is a **Hospital Management System database** built using SQL. It is designed to manage and organize hospital data such as physicians, patients, nurses, departments, diagnoses, and medical procedures.

The system demonstrates the use of:

* Relational database design
* SQL table creation
* Data insertion
* Data retrieval using queries
* Joins and subqueries

---

## 🗂️ Database Structure

The database consists of the following tables:

* **Physician** – Stores doctor details
* **Department** – Stores hospital departments and their heads
* **Affiliated_With** – Links physicians to departments
* **Nurse** – Stores nurse information
* **Patient** – Stores patient details
* **Patient_Diagnosis** – Stores diagnosis and prescriptions
* **Procedures** – Stores medical procedures and costs

---

## 🔗 Entity Relationships

* A **Physician** can be affiliated with multiple departments
* A **Department** has a head physician
* A **Patient** is assigned a primary physician
* A **Patient Diagnosis** connects patients with physicians
* Medical **Procedures** are linked to diagnoses

---

## ⚙️ Features

* ✔ Fully structured relational database
* ✔ Use of primary keys and foreign keys
* ✔ Realistic hospital dataset
* ✔ Multiple SQL queries including:

  * SELECT queries
  * JOIN operations
  * SUBQUERIES
  * AGGREGATE functions
  * LIKE operator
  * UPDATE & ALTER operations

---

## 🧪 Sample Queries Included

* List physicians in alphabetical order
* Find patients by gender
* Retrieve nurse details based on roles
* Calculate average procedure cost
* Find second highest procedure cost
* Join patients with physicians
* Subqueries for advanced filtering

---

## 🚀 How to Run

1. Open MySQL / any SQL-supported DBMS
2. Run the script:

   ```sql
   Hospital_Database.sql
   ```
3. Then execute:

   ```sql
   Hospital_Query.sql
   ```

---

## ⚠️ Important Notes

* Ensure tables are created in the correct order to avoid foreign key errors
* Some queries (like DROP column) modify the schema — use with caution
* Case sensitivity may vary depending on the database system

---

## 🛠️ Technologies Used

* SQL (MySQL)


## 📊 Learning Outcomes

This project helps in understanding:

* Database normalization
* Relational schema design
* SQL query writing
* Data relationships and constraints

---

## 🤝 Contributing

Feel free to fork this repository and improve:

* Query optimization
* Database design
* UI integration (future scope)
