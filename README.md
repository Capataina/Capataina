# 👋 Hi, I'm Cap

I'm a **systems-focused software engineer** building **AI runtimes**, **low-latency engines**, and **performance-critical infrastructure** in **Rust** and **C++**. Currently shipping a local-first DeFi analytics platform on Tauri (**Aurix**), a brain-inspired continual-learning substrate without backprop (**NeuroDrive**), a lock-free limit-order-book matching engine in safe Rust (**Nyquestro**), and a 14-skill agentic-tooling ecosystem layered over Claude Code that orchestrates everything from job discovery to vault upkeep to repository extraction.

- 🎓 **Computer Science graduate** from the University of York (July 2025), focused on Rust systems, deep learning, and evolutionary computation; final-year dissertation on personal knowledge management and information retrieval systems, with **Neuronika** (an AI-powered PKM application) built as the practical project addressing the literature gaps it identified
- 💼 **Seeking hybrid software roles in London** across systems engineering, AI infrastructure, low-latency trading, or local-first product engineering, with full UK right to work through August 2027 on a Graduate Visa
- 🎯 **Core interests:** local-first systems, DeFi infrastructure, brain-inspired AI, and trading-systems microstructure — areas where correctness, performance, and architecture trade off in genuinely interesting ways
- 🔭 **Long-term direction:** high-performance systems engineering, AI-infrastructure work, and AI in healthcare — building tools that respect physics, latency budgets, and individual data instead of population averages

---

## 🧠 My Focus Areas

- 🤖 **AI & machine learning** — neuroevolution, from-scratch reinforcement learning, and brain-inspired plasticity rules explored deliberately without backpropagation or ML frameworks
- 🧵 **Compilers & GPU** — kernel fusion via e-graph rewriting, WGSL and PTX codegen, and ONNX / TorchScript model lowering toward a fused-kernel inference path
- ⚡ **Trading & fintech** — order-book matching with price-time priority, lock-free and wait-free concurrent data structures, and binary UDP wire protocols for low-latency market access
- 🖼️ **Local-first applications** — embedded ML inference via ONNX Runtime (CLIP, DINOv2, SigLIP-2) and Tauri 2 desktop architecture with typed IPC envelopes
- 💹 **DeFi infrastructure** — Uniswap V3 AMM mechanics with Q64.96 fixed-point math, cross-DEX arbitrage via hand-crafted JSON-RPC and ABI encoding, and on-chain analytics over free public RPC endpoints
- 🌐 **Network & concurrency** — HTTP servers from raw TCP sockets up through HTTP/2, WebSockets, and QUIC on a hand-rolled event loop with zero-copy I/O patterns
- 🛠️ **Systems tooling** — Ratatui TUIs with vim-style navigation, local-first CLIs that integrate AI agents as first-class components, and an agent-orchestration skill ecosystem layered over Claude Code

---

