# EventsWale 
#### A Smart Platform for Managing Educational and College Events


## Authors

- [@Lovish Mehra](https://github.com/Lovish-Mehra-06)
- [@KS Nithin](https://github.com/Nithin0620)
- [@Nitin Kumar](https://github.com/nitinkumarKN)
- [@Anuraj Upadhyay](https://github.com/Anrj007)


## Table of Contents
- [Introduction](##introduction)
- [Main Features](#Main-Features)
- [Additional Features](#Additional-Features)
- [Technical Stack](#technical-stack)
- [Installation](#installation)
- [Troubleshooting](#Troubleshooting)
- [Contact](#contact)

## Introduction
EventsWale is an user platform designed to make the organization of events such, as seminars and workshops more straightforward and hassle free for both the organizers and attendees involved in the process.It aims to address the challenges that arise during event planning and execution while enhancing efficiency throughout the experience.EventsWale enables organizers to plan and promote events while ensuring that attendees have an enjoyable time.Connecting educators with students and professionals alike fosters an environment that emphasizes growth and knowledge exchange, within a community. 


Managing educational events like seminars, workshops, and hackathons can be challenging for organizers and attendees alike. Organizers often struggle to promote their events, while attendees find it hard to locate events that match their interests and schedules. Furthermore, tracking attendance, accessing certificates, and building a professional profile can become disorganized.

## Main Features
- **Event Management for Organizers**: Easily input event details, including name, description, date, time, location, type (seminar, hackathon, workshop), domain (IoT, AI, Web3, Blockchain), target audience, ticket availability, and registration links.
- **User-Friendly Event Browsing**: Users can effortlessly browse and filter events based on their interests, type, domain, and location.
- **Simplified Sign-Ups**: Event sign-ups are streamlined through ticket purchases or form submissions.
- **Tracking and Portfolio Features**: Users can track attended events, competition rankings, and store certificates. Create portfolios to showcase skills and achievements.
- **Notifications and Insights**: Additional features, such as email reminders and event insights, keep users connected.

## Additional Features
- Light/dark mode toggle
- Live previews
- Fullscreen mode
- Cross platform
- Browse and filter events by various criteria
- User registration and login using OAuth 2.0
- Event sign-ups and ticket purchasing
- Attendance tracking and certificate management
- Portfolio creation for skills and achievements
- Email reminders for upcoming events

## Technical Stack
- **Frontend**: HTML, CSS, JavaScript, React.js
- **Backend**: Django (Python)
- **Database**: MySQL
- **Authentication**: OAuth 2.0
- **Additional Libraries**: Material-UI (and more)
- **Version Control**: GitHub

## Installation
To set up the project locally and start using **EventsWale**, follow these steps:

### Prerequisites
Before starting, ensure that you have the following installed on your system:
- **Node.js** (v14 or higher) and **npm** (v6 or higher): [Download Node.js](https://nodejs.org/en/)
- **Python** (v3.8 or higher): [Download Python](https://www.python.org/downloads/)
- **MySQL**: [Install MySQL](https://www.mysql.com/downloads/)
- **Git**: [Install Git](https://git-scm.com/)

### Step 1: Clone the Repository
Clone the repository from GitHub to your local machine:

```bash
git clone https://github.com/yourusername/EventsWale.git
cd EventsWale


1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/EventEase.git
   cd EventEase
   ```
   
### Step 2: Set Up the Backend (Django)

Navigate to the backend directory:
```bash
cd backend 
```

Create a virtual environment:
```bash
python -m venv env
```

Activate the virtual environment:

On Windows:
```bash
.\env\Scripts\activate
```
On MacOS/Linux:
```bash
source env/bin/activate
```

Install the required Python dependencies:
```bash
pip install -r requirements.txt
```

Set up the database in ```settings.py``` by updating it to your local MySQL configuration:
```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'your_database_name',
        'USER': 'your_mysql_username',
        'PASSWORD': 'your_mysql_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

Run migrations to set up the database schema:
```bash
python manage.py migrate
```
Create a superuser for admin access:
```bash
python manage.py createsuperuser
```
Start the backend server:
```bash
python manage.py runserver
```


### Step 3: Set Up the Frontend (React.js)
Open a new terminal and navigate to the frontend directory:

```bash
cd ../frontend
```
Install the required npm dependencies:

```bash
npm install
```
Start the React development server:

```bash
npm start
```

The frontend will be running at ```http://localhost:1000```.

Step 4: Connecting Frontend to Backend
In your frontend ```.env``` file, set the backend URL for API requests:

```bash
REACT_APP_BACKEND_URL=http://localhost:2000
```
Step 5: Open the Application

- Visit ```http://localhost:1000``` to use the frontend.
- The backend API can be accessed at ```http://localhost:2000```.

## Troubleshooting
Ensure that:

- MySQL is running and accessible.
- You have the correct versions of Node.js and Python installed.
- The Python virtual environment is activated.



## Contact

For any inquiries, feel free to reach out:

Lovish Mehra - lovish06mehra@gmail.com

Project Link: [EventsWale GitHub Repository](https://github.com/Lovish-Mehra-06/EventsWale_Project.git)
