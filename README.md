Medicine Reminder & Prescription Tracker

A simple command-line application to help users save prescriptions, manage medicine schedules, and receive time-based reminders.

📌 Project Overview

This project is a lightweight Python-based tool that allows users to store prescriptions, view or delete them, and get automatic medicine reminders.
It uses JSON storage, a background scheduler, and a CLI interface.

✨ Features

➕ Add prescriptions (name, dosage, times per day)

📄 View all saved prescriptions

❌ Delete prescriptions

⏰ Automatic reminder system that checks every minute

💾 Data stored persistently in JSON format

🧩 Modular and easy-to-extend code

🛠️ Technologies Used

Python 3

json (for data storage)

datetime (for time checking)

time (for scheduler)

os (for directory & file handling)

📂 Folder Structure
project/
│── data/
│   └── prescriptions.json
│── main.py
│── README.md

🚀 How to Run the Project
1. Clone the Repository https://github.com/drishti25boe10074-ai/Repository/blob/main/README.md

2. Navigate to Project Folder
cd medicine-reminder

3. Run the Program 
python main.py Python Medicine Reminder & Prescription_tracker.py 

📝 Usage Instructions
1️⃣ Add Prescription

Enter medicine name

Dosage (ex: 1 tablet)

Reminder times in HH:MM (comma separated)integration

🧪 Testing

Input validation tests

Time-checking functionality

JSON data integrity

Scheduler loop behavior
