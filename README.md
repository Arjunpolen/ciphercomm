==============================
       CIPHERCOMM
  Secure Chat, Simplified
==============================
# ciphercomm
CipherComm is a simple, secure terminal-based chat application built in Java. It uses AES encryption for message privacy and multithreading to support multiple clients in real-time.
### How It Was Built

- Java was used to create a simple and efficient client-server chat application.  
- The server listens for multiple client connections using multithreading, allowing simultaneous chats.  
- AES encryption secures all communication between clients and the server.  
- Clients encrypt messages before sending, and the server decrypts them for safe broadcasting.  
- The server encrypts outgoing messages to clients, ensuring end-to-end security.  
- Communication protocol handles connection setup, messaging, and graceful exit commands.  
- Clients connect via TCP sockets and communicate through encrypted text streams.  
- Multithreading provides each client with a dedicated handler thread to prevent blocking.  
- The server continuously runs, dynamically accepting new clients.  
- AES key length and encryption parameters are chosen carefully to avoid vulnerabilities.  
- User input and output are handled via the terminal for simplicity and broad compatibility.  
- Code is structured for easy extension, such as adding a GUI or message history later.  
- Exception handling manages client disconnects and network errors smoothly.  
- Only Java’s built-in libraries are used, making compilation and running easy on any platform.  
- Encryption and decryption are thoroughly tested to ensure message integrity.  
- Real-time communication is achieved with minimal latency through efficient thread management.  
- The application runs on JVM, making it platform-independent.  
- No third-party dependencies keep the project lightweight and straightforward.  
- A chat history feature was added so new clients receive past conversations upon connecting.  
- This foundation allows for future additions like user authentication and more features.

