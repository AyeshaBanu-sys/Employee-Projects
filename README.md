# Employee-Projects

This repository contains SQL scripts for practicing table creation, data insertion, updates, filtering, and subqueries. It is intended to help understand SQL operations using real-time examples like employee and project data.

---

## 📁 Files Included

- `employeeinfo_table.sql` – Select query for EmployeeInfo table.
- `projectsinfo_table.sql` – Select query for ProjectsInfo table.
- `sql all querys.sql` – Contains:
  - Table creation
  - Data insertion
  - Alter, update, delete
  - Filtering (WHERE, AND, OR, IN, LIKE)
  - Aggregate functions (SUM, AVG, MIN, MAX)
  - Group By, Having
  - Subqueries
 
### Table Name: EmployeeInfo

| ColumnName  | DataType     | Description               |
|-------------|--------------|---------------------------|
| E_id        | INT          | Employee ID (Primary Key) |
| e_Names     | VARCHAR(40)  | Employee Name             |
| e_Dept      | VARCHAR(30)  | Department                |
| e_Salary    | INT          | Employee Salary           |
| e_Age       | INT          | Employee Age              |
| e_Loc       | VARCHAR(40)  | Employee Location         |

| E_id | e_Names    | e_Dept | e_Salary | e_Age  | e_Loc|
|------|------------|--------|----------|--------|------|
| 1    | Ayesha     | QA     | 15500    | 23     | HYD  |
| 2    | Shivani    | QA     | 15000    | 24     | KNR  |
| 3    | Anusarika  | DEV    | 20000    | 25     | BPL  |
| NULL | NULL       | NULL   | NULL     | NULL   | NULL |


### Table Name: ProjectsInfo

| Column Name    | Data Type     | Description           |
|----------------|---------------|-----------------------|
| e_id           | INT           | Employee ID (FK)      |
| project_name   | VARCHAR(50)   | Name of the Project   |
| project_status | VARCHAR(20)   | Status of the Project |
  
| e_id | project_name     | project_status |
+------+------------------+----------------+
| 1    | AutomationSuite  | Active         |
| 2    | RegressionPack   | Completed      |
| 3    | UATSupport       | Pending        |
