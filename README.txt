STUDENT MANAGEMENT SYSTEM — JAVA SWING + SQLITE

Features:
- Add, update, delete, and search student records
- Save subject marks (0–100)
- Calculate total, percentage, grade, and PASS/FAIL
- Automatically creates students.db and inserts the five sample records on first run

Requirements:
- Java JDK 11 or later
- Apache Maven
- Internet connection on the first run so Maven can download SQLite JDBC

Run on Windows:
1. Extract this ZIP.
2. Open Command Prompt in the StudentManagementSystem folder.
3. Run: mvn clean compile exec:java -Dexec.mainClass=StudentManagementSystem

A database named students.db is created in the folder where you run the command.
Grade rules follow your SQL: A+ >= 90, A >= 80, B >= 70, C >= 60, D >= 50, otherwise F.
PASS requires at least 33 marks in every subject.
