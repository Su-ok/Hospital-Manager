# Hospital Manager

## Requirements

- **Tkinter**: GUI design
- **mysql-connector**: Connects to MySQL database
- **MySQL Workbench**

## MySQL Setup

1. Create a table named `hospital` in an existing or new database in MySQL Workbench.
2. Update the connection details (host, username, password, database) in the code at lines 145, 156, 168, and 199.
3. The table must have the following columns:
   - `Reference_No` (INT, primary key)
   - `Nameoftablet` (VARCHAR(25))
   - `Dose` (VARCHAR(25))
   - `Issuedate` (VARCHAR(25))
   - `Expdate` (VARCHAR(25))
   - `Patientname` (VARCHAR(25))

## Running the Project

1. Run the code to open the "HOSPITAL MANAGEMENT SYSTEM" window.
2. The window includes:
   - **Top Half**: Patient Information (left), Prescription (right)
   - **Bottom Half**: Database table display
   - **Middle**: Buttons for various operations
3. Button Functions:
   - **Prescription**: Display input data in Prescription
   - **Prescription Data**: Insert data into the database
   - **Update**: Update a row in the database
   - **Delete**: Delete a row from the database
   - **Clear**: Clear all input fields
   - **Exit**: Exit the application
