# Online Ecommerce Application (JSP + Servlets + JDBC)

## Project Description
The Online Ecommerce Application is a functional web-based shopping platform built using core Java technologies such as JSP, Servlets, and JDBC. 
The project demonstrates important concepts like user registration, login, session management, product listing, and database connectivity. 
It follows an MVC-like approach—JSP for UI, Servlets for logic, and JDBC for data management—making it ideal for beginners who want to understand Java web application development without frameworks.

## Installation

### Software Requirements
- **JDK 17 or above**
- **Apache Tomcat 9**
- **Eclipse IDE (Enterprise Edition)**
- **MySQL Server**
- **MySQL Connector/J (JDBC Driver)**

### Project Setup
1. Create a new **Dynamic Web Project** in Eclipse.
2. Set **Apache Tomcat v9.0** as the Target Runtime.
3. Add the MySQL connector JAR into:  
   `src/main/webapp/WEB-INF/lib/`
4. Create MySQL database:
   ```sql
   CREATE DATABASE ecommerce;
   ```
5. Create required tables (`users`, `products`).
6. Update your DBConnection.java with MySQL username & password.
7. Verify servlet mappings inside:  
   `src/main/webapp/WEB-INF/web.xml`

## Execution Steps
1. Start **MySQL server**.
2. Start **Apache Tomcat** from Eclipse (Servers tab → Start).
3. Deploy the project:  
   `Right-click project → Run As → Run on Server`
4. Open in browser:  
   `http://localhost:8080/OnlineEcommerceApp/`
5. Access login, register, dashboard, and product pages as needed.
=======
# 📦 Online E-Commerce Platform – SmartBuys

An online marketplace enabling buyers, sellers, and admins to interact seamlessly for smooth digital shopping and business management.
This platform provides a complete workflow including product listing, online shopping, and real-time order tracking.


Presentation - Online E-Commerc…

# 🚀 Features
# 👤 Admin Panel

Manage users, products, and orders centrally

Maintain smooth marketplace operations

Monitor platform activity efficiently


Presentation - Online E-Commerc…

# 🛍️ Seller Dashboard

Create and manage product listings

Update inventory and process orders

Gain insights into sales performance

Intuitive interface improves efficiency and productivity


Presentation - Online E-Commerc…

# 🛒 Buyer Experience

Browse a wide range of products

Purchase items quickly and securely

Track order status in real time

User-friendly interface for smooth navigation


Presentation - Online E-Commerc…

# 📊 Why E-Commerce?

300M+ online shoppers worldwide

70% growth in digital sales

90% customers prefer online shopping


Presentation - Online E-Commerc…

The rise of digital platforms has transformed modern shopping, providing convenience, global reach, and business opportunities for all stakeholders.

# 🧩 System Architecture

Clear interaction flows between users and backend services

Supports structured data processing across dashboard roles


Presentation - Online E-Commerc…

# 👥 User Types
User Type	Role
Admin	Platform management and oversight
Seller	Product management and order handling
Buyer	Product browsing and purchasing

All users work together to create a smooth and efficient digital shopping system.


Presentation - Online E-Commerc…

# 🧠 Team – The Hivers

Shree Rajan (Team Leader)

Suhana Kumari

Aashish Kishor

# 📌 Future Enhancements

Payment gateway integration

Recommendation engine

AI-based search filtering

Mobile app support
