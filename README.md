
# Ticket Board Project

This project consists of a GraphQL backend and a React frontend to manage ticket boards. It allows you to:
- Create a new board
- Create tickets
- Update tickets
- Delete tickets

## Backend Setup

### Prerequisites
- Java 11+
- Maven

### Steps to Run
1. Navigate to the backend directory:
   ```bash
   cd ticket-board-backend
   ```
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The backend will be available at `http://localhost:8080/graphql`.

## Frontend Setup

### Prerequisites
- Node.js 16+

### Steps to Run
1. Navigate to the frontend directory:
   ```bash
   cd ticket-board-frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the application:
   ```bash
   npm start
   ```

The frontend will be available at `http://localhost:3000`.

## Features

- **Create Board**: Add a new board using the frontend form.
- **Create Ticket**: Add tickets to a selected board.
- **Update Ticket**: Edit ticket details.
- **Delete Ticket**: Remove tickets from a board.

---
Enjoy your ticket management system!
