# Getting Started

## Prereqs
- Node.js 20+, PNPM 9+
- Docker (optional for local Postgres)
- Make (optional)

## Setup
1. `pnpm install`
2. Copy `.env.example` to `.env` and set values
3. `pnpm -w run dev`

## Environment
```
DATABASE_URL=postgres://user:pass@localhost:5432/foodtribe
NEXT_PUBLIC_APP_URL=http://localhost:3000
```
