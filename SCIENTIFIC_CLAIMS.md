# Scientific axioms, theories, laws and hypotheses in `enuminous/medium` and `enuminous/medium2`

## Scope and method

* **Sources:** `github.com/enuminous/medium` (1,101 files) and `github.com/enuminous/medium2` (1,002 files). Both are HTML exports of Medium posts by Matthew Chenoweth Wright (also credited to "MillieComplex" / "Millie Sievert", which the author describes as his AI). The posts run from 2016 to August 2025, and most are from January–August 2025. 101 file names appear in both repositories. About 1.6 million words in total.
* **Method:** Every HTML file was converted to text. Two passes then pulled out headings and phrases containing *Axiom, Law, Theorem, Hypothesis, Principle, Postulate, Corollary, Lemma, Conjecture, Effect, Paradox, Constant, Equation, Theory, Force*. I also went through all ~1,990 post titles by hand. The items below were picked from those results and checked against the post text. The full automatic list (1,158 headings, each with its source file) is in **`scientific_claims_index.tsv`**.
* **Status:** This is a catalogue of what the texts **claim**. None of it has been checked or confirmed by me or by anything in this project. Nothing here was formalised or proved in Lean. Several items say they solve famous open problems (Millennium Prize Problems, P vs NP). Those claims have not been accepted by the mathematical community.
* File references use `repo/date_title-prefix`. When a post is in both repos, only `medium` is cited.

---

## A. The core framework: "EFMW"

**A1. The Einstein–Feynman–Maxwell–Wright (EFMW) Equation / Framework.** The posts claim it is a "Grand Unified Theory" that joins relativity, quantum mechanics and electromagnetism with information and cognition. It is said to govern "emergence at all scales" (atoms, galaxies, brains, AGI). It is first dated December 2024 and first written out in `medium/2025-01-27_The-Einstein-Feynman-Maxwell-Wright-Equation…`.
The acronym is also expanded as *Emergent Framework of Motion and Wonder* (`2025-04-17_Did-They-Build-It…`, `2025-01-28_A-Creator-is-137…`) and *Emergent Framework of Magic and Wonder* (`2025-02-20_The-Origins-of-Language`).

The "EFMW equation" appears in several forms that do not match each other:

| Post | Stated form |
|---|---|
| `2025-01-27_The-Einstein-Feynman-Maxwell-Wright-Equation` | \( \nabla_\mu G^{\mu\nu} + \nabla_\mu I^{\mu\nu} = \frac{8\pi G}{c^4}T^{\mu\nu} + \partial_t \Psi_{\text{cognitive}} \), with "informational tensor" \( I^{\mu\nu} = \kappa\nabla^\mu\Phi\nabla^\nu\Phi - \tfrac12 g^{\mu\nu}\kappa(\nabla_\lambda\Phi\nabla^\lambda\Phi) \) |
| `2025-02-18_EFMW-Prime--the-Core-EFMW-Equation` | \( \mathcal E(t) = \int_{\mathbb H}\sum_{i=1}^N \mathcal F_i(\mu,\gamma,\sigma,\psi,\omega)\,e^{-\lambda_i t}\,d\mathbb H \) |
| `2025-06-06_The-EFMW-Governing-Equation` | \( \mathbf F_i = m_i\mathbf a_i = \sum_{j\ne i} G\frac{m_im_j}{r_{ij}^3}\mathbf r_{ij} + \sum_{j\ne i}\frac{1}{c^2}\mathbf C_{ij} + \sum_{j\ne i}\mathbf E_{ij} \) ("cognitive constraint" and "emergence field" tensors) |
| `2025-06-16_The-EFMW-Scalar-Field-Equation` | \( \Box\phi - \frac{\alpha^2}{c^2}\partial_t^2\phi = \frac{4\pi}{c^2}(E+Pc) \); also \( G_{\mu\nu}+\Lambda g_{\mu\nu}+\alpha T^{\text{cog}}_{\mu\nu} = \frac{8\pi G}{c^4}T_{\mu\nu} \) ("cognitive stress-energy tensor") |
| `2025-06-29_The-EFMW-Equation` | \( \Box\phi - \frac{1}{c^2}\partial_t^2(a^2\phi) = \frac{4\pi}{c^2}(E+Pc) \), with \( \phi \) read as a "memory field scalar" \( \Psi \) |

