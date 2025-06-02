# Notes App with Node.js, Express, and MongoDB

A full-featured notes application built with Node.js, Express, and MongoDB that allows users to create, read, update, and delete notes. The application includes user authentication using Google OAuth 2.0.

## Features

- User authentication with Google OAuth 2.0
- Create, read, update, and delete notes
- Responsive design
- Session management with MongoDB store
- EJS templating engine for dynamic content
- Express.js backend framework

## Prerequisites

Before running this application, make sure you have the following installed:
- Node.js (v12 or higher)
- MongoDB (v4.4 or higher)
- npm (Node Package Manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Notes-NodeJs-CRUD-MongoDB.git
cd Notes-NodeJs-CRUD-MongoDB
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add the following environment variables:
```
MONGODB_URI=your_mongodb_connection_string
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
```

## Project Structure

```
Notes-NodeJs-CRUD-MongoDB/
├── server/             # Server-side code
│   ├── config/        # Database and authentication configuration
│   ├── routes/        # Application routes
│   └── models/        # Database models
├── public/            # Static files (CSS, JavaScript, images)
├── views/             # EJS templates
│   └── layouts/       # Layout templates
├── app.js            # Main application file
├── package.json      # Project dependencies and scripts
└── README.md         # Project documentation
```

## Dependencies

- express: Web application framework
- mongoose: MongoDB object modeling tool
- passport: Authentication middleware
- passport-google-oauth20: Google OAuth 2.0 strategy
- express-session: Session middleware
- connect-mongo: MongoDB session store
- ejs: Templating engine
- express-ejs-layouts: Layout support for EJS
- method-override: HTTP method override middleware
- dotenv: Environment variable management

## Running the Application

1. Start the application:
```bash
npm start
```

2. The application will be available at `http://localhost:5000`

## Development

For development with automatic server restart:
```bash
npm install nodemon --save-dev
npx nodemon app.js
```

## Features to be implemented

- [ ] Email notifications
- [ ] Note sharing
- [ ] Tags and categories
- [ ] Rich text editor
- [ ] Export notes functionality

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

 
