# 💬 RealTime Chat Application

A real-time chat application built using **Spring Boot** for the backend and **HTML/CSS/JS + Socket.IO** on the frontend. Users can join and chat instantly in a clean and simple UI.

## 🚀 Features

- Real-time messaging via WebSockets
- Multiple users can join and chat simultaneously
- Simple frontend UI
- Scalable backend using Spring Boot

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Socket.IO
- **Backend**: Spring Boot (Java)
- **WebSocket Communication**: Spring WebSocket + STOMP

![Screenshot 2025-04-13 184519](https://github.com/user-attachments/assets/a395becb-cbe6-4e8e-95f9-afb870a98708)
![Screenshot 2025-04-13 184647](https://github.com/user-attachments/assets/f16d06a7-0568-425b-8045-6049e04eefd2)



## 📁 Folder Structure

📦 RealTime-chat-application ┣ 📂 frontend ┃ ┣ 📜 index.html ┃ ┣ 📜 style.css ┃ ┗ 📜 app.js ┣ 📂 backend ┃ ┣ 📂 src ┃ ┃ ┣ 📂 main ┃ ┃ ┃ ┣ 📂 java ┃ ┃ ┃ ┃ ┗ 📂 com.example.chat ┃ ┃ ┃ ┃ ┃ ┣ 📜 ChatController.java ┃ ┃ ┃ ┃ ┃ ┣ 📜 WebSocketConfig.java ┃ ┃ ┃ ┃ ┃ ┗ 📜 Message.java ┃ ┃ ┃ ┗ 📂 resources ┃ ┃ ┃ ┃ ┗ 📜 application.properties ┃ ┗ 📜 pom.xml

## 🧑‍💻 Getting Started

### Prerequisites

- Java 17+ and Maven installed

### Installation

```bash
git clone https://github.com/shrutim250/RealTime-chat-application.git
cd RealTime-chat-application/backend
mvn clean install

### Run the App
mvn spring-boot:run

