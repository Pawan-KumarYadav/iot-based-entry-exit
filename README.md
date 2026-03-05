🚪 IoT Based Entry Exit Monitoring System

An IoT-based Entry Exit Monitoring System designed to automatically track and record the entry and exit of users using RFID technology and ESP8266 WiFi module. The system stores data on a server and displays real-time logs through a web interface, making it suitable for attendance management, security monitoring, and access control systems.

📌 Project Overview

This project aims to automate the traditional attendance or access system by using RFID cards and IoT technology. When a user scans their RFID card, the system captures the UID of the card, sends the data to a server through WiFi, and records the entry or exit time in a database.

The stored data can be viewed on a web dashboard, providing real-time monitoring and record management.

⚙️ Technologies Used
Hardware

ESP8266 WiFi Module

RFID Reader (MFRC522)

RFID Tags/Cards

Arduino Nano / Arduino IDE

Breadboard

Jumper Wires

Buzzer (Optional)

Software

Arduino IDE

Node.js / PHP Backend

MongoDB Atlas / MySQL Database

HTML

CSS

JavaScript

Web Server

🧠 System Working

The RFID Reader scans the user's RFID card.

The system reads the unique UID of the card.

The ESP8266 module connects to WiFi.

The UID is sent to the backend server via HTTP request.

The server stores the user ID, entry time, and exit time in the database.

The data is displayed on a web dashboard in real-time.

📊 Features

✅ RFID Based Authentication
✅ Automatic Entry & Exit Logging
✅ Real-Time Data Monitoring
✅ Web Dashboard for Data Viewing
✅ Database Storage of User Records
✅ CSV Export Option
✅ User Identification System
✅ Scalable for Multiple Users

🏗️ Project Architecture
RFID Card
   │
   ▼
RFID Reader (MFRC522)
   │
   ▼
ESP8266 WiFi Module
   │
   ▼
Backend Server (Node.js / PHP)
   │
   ▼
Database (MongoDB / MySQL)
   │
   ▼
Web Dashboard
📁 Project Structure
IoT-Entry-Exit-Monitoring-System
│
├── Arduino_Code
│   └── rfid_esp8266_code.ino
│
├── Backend
│   ├── server.js
│   ├── routes
│   └── database_connection
│
├── Frontend
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── Database
│
└── README.md
🚀 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/iot-entry-exit-monitoring-system.git
2️⃣ Upload Arduino Code

Open Arduino IDE

Connect ESP8266 + RFID module

Upload the provided Arduino code.

3️⃣ Setup Backend Server

Install required packages:

npm install

Start server:

node server.js
4️⃣ Setup Database

Create a database in:

MongoDB Atlas
or

MySQL

Configure the database connection in the backend code.

5️⃣ Run Web Dashboard

Open:

http://localhost:3000

You can now monitor user entry and exit logs.

🖥️ Web Dashboard Features

Display user ID

Entry time

Exit time

Real-time updates

Search and filter functionality

🔐 Future Improvements

Face Recognition Integration

Mobile App Monitoring

Cloud-Based Data Storage

Multi-device synchronization

Advanced User Authentication

👨‍💻 Author

Pawan Kumar Yadav
Computer Engineering Student

GitHub: (https://github.com/Pawan-KumarYadav)

LinkedIn: https://www.linkedin.com/in/pawan-kumar-yadav-98471636a/
