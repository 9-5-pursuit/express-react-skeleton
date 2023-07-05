# Express React Skeleton

This is a skeleton for a full-stack web application using Express and React. It is intended to be used as a starting point for new projects. It is not intended to be a production-ready application.

## Using the Skeleton

1. Fork the repository on GitHub.

1. Clone the repository to your local machine.
    ```bash
    git clone <repository-url> <directory-name>
    # Example: git clone https://github.com/9-5-pursuit/express-react-skeleton my-app
    ```

1. Change into the directory.

    ```bash
    cd <directory-name>
    # Example: cd my-app
    ```

1. Setup a new remote repository on Github so that you don't overwrite the skeleton repository.

1. Link your local repository to your new remote repository.

    ```bash
    git remote set-url origin <new-repository-url>
    ```

1. Make a small change, then create a new commit to test the remote repository.

    ```bash
    git add .
    git commit -m "Update remote repository"
    git push
    ```

## Backend

### Prerequisites

- [Node.js](https://nodejs.org/en/) - JavaScript runtime
- [npm](https://www.npmjs.com/) - Package manager

### Getting Started

```bash
# Change into the backend directory
cd backend

# Install dependencies
npm install

# Start the development server
npm start
```

> Note: The development server will restart automatically when changes are made to the source code as long as you use Nodemon to start the server and leave the server running. If you stop the server, you will need to restart it manually. We've setup a script in the `package.json` file to make this the default behavior when you run `npm start`.

### Built With

- [Express](https://expressjs.com/) - Web framework
- [dotenv](https://www.npmjs.com/package/dotenv) - Environment variables
- [nodemon](https://nodemon.io/) - Development server
- [cors](https://www.npmjs.com/package/cors) - Cross-origin resource sharing
- [morgan](https://www.npmjs.com/package/morgan) - HTTP request logger

### Additional Notes

Since this is a skeleton, the `.env` file is included in the repository. This is not recommended for production applications. The `.env` file should be added to the `.gitignore` file and the environment variables should be set in the production environment.

## Frontend

### Prerequisites

- [Node.js](https://nodejs.org/en/) - JavaScript runtime
- [npm](https://www.npmjs.com/) - Package manager

### Getting Started

```bash
# Change into the frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm start
```

> Note: You should have the backend development server running before starting the frontend development server. Each server should be running simultaneously in separate terminal windows. This can be a lot to keep track of at first, so take your time when making changes to the repository.

### Built With

- [React](https://reactjs.org/) - JavaScript library for building user interfaces
- [react-router-dom](https://reactrouter.com/web/guides/quick-start) - Routing
- [axios](https://www.npmjs.com/package/axios) - HTTP client
- [uuid](https://www.npmjs.com/package/uuid) - Generate unique IDs
- [bootstrap](https://getbootstrap.com/) - CSS framework
- [react-bootstrap](https://react-bootstrap.github.io/) - Bootstrap components

### Additional Notes

Since this is a skeleton, the `.env` file is included in the repository. This is not recommended for production applications. The `.env` file should be added to the `.gitignore` file and the environment variables should be set in the production environment.