# Employee-Payroll-Management-System
**Payroll Management Software Overview**

This payroll management software is developed using Java and Microsoft SQL Server as the back-end relational database management system (RDBMS).

**Key Functions:**
- Add new employee details to the database.
- Modify existing employee information.
- Add or modify employee salary details.
- Support for both fixed and hourly salary calculations.
- Generate individual employee pay slips.
- Look up employee information and salary details stored in the database.
- User login capability with administrative access.
- Administrators can add new users to the system.

**Requirements:**
- - Netbeans IDE (7.4+).
- Microsoft SQL Server (2014+)
- JDBC/ODBC Driver for Microsoft SQL Server.

Setup:
1. Execute the 'schema.sql' file in the SQL folder.
2. Open the folder as a NetBeans project.
3. Configure your ODBC data source:
   - Open the ODBC Data Source Administrator.
   - Add a new data source.
   - Choose 'SQL Native Client 11.0', 'SQL Server', or 'ODBC Driver 11 for SQL Server' as your driver.
   - Enter 'SalaryManagementDB' as the name of the data source.
   - Select your Microsoft SQL Server as the server.
   - Provide your SQL Server Authentication credentials if required, or proceed with Integrated Windows Authentication.
   - Set the default database name to 'SalaryManagement' (the database created in Step 1).
   - Grant READWRITE permission.
   - Test the data source to ensure it is functioning correctly.
4. Run the project through the NetBeans IDE.
