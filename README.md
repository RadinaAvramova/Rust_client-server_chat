# Rust Client-Server Chat
Welcome to the Rust Client-Server Chat project! This Rust application provides a simple chat system where clients can connect to a server and exchange messages in real-time. With the Rust Client-Server Chat, users can communicate with each other over a network using a client-server architecture.

## Features
1. **Client-Server Communication:** Enables communication between multiple clients and a central server using TCP/IP sockets.

2. **Real-Time Messaging:** Allows clients to send and receive messages in real-time, facilitating instant communication between users.

3. **Server Management:** Provides server-side functionality for handling client connections, routing messages between clients, and managing chat rooms or channels.

4. **Client Interaction:** Allows clients to connect to the server, send messages, and receive messages from other clients connected to the same server.

5. **Multi-Platform Support:** Supports communication between clients running on different platforms (e.g., Windows, Linux, macOS) and connecting over a network.

## Installation
To run the Rust Client-Server Chat application, follow these steps:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/Rust_client-server_chat.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd Rust_client-server_chat

3. **Build the Application:** Build the Rust binaries for the client and server using Cargo, the Rust package manager:

cargo build

## Usage
1. **Start the Server:** Run the server binary to start the chat server:
   
cargo run --bin server

2. **Connect Clients:** Run the client binary on one or more machines to connect clients to the server:

cargo run --bin client

3. **Enter Username:** Enter a unique username for each client when prompted.

4. **Send Messages:** Type messages in the client terminal and press Enter to send them to the server and other connected clients.

5. **Receive Messages:** View messages from other clients in real-time as they are received by the server and relayed to connected clients.

6. **Disconnect:** Exit the client application to disconnect from the server and end the chat session.

## Customization
1. **User Interface:** Customize the client-side user interface to enhance the chat experience, add features, or improve usability.

2. **Server Configuration:** Modify server settings such as port number, maximum connections, or message handling logic to suit your requirements.

3. **Encryption and Security:** Implement encryption and security measures to protect communication between clients and the server, such as TLS/SSL encryption.
