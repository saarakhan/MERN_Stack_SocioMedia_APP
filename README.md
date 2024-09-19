# Social Media App

This is a full-stack social media web application that allows users to create profiles, share posts, connect with friends, and interact with content. The app is built using modern web technologies, featuring a robust backend and a dynamic, responsive frontend.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used

### Frontend:

- **JavaScript**
- **React**
- **Redux** (State Management)
- **Formik** (Form Handling)
- **Dropzone** (File Uploads)
- **Material UI** (UI Components)
- And more...

### Backend:

- **Node.js**
- **Express**
- **body-parser**
- **MongoDB**

### Authentication & Authorization:

- **JWT** (JSON Web Token)
- **bcrypt**

### Additional Backend Packages:

- **cors**
- **dotenv**
- **gridfs-stream**
- **helmet**
- **jsonwebtoken**
- **mongoose**
- **morgan**
- **multer**
- **multer-gridfs-storage**

## Features

- User Registration and Authentication (using JWT and bcrypt)
- Profile Management
- Posting and Interacting with Posts
- File Uploads with Dropzone and GridFS
- Responsive UI built with Material UI
- State management with Redux

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/social-media-app.git
```

2.Navigate to the project directory:

```bash
Copy code
cd social-media-app
```

3.Install backend dependencies:

```bash
Copy code
cd backend
npm install
```

4.Install frontend dependencies:

```bash
Copy code
cd ../frontend
npm install
```

## Usage

1.Start the backend server:

```bash
Copy code
cd backend
npm start
```

2.Start the frontend development server:

```bash
Copy code
cd frontend
npm start
```

Open your browser and navigate to http://localhost:3000.

## Contributing

Contributions are welcome! Please follow these steps:

1.Fork the repository.
2.Create a new branch (git checkout -b feature-branch).
3.Commit your changes (git commit -m 'Add new feature').
4.Push to the branch (git push origin feature-branch).
5.Open a pull request.
