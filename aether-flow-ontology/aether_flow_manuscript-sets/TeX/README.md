# Individual manuscript TeX sources

Last revised: 15 September 2026.

This folder contains the eight standalone Æther-Flow manuscripts. They preserve the distinction between an incomplete source ontology, adopted GR calculations, and the proposed AI-assisted research protocol. A valid negative finding must have an explicit scope; an unsuccessful search is not a proof of impossibility.

The canonical comprehensive TEX is [aether_flow_ontology.tex](../../aether_flow_ontology.tex). The standalone papers contain the corresponding scientific content for focused reading. The overview introduces the research sequence; the synthesis explains the AI evaluation design. No completed performance evaluation is reported.

## File map

| File | Description |
| --- | --- |
| [aether_flow_consistency.tex](aether_flow_consistency.tex) | GR mode count and flat-vacuum checks; requirements for scoped source-consistency and obstruction claims. |
| [aether_flow_dynamics.tex](aether_flow_dynamics.tex) | Adopted action, matter coupling, and weak-field limit; criteria for non-circular dynamics recovery. |
| [aether_flow_exact_closure_flagship_article.tex](aether_flow_exact_closure_flagship_article.tex) | Source interpretation, explanatory limits, and the proposed AI research evaluation protocol. |
| [aether_flow_exact_closure_note.tex](aether_flow_exact_closure_note.tex) | Compact GR benchmark, open source question, and distinctions among research outcomes. |
| [aether_flow_exact_closure_sequence_overview.tex](aether_flow_exact_closure_sequence_overview.tex) | Manuscript map, dual research objective, and bounded feasibility sequence. |
| [aether_flow_foundations.tex](aether_flow_foundations.tex) | Source assumptions, reconstruction targets, and the distinction between non-entailment and incompatibility. |
| [aether_flow_geometry.tex](aether_flow_geometry.tex) | Observer geometry and a geometry-first source milestone; local and global limits. |
| [aether_flow_relativistic_recovery.tex](aether_flow_relativistic_recovery.tex) | GR measurement relations and criteria for partial, approximate, or exact source recovery. |
| `shared/` | Shared packages, formatting, commands, and bibliography used by all eight sources. |

## Build the standalone manuscripts

Run from this `TeX/` folder in the complete repository so that `shared/preamble.tex` and `shared/references.bib` are available:

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error aether_flow_*.tex
```

The build requires pdfLaTeX, Biber, and the packages declared in the shared preamble. Place the resulting PDFs with the matching filenames in `../PDF/`. Do not include auxiliary build files in the manuscript set.

When editing a paper, apply the same scientific changes to its chapter in the canonical source. Preserve its labels, notation, assumptions, and citations; the comprehensive document prefixes local labels to avoid collisions. Compilation and reference checks do not independently validate a derivation.
