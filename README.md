# 🌍 Hello, World! — in 344 Languages

> 用 **344 种语言**，向世界说一声「你好」。
> One page, hundreds of ways to say **Hello, World!**

**Live demo:** https://szrd2026.github.io/hello-world-multilingual/

![preview](assets/preview.svg)

![languages](https://img.shields.io/badge/languages-344-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue)
![dependencies](https://img.shields.io/badge/dependencies-0-orange)

---

## ✨ Features

- 🌐 **344 greetings** — from Abaza, Abkhaz and Afrikaans to Yoruba, Zulu… and even Ahom script and ancient Greek
- 🎞 **Animated hero** — cycles through the greetings with a smooth blur-fade, pause / shuffle / copy buttons
- 🔍 **Instant search** — filter by language name, greeting, romanization or language code
- 📋 **One-click copy** — click any card to copy its greeting to your clipboard
- ✍️ **Romanizations** — pronunciation hints for non-Latin scripts (e.g. 你好 → *nǐ hǎo*)
- 🪶 **Zero dependencies** — pure vanilla HTML / CSS / JS, no build step, one small `data.js`
- 🌌 **Aurora dark theme** — responsive, respects `prefers-reduced-motion`; `/` focuses search

## 🚀 Run locally

Just open `index.html` in your browser — that's it. Or serve it:

```bash
python -m http.server 8000
# → http://localhost:8000
```

## 🗂 Project structure

```
hello-world-multilingual/
├── index.html   # the page (UI + logic)
├── data.js      # 344 greetings: [{ n: name, g: greeting, r?: romanization, c: language code }]
└── LICENSE      # MIT
```

## ➕ Add or fix a greeting

Edit `data.js` and add an entry, then open a PR:

```js
{"n":"Klingon","g":"nuqneH","r":"nuqneH","c":"tlh"},
```

Corrections to existing greetings are very welcome — especially from native speakers!

## 📚 Sources & accuracy

Greetings were collected from [Wiktionary](https://en.wiktionary.org/wiki/hello) (via the
[kaikki.org](https://kaikki.org) machine-readable extract) and cross-checked/completed with
Google Translate. Some regional and minority-language greetings vary by dialect and context,
and machine-translated entries may not be perfect — if you spot an error, please open an issue
or PR and it will be fixed. 🙏

## 中文说明

一个单页小网站：用 344 种语言展示「你好」的写法。打开 `index.html` 即可使用；
输入框可实时搜索语言或问候语；点击卡片一键复制。全部零依赖，欢迎通过 PR 增补或纠错。

## 📄 License

[MIT](LICENSE) © 2026 [szrd2026](https://github.com/szrd2026)