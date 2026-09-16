# Æther-Flow ontology manuscripts

Last revised: 15 September 2026.

This folder contains the canonical comprehensive manuscript and the eight standalone papers. The research asks whether a specified development of the Æther-Flow source ontology can recover a declared part of General Relativity (GR), or whether a scoped obstruction can be established. It also defines a proposed AI-assisted research case study using Sys4AI.

The physical aim is to explain the spacetime relations accessible to observers through intrinsic ordered motion in a proposed four-dimensional substrate, while preserving GR as the recovery target. Experienced space and S-time express that aim; they are not yet derived measurement structures. The flow is not intended as a medium moving through a pre-existing three-dimensional space.

The source proposal and the adopted GR model remain separate. The manuscripts contain GR calculations, explicit source limitations, and a research evaluation protocol. They do not report a source-to-GR derivation, a universal impossibility theorem, or completed AI evaluation results.

## Canonical versions and reading order

[aether_flow_ontology.pdf](aether_flow_ontology.pdf) is the canonical reading version. [aether_flow_ontology.tex](aether_flow_ontology.tex) is its self-contained source, including an embedded bibliography. The comprehensive document contains the same scientific content as the standalone papers, organized into eight chapters with namespaced cross-references and one bibliography.

For an introduction, read the standalone overview or synthesis. Foundations defines the assumptions and outcome categories. Dynamics, Consistency, Relativistic Recovery, and Geometry provide the GR comparison calculations and corresponding source-research targets. The Exact-Closure Note gives a compact statement of the benchmark and its limits. The synthesis contains the detailed proposed AI evaluation protocol.

A verified derivation, a counterexample to entailment, a scoped obstruction, and an unresolved search are distinct outcomes. A valid negative physical result may still be successful reasoning. All claims must retain their assumptions and domain.

## File map

| Item | Description |
| --- | --- |
| `README.md` | Purpose, status, canonical files, and reading guide. |
| `aether_flow_ontology.pdf` | Canonical comprehensive manuscript. |
| `aether_flow_ontology.tex` | Self-contained canonical LaTeX source with embedded bibliography. |
| `aether_flow_manuscript-sets/` | Eight standalone papers: compiled files in `PDF/` and editable sources in `TeX/`. |

## Build the comprehensive manuscript

Run from this folder with a LaTeX installation providing pdfLaTeX, Biber, and the packages used by the source:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error aether_flow_ontology.tex
```

Keep the comprehensive source and the corresponding standalone text synchronized when changing a shared scientific statement. Successful compilation checks document production; it is not a proof of the physical claims.
