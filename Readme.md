# Java Terminal Chat Application

This project is a simple yet powerful terminal-based chat application developed in Java. It features a server that supports multiple client connections, enabling real-time communication between users.

## Features

- **Multi-Client Support**: The server allows multiple clients to connect simultaneously.
- **Broadcast Messaging**: Messages sent by a client are broadcast to all other connected clients.
- **Unique Usernames**: Each client is uniquely identified by a username.

## Requirements

- Java Development Kit (JDK) 8 or later
- A terminal or command line interface

## Setup and Execution

### 1. Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/QuanTran086/chat-application.git
cd chat-application
```

### 2. Compile the Java Files

Next, compile the server and client Java files. Open a terminal in the project directory and execute the following commands:

```bash
javac Server.java
javac Client.java
```

### 3. Start the Server

To launch the server, run the following command in your terminal:

```bash
java Server
```

### 4. Connect a Client

To connect a client to the server, open a new terminal window or tab and run:

```bash
java Client
```
