# Hi! I'm Aneesh 👋

Computer science student.

I enjoy building developer tools, backend infrastructure, and systems software.

If I don't know how something works, there's a 99.9% chance I'll spend 3 days building a broken version of it from scratch just to find out.

> currently trying to replace *"it works on my machine"* with *"it works everywhere"* (or at least until Nix breaks).

---

# 🛠️ featured projects

## 🪵 Loom
A distributed log aggregation platform.

Featuring real-time ingestion, semantic search, vector embeddings, and AI-assisted querying.

> Making production logs slightly less terrifying when production inevitably catches fire at 2 AM.

---

## 🌉 ByteBridge
A secure peer-to-peer file transfer utility written in **Go**.

Designed to make sending files between computers simple—whether they're on the same Wi-Fi or across the internet.

Features:
- Direct LAN transfers & relay-based remote transfers
- Cross-platform binaries & secure session IDs
- Planned end-to-end encryption and NAT traversal (STUN/TURN)

> Moving bytes from A → B shouldn't require uploading them to someone else's cloud bucket.

---

### 🎞️ FrameShift
A fast, zero-dependency CLI tool for batch video conversion built with **Go + FFmpeg**.

Features:
- Instant execution via Nix (`nix run github:Aneeshie/video-converter`)
- Single-file and batch directory processing
- Integrated natively into `nara-cli`

> *Because remembering raw `ffmpeg` flags is an unnecessary cognitive load.*

---

## ❄️ `.dotfiles` & `nara-cli`
A fully declarative, reproducible macOS system architecture engineered with **Nix Flakes**, `nix-darwin`, and `home-manager`.

Features:
- **`nara-cli`**: A bespoke CLI workflow engine written in **Go** to handle system rebuilds (`nara rebuild`), health diagnostics (`nara doctor`), Nix store optimization (`nara clean`), and ephemeral package execution (`nara run`).
- **Zero Imperative Drift**: Rebuilding enforces exact system state, GUI apps, and shell aliases.
- **Hermetic Dev Environments**: Pre-configured `direnv` + `nix-direnv` for instant, zero-pollution shell environments.

> Because reinstalling macOS shouldn't mean spending 6 hours running `brew install` and forgetting your `.zshrc`.

---

## 🖥️ Nara
A keyboard-first terminal emulator built with **Rust + Tauri**.

Currently implementing:
- Multi-tab support & split panes
- PTY management & GPU-accelerated rendering
- Keyboard-driven workflow for vim-addicts

> Learning how terminals actually work instead of treating them like black magic and `/dev/null`.

---

## 📡 WhisperNet
An offline-first peer-to-peer mesh communication platform.

Built for situations where traditional communication fails (or your Wi-Fi router gets hit by lightning).

Features:
- Local Wi-Fi mesh networking & WebRTC P2P communication
- QR-based offline synchronization & cryptographically signed messages
- Stealth mode & Progressive Web App (PWA) support

> Because communication shouldn't depend on one cloud server staying alive in Virginia.

---

## 🛒 Ecommerce Backend
A production-style backend built in **Go**.

Featuring:
- Authentication & Refresh Token flows
- PostgreSQL, Docker, Clean Architecture & Repository Pattern

> Built to learn how real backend systems are designed before someone forces me to maintain a monolith.

---

# 🌱 currently learning

🦀 **Rust** *(learning to fight the borrow checker and win)*

🐹 **Go** *(goroutines go brrr)*

⚙️ **Operating Systems & Kernel Magic**

🌐 **Distributed Systems & Consensus Algorithms**

💾 **Database Internals & B-Trees**

🖥️ **Terminal Internals & PTY Pseudo-terminals**

❄️ **Nix Flakes & NixOS** *(graduating from Nix enjoyer™ to Nix wizard)*

---

# 🧰 toolbox

### Languages
Go • Rust • TypeScript • SQL • Nix

### Backend & Storage
PostgreSQL • Docker • REST • gRPC • Redis

### Systems & DevOps
Nix Flakes • nix-darwin • Home Manager • Linux • Git

### Frontend
React • Tauri

### Daily Drivers
macOS / Linux • Nix • Neovim • Ghostty • AeroSpace

---

---
# 📊 Activity & Stats

<div align="center">

  <!-- Contribution Streak -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Aneeshie&theme=gruvbox&hide_border=true" alt="Aneeshie Streak Stats" height="150" />
  
  <!-- Overall Stats (Commits, PRs, Issues, Stars) -->
  <img src="https://github-readme-stats.vercel.app/api?username=Aneeshie&show_icons=true&theme=gruvbox&hide_border=true&count_private=true" alt="Aneeshie GitHub Stats" height="150" />

</div>

<br />

<div align="center">

  <!-- Most Used Languages Card -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aneeshie&layout=compact&theme=gruvbox&hide_border=true&langs_count=6" alt="Top Languages" height="150" />

</div>

<div align="center">

*"There are two hard things in computer science: cache invalidation, naming things, and configuring Nix Flakes without crying."*

</div>
