# PathFider – AI-Powered Study & Career Platform

PathFinder is a modern web application designed to help students excel in exams and navigate their careers using AI-powered tools. Built with [Astro](https://astro.build/), Svelte, and TailwindCSS, it provides a seamless, interactive experience for learning, practice, and career guidance.

## Features

- **Exam AI**: Access previous year question papers (PYQ), upload PDFs, and interact with an AI chatbot for smart study assistance.
- **Career Navigator**: Submit your resume and preferences to receive career analysis and guidance.
- **Authentication**: Simple signup and login forms (with social login placeholders).
- **Responsive UI**: Beautiful, mobile-friendly layouts using TailwindCSS.
- **Integrated Chatbot**: Ask questions about uploaded PDFs and get instant answers.

## Project Structure

```
killin/
├── public/                # Static assets (images, favicon)
├── src/
│   ├── assets/            # SVGs and backgrounds
│   ├── components/        # Svelte components (forms, chatbot, viewers)
│   ├── layouts/           # Astro layout files
│   ├── pages/             # Astro pages (index, login, signup, exam, career, etc.)
│   └── styles/            # Global styles (TailwindCSS)
├── package.json           # Project dependencies and scripts
├── astro.config.mjs       # Astro configuration
├── svelte.config.js       # Svelte integration config
├── tsconfig.json          # TypeScript config
└── .vscode/               # VSCode settings
```

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- npm

### Installation

1. Clone the repository:
   ```sh
   git clone <your-repo-url>
   cd Pathfinder
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm run dev
   ```

4. Open [http://localhost:4321](http://localhost:4321) in your browser.

### Backend API

- The app expects a backend running at `http://localhost:5000` for PDF upload, question answering, and career analysis.
- Update API endpoints in Svelte components if your backend runs elsewhere.

## Scripts

- `npm run dev` – Start development server
- `npm run build` – Build for production
- `npm run preview` – Preview production build

## Tech Stack

- [Astro](https://astro.build/)
- [Svelte](https://svelte.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- TypeScript
