# 🎨 Collaborative Whiteboard with Voice Commands

A **real-time collaborative whiteboard** built using the **Canvas API** + **Socket.IO** for multi-user drawing and the **Web Speech API** for local voice commands.  
Draw, sketch, brainstorm, and create together — just say the command, and watch it happen.

---

## ✨ Features
- 🖌 **Real-time collaboration**: Multiple users can draw on the same board simultaneously.
- 🎤 **Voice commands**: Control the board with your voice (e.g., “undo”, “clear board”, “set brush size 10”, “change color to red”).
- 🎯 **Drawing tools**: Brush, shapes, eraser, color picker, and brush size controls.
- 📤 **Export as PNG**: Save your masterpiece with one click.
- 🏠 **Room-based sessions**: Share a link to invite others.
- 🔄 **Undo/redo** support across users.
- 📱 **Responsive design** for desktop and mobile.
- 🌐 **Secure context** support for voice (HTTPS/localhost).

---

## 🛠 Tech Stack
- **Frontend**: HTML, CSS, JavaScript (Canvas API)
- **Real-time**: Node.js, Express, Socket.IO
- **Voice Recognition**: Web Speech API
- **Optional Enhancements**: WebRTC (audio/video), TailwindCSS, Redis for scaling

---

## 🎤 Voice Commands
undo

redo

clear board

set brush size <number>

change color to <color>

draw circle

draw rectangle

save board
