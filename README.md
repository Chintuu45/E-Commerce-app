# E-Commerce-app
Shopping cart web application
-----------------------------
E-commerce Web Application
----------------------------
A basic, full-stack e-commerce web application built with Java Servlets and JSP. This project demonstrates a foundational understanding of web development principles, including user authentication, product management, and a shopping cart system.

About The Project
-----------------
This web application serves as a learning project to understand the core concepts of server-side web development using Java. It provides a simple storefront where users can browse products, add items to a cart, register, and log in. The application is built on a standard MVC (Model-View-Controller) architecture, separating the business logic from the user interface.

Features
----------
User Authentication: Secure user registration and login functionality.

Product Catalog: Browse a list of available products.

Shopping Cart: Add, remove, and update items in a shopping cart.

Order History: View past orders and their details.

REST API: A basic REST endpoint to demonstrate API configuration.

Technologies Used
-----------------
Backend: Java, Servlets

Frontend: JSP (JavaServer Pages), HTML, CSS

Build Tool: Apache Maven

Web Server: Apache Tomcat

Templating: JSTL (JSP Standard Tag Library)

Database: SQL (JDBC for connectivity)

Getting Started
---------------
Follow these steps to set up and run the project locally.

Prerequisites
-------------
Java Development Kit (JDK) 8 or higher

Apache Maven 3.6+

An Apache Tomcat server

A SQL database (e.g., MySQL, PostgreSQL)

Installation
-------------
Clone the repository:

git clone [https://github.com/Chintuu45/E-Commerce-app.git](https://github.com/Chintuu45/.git)
cd EcommerceWebApp

Database Setup:
--------------
Create a new database and a user with appropriate permissions. Update the database connection URL, username, and password in your UserDAO.java and OrderDAO.java files to match your configuration.

Build the Project with Maven:
----------------------------
Open your terminal in the project's root directory (where pom.xml is located) and run the following command. The -U flag forces Maven to update all dependencies, which can help resolve issues with cached artifacts.

mvn clean install -U

This command will build the project and create a EcommerceWebApp.war file in the target directory.

Deploy to Tomcat:
------------------
Copy the EcommerceWebApp.war file from the target directory into the webapps folder of your Apache Tomcat installation.

Start Tomcat:
------------
Start your Tomcat server. The application will be automatically deployed.

Usage
-------
After deployment, open your web browser and navigate to:

http://localhost:8080/EcommerceWebApp/

From there, you can register a new user or log in to explore the application.

Contact
-------
If you have any questions, you can reach me here:

GitHub: @Chintuu45

Email: beherapanchanan933@gmail.com
Phone: +91 8455810080

License
Distributed under the MIT License. See LICENSE.txt for more information.
