📚 Student Record Management System (Python CLI)

A simple Command Line Interface (CLI) based Student Record Management System built with Python that allows users to:

➕ Add student records

📄 View all students

✏️ Update student details

❌ Delete student records

💾 Store data persistently using a JSON file

This project is ideal for beginners learning Python, file handling, and CRUD operations.

🚀 Features

Menu-driven CLI interface

Add student with:

Unique Student ID

Name

Marks for 4 subjects (Bengali, Math, Python, Java)

View all stored student records

Update existing student details

Delete student by ID

Automatic data persistence using students_record.json

Error handling for invalid inputs

🛠️ Tech Stack

Language: Python 3

Storage: JSON file

Concepts Used:

Classes & Objects

File Handling

Exception Handling

CRUD Operations

📂 Project Structure
student-record-system/
│
├── student_record_system.py     # Main application file
├── students_record.json         # Auto-created data file (after first run)
└── README.md

▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/your-username/student-record-system.git
cd student-record-system

2️⃣ Run the program
python student_record_system.py

🧾 Menu Options
1. Add Student
2. View All Students
3. Update Student
4. Delete Student
5. Exit

💡 Example Workflow

Choose option 1 → Enter name → Enter unique ID → Enter marks

Choose option 2 → View all stored records

Choose option 3 → Update student details

Choose option 4 → Delete a student by ID

Choose option 5 → Save and exit

🔐 Data Storage

All records are stored in:

students_record.json


This file is automatically created when the program runs for the first time.

⚠️ Known Limitations / Improvements

Input validation can be enhanced

Marks input format needs better parsing

Search functionality exists but is not linked to the menu

No percentage/grade calculation (can be added)

No GUI (CLI only)

🧠 Future Enhancements

Add search by student ID

Calculate total, percentage, and grade

Add subject-wise validation

Convert to GUI using Tkinter / PyQt

Migrate storage to SQLite or PostgreSQL

Add unit tests

🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

📜 License

This project is open-source and available under the MIT License.

👩‍💻 Author

Sangita Bera
Python Developer | Beginner Projects
