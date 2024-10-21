# BackendKickstarter

![BackendKickstarter](backend-kickstarter.png) <!-- Add a logo or banner image here -->

BackendKickstarter is a powerful and extensible starter template for building Node.js backend applications. It comes equipped with a comprehensive set of tools and configurations to help you kickstart your next project efficiently.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Running Tests](#running-tests)
- [Linting and Formatting](#linting-and-formatting)
- [Docker Support](#docker-support)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **TypeScript Support**: Built with TypeScript for improved type safety and a better developer experience.
- **Development and Build Scripts**: Includes scripts for development (`dev`), production (`start`), and building your application (`build`).
- **Linting and Formatting**: Integrated linting with [Biome](https://biomejs.dev) to maintain code quality, along with automatic formatting.
- **Testing Framework**: Comes with [Vitest](https://vitest.dev) for unit and integration testing.
- **Environment Configuration**: Utilizes `dotenv` for managing environment variables, ensuring secure and flexible configuration.
- **Express Framework**: Built on top of Express.js, making it easy to build web applications and APIs.
- **Data Validation**: Incorporates class-validator and Zod for data validation and transforming incoming request data.
- **MongoDB Support**: Integrated support for MongoDB using TypeORM, enabling seamless database operations.
- **API Documentation**: Automatically generates API documentation with Swagger UI.
- **Rate Limiting and Security**: Built-in middleware for rate limiting and security best practices using Helmet.

## Installation

To use BackendKickstarter, simply run the following command in your terminal:

 
npx create-backend-kickstarter 
What is the name of your project?
Replace `<project-name>` with the desired name for your new project.

## Usage

1. **Run the command** to create a new project:
    
    ```bash
    npx create-backend-kickstarter
    What is the name of your project? my-node-backend
    Do you want to include Docker support? Yes/No

    ```
2. **rename .env.example -> .env && .env.example.local -> .env.[environment].local**
    
3. **Start the development server**:
    
    ```bash
    pnpm run dev
    ```
    
4. **Build the application for production**:
    
    ```bash
    pnpm run build
    ```
    
5. **Run the production server**:
    
    ```bash
    pnpm start
    ```
    

## Configuration

During the setup process, you will be prompted to enter the following:

- **Project Name**: The name of your new project.
- **Docker Support**: Choose whether to include Docker support in your project.

You can manage environment variables using a `.env` file in the root directory of your project. Example:

```
DATABASE_URL=mongodb://localhost:27017/mydatabase
JWT_SECRET=mysecretkey
```

## Running Tests

To run the tests, use the following command:

```bash
pnpm run test
```

## Linting and Formatting

You can check your code for linting issues and automatically fix them with:

```bash
pnpm run lint
pnpm run lint:fix
```

## Docker Support

If you opted to include Docker support during setup, a `Dockerfile` will be created in your project directory. You can build and run your application in a Docker container with the following commands:

1. **Build the Docker image**:
    
    ```bash
    docker build -t my-backend .
    ```
    
2. **Run the Docker container**:
    
    ```bash
    docker run -p 3000:3000 my-backend
    ```
    

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request. Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Inspired by various starter templates and community contributions.
- Built with the help of:
    - [Express](https://expressjs.com/)
    - [TypeORM](https://typeorm.io/)
    - [Zod](https://zod.dev/)
    - [zod-to-openapi](https://github.com/asteasolutions/zod-to-openapi)
    - [Vitest](https://vitest.dev/)
    - [Biome](https://biomejs.dev/)