# University Management System - Client

A comprehensive university management system client application built with React and Redux. This client-side application communicates with a backend server to manage university resources such as semesters, courses, and course offerings.

## Features

- User authentication with JWT and refresh token
- Semester management
- Course management
- Course offering management
- Error handling with toast notifications
- Responsive user interface

## Technologies Used

- React
- Redux Toolkit & RTK Query
- TypeScript
- React Router
- Sonner (for toast notifications)
- Modern CSS/SCSS

## Getting Started

### Prerequisites

- Node.js (version 14.x or higher)
- npm or yarn
- Backend server running at http://localhost:5000

### Installation

1. Clone the repository

```bash
git clone <repository-url>
cd L2B3-PH-university-client
```

2. Install dependencies

```bash
npm install
# or
yarn
```

3. Start the development server

```bash
npm start
# or
yarn start
```

4. Open your browser and navigate to http://localhost:3000

## API Integration

The application communicates with a RESTful API at http://localhost:5000/api/v1. The API requires authentication for most endpoints. The client handles authentication tokens automatically and refreshes them when needed.

### API Features

- Authentication (login, register, refresh token)
- Semester management
- Course management
- Offered course management

## Project Structure

```
src/
├── components/       # Reusable UI components
├── pages/            # Application pages
├── redux/            # Redux state management
│   ├── api/          # RTK Query API definitions
│   ├── features/     # Redux slices
│   └── store.ts      # Redux store configuration
├── types/            # TypeScript type definitions
├── utils/            # Utility functions
└── App.tsx           # Main application component
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
