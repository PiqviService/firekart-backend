# Firekart Backend 🔥

Firekart Backend is a Node.js project that serves as the backend for the [Firekart](https://github.com/ashishrawat2911/firekart) e-commerce platform. This backend application uses MySQL as its database and provides a foundation for building RESTful APIs and server-side functionality for the Firekart platform. This guide will walk you through the setup and usage of the Firekart Backend. 🚀

## Current APIs

The current APIs for the Firekart platform are available at:

- Base URL: `https://firekart.cyclic.cloud/api/v1/`

You can refer to the [Firekart API Documentation](https://firekart.cyclic.cloud/api/v1/) for detailed information about the available endpoints and their usage.

Firekart, the e-commerce platform, utilizes these APIs for its functionality. You can find the frontend code for Firekart on [GitHub](https://github.com/ashishrawat2911/firekart). 🛒

## Prerequisites

Before you get started, ensure you have the following software installed on your system:

- **Node.js:** You can download and install Node.js from [here](https://nodejs.org/).
- **MySQL:** Download and install MySQL from [here](https://dev.mysql.com/downloads/).

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ashishrawat2911/firekart-backend.git
   ```

2. Navigate to the project directory:

   ```bash
   cd firekart-backend
   ```

3. Install project dependencies:

   ```bash
   npm install
   ```

## Configuration

### Environment Variables

Create a `.env` file in the root of the project and add the following environment variables:

```env
DB_HOST=<your-mysql-host>
DB_USER=<your-mysql-username>
DB_PASSWORD=<your-mysql-password>
DB_DATABASE=<your-mysql-database>
FCM_PROJECT_ID=<your-firebase-cloud-messaging-project-id>
FCM_CLIENT_EMAIL=<your-firebase-cloud-messaging-client-email>
FCM_CLIENT_ID=<your-firebase-cloud-messaging-client-id>
FCM_PRIVATE_KEY=<your-firebase-cloud-messaging-private-key>
JWT_SECRET_KEY=<your-jwt-secret-key>
PORT=<your-port-number>
```

Replace the placeholders with your specific configuration values. These variables configure the MySQL database connection, Firebase Cloud Messaging (FCM) settings, JSON Web Token (JWT) secret key, and the server port.

## Usage

### Development Server

To start the development server with hot-reloading:

```bash
npm run dev
```

### Production Build

To build the project for production:

```bash
npm run build
```

### Start Production Server

To start the production server:

```bash
npm start
```

## Documentation

API documentation and endpoints can be found in the `routes` directory. Make sure to document your APIs for easy reference.

## Dependencies

- **Express:** Web framework for Node.js.
- **MySQL2:** MySQL driver for Node.js.
- **jsonwebtoken:** JSON Web Token library for authentication.
- **bcrypt:** Password hashing library.
- **dotenv:** Load environment variables from a `.env` file.
- **express-validator:** Validation and sanitization library for Express.

## License

This project is licensed under the ISC License. See the `LICENSE` file for details.

## Author

[Ashish Rawat](https://github.com/ashishrawat2911)

Feel free to customize this README to fit your project's specific requirements. Happy coding!