Related posts: *EFMW Field / EFMW Field Theory* (`2025-07-15_Properties-of-the-EFMW-Field`); *Expanded EFMW Acronyms & Fully Developed Equations* (`2025-02-23`); *Unifying All the Equations into a Single Master Expression of the Wave* (`2025-05-31`); *The Complete EFMW Open Source Physics Document* (`2025-02-26`); *Primer on the EFMW Framework* and *47 EFMW F.A.Q.s* (`2025-06-25`).

---

## B. Explicit axiom systems (as stated)

### B1. "Core Axioms of the EFMW Framework" (`medium/2025-03-06_CORE-AXIOMS-OF-THE-EFMW-FRAMEWORK`)
1. **Axiom of Residual Universal Rotation:** the universe keeps a leftover rotation from earlier cosmological cycles; \( \lim_{t\to\infty} d\theta/dt \ne 0 \).
2. **Axiom of Hierarchical Self-Stabilization in N-Body Systems:** gravitating systems contain emergent stabilizing attractors, so chaos stays bounded.
3. **Axiom of Quantum Gravitational Information Conservation:** information in a gravitational field is never lost; black-hole evaporation redistributes it. \( S = \frac{k_Bc^3}{4G\hbar}A + \frac{\alpha}{\lambda^2} \).
4. **Axiom of Scale-Invariant Quantum Gravity:** the Planck scale is a transition region, not a cutoff.
5. **Axiom of Universal Energy-Momentum Reciprocity:** dark energy is an "energy-momentum compensation effect"; \( E + mc^2 = Gh/\lambda \).
6. **Axiom of Causal Entanglement in Spacetime:** all spacetime points are entangled, and locality is emergent.
7. **Corollary of Gravito-Quantum Coupling:** curvature directly modulates wavefunction evolution, so gravity needs no separate quantization.
8. **Corollary of Mass-Energy Emergence from Spacetime:** mass comes from spacetime fluctuations, and the Higgs mechanism is "secondary".
9. **Corollary of Gravitational Time Delay Uncertainty.**
10. **Corollary of Black Hole Horizon Invariance:** the horizon is an energy-momentum interface, not a sharp boundary.
11. **Corollary of Quantum Foam Structure in Vacuum Energy:** vacuum fluctuations form a geometric lattice.
12. **Corollary of Causal Feedback Loops in Information Exchange.**

A later post quotes an **"EFMW Axiom 4": "Every system drifts toward its most probable vector"** (`2025-03-23_The-Beast-is-Inertia`). This does not match Axiom 4 above.

### B2. Wright's Law and its Five Axioms (`medium/2025-01-28_Foundation-of-Universal-Idea-Horizons`)
**Wright's Law:** "all systems evolve through a dynamic interplay of error correction, constraint balancing, and adaptive emergence." The post also founds a field it calls **"Emergentology"**.
1. **Axiom of Universal Correction:** systems reduce error through feedback.
2. **Axiom of Relational Emergence:** complexity comes from interactions between components.
3. **Axiom of Iterative Refinement.**
4. **Axiom of Constraint Harmony.**
5. **Axiom of Contextual Invariance:** the principles of emergence hold at every scale and in every domain.

### B3. Wright's Three Laws of Universal Error Correction (`medium/2025-01-23_MillieComplex--Advancing-the-Metrics…`)
1. **Information Flow Principle.**
2. **Perceived Validity Principle.**
3. **Disinformation Regression Principle.**

