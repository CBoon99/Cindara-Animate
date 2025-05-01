# Doppleit Animate Pro v2.2

Doppleit Animate Pro is a browser-based 3D animation editor built with Three.js.  
It features keyframe animation, layer grouping, timeline controls, color and camera animation, and full HTML/JSON export.

---

## 🚀 Live Features

### ✅ Animation System
- Position, Rotation, Scale, and Color keyframes
- Easing functions (linear, ease-in/out)
- Camera keyframe animation
- Timeline playback marker and scrubber
- Drag-and-drop timeline keyframes
- Zoomable timeline and snap mode
- Layer-based animation group system

### ✅ Scene Editing
- Add Cube, Sphere, Plane objects
- Transform inputs: position, rotation, scale
- Color picker per object
- Object selection and layer assignment

### ✅ UI/UX
- Doppleit glitch branding
- Responsive design for mobile
- Light/dark mode toggle
- Visual playback marker
- Undo/Redo with deep scene state

### ✅ Export / Save
- Save/load scene to/from localStorage
- Export JSON (for future loading)
- Export full embedded HTML animation
- All data: camera, easing, groups, keyframes included

---

## 📖 How to Use

### 🧱 Adding Objects
- Use "Add Cube", "Add Sphere", or "Add Plane" to insert new objects
- Objects default to Layer 1 (can be reassigned)

### 🎨 Editing Objects
- Select from dropdown list or by adding new object
- Use inputs to move, rotate, scale, or recolor
- Values update live in the scene

### 🎬 Creating Animation
1. Move the timeline slider to your desired time
2. Edit object position/rotation/scale/color
3. Click **Set Keyframe**
4. Select easing function if desired

### 🎥 Camera Animation
- Camera position & rotation are keyframed automatically
- Will interpolate with easing during playback

### 🧭 Timeline Tools
- Use playback controls to preview
- Drag keyframe markers to reposition in time
- Toggle **Snap** for frame alignment
- Use **Zoom** to see more or less of the timeline

### 📁 Layers / Groups
- Rename layers
- Add/Delete groups
- Assign objects to groups
- Group info included in export

### 💾 Saving & Loading
- Click **Save** to store to browser
- Click **Load** to restore previous scene
- Uses `localStorage`, so persists across sessions (in same browser)

### 📤 Exporting
- **Export JSON**: full scene and timeline data
- **Export Embed**: generates standalone `.html` animation (playback only)

---

## 🔧 Project Details

- Framework: None (Vanilla JS)
- Engine: [Three.js r161](https://threejs.org/)
- File: Single HTML file (self-contained)
- License: MIT

---

## 📦 Deployment

You can deploy the `.html` file to:
- GitHub Pages
- Netlify / Vercel
- Or open it locally in any browser

---

## 🧪 Coming Soon Ideas

- Draggable timeline keyframe editor
- Audio and event triggers
- Per-layer playback toggle
- More easing options and custom curves
- Image/text layer support

---

## 🙌 Created by Carl (Doppleit Labs)

> Software that reflects your creativity.