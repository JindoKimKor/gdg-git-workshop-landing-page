# Branch Naming Convention

Use the following prefixes when creating branches:

| Prefix | Purpose | Example |
|--------|---------|---------|
| `feat/` | New feature | `feat/navbar` |
| `fix/` | Bug fix | `fix/broken-link` |
| `chore/` | Maintenance, config, dependencies | `chore/update-dependencies` |
| `docs/` | Documentation changes | `docs/update-readme` |
| `refactor/` | Code restructuring (no behavior change) | `refactor/clean-up-css` |
| `test/` | Adding or updating tests | `test/add-unit-tests` |

## Rules

- Use **lowercase** and **hyphens** (`-`) to separate words
- Keep it **short but descriptive**
- Match the branch name to the **ticket/issue** it addresses

## Examples

```
feat/navbar          ← Adding a navigation bar (Issue #1)
feat/hero-section    ← Adding the hero section (Issue #2)
feat/footer          ← Adding the footer (Issue #3)
fix/navbar-alignment ← Fixing a bug in the navbar
```
