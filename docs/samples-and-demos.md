# Samples & Demos

Samples and demos are a cornerstone of developer advocacy. This page covers best practices for creating, publishing, and maintaining them.

## What Makes a Great Sample?

A great sample:

- **Solves a real problem** that developers in your target audience actually encounter.
- **Is minimal and focused** — it demonstrates one key concept or scenario without unnecessary complexity.
- **Runs quickly** — developers should be able to clone, configure, and run it in under 5 minutes.
- **Is well documented** — the README explains the context, prerequisites, and how to run it.
- **Is maintained** — it works with current versions of the dependencies it relies on.

---

## Sample Quality Checklist

Before publishing a sample, verify it meets the following criteria:

### Code Quality

- [ ] Code follows the language/framework conventions for the ecosystem.
- [ ] No hardcoded secrets, credentials, or environment-specific values.
- [ ] Sensitive configuration is loaded from environment variables or a `.env` file (with a `.env.example` provided).
- [ ] No unnecessary dependencies are included.
- [ ] Code is formatted consistently.

### Repository Structure

- [ ] The repository has a clear, descriptive name.
- [ ] There is a `README.md` at the root (see [README Template](#readme-template) below).
- [ ] A `LICENSE` file is present (use MIT for most open-source samples).
- [ ] A `.gitignore` is present and appropriate for the language/framework.
- [ ] A `CONTRIBUTING.md` is present if contributions are expected.

### Runability

- [ ] The sample runs from a fresh clone without undocumented steps.
- [ ] Prerequisites are documented (language versions, tools, accounts needed).
- [ ] A working demo environment is available (GitHub Codespaces, Dev Container, or clear local setup steps).
- [ ] All required configuration values are documented.

### Documentation

- [ ] The README includes a description of what the sample demonstrates.
- [ ] Setup and run instructions are present and accurate.
- [ ] A screenshot or GIF of the running sample is included.
- [ ] Links to related documentation, blog posts, or tutorials are included.

---

## README Template

Every sample repository should have a README that follows this structure:

```markdown
# [Sample Name]

One-sentence description of what this sample demonstrates.

## Overview

2–3 sentence description of the scenario this sample covers and why it is useful.

## Features

- Feature 1
- Feature 2
- Feature 3

## Getting Started

### Prerequisites

- [Prerequisite 1] (link to installation instructions)
- [Prerequisite 2]

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/[org]/[repo].git
   cd [repo]
   ```
2. Install dependencies:
   ```bash
   [install command]
   ```
3. Configure environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your values
   ```

### Running the Sample

```bash
[run command]
```

## Demo / Screenshot

[Add a screenshot or GIF here]

## Resources

- [Related documentation](https://...)
- [Related blog post](https://...)
- [Related tutorial](https://...)
```

---

## GitHub Repository Best Practices

- Use **topics** on your GitHub repository to improve discoverability (e.g., `azure`, `github`, `typescript`, `tutorial`).
- Add a **description** to the repository (shown on GitHub and in search results).
- Add a **social preview image** to the repository for better visual appearance when shared.
- Enable **GitHub Discussions** if you want community members to ask questions about the sample.
- Pin the repository to your organization profile if it is a flagship sample.

---

## Demo Best Practices

For live or recorded demos, see [Advocacy Techniques – Live Demos](techniques.md#2-live-demos).

### Additional Demo Tips

- **Prepare your environment** – Close unnecessary windows and browser tabs. Increase your font size.
- **Have reset scripts** – If the demo modifies state, prepare a script to reset to a clean state between runs.
- **Test your recording setup** – If recording, check audio levels, screen resolution, and frame rate before you start.
- **Keep it to the point** – Aim for the shortest path from problem to working solution.

---

## Maintaining Samples

Samples that are broken or outdated reflect poorly on the product and the team. Plan for ongoing maintenance:

- Review samples at least every 6 months for dependency updates.
- Set up CI/CD to run automated tests on pull requests and on a schedule.
- Monitor GitHub Issues for reports of broken functionality.
- Update samples when breaking changes are released in the product or dependencies.
- Archive or redirect samples that are no longer maintained.

---

## Codespaces and Dev Containers

GitHub Codespaces and Dev Containers dramatically lower the barrier to trying a sample by eliminating local setup.

### Setting Up a Dev Container

Add a `.devcontainer/devcontainer.json` to your sample repository:

```json
{
  "name": "Sample Dev Container",
  "image": "mcr.microsoft.com/devcontainers/universal:2",
  "postCreateCommand": "[install command]",
  "customizations": {
    "vscode": {
      "extensions": [
        "[recommended extension id]"
      ]
    }
  }
}
```

This allows developers to open the sample in a fully configured environment with one click via GitHub Codespaces or VS Code Dev Containers.
