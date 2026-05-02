# RISC-V International

RISC-V International advances the RISC-V open standard instruction set architecture (ISA), promoting open hardware development and reducing dependency on proprietary processor designs. The organization maintains the canonical RISC-V ISA specifications, profiles, non-ISA specifications, extensions, and a rich ecosystem of open-source tools including simulators, compilers, debuggers, and verification frameworks.

## Specifications and Resources

### RISC-V ISA Specifications
The canonical RISC-V Instruction Set Architecture specifications including the Unprivileged ISA (RV32I/RV64I) and Privileged Architecture specification. Freely available as ratified standards.

- **Documentation:** https://riscv.org/technical/specifications/
- **GitHub:** https://github.com/riscv/riscv-isa-manual
- **Machine-readable DB:** https://github.com/riscv/riscv-unified-db

### RISC-V C API Documentation
Documentation of the RISC-V C API including calling conventions, ABI specifications, and compiler intrinsics.

- **GitHub:** https://github.com/riscv-non-isa/riscv-c-api-doc

### RISC-V Non-ISA Specifications
Supporting technical standards covering debug, trace, platform specifications, and interface standards.

- **GitHub Org:** https://github.com/riscv-non-isa

### RISC-V Spike ISA Simulator
The official RISC-V ISA Simulator and golden reference implementation.

- **GitHub:** https://github.com/riscv-software-src/riscv-isa-sim

### OpenSBI
The official open-source RISC-V Supervisor Binary Interface implementation, serving as firmware for RISC-V Linux systems.

- **GitHub:** https://github.com/riscv-software-src/opensbi

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [risc-v-specification-schema.json](json-schema/risc-v-specification-schema.json) | RISC-V specification document structure |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [risc-v-specification-structure.json](json-structure/risc-v-specification-structure.json) | Field documentation for specification records |

## JSON-LD

| Context | Description |
|---------|-------------|
| [risc-v-context.jsonld](json-ld/risc-v-context.jsonld) | Linked data context for RISC-V ISA and specification entities |

## Vocabulary

- [risc-v-vocabulary.yml](vocabulary/risc-v-vocabulary.yml) — Normative vocabulary for the RISC-V ISA covering architecture concepts, privilege levels, and standards process

## GitHub Organizations

| Organization | Description |
|-------------|-------------|
| [riscv](https://github.com/riscv) | ISA specifications and core documents |
| [riscv-non-isa](https://github.com/riscv-non-isa) | Non-ISA specifications (debug, trace, SBI, C API) |
| [riscv-software-src](https://github.com/riscv-software-src) | Software tools (Spike simulator, OpenSBI, tests) |

## Links

- **Website:** https://riscv.org/
- **Technical Specifications:** https://riscv.org/technical/specifications/
- **Wiki:** https://wiki.riscv.org/
- **Member Portal:** https://members.riscv.org/