## 🚀 Active Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Cernio**](https://github.com/Capataina/Cernio) | `Rust`, `Ratatui`, `SQLite`, `Tokio` | Local-first, human-AI collaborative job discovery and curation engine — a TUI-driven pipeline combining mechanical ATS scanning across hundreds of companies with conversational Claude-assisted evaluation against a structured candidate profile, where scripts handle volume and AI handles judgement |
| [**Image Browser**](https://github.com/Capataina/PinterestStyleImageBrowser) | `Rust`, `Tauri`, `React`, `SQLite`, `ONNX Runtime` | Local-first Pinterest-style image manager built around a 3-encoder semantic-search ensemble (CLIP, DINOv2, SigLIP-2) combined via Reciprocal Rank Fusion, with WAL-mode SQLite background indexing and typed IPC error envelopes — fully offline, privacy-preserving by design |
| [**Aurix**](https://github.com/Capataina/Aurix) | `Rust`, `Tauri`, `React`, `SQLite` | Local-first DeFi analytics platform shipping cross-DEX arbitrage detection, Uniswap V3 LP backtesting with Q64.96 fixed-point math, wallet tracking, gas prediction, and quantitative risk modelling against DeFi-native and TradFi baselines — running entirely on free public RPC endpoints with hand-crafted ABI encoding and zero premium-API dependencies |
| [**NeuroDrive**](https://github.com/Capataina/NeuroDrive) | `Rust`, `Bevy` | Brain-inspired continual-learning system built from neuroscience primitives — Hebbian plasticity, STDP eligibility traces, dopamine-modulated weight updates, and structural plasticity (synapse growth and pruning) running inside a deterministic 2D racing environment with raycast sensors and centerline-spline progress metrics, deliberately without backpropagation or ML frameworks |
| [**Nyquestro**](https://github.com/Capataina/Nyquestro) | `Rust`, `Ratatui`, `Tokio` | Lock-free limit-order-book matching engine in safe Rust shipping multi-instrument routing, a Ratatui observability dashboard with live latency and fill-rate telemetry, integrated risk controls (kill-switches, throttles, fat-finger protection), and live Coinbase WebSocket market-data integration for BTC, ETH, and SOL |
| [**Tessarix**](https://github.com/Capataina/Tessarix) | `Rust`, `Tauri`, `React`, `TypeScript`, `MDX` | Local-first interactive learning substrate combining lesson-narrative (Brilliant-style MDX pages with embedded widgets), drill-down algorithm playgrounds (Cartesian / visualgo step-through visualisations with editable code that re-runs the visualiser on every edit), ByteByteGo-style technical diagrams when interactivity is the wrong tool, and adaptive retrieval-practice with SM-2 / FSRS spacing over a generated question bank; three pillars per concept (teach / quiz / interview) sharing the same content + question bank, with an LLM-driven sync-learning agent that converts personal knowledge-base notes into draft lessons and question banks for editorial review |

---

## 🌱 Open Source Contributions

| 🔧 Project | ✏️ Contribution |
|------------|----------------|
| [**tracel-ai/burn**](https://github.com/tracel-ai/burn) ([PR #4894](https://github.com/tracel-ai/burn/pull/4894)) | A-FINE no-reference image-quality metric: 1,864-line implementation across 10 files, including an inlined CLIP ViT backbone with PyTorch-weight loader, 5 evaluator heads (technical, structural, aesthetic, authenticity, overall), end-to-end regression tests against the reference implementation, and a `forward_with_features` refactor preserving CLS-token output as a reusable feature-extraction surface for downstream metrics |
| [**tinygrad/tinygrad**](https://github.com/tinygrad/tinygrad) ([PR #15453](https://github.com/tinygrad/tinygrad/pull/15453)) | ONNX LSTM operator (forward, reverse, bidirectional) following tinygrad's ONNX backend conventions, with an end-to-end regression suite verifying behaviour against ONNX Runtime |
| **Game mods** — RimWorld, Minecraft, Terraria, Escape from Tarkov | 150,000+ aggregate downloads across published mods spanning gameplay rebalancing, content additions, and quality-of-life patches across four modding ecosystems |

---

## 🔒 Private Projects

Kept private because they're deeply personal or contain sensitive operational data. Open to talking about them in detail.

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| **LifeOS** | `Obsidian`, `Claude Code`, `Python` | Personal operating system built as an 800+ file Obsidian vault operated by a custom Claude Code personality and 6-skill ecosystem — a second brain that continuously synthesises across project, health, housing, and profile domains rather than acting as passive note storage, feeding downstream career tools through cross-repo profile distribution and a daily Morning Brew automation |
| **.config** | `OpenCode`, `Python`, `Fish`, `Neovim` | Versioned `~/.config` repository hosting shell config (Fish, Starship, Alacritty, Ghostty), system tools (btop, fastfetch), editor config (Neovim), and a full multi-skill agent ecosystem (AGENTS.md, 8 skills, 3 scripts) ported from Claude Code to opencode-native — meta-tooling that stays agent-agnostic across OpenCode, Claude Code, and Codex |
| **.claude** | `Claude Code`, `Python`, `Markdown` | Versioned global Claude Code configuration repository hosting a custom personality plus an 8-skill global ecosystem covering skill authorship, project context maintenance, code auditing, project research, project enhancement, learning curation, and orient / wrap-up session bookends — meta-tooling that treats Claude as a substrate, not a chat interface |
| **.codex** | `Codex`, `Python`, `Markdown` | Versioned global Codex configuration repository mirroring the Claude Code operating layer for Codex — AGENTS.md global context, project trust settings, reusable scripts, system/user skills, and orient / wrap-up session bookends adapted for Codex's runtime constraints |
| **OpenSourceContributions** | `Claude Code`, `Markdown` | Umbrella orchestration folder for open source contribution work — universal Claude Code personality, durable per-project memory preserved across clone deletions (contribution culture audits, repo conventions, postmortems, draft upstream comments), and a growing speech-patterns reference that translates casual chat voice into authentic Caner-voice for commits, PR bodies, issue comments, and review replies |

---

## 🗂️ Other Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Vynapse**](https://github.com/Capataina/Vynapse) | `Rust` | Hybrid neuroevolution and deep-learning runtime unifying NEAT topology mutation, DEAP population search, PyTorch-style autodiff, and TensorFlow-style graph compilation in a single from-scratch framework |
| [**AsteroidsAI**](https://github.com/Capataina/Asteroids-AI) | `Python`, `Arcade`, `NEAT`, `DEAP`, `PyTorch`, `TensorFlow` | Real-time AI benchmarking platform comparing neuroevolution, genetic algorithms, evolution strategies, and graph-based RL on continuous-control tasks under matched conditions for honest paradigm-vs-paradigm comparison |
| [**Consilium**](https://github.com/Capataina/Consilium) | `Python`, `LangChain` | Provider-agnostic multi-LLM debate platform orchestrating structured multi-round discussions between heterogeneous language models via LangChain — Textual TUI, structured per-round state emission, agreement and disagreement tracking, and thesis-style final synthesis written to transcripts |
| [**Chrona**](https://github.com/Capataina/Chrona) | `C++` | Git-inspired version control system built from first principles — content-addressed storage, immutable snapshots, commit DAGs, and staging semantics implemented without git's source as a reference |
| [**Xyntra**](https://github.com/Capataina/Xyntra) | `Rust` | ML graph fusion compiler pass using e-graph rewriting to identify kernel-fusion opportunities and emit optimised WGSL / PTX kernels for ONNX and TorchScript models, targeting an inference path that bypasses general-purpose graph executors |
| [**Zyphos**](https://github.com/Capataina/Zyphos) | `Rust` | Network protocol laboratory implementing HTTP servers from scratch — progressing from raw TCP sockets through HTTP/1.1, HTTP/2, WebSockets, and QUIC with a hand-rolled event loop and zero external networking framework dependencies |
| [**Tectra**](https://github.com/Capataina/Tectra) | `C++`, `FlatBuffers`, `Prometheus` | Production-style trading infrastructure combining a market-data feed handler, a pre-trade risk engine, a strategy execution framework, a backtesting engine, and a deterministic replay system for verifying strategy behaviour against historical sessions |

---

## 🚢 Currently Shipping

- 🧬 **Brain-inspired learning substrate (NeuroDrive)** — shipped the M6 substrate with Hebbian, STDP, and dopamine-modulated learning rules validated against a from-scratch A2C baseline
- 💹 **Vector A V3 LP backtester (Aurix)** — shipped end-to-end backtester with Q64.96 fixed-point math, multi-asset benchmarking, and regime-conditional capital allocation
- ⚡ **Order matching engine (Nyquestro)** — shipped Phase A through D with multi-instrument routing, a Ratatui observability dashboard, and live Coinbase market-data integration for BTC, ETH, and SOL
- 🖼️ **Multi-encoder semantic search (Image Browser)** — shipped 3-encoder Reciprocal Rank Fusion combining CLIP, DINOv2, and SigLIP-2 over typed IPC with WAL-mode SQLite indexing
- 🛠️ **Agentic tooling ecosystem (Cernio + LifeOS + .claude)** — shipping 14 specialist Claude Code skills layered across job discovery, vault upkeep, project extraction, code auditing, and daily Morning Brew synthesis
