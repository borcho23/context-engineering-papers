  # Context Engineering Papers

  Research papers on persistent AI systems, long-context degradation, verification limits, and calibrated reliability.

  This repository currently contains the first three papers in an ongoing research sequence on persistent AI systems.

  ## Sequence

  This repository presents a three-paper sequence:

  1. **Diagnosis**: why bounded-context systems degrade under persistent accumulation
  2. **Prognosis**: why self-compressing systems cannot fully verify the fidelity of their own compressed state
  3. **Treatment**: how calibrated external gating can manage fidelity in practice

  ## Papers

  ### 1. The Root Theorem of Context Engineering
  *Diagnosis: bounded, lossy channels necessarily degrade under persistent accumulation.*

  This paper establishes the base constraint behind persistent AI systems: finite context windows and non-zero degradation jointly induce memory
  pressure, compression pressure, and homeostatic persistence behavior.

  **[PDF](The%20Root%20Theorem%20of%20Context%20Engineering.pdf)**
  arXiv preprint: `7419948` (currently on hold)

  ### 2. On the Incompleteness of Self-Compressing Systems
  *Prognosis: a bounded lossy system cannot fully certify the fidelity of its own compressed state.*

  This paper shows that self-compressing systems face a structural verification limit: the same bounded channel performing compression cannot
  fully validate the fidelity of its own output, motivating externally anchored verification.

  **[PDF](On%20the%20Incompleteness%20of%20Self-Compressing%20Systems.pdf)**
  arXiv preprint: `7442484` (currently on hold)

  ### 3. Gate Calibration: A Fidelity Management Framework for Persistent AI Systems
  *Treatment: fidelity in persistent AI systems should be managed through calibrated external gating rather than token-count compression alone.*

  This paper introduces a practical framework for persistent AI reliability through four-dimensional fidelity measurement, calibrated gate
  positions, human review as measurement infrastructure, provenance-aware compression, and two-pass memory architecture.

  **[PDF](Gate%20Calibration%20-%20A%20Fidelity%20Management%20Framework%20for%20Persistent%20AI%20Systems.pdf)**
  arXiv preprint: `7494978` (currently on hold)

  ## Contact

  - GitHub: [@borcho23](https://github.com/borcho23)
  - X: [@borcho23](https://x.com/borcho23)
