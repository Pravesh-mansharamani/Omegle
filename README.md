# Omegle Clone 

## Technologies Used : React.js, Node.js, Socket.io, Express.js, WebRTC 

## Features :
- 2 people can connect and chat with each other.
- Max number of rooms server can handle at a time is 500. So, total 1000 users at once
- If a room is full, the user will be redirected to a new room.
- If a user leaves the room, the other user will be redirected to a new room.

## How to Setup : 
1. Clone the reop : 
```bash
git clone https://github.com/Pravesh-mansharamani/Omegle.git 
```

2. Install frontend dependencies : 
```bash
cd client
npm i 
```

3. Start the frontend server : 
```bash
npm run dev
```

4. Install backend dependencies : 
```bash
cd server
npm i 
```

5. Start the backend server : 
```bash
tsc -b
dist/index.js
```


