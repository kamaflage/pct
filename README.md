# Parallel Corpus Translator

A portable AI-powered translation corpus builder and prompt generator. Works with any language pair — built for Plautdietsch.

**[Live App →](https://kamaflage.github.io/parallel-corpus-translator/)**

---

## What It Is

Parallel Corpus Translator helps you build a verified bilingual sentence corpus and use it to generate structured translation prompts for any LLM — Claude, ChatGPT, Gemini, or any other. No API keys. No subscriptions. No data leaves your device.

---

## Features

- **Builder** — load HTML article pairs, auto-align paragraphs by JW paragraph numbers, push to corpus
- **Corpus** — manage and search your verified parallel sentence pairs
- **Phrases** — build a phrase and terminology library auto-extracted from your corpus
- **Matcher** — visually link words and phrases between language pairs
- **Translator** — generate structured prompts from your corpus, paste into any LLM, review and approve segments
- **Queue** — manage completed translations pending review
- **Multi-language profiles** — separate settings for different language pairs
- **PWA** — installable on Android and iOS, works offline
- **Zero dependencies** — one HTML file, no build step, no backend

---

## How to Use

1. Open the [live app](https://kamaflage.github.io/parallel-corpus-translator/)
2. Complete the setup wizard — set your source and target language names
3. In **Builder**: load matching HTML article pairs (one source, one target language)
4. Review paragraph alignment and push pairs to **Corpus**
5. In **Phrases**: extract terminology from your corpus or add manually
6. In **Translator**: paste source text → Build Prompt → copy into any LLM
7. Paste the LLM response back → review segments → Save to Queue

---

## Installing as an App

**Android (Chrome or Brave):** Open the live URL → tap the install prompt or browser menu → **Add to Home Screen**

**iOS (Safari):** Open the live URL → tap Share → **Add to Home Screen**

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | The full app — single file, zero dependencies |
| `manifest.json` | PWA manifest for installability |
| `sw.js` | Service worker for offline support |
| `icon-192.png` | App icon (192×192) |
| `icon-512.png` | App icon (512×512) |

---

## Self-Hosting

No build step required. Clone or download the repo and open `index.html` in any browser, or serve from any static host.

---

## Author

Built by [Chris R](https://github.com/kamaflage) as part of the ADRIAN framework.

## License

MIT — use it, fork it, build on it.
