# MakerOps Labs

<img src="../assets/images/makerops-hero.png" alt="MakerOps Labs" width="100%">

MakerOps Labs is a collection of free, self-hosted tools and resources built for small-scale makers and manufacturing outfits. The goal is to give small teams the same operational capabilities as larger organizations — without SaaS subscriptions, cloud lock-in, data exposure, or per-seat pricing.

> This organization is a work in progress. New repositories and integrations are being added as the ecosystem grows.

---

## Repositories

### [makerops-core](https://github.com/makerops-labs/makerops-core)

The central operations server. A Docker Compose stack that brings together best-in-class open-source and fair-use tools for running a small manufacturing business:

- **Inventory & production** — parts, BOMs, purchase and sales orders (InvenTree)
- **Invoicing & accounting** — quotes, billing, expenses (Invoice Ninja)
- **Customer support** — shared inbox and help desk (FreeScout)
- **Project management** — tasks, sprints, and work tracking (Plane)
- **Knowledge base** — internal docs and wikis (Outline)
- **Workflow automation** — integrates all services together (n8n, trigger.dev)
- **Local AI** — on-device LLM inference and image generation (Ollama, ComfyUI)

Runs comfortably on a modest home server or workstation (8–16 GB RAM).

### [makerops-edge](https://github.com/makerops-labs/makerops-edge)

A lightweight per-device companion that brings AI-powered assistance to individual team members. Runs locally with no required cloud dependencies and can connect to a shared Core instance for team workflows.

- Headless AI assistant with persistent local memory
- 118+ service integrations (email, calendar, project tools, and more)
- Works with cloud APIs (OpenAI, Anthropic, Gemini) or fully offline via Core's Ollama service
- Memory stored as local Markdown files — readable and editable in Obsidian

### More coming

Additional repositories are in development to expand the ecosystem. Stay informed and help others with the same by:

1. Follow the `MakerOps Labs` Organization to see when we launch new tools.
2. Star the repositories to help others find the project.
3. Watch the repositories (Click Watch -> Custom -> Releases) to get notified immediately when we drop a new version.

---

## Who is this for?

Small shops, solo makers, and growing workshops that want:

- Full control over their operational data
- A capable toolset without monthly subscription costs
- The option to run AI workflows without sending data to the cloud
- Modular setup — run only the services your operation actually needs

---

## Principles

- **Self-hosted** — your infrastructure, your data
- **Fair-use** — built on community-maintained tools for community use
- **Modular** — enable only what you need
- **Privacy-first** — no required cloud connections
- **Maker-focused** — designed for the realities of small-scale production, not enterprise IT

---

## Getting Started

See the README in each repository for setup instructions:

- [makerops-core](https://github.com/makerops-labs/makerops-core#readme)
- [makerops-edge](https://github.com/makerops-labs/makerops-edge#readme)
