# 👥 Employee Management System with QR Code Integration 📱

## 🎯 About the Project
The **Employee Management System** is a web-based application designed to simplify employee data management for small and medium-sized businesses. It includes features for adding, updating, and deleting employee records manually or through QR code scanning. With a user-friendly interface and responsive design, the system ensures seamless operation across all devices.

## ⭐ Features

### 1. 📝 Manual Employee Management
* Add, view, update, and delete employee details
* Intuitive modals for input and action confirmation

### 2. 📸 QR Code Scanning
* Add employee details by scanning a QR code with your device's camera
* Leveraging the `html5-qrcode` library for real-time QR scanning

### 3. 🎨 Interactive User Interface
* Modern design with hover effects, buttons, and responsive layouts
* Enhanced table view for better readability and sorting of data

### 4. ⚡ AJAX Integration
* Real-time employee addition and deletion without page reloads

### 5. 📱 Responsive Design
* Works perfectly on desktops, tablets, and mobile devices

## 🛠️ Technologies Used

### Frontend
* HTML5
* CSS3
* JavaScript
* QR Scanner: `html5-qrcode` library

### Backend
* PHP
* MySQL

### Other Tools
* AJAX for asynchronous data handling

## 💻 Installation and Setup

### 1. Clone the Repository
```bash
git clone URL_TO_THIS_PROJECT_REPO
```

### 2. Set Up Database
* Import the provided `employee_management.sql` file into your MySQL server
* Ensure the database name is `employee_management`

### 3. Configure Database Connection
* Update the `db.php` file with your database credentials:
```php
$servername = "localhost";
$username = "YOUR_DATABASE_USERNAME";
$password = "YOUR_DATABASE_PASSWORD";
$dbname = "employee_management";
```

### 4. Start a Local Server
* Use software like **XAMPP** or **WAMP** to host the project locally
* Place the project folder in the `htdocs` directory

### 5. Access the Application
```
http://localhost/employee-management/
```

## 📖 Usage Instructions

### 👨‍💼 Adding Employees
* **Manually**:
  * Click on the "Add New Employee" button
  * Fill out the form and submit the details
* **Using QR Code**:
  * Click on the "Add Employee with QR" button
  * Scan the QR code containing employee details
  * The details will be added automatically

### 👀 Viewing Employees
* The employee table displays all records
* Hover over rows to highlight them for better visibility

### ❌ Deleting Employees
* Click the "Delete" button corresponding to the employee record
* Confirm the action, and the record will be deleted in real-time

## 🎥 Video Demonstration
Watch the demonstration video [here](https://www.linkedin.com/posts/kavishnu-g-1a8612288_php-javascript-mysql-activity-7247944685992697857-FaY6?utm_source=share&utm_medium=member_android)

## 🤝 Contributing
Contributions are welcome! If you have suggestions for improving the project or adding new features:

1. Fork the repository
2. Create a new branch:
```bash
git checkout -b feature/YourFeatureName
```
3. Commit your changes:
```bash
git commit -m "Add your message here"
```
4. Push to the branch:
```bash
git push origin feature/YourFeatureName
```
5. Open a pull request

## 📄 License
This project is licensed under the **MIT License**. See the LICENSE file for details.
