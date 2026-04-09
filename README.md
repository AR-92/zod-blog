# Zod Blog

Blog site for the Zod AI agent platform.

Built with [Astro](https://astro.build/), Tailwind CSS, and DaisyUI.

## Getting Started

```bash
# Install dependencies
bun install

# Start the development server
bun run dev

# Build for production
bun run build

# Preview the production build
bun run preview
```

## Project Structure

```
zod-blog/
├── public/              # Static assets
├── src/
│   ├── components/      # Astro components
│   ├── content/         # Blog posts (Markdown)
│   ├── layouts/         # Page layouts
│   ├── pages/           # Pages and routes
│   ├── styles/          # Global styles
│   └── content.config.ts # Content collections config
├── astro.config.mjs     # Astro configuration
└── package.json
```

## Adding Blog Posts

Add new blog posts to `src/content/blog/` as Markdown files with frontmatter:

```markdown
---
title: 'Your Post Title'
excerpt: 'A brief summary of the post'
date: 2026-04-09
author: Your Name
authorTwitter: yourtwitter
image: /placeholder.svg
tags: ['tag1', 'tag2']
---

Your post content here...
```

## Scripts

| Command          | Description                          |
| ---------------- | ------------------------------------ |
| `bun run dev`    | Start dev server at localhost:4321   |
| `bun run build`  | Build for production                 |
| `bun run preview`| Preview production build locally     |
