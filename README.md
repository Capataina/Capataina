# 👋 Hi, I'm Cap

<p align="center">
  <img src="https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/-Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black" alt="Tauri" />
  <img src="https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/-ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX" />
  <img src="https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/-Bevy-232326?style=flat-square&logo=bevy&logoColor=white" alt="Bevy" />
</p>

I'm a **systems-focused software engineer** building **AI runtimes**, **low-latency engines**, and **performance-critical infrastructure** in **Rust** and **C++**. Currently shipping a local-first DeFi analytics platform on Tauri (**Aurix**), a brain-inspired continual-learning substrate without backprop (**NeuroDrive**), a lock-free limit-order-book matching engine in safe Rust (**Nyquestro**), and a 14-skill agentic-tooling ecosystem layered over Claude Code that orchestrates everything from job discovery to vault upkeep to repository extraction.

- 🎓 **Computer Science graduate** from the University of York (July 2025) — coursework spanning Rust systems work, CNN / MLP / RNN architectures, evolutionary computation in DEAP, cryptography (AES, RSA, Diffie-Hellman, BB84 quantum key distribution), and a final-year multithreaded Unity ECS roguelite project
- 💼 **Seeking hybrid software roles in London** — systems engineering, AI infrastructure, low-latency trading, or local-first product engineering, with full UK right to work through August 2027 on a Graduate Visa
- 🎯 **Core interests:** local-first systems, DeFi infrastructure, brain-inspired AI, and trading-systems microstructure — areas where correctness, performance, and architecture trade off against each other in genuinely interesting ways
- 🔭 **Long-term direction:** high-performance systems engineering, AI-infrastructure work, and AI in healthcare — building tools that respect physics, latency budgets, and individual physiological data instead of population averages

---

## 🧠 My Focus Areas

- 🤖 **AI & machine learning** — neuroevolution, from-scratch reinforcement learning, and brain-inspired plasticity (Hebbian rules, STDP eligibility traces, dopamine-modulated updates, structural growth and pruning) explored deliberately without backpropagation or external ML frameworks
- 🧵 **Compilers & GPU** — kernel fusion via e-graph rewriting, WGSL and PTX codegen, and ONNX / TorchScript model lowering toward a fused-kernel inference path that bypasses general-purpose graph executors
- ⚡ **Trading & fintech** — order-book matching with price-time priority, lock-free and wait-free concurrent data structures, deterministic replay engines, and binary UDP wire protocols for sub-microsecond market access
- 🖼️ **Local-first applications** — embedded ML inference (CLIP, DINOv2, SigLIP-2 via ONNX Runtime), semantic search over personal data, and Tauri 2 desktop architecture with typed IPC envelopes that survive the language boundary cleanly
- 💹 **DeFi infrastructure** — Uniswap V3 AMM mechanics with Q64.96 fixed-point math, cross-DEX arbitrage detection via hand-crafted JSON-RPC and ABI encoding, and on-chain analytics over free public RPC endpoints with zero premium-API dependencies
- 🌐 **Network & concurrency** — HTTP servers from raw TCP sockets up through HTTP/2, WebSockets, and QUIC; async runtimes on a hand-rolled event loop; and zero-copy I/O patterns for protocol-level work
- 🛠️ **Systems tooling** — Ratatui TUIs with vim-style navigation, local-first CLIs that integrate AI agents as first-class components, and an agent-orchestration skill ecosystem layered over Claude Code that treats AI as a substrate for daily work rather than a chatbot

---

