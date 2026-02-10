# Platform of Things

Articles and Things - A Jekyll site using the just-the-docs theme.

## Requirements

- Ruby
- Bundler

## Setup

```bash
bundle install
```

## Development

```bash
bundle exec jekyll serve
```

Visit `http://localhost:4000`

## Adding Articles

Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`:

```markdown
---
layout: post
title: "Your Article Title"
---

Your content here.
```

## Assets

Place images, PDFs, and other assets in the `assets/` folder. Reference them in posts:

```markdown
![Alt text](/assets/image.png)
[Download PDF](/assets/document.pdf)
```

## Structure

```
_posts/          # Articles
assets/          # Images, PDFs, etc.
articles.md      # Articles listing page
projects.md      # Projects page
index.md         # Home page
_config.yml      # Jekyll configuration
```
