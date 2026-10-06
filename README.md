# MTEC3200 Project 1

This repository contains the Cat Box MVP, a Next.js app for helping cat owners take short, guided play breaks during work or study sessions.

## Project purpose

The app is based on the product requirements in `docs/PRD.md` and is intended to validate whether a lightweight, owner-led activity prompt helps redirect a kitten away from distractive items like chargers, keyboards, and screens.

## Current folder structure

```text
.
├── .github/
│   └── skills/
├── .vscode/
│   └── launch.json
├── app/
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── docs/
│   ├── PRD.md
│   ├── interviews/
│   │   └── interview-1.md
│   ├── research/
│   │   ├── AGENTS-template.md
│   │   ├── MVP-template.md
│   │   ├── PRD-template.md
│   │   ├── interview.md
│   │   ├── problem_statement.md
│   │   ├── routine-audit.md
│   │   ├── synthesis.md
│   │   └── what_how_why.md
│   └── synthesises/
│       └── synthesis-1.md
├── public/
│   ├── file.svg
│   ├── globe.svg
│   ├── next.svg
│   ├── vercel.svg
│   └── window.svg
├── .gitignore
├── AGENTS.md
├── README.md
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── package-lock.json
├── package.json
├── tsconfig.json
└── tsconfig.tsbuildinfo
```

## Key directories

- `app/`: main Next.js App Router application code and styling.
- `docs/`: product requirements, interviews, research notes, and synthesis documents.
- `public/`: static frontend assets.
- `.github/`: repository automation and helper skills.
- `.vscode/`: editor configuration.

## Getting started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open http://localhost:3000 to view the app.

## Common project commands

```bash
npm run dev
npm run build
npm run start
npm run lint
```

## Notes

- The app is built with Next.js, React, TypeScript, and Tailwind CSS.
- Product and research context lives in `docs/`, while app implementation lives in `app/`.
- This repo is currently structured as a product prototype and research workspace, not a final production app.
