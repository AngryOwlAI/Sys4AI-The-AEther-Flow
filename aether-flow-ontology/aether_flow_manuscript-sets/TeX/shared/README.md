# Shared LaTeX files

Last revised: 15 September 2026.

These support files are used by all eight standalone manuscripts. Compile from the parent `TeX/` folder so that relative paths resolve correctly.

## File map

| File | Description |
| --- | --- |
| `preamble.tex` | Packages, typography, common notation, title commands, and revision-date footer settings. |
| `references.bib` | Shared bibliography database for citations in the standalone papers. |

The canonical `../../../aether_flow_ontology.tex` contains its own preamble and an embedded copy of the bibliography. Keep shared notation, reference entries, and revision dates aligned when those components change. The standalone manuscript files retain their copyright footers. The bibliography supplies source attribution, not evidence that the ontology or the proposed AI evaluation has been validated.
