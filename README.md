# Idea Forge 

Idea Forge is a full-stack Next.js app that helps you generate **unique, technically plausible project ideas**, and then turns them into a concrete, buildable plan.

Instead of spitting out yet another “to-do app” or “smart door lock,” it will:
- Fuses together multiple technical domains
- Injects constraints (offline-only, low BOM cost, no cameras, etc.)
- Asks an LLM to propose several candidate ideas in a strict JSON format
- Checks the web for similar products/projects to estimate novelty

Once you like an idea, you can hit **“Plan this project”** to get:
- A rough **timeframe** (weeks + intensity)
- Required **technical knowledge** and topics to learn
- A high-level **budget estimate**
- **Funding ideas** (grants, labs, clubs, etc.)
- **Alternative solutions** that exist today
- Concrete **problems it solves** / use cases
- Key **risks & gotchas**
- A set of **chronological milestones** you can follow like a mini roadmap

Future features
- Next.js (App Router)
- A small novelty engine powered by an LLM (no database required)
- A modern dark UI with interactive idea cards and a project planner panel
- PostgreSQL + Prisma for storing ideas and domains/primitives
- Tavily (or another search provider) to check for similar work
- API endpoints for generating, storing, and browsing ideas over time
