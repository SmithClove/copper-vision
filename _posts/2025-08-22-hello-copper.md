---
layout: post
title: Hello, Copper
date: 2025-08-22
tags: [meta, setup]
excerpt: Launch notes for Copper Vision — the design, stack, and how it ships via GitHub Pages.
---

Quick notes on the stack:

- **Jekyll + GitHub Pages**: simple, reliable, free.
- **Tailwind (Play CDN)**: fast iteration without a build pipeline.
- **Dark mode**: header toggle, respects OS preference.
- **SEO**: `jekyll-seo-tag`, `jekyll-sitemap`, `jekyll-feed`.
- **Custom domain**: `CNAME` set to `copper.vision`.

Edit `_config.yml` for metadata. Write posts in `_posts` using Markdown front matter.
