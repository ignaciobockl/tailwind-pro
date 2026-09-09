# Contributing

Thank you for your interest in improving tailwind-pro!

## How to contribute

1. Fork the repository
2. Create a branch from `develop`
3. Make changes
4. Ensure CI passes
5. Open a Pull Request to `develop`

## Adding rules

Rules live in `rules/` as `.mdc` files.

- Keep content generic and universal
- Focus on Tailwind CSS v4+ patterns
- Include code examples with proper syntax highlighting
- No project-specific references

## Adding snippets

Snippets live in `snippets/`.

- Provide portable, copy-pasteable examples
- Use generic naming
- Include minimal comments explaining purpose

## Adding test cases

- `test-cases/trigger/` — cases that should activate the skill
- `test-cases/non-trigger/` — cases that should NOT activate the skill
- Use `.md` files with clear description and context

## Commits

Use Conventional Commits in English.

Examples:
- `feat: add container queries rule`
- `fix: correct dark mode example`
- `docs: update README badges`
- `chore: update CI workflow`

## Pull Request Guidelines

- Target branch: `develop`
- PR title follows Conventional Commits
- Describe changes and rationale
- Link related issues if any

## Code of Conduct

By participating, you agree to abide by the [Code of Conduct](CODE_OF_CONDUCT.md).

We welcome contributors of all backgrounds.
