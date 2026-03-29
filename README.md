# Arunika-Outdoor-Mini-APP
This project is a web-based rental management system developed using Flask (Python).  
It is designed to manage equipment rental activities with two user roles: **Admin** and **Renter (User)**.

The application allows renters to manage their rental activities, while admins handle equipment and monitor rental transactions.
The system uses SQLite database integrated with Flask-SQLAlchemy.

---

## Features

### Authentication & Authorization
- User registration with personal data  
- Login and logout system  
- Session-based authentication  
- Role-based access control (Admin & Renter)  

---

### Admin Menu

1. Equipment Management  
   - Add Equipment  
   - Update Equipment  
   - Delete Equipment  

2. Rental Management  
   - View Rental List  
   - Monitor Rental Status (Active, Returned, Cancelled)  

3. Logout  

---

### Renter Menu

1. View Equipment List  
2. Create Rental  
3. Update Rental  
4. Cancel Rental  
5. Return Equipment  
6. View Invoice  
7. View Personal Data  
8. Logout  

---

## How the System Works

The overall workflow is quite straightforward:

- A user opens the application
- Logs in or registers
- Gets redirected based on their role
- Performs actions from their respective menu

Admins manage the system behind the scenes, while renters interact with the rental process directly.

---

## Project Structure

```
project-folder/
│
├── app.py
├── Database.py
├── Equipment_Management.py
├── Rents_Management.py
├── Renter.py
├── Profile.py
├── Invoice.py
├── Main_Menu.py
├── Menu_Auth.py
├── Validators.py
│
├── templates/
├── static/
├── instance/
└── requirements.txt
```
---

## Workflow

Authentication Menu
<img width="4888" height="1707" alt="Authenthication" src="https://github.com/user-attachments/assets/15ef25fc-b012-4e43-a836-b44f651fe661" />

Admin Menu 
<img width="3414" height="2682" alt="admin menu" src="https://github.com/user-attachments/assets/d59ea1fd-b200-4ad5-8ebc-3c9dd7c764f1" />

Renter Menu
<img width="3554" height="2550" alt="renter menu" src="https://github.com/user-attachments/assets/a77d6112-52e9-4553-baf6-5d5018770f91" />

---




