<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->
# Awesome Model checking

Finite-state, symbolic, temporal, probabilistic and refinement-oriented model checking. These techniques may return traces, invariants, bounded witnesses or numerical approximations rather than theorem-prover proofs.

**Status:** starter collection, 2026-11-15. Curator: unassigned. These are independently written short annotations of external resources; no benchmark, integration, solver invocation or checker execution has been performed for this starter.

## Learn and get started

- [TLA+ tools / TLC](https://github.com/tlaplus/tlaplus) — Read the toolchain and TLC execution options; exhaustive exploration depends on a finite model.
- [TLA+ project](https://lamport.azurewebsites.net/tla/tla.html) — Specification principles, practical examples and learning materials.
- [Alloy Analyzer](https://alloytools.org/) — Explore relational specifications and scope-limited model finding.

## References and implementations

- [SPIN](https://spinroot.com/spin/whatispin.html) — Promela/LTL explicit-state verification and counterexample traces.
- [PRISM](https://www.prismmodelchecker.org/) — Quantitative probabilistic model checking with explicit modeling assumptions.
- [ProB](https://prob.hhu.de/) — Model checking and animation for B-family and Event-B specifications.

## Benchmark, examples and community paths

- [UPPAAL](https://uppaal.org/) — Timed-automata verification; check edition, licensing and model semantics.
- [Apalache](https://apalache-mc.org/) — Symbolic checking for TLA+ specifications; compare the explored scope with TLC.

## First exercise — not executed here

Model a small mutual-exclusion system, state an invariant and then introduce an error to observe a counterexample. Record bounds, fairness assumptions and the tool's exact semantics.

## Evidence and interoperability

Bounded absence of a counterexample is not a global proof. Distinguish finite-state exhaustion, symbolic overapproximation, probabilistic estimates and infinite-state theorem proof.

Capture provenance (source commit, tool and checker versions, flags, inputs, assumptions, certificate formats, output status, elapsed time, licence) before using an entry in a research/assurance claim.

## Upstream survey, curation and contribution

A preliminary survey on 2026-11-15 compared broader resources such as [awesome-formal-verification](https://github.com/hohieuai/awesome-formal-verification), [formal-verification-resources](https://github.com/astrio-labs/formal-verification-resources), plus canonical projects above. This is not an exhaustive survey and no external descriptions were imported. The focused value here is evidence-aware navigation and links from the [ECHIDNA coverage ledger](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/CATALOGUE.adoc). Inclusion is not an endorsement, and upstream materials retain their respective licences.

Contribute fixes and additional learning material through an [issue](https://github.com/stuff-of-awe/awesome-model-checking/issues) or [PR](https://github.com/stuff-of-awe/awesome-model-checking/pulls); see [maintenance policy](https://github.com/stuff-of-awe/.github/blob/main/docs/collections/MAINTENANCE.adoc). Original annotations are CC-BY-SA-4.0. Collectors and maintainers are invited; quarterly review is a goal, not evidence of actual review.
