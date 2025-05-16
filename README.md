# 📡 Local Chat Project Using Python Sockets

This repository contains a simple **client-server chat application** built using **Python sockets and threading**. It allows multiple clients to connect to a server over a **local network** and exchange text messages in real-time.

This project was developed to gain a deeper understanding of fundamental **networking concepts**, such as socket communication, multi-threading, and client-server architecture.

---

## 🧠 Features

* Establishes a TCP connection between client and server over the local network
* Supports multiple clients using Python's `threading` module
* Sends and receives messages with a fixed header to denote message size
* Recognizes a disconnect command (`!DISCONNECT`) to end the session cleanly
* Displays real-time message logs on the server side

---

## 🛠 Technologies Used

* Python 3
* `socket` module
* `threading` module

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
https://github.com/vinaymabbu/Chatproject.git
```

### 2. Start the Server

Run the server script to start listening for incoming client connections.

```bash
python server.py
```

### 3. Start the Client(s)

Run the client script in one or more terminals or devices connected to the same local network.

```bash
python client.py
```

### 4. Chat

* Type a message and press Enter to send.
* To disconnect, type:

```text
!DISCONNECT
```

---

## 📚 Educational Purpose

This project is designed for beginners who want to:

* Understand the basics of network sockets
* Learn how servers handle multiple clients using threads
* Implement a simple message protocol with headers

---

## 📦 Project Structure

```
Chatproject/
├── client.py        # The client-side script
├── server.py        # The server-side script
└── README.md        # Project overview and instructions
```

---

## 💡 Future Enhancements (Optional Ideas)

* Add a GUI using Tkinter or PyQt
* Support encrypted communication using SSL
* Allow file sharing over the network
* Implement message broadcasting to all connected clients

---

## 🙋‍♂️ Author's Note

> This chat app is a basic project I built as a student to understand networking and threading in Python. It was an exciting and valuable step toward my goals in cybersecurity and software development. Feel free to explore, modify, or expand it!

---

## 📬 Contact

If you have questions, suggestions, or feedback, feel free to reach out via GitHub issues or connect with me at: [https://github.com/vinaymabbu](https://github.com/vinaymabbu)
