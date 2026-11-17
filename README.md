# Chatting Application

A desktop-based real-time chatting application developed using **Java**. This project demonstrates client-server communication and allows users to exchange messages through a graphical user interface.

## Features

- **One-to-One Chatting:** Send and receive messages between two users.
- **Group Chatting:** Multiple users can communicate in a shared chat room.
- **Graphical User Interface:** Simple and interactive desktop chat interface.
- **Real-Time Communication:** Exchange messages through client-server architecture.
- **Multiple Clients:** Supports multiple users in the group chatting application.
- **Send Messages:** Enter messages and send them using the chat interface.

## Project Structure

```text
Chatting/
│
├── Chatting Application/
│   ├── src/
│   │   └── chatting/
│   │       └── application/
│   │           ├── Client.java
│   │           └── Server.java
│   ├── build/
│   └── build.xml
│
├── Group Chatting Application/
│   ├── src/
│   │   └── group/
│   │       └── chatting/
│   │           └── application/
│   │               ├── Server.java
│   │               ├── UserOne.java
│   │               ├── UserTwo.java
│   │               └── UserThird.java
│   ├── build/
│   └── build.xml
│
└── README.md
```

## Technologies Used

- Java
- Java Swing (GUI)
- Java AWT
- Socket Programming
- Client-Server Architecture
- VS Code / NetBeans

## Requirements

- JDK 8 or later
- Visual Studio Code or NetBeans
- Java Extension Pack (for VS Code)

## Application Workflow

1. Start the server.
2. Launch the client or multiple users.
3. The application establishes communication with the server.
4. Users enter messages in the chat interface.
5. Messages are exchanged through the client-server connection.

## Learning Outcomes

- Understanding Java Socket Programming.
- Implementing client-server communication.
- Developing desktop applications using Java Swing.
- Managing multiple client connections.
- Understanding real-time messaging concepts.

