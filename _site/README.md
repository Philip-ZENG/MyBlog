# Philip's Blog

A Jekyll-based blog website featuring a comprehensive AI technology report.

## Features

- **Table of Contents**: Automatically generated table of contents for blog posts
  - Fixed sidebar on desktop (right side)
  - Responsive design that adapts to different screen sizes
  - Smooth scrolling navigation
  - Active section highlighting
  - Hidden on mobile devices for better UX

## How to Use

### Adding Table of Contents to Posts

To add a table of contents to any blog post:

1. Add front matter to your markdown file:
```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD
---
```

2. The table of contents will be automatically generated from all headings (h1, h2, h3, h4, h5, h6) in your post.

### Running the Blog

1. Install dependencies:
```bash
bundle install
```

2. Build the site:
```bash
bundle exec jekyll build
```

3. Serve locally:
```bash
bundle exec jekyll serve
```

4. Visit `http://localhost:4000` in your browser

## Table of Contents Features

- **Automatic Generation**: No manual configuration needed
- **Hierarchical Display**: Different heading levels are indented appropriately
- **Smooth Scrolling**: Click any TOC item to smoothly scroll to that section
- **Active Highlighting**: Current section is highlighted as you scroll
- **Responsive Design**: Adapts to different screen sizes
- **Mobile-Friendly**: Hidden on small screens to preserve space

## Customization

The table of contents styling and behavior can be customized by editing the CSS and JavaScript in `_layouts/post.html`.


