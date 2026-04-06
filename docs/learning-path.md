# Learning Path

A guided route through the recipes, from zero to quantum algorithms. Follow this if you're new and want a structured progression.

---

## Stage 1: The basics

*What's a qubit? What's a gate? What does measurement mean?*

These recipes build your intuition for the three things that make quantum computing different: **superposition**, **entanglement**, and **measurement**.

| Order | Recipe | Key concept |
|-------|--------|-------------|
| 1 | [Bell State](recipes/01-bell-state/README.md) | Entanglement — two qubits, perfectly correlated |
| 2 | [Teleportation](recipes/02-teleportation/README.md) | Using entanglement as a resource to transmit quantum information |
| 3 | [Deutsch-Jozsa](recipes/03-deutsch-jozsa/README.md) | Your first quantum speedup — interference as computation |

!!! note "After Stage 1 you'll understand"
    - What qubits and gates actually do (not just the math — the *behaviour*)
    - Why entanglement is useful, not just spooky
    - How interference lets quantum computers answer questions in fewer steps

---

## Stage 2: Querying and searching

*How do you extract information from a quantum system?*

| Order | Recipe | Key concept |
|-------|--------|-------------|
| 4 | Bernstein-Vazirani | Querying a hidden structure with one question |
| 5 | Simon's Problem | Exponential speedup from structure in a function |
| 6 | Grover's Search (3 qubits) | Amplitude amplification — boosting the right answer |

!!! note "After Stage 2 you'll understand"
    - How oracles encode problems into quantum circuits
    - Why quantum speedups come from *structure*, not magic
    - The difference between quadratic and exponential advantage

---

## Stage 3: Real applications

*What can you actually compute?*

| Order | Recipe | Key concept |
|-------|--------|-------------|
| 7 | QAOA for MaxCut | Variational optimization on a graph |
| 8 | VQE for H₂ | Finding the ground-state energy of a molecule |
| 9 | Quantum Fourier Transform | The engine behind phase estimation and Shor's algorithm |

!!! note "After Stage 3 you'll understand"
    - How hybrid classical-quantum algorithms work
    - How quantum simulation connects to chemistry
    - What the QFT actually does and why it matters

---

## Stage 4: Deep cuts

*Advanced techniques for when you want the full picture.*

| Order | Recipe | Key concept |
|-------|--------|-------------|
| 10 | Quantum Phase Estimation | Precision measurement of eigenvalues |
| 11 | Error Mitigation (ZNE) | Making noisy results useful |
| 12 | Quantum Counting | Combining Grover with QPE |

---

## Philosophy

Each stage builds on the previous one, but every recipe is self-contained. If you already understand entanglement, skip to Stage 2. If you're here for VQE, jump straight to Stage 3 — links to prerequisite concepts are built into every recipe.

The goal is **understanding**, not coverage. We'd rather you deeply grasp six circuits than skim twenty.
