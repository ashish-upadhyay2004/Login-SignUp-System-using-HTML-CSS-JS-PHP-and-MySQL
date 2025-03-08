**# Login/SignUp System using HTML, CSS, JS, PHP, and MySQL**

## **Description**
This project provides a simple Login and Signup system with database connectivity using **HTML, CSS, JavaScript, and PHP**. The system validates user credentials by checking the entered email and password against the database and allows new users to register securely. It includes a frontend built with **HTML, CSS, and JavaScript** and a backend implemented using **PHP and MySQL**.

### **Features**
- User Registration (SignUp)
- User Authentication (Login)
- Secure Password Hashing
- Database Connectivity with MySQL
- User Session Management
- Basic Frontend Styling with HTML & CSS
- JavaScript for Client-side Validation

## **Technologies Used**
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** MySQL

## **Installation & Setup**
1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/yourrepository.git
   cd yourrepository
   ```
2. **Setup Database**
   - Create a database (e.g., `user_db`)
   - Import the `database.sql` file provided in the repository
3. **Configure Database Connection**
   - Open `config.php`
   - Set your database credentials:
     ```php
     <?php
     $host = "localhost";
     $user = "root";
     $password = "";
     $dbname = "user_db";
     $conn = new mysqli($host, $user, $password, $dbname);
     if ($conn->connect_error) {
         die("Connection failed: " . $conn->connect_error);
     }
     ?>
     ```
4. **Run the Project**
   - Start a local server using XAMPP or WAMP
   - Place the project folder in `htdocs`
   - Open `http://localhost/yourrepository/`

## **Usage**
- **Sign Up:** New users can register using their email and password.
- **Login:** Registered users can log in to access the system.
- **Logout:** Users can log out securely.

## **Folder Structure**
```
/yourrepository
│── /css        # Stylesheets
│── /js         # JavaScript files
│── /php        # PHP scripts (login.php, signup.php, config.php)
│── /database   # SQL files
│── index.html  # Homepage
│── README.md   # Documentation
```

## **License**
This project is open-source and available under the MIT License.

---
**Contributions & Issues:** Feel free to contribute or raise issues for improvements!

### **Author**
[ASHISH UPADHYAY] - GitHub: (https://github.com/ashish-upadhyay2004)

