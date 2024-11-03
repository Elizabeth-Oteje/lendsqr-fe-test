# Admin Management System

This project is an **Admin Management System** built with **React**, **TypeScript**, and **SCSS**. The application enables admins to log in, access their dashboard, view a list of all users, and view detailed information for each user.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the App](#running-the-app)
  - [Build for Production](#build-for-production)
- [Scripts](#scripts)
- [Available Pages](#available-pages)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **Admin Login**: Secure login functionality for administrators.
- **Dashboard**: Overview page for admins, displaying essential metrics and navigation.
- **User Management**: List all users in the system, with basic details.
- **User Details**: View detailed information for each individual user.

---

## Tech Stack

- **React**: Frontend JavaScript library for building user interfaces.
- **TypeScript**: Superset of JavaScript with static typing, enhancing code quality and maintainability.
- **SCSS**: CSS preprocessor that adds nested rules, variables, and mixins for better styling structure.
- **React Router**: For routing and navigation between application pages.
- **Context API**: For global state management, especially for user authentication.

## Project Structure

The following folder structure is used to keep the codebase modular and maintainable:

my-app/
├── .vscode/ # Editor settings
├── public/ # Static assets
├── src/
│ ├── assets/ # Images and static files
│ ├── components/ # Reusable components (e.g., Button, Modal)
│ ├── context/ # Context API for global state (e.g., AuthContext)
│ ├── hooks/ # Custom hooks
│ ├── pages/ # Main application pages
│ │ ├── Dashboard/ # Admin dashboard page
│ │ ├── Login/ # Login page
│ │ ├── Users/ # User listing page
│ │ └── UserDetails/ # Individual user details page
│ ├── services/ # API calls and business logic (e.g., authService, userService)
│ ├── types/ # TypeScript type definitions
│ ├── App.tsx # Main application component
│ ├── index.tsx # Application entry point
│ └── styles/ # Global SCSS styles
└── .prettierrc # Code formatting
└── tsconfig.json # TypeScript configuration

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- **Node.js** (v22.5.1)
- **npm**

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Elizabeth-Oteje/lendsqr-fe-test.git
   cd lendsqr-fe-test
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

   or if you prefer `yarn`:

   ```bash
   yarn install
   ```

### Running the App

To start the development server, run:

```bash
npm start
```

or with `yarn`:

```bash
yarn start
```

The app will be running at [http://localhost:3000](http://localhost:3000).

### Build for Production

To build the app for production:

```bash
npm run build
```

This will create an optimized build in the `build` folder, ready for deployment.

---

## Scripts

The following scripts are available:

- **`npm start`**: Starts the development server.
- **`npm run build`**: Builds the app for production.
- **`npm run test`**: Runs tests

---

## Available Pages

1. **Login Page**:
   - Allows admins to securely log in to access the system.
2. **Dashboard**:
   - The main hub for administrators, providing access to user management and displaying essential metrics.
3. **Users Page**:
   - Lists all users in the system, with search and filter capabilities.
4. **User Details Page**:
   - Displays in-depth information for each user.

---
