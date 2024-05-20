# MernFoods

Deployment Link: https://food-ordering-app-frontend-3g1e.onrender.com/

## Table of Contents

-   [Project Description](#project-description)
-   [Objectives](#objectives)
-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [Environment Variables](#environment-variables)
-   [Run Locally](#run-locally)
-   [Tech Stack](#tech-stack)
-   [Screenshots](#screenshots)

## Project Description

> MernFoods is a Full Stack MERN web application designed as an enterprise level Food Ordering Application . It includes User Authentication using OAuth0 and payments via Stripe and we implimented a Stunning responsive User Interface by Shad cn .

## Objectives

> -   Provide a highly secure and user-friendly authentication mechanism for public networks.
> -   Offer a secure platform for users to track their daily transactions.

## Features

> #### User Authentication
>
> -   Implimented User Authentication Using OAuth2.0

## Technologies Used

> #### Backend
>
> -   Utilized Node.js and Express.js to build REST APIs serving as the application's backend.
> -   Engineered a secure authentication system by using the OAuth2.0 library.
> -   Conducted comprehensive testing using Postman for optimal performance.
> -   Implimented a secure payment service by Stripe.

> #### Frontend
>
> -   Leveraged ShadCN-UI and DevExtreme to desgin a seamless user interface for enhanced user experience.
> -   Enhanced user convenience by eliminating repeated logins using Local Storage, maintaining persistent login session.

> #### Database
>
> -   Stored all data, including user information and transaction details in MongoDB, a NoSQL database.
> -   Utilized MongoDB Atlas, a cloud based database.

> #### Deployment
>
> -   Deployed the Backend for the application on Render.
> -   Deployed the Frontend for the application on Render.
> -   Set up Continuous Integration and Continuous Deployment (CI/CD) pipelines for automated builds and deployments.


#### Server related environment variables

-   `MONGO_URL` : Your MongoDB connection string
-   `PORT` : Port number

## Run Locally

Clone the project

Backend and Frontend

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

**Client:** React.js, Shad-UI, TypeScript, Tailwind, React

**Server:** Node.js, Express.js, OAuth2.0, Stripe, Clioudinary

**Database:** MongoDB Atlas

**Testing:** Postman

