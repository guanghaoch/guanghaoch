---
layout: post
title: "Getting Started with Jekyll"
date: 2026-02-01 14:00:00 -0800
categories: [Tutorial, Web Development]
tags: [jekyll, tutorial, web-development]
---

Jekyll is a fantastic static site generator that makes it easy to create and maintain websites. In this post, I'll share some tips on getting started.

## Why Jekyll?

- **Simple:** Write in Markdown, not HTML
- **Static:** No database, just files
- **Fast:** Static sites load quickly
- **GitHub Pages:** Free hosting with GitHub

## Basic Structure

A typical Jekyll site includes:

```
_config.yml       # Configuration
_layouts/         # Page templates
_includes/        # Reusable components
_posts/           # Blog posts
assets/           # CSS, images, etc.
```

## Creating Posts

Posts go in the `_posts` directory and follow this naming convention:

```
YYYY-MM-DD-title.md
```

Each post starts with front matter:

```yaml
---
layout: post
title: "Your Title"
date: 2026-02-01
---
```

## Next Steps

Explore the [Jekyll documentation](https://jekyllrb.com/docs/) to learn more about customizing your site.
