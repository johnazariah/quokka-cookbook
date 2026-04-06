---
hide:
  - navigation
---

# The Quokka Cookbook

<div class="grid" markdown>

**Quantum computing recipes you can actually run.** No framework bloat. No 47 imports. Just circuits, explained — then executed.

</div>

---

## The idea

Most quantum computing resources teach you qubits and gates, then leave you stranded somewhere around phase kickback wondering *why you should care*.

We do it the other way around. Each recipe starts with a **problem** — something concrete and interesting — then builds the quantum circuit that solves it, step by step, in standard [OpenQASM 2.0](https://openqasm.com/). Every recipe runs on [Quokka](https://www.quokkacomputing.com/) — a 30-qubit quantum computing system you can hold in your hand.

**Clone it. Read it. Run it on your Quokka.**

```bash
git clone https://github.com/johnazariah/quokka-cookbook
```

Open any `.qasm` file, paste it into your Quokka, and see the results.

!!! tip "How each recipe works"

    Every recipe follows the same structure:

    1. **What are we making?** — the problem, in plain language
    2. **Ingredients** — what you need to know (with links if you need a refresher)
    3. **Method** — the circuit, built incrementally with explanation at every step
    4. **Taste test** — run it, see the output, interpret the results
    5. **Chef's notes** — gotchas, deeper connections, and what to try next

## Start cooking

<div class="grid cards" markdown>

-   :material-silverware-fork-knife:{ .lg .middle } **Appetizers**

    ---

    The fundamentals: entanglement, teleportation, your first quantum speedup.

    [:octicons-arrow-right-24: Bell State](recipes/01-bell-state/README.md)

-   :material-book-open-variant:{ .lg .middle } **Learning Path**

    ---

    Not sure where to start? Follow the guided path from zero to quantum algorithms.

    [:octicons-arrow-right-24: Show me the way](learning-path.md)

-   :material-bookshelf:{ .lg .middle } **References**

    ---

    Textbooks, papers, courses, and talks — curated recommendations for going deeper.

    [:octicons-arrow-right-24: Further reading](references.md)

-   :material-github:{ .lg .middle } **Contribute**

    ---

    Found a bug? Want to add a recipe? Every recipe is a PR away.

    [:octicons-arrow-right-24: GitHub](https://github.com/johnazariah/quokka-cookbook)

</div>

## Who is this for?

- **Students** taking a quantum computing course who want a hands-on companion
- **Software engineers** curious about quantum computing but allergic to hype
- **Researchers** who want a quick reference for standard circuits and protocols
- **Anyone** who learns by doing rather than by reading axioms

No physics degree required. We introduce every concept when it's needed, in the context of a working circuit. If you can read a `for` loop, you can read a quantum circuit.

## What is Quokka?

[Quokka](https://www.quokkacomputing.com/) is a 30-qubit quantum computing system built by [Eigensystems](https://www.quokkacomputing.com/) in Australia. It's a physical device — a puck that fits in your hand — with a companion app ([iOS](https://apps.apple.com/au/app/quokka-quantum/id6754873585)) and cloud platform. Design circuits, load them onto your Quokka, and see the results. It runs standard OpenQASM 2.0, so there's no proprietary language to learn.

Every `.qasm` file in this cookbook is a valid OpenQASM 2.0 program. If you want to go beyond Quokka, the same files run on IBM Quantum, Qiskit, or any other QASM-compatible platform. **Your learning is portable.**

