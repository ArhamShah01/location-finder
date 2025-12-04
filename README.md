# 📍 Location Fetcher Web App

This project is a simple JavaScript-based web application that fetches the user's current geographical location (latitude and longitude) using the **HTML Geolocation API**. Once permission is granted, the application retrieves the coordinates and displays them on the page.

---

## 🚀 Features

- Retrieves user's **current latitude and longitude**
- Provides **error handling** for denied permission, timeout, or unavailable location
- Displays the fetched location on the webpage
- Built using plain **HTML, CSS, and JavaScript** (no frameworks)

---

## 📂 Project Structure

index.html

All code is contained within a single HTML file including inline CSS and JavaScript.

---

## ⚙️ How It Works

1. User clicks the **“Fetch Location”** button.
2. Browser asks permission to access location.
3. If granted:
   - Coordinates are retrieved using:
     ```js
     navigator.geolocation.getCurrentPosition()
     ```
4. Location gets displayed on the screen.

---

## 🧱 Prerequisites

✔ A modern browser that supports **Geolocation API**  
❌ Geolocation will not work on insecure HTTP — **use HTTPS**, or run locally

---

## ▶️ How to Run

### **Option 1 — Run locally**
Just open the `index.html` file directly in your browser.

### **Option 2 — Using Live Server**
1. Install Live Server (VS Code extension)
2. Right-click `index.html`
3. Select **"Open with Live Server"**

---

## 🔐 Permissions & Security

- The browser **must ask users for permission**
- Geolocation API does **not provide the exact location without consent**
- On Chrome, geolocation **requires HTTPS**, except on `localhost`

---

## 🧩 Customization Ideas

- Integrate Google Maps / Leaflet map display
- Save location to backend
- Track movement (watchPosition API)
- Draw location path
- Show timestamp and accuracy radius

---

## 📜 License

This project is free to use and modify.

---

## ✨ Author

Developed as a simple example of using the **HTML5 Geolocation API**.
