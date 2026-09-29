# 🔐 Password Generator

> Generate strong, secure passwords instantly — with custom length, character types, and a live strength meter.

<p align="center">
  <a href="https://amiralikop90.github.io/Password-Generator/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Online-success?style=for-the-badge" alt="Live Demo">
  </a>
  <img src="https://img.shields.io/badge/HTML5-Single_File-orange?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/Zero-Dependencies-brightgreen?style=for-the-badge" alt="Zero Dependencies">
</p>

---

## 📖 About

**Password Generator** is a sleek, single-file web tool that creates strong, cryptographically secure passwords right in your browser. It uses the **Web Crypto API** — the most secure way to generate random numbers — and never sends your passwords to any server.

Whether you're signing up for a new account, updating weak passwords, or just need a strong password on the fly, this tool gets it done in one click.

---

## ✨ Features

- 🔐 **Cryptographically secure** — uses Web Crypto API (`crypto.getRandomValues`)
- 📏 **Custom length** — from 4 to 64 characters via slider
- 🔤 **Character types** — lowercase, uppercase, numbers, symbols
- 🚫 **Exclude similar characters** — removes `i`, `l`, `1`, `L`, `o`, `0`, `O`
- 📊 **Live strength meter** — weak, medium, strong
- 📋 **One-click copy** to clipboard
- 🔄 **Regenerate** with any setting change
- 🌐 **Trilingual interface** — Persian (فارسی), English, Chinese (中文)
- 🌙 **Dual themes** — Matte Black and Cloud White
- 💾 **Persistent preferences** — theme and language saved in `localStorage`
- 📱 **Fully responsive** — mobile, tablet, and desktop
- ♿ **Accessible** — ARIA labels, semantic HTML
- 🔍 **SEO-optimized** — meta tags, Open Graph, Twitter Cards, JSON-LD, hreflang
- ⚡ **Zero dependencies** — one HTML file, nothing else
- 🚀 **GitHub Pages ready** — deploy in under a minute

---

## 🚀 Live Demo

👉 **[https://amiralikop90.github.io/Password-Generator/](https://amiralikop90.github.io/Password-Generator/)**

---

## 🛠️ How to Use

1. Open the live demo
2. Choose the **length** with the slider (4–64)
3. Toggle character types: **lowercase**, **uppercase**, **numbers**, **symbols**
4. Optionally enable **Exclude Similar** to remove confusing characters
5. The password is generated automatically — click **📋 Copy** to use it
6. Click **🔄 Generate Password** to get a new one

---

## 🔒 Security

- ✅ **Web Crypto API** — the browser's most secure random number generator
- ✅ **No server** — everything runs in your browser
- ✅ **No tracking** — no analytics, no cookies, no logs
- ✅ **No storage** — passwords are never saved anywhere
- ✅ **Open source** — inspect the code yourself

---

## 📦 Deploy on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose **Branch:** `main` and **Folder:** `/ (root)`
5. Click **Save** — your site will be live at:
https://amiralikop90.github.io/Password-Generator/

text

---

## 🌍 Supported Languages

| Language | Code | Direction |
|----------|------|-----------|
| 🇮🇷 Persian | `fa` | RTL |
| 🇬🇧 English | `en` | LTR |
| 🇨🇳 Chinese | `zh` | LTR |

Language can be switched from the top bar — your choice is remembered across visits via `localStorage`.

---

## 🎨 Themes

- ☁️ **Cloud White** — soft, light, airy (default)
- 🖤 **Matte Black** — deep, flat, no glare

Toggle from the top-left button. Your preference is saved automatically.

---

## 📁 Project Structure
.
├── index.html # Entire app: HTML + CSS + JS in one file
├── robots.txt # Search engine crawler rules
├── sitemap.xml # URL list for search engines
├── LICENSE # MIT License
└── README.md # This file

text

> The entire application lives inside a **single `index.html`** — no build tools, no bundlers, no `node_modules`.

---

## 🧰 Tech Stack

- **HTML5** — semantic, accessible markup
- **CSS3** — custom properties for theming, no frameworks
- **JavaScript (Vanilla)** — no frameworks, no libraries
- **Web Crypto API** — for cryptographically secure random generation
- **GitHub Pages** — free static hosting

---

## 🔍 SEO Features

This project ships with production-grade SEO out of the box:

- ✅ Optimized `<title>` and `<meta description>`
- ✅ `hreflang` tags for multilingual content
- ✅ Open Graph (Facebook, LinkedIn, Telegram)
- ✅ Twitter Card (`summary_large_image`)
- ✅ JSON-LD structured data (`WebApplication` schema)
- ✅ Canonical URL
- ✅ `robots.txt` and `sitemap.xml`
- ✅ Google Search Console verified
- ✅ Semantic headings
- ✅ ARIA labels for accessibility

---

## 💡 Password Tips

- 📏 **Use at least 12 characters** for most accounts
- 🔐 **Use 16+ characters** for important accounts (email, banking)
- 🔤 **Mix character types** — lowercase, uppercase, numbers, symbols
- 🎲 **Use a unique password** for each account
- 🔑 **Use a password manager** to store them securely
- 🔄 **Change passwords** if a service reports a breach

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features, additional languages, or UI improvements:

1. Fork the repository
2. Create your branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 🔮 Planned Features

- 🎯 **Passphrase generator** — memorable word-based passwords
- 📊 **Entropy calculation** — more detailed strength analysis
- 📜 **Password history** — recently generated (session only)
- 🚫 **Custom excluded characters** — your own blacklist
- 📱 **PWA support** — install as a mobile app
- 🌐 **More languages** — Arabic, Russian, Spanish, German, French
- 🎨 **Preset templates** — bank, email, social media profiles
- 📄 **Export as text file**

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

See the [LICENSE](LICENSE) file for details.

For more information, visit the license page:
👉 **[https://psoa.ir/licens.html](https://psoa.ir/licens.html)**

---

## 👤 Author

**Amirali Kamani**

- 🌐 Website: [psoa.ir](https://psoa.ir)
- 💻 GitHub: [@Amiralikop90](https://github.com/Amiralikop90)
- 📜 License page: [psoa.ir/licens.html](https://psoa.ir/licens.html)

---

<p align="center">
  Made with ❤️ — because strong passwords should be one click away.
</p>
