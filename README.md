# Ticketing App

The Ticketing App is a web application built with Next.js, MongoDB, and Tailwind CSS. It serves as a ticket management system, providing users with the ability to create, update, and delete tickets, facilitating efficient communication and issue resolution.

## Technologies Used

- **Frontend:**

  - [Next.js](https://nextjs.org/): React framework for server-rendered React applications.
  - [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.

- **Backend:**
  - [Node.js](https://nodejs.org/): JavaScript runtime.
  - [Express](https://expressjs.com/): Web application framework for Node.js.
  - [MongoDB](https://www.mongodb.com/): NoSQL database for storing ticket data.

## Getting Started

- Node.js and npm installed.
- MongoDB installed and running.
- Tailwind CSS configured

### Installation

1. Clone the repository: ` git clone https://github.com/Kalutu/ticketing-app`
2. Change into the project directory: `cd ticketing-app`
3. Set up environment variables:
   - Create a .env file in the backend directory and add necessary configurations.
   - `MONGO_URI=your_mongodb_connection_string`
4. Install dependencies: `npm install`
5. Start the development server: `npm run dev`
   The app will be accessible at http://localhost:3000 by default.

## API Routes

### POST /api/Tickets/new

Creates a new ticket.

### GET /api/Tickets

Fetches all tickets.

### GET /api/Tickets/:id

Fetches a specific ticket by ID.

### PUT /api/Tickets/:id

Updates a specific ticket by ID.

### DELETE /api/Tickets/:id

Deletes a specific ticket by ID.

## Contributing

We welcome contributions! If you find a bug or have a feature request, please open an issue or submit a pull request.
