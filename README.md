# 🔍 Secret Search Engine

<p align="center">
  <img src="https://media.giphy.com/media/3o7TKtnuHOHHUjR38Y/giphy.gif" width="600" alt="Recon Animation"/>
</p>

Secret Search Engine is an advanced reconnaissance toolkit for bug bounty hunters and OSINT researchers. It consolidates powerful search queries (Google dorks) and platform integrations to help discover exposed assets, sensitive files, and potential vulnerabilities.

Built and improved by CyberTechAjju — inspired by the original project by gatiella.

---

## ✨ Key Features

- 100+ curated Google dorks across multiple categories
- Platform integrations: Google, GitHub, Shodan, Censys, crt.sh, Web Archive, Reddit, Pastebin, Yandex
- Subdomain discovery and asset enumeration
- Exposed file detection (.env, .git, backups, config files, databases)
- Vulnerability heuristics (phpinfo, open redirects, Struts RCE indicators, upload script checks)
- Secrets hunting (API keys, tokens, cloud credentials)
- OSINT gathering (LinkedIn, ThreatCrowd, OpenBugBounty, Reddit mentions)
- Query builder with tokens (site, inurl, ext, intitle, intext, -)
- Favorites & history with export/import support
- Keyboard shortcuts for faster workflow

---

## 🚀 Demo

<p align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="700" alt="Demo GIF"/>
</p>

---

## 📦 Installation

No runtime or external dependencies required — this is a static HTML toolkit.

1. Clone the repository:
   ```bash
   git clone https://github.com/cyberajju/Secret-Search-Engine.git
   cd Secret-Search-Engine
   ```
2. Open `index.html` in your browser.

Tip: Use a modern browser (Chrome, Firefox) for best UI/UX.

---

## 🎮 Usage

1. Enter target domain(s). Multiple targets can be comma-separated for batch mode.
2. Select the platform to search (Google, GitHub, Shodan, etc.).
3. Choose a dork category and click a query to launch searches in the selected platform.
4. Use the query builder to combine tokens and craft custom searches.
5. Save favorite dorks and export/import them for reuse.

---

## 🧰 Dorks

This project includes 100+ curated Google dorks organized by category to speed up reconnaissance.  
To keep the README readable, see the DORKS.md file (or the dorks section in the UI) for the complete list.

---

## 🖼️ Screenshots

<p align="center">
  <img src="https://media.giphy.com/media/26AHONQ79FdWZhAI0/giphy.gif" width="700" alt="UI Screenshot"/>
</p>

---

## 🏆 Credits

- Original inspiration: gatiella  
- Upgrades, UI/UX improvements, and maintenance: CyberTechAjju

---

## ⚡ Roadmap

- Add more dork categories (Cloud, IoT, APIs)
- Dark/light theme toggle
- Export results to CSV/JSON
- Integration with bug-bounty platforms

---

## 📜 License

MIT License — free to use, modify, and share. Please use the tool responsibly and ethically.

---

<p align="center">
  <b>✨ Keep learning, keep hacking — <a href="https://github.com/cyberajju">CyberTechAjju</a> ✨</b>
</p>