# stefan-coder

Personal website for [Stefan Popov](https://github.com/popovstefan).

Built with [Hugo](https://gohugo.io/) and the [hugo-coder](https://github.com/luizdepra/hugo-coder) theme. Deployed automatically to GitHub Pages on every push to `main`.

**Live site:** https://popovstefan.github.io/stefan-coder/

## Local development

Prerequisites: [Hugo Extended](https://gohugo.io/installation/) (required for SCSS).

```bash
git submodule update --init --recursive
hugo server -D
```

Open http://localhost:1313/stefan-coder/

The site is a landing page plus [About](content/about.md) and [Experience](content/experience.md).

## Deployment

GitHub Actions (`.github/workflows/hugo.yaml`) builds and deploys the site. Enable **Settings → Pages → Build and deployment → GitHub Actions** in the repository if not already configured.
