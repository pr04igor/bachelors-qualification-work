# Bug Tracker

This project is a web-based bug tracking system designed to help teams manage and track software issues efficiently. It allows users to register, log in, add bugs, and track their status.

## Technologies Used

### Frontend:
- **React**
- **React Router**
- **Axios** (for API requests)
- **CSS** (for styling)

### Backend:
- **Node.js**
- **Express.js**
- **MongoDB** (with Mongoose)
- **JWT (JSON Web Token)** (for authentication)
- **bcrypt** (for password hashing)
- **Jest** (for testing)

## Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (latest LTS version recommended)
- **MongoDB** (local or cloud instance)

## Getting Started

### 1. Clone the repository:

```sh
git clone https://github.com/pr04igor/bugtracker.git
cd bugtracker
```

### 2. Set up the environment variables

Create a `.env` file in the `logic-backend` folder and add the following:

```ini
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 3. Install dependencies

#### Frontend:
```sh
cd bugtracker-frontend
npm install
```

#### Backend:
```sh
cd ../logic-backend
npm install
```

### 4. Run the application

#### Start the backend server:
```sh
cd logic-backend
node server.js
```

#### Start the frontend:
```sh
cd ../bugtracker-frontend
npm start
```

The frontend will start at `http://localhost:3001`, and the backend will run at `http://localhost:3000`.

## Features

- **User Authentication**: Register and log in with hashed passwords.
- **Bug Management**: Create, track, and update bug statuses.
- **Role Management**: Assign bugs to users.
- **File Uploads**: Attach files to bug reports.
- **Labeling System**: Categorize bugs with labels.

## Future Improvements

- User roles and permissions
- Advanced search and filtering
- Email notifications for bug updates

## Contact

Project author: Igor Pron ([GitHub Profile](https://github.com/pr04igor))  
For any questions, feel free to open an issue or submit a pull request!

## License

This project is licensed under the MIT License. Feel free to contribute!
