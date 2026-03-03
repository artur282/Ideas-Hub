# Contributing to Ideas Hub

Thank you for your interest in contributing to Ideas Hub! 🎉

## How to Contribute

### 🐛 Reporting Issues

If you find a bug or have a suggestion:

1. Check [existing issues](../../issues) to avoid duplicates
2. Open a new issue with a clear title and description
3. Include steps to reproduce (for bugs)

### 💡 Suggesting Improvements

- Propose new templates or improvements to existing ones
- Suggest workflow enhancements
- Share ideas for new AI agent integrations

### 🔧 Submitting Pull Requests

1. **Fork** the repository
2. **Create a branch** from `main`:

   ```bash
   git checkout -b feature/your-improvement
   ```

3. **Make your changes** following the conventions below
4. **Commit** with a descriptive message:

   ```bash
   git commit -m "feat: add new template for API design"
   ```

5. **Push** and open a Pull Request

### Commit Message Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/):

| Prefix | Use For |
|--------|---------|
| `feat:` | New features or templates |
| `fix:` | Bug fixes |
| `docs:` | Documentation changes |
| `refactor:` | Restructuring without changing behavior |

## 📐 Conventions

### Folder Names

- Always use `kebab-case`
- Be descriptive: `api-recipe-manager`, NOT `project-1`

### Templates

- Use markdown headers hierarchically (single `# H1` per file)
- Keep lines under 100 characters
- Use GitHub alerts (`[!NOTE]`, `[!TIP]`, etc.) for callouts
- Include Mermaid diagrams for architecture when useful

### File Structure per Idea

```
ideas/<name>/
├── README.md                              ← Always present
└── docs/
    └── plans/
        ├── YYYY-MM-DD-<name>-design.md    ← After brainstorming
        └── YYYY-MM-DD-<name>-plan.md      ← When ready to implement
```

## 🌍 Code of Conduct

Be respectful, constructive, and inclusive. We follow the [Contributor Covenant](https://www.contributor-covenant.org/) code of conduct.

---

Thank you for helping make Ideas Hub better! ⭐
