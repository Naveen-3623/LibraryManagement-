📚 Library Management System (LMS)
Overview:
Library Management System is a simple Java web application developed using Servlets, JDBC, Oracle 11g XE, and Apache Tomcat.
It performs basic CRUD operations (Add and View Books) using a layered architecture.

Technologies Used:
Java
Servlets
JDBC
Oracle 11g XE
Apache Tomcat
HTML

Project Structure:
bean – Contains AuthorBean, BookBean
dao – Contains AuthorDAO, BookDAO
service – Business logic (Administrator)
servlets – Request handling (MainServlet, ViewServlet)
util – Database connection (DBUtil)
webapp – HTML pages (AddBook, ViewBook, Menu, Failure, Invalid)

Features:
✔ Add Book
✔ View Book
✔ Author Validation
✔ Exception Handling
✔ MVC Architecture

How to Run:
Create tables in Oracle 11g XE.
Update database credentials in DBUtil.java.
Deploy on Tomcat.

OUTPUT:
<img width="1918" height="388" alt="image" src="https://github.com/user-attachments/assets/22345aff-10d7-419e-9d81-f3908c836db8" />

<img width="620" height="518" alt="image" src="https://github.com/user-attachments/assets/15992a40-95ef-4936-b7f8-d470d00dc2ee" />

<img width="534" height="458" alt="image" src="https://github.com/user-attachments/assets/d55008a4-0801-48fa-82e7-7fe136af6318" />


Developed by: Naveen Kumar S
