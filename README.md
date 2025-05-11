# Confession App

A full-stack web application that allows users to share their confessions anonymously in a safe and supportive environment. Built with React, Node.js, and MongoDB.

## Features

- 🔐 Anonymous confession sharing
- 🎨 Modern and responsive UI with glass morphism design
- 🔍 Search functionality for confessions
- 📱 Mobile-friendly interface
- 🎯 Category-based organization
- 💬 Interactive user engagement
- 🔒 Secure and private platform
- 🔄 Real-time updates
- 📊 User analytics
- 🛡️ Content moderation

## Tech Stack

### Frontend
- **Framework**: React + Vite
- **Styling**: Tailwind CSS
- **Icons**: React Icons
- **State Management**: React Context API
- **Routing**: React Router DOM
- **HTTP Client**: Axios

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **Validation**: Joi
- **API Documentation**: Swagger/OpenAPI
- **Testing**: Jest

## Project Structure

```
confession-app/
├── frontend/                # React frontend application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── context/       # React context providers
│   │   ├── assets/        # Static assets
│   │   ├── styles/        # Global styles
│   │   └── App.jsx        # Main application component
│   ├── public/            # Public assets
│   └── index.html         # Entry HTML file
│
└── backend/               # Node.js backend application
    ├── src/
    │   ├── config/       # Configuration files
    │   ├── controllers/  # Route controllers
    │   ├── middleware/   # Custom middleware
    │   ├── models/       # Database models
    │   ├── routes/       # API routes
    │   ├── services/     # Business logic
    │   └── utils/        # Utility functions
    └── tests/            # Test files
```

## Getting Started

### Prerequisites

- Node.js (v14.0.0 or higher)
- MongoDB (v4.4 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone [repository-url]
cd confession-app
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
# or
yarn install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
# or
yarn install
```

4. Set up environment variables:
   - Create `.env` file in the backend directory
   - Add the following variables:
   ```
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

5. Start the development servers:

Frontend:
```bash
cd frontend
npm run dev
# or
yarn dev
```

Backend:
```bash
cd backend
npm run dev
# or
yarn dev
```

6. Access the application:
   - Frontend: `http://localhost:5173`
   - Backend API: `http://localhost:5000`

## API Documentation

The API documentation is available at `http://localhost:5000/api-docs` when the backend server is running.

### Main API Endpoints

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - User login
- `GET /api/confessions` - Get all confessions
- `POST /api/confessions` - Create a new confession
- `GET /api/confessions/:id` - Get a specific confession
- `PUT /api/confessions/:id` - Update a confession
- `DELETE /api/confessions/:id` - Delete a confession

## Features in Detail

### Frontend Pages

#### Home Page
- Featured confessions
- Category navigation
- Search functionality
- Trending confessions

#### Confession Page
- Detailed confession view
- Comments section
- Related confessions
- Share functionality

#### About Page
- Team information
- Project mission
- Contact details

#### FAQ Page
- Common questions and answers
- User guidelines
- Privacy policy

### Backend Services

#### Authentication Service
- User registration
- User login
- Password reset
- Email verification

#### Confession Service
- CRUD operations for confessions
- Category management
- Search and filtering
- Content moderation

#### Analytics Service
- User engagement metrics
- Popular confessions
- Category statistics

## Testing

### Frontend Tests
```bash
cd frontend
npm run test
# or
yarn test
```

### Backend Tests
```bash
cd backend
npm run test
# or
yarn test
```

## Deployment

### Frontend Deployment
1. Build the frontend:
```bash
cd frontend
npm run build
# or
yarn build
```

2. Deploy the `dist` folder to your hosting service (e.g., Vercel, Netlify)

### Backend Deployment
1. Set up environment variables on your hosting service
2. Deploy to your preferred platform (e.g., Heroku, DigitalOcean)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For any queries or support, please reach out to:
- Email: anaschaudhary1151@gmail.com

## Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for their invaluable tools and resources
