# Two-Phase Model of Intelligence (Working Hypothesis)

## 1. Overview

This note proposes a working hypothesis that intelligence can be modeled as a two-phase iterative process:

* **Phase 1: Stochastic Hypothesis Generation**
* **Phase 2: Constraint-Based Validation / Execution**

Intelligence emerges from the continuous interaction between these two phases rather than from either component alone.

---

## 2. Phase 1 — Stochastic Generation

Phase 1 is a probabilistic exploration process over a hypothesis space.

Characteristics:

* High entropy / exploratory
* Pattern-based inference
* Heuristic-driven
* Non-deterministic trajectory
* Produces candidate explanations, solutions, or plans

This phase is structurally similar to next-token prediction systems, where outputs are drawn from a learned distribution over plausible continuations.

Functionally, Phase 1 answers:

> “What might be a possible solution?”

---

## 3. Phase 2 — Constraint-Based Validation

Phase 2 performs structured evaluation of candidate outputs from Phase 1.

Characteristics:

* Low entropy / high constraint
* Invariant preservation
* Logical or formal consistency checking
* Stepwise validation or rejection
* Strong emphasis on correctness over plausibility

This phase is responsible for filtering, correcting, or rejecting outputs generated in Phase 1.

Functionally, Phase 2 answers:

> “Is this solution valid under the given constraints?”

---

## 4. Iterative Coupling

Intelligence arises from iterative coupling:

1. Phase 1 generates candidate hypotheses
2. Phase 2 evaluates and constrains them
3. Feedback from Phase 2 reshapes Phase 1 distribution
4. Repeat until convergence

This can be abstracted as:

[
H_{t+1} \sim P(H \mid feedback_{t})
]

---

## 5. Key Hypothesis

A central claim of this model is:

> Human intelligence implements both Phase 1 and Phase 2 internally as a tightly coupled system.

In contrast, current large language models appear to strongly implement Phase 1-like behavior, while Phase 2 behavior is partially externalized or approximated.

---

## 6. Repeatability Criterion for Phase 2

A proposed empirical criterion for Phase 2 behavior:

> Given identical input and constraints, a true Phase 2 system should converge to consistent correctness-class outputs.

Note: this does not require identical reasoning traces, but requires stable invariant preservation and verifiable correctness.

---

## 7. Interpretation of Current LLMs

Under this framework:

* LLMs are strong Phase 1 systems (hypothesis generators)
* Phase 2 behavior is weak, inconsistent, or externally scaffolded
* Apparent reasoning is often distributional imitation of reasoning structure rather than execution of a symbolic procedure

This leads to behavior that can resemble reasoning without guaranteeing internal consistency.

---

## 8. Open Questions

* Can Phase 2 emerge from sufficiently large Phase 1 systems?
* Is Phase 2 fundamentally symbolic, or can it be implemented as constrained probabilistic computation?
* Is “formal reasoning” an internal mechanism or an emergent constraint satisfaction property?

---

## 9. Summary

Intelligence may not be a monolithic reasoning system, but rather a feedback loop between:

* Generative stochastic exploration (Phase 1)
* Constraint-driven validation (Phase 2)

The strength of an intelligent system may depend less on either phase individually, and more on the stability and tight coupling of the loop between them.
