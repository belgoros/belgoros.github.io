# Portfolio & CV Site

A modern Jekyll-based portfolio and CV page with Tailwind CSS.

## Tech Stack

- **Jekyll** - Static site generator
- **Tailwind CSS v4** - Utility-first CSS framework
- **GitHub Pages** - Hosting

## Prerequisites

- **Ruby** & **Jekyll**
- **Node.js** & **npm** (for Tailwind CSS)

## Installation

1. Clone the repository locally
```bash
git clone https://github.com/belgoros/belgoros.github.io.git
cd belgoros.github.io
```

2. Install Ruby dependencies
```bash
bundle install
```

3. Install Node.js dependencies
```bash
npm install
```

## Development

### Build Tailwind CSS

Build the CSS file (required before running Jekyll):
```bash
npm run build:css
```

Watch for changes and auto-rebuild CSS:
```bash
npm run watch:css
```

### Run Jekyll

Start the Jekyll development server:
```bash
bundle exec jekyll serve
```

Then navigate to `http://localhost:4000`

## Making Changes

1. Update `_config.yml` with your personal details
2. Modify content in `_includes/` section files
3. If you change Tailwind classes, rebuild CSS with `npm run build:css`
4. Commit the generated `css/tailwind.css` file (required for GitHub Pages)

## Deployment to GitHub Pages

GitHub Pages will automatically build and deploy when you push to the `master` branch:

```bash
# Build CSS
npm run build:css

# Commit changes
git add .
git commit -m "Update content"

# Push to GitHub
git push origin master
```

Your site will be live at `https://belgoros.github.io`

## Project Structure

```
.
├── _config.yml           # Site configuration
├── _includes/            # Section components
├── _layouts/             # Page layouts
├── css/
│   ├── input.css        # Tailwind source
│   └── tailwind.css     # Built CSS (commit this)
├── index.html           # Main page
└── package.json         # Node dependencies
```

## Customization

- **Colors & Theme**: Edit `css/input.css` @theme section
- **Content**: Update `_config.yml` and section files in `_includes/`
- **Layout**: Modify `_layouts/default.html` and section order in `index.html`
