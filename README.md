# Wasm and Move VM Fuzzing

> Differential and coverage-guided fuzzing of WebAssembly runtimes, Move VMs and gas metering beyond the EVM.

## Contents

<!-- toc:start -->
1. [Why Fuzz Virtual Machines](chapters/01-why-vm-fuzzing.md)
2. [Generating Valid Wasm Modules](chapters/02-generating-valid-wasm.md)
3. [Differential Runtime Testing](chapters/03-differential-runtime-testing.md)
4. [Fuzzing the Move VM and Bytecode Verifier](chapters/04-move-vm-and-verifier.md)
5. [Gas Metering Bugs](chapters/05-gas-metering-bugs.md)
6. [Running a VM Fuzzing Campaign](chapters/06-running-a-vm-fuzzing-campaign.md)
<!-- toc:end -->

## How to read this

Read chapters in order, or jump to what you need. Every chapter ends with exercises and further reading. See [RESOURCES.md](RESOURCES.md) and [GLOSSARY.md](GLOSSARY.md).

## Build

```bash
mdbook serve   # optional: renders SUMMARY.md as a website
```

## License

Text: CC BY-SA 4.0. Code snippets: MIT. See [LICENSE](LICENSE).
