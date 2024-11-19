# E-Commerce Web Application

## 📋 Overview
A feature-rich **PHP-based e-commerce web application** designed to address essential functionalities for a digital marketplace. It includes secure user authentication, product management, shopping cart features, and order processing, all while leveraging MySQL for robust database management.

## 🚀 Features
- **User Authentication**: Secure login and registration with password hashing.
- **Product Management**: Add, update, and manage product details.
- **Shopping Cart**: Dynamic cart with real-time item management.
- **Order Processing**: Smooth and efficient order workflows.
- **Admin Panel**: Secure interface for managing products and orders.
- **Payment Option**: Supports **Cash on Delivery (COD)**.

## 🛠️ Requirements
- PHP and MySQL installed on the server.
- PHPMyAdmin for database management.

## ⚙️ Setup Instructions
1. **Database Setup**:
   - Open PHPMyAdmin and create a new database.
   - Import the `bolt.sql` file (for older PHPMyAdmin versions) or `bolt-new-phpmyadmin.sql` (for newer versions) to set up the required tables.

2. **Server Deployment**:
   - Upload all project files to your server, excluding the SQL files.
   - Open the `config.php` file and update it with your database credentials (username and password).
   - Re-upload the updated `config.php` file to the server.

3. **Admin User**:
   - Default admin account credentials:
     - Email: `sjobs@apple.com` or `admin@admin.com`
     - Password: `steve`
   - Verify these credentials in the database or create a new admin user manually.

4. **Run the Application**:
   - Access the application through your server’s URL. The web application should now be operational.

## 📌 Current Status
### Implemented
- Core e-commerce functionalities.
- Secure user authentication and admin interface.
- Responsive and user-friendly design.

### In Progress
- Integration of additional payment gateways.
- Implementation of email notifications for purchases.

## 💻 Technologies Used
- **Frontend**: HTML, CSS, JavaScript, jQuery.
- **Backend**: PHP.
- **Database**: MySQL.

## 🔮 Future Enhancements
- Adding support for payment gateways like PayPal and Stripe.
- Implementing personalized email notifications for order confirmation and updates.
- User review and rating system.
- AI-based personalized product recommendations.

## 🤝 Contributors
- **Yatharth Verma (B22CS064)**: User Management and Product Management modules.
- **Rhythm Baghel (B22CS042)**: Shopping Cart, Order Processing, and Product Management.
- **Souvik Maji (B22CS089)**: Database configuration, Admin Panel, and Shopping Cart.

For more details and source code, visit the [GitHub Repository](https://github.com/RHYTHM2405/E-Commerce_DBMS).

---
