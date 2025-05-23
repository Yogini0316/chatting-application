# 💬 Java Chatting Application

A simple two-way chatting application built in Java using socket programming. The application consists of two classes: **Server** and **Client**, designed to send and receive text messages over a local network.

---

## 🧑‍💻 Developed With

- **Language**: Java  
- **IDE**: NetBeans  
- **Architecture**: Socket-based (TCP/IP)  
- **Classes**:
  - `Server.java`
  - `Client.java`
- **Database**: None (currently)

---

## 📁 Project Structure

ChattingApp/
│
├── Server.java # Handles incoming client connections and receives messages
├── Client.java # Connects to the server and sends messages
└── README.md

---

## 🔌 How It Works

- The **Server** waits for incoming connections on a specified port.
- The **Client** connects to the server using the IP address and port.
- Both programs use `Socket` and `ServerSocket` for communication.
- Messages are transmitted via input/output streams.

---

## 🏃‍♂️ How to Run (in NetBeans)

1. **Clone or Download the project** to your local machine.

2. **Open the project in NetBeans**:
   - File → Open Project → Select the folder containing `Server.java` and `Client.java`.

3. **Run the Server**:
   - Right-click on `Server.java` → Run File

4. **Run the Client**:
   - Right-click on `Client.java` → Run File
   - You can run multiple clients to simulate multiple users.

> 🔁 The server must be running before starting the client.

---

## 🧪 Sample Output

[Server Console]
Client connected.
Client: Hello!
Server: Hi there!

[Client Console]
Connected to server.
Server: Hi there!
Client: Hello!


---

## 📌 Features

- Real-time chat via TCP sockets
- Simple console-based interface
- Easy to extend for multiple clients (with threading)

---

## 🚀 Future Improvements

- [ ] GUI using Java Swing or JavaFX
- [ ] Support for multiple clients (threaded server)
- [ ] Message logging or chat history
- [ ] Add file-sharing feature

---

## 👩‍💻 Author

- **Yogini Sonawane**  
  [GitHub: Yogini0316](https://github.com/Yogini0316)

---

## 📄 License

This project is for learning and educational purposes only.