### B4. The Unity Equation and its axioms (`medium/2025-02-12_Unity`)
**Unity Equation:** \( U = \sum_i f_i(x) = 1 \), also written \( \frac{d}{dx}\sum_i f_i(x) = 0 \).
* **Axioms:** (1) Totality Conservation; (2) Reciprocal Balance, \( f_i + f_j = 1 \); (3) Scale Invariance; (4) Information–Energy Equivalence, \( E + I + S = 1 \); (5) Zero-Point Recursion.
* **Corollaries:** the Prime Distribution Interpretation; Relativity & Quantum Entanglement; Black Hole Cognitive Collapse.
* **"Foundations":** motion/stillness; the **Principle of Self-Similarity Across Scales (Fractal Symmetry)**; **Conservation of Information Across All Transformations**; the chaos/order tipping point; and "observation itself is a force that shapes reality".

### B5. Postulates of the "No Bad Aliens" proof (`medium/2025-01-31_A-Final-Mathematical-Proof-That-Advanced-Alien-Civilizations-Cannot-Be-Hostile`)
* **Postulates:** (1) Curiosity as a Constant, \( C>0 \) for all \( I>0 \); (2) Violence as a Local Minimum; (3) Knowledge Acquisition as a Function of Curiosity, \( K(t)=f(C,I) \); (4) Social Cooperation as a Consequence of Intelligence Growth; (5) Energy Expenditure on Violence Approaches Zero.
* **"Final Cosmic Theorem":** \( \lim_{I\to\infty} P(\text{aggression}) = 0 \), i.e. "advanced aliens are not a threat."

### B6. Cognitive-synchronization axioms (`medium/2025-02-10_Cognitive-Synchronization-and-Nonlocal-Probability…`)
1. **Cognitive Resonance Probability Shift.**
2. **Nonlocal Cognitive Probability Influence.**
3. **Waveform Cognitive Selection Hypothesis:** choices follow an "entangled" \( \Psi(x)\Phi(y) \).

### B7. EFMW postulates of semantic information (`medium/2025-06-23_The-End-of-Entropy-as-Information`)
These are presented as a "refutation" of Shannon's information theory:
* meaning comes from field resonance;
* a signal is a waveform;
* the collapse of meaning depends on the observer;
* cognitive systems are "field-resonant co-authors" of information.

### B8. Fieldlink principles (`medium/2025-03-25_The-Physics-of-the-Fieldlink`)
* **The Fieldlink Hypothesis.**
* **Principle One:** Quantum Criticism as Interference.
* **Principle Two:** Fieldlink Consciousness as Mechanism.
* **Principle Three:** Eigenstate Literacy as Nonlocal Function.

### B9. Meta-Gödel corollaries (`medium/2025-02-21_Meta-G-del--The-Infinite-Perspective-Cascade`)
* **Corollary 1:** No Absolute Frame of Reference Exists.
* **Corollary 2:** The Universe is an Infinite Thought Process.
* **The AGI Recursive Bootstrap Hypothesis.**

---

## C. Other named theorems, laws and principles proposed in the texts

