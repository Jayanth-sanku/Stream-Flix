# Stream Flix

Stream Flix is a streaming platform built using React.js, Firebase Authentication, and TMDb API.

## Overview

Stream Flix is a web application that allows users to stream movies and TV shows. It utilizes React.js for the frontend development, Firebase Authentication for user authentication, and TMDb API for fetching movie and TV show data.

## Features

- User Authentication: Users can sign up, log in, and log out securely using Firebase Authentication.
- Browse Content: Users can browse a wide range of movies and TV shows fetched from TMDb API.
- Search Functionality: Users can search for specific movies or TV shows by title.
- Watchlist: Users can add movies and TV shows to their watchlist for later viewing.
- Responsive Design: The website is responsive and works seamlessly across different devices and screen sizes.

## Installation

1. Clone the repository:


2. Install dependencies:


3. Set up Firebase:

   - Create a Firebase project at https://console.firebase.google.com/
   - Obtain your Firebase configuration object.
   - Add your Firebase configuration to `src/firebase/firebaseConfig.js`.

4. Obtain TMDb API key:

   - Sign up for an account at https://www.themoviedb.org/.
   - Generate an API key.
   - Add your TMDb API key to `src/utils/constants.js`.

5. Start the development server:


6. Open your browser and navigate to `http://localhost:3000` to view the application.

## Technologies Used

- React.js
- Firebase Authentication
- TMDb API
- HTML/CSS

## Contributing

Contributions are welcome! If you'd like to contribute to Stream Flix, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Special thanks to the creators of React.js, Firebase, and TMDb for providing the tools and APIs necessary to build Stream Flix.

