


![ChatApp](https://github.com/IlKostadinovski/ChatApp/assets/90513974/725b3344-ca9a-4e0a-abe7-644783229220)



This ChatApp is a server-side application written in C# for managing real-time communication between clients. Here's a detailed explanation of its components and functionality:

1. Architecture
Client-Server Model: The app uses a client-server architecture where the server handles connections, message routing, and user management.
TCP Sockets: It uses TCP sockets for communication between the server and clients.
2. Features
User Authentication: Users can register and log in. User data is stored in a SQLite database.
Real-time Messaging: Messages are sent and received in real-time using TCP sockets.
User Presence: Tracks and broadcasts the online/offline status of users.
Image Sending: Supports sending large images between users.
Emoji Sending: Allows users to send emojis.
3. Technologies Used:
C#: The primary programming language used.
XAML is used for the interface.
TCP Sockets: For real-time communication.
SQLite: For storing user data.
Dapper: For database operations.
 
