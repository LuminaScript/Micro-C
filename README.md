# Micro-C

Micro-C is a minimal C compiler written in Ocaml, designed for educational purposes to demonstrate compiler design (lexer, parser, semantic analysis, code generation). It compiles a subset of C to x86 assembly on POSIX systems.

## Features
- Lexer and recursive descent parser for basic C syntax (int, char, if, while, functions).
- Basic type checking and symbol table.
- Generates x86 assembly.
- Minimal dependencies (standard C libraries).

**Limitations**: No structs, arrays, pointers, or advanced features.

## Quick Start

### Prerequisites
- C compiler (GCC/Clang)
- POSIX environment (Linux/macOS; Windows via WSL/MinGW)
- Make (optional)

### Installation
```bash
git clone https://github.com/LuminaScript/Micro-C.git
cd Micro-C
make
