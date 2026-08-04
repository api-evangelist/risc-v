# RISC-V International

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
