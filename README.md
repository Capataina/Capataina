# 👋 Hi, I'm Cap

I'm a **systems-focused software engineer** building **AI runtimes**, **low-latency engines**, and **performance-critical infrastructure** in **Rust** and **C++**. Right now that means a media-agnostic retrieval engine (**Mnemosyne**), an on-device macOS time tracker (**Vespora**), a graph view for Linear (**Nonlinear**), and a public per-mod profiler for tModLoader.

- 🎓 **Computer Science graduate** from the University of York (July 2025), focused on Rust systems, deep learning, and evolutionary computation; final-year dissertation on personal knowledge management and information retrieval systems, with **Neuronika** (an AI-powered PKM application) built as the practical project addressing the literature gaps it identified
- 💼 **Seeking hybrid software roles in London** across systems engineering, AI infrastructure, low-latency trading, or local-first product engineering, with full UK right to work through August 2027 on a Graduate Visa
- 🎯 **Core interests:** local-first systems, DeFi infrastructure, brain-inspired AI, and trading-systems microstructure: areas where correctness, performance, and architecture trade off in genuinely interesting ways
- 🔭 **Long-term direction:** high-performance systems engineering, AI-infrastructure work, and AI in healthcare, building tools that respect physics, latency budgets, and individual data instead of population averages

---

## 🧠 My Focus Areas

- 🤖 **AI & machine learning:** neuroevolution, from-scratch reinforcement learning, and brain-inspired plasticity rules explored deliberately without backpropagation or ML frameworks
- 🧵 **Compilers & GPU:** kernel fusion via e-graph rewriting, WGSL and PTX codegen, and ONNX / TorchScript model lowering toward a fused-kernel inference path
- ⚡ **Trading & fintech:** order-book matching with price-time priority, lock-free and wait-free concurrent data structures, and binary UDP wire protocols for low-latency market access
- 🖼️ **Local-first applications:** embedded ML inference via ONNX Runtime (CLIP, DINOv2, SigLIP-2) and Tauri 2 desktop architecture with typed IPC envelopes
- 💹 **DeFi infrastructure:** Uniswap V3 AMM mechanics with Q64.96 fixed-point math, cross-DEX arbitrage via hand-crafted JSON-RPC and ABI encoding, and on-chain analytics over free public RPC endpoints
- 🌐 **Network & concurrency:** HTTP servers from raw TCP sockets up through HTTP/2, WebSockets, and QUIC on a hand-rolled event loop with zero-copy I/O patterns
- 🛠️ **Systems tooling:** Ratatui TUIs with vim-style navigation, local-first CLIs that integrate AI agents as first-class components, and an agent-orchestration skill ecosystem layered over Claude Code

---

