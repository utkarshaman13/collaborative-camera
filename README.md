

🎨 Collaborative Canvas - Multi-User Drawing App

⚠️ Disclaimer

This project is provided for educational and research purposes only.
Use this application responsibly and only on systems and networks you own or have permission to test.
The author is not responsible for any misuse, damages, or violations of applicable laws caused by the use or modification of this software.
By using this tool, you agree to comply with all relevant legal and ethical standards.


🧩 Introduction

Collaborative Canvas is a real-time, multi-user drawing application built using Node.js, Socket.io, and HTML5 Canvas.
It allows multiple users to draw simultaneously on a shared canvas, with instant synchronization across all connected clients.

This tool demonstrates real-time data transmission, WebSocket communication, and collaborative UI updates — ideal for learning web sockets, event broadcasting, and frontend-backend synchronization.

---

🧠 Pre-requisites

Before running the application, ensure that you have:

🐧 Linux / macOS / Windows environment
🟢 Node.js (v14 or above)
⚡ npm (Node Package Manager)



⚙️ Installation

Clone the repository:

bash
git clone https://github.com/utkarshaman13/collaborative-canvas.git


Navigate to the project directory:
cd collaborative-canvas


Install dependencies:
npm install


Start the server:
npm start


Open your browser and visit:
http://localhost:3000




🧭 Options & Commands

| Command                 | Description                     |
| ----------------------- | ------------------------------- |
|  npm install            | Installs required dependencies  |
|  npm start              | Starts the Node.js server       |
|  Ctrl + C               | Stops the server                |
|  http://localhost:3000  | Access the collaborative canvas |



🚀 Features

🎨 Real-time Multi-User Drawing** — Draw simultaneously with others
👥 User Management** — See who’s connected
🖱️ Remote Cursor Tracking** — See others’ cursors live
↩️ Global Undo / Redo** — Undo or redo strokes collaboratively
📱 Touch Support** — Works on mobile & tablets
⚙️ Performance Monitoring** — Optimized for smooth real-time updates



🧪 Testing Multi-User Collaboration

1. Run the server:

   npm start
   
2. Open two or more browser windows/tabs:

   http://localhost:3000
   
3. Enter different usernames in each window
4. Start drawing — changes will appear in all clients instantly 🎉


📁 Project Structure


collaborative-canvas/
├── client/              # Frontend (HTML/CSS/JS)
│   ├── index.html       # FIXED: Socket.io client script added
│   ├── style.css
│   ├── canvas.js
│   ├── websocket.js
│   └── main.js
├── server/              # Backend (Node.js + Socket.io)
│   └── server.js
├── package.json
└── README.md


🧩 Fixes Implemented
✅ Added `<script src="/socket.io/socket.io.js"></script>` in `index.html`
✅ Improved WebSocket connection handling
✅ Enhanced console logging for debugging
✅ Fixed synchronization issues in multi-user sessions


📝 License

MIT License
Free to use, modify, and distribute with attribution.
See the (LICENSE) file for more details.

