# 👋 Hi, I'm Cap

Software engineer building AI/ML systems, game AI and performance tooling in Rust, C#, Swift and Luau.

---

## 🧠 What I work on

- 🤖 **AI and ML systems:** training and inference performance, GPU kernel fusion and from-scratch learning algorithms.
- 🎮 **Game AI:** work-scheduling, combat-lookahead and companion agents, built as mods for simulation games.
- ⚡ **Performance and profiling:** runtime instrumentation, IL injection and per-component cost attribution.
- 🖥️ **Products:** native macOS apps, cross-platform desktop apps, Safari extensions and Roblox games.

---

## 🔬 Systems and AI

| | 🔧 Project | 📄 What it is | 🧠 Stack |
|---|---|---|---|
| **ML Systems** | [**Blaze**](https://capataina.dev/blaze) | Contract-guarded, runtime-adaptive kernel-fusion planner for dynamic tensor operations: it times candidate fusion plans on live training steps and keeps the fastest one it measured | `Rust`, `Burn`, `CubeCL`, `Metal` |
| **RimWorld AI Trilogy** | **Let Us Handle This** | Plans every colonist's work priorities and daily schedule from the work on the map, pricing each job by its work plus the walk | `C#`, `Harmony` |
| | **We've Got Your Back** | Combat AI that looks a few seconds ahead before each move and picks the one that keeps everyone alive, then the fewest down | `C#`, `Harmony` |
| | **They Are Handling It** | Raider AI that remembers where its past raids died and attacks the colony from a different direction on its next raid | `C#`, `Harmony` |
| **Terraria** | [**Performance Profiler**](https://github.com/Capataina/TerrariaPerformanceProfilerMod) | Always-on per-mod CPU and memory profiler for tModLoader, injecting timing IL into every override a mod defines | `C#`, `MonoMod` |
| | [**AICompanion**](https://github.com/Capataina/AICompanion) | An AI companion that plays with you: it follows you, fights beside you, takes your orders and grows through its own tree | `C#`, `tModLoader` |

## 🌱 Open Source

- [**tracel-ai/burn**](https://github.com/tracel-ai/burn): added the A-FINE image-quality metric, with an inlined CLIP ViT-B/32 backbone and parity tests ([PR #4894](https://github.com/tracel-ai/burn/pull/4894)).
- [**tinygrad/tinygrad**](https://github.com/tinygrad/tinygrad): the ONNX LSTM operator, bringing Silero VAD v5 to tinygrad, under review ([PR #16119](https://github.com/tinygrad/tinygrad/pull/16119)).

## 🖥️ Apps

| | 🔧 Project | 📄 What it is | 🧠 Stack |
|---|---|---|---|
| **macOS** | [**TypeNotch**](https://capataina.dev/typenotch) | Adaptive touch-typing trainer in the MacBook notch that learns your slow key pairs and serves words that drill them until they are fast | `Swift`, `SwiftUI` |
| | [**Vespora**](https://capataina.dev/vespora) | On-device time tracker that reads your screen, narrates your day with the Mac's built-in AI, and turns it into billable hours | `Swift`, `Vision`, `Foundation Models` |
| **Desktop** | [**Lynceus**](https://capataina.dev/lynceus) | Local-first image browser over your own folders, with semantic search across a CLIP, DINOv2 and SigLIP-2 ensemble ([source](https://github.com/Capataina/Mnemosyne)) | `Rust`, `Tauri`, `React`, `ONNX` |
| **Safari** | **Imprix** | Extension that lifts a website's design language (tokens, layout, states, motion) into one paste-ready brief for an AI coding agent | `TypeScript` |

## 🎮 Roblox Games

| | 🔧 Game | 📄 What it is | 🧠 Stack |
|---|---|---|---|
| **Simulator** | **Cavern Crew** | Co-op mining game where every server digs one shared procedural voxel mine, through four cave zones, furnaces and a deep enchantment tree | `Luau`, `Rojo` |
| **Tycoon** | [**Cafe Cuties**](https://www.roblox.com/games/112211439306630) | Cafe management on a shared street: decorate your cafe, then serve customers through skill minigames that decide the tip, and hire staff to grow it | `Luau`, `Rojo` |
| **Roguelike** | **Nova Holdout** | Base defence on an alien planet: scavenge an open map by day, carry the loot home in a grid inventory, then hold off the night's attack waves | `Luau`, `Rojo` |

---

30,000+ Steam Workshop subscribers across my RimWorld mods · Computer Science, University of York
