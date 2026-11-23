# Inventory & Orders API

A RESTful backend API for managing product inventory, stock control, and customer orders, built with Node.js, Express, and TypeScript.

## Tech Stack

- **Runtime:** Node.js
- **Framework:** Express
- **Language:** TypeScript
- **Dev Runner:** tsx

## Getting Started

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```

The server runs by default on `http://localhost:3000`.

## Available Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `GET` | `/health` | Verifies that the server is up and running |

## Project Status

🚧 **In Progress** — Initial Express and TypeScript setup. Planned features include PostgreSQL with Prisma ORM, request validation with Zod, JWT authentication with role-based access, and automated API testing with Playwright.