# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [Unreleased]

> Changes in progress or planned. See open [issues](https://github.com/github-samples/gitfolio/issues) and [pull requests](https://github.com/github-samples/gitfolio/pulls).

### Planned
- Add navigation bar to all pages ([#99](https://github.com/github-samples/gitfolio/issues/99))
- Improve image customization support ([#103](https://github.com/github-samples/gitfolio/issues/103))

---

## [1.0.0] – Initial Release

### Added
- Cyberpunk / retro-futuristic visual theme with neon cyan, fuchsia, and yellow accents on a deep-space background
- `ProjectCard` component with configurable `title`, `description`, `tags`, `color` (cyan / fuchsia / purple / yellow), and `href`
- `SocialLink` component for GitHub, LinkedIn, and Twitter footer links
- `STACK_TRACE` and `PROTOCOLS` sections for displaying tech stack and personal values
- Profile photo support via `/public/me.png`
- About / Bio section with freeform developer story copy
- Responsive layout — mobile, tablet, and desktop
- Monospaced terminal typography for the coder aesthetic
- Glowing hover effects, pulsing status indicator, and smooth CSS animations
- Semantic HTML structure with accessible contrast ratios

### Infrastructure
- Built with [Next.js](https://nextjs.org/) 16 (App Router), [React](https://react.dev/) 19, [Tailwind CSS](https://tailwindcss.com/) 4, and [TypeScript](https://www.typescriptlang.org/) 5
- GitHub Pages deployment pre-configured via GitHub Actions workflow (`.github/workflows/`)
- `basePath` support in `next.config.ts` for subdirectory deployments (`/YOUR_REPO_NAME`)
- ESLint configured via `eslint.config.mjs`
- `.gitignore`, `postcss.config.mjs`, and `tsconfig.json` included

### Project files
- `README.md` with Quick Start, customization guide, and deployment steps
- `CONTRIBUTING.md` with PR workflow guidelines
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`
- `SUPPORT.md`
- `LICENSE` (MIT)

---

## How to Contribute

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on submitting issues and pull requests.

[Unreleased]: https://github.com/github-samples/gitfolio/compare/HEAD...HEAD
[1.0.0]: https://github.com/github-samples/gitfolio/commits/main
