# 🧪 Python Mini Projects – Part 2

### 🗓️ Submission Deadline: 14-June-2025

### 🧑‍🏫 Instructor: Jahanzaib

---

## 📌 Objective

These mini projects build your confidence in solving real-world problems using Python. You'll practice variables, data types, conditionals, loops, and dictionaries—core elements of Python programming.

---

## 🔧 Submission Instructions

You can use **Google Colab** or submit `.py` files in a GitHub repo and share the link on **Google Classroom**.

---

## 🔷 Project 1: Smart ATM Simulator

### 📖 Scenario:

Simulate a basic ATM system for a user to check balance, deposit, or withdraw money after successful login.

### ✅ Requirements:

* Use a dictionary like `{acc_no: {"name": str, "pin": int, "balance": float}}`
* Validate PIN before allowing access
* Menu options:

  1. View Balance
  2. Deposit Money
  3. Withdraw Money (check if enough balance)
  4. Exit

### 💡 Tips:

* Use `input()` to get user actions
* Wrap menu inside a `while True:` loop
* Use a `break` to exit the loop

### 🧪 Expected Output:

```
🏦 Welcome to Python ATM
Enter account number: 1001
Enter PIN: 1234
✅ Login successful!

1. View Balance
2. Deposit
3. Withdraw
4. Exit
Choose option: 1
Current balance: Rs. 5000.0

Choose option: 2
Enter deposit amount: 2000
New balance: Rs. 7000.0

Choose option: 3
Enter withdrawal amount: 3000
Withdrawal successful. New balance: Rs. 4000.0
```

---

## 🔷 Project 2: Movie Ticket Booking System

### 📖 Scenario:

Build a system where users can view movies and book or cancel tickets.

### ✅ Requirements:

* Movie dictionary: `{movie: {showtime: available_seats}}`
* Menu:

  1. View Available Movies
  2. Book Ticket
  3. Cancel Ticket
  4. Show Booking Summary

### 💡 Tips:

* Store bookings as a list of dictionaries
* Decrease available seats on booking; increase on cancellation

### 🧪 Expected Output:

```
🎬 Welcome to Movie Ticket Booking
1. View Movies
2. Book Ticket
3. Cancel Ticket
4. Exit

Choose option: 1
Avengers (6PM): 20 seats
Inception (5PM): 10 seats

Choose option: 2
Enter movie: Avengers
Enter showtime: 6PM
Enter tickets: 3
✅ Booking confirmed for Avengers at 6PM (3 tickets)

Choose option: 4
📄 Booking Summary:
- Avengers | 6PM | 3 tickets
```

---

## 🔷 Project 3: Online Course Enrollment System

### 📖 Scenario:

Allow students to enroll in courses. Each course has limited seats.

### ✅ Requirements:

* Courses stored as: `{course: {"seats": int, "students": [name1, name2...]}}`
* Menu:

  1. View Courses
  2. Enroll Student
  3. Drop Course
  4. View Enrolled Students
  5. Exit

### 💡 Tips:

* Check seat availability before enrollment
* Use `.append()` and `.remove()` on lists

### 🧪 Expected Output:

```
🎓 Welcome to Online Courses
1. View Courses
2. Enroll
3. Drop
4. View Students
5. Exit

Choose option: 1
Python - Seats Left: 3
AI - Seats Left: 2

Choose option: 2
Enter course name: Python
Enter student name: Fatima
✅ Fatima enrolled in Python

Choose option: 4
📘 Enrolled Students in Python: ['Fatima']
```

---

## 🔷 Project 4: Car Rental System

### 📖 Scenario:

Let customers rent and return cars from a small car agency.

### ✅ Requirements:

* Cars stored as: `{car_name: {"available": bool, "renter": str or None}}`
* Menu:

  1. View Available Cars
  2. Rent a Car
  3. Return a Car
  4. View All Rentals
  5. Exit

### 💡 Tips:

* Track availability with a boolean
* Match customer names to rented cars

### 🧪 Expected Output:

```
🚗 Welcome to Car Rental
1. View Cars
2. Rent Car
3. Return Car
4. Rentals

Choose option: 1
Available: Honda Civic, Suzuki Alto

Choose option: 2
Enter car name: Honda Civic
Enter your name: Ahmed
✅ Car rented successfully to Ahmed

Choose option: 4
🔑 Rented Cars:
- Honda Civic -> Ahmed
```

---

## 🔷 Project 5: Daily Expense Tracker

### 📖 Scenario:

Help users track how much they spend daily and in which categories.

### ✅ Requirements:

* Use dictionary: `{date: [{"category": str, "amount": int}, ...]}`
* Menu:

  1. Add Expense
  2. View All Expenses
  3. View by Category
  4. View by Date
  5. Exit

### 💡 Tips:

* Use `input("YYYY-MM-DD")` for date entry
* Use `defaultdict` or check if date exists before appending

### 🧪 Expected Output:

```
📊 Daily Expense Tracker
1. Add Expense
2. View All
3. By Category
4. By Date

Choose option: 1
Enter date (YYYY-MM-DD): 2025-06-01
Enter category: Food
Enter amount: 400
✅ Expense added

Choose option: 3
Enter category: Food
Total spent on Food: Rs. 1200
```

---
