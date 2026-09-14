# AhmedTrooper — Projects

A central index of my flagship open-source projects. Each section below links to a repo, describes what it does, and lists the stack behind it.

---

## 🛡️ Shieldr

**Defending your computer against the world's most chaotic penetration testers: toddlers and cats.**

A zero-compromise transparent screen lock and touch barrier for Linux, macOS & Windows. Built with **Tauri v2 + SolidJS + Rust**, Shieldr creates a fullscreen, always-on-top interactive barrier that intercepts mouse clicks, gestures, and OS shortcut keys while letting background videos and applications continue playing unobobstructed.

- 🛡️ Transparent Click & Gesture Interceptor
- 🔒 OS-Level Anti-Escape Guardrails (Alt+F4, Super, Ctrl+W, Alt+Tab)
- 🔐 Zero-Knowledge Dual Vault — Quick Unlock PIN, Argon2id Master Password, BIP-39 Recovery Phrase, Tauri Stronghold + OS Keyring
- ⏱️ Brute-Force Rate Limiting with exponential lockout
- 🎨 Frosted Glass & Display Customization (transparent → blackout)
- 📍 Discrete Floating Lock Badge with idle fade
- 🔊 Procedural Web Audio FX (zero external assets)
- 📜 Tamper-Resistant SQLite Audit Trail

**Stack:** Tauri v2 · SolidJS · Rust · TypeScript

🔗 [GitHub](https://github.com/AhmedTrooper/Shieldr) · [Peerlist](https://peerlist.io/ahmedtrooper/project/shieldr)

---

## 📄 RoleTect

**Local-first, privacy-focused desktop app + browser extension that centralizes your job application pipeline.**

RoleTect parses job descriptions into structured requirements and tailors professional LaTeX resumes and cover letters using sovereign AI models — your data never leaves your machine unless you want it to.

- **Local-First & Privacy Sovereign** storage
- **Multi-Provider AI Tailoring** (Gemini, OpenAI, Claude, Groq, AWS Bedrock, Ollama)
- **Built-in Tectonic LaTeX Compiler** with self-healing output
- **Companion Browser Ingestion** for LinkedIn, Indeed, Glassdoor
- **Side-by-Side Resume Comparison**
- **S3-Compatible Cloud Synchronization**
- **Technical Diagramming Canvas** (Mermaid.js)

**Stack:** Axum · Next.js · Tauri v2

🔗 [GitHub](https://github.com/AhmedTrooper/RoleTect) · [Peerlist](https://peerlist.io/ahmedtrooper/project/roletect--your-ai-career-workspace)

---

## 🚀 SyncLime (OSGUI)

**A premium native desktop media downloader engineered for high-speed multithreaded network queues without UI thread freezes.**

SyncLime manages large extraction loads smoothly by offloading parsing to a native Rust background task layer and serializing UI updates through a lightweight SQLite transactional cache — no process ghosting, no frontend freezes.

- ⚡ Fast Playlist Parsing & multi-track analysis
- 🎛️ Tactile Desktop Interface
- 🌐 Domain Routing Prefs, Proxies & Cookie Vault
- 🛡️ Process Protection Limits & Quit Safety
- 📜 Diagnostics Logs & Staging
- ✅ Real-Time Reference Validation
- 🧩 Browser Companion Extensions (Chrome + Firefox)

**Stack:** Tauri v2 · SolidJS · Rust · SQLite · yt-dlp · ffmpeg · aria2

🔗 [github.com/AhmedTrooper/SyncLime](https://github.com/AhmedTrooper/SyncLime)

---

## 🚨 Trative

**An open-source, white-label emergency response platform with real-time hybrid GPS tracking.**

Trative is a highly-scalable, production-ready fullstack monorepo built as a polyglot suite — Rust backend, Next.js admin portal, and Flutter mobile client — all aligned to a single OpenAPI source of truth.

- 🛰️ **Real-time Hybrid GPS Tracking** via Redis Geo
- 🗄️ **Robust Hive Local Caching** on the mobile client for offline resilience
- 🔐 **Secure Chunked S3 Media Uploads** with append-only message queue for data integrity
- 📡 **Role-Aware Homes** for admin and rescuer, with 3s SOS hold gesture
- 🧩 **OpenAPI-Driven Type Safety** across Rust, TypeScript and Dart
- 🐳 **Containerized Infra** — Postgres + PostGIS, Redis, MinIO via Docker Compose
- ☁️ **Cloud-Ready** — Terraform modules for AWS + Kubernetes deployment templates

**Stack:** Rust · Axum · Tokio · Next.js 16 · React 19 · Tailwind v4 · Shadcn UI · Bun · Flutter 3.44 · Dart · Postgres + PostGIS · Redis · MinIO · OpenAPI · Docker · Terraform · Kubernetes

🔗 Trative (commercial — link redacted)

---

<div align="center">

**[AhmedTrooper](https://github.com/AhmedTrooper)**

</div>
