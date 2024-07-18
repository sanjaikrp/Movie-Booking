# Movie Booking Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
  
## Introduction
The Movie Booking Project is a web application designed to allow users to browse and book movie tickets online. It provides an easy-to-use platform for checking movie showtimes, selecting seats, and making reservations.

## Features
- User registration and authentication
- Browse movies and showtimes
- Select seats and book tickets
- Payment integration
- Responsive design for both desktop and mobile

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Java
- Database: MongoDB
- Payment Gateway: Stripe API

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/sanjaikrp/Movie-Booking.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Movie-Booking
    ```
3. Install the frontend dependencies:
    ```sh
    cd client
    npm install
    cd ..
    ```
4. Install the backend dependencies:
    ```sh
    npm install
    ```
5. Set up the environment variables:
    ```sh
    cp .env.example .env
    ```
    Fill in the required values in the `.env` file, including your Stripe API keys.
6. Start the development servers:
    ```sh
    npm run dev
    ```

## Usage
1. Open your web browser and navigate to `http://localhost:3000` for the frontend.
2. Use the provided interface to register a new account or log in with an existing account.
3. Browse available movies, select showtimes, choose seats, and book your tickets.
