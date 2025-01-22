# MovieTix

A full-stack MERN movie ticket booking application with secure user authentication and responsive design.

## Features

- User authentication with JWT
- Movie browsing and searching
- Booking management
- Responsive mobile-first UI
- Redux state management

## Tech Stack

- MongoDB - Database
- Express.js - Backend framework
- React.js - Frontend library
- Node.js - Runtime environment
- Redux - State management
- Material-UI - UI components
- JWT - Authentication

## Installation

```bash
# Clone repository
git clone https://github.com/aryanmishra/MovieTix.git

# Install dependencies for server
cd MovieTix
npm install

# Install dependencies for client
cd client
npm install

# Run server and client concurrently
npm run dev
```

## Environment Variables

Create a `.env` file in the root directory:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

## Usage

1. Register/Login to access booking features
2. Browse available movies
3. Select show time and seats
4. View booking history

## API Endpoints

- `POST /api/auth/register` - Register user
- `POST /api/auth/login` - Login user
- `GET /api/movies` - Get all movies
- `POST /api/bookings` - Create booking
- `GET /api/bookings/user` - Get user bookings

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT
