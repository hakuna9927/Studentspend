# StudentSpend

StudentSpend is a student-focused personal finance dashboard that helps users understand spending habits, stay within budget, reach savings goals, and make smarter financial decisions with AI-assisted guidance.

Built with React, TypeScript, Tailwind CSS, and a Node/Express backend, the app combines transaction tracking, budgeting, goals, reporting, and conversational finance support in one experience.

## Features

- AI-powered financial guidance through the Ask page
- Transaction overview and management
- Budget tracking and monthly planning
- Savings and financial goals dashboard
- Weekly and monthly reports
- Loan tracking and debt overview
- Profile and settings management
- Dark mode experience with responsive UI

## Tech Stack

- Frontend: React, Vite, TypeScript, Tailwind CSS
- Charts & UI: Recharts, Lucide React
- Backend: Node.js, Express
- Database: MongoDB via Mongoose
- Auth & realtime data: Supabase

## Project Structure

```text
.
├── public/
│   └── StudentSpend-logo.png
├── server/
│   ├── config/
│   ├── routes/
│   ├── package.json
│   └── server.js
├── src/
│   ├── components/
│   ├── layouts/
│   ├── lib/
│   ├── pages/
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── index.html
├── package.json
├── vite.config.ts
├── tailwind.config.js
├── tsconfig.json
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18+
- npm
- MongoDB connection string
- Supabase project with URL and anon key

### Install dependencies

```bash
npm install
cd server
npm install
cd ..
```

### Environment Variables

Create a `.env` file in the `server/` directory for the backend:

```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Create a `.env.local` file in the project root for the frontend:

```bash
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Run the app locally

Start the frontend:

```bash
npm run dev
```

Start the backend API:

```bash
cd server
npm run dev
```

The frontend runs from Vite on the default port, while the backend API runs on the Node/Express server.

### Production build

```bash
npm run build
```

## Available Scripts

```bash
npm run dev       # Start the Vite development server
npm run build     # Build the frontend for production
npm run preview   # Preview the production build
npm run typecheck # Type-check the project
```

## Notes

This project is designed as a personal finance companion for students, with a focus on clarity, budgeting discipline, and goal-oriented decision making. The app includes a test-friendly environment for local development and can be extended with additional finance integrations or richer analytics.

## License

This project does not currently declare a formal license in the root repository.
