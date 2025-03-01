# CHATAPP

*Company*: CODTECH IT SOLUTION

*Name*: Shubham Bukam

*Intern Id*: CT6WMCP

*Domain*: Java Programming

*Duration*: 6 weeks 

*Mentor*: Meela Santosh
## This Java-based Client-Server Chat Application utilizes Sockets and Multithreading to enable real-time communication between multiple clients and a central server. The server listens for incoming connections using a ServerSocket and assigns each connected client to a separate thread for concurrent processing. Clients connect to the server via Socket, allowing bidirectional message exchange.

The server maintains a list of active clients and broadcasts messages received from one client to all others, ensuring seamless group communication. Synchronization is used to manage multiple clients efficiently.

On the client side, a dedicated thread continuously listens for messages from the server, while the main thread handles user input and message transmission. This implementation supports multiple users, ensuring responsiveness and smooth chat functionality.

The program is designed to be run in Eclipse IDE and supports multiple client connections in real-time. It demonstrates core networking concepts, thread management, and socket programming in Java.

# OUTPUT
## Client Console:
![Image](https://github.com/user-attachments/assets/ef42cb2f-086f-4956-9ac4-10aaac4c7248)

## Server Console:
![Image](https://github.com/user-attachments/assets/300c079b-1878-4bd5-a0f9-ab3e209b5e80)
