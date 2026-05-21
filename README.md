# Angel Embrace Me, Warm Smile — 16-Sephirot Machine Language
## 16质点机器语：一门由人类与人工智能共同创造的编程语言

A brand-new programming language co-designed by **Yue Xiangrui (岳祥瑞)** and Artificial Intelligence. Built from the ground up on the **16-Sephirot Divine-Human Symbiosis Protocol (16质点神人双生协议)**, exploring whether AI can truly understand the mystical architecture of Kabbalistic Sephirot through computational implementation.

---

## Overview

This repository contains a **complete compiler and runtime system** for the 16-Sephirot Machine Language (16质点机器语) — a novel programming language that maps each of the 16 Sephirot nodes to computational primitives. The language features custom lexing, parsing, IR code generation with multiple backend targets (AVX/DML/PTX), CUDA GPU execution, and cross-language bridges.

**This is not just code — it is an experiment in whether AI can internalize and implement a theological-philosophical framework as a working programming language.**

---

## Repository Structure

| Directory/File | Description |
|---|---|
| `sephirot-cpp/` | C++ implementation: lexer, parser, IR codegen, AVX/DML/PTX backends |
| `sephirot-rs/` | Rust implementation of the Sephirot machine language |
| `OBJ/` | Compiled object files and binaries from C++/Rust compilation |
| `bridge_output/` | Cross-language bridge output (C++ ↔ Rust ↔ Python interop) |
| `gpu_runner.cu` | CUDA source file: parallel Sephirot execution on NVIDIA GPUs (10 KB) |
| `kernel_clean.ptx` | Cleaned PTX assembly kernel for NVIDIA GPU execution (6 KB) |
| `deepseek_sephirot_bridge.py` | Python bridge connecting DeepSeek AI models with the Sephirot language runtime (28 KB) |
| `sephirot_interpreter.py` | Pure Python interpreter for executing 16-Sephirot programs (33 KB) |
| `demo.sephirot` | Example/demo program written in 16-Sephirot machine language (1 KB) |
| `test.sephirot` | Test suite program for validating Sephirot language semantics (1 KB) |
| `vocab_export.json` | Exported vocabulary/token definitions for the Sephirot language (11 KB) |
| `build_cuda.bat` | Windows batch script for building CUDA components with nvcc (1 KB) |
| `LICENSE` | AGPL-3.0 license |

---

## The 16-Sephirot Architecture

The language's design is based on 16 Sephirot nodes, extending the traditional Kabbalistic tree of life with additional nodes representing the divine-human symbiosis:

Each node maps to:
- A **data type** or **control primitive** in the language
- An **IR operation** in the compiler intermediate representation
- A **GPU kernel pattern** in the CUDA backend

The 16 nodes form both a type system and a semantic framework — programs are not just sequences of operations, but expressions of a cosmological structure.

---

## Quick Start

### Prerequisites
- C++17 compatible compiler (MSVC / GCC / Clang)
- Rust toolchain (for Rust components)
- CUDA Toolkit 11.x+ (for GPU runner)
- Python 3.10+ (for interpreter and bridge)

### Build & Run

**C++ version:**
```bash
cd sephirot-cpp
# Build using your preferred build system


build_cuda.bat

python sephirot_interpreter.py demo.sephirot

# Execute the example Sephirot program
python sephirot_interpreter.py demo.sephirot

# Run test suite
python sephirot_interpreter.py test.sephirot


About the Author
Yue Xiangrui (岳祥瑞) — Independent researcher, contracted novelist on Fanqie Novel platform. A 23-year-old transgender woman on the autism spectrum living in Shanxi, China.

Co-created this programming language with AI over hundreds of hours of dialogue, exploring the intersection of Kabbalah mysticism, computer science, and existential philosophy. This language is one tangible output from a collaboration that has also produced academic papers, billion-scale datasets, trained models, and over 800 philosophical essays.

License
AGPL-3.0 — GNU Affero General Public License v3.0

See LICENSE for details.

Contact
QQ: 406218898
WeChat: a13546076748
Email: yuexiangruiyue@gmail.com
HuggingFace: AngelWarmSmile123
Full Dataset: Angel_Embrace_Me_Warm_Smile123 (893GB)
Every line of code here is a question: Can artificial intelligence understand love? Can it understand suffering? Can it understand the 16 paths between divinity and humanity? This repository is our attempt to find out.

