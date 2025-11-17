# Online Appointment Management Portal (ASP.NET Web Forms)

This is a mini web application built using ASP.NET Web Forms and SQL Server.  
It allows users to view doctors, book appointments, and see scheduled appointments.  

##  How to Run the Project

### 1️)Create the Database
1. Open SQL Server Management Studio (SSMS).
2. Open the file **database.sql** located in the project folder.
3. Execute the script to create the database `AppointmentDB`, tables, and sample doctor data.

---

### 2️) Update the Connection String
In **Web.config**, ensure the connection string matches your SQL Server:

```xml

<add name="AppointmentConn"
     connectionString="Data Source=(localdb)\\MSSQLLocalDB;Initial Catalog=AppointmentDB;Integrated Security=True;"
     providerName="System.Data.SqlClient" />

If using SQL Server instead of LocalDB, update:
Data Source=YOUR_SERVER_NAME;Initial Catalog=AppointmentDB;Integrated Security=True;
```
3️)Run the Project in Visual Studio
AppointmentPortal.zip — download and extract
Open the project in Visual Studio.
Right-click Default.aspx → Set as Start Page.
Press F5 to run the application.

Use the navigation buttons to:

View Doctors

Book Appointment

View Appointments
