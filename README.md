# 💬 Multi-User Chat System (Java Socket Programming)

## 📘 Overview
This project is a **Java-based multi-client chat system** built using **Socket Programming**.  
It demonstrates how multiple clients can communicate with each other in real time through a **central server** using TCP connections.

The system consists of:
- A **Server** that listens for client connections and manages message broadcasting.
- Multiple **Clients (UserOne, UserTwo, UserThird)** that connect to the server and exchange messages.

---

## ⚙️ Features
- ✅ Real-time chat between multiple users  
- ✅ Multi-threaded server to handle multiple clients simultaneously  
- ✅ Simple console-based interface  
- ✅ Easy to run on any Java-supported system  
- ✅ Demonstrates core Java networking concepts  

---

## 🧩 Project Structure
📁 JavaChatSystem/
│
├── Server.java # Server program to handle client connections and message distribution

├── UserOne.java # Client 1 implementation

├── UserTwo.java # Client 2 implementation

├── UserThird.java # Client 3 implementation

└── README.md # Project documentation


---

## 🧠 How It Works
1. **Server (Server.java)**  
   - Starts on a specific port and waits for incoming client connections.  
   - Each connected client is assigned a dedicated thread.  
   - Messages received from one client are broadcasted to all others.

2. **Clients (UserOne.java, UserTwo.java, UserThird.java)**  
   - Each client connects to the server using the same IP and port.  
   - Users can send and receive messages in real time.  

---

## 🛠️ Requirements
- Java JDK 8 or above  
- Any text editor or IDE (VS Code, IntelliJ IDEA, Eclipse, etc.)  
- Terminal/Command Prompt for running programs  

---

## 🚀 How to Run

### 1️⃣ Compile all files
Open your terminal in the project directory and run:
```bash
javac Server.java UserOne.java UserTwo.java UserThird.java
2️⃣ Start the Server
java Server


Expected Output:

Server started and waiting for clients...

3️⃣ Run Clients (in separate terminals)
java UserOne
java UserTwo
java UserThird


Each client will connect to the server and can start chatting instantly.

🧪 Example Output
Server Console:
Server started and waiting for clients...
UserOne connected.
UserTwo connected.
UserThird connected.
Broadcast: UserOne says Hello everyone!
Broadcast: UserTwo says Hi UserOne!

Client Console (UserOne):
Connected to server.
Type your message:
Hello everyone!
UserTwo: Hi UserOne!

💡 Concepts Demonstrated:
Java Socket Programming (Socket, ServerSocket)
Input/Output Streams (BufferedReader, PrintWriter)
Multi-threading (Thread class for each client)
Client-Server Communication Model
Message Broadcasting Logic

🔮 Future Enhancements:
🧑‍💻 GUI using JavaFX or Swing
🔐 Encrypted messaging
👥 User authentication and custom usernames
📁 File transfer between users
```
## Project Explanation Video:
https://www.loom.com/share/9bc7c536ae91419cbb9c4354055e028a

👩‍💻 Author
Khyati Kumari
🎓 B.E. in Computer Science & Engineering
📧 khyatikash1604@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/khyati-kumari-nwd/)

🪪 License
This project is licensed under the MIT License.
You’re free to use for learning and research.
