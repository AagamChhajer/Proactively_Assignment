<!-- # Proactively - Assignment

## Preview

![Frontend](https://github.com/user-attachments/assets/60d49ed4-80f2-4de5-a952-f225b656ecfd)

![Frontend](https://github.com/user-attachments/assets/df9035c9-86ba-46af-9755-dd1d1672ad7f)




> [!WARNING]
> Made ```.env``` files public for the convenience of the reviewer. This is not recommended in a production environment.

## Tech Stack

### Backend
- Node.js
- Express
- Prisma
- TypeScript
- PostgreSQL (Database)

### Frontend
- Next.js
- React
- Tailwind CSS


### Prerequisites
- Node.js (v14 or higher)
- npm (v7 or higher)
- pnpm (v6 or higher)(recommended)

### Installation Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/aagamchhajer/proactively_assignment.git
    cd proactively
    ```

2. Install Backend Dependencies
    ```sh
    cd backend_proactively
    npm install
    npx prisma generate
    ```

3. Install Frontend Dependencies
    ```sh
    cd frontend_proactively
    npm install
    ```
4. Start the Backend Server
    ```sh
    cd backend_proactively
    npm run dev
    ```
5. Start the Frontend Server
    ```sh
    cd frontend_proactively
    npm run dev
    ```
6. Open [http://localhost:3001](http://localhost:3001) in your browser to see the frontend.

> [!NOTE]
> Step 5 and Step 6 should be run in separate terminals but both processes should be running simultaneously.

8. Backend running on [http://localhost:3000](http://localhost:3000).

9. To see the Database open [http://localhost:5555](http://localhost:5555) in your browser.

## API Testing Steps

You can test the API using Postman. Import the following Postman collection to get started:

1. Copy the given json link : ```https://raw.githubusercontent.com/aagamchhajer/proactively/refs/heads/main/aagamchhajer.json```
2. Open Postman
3. Click on Import
4. Paste the copied link

[Preview](https://github.com/user-attachments/assets/4dd60de9-4f2d-4088-a2c7-3424a039b233)

 -->
# Proactively Assignment Documentation

## Introduction

Welcome to the **Proactively Assignment**! Below is an overview of the project along with setup and testing instructions.

### Frontend Previews

Here are snapshots of the frontend:

![Frontend Example 1](https://github.com/user-attachments/assets/60d49ed4-80f2-4de5-a952-f225b656ecfd)

![Frontend Example 2](https://github.com/user-attachments/assets/df9035c9-86ba-46af-9755-dd1d1672ad7f)

> **Note:** `.env` files have been made public to aid the review process. This approach is unsuitable for production systems and should be avoided.

---

## Project Overview

This project leverages modern web development technologies for both the backend and frontend, ensuring a seamless and efficient user experience.

### Backend Technologies
- **Node.js**: JavaScript runtime environment.
- **Express**: Backend framework.
- **Prisma ORM**: Database modeling and querying.
- **TypeScript**: Typed JavaScript for maintainability.
- **PostgreSQL**: Relational database management system.

### Frontend Technologies
- **Next.js**: Framework for server-rendered React applications.
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework.

---

## Requirements

Before proceeding, ensure the following software is installed:

- **Node.js** (v14 or newer)
- **npm** (v7 or newer)
- **pnpm** (v6 or newer) *(recommended)*

---

## Installation Process

Follow these steps to set up the project locally:

### Step 1: Clone the Repository
```bash
git clone https://github.com/aagamchhajer/proactively_assignment.git
cd proactively
```

### Step 2: Backend Setup
Navigate to the backend directory, install dependencies, and generate Prisma client:
```bash
cd backend_proactively
npm install
npx prisma generate
```

### Step 3: Frontend Setup
Switch to the frontend directory and install dependencies:
```bash
cd frontend_proactively
npm install
```

### Step 4: Run the Servers

#### Launch the Backend Server
```bash
cd backend_proactively
npm run dev
```

#### Launch the Frontend Server
```bash
cd frontend_proactively
npm run dev
```

---

## Access the Application

- Open the frontend in your browser: [http://localhost:3001](http://localhost:3001)
- The backend is accessible at: [http://localhost:3000](http://localhost:3000)
- View the database interface: [http://localhost:5555](http://localhost:5555)

> **Tip:** Ensure both backend and frontend servers are running in separate terminal windows.

---

## API Testing with Postman

### Steps to Import the API Collection

1. Copy the following JSON File ![Json File](/aagamchhajer.json)
2. Open **Postman**.
3. Click the **Import** button.
4. Paste the copied link and complete the import.

<!-- ### API Preview -->

<!-- ![Postman Preview](https://github.com/user-attachments/assets/4dd60de9-4f2d-4088-a2c7-3424a039b233) -->

---

Feel free to explore and modify the project!