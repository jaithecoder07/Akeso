# AI Daily Energy Coach Platform

An AI-powered web application that helps users track, understand, and improve their daily energy levels using simple inputs like sleep, mood, stress, and activity.

Instead of just showing raw data, the platform provides personalized insights and suggestions to help users improve productivity, lifestyle balance, and mental well-being.

---

## Problem Statement

Many people experience low productivity, fatigue, and stress but do not understand the cause. Most tracking apps only collect data without giving meaningful guidance.

Users need a simple system that:
- Tracks daily habits
- Provides AI-based insights
- Helps improve lifestyle decisions
- Builds consistency through daily check-ins

---

## Solution

The AI Daily Energy Coach analyzes user inputs such as:

- Sleep hours
- Mood
- Stress level
- Activity level
- Energy level

Using AI logic, the platform generates:

- Daily energy score
- Personalized insights
- Suggestions to improve performance
- Progress tracking reports

The system also sends daily reminder emails with a link to the check-in form.

---

## Features

- User Authentication (Login & Signup)
- Daily Check-in Form
- AI-based Energy Analysis
- Personalized Recommendations
- Automated Email Reminders
- Report Generation
- Download & Share Reports
- Clean Dashboard UI
- REST API Integration
- FastAPI AI Service

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- Antigravity UI

### Backend
- Node.js (Express.js)
- Python FastAPI

### AI Processing
- AI-based logic for analyzing energy patterns

### Database
- SQLite

### Other Tools
- Axios
- Uvicorn
- python-multipart

---

## Project Structure

hackton/
│
├── frontend/
│   ├── dashboard
│   ├── checkin form
│   └── UI components
│
├── backend/
│   ├── routes/
│   │   └── api.js
│   ├── controllers/
│   │   └── energyController.js
│   ├── services/
│   │   └── ai_service.py
│   └── database
│
├── requirements.txt
├── package.json
└── README.md

---

## Installation

### 1. Clone Repository

git clone <repo-link>

cd hackton

---

### 2. Install Node.js Dependencies

npm install

or

npm install axios express cors

---

### 3. Install Python Dependencies

cd backend

pip install fastapi uvicorn python-multipart

or

pip install -r requirements.txt

---

### 4. Run Backend Server

Node API:

node api.js

FastAPI service:

uvicorn ai_service:app --reload

---

### 5. Run Frontend

Open index.html in browser

or run live server

---

## Workflow

User → Login → Daily Check-in → AI Processing → Report Generated → Download or Share

---

## Use Cases

- Personal productivity tracking
- Student wellness monitoring
- Employee health programs
- Fitness coaching apps
- Mental health awareness tools

---

## Future Scope

- Mobile app integration
- Wearable device sync
- Advanced AI insights
- Weekly & monthly analytics
- Notification system
- Multi-language support

---

## Author

JaiKishan Suthar

Hackathon Project

---

## License

For educational and hackathon use.
