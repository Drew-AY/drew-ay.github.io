# Portfolio

My portfolio website built with Jekyll. Hosted on GitHub Pages at [drew-yobo.github.io](https://drew-yobo.github.io).

## Development

### Prerequisites

- Ruby 2.7+
- Bundler

### Setup

```bash
bundle install
```

### Running Locally

```bash
bundle exec jekyll serve
```

Visit `http://localhost:4000` to view the site.

### Structure

- `_projects/` — Individual project pages
- `_posts/` — Blog posts (date-sorted)
- `_writeups/` — Technical deep-dives
- `_layouts/` — HTML templates
- `_includes/` — Reusable components (nav, footer)
- `_data/` — YAML data files (certifications, etc.)
- `assets/css/` — Styling
- `projects/`, `blog/`, `writeups/`, `certifications/`, `announcements/` — Section landing pages

### Adding Content

**New Project:**
```bash
touch _projects/my-project.md
```

**New Blog Post:**
```bash
touch _posts/2026-04-28-my-post.md
```

**New Writeup:**
```bash
touch _writeups/my-writeup.md
```

Each file uses YAML front matter for metadata (title, date, tags, etc.).

### Deployment

Push to `drew-yobo.github.io` repository. GitHub Pages automatically builds and deploys.
