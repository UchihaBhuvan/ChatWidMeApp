# Tsukuyomi
ChatWidMe is a web-based chat application built using the MERN stack, offering a user-friendly platform for real-time communication. Here's a breakdown of its functionalities and the MERN stack components involved:

**Features:**

**User Registration and Login**: Users can create accounts with usernames and passwords for secure access.
**Real-time Chat**: ChatWidMe facilitates instant messaging between users through a persistent chat connection.
**Private Messaging**: Users can engage in one-on-one conversations with their contacts.
**Contact List**: Users can add friends and manage their contact list for easy access.

**MERN Stack Implementation:**

MongoDB: The NoSQL database stores user data, chat history, and contact information.
Express.js: The Node.js web framework handles server-side logic, user authentication, routing, and API communication.
React.js: This JavaScript library builds the interactive user interface for the chat application. Users can see their contact list, chat windows, and message history in real-time.
Node.js: The JavaScript runtime environment acts as the foundation for the server-side functionality. It powers the Express.js server and enables real-time communication using technologies like web sockets.

Additional Considerations:

Scalability: The MERN stack is known for its scalability, allowing ChatWidMe to handle a growing number of users efficiently.
Security: Security features like password hashing and data encryption are crucial to protect user data and ensure a safe communication platform.
Real-time Communication: Websockets or similar technologies enable real-time message exchange between users without constant page reloads.


**How to start the app:**
Requirements: Node JS, Mongo DB
Go to the public folder an install yarn...
Then type 'yarn start' in cmd.
