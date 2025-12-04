# Lumos PWA

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![PWA](https://img.shields.io/badge/PWA-Progressive%20Web%20App-purple?style=for-the-badge)

A React-based Progressive Web App (PWA) designed for Lumos: A Mobile first AI Image Editor for 2030

## 📱 PWA Installation (Required for Optimal Experience)

This application is built as a Progressive Web App. For the intended user experience (full-screen mode, touch optimization, and performance), **it must be installed on your mobile device.**

**How to Install:**

* **iOS (Safari):**
    1.  Open the application URL in Safari.
    2.  Tap the **Share** button (square with an arrow).
    3.  Scroll down and select **"Add to Home Screen"**.
* **Android (Chrome):**
    1.  Open the application URL in Chrome.
    2.  Tap the menu icon (three dots in the upper right).
    3.  Select **"Install App"** or **"Add to Home Screen"**.

---

## 🔧 Architecture & Dependencies

### Voice Recognition API
The voice recognition backend is currently hosted via Google Colab. Ensure the notebook is running for voice features to function correctly.

* **API Endpoint/Notebook:** [Google Colab Voice Recognition Drive](https://colab.research.google.com/drive/1UIDXW-KNdcVDCg6QKgBXkzciooL3Jbdl?usp=sharing)

---

## 🚀 Getting Started

To set up the project locally for development:

### 1. Prerequisites
Ensure you have Node.js installed.

### 2. Installation
Clone the repository and install the dependencies:

```bash
npm install
```

### 3. Development Server
Run the app in development mode:

```bash
npm start
```

Open http://localhost:3000 to view it in your browser. The page will reload when you make changes.

### 4. Building for Production
To build the app for deployment (generating the PWA service workers and manifest):

```bash
npm run build
```