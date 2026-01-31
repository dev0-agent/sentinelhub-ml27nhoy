# SentinelHub

> The vigilant issue tracker for modern SaaS teams.

## Overview

SentinelHub is a full-stack issue management system designed for speed and simplicity. Built to help teams track bugs and feature requests without the bloat of enterprise tools, it leverages server-side rendering and optimistic UI patterns to provide a seamless, app-like experience.

## Tech Stack

- **Framework:** TanStack Start (React SSR)
- **Routing:** TanStack Router
- **Data Fetching:** TanStack Query (via Start loaders)
- **Database:** SQLite (via Drizzle ORM)
- **Styling:** Tailwind CSS

## Features

- **Real-time Feel:** Optimistic updates for status changes and issue creation.
- **Dashboard:** High-level metrics and priority breakdowns.
- **Issue Management:** Full CRUD capabilities with rich text support.
- **Workflow Control:** Customizable status pipelines (Backlog -> Done).
- **Deep Linking:** All filters and views are state-managed via URL.
- **Collaboration:** Threaded comments on every issue.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd sentinel-hub
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup Database**
   ```bash
   npm run db:push
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view the app.

## Documentation

- [TASKLIST.md](./TASKLIST.md) - Detailed breakdown of development tasks.
- [LEARNINGS.md](./LEARNINGS.md) - Technical decisions and architectural notes.
- [.dev0/RULES.md](./.dev0/RULES.md) - AI coding agent guidelines.