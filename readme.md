# Login System using Node.js and EJS

This is a simple login system implementation using Node.js and EJS (Embedded JavaScript) for rendering views. The system allows users to register, login, and logout.

## Prerequisites

Before running the application, make sure you have the following installed on your system:

- Node.js: https://nodejs.org
- npm (Node Package Manager): Usually comes with Node.js installation.

## Installation

1. Clone this repository to your local machine:

```bash
git clone <repository_url>
```

2. Navigate to the project directory:

```bash
cd login-system-nodejs-ejs
```

3. Install the required dependencies:

```bash
npm install
```

## Configuration

1. Rename the `.env.example` file to `.env` and configure the following environment variables:

- `PORT`: The port on which the server will run. Default: 3000
- `SESSION_SECRET`: A secret key used for session management. It's recommended to use a random string of characters.
- `MONGODB_URI`: The connection URI for your MongoDB database. Make sure to have MongoDB running and accessible.

## Usage

1. Start the application:

```bash
npm start
```

2. Open your web browser and go to `http://localhost:3000` (or the specified port in `.env`).

## Folder Structure

```
├── public/
│   └── styles/
│       └── style.css
├── views/
│   ├── login.ejs
│   ├── register.ejs
│   └── welcome.ejs
├── controllers/
│   ├── authController.js
│   └── userController.js
├── models/
│   └── User.js
├── routes/
│   ├── authRoutes.js
│   └── userRoutes.js
├── middlewares/
│   ├── authMiddleware.js
│   └── errorMiddleware.js
├── utils/
│   └── passportConfig.js
├── app.js
├── package.json
└── .env.example
```

## Technologies Used

- Node.js: Runtime environment for server-side code.
- Express: Web framework for Node.js.
- EJS: Templating engine for rendering views.
- MongoDB: NoSQL database for storing user data.
- Passport.js: Authentication middleware for Node.js.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the creators of Node.js, Express, EJS, MongoDB, and Passport.js for their excellent tools and libraries.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the system, feel free to create a pull request.

---

That's it! You now have a basic login system implemented using Node.js and EJS. Feel free to extend and modify it according to your requirements. Happy coding!

