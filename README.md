# Weather Dashboard

A simple weather dashboard that allows users to search for cities and view real-time weather information using the OpenWeather API. The application focuses on client-side API integration, asynchronous JavaScript, and responsive UI design.

🔗 **Live Demo:** https://weather-dashboard-beta-liart.vercel.app  

📦 **Source Code:** https://github.com/rajarshi-29/weather-dashboard

---

## 🚀 Features

- Add and manage multiple cities
- Fetches real-time weather data using REST APIs
- Persistent city list using `localStorage`
- Graceful error handling for invalid city names or API failures
- Responsive and clean UI built with Tailwind CSS

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS**
- **JavaScript (ES6+)**
- **OpenWeather API**
- **Deployment:** Vercel

---

## 🧠 Technical Overview

- Uses `fetch` with `async/await` to retrieve weather data from the OpenWeather REST API.
- Implements client-side state persistence using `localStorage`.
- Handles API error responses to ensure stable user experience.
- Dynamically updates the DOM based on user interactions and API responses.

---

## ⚠️ API Key Handling

This is a client-side application built using plain HTML and JavaScript.

- Since there is no backend or build step, the OpenWeather API key is included in the client-side code.
- For frontend-only projects, API keys cannot be fully hidden from the client.
- In real-world production systems, environment variables and backend proxies should be used to securely manage API keys.

This project is intended to demonstrate frontend API integration and awareness of secure deployment practices.

---

## 👤 Author

**Rajarshi Mukherjee**  
GitHub: https://github.com/rajarshi-29  
LinkedIn: https://linkedin.com/in/rm2904