## ✅ Completed Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| **TypeNotch** _(private)_ | `Swift`, `SwiftUI`, `macOS` | Adaptive touch-typing trainer that lives in the MacBook notch: hover in, type a served line, hover off. A ten-signal weakness profile (pairs, trios, lengths, words, finger zones × speed/error) drives the next word, so the thing trains rather than measures. v1.0.0 delivered to App Store Connect. |
| [**Lynceus**](https://github.com/Capataina/Mnemosyne) | `Rust`, `Tauri`, `React`, `SQLite`, `ONNX Runtime` | Local-first image browser for large collections: Pinterest-style masonry, manual tagging with a folders-as-tags model, per-image notes, and both text-label and natural-language semantic search over a 3-encoder ensemble (CLIP, DINOv2, SigLIP-2) fused via Reciprocal Rank Fusion, running fully offline through ONNX Runtime with WAL-mode SQLite indexing. The first product on the **Mnemosyne** engine in the same repo. |
| [**capataina.dev**](https://capataina.dev) | `Astro`, `TypeScript` | The umbrella marketing site: one domain that gives every project its own landing page, demo, and sales surface. Inverts the old interactive-CV site. Each project gets a real platform instead of a pane of text under a diagram. |
| **VibeNotch** _(private)_ | `Swift`, `SwiftUI`, `macOS` | A single-purpose agent situation-room living in the macOS notch, purpose-built for Claude Code Agent Teams in Ghostty: it watches teammates spawn, subagents fan out, inter-agent messages fly, and cross-family council dispatches go out to Codex and Gemini, then animates the live agent topology and the conversation between agents in real time. Deliberately narrow: not a general notch monitor, just the one thing off-the-shelf apps don't do. Shipped to `/Applications` as a personal tool. |
| [**Cernio**](https://github.com/Capataina/Cernio) | `Rust`, `Ratatui`, `SQLite`, `Tokio` | Local-first job discovery and curation engine: a TUI-driven pipeline combining mechanical ATS scanning across hundreds of companies with conversational evaluation against a structured candidate profile, where scripts handle volume and judgement stays human. Pipeline complete at v1.8.1 (730 companies, 1,459 graded roles). |

---

## 🚀 Active Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Mnemosyne**](https://github.com/Capataina/Mnemosyne) | `Rust`, `ONNX Runtime`, `SQLite` | Media-agnostic retrieval engine under Lynceus: asset catalogue, embedding storage, and cosine / Reciprocal Rank Fusion search, designed to be reused by future audio and 3D browsers. Only the encoders, thumbnailer, indexing pipeline, and Tauri surface are image-specific. Same repo as Lynceus; this row is the engine, that row is the shipped app. |
| **Vespora** _(private)_ | `Swift`, `SwiftUI`, `GRDB` | Native macOS menu-bar time tracker that captures the screen, OCRs it, narrates the day with on-device Apple Intelligence, attributes blocks to projects, and exports invoices. Sandboxed for the Mac App Store: the moat is that every competitor needs Accessibility APIs the sandbox forbids. |
| **Nonlinear** _(private)_ | `TypeScript`, `React` | The graph view Linear does not ship: a read-only, horizontal tech-tree of a workspace on an endless canvas. Issues branch and converge on milestones; structure places every connected card, and dates place only the unconnected ones. Demo workspace is the public front door; Sign in with Linear is the next rung. |
| [**Performance Profiler**](https://github.com/Capataina/TerrariaPerformanceProfilerMod) | `C#`, `.NET 8`, `tModLoader`, `MonoMod` | Always-on per-mod CPU profiler and play-session tracker for modded Terraria, aimed at the Steam Workshop and not published there yet: read-only MonoMod IL-detour instrumentation attributing every per-tick cost to the mod and subsystem that produced it, a btop-style foldable cost tree with green-to-red graded bars, real-time biome and boss-fight tracking, and a screenshot-shareable end-of-session retrospective surfacing dormant cost (frame time paid for mods with zero observed engagement). |

---

## 🌱 Open Source Contributions

| 🔧 Project | ✏️ Contribution |
|------------|----------------|
| [**tracel-ai/burn**](https://github.com/tracel-ai/burn) ([PR #4894](https://github.com/tracel-ai/burn/pull/4894)) | A-FINE no-reference image-quality metric: 1,864-line implementation across 10 files, including an inlined CLIP ViT backbone with PyTorch-weight loader, 5 evaluator heads (technical, structural, aesthetic, authenticity, overall), end-to-end regression tests against the reference implementation, and a `forward_with_features` refactor preserving CLS-token output as a reusable feature-extraction surface for downstream metrics |
| [**tinygrad/tinygrad**](https://github.com/tinygrad/tinygrad) ([PR #16119](https://github.com/tinygrad/tinygrad/pull/16119)) | ONNX LSTM operator (forward direction, default activations) at +21 tokenised lines, with explicit `NotImplementedError` raises for unsupported inputs and two LSTM tests enabled in the ONNX suite. Re-attempt of [PR #15453](https://github.com/tinygrad/tinygrad/pull/15453) (closed on tinygrad's line-budget policy) at the narrower scope the maintainer's review surfaced. |
| **Game mods:** RimWorld, Minecraft, Terraria, Escape from Tarkov | 150,000+ aggregate downloads across published mods spanning gameplay rebalancing, content additions, and quality-of-life patches across four modding ecosystems |

---

## 🔒 Private Projects

Kept private because they're deeply personal or contain sensitive operational data. Open to talking about them in detail.

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| **LifeOS** | `Obsidian`, `Python` | Personal operating system built as an Obsidian vault operated by agents: a second brain that continuously synthesises across career, health, housing, and profile domains rather than acting as passive note storage, and that feeds downstream career tools from one structured profile. |
| **AgentFulfyl** | `Astro`, `TypeScript` | A storefront where the customers are AI agents, not humans: agents discover the shop, buy a productised service, and it is fulfilled automatically, returning a result that is both human-readable and machine-parseable. A bet on B2A (business-to-agent) commerce as agents begin doing real purchasing on their principals' behalf. Discovery floor is live; payments and fulfilment are unwired on purpose. |

---

## 🗂️ Other Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Nyquestro**](https://github.com/Capataina/Nyquestro) | `Rust`, `Ratatui`, `Tokio` | Lock-free limit-order-book matching engine in safe Rust shipping multi-instrument routing, a Ratatui observability dashboard with live latency and fill-rate telemetry, integrated risk controls (kill-switches, throttles, fat-finger protection), and live Coinbase WebSocket market-data integration for BTC, ETH, and SOL |
| [**Aurix**](https://github.com/Capataina/Aurix) | `Rust`, `Tauri`, `React`, `SQLite` | Local-first DeFi analytics platform shipping cross-DEX arbitrage detection, Uniswap V3 LP backtesting with Q64.96 fixed-point math, wallet tracking, gas prediction, and quantitative risk modelling against DeFi-native and TradFi baselines, running entirely on free public RPC endpoints with hand-crafted ABI encoding and zero premium-API dependencies |
| [**NeuroDrive**](https://github.com/Capataina/NeuroDrive) | `Rust`, `Bevy` | Brain-inspired continual-learning system built from neuroscience primitives: Hebbian plasticity, STDP eligibility traces, dopamine-modulated weight updates, and structural plasticity (synapse growth and pruning) running inside a deterministic 2D racing environment with raycast sensors and centerline-spline progress metrics, deliberately without backpropagation or ML frameworks |
