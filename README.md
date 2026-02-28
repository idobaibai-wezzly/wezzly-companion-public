# Wezzly Companion

**The AI companion that actually sees your screen.**

[![Version](https://img.shields.io/badge/version-0.1.0-blue.svg)](https://github.com/idobaibai-wezzly/wezzly-companion-public/releases)
[![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon-black.svg)](https://github.com/idobaibai-wezzly/wezzly-companion-public/releases)
[![Windows](https://img.shields.io/badge/Windows-x64-0078D6.svg)](https://github.com/idobaibai-wezzly/wezzly-companion-public/releases)
[![License](https://img.shields.io/badge/license-Proprietary-red.svg)](#license)
[![Twitter Follow](https://img.shields.io/twitter/follow/WezzlyHQ?style=social)](https://x.com/WezzlyHQ)

<p align="center">
  <img src="assets/wezzly.svg" alt="Wezzly Companion" width="250">
</p>

## 🎬 Demo

[![Watch Wezzly in Action](https://img.youtube.com/vi/ya1Kz_iAraE/maxresdefault.jpg)](https://youtu.be/ya1Kz_iAraE)

**👆 Click to watch the demo video**

---

> 🌐 **[Visit wezzly.com →](https://wezzly.com)**
>
> 𝕏 **[Follow @WezzlyHQ →](https://x.com/WezzlyHQ)**
>
> ✉️ **[Contact →](mailto:idobaiba@gmail.com)**

---

## Why Wezzly?

Every AI assistant is **blind** — you have to describe what you're looking at, copy-paste text, upload screenshots.

**Wezzly can see.**

It watches your screen in real-time, understands what you're doing, and helps without the friction.

| Traditional AI | Wezzly Companion |
|----------------|------------------|
| "Paste the error message" | *sees your screen* "Line 47 has a typo" |
| "Describe what you're looking at" | *already watching* "That chart shows a downtrend" |
| "Upload a screenshot" | *sees it live* "I see you're on Twitter, want me to help?" |
| Can't watch videos | *watches with you* "At 2:34 he explains the key part" |

**No copy-paste. No uploads. It just sees.**

---

## ✨ Features

### 👁️ Vision & Awareness
- 🖥️ **Real-Time Screen Vision** — Continuous screenshots every 1-2 seconds. Sees exactly what you see.
- 🎬 **Video Co-Watching** — Watch YouTube, tutorials, movies together. Auto-activates video mode. Get real-time commentary and summaries.
- 📊 **Chart & Financial Analysis** — Analyze stock charts, crypto graphs, identify patterns, support/resistance, give trading opinions.
- 🐛 **Visual Code Debugging** — Sees your code errors on screen and helps fix them instantly.

### 🤖 Agent & Automation
- ⚡ **14+ Native Commands** — Click, type, scroll, run shell commands, open apps, manage files — all powered by Rust.
- 🔄 **Multi-Step Agent Loops** — Up to 10 iterations of autonomous task completion.
- ✅ **Smart Confirmations** — Safety dialogs for dangerous actions (delete, sudo, etc.).
- 🖱️ **Full Desktop Control** — Mouse clicks, keyboard input, scrolling, window management.

### 🧠 Multi-AI & Flexibility
- 🔌 **8+ AI Providers** — OpenAI, Anthropic Claude, Google Gemini, Grok, DeepSeek, Kimi, Ollama, and custom endpoints.
- 🔀 **Seamless Switching** — Change AI providers on the fly without losing context.
- 🏠 **Local Models** — Run completely offline with Ollama support.
- 🛠️ **Custom Endpoints** — Connect any OpenAI-compatible API.

### 💬 Companion Experience
- 🫧 **Always-On Floating Companion** — Lives on your desktop, not hidden in a chat window.
- 🎭 **Self-Aware Personality** — Witty, playful, slightly cocky. Knows it's an AI and owns it.
- 🗣️ **Ambient Voice Lines** — Random comments based on mood, position, and what you're doing.
- 🎮 **Interactive Wezzly** — Drag, shake, poke. Wezzly reacts to everything.
- 👀 **Position Awareness** — Knows when it's moved, minimized, or ignored.

### 🔒 Privacy & Security
- 💾 **100% Local** — All data stays on your machine. Zero cloud storage.
- 🔐 **Secure Keychain Storage** — API keys stored in macOS Keychain / Windows Credential Manager.
- 🚫 **No Telemetry** — We don't collect analytics, usage data, or anything else.
- 🎯 **Direct to Provider** — Screen data goes straight to your chosen AI using YOUR API key.

### 🖥️ Cross-Platform
- 🍎 **macOS** — Native Apple Silicon support, signed and notarized.
- 🪟 **Windows** — Full x64 support with native integration.
- 🐧 **Linux** — Works with gnome-screenshot or scrot.

---

## 📥 Download

### macOS (Apple Silicon)
1. Download `Wezzly Companion_0.1.0_aarch64.dmg` from [**Releases**](https://github.com/idobaibai-wezzly/wezzly-companion-public/releases)
2. Open the DMG and drag Wezzly Companion to Applications
3. Launch and configure your AI provider

✅ **macOS build is signed and notarized**

### Windows (x64)
1. Download `Wezzly Companion_0.1.0_x64-setup.exe` from [**Releases**](https://github.com/idobaibai-wezzly/wezzly-companion-public/releases)
2. Run the installer (you may see a SmartScreen warning — click "More info" → "Run anyway")
3. Launch and configure your AI provider

⚠️ **Windows build is unsigned** — SmartScreen warning is expected. Code signing coming soon.

---

## 🚀 Getting Started

1. Download and install from [**Releases**](https://github.com/idobaibai-wezzly/wezzly-companion-public/releases)
2. Launch Wezzly Companion
3. Click the ⚙️ settings icon
4. Select your AI provider (OpenAI, Anthropic, etc.)
5. Enter your API key
6. Start chatting!

**Pro tip:** Enable Screen Awareness in settings to let Wezzly see what you're working on.

### 🔐 Your Privacy, Guaranteed

- **100% Local** — Wezzly runs entirely on your machine. No servers, no cloud, no tracking.
- **Direct to Provider** — Screen data goes straight to your chosen AI (OpenAI, Anthropic, etc.) using YOUR API key. We never see it.
- **Secure Storage** — API keys stored in your system's native keychain (macOS Keychain / Windows Credential Manager), not in plain text.
- **No Telemetry** — We don't collect analytics, usage data, or anything else. Zero.
- **You're in Control** — Screen capture only runs when you enable it. Turn it off anytime.

---

## 🧠 Supported AI Providers

| Provider | Models | Vision Support |
|----------|--------|----------------|
| OpenAI | GPT-4o, GPT-4o-mini | ✅ |
| Anthropic | Claude 3.5 Sonnet, Claude 3 Opus | ✅ |
| Google | Gemini 1.5 / 2.0 | ✅ |
| Grok | Grok-2 | ✅ |
| DeepSeek | DeepSeek Chat | ✅ |
| Ollama | Local models | Varies |
| Custom | Any OpenAI-compatible API | Varies |

---

## 🔓 Open Source Pledge

Wezzly Companion is currently **source-available** to protect early development.

**We pledge to fully open-source the codebase when we reach 10,000 users.**

⭐ **Star this repo and help us get there!**

*Why not now? We're a solo developer building something meaningful. We believe in open source and will get there — with your help.*

---

## 🛠️ Tech Stack

Built with modern, performant technologies:

- [Tauri](https://tauri.app/) — Lightweight desktop framework
- [Rust](https://www.rust-lang.org/) — Fast, safe backend
- [TypeScript](https://www.typescriptlang.org/) — Type-safe frontend
- [Vite](https://vitejs.dev/) — Lightning-fast builds

---

## 💬 Community

- 🐛 **Bug reports:** [Open an issue](https://github.com/idobaibai-wezzly/wezzly-companion-public/issues)
- 💡 **Feature requests:** [Open an issue](https://github.com/idobaibai-wezzly/wezzly-companion-public/issues)
- 💬 **Discussions:** [Join the conversation](https://github.com/idobaibai-wezzly/wezzly-companion-public/discussions)
- 📧 **Contact:** [idobaiba@gmail.com](mailto:idobaiba@gmail.com)

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=idobaibai-wezzly/wezzly-companion-public&type=Date)](https://star-history.com/#idobaibai-wezzly/wezzly-companion-public&Date)

---

## 📄 License

Proprietary — © 2026 Ido Ben Aroya
