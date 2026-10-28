# Hi, I'm riagentic 👋

**Thirty years of engineering fundamentals. Since 2026, I build at agent speed and stay in control of what ships.**

📍 Europe · open to roles in **Zurich** (preferred) or **Dublin** · 📫 riagentic@proton.me

I've worked in IT for about 30 years, mostly on Linux and Java. In 2026 I changed how I build: AI agents now write most of my code, and my job is design, review and the gates that keep it honest. Everything on this profile was built that way, and each featured project has its own test suite.

What I build here: desktop apps on **[aio](https://github.com/riagentic/aio)**, my own full-stack TypeScript/Deno framework, plus **Rust** systems tools and **AI tooling** for coding agents and local LLMs.

I'm looking for engineering roles at strong AI, infrastructure and Web3 companies (Solana especially), where solid fundamentals and fluent use of agents both count.

---

## 🚀 Headline: a framework, plus 15 apps built on it

**[aio](https://github.com/riagentic/aio)** is my full-stack app framework. One `cell` is your server state, persistence, sync and UI, and it builds to browser, desktop (Electron), Android and a single binary. It has 2,700+ test files, its own linter (`aiol`), module-boundary and API-snapshot checks, and 121 version tags since Feb 2026.

**[aio-launcher](https://github.com/riagentic/aio-launcher)** proves aio runs real software. From one window it installs, updates and opens every app below, building each one from source on your machine. It checks for updates hourly and updates itself from GitHub releases on Linux, macOS and Windows.

| App | What it does |
| --- | --- |
| [cc](https://github.com/riagentic/cc) | Claude Control: runs Claude Code across many projects, with in-window approvals and local LLMs |
| [llama.master](https://github.com/riagentic/llama-master) | Gets, fits, runs and chats with llama.cpp models |
| [writy](https://github.com/riagentic/writy) | Documents, sheets and slides in one `.html` file |
| [protector](https://github.com/riagentic/protector) | Keeps your workstation from freezing (Rust daemon plus UI) |
| [machine](https://github.com/riagentic/machine) | Live hardware monitor (Rust/WASM parsers) |
| [netmap](https://github.com/riagentic/netmap) | Local network and internet path map |
| [fixable](https://github.com/riagentic/fixable) | Linux desktop health checks |
| [spacy](https://github.com/riagentic/spacy) | Shows where your disk space went |
| [mdview](https://github.com/riagentic/mdview) | Markdown viewer |
| [fjssm](https://github.com/riagentic/fjssm) | Fuzzy job-shop scheduling (a port of a 2002 MFC app) |
| [mushradar](https://github.com/riagentic/mushradar) | 3D mushroom forecast map of Czechia |
| [calcaio](https://github.com/riagentic/calcaio) | Scientific calculator that draws every result |
| [bsv](https://github.com/riagentic/bsv) | Bible Source Version reader (desktop and Android) |
| [ayd](https://github.com/riagentic/ayd) | Video downloader (yt-dlp) |
| [Space Invaders](https://github.com/riagentic/space-invaders) | Neon arcade game |
| amui | aio's own app manager |

## ⭐ Featured

| Project | What it is |
| --- | --- |
| **[gt](https://github.com/riagentic/gt)** | Globe Today puts world events on one 3D globe: news from 59 feeds, disasters, markets and prediction odds, plus optional local-AI briefs in 40 languages. It needs no keys and has no backend. |
| **[ricon](https://github.com/riagentic/ricon)** | A Rust terminal console with vertical tabs for working with Claude Code and OpenCode, built on ratatui and portable-pty. It has 184 unit tests and CI running fmt, clippy and tests. |
| **[cc](https://github.com/riagentic/cc)** | A desktop app that runs Claude Code across many projects side by side, with in-window tool approvals, session telemetry and local models (Ollama, LM Studio, llama.cpp) as a second engine. It has 589 test cases. |
| **[llama-master](https://github.com/riagentic/llama-master)** | A desktop app for llama.cpp: it gets a build, finds your models and works out what will actually fit in memory before running them. It has 465 test cases and 17 version tags. |
| **[rpx](https://github.com/riagentic/rpx)** | Zero-dependency, transport-agnostic RPC for Deno: a TypeScript interface is the contract, with swappable UDS, TCP, stdio and WebSocket transports. It has 50 test cases. |
| **[protector](https://github.com/riagentic/protector)** | A Linux freeze guard: a Rust daemon reads memory, swap and kernel PSI, scores process trees, and kills one runaway job only when the OS is about to lock up. |

---

## 🛠 Tech stack

- **Languages:** TypeScript, Rust, Java, C++, WebAssembly
- **Runtime and platforms:** Linux, Deno, Electron, Android, macOS and Windows
- **UI and graphics:** my own renderer in aio, Three.js and WebGL, ratatui (terminal UIs)
- **Data:** SQLite, WebSocket sync
- **AI:** Claude Code, llama.cpp, Ollama and LM Studio, agent tooling and local inference
- **Quality:** Deno test, cargo test and clippy, GitHub Actions, custom lint and architecture checks

---

## 🤖 How I work with AI agents

Agents write most of my code, and I say so openly. I own the design, the review and the quality gates. Each project carries its rules as code: an `AGENTS.md` or `CLAUDE.md` contract, [katana](https://github.com/riagentic/katana) rule files that agents are checked against, project linters such as `aiol`, module-boundary checks, and tests that must prove something (aio's suite rejects vacuous tests). A change isn't done until format, lint, type check and the test suite are green. The aim is to ship at agent speed while keeping the code small, reviewable and maintainable.

---

📫 Get in touch: riagentic@proton.me. I'm happy to share a full CV and references with a recruiter once we're talking.
