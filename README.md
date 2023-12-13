# Real-Time Chat App with ChatEngine.io

Welcome to our real-time chat application built with ChatEngine.io! This application allows users to chat in real-time, create chat rooms, and exchange messages seamlessly.

## Features

- **Real-Time Communication:** Experience instant messaging with real-time updates.
- **Chat Rooms:** Create and join different chat rooms.
- **User Management:** Manage users, invite them to chat rooms, and send private messages.
- **File Sharing:** Share images and files within the chat.

## Getting Started

### Client Side
To run the application locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Rekl0w/Chat-App.git
```
2. Install dependencies:

```bash
cd client
npm install
```
3. Configure ChatEngine.io:

    - Get your ChatEngine.io Project ID and Private Key from ChatEngine.io.
    - Update the Project ID in .env.local.
    ```.env
    VITE_CHAT_ENGINE_PROJECT_ID=XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
    ```
    - Start the application:
```bash
npm run dev
```

Visit http://localhost:5173 in your browser to access the application.

### Server Side
1. Navigate to the server directory:
```bash
cd server
```
2. Install dependencies:
```bash
npm install
```
3. Configure Private Key in index.js.

```javascript
headers: { "Private-Key": "XXXXXXXXXXX" }`
```

4. Start the server:

```bash
npm start
```
The server will run on http://localhost:5000.

Now, you can start chatting in real-time by accessing the client application in your browser and connecting to the server.

### Technologies Used
- React.js
- ChatEngine.io
- Node.js
- Express
- HTML
- CSS

Feel free to contribute to the development of this chat application. If you find any issues or have suggestions, please open an issue or submit a pull request.
