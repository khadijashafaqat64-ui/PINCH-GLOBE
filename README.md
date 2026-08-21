# PINCH // GLOBE 🌐

A futuristic, gesture-controlled 3D visualization interface built with **Three.js** and **MediaPipe Hands**.

PINCH // GLOBE allows users to interact with a real-time particle-based 3D object using hand gestures detected through a webcam.

## ✨ Features

* 🖐️ Real-time hand tracking
* 🤏 Pinch gesture for zoom control
* ☝️ 1 finger — Globe / Sphere
* ✌️ 2 fingers — Cube
* 🤟 3 fingers — Torus / Donut
* 🖐️ 4 fingers — Plane / Map
* ✊ Fist — Reset camera
* 🖐️ Open palm — Pause rotation
* 👋 Fast swipe — Change visual theme
* 👐 Two-hand control — Rotate the object
* 🎨 Multiple futuristic color themes
* 📹 Live webcam hand-tracking preview
* 🤖 Built-in AI assistant interface
* 📱 Responsive futuristic HUD interface

## 🛠️ Technologies

* HTML5
* CSS3
* JavaScript
* Three.js
* MediaPipe Hands
* WebGL
* Web Camera API

## 🎮 Gesture Controls

| Gesture     | Action         |
| ----------- | -------------- |
| 1 Finger    | Sphere / Globe |
| 2 Fingers   | Cube           |
| 3 Fingers   | Torus          |
| 4 Fingers   | Plane          |
| Pinch       | Zoom           |
| Fist        | Reset Camera   |
| Open Palm   | Pause Rotation |
| Second Hand | Rotate Object  |
| Fast Swipe  | Change Theme   |

## 🚀 How to Run

### Option 1 — Open Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/PINCH-GLOBE.git
```

Open the project folder and run `index.html` using a local development server.

For example, with VS Code, install the **Live Server** extension and select:

```text
Open with Live Server
```

### Option 2 — GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch.
6. Select `/root`.
7. Click **Save**.

After deployment, GitHub will provide a public website URL.

## 🔐 AI Assistant Note

The AI Assistant requires an API request to an external AI service.

For security, **never expose a private API key directly inside `index.html` or client-side JavaScript**.

A production version should use a backend server or serverless function to securely handle API authentication.

## 📁 Project Structure

```text
PINCH-GLOBE/
│
├── index.html
└── README.md
```

## 🎯 Project Goal

The goal of PINCH // GLOBE is to demonstrate how **computer vision, gesture recognition, WebGL and interactive UI design** can be combined to create a natural human-computer interaction experience.

## 👩‍💻 Author

**Khadija Shafaqat**

Robotics & AI Student

---

⭐ If you find this project interesting, consider giving the repository a star!
