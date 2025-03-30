# Tesla Harmonic Fork (THF)

A recursive prime-field sequence powered by Tesla’s 3-6-9 logic, prime-index spikes, and digit-based logic gates.

**Created by James McCann, 2025**

---

## Overview

The Tesla Harmonic Fork (THF) is a recursive integer sequence that grows rapidly and exhibits surprisingly structured behavior — including the natural emergence of prime substrings, palindromes, harmonic rhythm, and self-echoing digit zones.

It combines:
- Recursive concatenation
- Tesla-inspired digit logic (3, 6, 9)
- Prime-indexed mutation spikes

---

## Rule Definition

**Initial terms:**# Tesla-harmonic-fork
**For n ≥ 4:**

If `n` is a **prime index**:
- Look at the **last digit of aₙ₋₁**:
  - If `3` → multiply concat[aₙ₋₃, aₙ₋₂, aₙ₋₁] by `3ⁿ`
  - If `6` → **reverse** the concat before multiplying by `3ⁿ`
  - If `9` → multiply concat[...] by **(length of aₙ₋₁)²**

Else:
- `aₙ = concat[aₙ₋₃, aₙ₋₂, aₙ₋₁]` (no multiplier)

---

## Why It Matters

This isn’t just a novelty sequence.

**In this system:**
- Prime substrings naturally emerge (thousands per term)
- Palindromic primes and 369-patterns appear around harmonic spikes
- Every 27 terms (a₂₇, a₅₄, a₈₁...) act as **resonant prime bursts**
- Prime substring length increases over time (up to 26 digits found)

---

## Prime Density Graph

This chart shows how the number of prime substrings and the longest prime found evolves across the first 81 terms.

![Prime Density Graph](visuals/prime_density_graph.png)

---

## Contents

- `thf_engine.py` – code that generates THF terms with logic gates
- `thf_terms_sample.json` – example outputs (a₁ to a₈₁)
- `prime_density_data.csv` – prime substring statistics
- `visuals/` – graphs, spiral maps, and highlights
- `README.md` – this file

---

## Author

James McCann  
2025  
Built in collaboration with GPT-4 Turbo

---

## License

MIT – share, remix, explore.
