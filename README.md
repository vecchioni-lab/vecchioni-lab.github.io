# Vecchioni Lab website

A modular Quarto website for `https://vecchioni-lab.github.io`.

## First local preview

1. Install Quarto and VS Code.
2. Open this folder in VS Code.
3. Open a terminal in VS Code.
4. Run:

```bash
quarto preview
```

## Render the publishable site

```bash
quarto render
```

Quarto writes the finished website to `docs/`.

## Research-page editing

Each research area has its own folder under `research/`. The page title, subtitle, card summary, image, and order are controlled by the YAML metadata at the top of that folder's `index.qmd`.

Example:

```yaml
---
title: "DNA Crystal Engineering"
subtitle: "Programming periodic matter from nucleic acids"
description: "Card summary here."
image: "../../assets/images/research/dna-crystals.jpg"
order: 1
---
```

## Replace images

Replace the placeholder SVG files in `assets/images/` with your own JPG, PNG, WebP, or SVG files, then update the `image:` path in the relevant page metadata.
