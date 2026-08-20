# 👋 Hi, I'm Cap

I write local-first software, mostly in **Rust** and **Swift**, and **C++** when needed. The through-line is the same whether it is a Mac app or a matching engine: keep the data on the machine, make the hot path honest, and ship something you can actually open.

Right now that is a retrieval engine (**Mnemosyne**), an on-device time tracker (**Vespora**), a graph view for Linear (**Nonlinear**), and a public profiler for modded Terraria.

- 🎓 **York CS, July 2025.** Rust, deep learning, evolutionary computation. The dissertation was **Neuronika**, a personal knowledge app built to close gaps I found in the IR literature.
- 💼 **Looking for hybrid software roles in London** in systems, AI infrastructure, low-latency trading, or local-first product work. Full UK right to work through August 2027 on a Graduate visa.
- 🎯 **What I like working on:** local-first systems, DeFi internals, brain-inspired learning, trading microstructure. Places where correctness and speed actually fight.
- 🔭 **Longer term:** high-performance systems, AI infrastructure, and AI in healthcare. Tools that respect physics, latency budgets, and one person's data rather than a population average.

---

## 🧠 What I work on

- 🖼️ **Local-first apps:** on-device ML via ONNX Runtime (CLIP, DINOv2, SigLIP-2), Tauri 2 and native Swift / SwiftUI, typed IPC. Everything stays on the Mac.
- 🛠️ **Systems tooling:** Ratatui TUIs, local-first CLIs, and the agent-orchestration layer I actually run my work through.
- 🤖 **AI and learning:** neuroevolution, from-scratch reinforcement learning, and brain-inspired plasticity without backpropagation or an ML framework.
- ⚡ **Trading and fintech:** price-time priority books, lock-free structures, binary UDP for market access.
- 💹 **DeFi:** Uniswap V3 tick maths, Q64.96 fixed-point, cross-DEX arb on free public RPC. No paid APIs.
- 🧵 **Compilers and GPU:** kernel fusion via e-graph rewriting, WGSL and PTX codegen, ONNX / TorchScript lowering toward a fused inference path.
- 🌐 **Network:** HTTP from raw sockets through HTTP/2, WebSockets, and QUIC on a hand-rolled event loop.

---

