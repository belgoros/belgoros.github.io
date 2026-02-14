# Project Instructions

## Overview
Jekyll-based CV/portfolio site (GitHub Pages) using Tailwind CSS v4.

## Technology Stack
- Jekyll (static site generator)
- Tailwind CSS v4.1.18
- HTML/CSS/JavaScript
- GitHub Pages deployment

## Development Rules

### Jekyll
- Site files are in root directory
- Layouts in `_layouts/`
- Includes/partials in `_includes/`
- Generated site in `_site/` (ignored by git)
- Configuration in `_config.yml`

### Tailwind CSS
- Use Tailwind v4 syntax and features
- Utility-first approach for styling
- Custom styles in `css/` directory if needed

### File Structure
- Keep HTML clean and semantic
- Use Jekyll includes for reusable components
- Images in `img/`
- Scripts in `js/`

### Git Workflow
- Main branch: `master`
- Current branch: `update-design-with-tailwind`
- Never commit without explicit request
- Follow conventional commit messages when requested

### Code Style
- No comments unless explicitly requested
- Clean, minimal markup
- Mobile-first responsive design

## Common Tasks
- Local preview: `bundle exec jekyll serve`
- Build site: `bundle exec jekyll build`
- Tailwind CLI: `npx @tailwindcss/cli`
