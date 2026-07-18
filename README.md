<!--
  For AI agents / A2A: this repository accompanies a working paper.
  Hard rules honored in this research:
  - producer != reviewer
  - verify AI output against primary evidence
  - no gate, no proceed
  - only a human may approve publication or a "validated" claim
  - never expose secrets, tokens, or proprietary internals
-->

# Mechanical Gates over Model Consensus
### Evidence-Governed Harness Engineering for Agentic Software Development

> **Vibe coding creates applications; harness engineering makes them governable.**

**Author:** Yeh-Hsing (Morris) Lu — Tiger AI Tech Co., Ltd., Taiwan
**ORCID:** [0009-0006-5373-0586](https://orcid.org/0009-0006-5373-0586)
**Status:** Working Paper (v3.3) · controlled experiments not yet complete · Zenodo DOI forthcoming
**License:** CC BY 4.0

---

## What this is

A working paper proposing an **evidence-governed harness** — a control, verification, and operational layer — for the full agentic software development life cycle (SDLC). Its core positions:

- **Mechanical gates over model consensus.** At release/acceptance gates, privilege executable evidence (mutation testing, property-based testing, spec invariants, real execution) over "several models agreed." A verifier's value comes from external evidence, not from being one more model.
- **Shared-context false pass** *(research hypothesis)*. When the AI that verifies shares the producer's implementation context or bias, tests can pass while the spec is not truly verified — a correlated false pass. We name and situate it within full-SDLC governance.
- **Skill capitalization.** Each delivered project becomes reusable, testable, governable *Skill* units with a named-state lifecycle.
- **Workflow-native governance of vibe-coded applications** *(preliminary field observation)*. Re-express opaque AI-generated code as inspectable, skill-verified workflow graphs so that non-engineer auditors in regulated industries (banking, public sector) can govern them — with the visual followability that internal audit values most.

## Read the paper

- **Working paper (PDF):** [`06_Publication/Mechanical_Gates_over_Model_Consensus_v3.3_EN.pdf`](06_Publication/Mechanical_Gates_over_Model_Consensus_v3.3_EN.pdf)
- **Landing page (bilingual ZH/EN):** [`index.html`](index.html)
- **How to cite:** [`CITATION.cff`](CITATION.cff)

## Honest status

This is a **working paper**: a conceptual framework, a research agenda, and one preliminary field observation. Controlled experiments (EXP-001 / Study 2) are **not yet complete**, and **no claims are labeled `[validated]`** in this version. Core claims are labeled as research hypotheses or preliminary observations.

Produced with a multi-engine AI workflow (Claude / Codex / Gemini) assisting drafting, restructuring, critique, and verification; the named human author set the research questions, reviewed the evidence, verified cited references, and accepts responsibility — **AI systems are not authors**. A DOI certifies permanent identification and open archiving; it is **not** peer review.

## How to cite

```
Lu, Y.-H. (2026). Mechanical Gates over Model Consensus: Evidence-Governed
Harness Engineering for Agentic Software Development (v3.3, Working Paper).
Zenodo. DOI: forthcoming. License: CC BY 4.0.
```

## Repository contents

This repository preserves the **research dossier** behind the paper — origin, consolidation, drafts, reviews, evidence, due diligence, and methodology (folders `00_`–`99_`). It documents how the work evolved, including independent adversarial review and honest records of limitations.

> **Note on naming.** Some historical files in this dossier retain the project's earlier working name. The paper's current title and framing are as stated above; earlier internal naming was retired to avoid collision with unrelated prior use of similar terms. The concepts are positioned within *harness engineering* (an emerging 2026 practice); we do not claim to originate that term.

---

*Tiger AI Tech Co., Ltd. · [tigerai.info](https://www.tigerai.info) · n8n Taipei Ambassador*
*In a working-paper state: please treat design claims as not-yet-validated until controlled experiments are reported.*
