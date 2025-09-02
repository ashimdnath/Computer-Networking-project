# RealTimeChat (Java Swing + Sockets)

A simple real-time chat application built using **Java Swing** for the graphical user interface and **Java Sockets** for client-server communication.  
Supports text messaging, emoji replacement, file sharing, and profile pictures.

---

## ✨ Features
- 💬 Real-time text chat between multiple clients
- 🙂 Emoji shortcuts (`:)`, `:(`, `<3`, `:D`)
- 📁 File sharing (images & documents)
- 🖼️ Profile picture selection on startup
- ⌨️ Typing indicator ("user is typing...")
- ⏰ Message timestamps
- 🎨 Rounded avatar display

---

## 🖥️ Technologies Used
- Java (Swing, AWT, IO, Networking)
- Multi-threaded server-client communication
- Image handling (`ImageIO`)
- `DataInputStream` / `DataOutputStream`

---

## ⚙️ How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/RealTimeChat.git
cd RealTimeChat
```

### 2. Compile the code
Make sure you have **JDK 8+** installed.

```bash
javac Server.java Client.java
```

### 3. Start the server
```bash
java Server
```

The server will listen on port `50005` by default.

### 4. Start clients
Open multiple terminals or run multiple instances:

```bash
java Client
```

Each client will:
- Enter a username
- Select a profile picture
- Connect to the server and join the chat

---

## 📷 Screenshots
*(Add your screenshots here once you capture the running application)*


---

## 🚀 Future Improvements
- Private messaging (DMs)
- Message history (save chat logs)
- Encrypted communication
- Group chat rooms

---

## 📜 License
This project is open source under the [MIT License](LICENSE).
