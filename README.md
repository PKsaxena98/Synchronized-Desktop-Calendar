# Synchronized-Desktop-Calendar
A desktop calendar application built with Python, Tkinter, SQLite, and XML for event synchronization. It allows users to:

✔ Register & Login
✔ Add personal events with start and end times
✔ Share events globally and export shared events as XML
✔ View events stored locally in an SQLite database

📌 Features
✅ User Authentication (Register/Login)

✅ Event Management

Add Events

Mark Events as Shared

✅ Export Shared Events to XML

✅ Lightweight & Works Offline

✅ Simple GUI built with Tkinter

✅ SQLite Database Integration

🛠 Tech Stack
Language: Python 3.x

GUI: Tkinter, Tkcalendar

Database: SQLite

Data Exchange: XML

Modules:

bash
Copy
Edit
tkinter, tkcalendar, sqlite3, xml.etree.ElementTree

 How to Run
✅ 1. Install Dependencies
bash
Copy
Edit
pip install tk tkcalendar
✅ 2. Run the Notebook
Open calendar_app.ipynb in Jupyter Notebook or VS Code

Run all cells

✅ 3. Use the Application
Register a user → Click Register

Login with the same user → Click Login

Add Event

Enter Title

Start & End Time (Format: YYYY-MM-DD HH:MM)

(Optional) Check Share Event

Export Shared Events → Creates shared_calendar.xml in your folder

📦 Generated Files
Database: calendar.db → Stores users and events

XML File: shared_calendar.xml → Stores globally shared events for synchronization
