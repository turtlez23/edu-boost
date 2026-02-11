# EduBoost

## Project Description
EduBoost is a web application that automates Active Recall by turning user notes into interactive fill-in-the-blank tests. The Ultra-MVP focuses on a single value loop: paste text → generate test → solve and track results.

## Table of Contents
- [Project Description](#project-description)
- [Tech Stack](#tech-stack)
- [Getting Started Locally](#getting-started-locally)
- [Available Scripts](#available-scripts)
- [Project Scope](#project-scope)
- [Project Status](#project-status)
- [License](#license)

## Tech Stack
- Frontend: Astro 5, React 19, TypeScript 5, Tailwind 4, Shadcn/ui
- Backend: Supabase (PostgreSQL + Auth)
- AI: Openrouter.ai (provider gateway for multiple AI models)
- CI/CD & Hosting: GitHub Actions, DigitalOcean (Docker)

## Getting Started Locally
Prerequisites:
- Node.js `22.14.0` (see `.nvmrc`)
- npm (comes with Node.js)

Steps:
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the dev server:
   ```bash
   npm run dev
   ```
3. Open the app (default Astro dev URL shown in terminal).

## Available Scripts
- `npm run dev` — start Astro dev server
- `npm run build` — build production bundle
- `npm run preview` — preview production build
- `npm run astro` — run Astro CLI
- `npm run lint` — run ESLint
- `npm run lint:fix` — auto-fix lint issues
- `npm run format` — run Prettier on the repo

## Project Scope
In scope (Ultra-MVP):
- User authentication (email + password).
- Create tests by pasting up to 5000 characters of notes with a live counter.
- AI generates a fill-in-the-blank test, with mandatory edit-before-save.
- Save tests with a title and store them in the database.
- Solve tests with case-insensitive validation (diacritics-sensitive), score display, and retry.
- Dashboard “My Tests” list with last score, progress bar, and delete action.
- Track AI generation usage and acceptance rate (save vs reject).

Out of scope (Ultra-MVP):
- Flashcards module (all related features).
- Self-service password reset.
- Advanced account settings.
- File imports (PDF/DOCX/etc.).
- Test sharing.
- Mobile apps.
- Other test types.

Additional documentation:
- Product requirements: `.ai/prd.md`
- Tech stack overview: `.ai/tech-stack.md`

## Project Status
Ultra-MVP in progress. Target is to deliver the core value loop (text → test → result) by Dec 14, 2025.

## License
License not specified. Add a license file to clarify usage and distribution terms.
# 10x Astro Starter

A modern, opinionated starter template for building fast, accessible, and AI-friendly web applications.

## Tech Stack

- [Astro](https://astro.build/) v5.5.5 - Modern web framework for building fast, content-focused websites
- [React](https://react.dev/) v19.0.0 - UI library for building interactive components
- [TypeScript](https://www.typescriptlang.org/) v5 - Type-safe JavaScript
- [Tailwind CSS](https://tailwindcss.com/) v4.0.17 - Utility-first CSS framework

## Prerequisites

- Node.js v22.14.0 (as specified in `.nvmrc`)
- npm (comes with Node.js)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/przeprogramowani/10x-astro-starter.git
cd 10x-astro-starter
```

2. Install dependencies:

```bash
npm install
```

3. Run the development server:

```bash
npm run dev
```

4. Build for production:

```bash
npm run build
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run lint:fix` - Fix ESLint issues

## Project Structure

```md
.
├── src/
│   ├── layouts/    # Astro layouts
│   ├── pages/      # Astro pages
│   │   └── api/    # API endpoints
│   ├── components/ # UI components (Astro & React)
│   └── assets/     # Static assets
├── public/         # Public assets
```

## AI Development Support

This project is configured with AI development tools to enhance the development experience, providing guidelines for:

- Project structure
- Coding practices
- Frontend development
- Styling with Tailwind
- Accessibility best practices
- Astro and React guidelines

### Cursor IDE

The project includes AI rules in `.cursor/rules/` directory that help Cursor IDE understand the project structure and provide better code suggestions.

### GitHub Copilot

AI instructions for GitHub Copilot are available in `.github/copilot-instructions.md`

### Windsurf

The `.windsurfrules` file contains AI configuration for Windsurf.

## Contributing

Please follow the AI guidelines and coding practices defined in the AI configuration files when contributing to this project.

## License

MIT
