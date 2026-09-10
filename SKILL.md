---
name: tailwind-pro
description: Tailwind CSS v4+ design system patterns: @theme and OKLCH tokens, CVA + tailwind-merge, @utility and @custom-variant, @apply in @layer components, dark mode class strategies (incl. data-theme), @container queries, fluid clamp typography and spacing, arbitrary values and properties (color-mix, :has), @source and safelist performance, @keyframes and reduced-motion a11y, and v3-to-v4 migration. Use @reference for CSS Modules; not for Tailwind v1/v2, Bootstrap, Sass, or CSS-in-JS.
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
