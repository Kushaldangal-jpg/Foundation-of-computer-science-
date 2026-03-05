# Foundation-of-computer-science-
### General snapshot
```
- This project is a simple database for a college club membership list.
- It has data on students, clubs, and membership information indicating which club a student joined and vice versa.
- The database has three tables: Student, Club, and Membership. This design minimizes data duplication.
- The Membership table serves as a bridge table, allowing for:
  - a student to be a member of many clubs
  - a club to have many students as members
```
## Learning Objectives
```
- Understand why splitting data into tables improves database quality.
- Create tables with:
  - **Primary Key (PK)** to uniquely identify records
  - **Foreign Key (FK)** to link tables correctly
- Build a database that supports a **many-to-many relationship** using a linking table.
- Insert sample data into multiple tables.
- Use `SELECT` queries to view data.
- Use `JOIN` queries to combine tables and show meaningful results.
```
