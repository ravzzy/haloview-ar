# 🌌 HaloView AR

![haloview-ar](https://github.com/user-attachments/assets/6a85d9b8-de92-49fb-931b-3afd775bd8a7)

**HaloView AR** is a browser-based augmented reality experience that lets you view and interact with 3D holograms directly in your device. Featuring a futuristic UI, real-time model switching, and AR mode support, this project is built for immersive exploration using just your browser.

---

## 🚀 Features

- 🔄 Toggleable 3D model animations  
- 🧑‍🚀 Switch between multiple interactive models (Astronaut, Robot, Neil Armstrong)  
- 📱 AR support via WebXR, Scene Viewer, and Quick Look  
- 🌈 Holographic lighting and visual effects  
- 📱 Fully responsive and mobile-friendly  
- 🧩 Modular sidebar and navbar support via JS injection  
- 📺 No scrolling layout optimized for fullscreen immersion  

---

## 🧰 Tech Stack

- HTML5, CSS3, JavaScript (ES6+)
- [`<model-viewer>` by Google](https://github.com/google/model-viewer)
- Font Awesome for icons
- Google Fonts (`Noto Sans KR`, `Urbanist`)
- Google Analytics for tracking

---

## 🌍 AR Compatibility

- **Android (Chrome)** – Uses Scene Viewer  
- **iOS (Safari)** – Uses Quick Look  
- **Desktop** – WebXR support (requires compatible devices)

---

## ⚙️ Local Setup

Use any static file server like `http-server`, `live-server`, or a simple Python server:

```bash
# With Node.js http-server
npx http-server

# OR with Python
python3 -m http.server

Then open your browser and navigate to:
http://localhost:8080

👨‍💻 Author
ravzzy – @ravzzy on GitHub

