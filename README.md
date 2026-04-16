# 🎓 SmartCampus Management System (Java)

## 📌 Problem Statement

This project is developed as part of the **Final Java Assessment (GNC College)**.
The goal is to build a **Smart Campus Management System** that manages students, courses, and enrollments efficiently using core Java concepts.

---

## 🚀 Features

### 👨‍🎓 Student Management

* Add student details (ID, Name, Email)
* View all students

### 📚 Course Management

* Add course details (Course ID, Name, Fee)

### 📝 Enrollment System

* Enroll students in multiple courses
* One-to-many relationship using `HashMap`
* View enrollments

### ⚠️ Exception Handling

* Handles invalid input using `try-catch`
* Custom exception implemented for invalid operations

### ⚙️ Multithreading

* Enrollment processing simulated using threads
* Demonstrates asynchronous execution

### 💾 File Handling (Bonus)

* Save student data to file
* Read stored data from file

---

## 🛠️ Technologies Used

* Java (Core Java)
* OOP Concepts
* Collections (`ArrayList`, `HashMap`)
* Exception Handling
* Multithreading
* File Handling

---

## 🧠 Concepts Covered

* Classes & Objects
* Constructors
* Encapsulation
* Collections Framework
* Custom Exceptions
* Threading (`Thread` class)
* File I/O (`ObjectOutputStream`, `ObjectInputStream`)

---

## 📋 Menu Options

1. Add Student
2. Add Course
3. Enroll Student
4. View Students
5. View Enrollments
6. Process Enrollment (Thread)
7. Exit

---

## 🖥️ Sample Output

```
1. Add Student
Enter ID: 101
Enter Name: Satyam
Student Added!

3. Enroll Student
Enter Student ID: 101
Enter Course ID: 1
Processing enrollment...
Enrollment Completed!
```

---

## 📂 Project Structure

```
SmartCampus/
│── Main.java
│── Student.java
│── Course.java
│── README.md
```

---

## ⚡ Unique Feature Added

* Asynchronous enrollment processing using threads
* Custom exception for invalid inputs

---

## 📸 Screenshots

(Add screenshots of your program output here)

---

## 📦 How to Run

1. Compile:

```
javac Main.java
```

2. Run:

```
java Main
```

---

## 🧪 MCQ Answers (Conceptual)

1. **Collections Design:**
   ✅ B. HashMap<Student, ArrayList<Course>>

2. **Exception Handling:**
   ✅ C. Custom Exception

3. **Multithreading:**
   ✅ B. Use synchronized block

4. **OOP Design:**
   ✅ B. Interface

---

## 📌 Conclusion

This project demonstrates how Java can be used to build a real-world system using OOP, collections, exception handling, and multithreading.

---

## 👨‍💻 Author

**Satyam Shukla**

---

⭐ If you like this project, give it a star!
