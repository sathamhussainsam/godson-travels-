# Simple Shop Site

A Next.js application with Tailwind CSS, Prisma, and SQLite.

## Getting Started

First, install the dependencies:

```bash
npm install
```

Set up the database:

```bash
npm run db:push
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Database

This project uses Prisma with SQLite. The database file will be created at `prisma/dev.db` after running `npm run db:push`.

To open Prisma Studio:

```bash
npm run db:studio
```
