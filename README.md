# create-sanket-app

`create-sanket-app` is a CLI tool designed to help developers quickly scaffold backend projects using Node.js and Express. It simplifies the process of setting up a new project by handling common tasks such as setting up CORS, logging with Morgan, environment variables with dotenv, error handling, and more. The tool allows you to generate a full backend structure in either JavaScript or TypeScript, so you can get started faster.

## Features

- **Express Server Setup**: Automatically generates an Express.js application with routing and middleware configurations.
- **TypeScript or JavaScript**: Choose between TypeScript and JavaScript for your project.
- **CORS Integration**: Optionally include CORS middleware to handle cross-origin requests.
- **Morgan Logging**: Easily integrate Morgan for logging HTTP requests.
- **Environment Configuration**: Automatically integrates dotenv for managing environment variables.
- **Custom Error Handling**: Includes an `ErrorHandler` class and error-handling middleware.
- **Docker Support**: Optionally set up Docker for easy containerization and deployment.
- **Preconfigured npm Scripts**: Includes scripts for starting the server in development mode and compiling TypeScript.

## Installation

You can create a new project with `create-sanket-app` using `npx`:

\`\`\`
npx create-sanket-app
\`\`\`

This command will walk you through an interactive prompt to set up your project.

## How to Use

1. Run the following command to initialize a new project:

   \`\`\`bash
   npx create-sanket-app
   \`\`\`

2. You will be prompted to provide details about the project:
   - **Project Name**: The name of your new project.
   - **Language**: Choose between JavaScript or TypeScript.
   - **Enable CORS**: Optionally add CORS middleware.
   - **Basic Error Handling**: Add a basic error handler to your project.
   - **Environment File**: Configure environment variables using dotenv.
   - **Morgan for Logging**: Add Morgan middleware for HTTP request logging.
   - **Docker for Deployment**: Optionally set up Docker configuration files.

3. Once the prompts are complete, `create-sanket-app` will generate your project structure, install dependencies, and set up a development environment.

## Project Structure

The generated project will follow this structure:

![image](https://github.com/user-attachments/assets/97ffb982-38a8-4eea-ade2-a4a023f71959)



### npm Scripts

Your project will include the following npm scripts:

- `npm run dev`: Starts the development server using nodemon.
- `npm run watch`: Compiles TypeScript code and watches for changes (if TypeScript is selected).

## Example

\`\`\`
npx create-sanket-app
# Follow the interactive prompts to set up your project.

cd my-app
npm install
npm run dev
npm run watch
\`\`\`

After running these commands, your new backend project will be up and running with Express, CORS, Morgan, dotenv, and error handling configured.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Contributions are welcome to improve the tool or add new features!

"""
