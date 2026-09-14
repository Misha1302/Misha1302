# Mikhail Razakov

**Compiler & Program Analysis Engineer** — LLVM · C++ · static analysis · x86-64 codegen

I work on compiler and program-analysis problems across optimization legality, data-flow analysis, backend/code generation, and language infrastructure.

- **ISP RAS — Static Analysis Engineer:** SharpChecker, C#/.NET program analysis; current work includes symbolic-computation tasks.
- **ex-MCST — Compiler Engineering Intern:** LLVM 22/C++; implemented LICM with conservative safety checks and differential validation.
- **Accepted speaker at LangDev'26:** *Build the Language, Then Make the Abstractions Disappear: Extensible Programming on .NET.*
- **HSE Software Engineering, 2026–2030.**

## Selected engineering work

| Project | What it demonstrates |
| --- | --- |
| [LLVM Interprocedural Global IV Optimization](https://github.com/Misha1302/LLVM-interprocedural-global-IV-optimization) | Interprocedural effect analysis, affine evolution, APInt semantics, legality checks, LLVM transformation validation |
| [x86-64 Codegen & Register Allocation](https://github.com/Misha1302/x86-64-codegen-ra-playground) | SSA/CFG validation, liveness/interference, register allocation, spills, phi lowering, SysV x86-64, differential execution |
| [DerefAfterNullAnalyzer](https://github.com/Misha1302/DerefAfterNullAnalyzer) | Roslyn CFG, fixed-point data flow, branch refinement, loops/back edges, conservative invalidation |
| [UniversalToolchain](https://github.com/Misha1302/UniversalToolchain) | Deterministic compiler composition, dependency/conflict resolution, typed artifact routing, extensible language infrastructure |

## Current focus

I am especially interested in compiler backend/code generation, program analysis, LLVM infrastructure, and architectures that make compiler extensions composable without hiding correctness constraints.

**CV:** [Compiler & Program Analysis](https://misha1302.github.io/CV/en-compiler.html) · [Backend / Codegen](https://misha1302.github.io/CV/en-compiler-backend.html) · [Program Analysis](https://misha1302.github.io/CV/en-program-analysis.html)
