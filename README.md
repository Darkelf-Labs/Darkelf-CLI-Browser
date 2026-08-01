# Darkelf CLI  [![PyPI Downloads](https://static.pepy.tech/personalized-badge/darkelf-cli?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads)](https://pepy.tech/projects/darkelf-cli)

> A privacy-focused command-line web browser for the terminal.

Darkelf CLI is a lightweight terminal web browser written in Python that provides a fast, keyboard-driven browsing experience. It features DuckDuckGo search, multiple browsing modes, page rendering, tab management, history, Markdown rendering, customizable themes, and privacy-oriented networking features—all without requiring a graphical interface.

---

## Features

* 🌐 Terminal-based web browser
* 🔍 DuckDuckGo HTML search
* 🔗 Open any HTTP or HTTPS URL
* 📄 Readable page rendering
* 🔖 Link extraction and navigation
* 📚 Browsing history
* 📑 Multi-tab browsing
* 🎨 Multiple built-in themes
* 🔎 Search within pages
* 📝 Markdown page rendering
* 📤 Export links to text files
* 📂 Heading navigation
* 🛡️ Stealth request mode
* 🔒 Session isolation
* 🎲 Randomized request headers
* 🚫 Basic tracker detection
* ⚡ Lightweight with minimal dependencies

---

# Installation

Install from PyPI:

```bash
pip install darkelf-cli
```
---

# Quick Start

Launch Darkelf CLI:

```bash
darkelf-cli
```

Start directly in browser mode:

```bash
darkelf-cli --browser
```

Display help:

```bash
darkelf-cli --help
```

---

# Browser Controls

| Key   | Action                  |
| ----- | ----------------------- |
| ↑ / ↓ | Scroll page             |
| W / S | Scroll page             |
| J / K | Vim-style scrolling     |
| O     | Open link               |
| U     | Open URL                |
| B     | Back                    |
| H     | View history            |
| T     | Manage tabs             |
| t     | Change theme            |
| F     | Search DuckDuckGo       |
| /     | Search within page      |
| N     | Next search match       |
| G     | Jump to heading         |
| M     | Render page as Markdown |
| L     | List links              |
| E     | Export links            |
| ?     | Help                    |
| Q     | Quit                    |

---

# CLI Mode

Commands:

```text
search <query>
open <url>
debug <query>
stealth
help
exit
```

Example:

```text
darkelf> search python requests
darkelf> open https://python.org
```

---

# Themes

Darkelf CLI includes several built-in themes.

* Blue
* Dark
* Hacker
* Light

Themes can be changed at runtime while browsing.

---

# Privacy Features

Darkelf CLI includes several privacy-oriented capabilities designed to reduce unnecessary information leakage during normal browsing.

* Randomized User-Agent headers
* Randomized Accept-Language headers
* Configurable request delays
* Session isolation
* Optional stealth mode
* Tracker detection and blocking
* Minimal logging outside debug mode

These features are intended to help reduce browser fingerprinting and improve privacy while browsing.

---

# Requirements

* Python 3.11 or newer

Dependencies:

* requests
* beautifulsoup4
* rich

---

# Project Layout

```text
darkelf-cli/
├── darkelf_cli.py
├── pyproject.toml
├── README.md
├── LICENSE.md
└── .gitignore
```

---

# License

Licensed under the **GNU Lesser General Public License v3.0 (LGPL-3.0-or-later)**.

See the LICENSE file for complete licensing information.

---

# Disclaimer

Darkelf CLI is provided for educational, research, privacy, and legitimate Open Source Intelligence (OSINT) purposes.

Users are solely responsible for ensuring that their use of this software complies with applicable laws, regulations, export controls, and the terms of service of any websites or services they access.

---

# Contributing

Contributions are welcome.

Bug reports, feature requests, documentation improvements, and pull requests are appreciated.

If submitting a bug report, please include:

* Operating system
* Python version
* Darkelf CLI version
* Steps to reproduce
* Expected behavior
* Actual behavior

---

# Roadmap

Future development may include:

* Bookmark management
* Download manager
* Cookie management
* Reader mode
* Additional search engines
* Plugin architecture
* Configuration file support
* Improved HTML rendering
* Accessibility enhancements
* Performance optimizations

---

# Author

**Dr. Kevin Moore**

---

## Support

If you find Darkelf CLI useful:

* ⭐ Star the repository
* 🐞 Report bugs
* 💡 Suggest new features
* 🤝 Contribute improvements

---

**Darkelf CLI** — A fast, privacy-focused browser built for the terminal.
