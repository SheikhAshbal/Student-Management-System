# Student Management System
This is a simple student management system built using Python, Tkinter, and MySQL. It allows users to add, view, update, and delete student records.<br>
<h1>Create a Database and One Table</h1>
<h6>Create a database with this name: `student_management`</h6>
Create a table “student_register” under the “student_management” database.<br>
create table student_register(
	f_name VARCHAR(50) NOT NULL,
	l_name VARCHAR(50) NOT NULL,
	course VARCHAR(30) NOT NULL,
	subject VARCHAR(50) NOT NULL,
	year Int(10) NOT NULL,
	age Int(10) NOT NULL,
	gender char(10) NOT NULL,
	birth DATE NOT NULL,
	contact VARCHAR(15) NOT NULL,
	email VARCHAR(100) NOT NULL,
	PRIMARY KEY ( contact )
);
<h2>Features</h2>
Add New Student: Allows adding new student details such as first name, last name, course, subject, year, age, gender, birthday, contact number, and email.<br>
View Details: Displays detailed information about a student based on their contact number.<br>
Update: Allows updating student details based on their contact number.<br>
Delete: Deletes a student record based on their contact number.<br>
Clear: Clears the screen to enter new data or perform other operations.<br>
Exit: Closes the application.<br>
<h2>Requirements</h2>
Python 3.x<br>
Tkinter (Python GUI toolkit)<br>
MySQL database<br>
MySQL Connector/Python library (pymysql)<br>
Setup<br>
Install Python from python.org.<br>
Install Tkinter using pip install tk or pip install tkinter (depending on your Python version).<br>
Install MySQL and create a database named student_db.<br>
Create a table named student_register with columns f_name, l_name, course, subject, year, age, gender, birth, contact, and email.<br>
<h2>Usage</h2>
Clone this repository.<br>
Update credentials.py with your MySQL database credentials.<br>
Run student_management.py to start the application.<br>
Use the buttons to perform different operations such as adding, viewing, updating, and deleting student records.