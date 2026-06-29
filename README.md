<div align="center">

# ✦ AI Catalog

### A map of artificial intelligence tools

Services, models, tools, and skills from across the internet — gathered into one interactive tree.

[![Live Demo](https://img.shields.io/badge/🚀_Open_Site-0b1124?style=for-the-badge&logo=github&logoColor=5ad1ff)](https://YOUR-USERNAME.github.io/ai-catalog/)
[![License: MIT](https://img.shields.io/badge/License-MIT-7c8bff?style=for-the-badge)](LICENSE)
[![Made with HTML](https://img.shields.io/badge/HTML-CSS-JS-46e0c8?style=for-the-badge)](#)

</div>

---

## 🌌 About

**AI Catalog** is a navigational map of the AI landscape, inspired by [OSINT Framework](https://osintframework.com/). It's an expandable tree with a cosmic look: the root sits on the left, branches fan out to the right toward categories, and the leaves link to individual services.

> One HTML file. No dependencies, no build step, no server. Opens in any browser.

---

## ✨ Features

- 🌳 **OSINT-style tree** — horizontal, branches expand on click with smooth animation
- 🔭 **Cosmic theme** — dark background, twinkling stars, neon branches across the spectrum
- 🔍 **Live search** — instant filtering across the entire tree
- 🎓 **Learning branch** — free courses straight from the model creators
- 📱 **Zero dependencies** — pure HTML/CSS/JS, works offline
- ♿ **Respects `prefers-reduced-motion`** — animations turn off for those who need it

---

## 🗂️ Catalog structure

| Branch | What's inside |
|:-------|:--------------|
| ✦ **Text & LLM** | Chat assistants, open-source models, writing, translation |
| ❖ **Images** | Generation, editing, upscaling |
| ♪ **Audio & Voice** | TTS, STT, music, voice agents |
| ▷ **Video** | Generation, avatars, editing |
| ⟨⟩ **Code & Dev** | IDE assistants, agentic tools, no-code |
| ⚙ **Agents & Automation** | Automation, frameworks, protocols |
| ◈ **Data & Search** | AI search, vector databases, RAG |
| ⬡ **API & Infrastructure** | Model hosting, inference providers |
| ✸ **Free Learning** | Courses from AI creators and platforms |

---

## 🚀 Getting started

### Online
Just open 👉 **[YOUR-USERNAME.github.io/ai-catalog](https://YOUR-USERNAME.github.io/ai-catalog/)**

### Local
```bash
git clone https://github.com/YOUR-USERNAME/ai-catalog.git
cd ai-catalog
# open index.html in your browser — that's it
```

---

## 🛠️ Adding your own tool

All data lives in the `DATA` array inside `index.html`. Each tool is a `['Name', 'url']` pair:

```javascript
{name:'Chat assistants', items:[
  ['ChatGPT','https://chatgpt.com'],
  ['Claude','https://claude.ai'],
  ['Your service','https://example.com'],   // ← add it here
]}
```

Save the file — the tree rebuilds itself.

---


## 📄 License

[MIT](LICENSE) — use it freely.

<div align="center">

---

Made with ❤️ for everyone navigating the world of AI

⭐ Star the repo if the catalog helped you

</div>
