# 🌌 Galactic Gateway VR

**Step into a cosmic realm of immersive exploration.**  
**Galactic Gateway VR** is a fully interactive 3D universe built with A-Frame and WebVR, featuring planet portals, ambient music, sci-fi environments, and animated characters — all navigable in VR.

![image](https://github.com/user-attachments/assets/e755f943-1112-4875-ba5c-b698312a914f)

![Screenshot 2025-06-30 223505](https://github.com/user-attachments/assets/58590c72-7b5d-4954-845e-52421cf16b3f)



---

## >Features

- 🌍 **Planetary Hub** – A rotating galaxy with portals to uniquely designed planets.
- 🔁 **Orbiting Planets** – Each planet revolves around a glowing sun using animation.
- 🔊 **Dynamic Audio** – Background music changes per world with click sound effects.
- 🎮 **Interactive Controls** – Full WASD movement, gaze-based selection, and raycaster enhancements.
- 🔄 **Loading Screen** – Shows a preloader until all 3D assets, audio, and textures are fully loaded.

---

## 🌐 Live Demo

**[Live](https://galactic-gateway-vr.netlify.app/)**

---

## 📂 Directory Structure
```
src/
│
├── index.html # Main galaxy hub scene
├── p1.html    # 1st Planet
├── p2.html    # 2nd Planet
├── p3.html    # 3rd Planet
├── last.html  # 4th Planet
├── Models/ # .glb and 3D files
├── Images/ # .jpg/.png background textures
└── Audios/ # Background music
```
---

---

## 🔧 Technologies Used

| Tech           | Usage                               |
|----------------|-------------------------------------|
| 💠 A-Frame     | VR Framework for rendering scenes   |
| 🎨 Three.js    | Underlying 3D rendering engine      |
| 🔊 a-sound     | Audio control within scenes         |
| 🎭 GLTF Models | Animated 3D characters and objects  |
| ⚙️ JavaScript  | Scene logic and interactivity       |

---

## >How It Works

Each planet is represented by an animated entity rotating around a central star. Clicking on any planet transitions the user to a dedicated VR scene with unique:

- Background
- Music
- Characters
- Visual design

All assets are preloaded using `<a-assets>` and tracked to ensure the loading screen only disappears once everything is ready.

---

##  Screenshots
![image](https://github.com/user-attachments/assets/9beb591e-3730-407f-8e35-982e854debb5)

---
![image](https://github.com/user-attachments/assets/487f16a9-d54f-4532-b7ff-b3d171d3c4ce)

---
![image](https://github.com/user-attachments/assets/f86a060f-bfef-4251-944a-5ebf13aca929)

---

##  To Run Locally

```bash
git clone https://github.com/Pranav-Uniyal/Galactic-Gateway-VR.git
cd Galactic-Gateway-VR
# Open index.html in any browser (recommend Chrome)
```
---

## 📜 License

This project is licensed under the MIT License.

---

## Credits

 Designed & Developed by **Pranav Uniyal**

 Models sourced from Sketchfab

 ---
 ## “This isn’t just a web app. It’s a VR-powered portal to imagination.”

