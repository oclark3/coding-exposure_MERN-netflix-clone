# MERN Netflix Clone 🎥

## Description

The purpose of this project is to serve as a learning experience to expose me to building a full-stack web application using the MERN (MongoDB, Express.js, React.js, Node.js) stack. This project is a Netflix clone that was created by following @asaprogrammer_'s step-by-step YouTube tutorial: 
- [YouTube Tutorial](https://www.youtube.com/watch?v=gRroBZczKAU)
- [Tutorial's GitHub Repo](https://github.com/burakorkmez/mern-netflix-clone?tab=readme-ov-file)

## Features:

- Responsive Netflix-like UI designed with React and Tailwind CSS
- API integration to fetch movie data
- User authentication with JWT
- Search functionality

# How to Set the Project Up Locally

## Prerequisites

Ensure you have the following installed on your machine:

- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB

## Getting Started

1. Clone the repository and go into folder:
git clone https://github.com/oclark3/coding-exposure_MERN-netflix-clone.git

cd coding-exposure_MERN-netflix-clone

2. Go into backend and frontend folders and install dependencies:
cd backend
npm install
cd ../frontend
npm install

3. Create a .env file in the backend directory with the following content:
PORT=5000
MONGO_URI=your_mongo_uri
NODE_ENV=development
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key

Replace the placeholder values with your own:

your_mongo_uri: Your MongoDB connection string.
your_jwt_secret: A secret key for JWT authentication.
your_tmdb_api_key: Your API key from The Movie Database (TMDb).

4. Navigate to the frontend directory and build the React application:
cd ../frontend
npm run build

5. Start the application in the backend directory:
cd ../backend
npm start

- The application should now start in localhost:5000