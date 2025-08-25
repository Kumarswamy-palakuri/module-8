# React Week 7 Day 2
# Contact Management App (React + Node.js)

This is a full-stack contact management application built with a React frontend and a Node.js/Express backend API. It allows users to register, log in, and perform CRUD (Create, Read, Update, Delete) operations on their contacts.

## Features

-   **User Authentication**: Secure user registration and login system using JWT (JSON Web Tokens).
-   **Contact Management**: A simple and intuitive interface to manage personal contacts.
-   **CRUD Functionality**: Full capabilities to create, view, edit, and delete contacts.
-   **Responsive UI**: A user-friendly interface built with Material-UI.
-   **RESTful API**: A well-structured backend API to handle all data operations.

## Tech Stack

### Frontend (Client)

-   **Framework**: React.js
-   **UI Library**: Material-UI
-   **Routing**: React Router (`react-router-dom`)
-   **HTTP Client**: Axios
-   **Build Tool**: Create React App (`react-scripts`)

### Backend (Server)

-   **Framework**: Express.js
-   **Runtime**: Node.js
-   **Authentication**: JSON Web Token (`jsonwebtoken`)
-   **Password Hashing**: BcryptJS (`bcryptjs`)
-   **Middleware**: CORS

## Project Structure

The project is organized into two main directories:

-   `client/`: Contains the React frontend application.
-   `server/`: Contains the Node.js/Express backend API.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   Node.js (v18 or later recommended)
-   npm (or yarn)

### Installation & Setup

1.  **Clone the repository:**
    ```
    git clone https://github.com/Kumarswamy-palakuri/react-week-7-day-2.git
    cd react-week-7-day-2
    ```

2.  **Set up the Backend Server:**
    -   Navigate to the server directory:
        ```
        cd server
        ```
    -   Install dependencies:
        ```
        npm install
        ```
    -   Create a `.env` file in the `server` directory and add a secret key for JWT:
        ```
        JWT_SECRET=your_super_secret_key_here
        ```
    -   Start the development server:
        ```
        npm run dev
        ```
    The server will be running on `http://localhost:5000` (or the port specified in your code).

3.  **Set up the Frontend Client:**
    -   Open a new terminal window and navigate to the client directory from the project root:
        ```
        cd client
        ```
    -   Install dependencies:
        ```
        npm install
        ```
    -   Start the React development server:
        ```
        npm start
        ```
    The client will be running on `http://localhost:3000`. Open this URL in your browser to use the application.

## Available Scripts

### Backend (`/server`)

-   `npm start`: Starts the server in production mode using `node`.
-   `npm run dev`: Starts the server in development mode using `nodemon`, which automatically restarts the server on file changes.

### Frontend (`/client`)

-   `npm start`: Runs the app in development mode.
-   `npm run build`: Builds the app for production to the `build` folder.
-   `npm test`: Launches the test runner in interactive watch mode.
-   `npm run eject`: Ejects the app from Create React App's managed configuration.


This repository contains the code for **React Week 7 Day 2** practice/project.

## 📥 Clone the Repository

To clone this repository to your local machine, run the following command in your terminal or Git Bash:

```bash
git clone https://github.com/Kumarswamy-palakuri/react-week-7-day-2.git
```
## 🚀 Setup Instructions

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the project:
   ```bash
   npm start
   ```

3. Build for production:
   ```bash
   npm run build
   ```

## Key Features

-   **Component-Based Architecture:** The UI is built using reusable and modular React components.
-   **Client-Side Routing:** Uses React Router to enable seamless navigation between different pages (e.g., Home, Details, About) without a full page reload.
-   **State Management with Hooks:** Manages component state efficiently using React Hooks like `useState` and `useEffect`.
-   **API Integration:** Fetches data from a remote API to display dynamic content.
-   **Responsive Design:** The layout is designed to be functional and visually appealing across different screen sizes.
-   **Interactive Forms:** Includes forms for user input with validation and submission handling.
