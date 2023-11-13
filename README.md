# Cinema Booking System (Backend)

The Cinema Booking System is a web application that allows users to browse movies, book tickets, and manage their bookings. 

At the same time, it allows admin to manage the users, movie lists, and orders. 

This backend repository contains the server-side code for the application using Java Spring.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Deployment](#deployment)
- [API Integration](#api-integration)
- [Contributing](#contributing)
- [License](#license)

## Features
### User :
- Browse a list of movies, view movie details and search for a movie.
- User registration and login. (Using JWT token and Spring Security)
- Book movie tickets and view booking history.
- Cancel orders.
- Reset Password.

### Admin :
- #### Movie management :
  - Add movies with specific sessions and seats.
  - Edit Movies
  - Delete Movies
- #### Order management :
  - Filter all the orders with movie title, order date, user Id, total price, etc.
  - Update Order Status such as cancel, confirm or complete the order.
- #### User management :
  - Block user accounts.
  - Edit users information such as password, username and phone number.
  - View all the users information and filter with username, create date, or email.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java installed on your machine.
- A Frontend for the Cinema Booking System. (Please refer to `https://github.com/naya0000/MovieTheater__Frontend`
- A movie_project.sql file imported and connected to the server.

## Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

1. Clone the repository:

   ```bash
   git clone https://github.com/naya0000/MovieTheater__Backend.git
2. Navigate to the project directory:
   ```bash
   cd MovieTheater__Backend
3. Start the development server:
   ```bash
   press `run application`
4. Start the frontend server at the same time
   
5. Open your browser and visit http://localhost:3000/cinemas

## Project Structure

- `src/`: Contains the source code for the application.
  - `components/`: Reusable components used throughout the app.
  - `pages/`: Top-level pages/routes of the application.
    - `UserLogin/`: User login page
    - `UserSignUp/`: User sign up for new account.
    - `UserEdit/`: User edit account information.
    - `UserEditPassword/`: User change password.
    - `MovieListPage/`: List released and upcoming movies.
    - ``
  - `services/`: Services for making API requests.
  - `utils/`: Utility functions and constants.
- `public/`: Static assets and HTML template.