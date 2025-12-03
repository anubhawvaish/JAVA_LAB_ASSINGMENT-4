📘 Student Management System – File Handling & Collections (Java)

This project implements a Student Record Management System using Java File Handling and Collections Framework. Student records are stored permanently in a file (students.txt). The system allows adding, viewing, searching, deleting, and sorting student records.

Main class: RecordSystem4

🚀 Features ✔ File Handling

Read data using BufferedReader

Write data using BufferedWriter

Random file access using RandomAccessFile

✔ Collections

Stores students in ArrayList

Uses Iterator for traversal

Sorts records using Comparator

✔ Operations Supported

Add student

View all students

Search student by name

Delete student by name

Sort students by marks

Save and exit

🧩 Class Overview Student

Holds:

Roll number

Name

Email

Course

Marks

FileUtil

Responsible for:

Loading student records from file

Saving updated records

Random access reading

StudentManager

Handles:

Adding students

Viewing all records

Searching

Deleting

Sorting

RecordSystem4 (Main Class)

Runs the menu and controls the entire system.

📂 File Format (students.txt)

Each record is stored as:

rollNo,name,email,course,marks

Example:

101,Rohan,rohan@mail.com,B.Tech,82.5 102,Neha,neha@mail.com,BCA,91.0

▶️ How to Run

Create students.txt in the same directory (empty file is fine).

Save the code in:

RecordSystem4.java

Compile:

javac RecordSystem4.java

Run:

java RecordSystem4

📌 Sample Menu ===== Student File Menu =====

Add Student
View All Students
Search by Name
Delete by Name
Sort by Marks
Save & Exit
🎯 Learning Outcomes

After completing this assignment, you will understand:

File handling in Java

Reading/writing text files

Random access file operations

Collection framework usage

Sorting with Comparator

Iterator traversal

Persistent storage handling

👨‍💻 Author

Your Name Aryaveer Singh 2401010273 B.Tech CSE K.R. Mangalam University
