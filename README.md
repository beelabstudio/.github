# BEELABSTUDIO — Padrões da Organização

Repositório central de **community health files**, templates e padrões de qualidade para todos os projetos da BEELABSTUDIO.

## 📁 Estrutura

```
.github/
└── PULL_REQUEST_TEMPLATE.md   # Template genérico de Pull Request
```

## 📋 Pull Request Template

O arquivo `.github/PULL_REQUEST_TEMPLATE.md` é automaticamente aplicado a todos os repositórios da organização que **não possuam** um template próprio.

Inclui:
- Tipo de alteração (feat, fix, hotfix, refactor, style, docs, chore, i18n)
- Referências a issues, design e staging
- Checklist de qualidade de código
- Checklist de deploy
- Espaço para evidências visuais e notas ao reviewer

## 🏗️ Stack padrão dos projetos

- HTML5 + CSS3 + Vanilla JavaScript (ES6+)
- GitHub Actions para CI/CD
- Conventional Commits (`feat:`, `fix:`, `chore:`, `docs:`)
- Branches: `feature/`, `fix/`, `hotfix/`, `chore/`
