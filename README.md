# Room_Allotment
Simple Python hostel room allocation system for managing student room assignments.
# Room Allotment System (Python)

## 📌 Project Description

The Room Allotment System is a console-based Python application designed to allocate hostel rooms to students.  

The system assigns available rooms automatically and keeps track of occupied rooms using Python dictionaries and sets.

---

## 🚀 Features

- Allocate rooms to students
- Automatically assign first available room
- Prevent over-allocation
- Display final room allotment
- Show list of occupied rooms
- Menu-free simple execution

---

## 🛠 Technologies Used

- Python 3
- Dictionary data structure
- Set data structure
- Loops and conditionals

---

## 📂 How the System Works

- Rooms are stored in a dictionary:
  - Key → Room Number
  - Value → Student Name (or None if empty)
  
- Occupied rooms are tracked using a set.

- The program:
  1. Takes number of students as input
  2. Assigns rooms one by one
  3. Stops if all rooms are occupied
  4. Displays final allotment list

---

## ▶️ How to Run the Program

1. Make sure Python is installed.
2. Save the file as:
   room_allotment.py
3. Open terminal or command prompt.
4. Run:

   python room_allotment.py

---

## 📸 Example Output

```
Enter the number of students: 2
Enter the name of the student: Rahul
Rahul has been allotted room number 101
Enter the name of the student: Sneha
Sneha has been allotted room number 102
```

---

## ⚠️ Note

- Maximum capacity is 10 rooms (101–110).
- Data is stored temporarily (no database used).
- This is a beginner-friendly Python mini project.

---

## 👩‍💻 Author

Sneha Barik  
Python Mini Project
