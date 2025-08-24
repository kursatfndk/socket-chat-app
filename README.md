# socket-chat-app
A simple socket-based chat application built with Python.  Includes a server and a client script for real-time communication through the terminal.

# 🖥️ Socket Chat App

A simple Python chat application using sockets.  
This project includes a **server** and a **client** script that allow real-time messaging through the terminal.

---

## 🚀 Features
- Server listens for connections and accepts a client
- Client connects to the server and exchanges messages
- Real-time communication over TCP
- Exit chat by typing `quit`

---
## ⚙️ Requirements
- Python 3.8+
- No external libraries required (only built-in `socket`)

*(Optional: create a virtual environment if needed)*

---

## ▶️ Usage

### 1️⃣ Start the server
```bash
python chat_server.py
2️⃣ Start the client (in another terminal)
python chat_client.py
3️⃣ Chat!

Type your message and press Enter.

To disconnect, type:
quit
