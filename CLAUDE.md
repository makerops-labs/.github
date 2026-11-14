# CLAUDE.md — MakerOps Labs Org Profile

## What this repo is

This is the GitHub organization profile repository (`.github`) for the **MakerOps Labs** organization (`makerops-labs`). Its sole output is the content rendered at `github.com/makerops-labs` — specifically [profile/README.md](profile/README.md), the hero image in [assets/images/](assets/images/), and any future org-level GitHub configuration (issue templates, workflow policies, etc.).

It is **not** a software project. There is no build system, no dependencies, and no tests. Work here is entirely editorial and structural.

## Project context and goals

**MakerOps Labs** gives small-scale makers and manufacturing outfits the same operational tooling as larger organizations — without SaaS subscriptions, cloud lock-in, or per-seat pricing. Everything is self-hosted, modular, and built on open-source tools; MakerOps' own code is source-available.

The ecosystem currently consists of two sibling repositories (separate repos, not subdirectories here):

| Repo | Purpose |
|---|---|
| `makerops-core` | Docker Compose stack — InvenTree, Invoice Ninja, FreeScout, Plane, Outline, n8n, Ollama, ComfyUI |
| `makerops-edge` | Per-device AI companion — local memory, 118+ integrations, works offline via Core's Ollama |

More repos are in development (workflow templates, integration sandboxes, utilities).

**Core principles to preserve in all copy and decisions:**
- Self-hosted — user owns their data and infrastructure
- Built on open-source, community-maintained tools (MakerOps' own code is source-available: PolyForm Noncommercial or Internal Use)
- Modular — run only what you need
- Privacy-first — no required cloud connections
- Maker-focused — realities of small-scale production, not enterprise IT

## Audience

Primary: solo makers, small shops, growing workshops that want operational capability without subscription costs or cloud dependency.
Secondary: contributors and tool maintainers evaluating the ecosystem.

Speak to them plainly. Avoid enterprise jargon. Keep the tone practical and direct.

## What AI work looks like here

Most tasks in this repo will be one of:

1. **Copy edits** — refining the profile README for clarity, accuracy, or tone
2. **Structure changes** — adding sections, repos, or links as the ecosystem grows
3. **Asset guidance** — advising on or generating new visual assets
4. **GitHub org config** — issue templates, CODEOWNERS, funding.yml, etc.
5. **Cross-repo context** — understanding how this profile fits the broader ecosystem

## Guidelines for staying on track

- **Don't add complexity that doesn't serve the reader.** This is a landing page. Every sentence should earn its place.
- **Preserve the principles.** Any change to framing or copy should be consistent with the five core principles above. When in doubt, ask.
- **Match the existing tone.** The current README is plain, confident, and concise — no hype, no filler. Keep it that way.
- **Check sibling repos before making claims.** If a task references what `makerops-core` or `makerops-edge` does, verify against those repos rather than inferring from this one.
- **Don't invent repos or features.** The ecosystem is explicitly marked as a work in progress. Don't reference things that don't exist yet.
- **Keep the hero image path correct.** It is referenced as `../assets/images/makerops-hero.png` from inside `profile/README.md`.

## Repository layout

```
makerops-org/
├── CLAUDE.md                        # This file
├── README.md                        # Brief repo-level description
├── CONTRIBUTING.md                  # How to help (pull requests currently paused)
├── FUNDING.md                       # Ways to support the project
├── LICENSE                          # PolyForm Noncommercial OR Internal Use 1.0.0
├── profile/
│   └── README.md                   # GitHub org landing page (the main artifact)
└── assets/
    └── images/
        └── makerops-hero.png       # 1024x1024 hero image, ~1 MB
```

## Sibling repos (not in this directory)

- `../makerops-core` (sibling checkout) — if it exists locally
- `../makerops-edge` (sibling checkout) — if it exists locally

Check whether they're cloned before referencing their internals.
