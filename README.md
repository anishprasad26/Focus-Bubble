# Focus-Bubble
Project focusing on React and Flask



---

# **Focus Bubbles - Distraction & Mood Tracker**

## **Overview**

**Focus Bubbles** is a full-stack web application that helps users track distractions and moods during focused work or study sessions. The app uses a **React frontend** for an interactive UI and a **Flask backend** for data storage and API handling.

Each distraction or mood entry is visualized as an animated **bubble**, making the experience engaging and reflective.

---

## **Features**

* **Log Distractions in Real-Time**
* **Mood & Emotion Tracking**
* **Bubble Visualization** of logs
* **Persistent Storage** via Flask API
* **Minimal & Interactive UI**

---

## **Tech Stack**

| Frontend                     | Backend                    |
| ---------------------------- | -------------------------- |
| React.js (Vite)              | Flask (Python)             |
| Axios for API calls          | Flask-CORS                 |
| Framer Motion for animations | JSON or SQLite for storage |

---

## **Project Structure**

```
Focus_Bubble/
│
├── frontend/
│   ├── src/
│   │   └── main.jsx, App.jsx, components/
│   └── vite.config.js
│
├── backend/
│   └── app.py (Flask API)
│
├── README.md
└── package.json (for frontend)
```

---

## **How to Run the Project**

### **Frontend (React + Vite)**

1. Go to the `frontend` folder:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Run the development server:

```bash
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

### **Backend (Flask API)**

1. Go to the `backend` folder:

```bash
cd backend
```

2. Install Python dependencies:

```bash
pip install flask flask-cors
```

3. Run the Flask server:

```bash
python app.py
```

Backend runs at:

```
http://localhost:5000
```

---

## **API Endpoints**

| Method | Endpoint | Description                 |
| ------ | -------- | --------------------------- |
| `POST` | `/log`   | Logs a new distraction/mood |
| `GET`  | `/logs`  | Fetches all previous logs   |

---

## **Usage**

* Open the app in your browser.
* Use the form to log distractions or moods.
* Watch them appear as animated bubbles on the screen.

---


## **Future Enhancements**

* User authentication & profiles
* Export logs as CSV or PDF
* Weekly and monthly summaries

---

## **License**

This project is open-source and for educational purposes.

---
