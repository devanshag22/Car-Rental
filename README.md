# Car Rental System
This repository contain codebase for the assignment of CS253 requiring to create terminal based car rental system

This is an implementation of car rental system

It holds Customers, Employees, Cars and a Manager with credentials
username: admin
password: admin

other than that there are 10 cars, 5 customers, 5 employees
You can login in as manager and view all the details about all the customers

Car is rented for 7 days and due date is automatically set to be 7 days after renting it
failure to return it will impose a per day basis fine

for testing purpose, you may uncomment the part of one day and change it to 30sec instead of normal 86400
Make sure to keep in mind that previously set due date may cause some errors if returned with different settings(30 sec) due large difference in magnitude

The system is designed to handle all string format inputs and can't handle special inputs like Ctrl+Z,etc.
