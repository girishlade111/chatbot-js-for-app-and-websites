# Chatbot JS for Apps and Websites

A lightweight, dependency-free JavaScript chatbot widget you can drop into any app or website. A floating toggler button opens a clean, modern chat window with animated message bubbles, typing-style canned responses, and a mobile-responsive layout — all in a single self-contained HTML file.

## Features

- **Floating chat widget** — circular toggler button fixed to the bottom-right corner that opens/closes the chat panel.
- **Modern chat UI** — Poppins typography, Material Symbols icons, gradient header, and styled incoming/outgoing message bubbles.
- **Canned bot replies** — a small built-in response map answers common prompts (greetings, help requests, etc.) with a natural typing delay.
- **Auto-resizing input** — the message textarea grows with your text and resets after sending.
- **Keyboard friendly** — press Enter to send, Shift+Enter for a new line.
- **Fully responsive** — adapts to small screens; on mobile the panel goes full-width.
- **Zero dependencies, zero build step** — no npm, no bundler, no framework. Just open the HTML file in a browser.

## Tech Stack

- HTML5
- CSS3 (custom styles, flexbox layout, responsive media queries)
- Vanilla JavaScript (DOM event handling, message rendering)
- Google Fonts (Poppins) + Material Symbols icons via CDN

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/girishlade111/chatbot-js-for-app-and-websites.git
   cd chatbot-js-for-app-and-websites
   ```
2. Open `index.html` in any browser — that's it, the chatbot is live.
3. To embed it in your own site, copy the contents of `index.html` (or the `chatbot` markup, styles, and script blocks) into your page.

## Project Structure

```
chatbot-js-for-app-and-websites/
├── index.html                           # The chatbot widget demo (entry point for GitHub Pages)
├── chatbot js for app and websites.html # Original single-file demo
├── LICENSE
└── README.md
```

## Customizing Bot Replies

The demo's replies live in the script section of `index.html` in a responses object. Edit the keys/values there to teach the bot your own answers — no rebuild needed, just save and refresh.

## Deploy Notes

This is a plain static site. GitHub Pages serves it from the repository root (`main` branch, `/` path) — no build step required. Any static host (Cloudflare Pages, Netlify, Vercel) can deploy it by pointing at the repo root.

---

Built by Girish Lade — https://ladestack.in
