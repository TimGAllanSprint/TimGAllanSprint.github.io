# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages repository (`timgallansprint.github.io`) that hosts a personal portfolio website using Jekyll with markdown-based content.

## Site Architecture

**Static Site Generator**: GitHub Pages with Jekyll
- Automatic build and deployment on push to main branch
- No local build process required - GitHub Pages handles Jekyll compilation

**Content Structure**:
- `index.md` - Main landing page (rendered at root URL)
- `_config.yml` - Jekyll site configuration
- Content is written in markdown and automatically converted to HTML by Jekyll

## Configuration

**_config.yml** contains:
- Site metadata (title, description, author)
- Theme selection (currently: minima)
- Jekyll plugins (jekyll-feed, jekyll-seo-tag)
- Markdown processor: kramdown with GitHub Flavored Markdown (GFM)
- Syntax highlighter: rouge

**Available themes**: architect, cayman, dinky, hacker, leap-day, merlot, midnight, minima, minimal, modernist, slate, tactile, time-machine

## Content Development

**Adding new pages**:
- Create `.md` files in the root directory
- Jekyll automatically processes markdown files into HTML pages
- Pages are accessible at their filename path (e.g., `about.md` → `/about`)

**Markdown format**:
- Use GitHub Flavored Markdown (GFM)
- Front matter (YAML between `---` delimiters) can be added for page-specific settings

## Deployment

- Push to the `main` branch to deploy
- Site is live at: https://timgallansprint.github.io
- GitHub Pages automatically builds and publishes changes (typically within 1-2 minutes)

## Important Notes

- This repository uses markdown-only content (no HTML templates or custom Jekyll layouts)
- Jekyll configuration settings are fixed by GitHub Pages and cannot be modified (e.g., `safe: true`, `incremental: false`)
- No local development server setup is documented - changes are previewed by pushing to GitHub
