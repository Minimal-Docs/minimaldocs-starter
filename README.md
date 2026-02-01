<p align="center">
  <img src="images/icon.png" alt="MinimalDocs" width="120" height="120" />
</p>

<h1 align="center">Welcome to your documentation site</h1>

<p align="center">
  This repository powers your docs. Edit files here, push to GitHub, and your site updates automatically.
</p>

<p align="center">
  <a href="https://minimaldocs.com/docs"><strong>Documentation</strong></a> ·
  <a href="mailto:hello@minimaldocs.com"><strong>Support</strong></a>
</p>

---

## How it works

```
Edit markdown  →  Push to GitHub  →  Site updates
```

Your docs are written in **MDX** (Markdown with components). The `docs.json` file controls your navigation and site settings.

## Quick start

### 1. Preview locally

```bash
npm i -g minimaldocs
minimaldocs dev
```

Open [localhost:3000](http://localhost:3000) to see your docs.

### 2. Make your first edit

Open `index.mdx`, change the title, save — watch it update instantly.

### 3. Push to publish

```bash
git add .
git commit -m "Update docs"
git push
```

Your live site updates within seconds.

## Key files

| File | Purpose |
|------|---------|
| `docs.json` | Site name, navigation, colors, logo |
| `index.mdx` | Your homepage |
| `logo/` | Light and dark mode logos |
| `images/` | Screenshots and media |

## Next steps

📖 **[Customize your site](https://minimaldocs.com/docs/essentials/settings)** — colors, logo, navigation

✍️ **[Write with MDX](https://minimaldocs.com/docs/essentials/markdown)** — formatting, components, code blocks

🔌 **[Add API docs](https://minimaldocs.com/docs/api-reference)** — auto-generate from OpenAPI specs

---

<p align="center">
  <sub>Built with <a href="https://minimaldocs.com">MinimalDocs</a></sub>
</p>
