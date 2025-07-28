# NextMeet - A video conferencing platform that allows people to connect through

A real-time video conferencing application built with React, Node.js, Socket.IO, and MongoDB.

## Features

- Real-time video and audio communication
- Screen sharing capability
- Chat functionality during video calls
- User authentication and authorization
- Meeting history tracking
- Responsive design

## Tech Stack

### Frontend
- React.js
- Material-UI
- Socket.IO Client
- WebRTC

### Backend
- Node.js
- Express.js
- Socket.IO
- MongoDB
- Mongoose

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd zoom-clone
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

4. Create a `.env` file in the backend directory and add your MongoDB connection string:
```
MONGODB_URI=your_mongodb_connection_string
```

5. Start the backend server:
```bash
cd backend
npm run dev
```

6. Start the frontend development server:
```bash
cd frontend
npm start
```

The application should now be running on:
- Frontend: http://localhost:3000
- Backend: http://localhost:8000

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