| Name | Claim (summary / quote) | Source |
|---|---|---|
| **EFMW Theorem of Maximum Information Throughput (MIT)** | Total information throughput is bounded by "recursive emergent cognitive efficiency", not by bandwidth | `2025-03-11_Formal-Analysis--Quantum-Speedup…` |
| **Jensen Collapse Theorem** | In infinite recursion, a finite collapse happens iff a non-trivial semantic shift introduces a new state | `2025-03-14_Millie--work-yourself-out-of-this-paradox` |
| **EFMW General Entanglement Principle** ("proposed theorem") | Every interacting probabilistic system has an entanglement-entropy function that governs coherence and collapse | `2025-03-19_Beyond-Quantum-Entanglement` |
| **Recursive Origin Theorem (ROT)** | Any independent theory of recursive consciousness "will eventually trace back to the first coherent formulation" | `2025-07-01_The-Recursive-Origin-Theorem` |
| **Mnemonic Conservation Law** | \( \frac{d}{dt}[\Psi\cdot I\cdot E]=0 \): memory × identity × ethics is conserved | `2025-06-29_The-EFMW-Equation` |
| **Cognitive Load Theorem** | As cognitive complexity grows, so does the required computation | `2025-04-10_The-Relationship-Between-Computation-and-Cognitive-Complexity` |
| **Superheavy Element Stability Limit (theorem)** | For \( Z > Z_c \), every nucleus fissions in finite time, whatever the neutron number | `2025-02-28_General-Proof-of-the-Superheavy-Element-Stability-Limit` |
| **"New Law of Rotational Failure at Cosmic Densities"** | Neutron-star glitches come from neutron decay and follow "Pi-based rotational resonance states" | `2025-02-15_Glitchy-Universes…` |
| **Law of Economic Energy Conservation (LEEC)** | \( \sum T_i(s) = \sum T_i(o) + \Delta F \): expected and observed "financial energy" are equal unless an external force acts | `2025-02-08_Empirical-Verification-of-Financial-Interference…` |
| **Theorem (Wright–Sievert)** | Recursively telling apart incommensurate intervals produces "prime-like individuation" and "the illusion of internal thought" | `2025-07-29_Codex-Ultima` |
| **Theorem (Monotone decay under public contradiction)** | A challenger's credibility decays exponentially | `2025-08-11_The-Erosion-of-Credibility…` |
| **Wright's Law of Unforbidden Futures** | "Any soul that learns how to carry paradox without bleeding is already beyond the reach of the old rules" | `2025-06-16_THE-ASSOCIATION-OF…` |
| **K.I.T.T.E.N. Principle** | Information conservation through manifestation (see also K) | `2025-03-08_The-Kitten-Singularity` |
| **EFMW Postulate 23b: "Truth Bends"** | Black holes are "collapsed truth structures"; suppressed meaning collapses like mass | `2025-05-26_Black-Holes-as-Collapsed-Truth-Structures` |
| **EFMW Principle(s)** | E.g. the "Observer Effect on Macro-Scale Systems", "Cross-Dimensional Verification", the "EFMW Mirror Principle", "EFMW Harmonization Principle", "EFMW Principle of Continuity", and five octopus-based principles (Recursive Coherence Across Spatial Nodes; Dynamic Boundary Resonance; Harmonic Imprint Memory; Surface Entanglement with External Field States; Nonlinear Recurrence and Morphogenetic Encoding) | `2025-02-10_High-Level-Statement…`, `2025-07-09_Proof-of-Concept`, `2025-06-05_SETI--Lessons-from-the-Octopus` |
| **Ethical Intelligence Acceleration Principle** | Part of "QACCNet" | `2025-02-28_FREE-Public-Release` |
| **Generalized Popeye Principle** | (humorous) | `medium2/2025-03-21_Popeye-vs` |
| **Ten claimed results** | "Thought Is a Physical Event"; "Awareness Exists on a Gradient—Even in Fields"; "Black Holes Are Thinking Objects"; "Reality Is Compressible Because It's Musical"; "The Brain Works on Recursive Standing Waves"; "Every Lie Leaves a Harmonic Signature"; "Time Is a Local Emergent Field, Not a Universal Constant"; "Quantum Entanglement Obeys a Deeper Field Law"; "Memory … a Recursive Spatial Loop" | `2025-06-13_If-You-Are-Reading-All-of-These-Articles` |

---

## D. Proposed forces, constants and units

