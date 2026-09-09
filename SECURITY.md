# Security Policy

## Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 0.1.x   | :white_check_mark: |

## Reporting a Vulnerability

If you discover a security vulnerability, please do NOT open a public issue.

Email the maintainer at ignaciobockl96@gmail.com with:
- Description of the vulnerability
- Steps to reproduce
- Potential impact

We aim to acknowledge reports within 5 business days and provide a fix timeline.

## Security Best Practices

This skill concerns design system code. When applying patterns:
- Do not expose secrets in CSS custom properties
- Sanitize user-provided class names before concatenation
- Avoid `dangerouslySetInnerHTML` with dynamic Tailwind classes
- Keep dependencies up to date, especially tailwind-merge and CVA

Thank you for helping keep this skill safe.
