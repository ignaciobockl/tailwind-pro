---
name: tailwind-pro
description: "Tailwind CSS v4+ design system patterns: @theme and OKLCH tokens, CVA + tailwind-merge, @utility and @custom-variant, @apply in @layer components, dark mode class strategies (incl. data-theme), @container queries, fluid clamp typography and spacing, arbitrary values and properties (color-mix, :has), @source and safelist performance, @keyframes and reduced-motion a11y, and v3-to-v4 migration. Use @reference for CSS Modules; not for Tailwind v1/v2, Bootstrap, Sass, or CSS-in-JS."
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

## When to use

Use this skill when you need to:
- Build or migrate a design system with **Tailwind CSS v4+** (OKLCH, @theme, @utility, @custom-variant)
- Implement **component architecture** with CVA + tailwind-merge patterns
- Configure **dark mode** class strategy without flash / respecting system preference
- Use **container queries** (@container, named containers) for responsive components
- Apply **fluid typography** with clamp() via CSS variables
- Optimize **performance** with @source, safelist, critical CSS
- Ensure **accessibility** (focus-visible, reduced-motion, touch targets, forced-colors)
- Migrate from **Tailwind v3 → v4** following best practices

## Example

```css
/* tokens.css — design tokens via @theme */
@theme {
  --color-primary: oklch(0.55 0.22 260);
  --spacing-fluid: clamp(1rem, 2vw + 0.5rem, 2rem);
}

/* button.css — CVA + tailwind-merge component */
import { cva } from "class-variance-authority";
import { twMerge } from "tailwind-merge";

export const button = cva("inline-flex items-center justify-center font-medium transition-colors", {
  variants: {
    variant: {
      primary: "bg-primary text-primary-foreground hover:bg-primary/90",
      ghost: "bg-transparent hover:bg-accent text-accent-foreground",
    },
    size: {
      sm: "px-3 py-1.5 text-sm",
      md: "px-4 py-2",
    },
  },
  defaultVariants: { variant: "primary", size: "md" },
});

export const Button = ({ className, ...props }) => (
  <button className={twMerge(button({ variant, size }), className)} {...props} />
);
```

---

## Badges

![Version](https://img.shields.io/github/v/tag/ignaciobockl/tailwind-pro?label=version&sort=semver)
![License](https://img.shields.io/github/license/ignaciobockl/tailwind-pro)
![CI](https://github.com/ignaciobockl/tailwind-pro/actions/workflows/ci.yml/badge.svg)

Use rules in `rules/` and snippets in `snippets/` as reference implementations. Avoid project-specific code.
