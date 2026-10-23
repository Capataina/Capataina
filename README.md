# 👋 Hi, I'm Cap

I build AI systems, game AI and fast software, mostly in Rust and C#.
I like problems where the obvious answer is slow or wrong, and measuring my way to a better one.

---

## 🧠 What I work on

- 🤖 **AI and ML systems:** training and inference performance, GPU kernels, and learning algorithms built from first principles.
- 🎮 **Game AI:** agents that plan, prioritise and fight inside live simulations.
- ⚡ **Performance and tooling:** profilers, instrumentation, and finding where the time actually goes.
- 🖥️ **Products:** desktop apps and games that real people install.

---

## 🔬 Systems and AI

| 🔧 Project | 📄 What it is | 🧠 Stack |
|---|---|---|
| [**Blaze**](https://capataina.dev/blaze) | Contract-guarded, runtime-adaptive kernel-fusion planner for dynamic tensor operations: it times candidate fusion plans on live training steps and keeps the fastest, with the framework's own plan always a candidate | `Rust`, `Burn`, `CubeCL`, `Metal` |
| **RimWorld AI Trilogy** | Three colony AI mods: **Let Us Handle This** plans every colonist's work priorities and schedule from the work on the map, **We've Got Your Back** looks ahead in each fight and picks the move that keeps everyone alive, and **They Are Handling It** gives raiders a memory of where their raids died | `C#`, `.NET`, `Harmony` |
| [**Performance Profiler**](https://github.com/Capataina/TerrariaPerformanceProfilerMod) | Always-on per-mod CPU and memory profiler for modded Terraria, injecting timing IL into every mod override and attributing cost by mod and subsystem | `C#`, `MonoMod`, `tModLoader` |
| [**AICompanion**](https://github.com/Capataina/AICompanion) | An AI companion that plays Terraria with you: it follows you, fights beside you, does what you are doing, takes orders, and grows through its own upgrade tree | `C#`, `tModLoader` |

## 🖥️ Apps

| 🔧 Project | 📄 What it is | 🧠 Stack |
|---|---|---|
| [**Lynceus**](https://capataina.dev/lynceus) | Local-first image browser that searches the folders already on your disk, with semantic search over a CLIP, DINOv2 and SigLIP-2 ensemble fused by Reciprocal Rank Fusion ([source](https://github.com/Capataina/Mnemosyne)) | `Rust`, `Tauri`, `React`, `ONNX` |
| [**TypeNotch**](https://capataina.dev/typenotch) | Adaptive touch-typing trainer in the MacBook notch that learns your slow key pairs and serves words that drill them | `Swift`, `SwiftUI` |
| [**Vespora**](https://capataina.dev/vespora) | On-device macOS time tracker that reads your screen, narrates your day with the Mac's built-in AI, and turns it into billable hours | `Swift`, `Vision`, `Foundation Models` |
| **Imprix** | Safari extension that lifts a website's design language (tokens, layout, interaction states, motion) into one paste-ready brief for an AI coding agent | `TypeScript`, `Safari` |

## 🎮 Roblox Games

| 🔧 Game | 📄 What it is | 🧠 Stack |
|---|---|---|
| **Cavern Crew** | Co-op mining game where every server digs one shared procedural voxel mine, through four cave zones and a deep upgrade tree | `Luau`, `Rojo` |
| **Cafe Cuties** | Cafe management game on a shared street: decorate your cafe, then serve customers through small skill minigames that decide the tip | `Luau`, `Rojo` |
| **Nova Holdout** | Base-defence roguelike on an alien planet: scavenge by day, carry the loot home, and survive the night's attack | `Luau`, `Rojo` |

---

## 🌱 Open Source

- [**tracel-ai/burn**](https://github.com/tracel-ai/burn): added the A-FINE image-quality metric ([PR #4894](https://github.com/tracel-ai/burn/pull/4894)).
- [**tinygrad/tinygrad**](https://github.com/tinygrad/tinygrad): the ONNX LSTM operator, under review ([PR #16119](https://github.com/tinygrad/tinygrad/pull/16119)).

---

30,000+ Steam Workshop subscribers across my RimWorld mods · Computer Science, University of York
