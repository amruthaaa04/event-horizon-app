#  Event Horizon – Event Management & Booking Web App

Event Horizon is a modern Flask web application that allows users to browse events, view event details, and book tickets.  
Admins can create, edit, and delete events with a full admin dashboard.

---

##  Features

### 👤 User Features
- Register / Login / Logout
- View all events
- View event details
- Book events

### 🛡️ Admin Features
- Create events
- Edit events
- Delete events
- View all users & bookings

###  UI Features
- Modern Bootstrap UI
- Dark/Light mode theme
- Responsive layout

---

##  Technologies Used
- Python
- Flask
- SQLite
- HTML & CSS
- Bootstrap 5

---

## 📦 Installation

```bash
git clone https://github.com/amruthaaa04/event-horizon-app.git
cd event-horizon-app
pip install -r requirements.txt
python app.py


## 📁 Project Structure

event-horizon-app/
│── app.py # Main Flask application
│── app.db # SQLite database (auto-created)
│── requirements.txt # Python dependencies
│── README.md # Project documentation
│
├── templates/ # HTML templates
│ │── base.html
│ │── index.html
│ │── login.html
│ │── register.html
│ │── dashboard.html
│ │── admin_dashboard.html
│ │── event_detail.html
│ │── admin_create_event.html
│ │── admin_edit_event.html
│
├── static/ # Static assets
│ ├── css/
│ ├── js/
│ └── uploads/ # Event images