## 🚀 Active Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Cernio**](https://github.com/Capataina/Cernio) | `Rust`, `Ratatui`, `SQLite`, `Tokio` | Local-first, human-AI collaborative job discovery and curation engine — a TUI-driven pipeline combining mechanical ATS scanning across hundreds of companies with conversational Claude-assisted evaluation against a structured candidate profile, where scripts handle volume and AI handles judgement |
| [**Image Browser**](https://github.com/Capataina/PinterestStyleImageBrowser) | `Rust`, `Tauri`, `React`, `SQLite`, `ONNX Runtime` | Local-first Pinterest-style image manager built around a 3-encoder semantic-search ensemble (CLIP, DINOv2, SigLIP-2) combined via Reciprocal Rank Fusion, with WAL-mode SQLite background indexing and typed IPC error envelopes — fully offline, privacy-preserving by design |
| [**Aurix**](https://github.com/Capataina/Aurix) | `Rust`, `Tauri`, `React`, `SQLite` | Local-first DeFi analytics platform shipping cross-DEX arbitrage detection, Uniswap V3 LP backtesting with Q64.96 fixed-point math, wallet tracking, gas prediction, and quantitative risk modelling against DeFi-native and TradFi baselines — running entirely on free public RPC endpoints with hand-crafted ABI encoding and zero premium-API dependencies |
| [**NeuroDrive**](https://github.com/Capataina/NeuroDrive) | `Rust`, `Bevy` | Brain-inspired continual-learning system built from neuroscience primitives — Hebbian plasticity, STDP eligibility traces, dopamine-modulated weight updates, and structural plasticity (synapse growth and pruning) running inside a deterministic 2D racing environment with raycast sensors and centerline-spline progress metrics, deliberately without backpropagation or ML frameworks |
| [**Nyquestro**](https://github.com/Capataina/Nyquestro) | `Rust`, `Ratatui`, `Tokio` | Lock-free limit-order-book matching engine in safe Rust shipping multi-instrument routing, a Ratatui observability dashboard with live latency and fill-rate telemetry, integrated risk controls (kill-switches, throttles, fat-finger protection), and live Coinbase WebSocket market-data integration for BTC, ETH, and SOL |

---

## 🔒 Private Projects

Kept private because they're deeply personal or contain sensitive operational data. Open to talking about them in detail.

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| **LifeOS** | `Obsidian`, `Claude Code`, `Python` | Personal operating system built as a 600-file Obsidian vault operated by a custom Claude Code personality and 5-skill ecosystem — a second brain that continuously synthesises across project, health, housing, and profile domains rather than acting as passive note storage, feeding downstream career tools through cross-repo profile distribution and a daily Morning Brew automation |
| **.claude** | `Claude Code`, `Python`, `Markdown` | Versioned global Claude Code configuration repository hosting a custom personality plus a 14-skill ecosystem covering skill authorship, repository extraction, vault maintenance, code auditing, project research, resume iteration, and orient / wrap-up session bookends — meta-tooling that treats Claude as a substrate, not a chat interface |

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

## 🌱 Open Source Contributions

| 🔧 Upstream | ✏️ Contribution |
|------------|----------------|
| [**burn**](https://github.com/tracel-ai/burn) | A-FINE no-reference image-quality metric: 1,864-line implementation across 10 files, including an inlined CLIP ViT backbone with PyTorch-weight loader, 5 evaluator heads (technical, structural, aesthetic, authenticity, overall), end-to-end regression tests against the reference implementation, and a `forward_with_features` refactor preserving CLS-token output as a reusable feature-extraction surface for downstream metrics |
| [**tinygrad**](https://github.com/tinygrad/tinygrad) | ONNX LSTM operator (forward, reverse, bidirectional) following tinygrad's ONNX backend conventions, with an end-to-end regression suite verifying behaviour against ONNX Runtime |

---

## 🚢 Currently Shipping

- 🧬 **Brain-inspired learning substrate (NeuroDrive)** — shipping a M6 substrate with Hebbian plasticity, STDP eligibility-trace credit assignment, dopamine-modulated reward-prediction-error gating, and structural growth-and-prune learning rules, validated against a from-scratch A2C baseline inside a deterministic 2D racing environment
- 💹 **Vector A V3 LP backtester (Aurix)** — shipped end-to-end backtester with Q64.96 fixed-point math, multi-asset benchmarking against DeFi-native baselines (Aave, Compound, Lido, native staking) and TradFi baselines (T-bills, S&P 500, gold), and regime-conditional capital allocation under regime-aware weighting
- ⚡ **Order matching engine (Nyquestro)** — shipped Phase A through D: typed primitives and event types, multi-instrument routing across FIX / UDP / WebSocket / gRPC / CLI gateways, a Ratatui observability dashboard with live latency and fill-rate telemetry, and live Coinbase market-data integration for BTC, ETH, and SOL
- 🖼️ **Multi-encoder semantic search (Image Browser)** — shipping 3-encoder Reciprocal Rank Fusion combining CLIP, DINOv2, and SigLIP-2 over typed IPC envelopes, with WAL-mode SQLite indexing keeping the UI responsive during background embedding generation
- 🛠️ **Agentic tooling ecosystem (Cernio + LifeOS + .claude)** — shipping 14 specialist Claude Code skills layered across job discovery, vault upkeep, project extraction, code auditing, project research, daily Morning Brew synthesis, and meta-skill iteration, with skill authorship treated as a first-class engineering discipline
- 🌱 **Open-source Rust ML contributions** — shipping a 1,864-line A-FINE metric implementation into burn (tracel-ai) and an ONNX LSTM operator implementation into tinygrad, with both contributions sized to be substantively useful rather than cosmetic

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Capataina&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Capataina&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" alt="Top Languages" />
  <img src="https://streak-stats.demolab.com/?user=Capataina&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>
