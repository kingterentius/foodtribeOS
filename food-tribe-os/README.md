# Food Tribe OS

**The open-source components of the Operating System for a Circular Food Economy.**

> Connecting good people to good food through technology, incentives, and data.

---

## Our Vision
Food Tribe is a platform that connects diners, restaurants, and partners to reward sustainable choices and reduce food waste and insecurity. This repo contains the public, open-source building blocks and documentation for the platform.

## Core Modules (public subset)
- **apps/web** — Next.js front-end (landing, docs, and public UI patterns)
- **services/api** — Example API scaffolding with TypeScript/Express (public endpoints & contracts)
- **services/gamification** — Rules/points engine interface & sample rules
- **packages/ui** — Shared React components (design system starter)
- **packages/config** — Shared config (TypeScript, ESLint, Prettier)
- **docs** — Architecture, roadmap, contribution guide, governance

> Proprietary/private services (e.g., full data models, commercial integrations) should live in private repos and reference these public packages.

## Tech Stack
- Next.js • React • TypeScript
- Node.js • Express • PostgreSQL (via Prisma)
- Turbo/PNPM workspaces (monorepo), Docker
- GitHub Actions for CI

## Getting Started
```bash
# 1) Install PNPM & Turbo (optional) then install deps
pnpm install

# 2) Boot services
pnpm -w run dev
```

See [`docs/GETTING_STARTED.md`](docs/GETTING_STARTED.md) for full setup, including environment variables.

## Contributing
We ❤️ contributions! Please read [`CONTRIBUTING.md`](CONTRIBUTING.md) and our [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md). New issues are triaged with labels: `good first issue`, `help wanted`, and per-area labels.

## Security
See [`SECURITY.md`](SECURITY.md).

## License
MIT — see [`LICENSE`](LICENSE).

---

**Roadmap anchors**
- 90‑day foundation: repo hygiene, CI, public docs, first MVP module
- 18‑month: LA launch, gamification engine, RadicALL dashboard, second market

(Last updated 2025-08-29)
