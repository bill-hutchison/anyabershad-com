# Anya Bershad — Academic Website

Built with [al-folio](https://github.com/alshedivat/al-folio), a Jekyll theme for academics.

---

## Setup (one-time)

### 1. Fork al-folio
Go to https://github.com/alshedivat/al-folio and click **Fork**.
Rename the repo to `anya-site` (or whatever you'd like).

### 2. Copy these files into your fork
Replace / add the following files from this folder:

| File | Goes to |
|------|---------|
| `_config.yml` | root of repo |
| `_pages/about.md` | `_pages/about.md` |
| `_pages/publications.md` | `_pages/publications.md` |
| `_pages/cv.md` | `_pages/cv.md` |
| `_bibliography/papers.bib` | `_bibliography/papers.bib` |
| `_news/announcements.md` | `_news/announcements.md` |

### 3. Update _config.yml
Open `_config.yml` and set:
```yaml
url: https://YOUR_GITHUB_USERNAME.github.io
baseurl: /anya-site   # or whatever your repo is named
```

### 4. Add a photo
Place a headshot at:
```
assets/img/prof_pic.jpg
```
(Square crop recommended, at least 400×400px)

### 5. Enable GitHub Pages
- Go to your repo → **Settings** → **Pages**
- Source: **GitHub Actions**
- al-folio uses a built-in workflow — it will deploy automatically on every push.

### 6. Your site goes live at:
```
https://YOUR_GITHUB_USERNAME.github.io/anya-site/
```

---

## Keeping it updated

### Add a news item
Edit `_news/announcements.md` and add a new block at the top:
```markdown
---
layout: post
date: 2026-06-01
inline: true
---
**New paper** — *Title here* published in **Journal Name**.
```

### Add a publication
Edit `_bibliography/papers.bib` and add a new BibTeX entry.
Mark key papers with `selected = {true}` to feature them on the homepage.

### Update your bio
Edit `_pages/about.md`.

---

## al-folio docs
Full documentation: https://github.com/alshedivat/al-folio
