# 🎉 Event-O-Pedia

Event-O-Pedia is a web-based Sports Event Management System built to simplify the registration, tracking, and certification process for various sports events. The system allows both users and administrators to interact with and manage events efficiently.

---

## 🌐 Website Pages & Features

### 🧑‍💼 Admin Features
- **Admin Dashboard (adminindex):** View and manage events and participants.
- **Create Event (createevent):** Add new sports events.
- **Approve Participants (approveparticipants):** Accept or reject participant requests.
- **Event Status (eventstatus):** Track ongoing and completed events.
- **Certificates (certificates):** Manage and issue certificates to users.
- **Admin Profile (adminprofile):** Edit admin details.
- **Change Password (changepassword):** Update login credentials.

### 👤 User Features
- **Register (register):** New user sign-up.
- **Login (login):** Secure login for users and admins.
- **User Profile (userprofile):** View and edit profile information.
- **User Certificate (usercertificate):** Download event participation certificates.
- **Validate Certificate (validationcertificate):** Confirm authenticity of certificates.

### 📅 Events
- **Events List (events):** View available sports events.
- **Event Status (eventstatus):** See which events are live or completed.

### 📃 Static Pages
- **Home Pages (index1, index2, index3):** Informative landing pages with images and descriptions.
- **About (about):** Learn more about Event-O-Pedia.
- **Contact (contact):** Send feedback or inquiries.
- **Privacy Policy (privacypolicy):** Understand data handling and privacy.
- **References (references):** View acknowledgments or data sources.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP / Django / Node.js *(update depending on what you used)*
- **Database:** MySQL *(or update based on your DB)*

---

## 🗄️ Database

Entity-Relationship diagrams and database tables have been designed to manage:
- User accounts
- Events and status
- Participation
- Certificate generation and validation


---

## 🔒 Security Features

- Password hashing
- Role-based access (Admin vs User)
- Certificate validation

---

## 🖼️ Screenshots

Website screenshots are included in the `/screenshots` folder showing full functionality for:
- Home
- Login/Register
- Admin dashboard
- Event Management
- Certificate management

---

## 🚀 How to Run Locally


# Clone the repository
git clone https://github.com/yourusername/event-o-pedia.git
cd event-o-pedia

# For Python/Django projects
pip install -r requirements.txt
python manage.py runserver

# For PHP projects
Start XAMPP and place files in htdocs/

# Access via
http://localhost:8000/
