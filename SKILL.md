---
name: tailwind-pro
description: Enterprise patterns for Tailwind CSS v4+ including design tokens with @theme and OKLCH, CVA + tailwind-merge composition, dark mode class strategies, container queries, fluid typography with clamp, performance via @source and safelist, a11y best practices, and v3 to v4 migration guidance.
license: MIT
---

# Tailwind Pro

Skill for building production-grade design systems with Tailwind CSS v4+.

## Scope

- Design tokens: `@theme`, OKLCH colors, spacing, radius, shadows
- Component architecture: CVA with tailwind-merge, compound variants
- Theming: dark mode class strategy, no flash, system preference
- Layout: `@container`, named containers, responsive variants
- Typography: fluid type with `clamp()`, CSS variables
- Performance: `@source`, safelist, critical CSS, bundle size
- Accessibility: focus-visible, motion-reduce, touch targets, forced-colors
- Extensibility: `@utility`, `@custom-variant`
- Migration: v3 → v4 breaking changes, best practices

Use rules in `rules/` and snippets in `snippets/` as reference implementations. Avoid project-specific code.
