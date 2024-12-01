# 📚 Read Right! Bookstore System

Read Right! is a clean and efficient bookstore system built with PHP and MySQL. This straightforward application provides essential book shopping features for customers and a simple management interface for administrators.

## ✨ Features

### Customer Features
- 🔐 User authentication (Register/Login)
- 📚 Browse extensive book catalog
- 🔍 Search functionality
- 🛒 Shopping cart management
- 💳 Checkout process
- 📦 Order tracking
- 📞 Contact support
- 👤 User profile management

### Admin Features
- 📊 Dashboard overview
- 📚 Product management (Add/Edit/Delete books)
- 👥 User management
- 📦 Order management
- 📬 Contact message management
- 📈 Sales tracking

## 🚀 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Additional:** Responsive design for mobile compatibility

## 💻 Installation & Setup Guide

1. **Prerequisites**
   - PHP 7.4 or higher
   - MySQL 5.7 or higher
   - Web server (XAMPP, WAMP, or MAMP recommended for local development)
   - Git (for cloning the repository)

2. **Local Development Setup**
   ```bash
   # 1. Install XAMPP/WAMP/MAMP
   # Download and install from their official websites:
   # XAMPP: https://www.apachefriends.org/
   # WAMP: https://www.wampserver.com/
   # MAMP: https://www.mamp.info/

   # 2. Clone the repository into your web server's directory
   # For XAMPP: C:/xampp/htdocs/
   # For WAMP: C:/wamp64/www/
   cd your-web-server-directory
   git clone https://github.com/Khadalicioso/read_right.git

   # 3. Navigate to project directory
   cd read_right
   ```

3. **Database Setup**
   ```bash
   # 1. Open phpMyAdmin
   # XAMPP: http://localhost/phpmyadmin
   # WAMP: http://localhost/phpmyadmin (username: root, password: blank by default)

   # 2. Create a new database named 'shop_db'
   
   # 3. Import the database structure
   # In phpMyAdmin:
   # - Select the 'shop_db' database
   # - Click 'Import' tab
   # - Choose the file: shop_db.sql from the project
   # - Click 'Go' to import
   ```

4. **Configuration**
   - Open `config.php`
   - Update the database connection details:
     ```php
     $conn = mysqli_connect('localhost','root','','shop_db');
     ```

5. **Running the Application**
   - Start your local server (XAMPP/WAMP/MAMP)
   - Open your web browser
   - Visit: `http://localhost/read_right`

6. **Default Login Credentials**
   ```
   Admin Panel:
   URL: http://localhost/read_right/admin_page.php
   Username: admin@gmail.com
   Password: 111

   Test User Account:
   Username: user@gmail.com
   Password: 111
   ```

7. **Troubleshooting**
   - Ensure your web server (Apache) and MySQL services are running
   - Check if the database connection details in `config.php` match your setup
   - Verify that all files have proper read permissions
   - Clear your browser cache if you encounter display issues

## 📱 Usage

### Customer Area
1. Register/Login to your account
2. Browse books in the shop section
3. Add desired books to cart
4. Proceed to checkout
5. Track your orders

### Admin Area
1. Access admin panel through `/admin_page.php`
2. Default admin credentials:
   - Username: admin
   - Password: admin123
3. Manage products, orders, and users

## 🔒 Security Features

- Password hashing
- Session management
- SQL injection prevention
- XSS protection

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/Khadalicioso/read_right/issues).

## 📧 Contact

For support or queries, please reach out through the contact form on the website.

---
Made with ❤️ by [Khadalicioso](https://github.com/khadalicioso)
