# qaidjacobs.com

A Jekyll-powered portfolio website for Qa'id Jacobs, replacing the previous Squarespace site with a GitHub Pages compatible version.

## Development Setup

### Prerequisites
- Ruby 2.6+ 
- Bundler
- Jekyll

### Installation
```bash
# Install dependencies
bundle install

# Run the development server
bundle exec jekyll serve

# Build for production
bundle exec jekyll build
```

### Project Structure
```
├── _config.yml          # Jekyll configuration
├── _layouts/            # Page templates
├── _includes/           # Reusable components
├── _sass/              # SCSS stylesheets
├── assets/             # Static assets (CSS, JS, images)
├── _work/              # Case study collection
├── index.html          # Home page
├── work.html           # Portfolio page
├── about.html          # About page
├── publicly.html       # Speaking engagements
└── contact.html        # Contact page
```

## Deployment

This site is configured for GitHub Pages deployment. Simply push to the main branch and GitHub will automatically build and deploy the site.

## Features

- Responsive design
- Mobile-first navigation
- Case study portfolio
- Contact form integration
- SEO optimized
- Fast loading performance

## Technology Stack

- Jekyll 4.2.2
- SCSS for styling
- Vanilla JavaScript
- GitHub Pages hosting

---

© 2024 Qa'id Jacobs
