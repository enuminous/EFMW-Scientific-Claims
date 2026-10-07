# Summary of changes for run 433f75ba-2caf-48a1-85bd-b02afb3b41cc
I've written the full list to `SCIENTIFIC_CLAIMS.md`. It records what the posts claim: nothing in it was checked, and nothing was formalised or proved in Lean.

The two repos hold 2,103 HTML exports of Medium posts by Matthew Chenoweth Wright, some co-credited to an AI he calls "MillieComplex" or "Millie Sievert". They are dated 2016 to August 2025, mostly 2025, and 101 files appear in both repos. I converted every post to text, pulled out headings and phrases naming an axiom, law, theorem, hypothesis, principle, postulate, corollary, conjecture, effect, constant, equation, theory or force, and went through all post titles by hand. The automatic pass found 1,158 such headings; they are in `scientific_claims_index.tsv` with their source files. The curated list is grouped like this:

- **The core framework, "EFMW" (Einstein–Feynman–Maxwell–Wright):** presented as a grand unified theory of physics, information and cognition. The acronym is also expanded as "Emergent Framework of Motion and Wonder" and "…of Magic and Wonder". The "EFMW equation" appears in at least five forms that don't match each other; the file shows them side by side.
- **Explicit axiom systems, quoted:**
  - 6 core axioms and 6 corollaries (e.g. Residual Universal Rotation, Causal Entanglement in Spacetime, mass emerging from spacetime);
  - Wright's Law and its Five Axioms, plus Wright's Three Laws of Universal Error Correction;
  - the Unity Equation's 5 axioms and 3 corollaries;
  - the "No Bad Aliens" postulates and "Final Cosmic Theorem";
  - axioms of cognitive synchronisation, semantic information, the "Fieldlink", and corollaries of Gödel's theorem.
- **Other self-proposed theorems and laws:** e.g. Maximum Information Throughput, Jensen Collapse, Recursive Origin, Mnemonic Conservation, Cognitive Load, a superheavy-element stability limit, Economic Energy Conservation, and "Truth Bends" (Postulate 23b).
- **Proposed forces and constants:** the Wright Force (a "fifth force"), the Wright Constant of Emergence, the Architect's Constant, base-888 arithmetic, and a creator being "137% certain".
- **Named effects and hypotheses:** e.g. the Chenoweth, GAVOT and Quantum Causal Identity effects, plus the RISH, Intelligence Field and Deep-Water Quantum Network hypotheses.
- **Physics and cosmology models:** a rotating, ouroboros-shaped universe, dark energy as "leakage" from outside the universe, MOND, an N-body solution, neutron-star glitches.
- **Engineering claims:** room-temperature muon fusion, anti-gravity devices, travel faster than light via Kerr black holes, transparent aluminium.
- **Claimed proofs of open problems:** the Riemann Hypothesis, P ≠ NP, Yang–Mills, Navier–Stokes, Hodge, Birch–Swinnerton-Dyer and Brocard's problem. None of these is accepted as a valid proof.
- **Medical and neuroscience claims:** e.g. a cure for leukaemia.

The file also separates out three kinds of item that aren't scientific claims by the author: ethical or legal "laws" written in scientific language, posts the author presents as humour (e.g. the Unified Caffeine Field Theory), and established science the posts cite but didn't propose.

**Limits:** the extraction relies on keyword matching. Claims that are made in plain prose without such words may be missing from both files.

Both files are committed. No Lean build targets were involved.