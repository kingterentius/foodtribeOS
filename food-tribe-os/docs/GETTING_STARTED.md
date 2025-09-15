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
Getting Started with Food Tribe OS
Welcome to the Food Tribe OS! This document provides everything you need to know to get started with the Food Tribe ecosystem, whether you're a developer, a designer, or a community contributor.

What is Food Tribe OS?
Food Tribe OS is an open-source initiative dedicated to connecting good people to good food. It's a comprehensive platform that includes a discovery application, community engagement tools, and a rich database of food-related information. Our mission is to build a transparent, equitable, and accessible food system for everyone.

The ecosystem is built upon four core pillars:

Supporting: Focusing on cuisine, culinary arts, and culture.

Provisioning: Addressing food justice, access, and equity.

Regulating: Covering food science, data, and innovation.

Cultural: Exploring the physical and social aspects of eating and drinking.

First Steps
Explore the Vision: Start by reviewing the docs/OS_DIAGRAM.md and docs/ROADMAP.md to understand the big picture and where we're headed.

Understand Our Users: Check out docs/personas.md to get familiar with the different users we're building for, from "Foodies" to "Non-Profits."

Join the Community: We welcome contributors of all kinds! Please read our CONTRIBUTING.md and CODE_OF_CONDUCT.md in the root directory to learn how you can participate.

Setting Up Your Development Environment
To start working on the Food Tribe OS applications, you will need to have Node.js and npm (or yarn) installed on your machine.

Clone the repository:

git clone [https://github.com/foodtribeOS/food-tribe-os.git](https://github.com/foodtribeOS/food-tribe-os.git)
cd food-tribe-os

Install dependencies:
Navigate to the specific app or package you want to work on (e.g., apps/web/discovery-app) and run:

npm install

Run the application:

npm start

This will launch the development server for the application you're working on.

We're thrilled to have you here. Let's build a better food future together!
