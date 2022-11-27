# Grain Playground

This project serves as a playground for exploring this [Grain](https://grain-lang.org/) programming language.

## Prerequisites

Ensure the following requirements are met prior to usage:

- Node.js 14 or higher
- Grain [installed](https://grain-lang.org/docs/getting_grain)
- Wasm3 [installed](https://github.com/wasm3/wasm3/blob/main/docs/Installation.md) (optional)

## Exercises

The OCmal [exercises](https://ocaml.org/problems) are solved in Grain and are used as a means to explore Grain syntax, semantics, and idioms.

## Run

```
grain main.gr
```

### Wasm3

The Grain compiler generates WebAssembly (WASM) binaries that can be executed by a WASM interpreter.

The following command assumes that the [Wasm3](https://github.com/wasm3/wasm3) interpreter is installed:

```
wasm3 main.gr.wasm
```
