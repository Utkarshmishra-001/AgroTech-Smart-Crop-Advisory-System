# 🌾 AgroTech - Smart Crop Advisory System

AgroTech is a premium, data-driven agricultural platform designed to empower farmers with modern technology. It bridges the gap between traditional farming knowledge and scientific precision using AI-powered insights, real-time market tracking, and digital soil analysis.

---

## 📜 Synopsis

**AgroTech** is an innovative, all-in-one agricultural web application tailored to modernize farming practices and enhance crop yield. In an era where climate unpredictability and soil degradation pose significant challenges, AgroTech provides a comprehensive digital ecosystem for farmers. The platform integrates a smart **Crop Advisory System** that recommends optimal crops based on soil and weather conditions, a **Digital Soil Lab** for precise fertilizer calculations, and a real-time **Weather & AI Recommendation Engine** for day-to-day planning.

Further empowering the agricultural community, AgroTech features live **Market Price (Mandi) tracking** to ensure fair trade, an **AI Pest Scanner** for instant disease diagnosis and treatment suggestions, and an integrated **Drone Sprayer Service** booking system for efficient pesticide application. By combining modern modern web technologies with a robust AI backend, AgroTech creates a seamless, user-friendly portal that bridges the gap between traditional agricultural knowledge and cutting-edge scientific precision, ultimately transforming farming into a more sustainable, profitable, and data-driven enterprise.

---

## 🚀 Features

### 1. 🌾 Smart Crop Advisory
Comprehensive cultivation guides for over 10 major crops, including ideal soil types, temperature ranges, and rainfall requirements.

### 2. 🧪 Digital Soil Lab
A virtual laboratory where farmers can input Nitrogen (N), Phosphorus (P), Potassium (K), and pH levels. The system calculates precise fertilizer requirements (Urea, DAP, MOP) based on the target crop.

### 3. ☁️ Live Weather & AI Recommendation
- **City Search & Sync**: Manually enter your city or use browser geolocation to fetch real-time local weather data.
- **AI Recommendation**: An intelligent engine that analyzes the current month (Season) and temperature to suggest the most profitable crop to plant *today*.
- **Interactive WhatsApp Alerts**: Get instant weather warnings and send custom queries/messages directly to agri-experts via WhatsApp.

### 4. 📈 Live Market Access (MP Mandi)
Direct tracking of crop prices across all major districts of Madhya Pradesh (MP). It provides Min, Max, and Average prices along with trend indicators (Rising/Falling).

### 5. 🪲 AI Pest Scanner
Farmers can upload images of infected crops. The system identifies the pest or disease (e.g., Yellow Rust, Aphids) and provides expert chemical and biological solutions.

### 6. 🚁 Drone Sprayer Service
A high-tech booking system for precision pesticide and fertilizer spraying, helping farmers save 90% water and cover large areas 10x faster.

### 🏛️ Government Schemes
A curated list of central and state government initiatives like PM-Kisan and Fasal Bima with easy "Learn More" links.

---

## 🛠️ Technology Stack

- **Frontend**: 
    - **HTML5**: Semantic structure and modern layout.
    - **CSS3 (Vanilla)**: Custom styling featuring **Glassmorphism**, responsive flex/grid layouts, and smooth micro-animations.
    - **JavaScript (ES6)**: Core logic for AI recommendations, form processing, and dynamic rendering.
- **Backend & Database**:
    *   **Python (FastAPI/Flask)**: Powering the core AI engine and serving as the primary backend for Machine Learning model inference.
    *   **Libraries**: **TensorFlow/Keras** (for Pest Diagnosis), **OpenCV** (Image Processing), **Pandas** (Soil Data Analysis).
    *   **Node.js**: (Optional) For high-concurrency real-time notifications.
    *   **MongoDB / Firebase**: For persistent storage of market price history and user activity logs.
- **APIs & Libraries**:
    - **Font Awesome**: Professional iconography.
    - **Google Fonts (Outfit)**: Modern typography.
    - **Browser Geolocation API**: To detect farm location.
    - **BigDataCloud API**: For reverse geocoding (City detection).
- **Storage**:
    - **LocalStorage**: To save soil analysis reports and history without needing a database.

---

## ⚙️ How It Works

1. **Advisory**: Uses a JSON-based database to store crop attributes and renders them dynamically via modals.
2. **Soil Analysis**: Implements mathematical algorithms to calculate the gap between "Current Value" and "Ideal Value" for specific crop varieties.
3. **Pest Scanner**: Simulates an AI image recognition process with a "Scan Line" animation and randomized diagnosis from an expert-curated dataset.
4. **Market Data**: Structured data arrays covering multiple districts (Indore, Sagar, Bhopal, etc.) and mandis.

---

## 💻 How to Run Locally

This application consists of a modern frontend and a Python FastAPI backend. You need to run both concurrently for full functionality (especially the Soil Lab and Pest Diagnosis AI).

### 1. Start the Backend (FastAPI)

1. Open your terminal and navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the FastAPI server:
   ```bash
   python app.py
   ```
   *The backend will start running on `http://localhost:8005`.*

### 2. Start the Frontend (Web App)

1. Open **a new terminal window** (keep the backend running) and navigate to the root folder:
   ```bash
   cd AgroTech
   ```
2. Start a local HTTP server to serve the frontend files:
   ```bash
   python -m http.server 5501
   ```
3. Open your browser and go to `http://localhost:5501` to use the app.

> **Note:** Do not open `index.html` directly (via `file://` protocol) as browser CORS policies will block communication with the backend. Always use a local HTTP server. Enable **Location permissions** in your browser when prompted to use the Weather & Auto-detect features.

---

## 👨‍💻 Created By
**Utkarsh Mishra**
Building the future of sustainable and smart agriculture.
# AgroTech-Smart-Crop-Advisory-System
