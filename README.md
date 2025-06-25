# workout-logger
# 🏋️ AI-Powered Workout Logger

A smart desktop application that tracks your workouts using natural language input. Built with Python and Tkinter, the app uses Nutritionix API to analyze exercises and logs the results in a Google Sheet via Sheety API.

---

## 🚀 Features

- ✨ **Natural language input** (e.g., "I ran 5km and did 30 minutes of yoga")
- 🧠 **AI-based workout parsing** using [Nutritionix API](https://www.nutritionix.com/business/api)
- 📝 **Google Sheets integration** via [Sheety API](https://sheety.co/)
- 📊 Displays exercise, duration, and calories burned in a GUI
- 🖥️ **Tkinter GUI** with real-time logging and beautiful UI


---

## 🛠️ Tech Stack

- Python 3
- Tkinter (GUI)
- Nutritionix API (for AI workout parsing)
- Sheety API (for Google Sheets logging)
- datetime, requests, scrolledtext, messagebox

---

## 🧪 How It Works

1. User describes their workout in plain English.
2. The app sends the query to Nutritionix, which returns structured data (exercise name, duration, calories).
3. Results are:
   - Displayed in the GUI
   - Logged in a connected Google Sheet via Sheety API
4. A success message is shown after logging.

---

## 📦 Installation

```bash
pip install requests
