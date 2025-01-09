
NAME: DERUNGULA VENKATADRI

COMPANY: CODTECH IT SOLUTION

ID::CT08DVW 

DOMAIN: JAVA PROGRAMMING

DURATION: DEC17 2024 TO JAN17 2025

MENTOR: N.SANTHOSH

**#Chat Application using Java Sockets and Multithreading**

**Overview**

This project implements a simple client-server chat application using Java sockets and multithreading.
The server can handle multiple clients simultaneously, allowing real-time messaging between connected users.
It demonstrates core networking concepts and thread management in Java.

**Features**

Multi-client support: Multiple users can connect to the chat server simultaneously.
Broadcast messages: Messages sent by a client are broadcast to all other connected clients.
Real-time communication: Uses Java sockets for instant messaging.
Threaded architecture: Each client connection is handled by a separate thread on the server.

**Technologies Used**

Java: Programming language for both client and server components.

Java Sockets: For network communication between clients and the server.

Multithreading: To manage multiple clients efficiently on the server.

**How It Works**

**Server**:

Starts on a specified port (default: 12345).
Listens for client connections.

Creates a new thread for each client, ensuring that all clients can communicate simultaneously.

Broadcasts messages received from one client to all other clients.

**Client:**

Connects to the server on the same port.
Sends messages to the server, which are then broadcast to all other connected clients.
Displays messages received from the server in real time.
Setup and Usage
Prerequisites
Java Development Kit (JDK) installed.
Basic understanding of Java and networking.

**Possible Enhancements**

Add user authentication for secure messaging.
Implement private messaging between specific clients.
Add a GUI using JavaFX or Swing for a more user-friendly interface.
Integrate timestamps with messages.
Add persistent message storage using a database.

![Screenshot (22)](https://github.com/user-attachments/assets/c2cb1ac3-223f-4b6c-a0f0-8f7019d6c4fa)

![Screenshot (23)](https://github.com/user-attachments/assets/ea840a28-a317-49f5-983d-560108fba94d)


