# Sungjoo Kim — Systems Builder

I build tools that turn opaque systems into readable structure.

My work sits at the intersection of **reverse engineering**, **decompiler architecture**, **AI agent tooling**, **Rust systems engineering**, and unconventional computational modeling.

---

## Focus

- **Decompiler Engineering** — binary loading, instruction lifting, IR design, CFG structuring, pseudocode generation.
- **Reverse Engineering Automation** — MCP servers for static analysis, dynamic malware analysis, forensics, and security workflows.
- **Rust-Native Systems** — modular workspaces, WASM applications, CLI-first tooling, agent-facing infrastructure.
- **AI-Native Developer Tools** — frameworks designed for LLMs and code agents, not only human operators.
- **Computational Metaphysics** — modeling abstract domains such as destiny, astrology, and life cycles as executable systems.

---

## Main Projects

### [Fission](https://github.com/sjkim1127/Fission)

**Rust-native reverse-engineering and binary decompilation workspace.**

Fission is built around a Fission-owned intermediate representation pipeline: Sleigh-style instruction semantics feed into Rust-owned p-code, NIR, HIR, structuring, rendering, automation, and quality gates.

The goal is not only to decode instructions, but to produce decompiler output that is mechanically traceable, semantically defensible, and useful for day-to-day reverse engineering.

**Keywords:** Rust, decompiler, p-code, NIR, HIR, CFG, binary analysis, pseudocode rendering.

---

### [Eon](https://github.com/sjkim1127/Eon)

**The Destiny Reversing Engine.**

Eon reinterprets Korean Saju and Vedic Astrology through systems engineering and reverse engineering. It treats life data as a kind of source code: something that can be compiled, simulated, debugged, linted, fuzzed, and optimized.

It is implemented as a **100% Rust / Dioxus Web / WASM** application, with a modular crate architecture covering Saju analysis, Vedic astrology, Swiss Ephemeris bindings, service DTOs, AI integration, and browser-native UI.

**Key ideas:**

- **Saju-VM** — compiles Four Pillars data into register-like elemental states.
- **Destiny TTD** — time-travel debugging for life-cycle turning points.
- **Destiny Fuzzer** — explores Daeun × Sewun combinations to detect vulnerable future cycles.
- **Destiny Linter** — emits structured diagnostics for Saju patterns.
- **Vedic Engine** — divisional charts, Shadbala, Dasha systems, Yoga detection, Panchanga, and Ashtakavarga.

**Keywords:** Rust, Dioxus, WASM, Saju, Vedic Astrology, systems modeling, simulation, AI-assisted interpretation.

---

### [Reversecore MCP](https://github.com/sjkim1127/Reversecore_MCP)

**AI-powered reverse engineering and security analysis through Model Context Protocol.**

Reversecore MCP turns AI clients into security research workstations by exposing a broad analysis toolchain for static analysis, decompilation, dynamic triage, malware analysis, vulnerability research, SAST, digital forensics, and MITRE ATT&CK-mapped reporting.

**Keywords:** MCP, Radare2, r2ghidra, Capstone, LIEF, YARA, angr, Volatility3, malware analysis, forensics.

---

### [NexusCore MCP](https://github.com/sjkim1127/Nexuscore_MCP)

**AI-driven dynamic malware analysis server.**

NexusCore bridges LLM agents with low-level system instrumentation, enabling interactive debugging, malware execution control, memory dumping, Frida-based instrumentation, YARA verification, and real-time forensic triage.

**Keywords:** MCP, malware analysis, Frida, Unicorn, Ghidra, IDA, x64dbg, PE-Sieve, CAPA, dynamic analysis.

---

### [Architect MCP](https://github.com/sjkim1127/Architect_MCP)

**Static analysis and architectural governance server for AI agents.**

Architect MCP uses Tree-sitter and high-performance parallel analysis to help AI agents understand, visualize, and govern large codebases across multiple languages.

**Keywords:** MCP, Tree-sitter, Rayon, static analysis, call graphs, dependency analysis, architecture linting, AI context optimization.

---

### [Aether](https://github.com/sjkim1127/Aether)

**Infrastructure layer for AI code generation.**

Aether is a type-safe framework that bridges creative LLM output and rigid software engineering through structured templates, semantic caching, self-healing TDD loops, and token-efficient protocol optimization.

**Keywords:** Rust, TypeScript, Python, code generation, semantic caching, self-healing loops, AI infrastructure.

---

### [ReactCut](https://github.com/sjkim1127/ReactCut)

**AI IDE-first, code-based video editing framework.**

ReactCut treats video editing as deterministic TypeScript code, making it easier for AI agents and developers to generate, validate, preview, and render videos from a code editor.

**Keywords:** TypeScript, React, Rust, WASM, Remotion, FFmpeg, video-as-code, AI IDE workflow.

---

## Engineering Identity

I am most interested in systems where the original intent is hidden behind layers:

- binary code without source,
- large codebases without architectural clarity,
- malware without explicit behavior,
- AI outputs without deterministic structure,
- symbolic domains without executable models.

My default approach is to recover structure, define ownership boundaries, build intermediate representations, and make the system inspectable.

> Source code can disappear. Intent usually leaves traces.

---

## Tech Stack

**Languages:** Rust, Python, TypeScript, C/C++  
**Domains:** Reverse Engineering, Decompilation, Malware Analysis, Static Analysis, MCP, AI Tooling, WASM  
**Tools & Frameworks:** Dioxus, Tree-sitter, Radare2, Ghidra/r2ghidra, Capstone, LIEF, Frida, YARA, angr, Volatility3, Remotion, FFmpeg

---

## Current Direction

- Building **Fission** into a serious Rust-native decompilation workspace.
- Developing **Eon** as a systems-engineered Saju/Vedic analysis platform.
- Expanding MCP-based infrastructure for AI-assisted reverse engineering, malware analysis, and architectural understanding.
- Exploring tools where AI agents interact with deterministic, inspectable systems instead of loose prompt strings.

---

**GitHub:** [@sjkim1127](https://github.com/sjkim1127)
