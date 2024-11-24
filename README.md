 
---

# StudyBud  

StudyBud is a Django-based web application designed to help students create study groups, manage schedules, and communicate effectively within the group through messaging.  

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![Django](https://img.shields.io/badge/Django-4.x-green)  
![License](https://img.shields.io/badge/License-MIT-brightgreen)  

---

## Table of Contents  
- [Features](#features)  
- [Screenshots](#screenshots)  
- [Setup Instructions](#setup-instructions)  
  - [1. Clone the Repository](#1-clone-the-repository)  
  - [2. Create a Virtual Environment](#2-create-a-virtual-environment)  
  - [3. Activate the Virtual Environment](#3-activate-the-virtual-environment)  
  - [4. Install Dependencies](#4-install-dependencies)  
  - [5. Apply Database Migrations](#5-apply-database-migrations)  
  - [6. Create a Superuser](#6-create-a-superuser)  
  - [7. Run the Development Server](#7-run-the-development-server)  
  - [Access the Admin Panel](#access-the-admin-panel)  
- [Technologies Used](#technologies-used)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features  

- **Study Group Management:** Create and manage study groups.  
- **Scheduling:** Plan and track study sessions.  
- **Real-Time Messaging:** Communicate in real-time with group members.  
- **Admin Panel:** Easy-to-use Django admin interface for managing users, study groups, and messages.  
- **Responsive Design:** User-friendly interface designed with Bootstrap for mobile and desktop compatibility.  

---

## Screenshots  

### Home Page  
![Home Page](StudyBud/project_images/Homepage.png) 

### Login Page  
![Login Page](screenshots/login_page.png)  

### Registration Page  
![Registration Page](screenshots/registration_page.png)  

### Create Room Page  
![Create Room Page](screenshots/create_room.png)  

### Profile Page  
![Profile Page](screenshots/profile_page.png)  

### Room Page  
![Room Page](screenshots/room.png)  

### Edit Profile Page  
![Edit Profile Page](screenshots/edit_profile.png)  

---

## Setup Instructions  

Follow these steps to set up the application on your local system:  

### 1. Clone the Repository  
Clone the repository to your local machine using the following command:  

```bash  
git clone https://github.com/shivnandk/StudyBud.git  
cd StudyBud  
```  

### 2. Create a Virtual Environment  
Create a virtual environment to isolate dependencies (recommended).  

**On Windows:**  
```bash  
python -m venv env  
```  

**On macOS/Linux:**  
```bash  
python3 -m venv env  
```  

### 3. Activate the Virtual Environment  
Activate the virtual environment you just created.  

**On Windows:**  
```bash  
.\env\Scripts\activate  
```  

**On macOS/Linux:**  
```bash  
source env/bin/activate  
```  

### 4. Install Dependencies  
Install the required Python packages listed in the `requirements.txt` file:  

```bash  
pip install -r requirements.txt  
```  

### 5. Apply Database Migrations  
Apply migrations to set up the database schema:  

```bash  
python manage.py migrate  
```  

### 6. Create a Superuser  
Set up a superuser account to access the admin panel:  

```bash  
python manage.py createsuperuser  
```  

Follow the prompts to provide the username, email, and password.  

### 7. Run the Development Server  
Start the Django development server:  

```bash  
python manage.py runserver  
```  

The application will be accessible at:  
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)  

### Access the Admin Panel  
Visit the admin panel at:  
[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)  
Log in using the superuser credentials you created.  

---

## Technologies Used  

- **Django**: High-level Python web framework.  
- **Django Channels**: Real-time communication (WebSockets) for messaging.  
- **Django Rest Framework**: For building APIs (if needed for mobile apps).  
- **Bootstrap**: For front-end design and layout.  
- **Pillow**: Python Imaging Library for handling image files.  
- **Celery**: For handling asynchronous tasks like email notifications.  

---

## Contributing  

We welcome contributions to improve StudyBud! Here's how you can contribute:  

1. Fork the repository on GitHub.  
2. Create a new branch for your feature or fix:  
   ```bash  
   git checkout -b feature-name  
   ```  
3. Make your changes and commit them:  
   ```bash  
   git commit -am 'Add new feature'  
   ```  
4. Push your branch to GitHub:  
   ```bash  
   git push origin feature-name  
   ```  
5. Open a Pull Request on the main repository.  

---

## License  

This project is licensed under the [MIT License](LICENSE).  

Feel free to star ⭐ the repository if you find this project useful!  

---

Replace the placeholder paths for screenshots (e.g., `screenshots/homepage.png`) with the correct relative paths if necessary. Ensure that your screenshots are in the `screenshots` directory, which is in the same level as your README file.
