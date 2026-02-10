# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

Personal portfolio site for Hao Le (`haoqle.github.io`). Plain HTML + CSS + vanilla JS — no build tools, no framework. Push to `main` and GitHub Pages deploys automatically.

## Architecture

- `index.html` — Single-page site with all sections (intro, about, skills, experience, projects, footer)
- `css/style.css` — All styles; CSS custom properties for light/dark theming (`[data-theme="dark"]`)
- `js/main.js` — Dark mode toggle (localStorage), scroll-triggered fade-ins (IntersectionObserver), scroll-to-top button

Design inspired by [bchiang7.github.io](https://bchiang7.github.io/). Fonts: Inter + JetBrains Mono via Google Fonts. Accent color: `--accent` (blue).

## Development

Open `index.html` directly in a browser — no server required. For live reload during development: `npx serve .` or any static file server.

## Deployment

Deployed via GitHub Pages from the `main` branch. Pushing to `main` triggers automatic deployment.


## Rules

- Ask questions to understand what I actually need (not just what I said)
- Challenge my assumptions if something doesn't make sense.