# TLA Plus Foundation (tla-plus-foundation)
The TLA+ Foundation is an independent nonprofit hosted by the Linux Foundation, dedicated to fostering the adoption of the TLA+ specification language in industry, academia, and education. Created by Leslie Lamport, TLA+ is a high-level formal specification language based on set theory and temporal logic for modeling concurrent and distributed systems. Inaugural members include Amazon Web Services (AWS) and Oracle. The Foundation funds research and development, maintains the TLC model checker, TLAPS proof system, and TLA+ Toolbox IDE, and coordinates community resources including the VS Code extension, CommunityModules, and formal verification examples. The current stable release is v1.7.4 (The Xenophanes release).

**URL:** [https://foundation.tlapl.us/](https://foundation.tlapl.us/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Formal Methods, Linux Foundation, Specifications, Verification, Distributed Systems, Concurrency

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## APIs

### TLC Model Checker
TLC is the primary model checker for specifications written in TLA+. It can be run from the command line using tla2tools.jar or consumed as a Java dependency via Maven from central.sonatype.org. Requires Java 11+. The current stable release is v1.7.4 (The Xenophanes release) with pre-release v1.8.0 (The Clarke release) available.

**Human URL:** [https://github.com/tlaplus/tlaplus](https://github.com/tlaplus/tlaplus)

#### Tags:

 - Model Checking, Formal Verification, Java

#### Properties

- [Documentation](https://tla.msr-inria.inria.fr/tlatoolbox/doc/model/executing-tlc.html)
- [GitHubRepository](https://github.com/tlaplus/tlaplus)

### TLAPS Proof System
The TLA+ Proof Manager (TLAPS) is a proof system for TLA+ specifications, enabling formal mathematical proofs of system properties. It integrates with back-end provers and supports interactive proof development.

**Human URL:** [https://tla.msr-inria.inria.fr/tlaps/](https://tla.msr-inria.inria.fr/tlaps/)

#### Tags:

 - Proof System, Formal Verification, Mathematics

#### Properties

- [Documentation](https://tla.msr-inria.inria.fr/tlaps/)
- [GitHubRepository](https://github.com/tlaplus/tlapm)

### TLA+ Toolbox IDE
The TLA+ Toolbox is a full-featured IDE for writing TLA+ specifications, running TLC model checks, and managing proofs with TLAPS. Available as a standalone Eclipse-based application.

**Human URL:** [https://github.com/tlaplus/tlaplus](https://github.com/tlaplus/tlaplus)

#### Tags:

 - IDE, Tooling, Development

#### Properties

- [Documentation](https://tla.msr-inria.inria.fr/tlatoolbox/doc/)
- [GitHubRepository](https://github.com/tlaplus/tlaplus)

### TLA+ VS Code Extension
The official TLA+ extension for Visual Studio Code providing language support, syntax highlighting, TLC integration, and model checking from within the VS Code editor.

**Human URL:** [https://marketplace.visualstudio.com/items?itemName=alygin.vscode-tlaplus](https://marketplace.visualstudio.com/items?itemName=alygin.vscode-tlaplus)

#### Tags:

 - IDE, VS Code, Tooling

#### Properties

- [Documentation](https://github.com/tlaplus/vscode-tlaplus)
- [GitHubRepository](https://github.com/tlaplus/vscode-tlaplus)

### TLA+ Community Modules
A curated collection of TLA+ snippets, operators, and modules contributed by the TLA+ community, providing reusable formal specification components for common patterns in concurrent and distributed systems.

**Human URL:** [https://github.com/tlaplus/CommunityModules](https://github.com/tlaplus/CommunityModules)

#### Tags:

 - Community, Modules, Specifications

#### Properties

- [Documentation](https://github.com/tlaplus/CommunityModules)
- [GitHubRepository](https://github.com/tlaplus/CommunityModules)

### TLA+ Specification Examples
A collection of TLA+ specifications of varying complexity covering distributed algorithms, consensus protocols, concurrent data structures, and system models. Includes reference implementations for learning and validation.

**Human URL:** [https://github.com/tlaplus/Examples](https://github.com/tlaplus/Examples)

#### Tags:

 - Examples, Specifications, Learning

#### Properties

- [Documentation](https://github.com/tlaplus/Examples)
- [GitHubRepository](https://github.com/tlaplus/Examples)

## Common Properties

- [Website](https://foundation.tlapl.us/)
- [Documentation](https://lamport.azurewebsites.net/tla/tla.html)
- [GitHubOrganization](https://github.com/tlaplus)
- [Support](mailto:support@tlapl.us)

## Features

| Name | Description |
|------|-------------|
| TLC Model Checker | Explicit-state model checker for TLA+ specifications supporting both exhaustive verification and simulation modes. |
| TLAPS Proof System | Interactive proof manager for formally verifying TLA+ specifications against mathematical proofs. |
| TLA+ Toolbox IDE | Eclipse-based IDE for writing, model-checking, and managing TLA+ specifications with TLAPS integration. |
| VS Code Extension | Official Visual Studio Code extension providing TLA+ language support and TLC integration. |
| Community Modules | Reusable TLA+ operator and module library contributed and maintained by the community. |
| Grant Program | Foundation grants funding research and industry initiatives to advance TLA+ specification and tool adoption. |
| Maven Package Distribution | TLA+ tools available as Maven Java dependency from central.sonatype.org for programmatic integration. |
| PlusPy Python Interpreter | Python interpreter for executing TLA+ specifications, enabling Python-based formal modeling workflows. |

## Use Cases

| Name | Description |
|------|-------------|
| Distributed Algorithm Verification | Model-check distributed consensus, replication, and coordination protocols against safety and liveness properties. |
| Concurrent System Specification | Formally specify concurrent data structures, lock-free algorithms, and parallel systems using TLA+. |
| Protocol Design and Validation | Use TLA+ to design and validate network protocols, database transactions, and API contracts before implementation. |
| Tooling Integration via Java API | Embed TLC model checking in CI/CD pipelines or custom tools using the tla2tools Maven dependency. |
| Education and Training | Use the TLA+ Toolbox, VS Code extension, and Leslie Lamport's video course to learn formal methods. |
| Safety and Liveness Proof | Use TLAPS to produce machine-checked proofs of safety and liveness properties for critical systems. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon Web Services | Founding member; AWS uses TLA+ for distributed systems design including DynamoDB and S3 protocols. |
| Oracle | Founding member; uses TLA+ for database and distributed system specification. |
| Microsoft | Early TLA+ adopter for Azure and distributed systems formal verification. |
| Visual Studio Code | Official VS Code extension for TLA+ editing and model checking. |
| Maven Central | TLA+ tools distributed as Java Maven dependency for programmatic integration. |
| Linux Foundation | Parent organization hosting the TLA+ Foundation as an independent nonprofit project. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
