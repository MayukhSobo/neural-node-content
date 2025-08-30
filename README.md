# Neural Node - Blog Content

This repository contains all the blog post content for the Neural Node data science blog.

## Structure

All blog posts are stored as MDX files in the root directory:

- `*.mdx` - Blog post files with frontmatter and content

## Adding New Posts

1. Create a new `.mdx` file
2. Add frontmatter with title, date, excerpt, tags, etc.
3. Write your content using MDX format
4. Commit and push - the blog will automatically rebuild!

## Frontmatter Format

```yaml
---
title: "Your Post Title"
date: "2024-01-15"
excerpt: "Brief description of your post"
tags: ["data-science", "python", "machine-learning"]
readingTime: "8 min read"
---
```

## Content Guidelines

- Use MDX format for rich content
- Include proper frontmatter metadata
- Add relevant tags for categorization
- Write engaging excerpts for post previews

## Auto-Deployment

This repository is connected to the Neural Node blog via Vercel. Any push to this repo will automatically trigger a rebuild and deployment of the blog with your new content. 