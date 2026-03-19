# Chantal's Dev Portfolio & Blog

A personal developer portfolio and blog built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). Showcasing projects, sharing insights on web development, mobile, DevOps, and more.

## Live Site

Visit: [https://Uchantal.github.io/Githubactions](https://Uchantal.github.io/Githubactions)

## Local Development

### Prerequisites
- Ruby 3.x
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Serve locally
bundle exec jekyll serve
```

Then open [http://localhost:4000](http://localhost:4000) in your browser.

## Structure

```
Githubactions/
├── _config.yml       # Site configuration
├── _posts/           # Blog posts (5 posts)
├── index.md          # Home page
├── about.md          # About page
├── blog.md           # Blog listing page
├── projects.md       # Projects page
├── contact.md        # Contact page
└── Gemfile           # Ruby dependencies (includes github-pages gem)
```

## Theme

This site uses the [Cayman](https://github.com/pages-themes/cayman) theme via `jekyll-remote-theme`.

## Pages

1. Home (`/`)
2. About (`/about/`)
3. Projects (`/projects/`)
4. Blog (`/blog/`)
5. Contact (`/contact/`)

Plus 5 blog posts on topics: Jekyll, React, GitHub Actions, Flutter, and Learning to Code.
