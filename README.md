# Chat Application Backend

This is the backend server for a real-time chat application built with Node.js, Express, and Socket.IO.

## Features

- Real-time messaging using Socket.IO
- Room-based chat system
- User presence tracking
- Message history per room
- Automatic cleanup of inactive rooms

## Requirements

- Node.js >= 18.0.0
- npm or yarn

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
PORT=3000
FRONTEND_URL=http://your-frontend-url
```

## Running the Server

Development mode:
```bash
npm run dev
```

Production mode:
```bash
npm start
```

## Deployment on Railway

1. Create a new project on Railway
2. Connect your GitHub repository
3. Add the required environment variables in Railway dashboard
4. Deploy the application

The server will automatically start using the `npm start` command defined in `package.json`.