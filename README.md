# 🧬 Evolutionary Mjolnir 🔨

**Evolutionary Mjolnir** is a protein design tool that combines **Rosetta** and **ESM2** to identify and fix energetically unfavorable residues in protein structures. Inspired by the idea of "hammering down" high-energy contributions, the tool uses evolutionary insights to propose stabilizing mutations — just like Mjolnir striking down a protruding nail.

---

## ✨ Concept

Many protein design workflows rely on physics-based models (like Rosetta) or machine learning-based sequence models (like ESM2). Evolutionary Mjolnir integrates the strengths of both:

1. **Rosetta** detects residues with unfavorable energetic contributions in the context of the protein structure.
2. **ESM2**, a protein language model trained on evolutionary data, suggests plausible substitutions at these positions.

The result? A guided, evolution-aware mutational strategy for protein stabilization and redesign.

