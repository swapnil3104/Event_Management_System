# Event_Management_System
This is a Python-based Event Management System application that uses Tkinter for the graphical user interface and SQLite for the database. It allows users to log in, register, and manage events based on their roles (participant, organizer, or admin). The system includes functionalities for adding, viewing, and modifying events with cost estimation based on event type and additional requirements.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________

Features
1. User Roles
Admin: Can view and modify all events.
Organizer: Can add events, calculate costs based on requirements, and view their events.
Participant: Can register and log in to the system.
2. Registration & Login
New users can register with a username, password, email, and contact information.
Users can log in and access role-specific dashboards.
3. Event Management
Add Event: Organizers can create events with details like name, description, date, time, location, type, and requirements (e.g., decoration, food, sound, security).
Cost Estimation: Event costs are calculated dynamically based on the event type and selected requirements.
View & Modify Events: Admins can view all events with details and manage them.
4. Database Integration
All user and event information is stored in an SQLite database.
Data persists between sessions.
