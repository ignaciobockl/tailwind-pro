# Qualitative Rubric

Rate each dimension from 1 to 5.

## Theme Tokens
1 - No @theme usage, hard-coded colors
3 - Basic @theme with some tokens
5 - Complete @theme with OKLCH, semantic tokens, spacing scale

## CVA Patterns
1 - Manual class strings, duplication
3 - Uses cva but no tailwind-merge
5 - cva + tailwind-merge + compoundVariants + types

## Dark Mode
1 - No dark mode or flash
3 - class strategy with FOUC
5 - 3-way strategy, no flash, system preference, script in head

## Container Queries
1 - Only viewport media queries
3 - Uses @container with named containers
5 - Full component-level responsive with @container variants

## Fluid Typography
1 - Fixed font sizes
3 - Some clamp usage
5 - Systematic fluid type with CSS variables and clamp

## Performance
1 - No @source, large bundle
3 - Basic @source config
5 - Optimized @source, safelist, critical CSS, bundle metrics

## A11y
1 - No focus/motion considerations
3 - Basic focus-visible
5 - focus-visible, motion-reduce, touch targets, forced-colors

## Migration
1 - No migration guidance
3 - Basic v3 to v4 notes
5 - Comprehensive breaking changes and patterns

## Scoring Guide
- 1: Missing
- 2: Partial
- 3: Adequate
- 4: Good
- 5: Excellent
