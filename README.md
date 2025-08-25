# 💍 Wedding Vendor Management System
*A platform to seamlessly connect customers with wedding vendors and manage bookings.*  

![Build](https://img.shields.io/badge/build-passing-brightgreen)  ![License](https://img.shields.io/badge/license-MIT-blue)  ![ASP.NET](https://img.shields.io/badge/framework-ASP.NET-lightblue)  ![Database](https://img.shields.io/badge/database-SQL%20Server-orange)  

---

## Project Description
The **Wedding Vendor Management System** helps streamline wedding planning by providing a platform where customers can discover, compare, and book wedding vendors.  
It enables vendors to showcase services while giving administrators tools to manage users and orders.  

Designed for engaged couples, vendors, and admins, the system simplifies the entire vendor booking process.  

---

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Testing](#testing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [FAQs](#faqs)
- [Contact](#contact)

---

## Features
-  Secure login for Admin, Customer, and Vendor  
-  Customer registration and order management  
-  Vendor registration, profile, and inquiry management  
-  Admin dashboard with metrics and management tools  
-  Location-based vendor categorization (state, city, category, subcategory)  
-  Order tracking and inquiry system  
-  Dashboard analytics for each role  

---

##  Technology Stack
- **Frontend**: ASP.NET Web Forms, HTML, CSS, JavaScript  
- **Backend**: ASP.NET (C# Code-behind)  
- **Database**: SQL Server  
- **Server**: IIS (Internet Information Services)  
- **Other Tools**: ADO.NET for data access  

---


##  Installation
1. Install **Visual Studio** with ASP.NET support.  
2. Install **SQL Server** and configure a database.  
3. Clone this repo:  
   ```bash
   git clone https://github.com/Jay-Shah-92/wedlist.git


##  Usage

* Login as **Admin** → Manage customers, vendors, and orders.
* Login as **Customer** → Browse vendors, create orders, and track them.
* Login as **Vendor** → Update profile, respond to inquiries, and track engagement.

---

##  Configuration

* Modify the `Web.config` file to update database connection strings.
* Adjust application settings (like default roles or categories) in the database.

---

##  Testing

* **Manual Testing**:

  1. Register new customer and vendor accounts.
  2. Verify login system and dashboards.
  3. Place an order and validate the database entry.

---

## License

This project is licensed under the [MIT License](LICENSE).  
![License](https://img.shields.io/badge/license-MIT-blue)

---

##  Acknowledgments

* Inspired by the challenges of planning weddings efficiently.
* Built with ASP.NET & SQL Server.

---

##  FAQs

* **Q: Why is my login failing?**
  **A**: Verify that your email and password are correctly registered in the database.

* **Q: How do I deploy this on a live server?**
  **A**: Configure IIS and update your `Web.config` with the production DB connection string.

---

##  Contact

For questions or collaboration:

* **Author**: Jay Shah
* **Email**: [jayshah92.ca@gmnail.com](mailto:jayshah92.ca@gmail.com)
* **GitHub**: [Jay-Shah-92](https://github.com/Jay-Shah-92)
