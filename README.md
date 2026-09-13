# tailwind-pro

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)
[![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](CHANGELOG.md)
[![Contributing](https://img.shields.io/badge/contributing-welcome-green.svg)](CONTRIBUTING.md)
[![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-enforced-lightgrey.svg)](CODE_OF_CONDUCT.md)

Enterprise patterns for Tailwind CSS v4+ — design systems, component architecture, dark mode, container queries, fluid typography, performance, accessibility, and migration.

## What it does

This skill provides reusable rules, snippets, and test cases for building production-grade UIs with Tailwind CSS v4+.

- Design tokens with `@theme` and OKLCH
- CVA + tailwind-merge component patterns
- Dark mode class strategy without flash
- Container queries with `@container`
- Fluid typography using `clamp()`
- Performance with `@source`, safelist, and critical CSS
- A11y: focus-visible, motion-reduce, touch targets, forced-colors
- Custom utilities and variants
- v3 → v4 migration guidance

## Structure

```
tailwind-pro/
├─ SKILL.md
├─ README.md
├─ LICENSE.md
├─ CHANGELOG.md
├─ SECURITY.md
├─ CODE_OF_CONDUCT.md
├─ CONTRIBUTING.md
├─ .github/workflows/ci.yml
├─ rules/          # 10 .mdc rules
├─ snippets/       # 6 reusable snippets
├─ test-cases/
│  ├─ trigger/     # 25 should-activate cases
│  └─ non-trigger/ # 25 should-not-activate cases
└─ eval/
   ├─ qualitative-rubric.md
   └─ quantitative-metrics.yaml
```

## Quick start

1. Read `SKILL.md` for overview.
2. Apply rules from `rules/`.
3. Copy snippets from `snippets/` as starting points.
4. Validate with `test-cases/` and `eval/`.

## Examples

- Design tokens: `rules/theme-tokens-design-system.mdc`
- CVA button: `snippets/cva-button.ts`
- Dark mode: `rules/dark-mode-strategies.mdc`
- Container query card: `snippets/container-query-card.css`

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Use Conventional Commits and PR to `develop`.