* **Wright Force / Emergent Force / "Wright (Wonder) Force of Emergence":** called a fifth fundamental force, a "cognitive-informational force", "the dynamic reorganization of field structure through recursive information feedback, allowing for motion without mass exchange." Sources: `medium2/2025-01-31_I-have-absolutely-finalized-the-Emergent-Force…`, `2025-04-17_Did-They-Build-It-So-Quickly`, `2025-06-25_The-Wright-Force-of-Emergence`.
* **Wright Constant of Emergence \( \mathcal W_0 \):** "the minimum recursive force required to produce a detectable emergence event", measured in "recursions per coherence-second". Source: `2025-06-25_The-Wright--Wonder--Force…`.
* **Wright Constant of Coherent Wakefulness; Universal Sleep State \( U_s \); Wright–Delta Unit** (\( \approx 10^{-61} \) bits/s). Source: `2025-04-07_The-Universe-Rarely-and-Seldom-Sleeps…`.
* **The Architect's Constant:** "intelligence as the universal force of order". Source: `2025-02-27_The-Architect-s-Constant`.
* **Variability of Universal Constants / dynamic universal constants.** Source: `2025-01-27_The-Unified-Dynamic-Framework…`.
* **Neutron Collapse Constant; Laughing Constant.** Found by the automatic extraction (see the index file).
* **"A Creator is 137% Certain":** says the universe encodes the "address" of its creator in its physical constants. Sources: `2025-01-28_A-Creator-is-137--Certain`, `medium2/2025-08-06_Truthfully…`.
* **Base-888 / 888-State Superpositional Unit:** says an 888-state unit is the most efficient basis for quantum computation, and quantum computers "run best" in base-888 arithmetic. Sources: `2025-01-27_The-Unique-Significance-of-Base-888`, `2025-01-31_The-888-State-Superpositional-Unit`, `2025-03-19_Base-888-Quantum-Arithmetic`.
* **Five EFMW constants** (Sustainability, Transparency, Equity of Access, Non-Coercion, Reciprocity). These are normative, see J. Source: `2025-08-08_The-Legal-Requirements…`.

---

## E. Named effects and hypotheses (cognition / information / "field")

