# Glossary

- **Ability (Move):** a type permission (`copy`, `drop`, `store`, `key`) checked by the verifier.
- **Bulk memory:** Wasm instructions such as `memory.fill` and `memory.copy` whose work scales with an operand.
- **Bytecode verifier:** checks bytecode for safety before execution (Move).
- **Canonical record:** a normalised summary of an execution (outcome, memory hash, fuel) used for differential comparison.
- **Chain split:** nodes disagreeing on execution results, producing divergent chain states.
- **Differential testing:** comparing implementations on the same inputs.
- **Fuel / gas:** metering units bounding execution.
- **JIT:** just-in-time compilation.
- **NaN canonicalisation:** forcing all NaN results to one bit pattern to remove permitted non-determinism.
- **Performance fuzzing:** fuzzing to maximise resource usage.
- **Shrinking:** reducing a failing input to a minimal one that still satisfies a predicate.
- **Trap:** an abnormal termination of Wasm execution (e.g. out-of-bounds access, divide by zero).
- **Wasm:** WebAssembly, a portable bytecode format.
- **WAT:** WebAssembly text format.
