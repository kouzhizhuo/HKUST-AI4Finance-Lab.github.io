# HKUST-AI4Finance-Lab Website

This repository contains the Hugo Blox website for HKUST-AI4Finance-Lab.

## Update Content

- Homepage research directions: `content/_index.md`
- People profiles: `content/authors/<slug>/_index.md`
- Publications and benchmark projects: `content/publication/<slug>/index.md`
- Site settings and theme colors: `config/_default/params.yaml` and `data/themes/hkust.toml`

## Local Development

Install Hugo Extended and then run:

```bash
hugo server
```

GitHub Actions builds and deploys the site automatically on pushes to `main`.
