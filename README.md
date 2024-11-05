Hotel Booking Application

Welcome to the Hotel Booking Application! This application enables users to book hotels in multiple cities, manage bookings, and view hotel details with ease. Built with the MERN stack, this app offers a responsive, dynamic user interface along with a secure, scalable backend.
Table of Contents

    Objective
    Features
    Tech Stack Used
    Project Structure
    Getting Started
    Usage
    Future Scope
    Contributors

Objective

The objective of this application is to provide a convenient and user-friendly platform for booking hotel rooms across multiple cities, allowing users to browse, search, and sort hotels according to their preferences.
Features

    User Authentication: Secure registration, login, and JWT-based authentication.
    Hotel Search: Browse hotels in London, Madrid, and Berlin.
    Room Booking: View room details and availability, and book rooms.
    Sorting and Filtering: Sort by price, filter by room type, and more.
    Responsive Design: Accessible on desktops, tablets, and mobile devices.
    Booking History: Users can view and manage past bookings.

Tech Stack Used
Frontend

    React: For building the UI with reusable components.
    CSS: For responsive and visually appealing design.

Backend

    Node.js and Express: To create a secure, fast, and RESTful API.
    MongoDB: For storing user, hotel, and booking data, managed with Mongoose for schema validation and data consistency.

Project Structure

    /api: Contains the backend code, including routes, models, and controllers.
        models: Defines the data structure for users, hotels, and rooms.
        controllers: Contains the logic for handling API requests.
        routes: Defines routes for user, hotel, and booking functionalities.

    /client: Contains the frontend code built with React, including components, pages, and assets.

Getting Started

Follow these steps to set up the project locally:
1. Clone the Repository

bash

git clone <repository-url>

2. Navigate to the Project Directory

bash

cd <project-folder>

3. Set Up the Backend

    Navigate to the api directory:

    bash

cd api

Install backend dependencies:

bash

npm install

Set up environment variables (e.g., MongoDB connection string, JWT secret) in an .env file in the api directory:

plaintext

MONGODB_URI=your-mongodb-connection-string
JWT_SECRET=your-jwt-secret

Start the backend server:

bash

    npm start

    The server will start on http://localhost:5000 (or the specified port in your environment variables).

4. Set Up the Frontend

    Navigate to the client directory:

    bash

cd ../client

Install frontend dependencies:

bash

npm install

Start the frontend server:

bash

    npm start

    The client application will start on http://localhost:3000.

Usage

Once the servers are running, you can start using the app:

    Open the client in your browser: http://localhost:3000.
    Register and Login to access the application’s features.
    Browse Hotels by selecting a city (London, Madrid, Berlin).
    View Room Details and Book a Room as per your needs.
    Use the Sort and Filter options to refine your search by price, rating, and room type.
    Check Your Bookings under the user profile to view your booking history.

Future Scope

This application is designed with scalability in mind, allowing for the following future enhancements:

    Additional Cities: Add more cities to expand hotel booking options.
    User Reviews and Ratings: Implement a review system for users to rate their experiences.
    Payment Integration: Allow users to pay for bookings directly through the app.
    Admin Dashboard: Create a dashboard for hotel owners to manage listings and view bookings.
    Recommendation System: Suggest hotels based on user preferences and booking history.

Contributors
Work Distribution

    Mayur: Frontend design and implementation using React, JSX, CSS, and API integration for connecting to the backend.
    Hriday: Backend development with Node.js, Express, and MongoDB, implementing secure authentication, data modeling, and the main API endpoints.
