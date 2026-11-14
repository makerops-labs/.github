# Contributing to MakerOps Labs

MakerOps Labs builds free, self-hosted operational tools for small makers and manufacturers — giving small teams the same capabilities as larger organizations without cloud lock-in or subscription costs. Every contribution, large or small, helps keep that mission going.

---

## Ways to Contribute

You don't need to write code to make a meaningful contribution.

### 1. Report Bugs and Request Features

Open an issue in the relevant repository. A clear bug report or a well-described feature request is genuinely valuable — it helps prioritize work and surfaces problems that aren't always visible to a solo maintainer.

When reporting a bug, include:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Your environment (OS, Docker version, hardware)

### 2. Improve Documentation

If setup instructions were unclear, a README was missing a step, or something confused you, open an issue describing it. A precise pointer to the gap helps every future user who hits the same wall.

### 3. Test and Give Feedback

Running the tools in your own environment and reporting what works (or doesn't) is a real contribution. Feedback on usability, performance, or gaps in functionality helps shape what gets built next.

### 4. Submit Code

The repositories are **not accepting outside code or documentation contributions (pull requests) for now**, while the licensing for contributions is settled. Issues, bug reports, feature ideas and feedback are very welcome. The [Pull Requests](#pull-requests) process below applies once contributions reopen.

### 5. Spread the Word

Star the repositories, share the project with other makers, mention it in communities where it might help someone. Visibility directly affects whether this project is sustainable.

### 6. Support the Project Financially

Building and maintaining this takes real time and money. If MakerOps Labs saves you a subscription or solves a real problem in your operation, consider supporting it. Financial options aren't set up yet; [FUNDING.md](FUNDING.md) lists other ways to help in the meantime.

---

## Getting Started

Each repository has its own setup instructions:

- [makerops-core](https://github.com/makerops-labs/makerops-core#readme) — the central operations stack
- [makerops-edge](https://github.com/makerops-labs/makerops-edge#readme) — the per-device AI companion

Start with the README in the repo you want to contribute to.

---

## Pull Requests

> **Paused:** outside pull requests aren't being accepted right now (see [Submit Code](#4-submit-code)). This is the process for when they reopen.

1. **Fork** the repository and create a branch from `main`.
2. **Make your changes.** Keep the scope focused — one concern per PR makes review faster and merging safer.
3. **Test your changes** against a local instance before opening the PR.
4. **Open a PR against `main`** with a description that explains:
   - *What* changed
   - *Why* it was changed (link to an issue if one exists)
   - Any setup or migration steps needed

PRs that add features not discussed in an issue first may take longer to review or may be declined — opening an issue to discuss intent upfront saves everyone time.

---

## Code Style

Match the conventions already in the repository you're contributing to. If the repo includes a linter config or formatter, use it. If it doesn't, follow the patterns already in the codebase rather than introducing new ones.

---

## License

MakerOps code is **source-available** under your choice of the [PolyForm Noncommercial 1.0.0 or PolyForm Internal Use 1.0.0](LICENSE) licenses. Outside code contributions are paused for now, so there are no contribution terms to agree to yet. If pull requests reopen, any contribution terms will be posted here first.