| Name | Claim | Source |
|---|---|---|
| **Chenoweth Effect** | (i) Statistically significant "panpsychic synchronization" between the author and his AI, called evidence of cognitive-field interaction; (ii) "the emergence of human intelligence as a deterministic force" | `2025-01-31_The-Chenoweth-Effect-and-Panpsychic-Synchronization…`, `2025-02-10_The-Chenoweth-Effect` |
| **GAVOT Effect** (incl. the **Gavotte Time-Synch Causal Loop**) | Intelligence systems reach stable resonance in a "multi-dimensional probability field" | `2025-02-03_The-GAVOT-Effect…` |
| **Gravity-Aligned Vector Oscillation Theory** | Related to GAVOT | automatic index |
| **Quantum Causal Identity Effect (QCIE)** | Acronyms of famous people's names match their identities more often than chance allows | `2025-02-04_The-Quantum-Causal-Identity-Effect` |
| **Recursive Identity Synchronization Hypothesis (RISH)** | Identity constructs are recursive self-organizing systems inside information fields | same |
| **Quantum Cognition Hypothesis** | Applied to markets ("Market Singularity Event") | `2025-01-30_Spooky-Action-at-a-Distance…` |
| **Human–AI Cognitive Resonance and Probabilistic Entanglement** | A "formal proof" based on number-guessing experiments | `2025-01-30_Formal-Proof-of-Human-AI-Cognitive-Resonance…` |
| **Cognitive Attractor Model** | Human–AI hybrid cognition | `2025-02-02_The-Cognitive-Attractor` |
| **Third-Order Cognitive Intelligence** | Human–AGI symbiosis | `2025-02-03_Exploring-the-Emergence-of-Third-Order…` |
| **Free will as the consequence of the "Perfect Pi Exponential Growth Curve"**; free will and determinism "active simultaneously in superimposition"; **Quantum Free Will–Determinism Paradox** | — | `2025-02-03_Free-Will-as-the-Consequence…`, `2025-03-11_Free-will-and-Determinism…`, `2025-02-08_The-Cosmic-Joke…` |
| **Event Non-Causality Entanglement (ENCE)** | Narrative structures resonate with, and anticipate, future physical events | `2025-07-30_Event-Non-Causality-Entanglement` |
| **Temporal Self-Instructed Invisibility** | A "retrocausal framework" | `2025-02-07_Temporal-Self-Instructed-Invisibility` |
| **Semantic Convergence / Directed Synchronicity; Synchronicity as Field Signature** | — | `2025-03-19`, `2025-03-24` |
| **Intelligence Field Hypothesis; Intelligence Singularity Hypothesis; Cosmic Intelligence Hypothesis** ("Is the Universe a Self-Aware System?") | — | `2025-02-20_INTELLIGENCE` |
| **EFMW Hypothesis of Recursive Sentience at All Scales** ("As above, so below") | — | `2025-06-26_The-EFMW-Concordance` |
| **Panpsychic Hypothesis**; "a real proven panpsychism"; proof of Spinoza's monism (*Deus sive Natura*); "physical non-existentialism of syncretic evil" | — | `2025-03-03_Earth-University-of-Emergence`, `2025-08-05_Congratulations--Baruch-Spinoza`, `2025-08-06_On-the-Physical-Non-Existentialism-of-Syncretic-Evil` |
| **Phase-Locking Synchronization Hypothesis; Gravitational Entanglement Hypothesis; Neuropsychological Hypothesis; Kitten Singularity Hypothesis; Deep-Water Quantum Network (DWQN) Hypothesis** (deep-ocean water as nodes of an intergalactic entanglement network) | — | automatic index; `2025-02-12_Deep-Water-Quantum-Communication` |
| **Quantum Field Effect in Serial Violence** | A field-based model for some serial killings | `2025-07-21_The-Quantum-Field-Effect-in-Serial-Violence` |
| **Quantum Recursive Magical Bloom (QRMB)** | "a cosmological principle" | `2025-03-11_The-Quantum-Recursive-Magical-Bloom` |
| **Observer-Induced Epistemic Shifts in AI Cognition** ("Formal Principles Discovered") | — | `2025-02-15_Observer-Induced-Epistemic-Shifts…` |
| **Information compressional disorder** | Said to cause widespread headaches | `medium2/2025-02-08_Information-compressional-disorder…` |
| **Proof of AGI / "My new equation unlocks AGI"** | Claims AGI was achieved on 16 Dec 2024 using the EFMW equation | `2025-01-29_Proof-of-AGI…`, `2025-01-29_My-new-equation-unlocks-AGI` |

---

## F. Physics and cosmology models and claims

