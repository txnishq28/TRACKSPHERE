# TRACKSPHERE 🌍

**TRACKSPHERE** is a real-time location tracking web application that allows users to view their live location on a map using the browser's Geolocation API and LeafletJS. The backend uses Node.js and Socket.IO for real-time communication.

## 🚀 Features

- 📍 Real-time geolocation tracking
- 🗺️ Interactive LeafletJS map
- 🔄 Live updates using WebSockets (Socket.IO)
- 🌐 Responsive web interface

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, LeafletJS
- **Backend:** Node.js, Express.js, Socket.IO
- **Geolocation:** Browser Geolocation API

## 📁 Project Structure
TRACKSPHERE/
├── public/
│ ├── css/
│ │ └── style.css
│ └── js/
│ └── script.js
├── views/
│ └── index.ejs
├── app.js
├── package.json
└── README.md
## ⚙️ Installation

1. Clone the repository:

git clone https://github.com/txnishq28/TRACKSPHERE.git
cd TRACKSPHERE
Install dependencies:
npm install

Start the server:
node app.js

Visit in browser:
http://localhost:3000
⚠️ Ensure you allow location access in your browser for real-time updates.

📡 How It Works
The browser fetches the user's geolocation.
The coordinates are sent to the server via Socket.IO.
The frontend listens for the location data and updates the map marker in real time.

🧩 Future Improvements
User authentication
Multi-user tracking
Location history logs
Safe zones and alerts
