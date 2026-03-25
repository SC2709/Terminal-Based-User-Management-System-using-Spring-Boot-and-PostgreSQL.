#Terminal-Based User Management System using Spring Boot and PostgreSQL.

I created a User Management System project which runs on the terminal using Spring Boot, Spring Tool Suite (STS), and PostgreSQL.
First, I created the project using Spring Boot in STS. After that, I added the required dependencies in the pom.xml file, mainly for Spring Boot and PostgreSQL, so that my project can connect with the database.
Then, I worked on the database connection part by creating a separate PostgreSQLConnection.java file. In this file, I added the database URL, username, and password, and handled the connection using exception handling (try-catch). If the connection fails, it displays an error message like "The Database Connection Failed!".
After setting up the connection, I created the main logic of the project in the UserManagement.java file. In this part, I implemented the main features such as adding a user, viewing users, updating user details, deleting users, and exiting the system.
The project works using a menu-driven approach in the terminal, where the user selects options and performs various user management operations like add, view, update, and delete.
Overall, this project helped me understand how to connect Java with a database, perform CRUD operations, handle exceptions, and structure a backend application using Spring Boot.