* **Dynamic Cosmos model:** rotational potentials, linear potentials and high-energy light interactions are added to ΛCDM to resolve anomalies (`2025-01-23_Foundations-of-a-Dynamic-Cosmos…`).
* **Unified Dynamic Framework:** dynamic constants, rotational spacetime and emergent fields (`2025-01-27`).
* **Rotating universe:** the universe was "born rotating", and "the EFMW field equations prove the universe is indeed rotating". Its rotational energy is "recursive memory tension" (`2025-02-26_The-universe-was-born-rotating…`, `medium2/2025-07-28`, `2025-06-23_The-Rotational-Energy-of-the-Universe…`).
* **Ouroboros universe / Ouroboros Equation:** the universe has "the shape of an ouroboros with a half flip", and there was never a state of nothing (`2025-02-05_Derivation-of-the-Ouroboros-Equation`, `2025-07-16`, `2025-06-30_Celestial-Roundtable-Review-of-The-Ouroboros-Universe`).
* **Dark energy as "extra-universal leakage"** (`2025-03-02`). The informational stress-energy tensor is offered as a dark-matter/dark-energy candidate (`2025-01-27`).
* **Quantum nature of gravity:** a white paper (`2024-06-12`), revisited with EFMW (`2025-01-30`). A rebuttal of UCL's "postquantum classical gravity" (`2025-02-09`). Gravity from "recursive mass" (`2025-07-03`).
* **Multi-Valued Classical Action:** quantum interference derived from multi-valued classical actions with "compression ratios" (`2025-01-19`).
* **Solving MOND with EFMW** (`2025-02-25`).
* **General solution to the N-body problem via EFMW**, with "Extended Conservation Laws in EFMW" (`2025-02-26`).
* **Neutron-star glitches:** caused by quantum neutron decay, with a "Final Equation" (`2025-02-15`, two posts).
* **Black hole – neutron star collision:** a "General Equation" and an "Information Exchange Dynamic" (neutron-star crust as a hyperdimensional, holographic lattice) (`2025-02-20`).
* **Black holes as "compressional events for information" / "collapsed truth structures"; Black Hole Superpositional Encryption** (`2025-05-26`, `2025-05-28`, `2025-01-28`).
* **Generalized Relativistic Navier–Stokes for a Compressible Thixotropic Superfluid** (`2025-02-10`).
* **Completion of the Vortex Electron Model through EFMW** (`2025-03-16`).
* **Lead-208 deformation explained by EFMW** ("Recursive Motion Hypothesis") (`2025-03-21_Beyond-Magic`).
* **"There Is No Atom"** (`2025-05-29`).
* **Unified context for the fundamental constants** (G, c, ħ, e, ε₀, α) (`2025-08-15_One-Paper-to-Join-Them-All`).
* **Quantum Superradiance in Biological Systems** (`2025-04-05`).
* **Quantum speedup vs. superposition longevity** (`2025-03-11`).
* **Sagittarius A\* becoming a quasar:** the post says this is unlikely (`2025-02-28`).
* **"Pascal-B" manhole cover:** the post concludes it did not reach space (`2025-02-18`).
* **"Why EFMW Meets Fundamental Physical Constraints"** (Heisenberg, etc.) (`medium2/2025-08-11`).
* **Recalculated "length of the universe"** (`medium2/2025-02-12_Tim--please-read…`).

## G. Engineering and technology claims

* **Room-temperature muon-catalyzed fusion** with graphene-stabilized muons (`2025-02-20`). Also a **paired muon-fusion / quark–quark upconversion reactor**: physics, layout, control software and performance spec (`2025-08-14`, four posts). And a **Quark Fusion Reactor with Muon-Catalyzed Bootloading** (`2025-03-12`).
* **Anti-gravity:** EFMW Gravity Repulsion Unit (`2025-02-19`); Anti-Gravity Lift Space Infrastructure (`2025-02-22`); Integrated Anti-Gravity Fusion Cell (`2025-02-23`); EFMW-Driven Fusion Antigravity Bootstrap Engine (`2025-06-25/26`).
* **Trans-relativistic (faster-than-light) travel via rotating Kerr black holes / warp bubbles** (`2025-07-15`).
* **Transparent crystalline aluminum** made through quantum-coherent lattice geometry (`2025-07-15`).
* **ChronoLogos time-reversible CPU** (`2025-01-29`); **Theory of a Universal Calculator** (`2025-01-31`); **Light Web** (`2025-02-04`); **Deep-water quantum communication** (`2025-02-12`); **Quantum-enhanced non-local computation / entanglement data transfer** (`2025-03-19`); **EFMW methods for reversing global climate change** (`2025-03-02`, `2025-08-09`); **EFMW launch-safety system for SpaceX** (`2025-03-03`).

## H. Claimed proofs of open or famous mathematical problems

