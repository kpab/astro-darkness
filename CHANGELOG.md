# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2026-06-19

### Changed
- Upgraded to **Astro 6** (`astro@^6.0.0`, `@astrojs/mdx@^6.0.0`) ([#25](https://github.com/kpab/astro-darkness/issues/25))
- Updated `@astrojs/rss` to `^4.0.18` and `@astrojs/sitemap` to `^3.7.0`
- Updated Three.js to `^0.184.0` (and `@types/three`)
- Updated `@astrojs/check` to `^0.9.9`
- Migrated content collection schemas to import `z` from `astro/zod` (Zod 4)
- Bumped CI Node version to 22 and added `engines.node >= 22`

### Fixed
- Three.js animation persistence across View Transitions navigation ([#6](https://github.com/kpab/astro-darkness/pull/6))

## [1.0.0] - 2026-01-04

### Added
- Initial release of Darkness - Astro Dark Theme
- Dark-themed portfolio/blog template with professional color palette
- Three.js particle system with 5000 animated particles and 3D effects
- Full-featured blog system using Astro Content Collections
- Portfolio/project showcase with featured projects support
- Responsive mobile-first design with floating navigation bar
- Smooth animations and hover effects throughout
- TypeScript support for type-safe development
- MDX support for blog posts and project pages
- RSS feed generation for blog posts
- Sitemap generation for SEO
- Content collections for blog posts and projects with schema validation
- Customizable CSS variables for easy theming
- Multiple sample blog posts demonstrating features
- Sample projects showcasing portfolio capabilities
- About page with skills and features sections
- Google Fonts integration (Space Grotesk + DM Sans)
- GitHub Pages deployment workflow
- MIT License

### Technical Stack
- Astro 5.1.0 as the static site generator
- Three.js 0.160.0 for 3D particle effects
- TypeScript 5.9.3 for type safety
- @astrojs/mdx for enhanced markdown support
- @astrojs/rss for feed generation
- @astrojs/sitemap for SEO optimization

[unreleased]: https://github.com/kpab/astro-darkness/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/kpab/astro-darkness/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/kpab/astro-darkness/releases/tag/v1.0.0
