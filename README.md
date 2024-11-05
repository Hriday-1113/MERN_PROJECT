# Hotel Booking App

## Overview

This is a MERN stack application designed to facilitate hotel bookings in three popular European cities: **London**, **Madrid**, and **Berlin**. The app allows users to browse available hotels, register/login to manage bookings, and sort options by price and other criteria for easy navigation.

## Features

- **User Authentication**: Secure login and registration for personalized experiences.
- **Hotel Search & Booking**: Search hotels in London, Madrid, or Berlin, and book rooms directly.
- **Price Sorting**: Sort hotel listings by price to quickly find options within a budget.
- **User-Friendly Interface**: Responsive design optimized for various devices.

## Tech Stack

- **Frontend**: React, with CSS for styling
- **Backend**: Node.js, Express.js
- **Database**: MongoDB for data storage
- **Authentication**: JSON Web Tokens (JWT) for secure user authentication

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd booking-app

    Install dependencies:

    bash

npm install
cd client
npm install

Set up environment variables: Create a .env file in the root and add the following:

plaintext

MONGODB_URI=<your-mongodb-uri>
JWT_SECRET=<your-secret-key>

Run the application:

    Start the server:

    bash

npm run dev

Start the client:

bash

        cd client
        npm start

    Access the application at http://localhost:3000.

Usage

    Login/Register: Create an account or log in to manage your bookings.
    Browse Hotels: Choose from a variety of hotels in London, Madrid, and Berlin.
    Book Rooms: Select your desired room and confirm the booking.
    Sort Options: Sort hotels by price to find suitable options.

Future Enhancements

    Additional cities and hotels.
    User reviews and ratings for each hotel.
    Enhanced sorting and filtering options.
