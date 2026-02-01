# Welcome to your documentation site

This repository powers your documentation at **[your-site].minimaldocs.com**. Edit the files here, push to GitHub, and your site updates automatically.

## How it works

```
Edit markdown → Push to GitHub → Site updates
```

Your docs are written in MDX (Markdown with components). The `docs.json` file controls your navigation and site settings.

## Quick start

### 1. Preview locally

```bash
npm i -g minimaldocs
minimaldocs dev
```

Open `http://localhost:3000` to see your docs.

### 2. Make your first edit

Try changing the title in `index.mdx`, save, and watch it update instantly.

### 3. Push to publish

```bash
git add .
git commit -m "Update docs"
git push
```

Your live site will update within seconds.

## Key files

| File | Purpose |
|------|---------|
| `docs.json` | Site name, navigation, colors, logo |
| `index.mdx` | Your homepage |
| `logo/` | Light and dark mode logos |

## Next steps

- [Customize your site](https://minimaldocs.com/docs/essentials/settings) — colors, logo, navigation
- [Write with MDX](https://minimaldocs.com/docs/essentials/markdown) — formatting, components, code blocks
- [Add API docs](https://minimaldocs.com/docs/api-reference) — auto-generate from OpenAPI specs

## Need help?

- [Documentation](https://minimaldocs.com/docs)
- [Email support](mailto:hello@minimaldocs.com)
