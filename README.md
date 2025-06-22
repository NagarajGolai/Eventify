# Eventify

**Eventify** is an event management web application designed to help users create, manage and browse upcoming events with ease. The platform allows event organizers to publish events and attendees to discover and register for them.

[![🌐 Visit Eventify](https://img.shields.io/badge/Live_Site-Visit_Eventify-brightgreen?style=for-the-badge)](https://eventify.pythonanywhere.com)
---

## 🔧 Tech Stack

- Python 3.x
- Django
- HTML/CSS/JavaScript
- SQLite3 (default) or PostgreSQL (for production)
- Bootstrap (optional for UI styling)

---

## 🚀 Features

- User authentication (signup/login/logout) with email verification
- Create and manage events
- RSVP and registration system
- Categorized event listings
- Admin dashboard for moderation
- Mobile-responsive UI
- 🎟️ Ticket generation with unique QR codes upon RSVP to an event
- 📧 Email ticket delivery after RSVP confirmation
- 🔐 Email verification required during user signup


---
## 📦 Installation

### **1. Clone the Repository**

```bash
git clone https://github.com/NagarajGolai/Eventify.git
cd EM
```
### **or**
### Download the zip file and :
```bash
cd your/path/to/the/zip/file
unzip EM.zip
```

### **2. Create a virtual environment as the sibling of EM folder**
#### Can work without virtual environment too
```bash
python -m venv venv
source venv/bin/activate        # For Linux/macOS
venv\Scripts\activate           # For Windows
```
### **4. Apply Migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

### **5. Create Superuser (Admin Access)**
```bash
python manage.py createsuperuser
```

### **6. Run the Development Server**
```bash
python manage.py runserver
```
### **7.Then open:** 
```bash 
http://127.0.0.1:8000
```
## Ready to go

---
---
---
---

## 🔗 Links

[![🌐 Visit Eventify](https://img.shields.io/badge/Live_Site-Visit_Eventify-brightgreen?style=for-the-badge)](https://eventify.pythonanywhere.com)

[![💻 GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](https://github.com/NagarajGolai/)

[![👔 LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](www.linkedin.com/in/nagarajgolai)