## ✅ Completed Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| **TypeNotch** _(private)_ | `Swift`, `SwiftUI`, `macOS` | Adaptive touch-typing trainer that lives in the MacBook notch: hover in, type a served line, hover off. A ten-signal weakness profile (pairs, trios, lengths, words, finger zones × speed/error) drives the next word, so the thing trains rather than measures. v1.0.0 delivered to App Store Connect. |
| [**Lynceus**](https://github.com/Capataina/Mnemosyne) | `Rust`, `Tauri`, `React`, `SQLite`, `ONNX Runtime` | Local-first image browser for large collections: Pinterest-style masonry, manual tagging with a folders-as-tags model, per-image notes, and both text-label and natural-language semantic search over a 3-encoder ensemble (CLIP, DINOv2, SigLIP-2) fused via Reciprocal Rank Fusion, running fully offline through ONNX Runtime with WAL-mode SQLite indexing. The first product on the **Mnemosyne** engine in the same repo. |
| [**capataina.dev**](https://capataina.dev) | `Astro`, `TypeScript` | The umbrella marketing site: one domain that gives every project its own landing page, demo, and sales surface. Inverts the old interactive-CV site. Each project gets a real platform instead of a pane of text under a diagram. |
| [**Cernio**](https://github.com/Capataina/Cernio) | `Rust`, `Ratatui`, `SQLite`, `Tokio` | Local-first job discovery and curation engine: a TUI-driven pipeline combining mechanical ATS scanning across hundreds of companies with conversational evaluation against a structured candidate profile, where scripts handle volume and judgement stays human. Pipeline complete at v1.8.1 (730 companies, 1,459 graded roles). |

---

## 🚀 Active Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Mnemosyne**](https://github.com/Capataina/Mnemosyne) | `Rust`, `ONNX Runtime`, `SQLite` | Media-agnostic retrieval engine under Lynceus: asset catalogue, embedding storage, and cosine / Reciprocal Rank Fusion search, designed to be reused by future audio and 3D browsers. Only the encoders, thumbnailer, indexing pipeline, and Tauri surface are image-specific. Same repo as Lynceus; this row is the engine, that row is the shipped app. |
| **Vespora** _(private)_ | `Swift`, `SwiftUI`, `GRDB` | Native macOS menu-bar time tracker that captures the screen, OCRs it, narrates the day with on-device Apple Intelligence, attributes blocks to projects, and exports invoices. Sandboxed for the Mac App Store: the moat is that every competitor needs Accessibility APIs the sandbox forbids. |
| **Nonlinear** _(private)_ | `TypeScript`, `React` | The graph view Linear does not ship: a read-only, horizontal tech-tree of a workspace on an endless canvas. Issues branch and converge on milestones; structure places every connected card, and dates place only the unconnected ones. Demo workspace is the public front door; Sign in with Linear is the next rung. |
| **AgentFulfyl** _(private)_ | `Astro`, `TypeScript` | A storefront where the customers are AI agents, not humans: agents discover the shop, buy a productised service, and it is fulfilled automatically, returning a result that is both human-readable and machine-parseable. A bet on B2A (business-to-agent) commerce as agents begin doing real purchasing on their principals' behalf. Discovery floor is live; payments and fulfilment are unwired on purpose. |
| [**Performance Profiler**](https://github.com/Capataina/TerrariaPerformanceProfilerMod) | `C#`, `.NET 8`, `tModLoader`, `MonoMod` | Always-on per-mod CPU profiler and play-session tracker for modded Terraria, aimed at the Steam Workshop and not published there yet: read-only MonoMod IL-detour instrumentation attributing every per-tick cost to the mod and subsystem that produced it, a btop-style foldable cost tree with green-to-red graded bars, real-time biome and boss-fight tracking, and a screenshot-shareable end-of-session retrospective surfacing dormant cost (frame time paid for mods with zero observed engagement). |

---

## 🌱 Open Source Contributions

| 🔧 Project | ✏️ Contribution |
|------------|----------------|
| [**tracel-ai/burn**](https://github.com/tracel-ai/burn) ([PR #4894](https://github.com/tracel-ai/burn/pull/4894)) | A-FINE no-reference image-quality metric: 1,864-line implementation across 10 files, including an inlined CLIP ViT backbone with PyTorch-weight loader, 5 evaluator heads (technical, structural, aesthetic, authenticity, overall), end-to-end regression tests against the reference implementation, and a `forward_with_features` refactor preserving CLS-token output as a reusable feature-extraction surface for downstream metrics |
| [**tinygrad/tinygrad**](https://github.com/tinygrad/tinygrad) ([PR #16119](https://github.com/tinygrad/tinygrad/pull/16119)) | ONNX LSTM operator (forward direction, default activations) at +21 tokenised lines, with explicit `NotImplementedError` raises for unsupported inputs and two LSTM tests enabled in the ONNX suite. Re-attempt of [PR #15453](https://github.com/tinygrad/tinygrad/pull/15453) (closed on tinygrad's line-budget policy) at the narrower scope the maintainer's review surfaced. |
| **Game mods:** RimWorld, Minecraft, Terraria, Escape from Tarkov | 150,000+ aggregate downloads across published mods spanning gameplay rebalancing, content additions, and quality-of-life patches across four modding ecosystems |

---

## 🗂️ Other Projects

| 🔧 Project | 🧠 Tech Stack | 📄 Summary |
|-----------|--------------|-----------|
| [**Nyquestro**](https://github.com/Capataina/Nyquestro) | `Rust`, `Ratatui`, `Tokio` | Lock-free limit-order-book matching engine in safe Rust shipping multi-instrument routing, a Ratatui observability dashboard with live latency and fill-rate telemetry, integrated risk controls (kill-switches, throttles, fat-finger protection), and live Coinbase WebSocket market-data integration for BTC, ETH, and SOL |
| [**NeuroDrive**](https://github.com/Capataina/NeuroDrive) | `Rust`, `Bevy` | Brain-inspired continual-learning system built from neuroscience primitives: Hebbian plasticity, STDP eligibility traces, dopamine-modulated weight updates, and structural plasticity (synapse growth and pruning) running inside a deterministic 2D racing environment with raycast sensors and centerline-spline progress metrics, deliberately without backpropagation or ML frameworks |
