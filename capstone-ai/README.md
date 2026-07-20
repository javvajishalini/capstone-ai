# Capstone AI

An AI-powered web application built as a capstone project. The frontend delivers an interactive experience for users to work with intelligent, automated workflows through a modern React interface.

> **Status:** Early development — repository setup is complete; application scaffolding and core features are in progress.

## Overview

Capstone AI pairs a React frontend with a Node.js backend to expose AI-driven capabilities through a responsive, accessible UI. The focus is on clear user feedback (loading states, errors, and results), maintainable TypeScript code, and a design that scales as features are added.

## Tech Stack

| Layer    | Technologies                          |
| -------- | ------------------------------------- |
| Frontend | React, TypeScript, Vite, Tailwind CSS |
| Backend  | Node.js                               |
| Tooling  | ESLint, Prettier, Vitest              |

## Prerequisites

- **Node.js** 18+ (20 LTS recommended)
- **npm**, **pnpm**, or **yarn**

## Getting Started

```bash
# Clone the repository
git clone <repository-url>
cd capstone-ai

# Install dependencies (after project scaffolding)
npm install

# Start the development server
npm run dev
```

The dev server runs at `http://localhost:5173` by default (Vite).

### Environment Variables

When an `.env.example` file is added, copy it to `.env.local` and set the required values:

```bash
cp .env.example .env.local
```

Never commit secrets or `.env.local` to version control.

## Scripts

These commands will be available once the Vite project is initialized:

| Command           | Description                        |
| ----------------- | ---------------------------------- |
| `npm run dev`     | Start the Vite development server  |
| `npm run build`   | Create a production build          |
| `npm run preview` | Preview the production build locally |
| `npm run test`    | Run Vitest unit tests              |
| `npm run lint`    | Run ESLint                         |

## Project Goals

- Build a responsive, accessible UI that works across desktop and mobile viewports.
- Integrate AI features with explicit loading, error, and success states so users always know what is happening.
- Keep a scalable folder structure with typed APIs and shared conventions (see [CLAUDE.md](./CLAUDE.md)).
- Maintain consistent code quality through ESLint, Prettier, Vitest, and [Conventional Commits](https://www.conventionalcommits.org/).

## Development Guidelines

Coding conventions, testing expectations, and git workflow are documented in [CLAUDE.md](./CLAUDE.md).

## License

This project is licensed under the [MIT License](./LICENSE).
