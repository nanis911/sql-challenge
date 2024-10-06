# SQL-Challenge

For this project, I designed tables to hold employee data from CSV files, imported the data into a PostgreSQL database, and performed data modeling, engineering, and analysis.

## Database Schema

The database contains the following tables:

1. **employees**: Employee personal information.
2. **departments**: Department details.
3. **dept_emp**: Links employees to departments.
4. **dept_manager**: Stores department managers.
5. **salaries**: Employee salary information.
6. **titles**: Employee job titles.

### Key Features:
- **Foreign Keys**: Enforce relationships between employees, departments, and salary records.
- **Composite Keys**: Used in `dept_emp` and `dept_manager` for multi-column unique identification.

