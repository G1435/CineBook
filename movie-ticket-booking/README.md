# Movie Ticket Booking Web Application

## Overview
This project is a complete Movie Ticket Booking Web Application built using the MERN stack (MongoDB, Express.js, Node.js, HTML, CSS, JavaScript). It allows users to register, log in, browse movies, select seats, and confirm bookings.

## Features
- User authentication (registration and login)
- Movie listing with details
- Interactive seat selection
- Booking confirmation
- Responsive UI

## Project Structure
```
movie-ticket-booking
├── models
│   ├── User.js
│   ├── Movie.js
│   └── Booking.js
├── routes
│   ├── auth.js
│   ├── movies.js
│   └── bookings.js
├── public
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   ├── auth.js
│   │   ├── movies.js
│   │   ├── booking.js
│   │   └── utils.js
│   ├── register.html
│   ├── login.html
│   ├── index.html
│   ├── movie-details.html
│   ├── seat-selection.html
│   └── confirmation.html
├── server.js
├── package.json
├── .env
└── README.md
```

## Installation Instructions
1. Clone the repository:
   ```
   git clone <repository-url>
   cd movie-ticket-booking
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up MongoDB:
   - Create a MongoDB database and collection.
   - Update the `.env` file with your MongoDB connection string.

4. Start the server:
   ```
   node server.js
   ```

5. Open your browser and navigate to `http://localhost:3000` to access the application.

## Usage
- **Register**: Create a new account by filling out the registration form.
- **Login**: Access your account using your registered email and password.
- **Browse Movies**: View the list of available movies on the home page.
- **Select Seats**: Choose a movie to view details and select your preferred seats.
- **Confirm Booking**: Review your selection and confirm your booking.

## Technologies Used
- MongoDB
- Express.js
- Node.js
- HTML
- CSS
- JavaScript

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or features.

## License
This project is licensed under the MIT License.