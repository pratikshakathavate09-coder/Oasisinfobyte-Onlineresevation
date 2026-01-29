# Oasisinfobyte-Onlineresevation
# 🚆 Railway Reservation System

A console-based Java application that simulates a basic railway ticket reservation system.
The system allows an admin user to **log in**, **book train tickets**, and **cancel tickets** using a generated PNR number.

---

## 📌 Features

* Admin login authentication
* Ticket booking with passenger details
* Automatic PNR generation
* Predefined Express trains with names
* Predefined destinations
* Ticket cancellation using PNR
* In-memory data storage using `HashMap`

---

## 🚄 Express Trains Available

| Train Number | Train Name          |
| ------------ | ------------------- |
| 101          | Deccan Express      |
| 102          | Intercity Express   |
| 103          | Maharashtra Express |
| 104          | Sahyadri Express    |
| 105          | Konkan Express      |

---

## 🌍 Destinations Supported

* Pune
* Mumbai
* Nagpur
* Nashik
* Kolhapur

---

## 🛠 Technologies Used

* Java (JDK 8 or higher)
* Core Java concepts

  * Classes & Objects
  * Methods
  * Switch Case
  * Exception Handling
  * Collections (`HashMap`)
  * Scanner

---

## 🔐 Login Credentials

```
Login ID : admin
Password : 1234
```

---

## ▶ How to Run the Program

### Compile

```bash
javac RailwayReservationApp.java
```

### Run

```bash
java RailwayReservationApp
```

---

## 📋 Application Flow

1. User logs in using admin credentials
2. Main menu appears

   * Book Ticket
   * Cancel Ticket
   * Exit
3. Booking generates a unique PNR
4. Cancellation removes ticket using PNR

---

## 🖥 Sample Output

### 🔑 Login Screen

```
===== Railway Reservation System =====
Enter Login ID: admin
Enter Password: 1234
Login Successful!
```

---

### 📋 Main Menu

```
1. Book Ticket
2. Cancel Ticket
3. Exit
Enter your choice: 1
```

---

### 🎟 Ticket Booking Output

```
Enter Passenger Name: Pratiksha
Enter Age: 21

Available Trains:
101 - Deccan Express
102 - Intercity Express
103 - Maharashtra Express
104 - Sahyadri Express
105 - Konkan Express

Select Train Number: 103
Enter Source: Pune
Enter Destination: Mumbai
Select Class (Sleeper/AC): AC

Ticket Booked Successfully!
PNR Number: 45872
```

---

### ❌ Ticket Cancellation Output

```
Enter PNR Number: 45872

Passenger Name: Pratiksha
Train: Maharashtra Express
From Pune To Mumbai

Confirm Cancellation (Y/N): Y
Ticket Cancelled Successfully.
```

---

## ⚠ Important Notes

* Data is stored only during program execution
* No database is used
* Data is lost once the program stops
* Designed for academic demonstration

---

## 👩‍💻 Author

**Github:- @pratikshask09**

Third Year Engineering Student
Java Mini Project

---

## ✅ Conclusion

This Railway Reservation System demonstrates the working of a basic reservation system using Java. It helps understand authentication, user input handling, collections, and control flow in a real-world scenario.

---

 
