# Medical-SOS: Emergency Medical Service Platform

This is a comprehensive web application designed to streamline emergency medical services, connecting patients, doctors, drivers, and pharmacies in a unified platform. The project is built with Next.js and utilizes modern web technologies to deliver a fast, reliable, and user-friendly experience.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Make sure you have Node.js and npm (or yarn/pnpm) installed on your system.

- [Node.js](httpss://nodejs.org/) (v20 or later recommended)
- [npm](httpss://www.npmjs.com/get-npm)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/MonowarHusain/medical-sos.git
    cd medical-sos
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up the database:**
    This project uses Prisma as its ORM. Ensure you have a database set up.
    ```bash
    npx prisma generate
    npx prisma db push
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Available Scripts

In the project directory, you can run:

-   `npm run dev`: Runs the app in development mode.
-   `npm run build`: Builds the app for production.
-   `npm run start`: Starts a production server.

## Technologies Used

-   **Framework:** [Next.js](httpss://nextjs.org/) 16.1.1
-   **Language:** [TypeScript](httpss://www.typescriptlang.org/)
-   **UI Library:** [React](httpss://reactjs.org/) 19.2.3
-   **Styling:** [Tailwind CSS](httpss://tailwindcss.com/)
-   **Database ORM:** [Prisma](httpss://www.prisma.io/)

## Project Structure

The application follows the standard Next.js `app` directory structure:

```
app/
├── (admin)         # Admin-specific routes and layouts
├── (user)          # General user routes
├── components/     # Shared React components
├── actions.ts      # Server-side actions
└── globals.css     # Global styles
prisma/
└── schema.prisma   # Database schema definition
public/             # Static assets
```
