# Innpae 🚀

**Innpae** is an AI-powered developer tool that turns natural-language product ideas into working backend code.  
Think: **Prompt → API → Database Schema → Zip Downloadable Project**.

It is built as a fast-moving MVP to help founders and developers prototype real backends in minutes instead of days.

---

## Why Innpae?

Building frontends is fast now.  
Setting up a backend is still slow: auth, schemas, routes, configuration.

Innpae removes that friction.

You describe your idea in plain English.  
It gives you a real backend codebase.

### Use cases
- Rapid SaaS MVPs
- Hackathon projects
- Startup backend bootstrapping
- Learning backend architecture faster

---

## Features

- Text prompt → backend structure generation
- AI-powered schema and API route planning
- Structured project folders
- API + ORM boilerplate
- Downloadable ZIP export
- Stack customization (planned and partially implemented)

> This is an early-stage MVP. Some features are being actively built.

---

## Tech Stack

- **Framework:** Next.js (App Router) + TypeScript
- **Runtime:** Bun / Node.js
- **ORM (planned):** Prisma
- **LLM:** Gemini (or compatible LLM)
- **File packaging:** JSZip (or similar)

---

## Getting Started

### Prerequisites

- Node.js or Bun
- Git installed
- LLM API Key (if running locally with AI enabled)

### Local Setup

```bash
git clone https://github.com/ikunal-04/innpae.git
cd innpae

bun install
bun dev
```

App runs on:

```bash
http://localhost:3000
Usage Flow
Open the web app.
```

Enter a product idea like:

```bash
A task manager where users can create projects and assign tasks.
Select your stack (DB / ORM / Framework) when available.

Submit the prompt.
```

The system:
- Generates schemas
- Creates API routes
- Structures folders
- Download the ZIP.
- Run it locally with the provided CLI commands.

---

## Project Structure

```bash
/
├── app/              # Next.js App Router
├── components/       # UI components
├── lib/              # Core logic (LLM + codegen helpers)
├── prisma/           # ORM schema (generated)
├── public/           # Static files
├── hooks/            # Custom hooks
├── config/           # Environment config
└── README.mdx
```

---

## Roadmap

- Planned and in-progress:
 - Full Gemini / LLM integration
 - Multi-stack support (MySQL, MongoDB, Postgres)
 - ORM choices (Prisma, Drizzle, TypeORM)
 - Real-time file viewer (like VSCode)
 - Live iframe preview of generated backend
 - Auth + user projects

---

## Contributing

Contributions are welcome.

```bash
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request
Be clean. Be precise. No sloppy code.
```
