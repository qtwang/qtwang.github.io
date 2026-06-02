# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this is

Personal academic homepage for Qitong Wang (postdoc at Harvard University), hosted at [qtwang.github.io](https://qtwang.github.io). Built with Jekyll using the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme (`remote_theme: mmistakes/minimal-mistakes@4.23.0`).

**Note:** We are now working on refactoring this into a new modern minimalist version.

## Local development

```bash
# Install dependencies (requires Ruby/Bundler)
bundle install

# Serve locally with live reload
bundle exec jekyll serve

# Build without serving
bundle exec jekyll build
```

The site is served at `http://localhost:4000` by default. Changes to `_config.yml` require a server restart.

## Architecture

All actual content lives in `_pages/` — this site does not use Jekyll `_posts/`. Pages are included via `_config.yml`:

```yaml
include:
  - _pages
```

**Key files for content updates:**
- `_pages/home.md` — the main landing page (permalink: `/`). Contains publications, talks, services, and awards as Markdown tables.
- `_pages/kdd21-seanet.md` and `_pages/pvldb22-iedeal.md` — supplementary pages for specific papers.
- `_config.yml` — site metadata, author bio, avatar, social links, and theme skin.
- `assets/images/` — profile photo (`bio-photo.png`), logos, and OG image.

**Layout chain:** Pages use `layout: single` (defined in `_layouts/single.html`) which wraps content with the author sidebar. The `layout: single-comments` variant enables comments.

**Theme customization hooks** (currently mostly empty, available for future use):
- `_includes/head/custom.html` — inject into `<head>`
- `_includes/footer/custom.html` — inject into footer
- `_includes/author-profile-custom-links.html` — add links below the author sidebar

**Navigation:** `_data/navigation.yml` controls the masthead nav links. Currently not customized.

## Content conventions

- Publications are listed as a Markdown table in `_pages/home.md`, newest first.
- `<span>&dagger;</span>` marks corresponding authors.
- Paper supplementary pages link back from the publications table via relative URLs (e.g., `[supp](/kdd21-seanet)`).
- PDFs linked externally (arxiv, venue proceedings) — not hosted locally.
- `hidden: true` in front matter keeps pages out of auto-generated navigation.
