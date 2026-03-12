# ☁️ Weather Forecast App

![HTML](https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-orange)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![Express](https://img.shields.io/badge/Framework-Express.js-black)
![API](https://img.shields.io/badge/API-Weather%20API-blue)

A full-stack weather forecast web application that fetches and displays real-time weather information for any city using a weather API.

---

# 📖 Overview

The **Weather Forecast App** allows users to search for a city and view its current weather conditions such as:

- Temperature
- Weather condition
- Humidity
- Wind information

The project demonstrates how a **frontend interface interacts with a backend server**, which then retrieves weather data from an external API.

---

# ✨ Features

✔ Search weather by city name  
✔ Real-time weather data retrieval  
✔ Weather condition icons and animations  
✔ Backend server for API requests  
✔ Clean and responsive user interface  

---

# 🛠 Technologies Used

## Frontend
- HTML5
- CSS3
- JavaScript

## Backend
- Node.js
- Express.js

## Other Tools
- Weather API
- npm

---

# 📂 Project Structure

```
weather-forecast-app
│
├── .github
│   └── copilot-instructions.md
│
├── docs
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   └── images
│       ├── clear.svg
│       ├── clouds.svg
│       ├── rain.svg
│       ├── snow.svg
│       └── ...
│
├── weather-backend
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   ├── .env
│   └── .gitignore
│
└── README.md
```

*Note:* The `node_modules` folder is not included here because it is automatically generated when dependencies are installed.

---

# ⚙️ How It Works

1. The user enters a **city name** in the search field.
2. The frontend sends a request to the **Node.js backend server**.
3. The backend fetches weather data from a **Weather API**.
4. The server returns the data to the frontend.
5. The frontend dynamically updates the UI with weather information.

---

# ▶️ How to Run the Project

## 1️⃣ Clone the repository

```bash
git clone https://github.com/ekbalshah-dev/weather-forecast-app.git
```

## 2️⃣ Navigate to the project folder

```bash
cd weather-forecast-app
```

## 3️⃣ Install backend dependencies

```bash
cd weather-backend
npm install
```

## 4️⃣ Add API Key

Create a `.env` file inside the **weather-backend** folder and add your weather API key:

```
API_KEY=your_weather_api_key_here
```

## 5️⃣ Start the backend server

```bash
node server.js
```

## 6️⃣ Open the frontend

Open the file:

```
docs/index.html
```

in your browser.

---

# 🎯 Purpose of the Project

This project was built to practice:

- Full-stack web development
- API integration
- Backend server creation with Node.js
- Dynamic UI updates using JavaScript

---

# 👨‍💻 Author

**Ekbal Shah**  
B.Sc Computer Science Student  
Bengaluru, India  

GitHub: https://github.com/ekbalshah-dev
