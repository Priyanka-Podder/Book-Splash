# Book Splash 📚

## Overview

Book Splash is a web application designed to enhance the book purchasing experience by consolidating free and priced books from various sources into one centralized platform. The application allows users to easily discover and purchase books, while also providing a seamless user authentication system for accessing exclusive paid content.

## Features

- **📚 Centralized Book Marketplace**: Find both free and paid books from various sources in one place.
- **🔒 User Authentication**: Secure sign-up and login process for users to access exclusive content.
- **📱 Responsive Design**: Mobile-friendly interface for a better user experience across devices.
- **🔍 Search and Filter Options**: Easily search for books by title, author, or genre.

## Technologies Used
<div>
  <a href="https://reactjs.org/" target="_blank" style="margin-right: 10px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="40" height="40"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" style="margin-right: 10px;">
    <img src="https://tailwindcss.com/_next/static/media/tailwindcss-mark.3c5441fc7a190fb1800d4a5c7f07ba4b1345a9c8.svg" alt="Tailwind CSS" width="40" height="40"/>
  </a>
  <a href="https://nodejs.org/" target="_blank" style="margin-right: 10px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="40" height="40"/>
  </a>
  <a href="https://expressjs.com/" target="_blank" style="margin-right: 10px;">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js" width="40" height="40"/>
  </a>
  <a href="https://www.mongodb.com/" target="_blank">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="40" height="40"/>
  </a>
</div>


## Installation

To get started with Book Splash, follow these steps:

## Prerequisites

- Node.js (version 14 or later)
- MongoDB

## Clone the Repository

```bash
git clone https://github.com/Priyanka-Podder/Book-Splash.git
cd Book-Splash
```

## Install Dependencies

Navigate to the server directory and install the dependencies:

```bash
cd server
npm install
```

Then navigate to the client directory:

```bash
cd ../client
npm install
```

## Set Up Environment Variables

Create a `.env` file in the `server` directory and add the following variables:

```plaintext
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

## Start the Application

1. Start the server:

   ```bash
   cd server
   npm start
   ```

2. In a new terminal, start the client:

   ```bash
   cd client
   npm start
   ```

Your application should now be running on `http://localhost:3000`.

## Usage

- Visit the homepage to browse featured books.
- Use the search bar to find specific titles or authors.
- Register or log in to access paid content.

## Contributing

Contributions are welcome! If you'd like to contribute to Book Splash, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a new Pull Request.
