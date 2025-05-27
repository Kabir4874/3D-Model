# 3D Model Project

The **3D Model Project** consists of two main components: a **frontend** built with **React**, **Vite**, and **Three.js** for rendering 3D models, and a **backend** built with **Express** for handling API requests and other server-side operations.

This repository contains:

1. **3D-Model\_Frontend**: A React-based frontend for displaying 3D models, animations, and interactive content.
2. **backend**: A Node.js/Express backend for managing API requests.

---

## Project Structure

The repository includes the following:

### 1. **3D-Model\_Frontend**

* **React** application built using **Vite** for fast development and **Three.js** for 3D rendering.
* **TailwindCSS** for styling, **Framer Motion** for animations, and **Swiper** for carousels.

### 2. **backend**

* **Express** server for handling API requests and integration with the frontend.
* Built with basic server-side functionality using **Axios** for HTTP requests.

---

## Prerequisites

Before running the application, ensure you have the following installed:

* **Node.js** (v16 or above)
* **npm** (Node Package Manager, comes with Node.js)
* **git** (to clone the repository)
* **Yarn** (optional, but recommended for some projects)

---

## Getting Started

Follow these steps to set up and run the **3D Model Project** on your local machine.

### 1. Clone the Repository

Clone the repository using the following command:

```bash
git clone <repository-url>
cd 3d-model-project
```

### 2. Install Dependencies

Each project has its own set of dependencies. Install them separately for each project.

#### **Frontend (3D-Model\_Frontend)**

Navigate to the `3D-Model_Frontend` directory and install the dependencies:

```bash
cd 3D-Model_Frontend
npm install
```

#### **Backend (Express)**

Navigate to the `backend` directory and install the dependencies:

```bash
cd backend
npm install
```

---

## Running the Projects

After installing the dependencies, you can run the projects individually.

### 1. Run the Frontend (React App)

For the **frontend** project, navigate to the `3D-Model_Frontend` directory and start the development server:

```bash
cd 3D-Model_Frontend
npm run dev
```

This will start the Vite development server, and the frontend will be available at `http://localhost:3000`.

### 2. Run the Backend (Express Server)

For the **backend** project, navigate to the `backend` directory and start the server:

```bash
cd backend
npm run server
```

This will start the Express server, and the backend will be available at `http://localhost:5000`.

---

## Running Tests

### 1. Frontend Tests (React)

To run tests for the **frontend** project, use the following command:

```bash
cd 3D-Model_Frontend
npm run test
```

### 2. Backend Tests (Node/Express)

To run tests for the **backend** project (if applicable), you can use the following:

```bash
cd backend
npm run test
```

---

## Build

Once you're done with development and want to create production-ready builds, you can build each project.

### 1. Build the Frontend

For the **frontend** project:

```bash
cd 3D-Model_Frontend
npm run build
```

This will create an optimized production build in the `dist/` directory.

### 2. Build the Backend

For the **backend** project, the project is already set up to run in a production environment using Node.js:

```bash
cd backend
npm run start
```

---

## Features

* **Frontend (3D Model Rendering)**:

  * Built with **React** and **Vite** for fast development.
  * Uses **Three.js** for rendering 3D models and animations.
  * **TailwindCSS** for modern, responsive design.
  * **Framer Motion** for animations and transitions.
  * **Swiper** for carousel-style image galleries.

* **Backend (Express)**:

  * API handling for interactions between frontend and backend.
  * Uses **Axios** for making HTTP requests.

---

## Technologies Used

* **Frontend**:

  * React
  * Vite
  * Three.js (3D Rendering)
  * TailwindCSS
  * Framer Motion
  * Swiper
  * React Icons
  * React Router

* **Backend**:

  * Express
  * Axios
  * Node.js

* **Development Tools**:

  * ESLint
  * Prettier
  * Jest
  * Nodemon
  * Vite (for frontend)

