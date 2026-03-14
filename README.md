# BEELABSTUDIO — Organisation Standards

Central repository for **community health files**, templates, and quality standards across all BEELABSTUDIO projects.

## ⚠️ Global Rule — Language

> **All documentation, comments, commit messages, README files, PR descriptions, and any other written artifact must be in English — regardless of the language used in the request.**

## 📁 Structure

```
.github/
└── PULL_REQUEST_TEMPLATE.md        # Generic Pull Request template
skills/
├── domain/                         # Domain-specific AI skills
├── enabling/                       # Enabling / cross-cutting AI skills
├── foundation/                     # Foundation engineering role skills
└── process/                        # Workflow and process skills
```

## 📋 Pull Request Template

The `.github/PULL_REQUEST_TEMPLATE.md` file is automatically applied to all organisation repositories that **do not have** their own template.

Includes:
- Type of change (feat, fix, hotfix, refactor, style, docs, chore, i18n)
- References to issues, design and staging
- Code quality checklist
- Deploy checklist
- Space for visual evidence and reviewer notes

## 🤖 Shared AI Skills

The `skills/` directory contains reusable AI skill definitions (`SKILL.md` files) organised by category. Clone this repository locally and reference skills from your project's `copilot-instructions.md`.

| Category | Description |
|----------|-------------|
| `domain/` | Specialised domain knowledge (nutrition, databases, migrations…) |
| `enabling/` | Cross-cutting capabilities (SEO, UX/UI, integrations, research…) |
| `foundation/` | Core engineering roles (software engineer, QA, DBA, PM…) |
| `process/` | Workflow and process skills (git, business analysis, fiscal…) |

### Setup

Clone this repository to use shared skills locally:

```bash
git clone git@github.com:beelabstudio/.github.git ~/repos/.github
```

Then reference skills from your project's `copilot-instructions.md` using the path:
```
~/repos/.github/skills/<category>/<skill-name>/SKILL.md
```

## 🏗️ Default project stack

- HTML5 + CSS3 + Vanilla JavaScript (ES6+)
- GitHub Actions for CI/CD
- Conventional Commits (`feat:`, `fix:`, `chore:`, `docs:`)
- Branches: `feature/`, `fix/`, `hotfix/`, `chore/`
