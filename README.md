# 💬 Basic Chatting App

This is a simple real-time chatting application built using **Node.js**, **Express**, and **Socket.io**. It allows users to send and receive messages live in the browser.

---

## 🚀 Features

- Real-time messaging using WebSockets (Socket.io)
- Broadcast messages to all connected clients
- Simple and responsive UI using HTML and CSS
- Uses Express.js to serve static files

---

## 📁 Project Structure

basic-chatting-app/ │ ├── public/ │ ├── index.html # Frontend UI │ └── index.css # Styling │ ├── server.js # Express + Socket.io server ├── package.json └── README.md # You're here!

yaml
Copy
Edit

---

## 🛠️ Technologies Used

- Node.js
- Express.js
- Socket.io
- HTML/CSS

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Ramanand-tomar/basic-chatting-app.git
cd basic-chatting-app
2. Install dependencies
bash
Copy
Edit
npm install
3. Start the server
bash
Copy
Edit
node server.js
4. Open the app in your browser
arduino
Copy
Edit
http://localhost:9000
🌐 How It Works
When a user types a message and clicks Send, it emits a user-message event via Socket.io.

The server listens for this event and broadcasts the message to all other clients using socket.broadcast.emit.

The frontend listens for message events and displays them in the UI.

📸 Screenshots
Add screenshots of the UI for better understanding if needed.

🧠 Future Improvements
Add user names or login system

Save messages in database (MongoDB or Firebase)

Show "user joined/left" notifications

Create private rooms or group chats

📄 License
This project is open-source and available under the MIT License.

👨‍💻 Author
Made with ❤️ by Ramanand Tomar

yaml
Copy
Edit

---

👉 **Next Step:**  
- Create a new file in your project root named `README.md`.
- Paste this full content into that file and save it.
- Commit and push it:

```bash
git add README.md
git commit -m "Added README file"
git push origin main