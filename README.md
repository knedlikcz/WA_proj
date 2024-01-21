Chat-app

1. Node.js:

    A driving force for server-side development, enabling robust JavaScript functionality.

2. Socket.io:

    Revolutionizing real-time communication, fostering seamless interactions between clients and servers.

3. REST API:

    Tailor your chat experience with precision through endpoints designed for message retrieval.

4. HTML/CSS/JavaScript:

    Crafted front-end components enhance the user experience with a visually appealing interface.

5. Express:

    Providing the foundational framework that supports the entire application.

Dive into WebSocket Dynamics

WebSocket communication adds a dynamic symphony to the chat experience:

    The server establishes a WebSocket connection, orchestrating real-time interactions with Socket.io.
    Users announce their presence using the 'join' event upon entering a chat room, triggering server broadcasts for a harmonious experience.
    Messages seamlessly flow through 'message' events, dynamically broadcasted by the server to all room occupants.
    Front-end magic unfolds with Socket.io, ensuring a real-time update of the chat interface.

Explore RESTful Endpoints

Unlock the potential of our RESTful API through strategic endpoints:

    Global Chat Pulse
        URL: /api/messages
        Method: GET
        Purpose: Immerse yourself in the rich tapestry of all chat messages.

    User's Echo Chamber
        URL: /api/messages/user/:username
        Method: GET
        Purpose: Tailor your chat experience by delving into messages linked to a specific user.

    Room Symphony
        URL: /api/messages/room/:room
        Method: GET
        Purpose: Immerse yourself in a specific room's chat symphony.

    Keyword Mosaic
        URL: /api/messages/contains/:word
        Method: GET
        Purpose: Curate your chat content by fetching messages containing a specified keyword.

Quick Launch Guide

Embark on your conversational adventure with ChatSphere:

    Open the command prompt and navigate to the repository folder.
    Initiate npm: npm init -y.
    Install dependencies: npm install express socket.io.
    Launch the server: node app.js.
    Open your web browser and let the conversations flow at http://localhost:8080.