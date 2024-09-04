# Node.js Raw Web Socket

This project demonstrates how to create a basic WebSocket server using Node.js without relying on any external WebSocket libraries. It's a great starting point for understanding the fundamentals of WebSocket communication in a Node.js environment.

## Features

- Raw WebSocket implementation in Node.js
- Simple client-side JavaScript for WebSocket interaction
- Real-time bidirectional communication between server and client

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 18.0 or higher recommended)
- npm (usually comes with Node.js)

## Installation

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/albugowy15/nodejs-raw-websocket.git
   ```

2. Navigate to the project directory:

   ```
   cd nodejs-raw-websocket
   ```

3. Install the development dependencies (for running with nodemon):
   ```
   npm install
   ```

## How to Run

1. Start the WebSocket server:

   ```
   npm run start
   ```

   This command will use nodemon to run the server, automatically restarting it when you make changes to the code.

2. Open the `index.html` file in your web browser. You can do this by:

   - Double-clicking the file in your file explorer
   - Drag and dropping the file into your browser
   - Using a local development server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code

3. You should now see the client interface in your browser, connected to the WebSocket server.

## Project Structure

- `server.mjs`: The Node.js WebSocket server implementation
- `index.html`: The client-side HTML and JavaScript for interacting with the WebSocket
- `package.json`: Project configuration and dependencies

## How It Works

1. The server listens for incoming WebSocket connection requests.
2. When a client connects, it performs the WebSocket handshake.
3. After a successful handshake, the server can send and receive messages to/from the client.
4. The client JavaScript establishes a WebSocket connection and provides a simple interface for sending messages and displaying received messages.