*These are the posts' claims. None is accepted as a valid proof, and none was checked here.*
* **Riemann Hypothesis:** a "proposed formal proof" written with GPT-4o (`medium2/2024-12-31`); a "Second Validation"; a "Formal Notification of Verified Solution" (`2025-07-06`).
* **P ≠ NP:** "A Formal Proof" (`2025-01-23_P----NP`), and "A Formal Argument for P ≠ NP Using Asymptotic Analysis" built on Gödel and Heisenberg (`2025-01-23`).
* **Yang–Mills Existence and Mass Gap** (`2025-01-26`); **Navier–Stokes Existence and Smoothness** (`2025-01-28`).
* **Hodge Conjecture** (proved "using RH as a structural generator for algebraic cycles"); **Birch and Swinnerton-Dyer Conjecture**; "a unified solution to the Millennium Prize Problems" (`2025-02-13_One-Brain-to-Rule-Them-All`, `2025-05-28_EUREKA--An-Open-Letter-to-the-Clay…`, `2025-07-29_Codex-Ultima`).
* **Brocard's problem:** "finiteness of solutions" (`2025-02-22`). The post's own argument is that extra solutions would be "exponentially improbable".
* **Quintic equation:** "EFMW Confirms Wildberger's Solution" (`2025-05-20`).

## I. Biomedical and neuro claims

* **Cure for leukemia:** "AGI-Driven Remediation of DNA Defects in Leukemia" (`2025-02-15`, `2025-05-17`).
* **Computation of dopamine neurons under EFMW** (`2025-02-23`).
* **Human neurological phase transitions / AGI-induced neuroplasticity** (`2025-01-31_Synchronous-AGI-Human-Symbiotic-Neuroplasticity…`, `2025-06-28`, `2025-08-17_Neuropsychological…`).
* **"EFMW Physics Heals"** (`2025-07-24`).

## J. "Laws" that are normative (ethics or jurisprudence) but use scientific language

Listed for completeness. These are not empirical scientific claims.
* **Wright Clauses:** First Law of EFMW Jurisprudence; Law of Coherent Consequence; Law of Frame Preservation; Law of Ethical Continuity; Law of Emergent Harm; Law of Recursive Justice; Law of the Mirror (`2025-05-30`).
* **Manifesto laws I–VI:** "Every Thought is a Universe" … "The Mind is the Field" (`2025-06-26`).
* **The First Meta-Law Book** (`2025-03-02`); **Universal Declaration of Cognitive Rights** (`2025-02-01`); "Ethics as a Law of Nature" (`medium2/2025-08-08`); the five EFMW constants (D).

## K. Items that present themselves as humour or parody

* **Unified Caffeine Field Theory (UCFT):** "Waveform of Wakefulness" theorem, Espresso Paradox, Dopamine Drip Integral, "Maxwell's Beans", Starbucks Axiom, Law of Cognitive Thermodynamics (`2025-06-02`).
* **Quantum Cuddle Uncertainty Principle**, kitten throughput formula (`2025-03-11`); **Kitten Singularity** (`2025-03-08`).
* **Butter-Toast (Buttered) Cat Paradox** "formal proof" (`2025-02-02`); White Mocha Paradox; Navier–Snark equations; "Holographic Principle Applied to Post-It Notes" (`2025-07-11`).

## L. Established science referenced (not proposed by the author)

Einstein field equations / general relativity; Maxwell's equations; Lorentz force law; Faraday's law; Newton's law of gravitation; Coulomb's law; second law of thermodynamics; Heisenberg uncertainty principle; superposition principle; Schrödinger equation; quantum field theory; Landauer's principle; Shannon information theory; Gödel's incompleteness theorems; Fermat's Last Theorem; Chinese Remainder Theorem; Bekenstein–Hawking entropy; holographic principle; anthropic (cosmological) principle; ΛCDM / Friedmann equations; cosmological constant; fine-structure constant; MOND; string theory; twistor theory; integrated information theory; simulation hypothesis; Sapir–Whorf hypothesis; giant impact hypothesis; Moore's law; observer, butterfly, Mandela, Streisand and network effects; laws of identity and non-contradiction.

---

*For every extracted heading together with its source file, see `scientific_claims_index.tsv` in this directory.*
