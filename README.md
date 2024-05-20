# MernFoods

Deployment Link: [https://food-ordering-app-frontend-3g1e.onrender.com/](https://food-ordering-app-frontend-3g1e.onrender.com/)

## Table of Contents

- [Project Description](#project-description)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Run Locally](#run-locally)
- [Tech Stack](#tech-stack)

## Project Description

MernFoods is a Full Stack MERN web application designed as an enterprise-level Food Ordering Application. It includes User Authentication using Auth0 and payments via Stripe, and we implemented a stunning responsive User Interface by ShadCN.

## Objectives

- Provide a highly secure and user-friendly authentication mechanism for public networks.
- Offer a secure platform for users to track their daily transactions.

## Features

- **User Auth/Registration/Profiles**: Secure user authentication and profile management using Auth0.
- **Search/Sort/Filter/Pagination**: Enhanced user experience with comprehensive search, sort, filter, and pagination functionalities.
- **Manage Restaurant & Image Upload**: Efficient restaurant management with image upload capabilities using Cloudinary.
- **Manage Cart & Stripe Checkout**: User-friendly cart management and secure payments via Stripe.
- **Live Order Status**: Real-time tracking of order status for users.

## Technologies Used

### Backend

- Utilized Node.js and Express.js to build REST APIs serving as the application's backend.
- Engineered a secure authentication system using the OAuth2.0 library.
- Conducted comprehensive testing using Postman for optimal performance.
- Implemented a secure payment service with Stripe.

### Frontend

- Leveraged ShadCN-UI and DevExtreme to design a seamless user interface for enhanced user experience.
- Enhanced user convenience by eliminating repeated logins using Local Storage, maintaining persistent login sessions.

### Database

- Stored all data, including user information and transaction details, in MongoDB, a NoSQL database.
- Utilized MongoDB Atlas, a cloud-based database.

### Deployment

- Deployed the backend for the application on Render.
- Deployed the frontend for the application on Render.
- Set up Continuous Integration and Continuous Deployment (CI/CD) pipelines for automated builds and deployments.

## Server Related Environment Variables

- `MONGO_URL`: Your MongoDB connection string
- `PORT`: Port number

## Run Locally

Clone the project repositories:

```bash
git clone https://github.com/ramraj1096/food-ordering-app-backend
git clone https://github.com/ramraj1096/food-ordering-app-frontend

```

Go to the project directory

```bash
  cd top-level-folder(Contains frontend and Backend)
```

Go to the backend directory and Install dependencies

```bash
  cd backend
```

```bash
  npm install
```

Start the backend server

```bash
  npm run dev
```

Go to the frontend directory and Install dependencies

```bash
  cd frontend
```

```bash
  npm install
```

Start the frontend server

```bash
  npm run dev
```

## Tech Stack

Client: React, TypeScript, Shadcn, Tailwind, React Hook Form

Server: Node.js, Express.js

Database: MongoDB, MongoDB Atlas

Authentication: Auth0

Payments: Stripe

Image Upload: Cloudinary

Version Control: GitHub

Deployment: Render

