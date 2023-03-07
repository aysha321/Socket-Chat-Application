# Socket-Chat-Application
# Chat App
This is a simple chat application built using Node.js and Socket.io.
Users can join the chat room by entering their username and password.
After successful login, they can send messages to everyone in the chat room or to specific users by using the "Where to" input field.

# Technologies used
Node.js
Socket.io
jQuery

# File Structure
index.html - contains the HTML markup for the chat application
script.js - contains the JavaScript code to interact with the Socket.io server
server.js - contains the Node.js code to start the Socket.io server and handle client connections

# How it works
The client-side code uses Socket.io to establish a connection with the server. After successful connection, it sends a "login" event to the server with the username and password entered by the user.

The server-side code verifies the user's credentials and adds them to the list of connected users. The server also listens for incoming messages from the clients and broadcasts them to all users in the chat room or to specific users based on the "Where to" input field.

The client-side code listens for incoming messages from the server and displays them in the chat box. The user can send messages by entering the message text in the "Message To Send" input field and clicking the "SEND" button.
