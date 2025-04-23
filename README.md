# Assessment 2 - Chat Application

## Features

-  Real-time message broadcasting between users
-  Typing indicator when a user is typing in the chat
-  User list display showing all currently connected users
-  Notifications when users join or leave the chat
-  Fully responsive design for mobile, tablet, and desktop
-  Navigation links across pages

## Pages

- index.html - Home page with welcome
- chat.html - The main chat interface
- about.html - About/project info and external resources

## Development Approach

The chat logic uses a client-server model
- The server (in index.js) handles connections, broadcasts events, and maintains an active user list using Set.
- The client (in chat.js) listens and emits socket events (chat message, typing, new user, `disconnect) and dynamically updates the UI.

Used HTML5 structures to ensure accessibility and maintainability. CSS styling was validated and consistently applied across all pages, with responsiveness built via flexbox and media queries.

## Technical Stack

- Front-End: HTML5, CSS3, JavaScript 
- Back-End: Node.js, Express
- WebSockets: Socket.IO

## Challenges Faced

- Ensuring reliable join/leave notifications across all connected users
- Updating the active user list in real time
- Keeping message formatting clean and scrollable on all screen sizes

## How to Run

1. Clone the repo:
   git clone https://github.com/your-username/your-repo.git
2. Navigate to project folder
   cd your-repo
3. Install dependencies (once) 
   npm Install
4. Navigate to directory
   cd ~/workspace/Assessment2/CA4
5. Start the server
   node index.js
6. Open browser and go to 
   http://localhost:5000




