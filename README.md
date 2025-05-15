# 🗨️ Multi-Client ChatApp (Java Swing)

A multi-client chat application built with **Java Swing**, enabling users to exchange messages, images, files, and emoji stickers over a local or networked server. Developed using **NetBeans 23** and **JDK 23 (or similar)**, this project demonstrates core concepts of socket programming, multithreading, and GUI development in Java.

---

## 📂 Project Structure

- `Server.java` – Manages incoming client connections, broadcasts messages, and handles file/data routing.
- `Client.java` – Client-side application that connects to the server, sends/receives messages and files via a Swing-based GUI.
- `Message.java` – A serializable class used for structured communication between server and clients.

---

## ✨ Features

- ✅ **Multi-client support** – Multiple clients can connect and chat simultaneously.
- 💬 **Real-time messaging** – Instant delivery of text messages.
- 📁 **File transfer support** – Share any type of file between clients.
- 🖼️ **Image sharing** – Send and receive image files.
- 😊 **Emoji & sticker support** – Enhance conversations with fun visuals.
- 🔄 **Asynchronous I/O** – Non-blocking communication using threads.
- 📡 **Socket-based networking** – Uses TCP sockets for robust data transmission.

---

## 🛠️ Requirements

- Java JDK 17 or later (preferably JDK 23)
- NetBeans IDE 23 or equivalent
- OS with support for Java GUI (Windows, Linux, macOS)

---

## 🚀 Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/Multi-Client_ChatApp.git
   cd Multi-Client_ChatApp
