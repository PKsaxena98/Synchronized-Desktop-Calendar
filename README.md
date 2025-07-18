# Synchronized-Desktop-Calendar
A desktop calendar application built with Python, Tkinter, SQLite, and XML for event synchronization. It allows users to:

- Register & Login
- Add personal events with start and end times
- Share events globally and export shared events as XML
- View events stored locally in an SQLite database

# Features
- User Authentication (Register/Login)
- Event Management
- Add Events
- Mark Events as Shared
- Export Shared Events to XML
- Lightweight & Works Offline
- Simple GUI built with Tkinter
- SQLite Database Integration

# Tech Stack

- Language: Python 3.x
- GUI: Tkinter, Tkcalendar
- Database: SQLite
- Data Exchange: XML

# Modules:
tkinter, tkcalendar, sqlite3, xml.etree.ElementTree

# How to Run
1. Install Dependencies:
    - pip install tk tkcalendar

2. Run the Notebook
    - Open calendar_app.ipynb in Jupyter Notebook or VS Code

3. Use the Application
    - Register a user → Click Register
    - Login with the same user → Click Login
    - Add Event
      - Enter Title
      - Start & End Time (Format: YYYY-MM-DD HH:MM)
      - (Optional) Check Share Event
    - Export Shared Events → Creates shared_calendar.xml in your folder

# Generated Files

- Database: calendar.db → Stores users and events

- XML File: shared_calendar.xml → Stores globally shared events for synchronization

# Screenshots

### Login Screen
<img width="1366" height="726" alt="2025-07-19" src="https://github.com/user-attachments/assets/33d1f35a-e9c1-43e9-ac83-fded29131d1f" />
<img width="1366" height="723" alt="2025-07-19 (3)" src="https://github.com/user-attachments/assets/090101fc-4c2e-41b8-b69f-ad3992bf0e18" />
### Dashboard
<img width="1366" height="722" alt="2025-07-19 (1)" src="https://github.com/user-attachments/assets/1c13a0e7-41bc-4bc1-9ae3-0b4cb4f78a93" />
<img width="1351" height="692" alt="2025-07-19 (5)" src="https://github.com/user-attachments/assets/08f1c773-3f83-4613-9b0f-787145725331" />
<img width="1353" height="687" alt="2025-07-19 (4)" src="https://github.com/user-attachments/assets/40b2ff17-4503-41f1-91d9-bef7d108a302" />



