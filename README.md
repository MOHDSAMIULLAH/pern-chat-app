# PERN Stack Project: Real Time Chat App | Postgres, TypeScript, Prisma

This is a real-time chat application built using the PERN stack (PostgreSQL, Express, React, Node.js), TypeScript, Socket.IO, Prisma, and TailwindCSS. It features real-time messaging, JWT-based authentication, online user status management, and a modern UI design with glassmorphism effects.

## Live Link: https://pern-chat-app-master-qq4p.onrender.com/

![alt text](<Screenshot from 2024-12-07 12-14-11.png>)

## Features

- **Real-time Messaging:** Seamless communication using Socket.IO.
- **JWT Authentication & Authorization:** Secure user authentication and login.
- **Online User Status:** Manage and display online/offline user status in real-time.
- **State Management:** Global state management using Zustand.
- **Error Handling:** Comprehensive error handling on both the server and client sides.
- **UX/UI:** Audio alerts for incoming messages, shaking effect on new messages, auto-scrolling to the bottom for new content, and a glassmorphism effect for the chat background.
- **Deployment:** Deployed the app for free using Render.

## Tech Stack

- **Frontend:** React, TypeScript, TailwindCSS
- **Backend:** Node.js, Express, PostgreSQL, Prisma, Socket.IO
- **Authentication:** JWT
- **State Management:** Zustand
- **Deployment:** Deployed on free hosting platforms

## Getting Started

### Prerequisites

- Node.js
- PostgreSQL

# Run Locally

### Setup .env file

```js
DATABASE_URL=...
JWT_SECRET=...
NODE_ENV=...
PORT=...
```

### Install dependencies

```shell
npm install
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```


