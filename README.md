# stefan-coder

Personal website and blog for [Stefan Popov](https://github.com/popovstefan).

Built with [Hugo](https://gohugo.io/) and the [hugo-coder](https://github.com/luizdepra/hugo-coder) theme. Deployed automatically to GitHub Pages on every push to `main`.

**Live site:** https://popovstefan.github.io/stefan-coder/

## Local development

Prerequisites: [Hugo Extended](https://gohugo.io/installation/) (required for SCSS).

```bash
git submodule update --init --recursive
hugo server -D
```

Open http://localhost:1313/stefan-coder/

## Publishing a blog post

Create a new file in `content/posts/` or scaffold one:

```bash
hugo new posts/my-post-title.md
```

Set `draft = false` in the front matter when ready to publish, then push to `main`.

## Deployment

GitHub Actions (`.github/workflows/hugo.yaml`) builds and deploys the site. Enable **Settings → Pages → Build and deployment → GitHub Actions** in the repository if not already configured.
