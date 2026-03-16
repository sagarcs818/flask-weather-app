# 🌦️ Flask Weather App

A modern and responsive **Weather Web Application** built using **Flask**, **HTML**, **CSS**, and **Bootstrap**.

The application fetches **real-time weather data** and automatically switches between **Day Mode ☀️** and **Night Mode 🌙** based on the local time of the searched city.

---

## 🚀 Features

* 🌍 Search weather by **city name**
* 🏙️ Default weather displayed for **Patna**
* ☀️ **Day Mode UI** based on city daytime
* 🌙 **Night Mode UI** based on city nighttime
* ⏱️ Real-time weather details:

  * Temperature
  * Feels-like temperature
  * Humidity
  * Wind speed
  * Pressure
  * Sunrise & Sunset
* ❌ **Custom error handling page** for invalid city or API failure
* 📱 Fully **responsive design** using Bootstrap

---

## 🖼️ Screenshots

### 🏠 Home Page (Default – Patna Weather)

Displays the **default weather information for Patna** when the application loads.
Users can search for any city using the search bar.

![Home Page](https://github.com/user-attachments/assets/7a07538c-958f-40fe-9e3e-5dc2298d7c6b)

---

### ☀️ Day Mode

Automatically activated when it is **daytime at the searched location**.
The interface switches to a **bright theme** to reflect daytime conditions.

![Day Mode](https://github.com/user-attachments/assets/b3f49a15-e9f9-49f1-a864-8ff8253dbd43)

---

### 🌙 Night Mode

Displayed when it is **nighttime at the searched location**.
The UI changes to a **dark theme** to provide a better night viewing experience.

![Night Mode](https://github.com/user-attachments/assets/a399d1ad-6d05-4c6d-ab57-86887d567e54)

---

### ⚠️ Error Handling Page

Shown when an **invalid city name is entered** or when the **weather API request fails**.

![Error Page](https://github.com/user-attachments/assets/00a850fe-8520-4eac-9839-481caf782820)

---

## 🛠️ Tech Stack

* **Backend:** Flask, Python
* **Frontend:** HTML, CSS, Bootstrap
* **API:** Visual Crossing Weather API

---

## 📂 Project Structure

```text
WEATHER-APP-PROJECT/
│
├── static/
│   ├── css/
│   ├── images/
│   └── bootstrap files
│
├── templates/
│   ├── index.html
│   ├── cityDay.html
│   ├── cityNight.html
│   ├── error.html
│   ├── privacy.html
│   └── usage.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sagarcs818/flask-weather-app.git
cd flask-weather-app
```

---

### 2️⃣ Create a virtual environment

```bash
python -m venv venv
```

---

### 3️⃣ Activate the virtual environment

Windows

```bash
venv\Scripts\activate
```

Mac / Linux

```bash
source venv/bin/activate
```

---

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 5️⃣ Get your free Visual Crossing API key

* Go to https://www.visualcrossing.com/weather-api
* Sign up for a free account
* Copy your API key

---

### 6️⃣ Add your API key

Open **app.py** and replace:

```python
API_KEY = "<YOUR_API_KEY>"
```

---

### 7️⃣ Run the application

```bash
python app.py
```

---

### 8️⃣ Open your browser and visit

```
http://127.0.0.1:5000/
```

---

⭐ If you like this project, consider **starring the repository**.
