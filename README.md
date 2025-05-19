# 🏗️ 3D Model Generator from 2D Blueprints

This is a web-based application that allows users to upload a 2D architectural blueprint and view a static 3D representation of the structure. It serves as an early prototype for a future AI-based system that will dynamically convert 2D plans into 3D construction models.

---

## 🧠 Problem Statement

Architects and civil engineers often need to manually visualize 3D structures based on 2D blueprints, which is time-consuming and prone to interpretation errors. This application is a step toward automating that transformation using artificial intelligence and 3D rendering.

---

## ⚙️ Features

- Upload a 2D architectural blueprint (image format)
- Render and view a **static 3D model** using Three.js
- Interact with the 3D model (rotate, zoom, and pan)
- Clean and modern UI built with React

---

## 🛠️ Tech Stack

- **Frontend:** ReactJS, Three.js
- **Backend:** (Planned) Flask + AI model using OpenCV and PyTorch
- **Hosting:** Vercel (Frontend)

---

## 📁 File Structure

bash
project-root/
├── frontend/               # ReactJS project
├── static_3d_model/        # Contains static 3D image rendered in the frontend
├── backend/ (future)       # Flask backend for AI inference
├── README.md




Create a new directory and open it in VS Code
Copy all the files provided above into their respective locations

Open terminal in VS Code and run:

npm install
npm run dev
The application will start at http://localhost:5173

Key Features:

Home page with animated hero section
Interactive 3D model viewer using Three.js
Dashboard with model management
Smooth animations using Framer Motion
Responsive design with Tailwind CSS

The app will run on http://localhost:3000
