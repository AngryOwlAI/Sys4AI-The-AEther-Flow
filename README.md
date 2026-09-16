# Æther-Flow Ontology

<p align="center">
  <img src="https://github.com/user-attachments/assets/aac9e81a-321f-4952-9e84-10a8c41555dc" alt="The Æther-Flow research program" width="100%" />
</p>

Last revised: 15 September 2026.

Æther-Flow is a physics research proposal and an AI-assisted research case study. Its scientific goal is to determine whether General Relativity (GR) can be derived from a precisely specified development of the ontology, or whether a proposed route can be ruled out under explicit assumptions. A justified negative result is an acceptable research outcome.

The project is intended to use **Sys4AI**, an agentic AI framework, to coordinate research roles, tasks, tools, and verification. The ontology supplies the scientific starting point. Sys4AI would organize the investigation; its use does not establish the physical proposal or the capability of an AI model. This repository contains the manuscripts and supporting documentation, not a runnable evaluation system or completed performance results.

## The source idea and its present status

The project asks what physical reality could underlie the spacetime geometry described by GR. Its working hypothesis is a four-dimensional substrate called the **Æther**, whose intrinsic ordered motion is **Æther-Flow**. "Substrate" means a proposed underlying physical reality, not an observed material. The intended explanation would preserve GR rather than introduce different predictions for their own sake.

In this picture, observers are part of the underlying reality and register its local effects. Experienced three-dimensional space and **S-time**, the proposed connection between ordered change and temporal experience, describe what the research seeks to explain. The flow is not intended as a wind through an already existing space. The question is whether it can produce the metric, the structure that assigns spacetime intervals and causal relations, together with the measurement rules used by observers.

This physical intent is distinct from its mathematical specification. At present, the source assumptions provide a smooth four-dimensional manifold, a setting described locally by four coordinates, and an unresolved symbol for source order or evolution. They do not yet define source dynamics, physical clocks, or a rule that produces spacetime geometry. Calling the source four-dimensional does not complete those steps.

The quantitative calculations use a separately adopted GR model. Its metric describes spacetime intervals, its equations connect geometry to matter, and its measurement rules describe clocks and light. Reproducing those calculations is not a derivation of GR from the ontology. They provide explicit targets against which a future source construction can be checked. In the manuscripts, **exact closure** names this choice of a GR reference model. In source research, agreement with that model is a target to demonstrate, not a result guaranteed by the ontology. A candidate that fails the target can be rejected without abandoning GR as the reference.

No source-to-GR derivation or theorem excluding every possible source completion is established in these manuscripts. The first research milestone is a defined source model and a checkable claim, not another restatement of the GR equations.

## What would count as a result?

Each research task must specify its assumptions, permitted reconstructions, target, and domain. Recovering a local causal structure is different from recovering a clock rule, gravitational dynamics, or a full specified GR model. A selected solution, an approximation, and an exact result must be labeled accordingly.

| Outcome | Meaning |
| --- | --- |
| Verified derivation | The declared target follows from the stated assumptions, with the relevant checks completed. |
| Counterexample to entailment | An admissible example violates the required conclusion. The assumptions do not force that conclusion; a compatible completion may still exist. |
| Scoped obstruction | A proof excludes recovery within the defined model or reconstruction class and stated conditions. It does not automatically exclude every future version of the ontology. |
| Unresolved search | Neither a verified derivation nor a valid negative argument has been obtained. Failure to find a proof is not proof of impossibility. |

A source specification must also have admissible models, or identify existence as an unresolved condition. An inconsistent set of assumptions cannot earn physical recovery credit through a vacuous implication. Likewise, adding Einstein's equations as a premise cannot count as deriving them.

## How AI research would be assessed

A **fixed-assumption audit** checks what follows from the proposal as given. **Open construction** permits new definitions or laws, but each addition must be recorded and the resulting claim must name the strengthened assumptions. AI can help develop the missing mathematics; it must not silently change the question.

The physical outcome and the correctness of the reasoning are assessed separately. A valid obstruction can count as successful AI-assisted research even when it rules out a candidate source model. Repeating a gap already described in these manuscripts is an audit finding, not new research. Credit for progress requires an inspectable construction, implication, counterexample, or other result beyond the supplied material.

The proposed protocol calls for independent checking, recorded sources and assumptions, comparable tools and resource budgets, and disclosure of human intervention. A result from a multi-agent Sys4AI workflow measures that whole arrangement unless a controlled comparison isolates the model's contribution. One ontology is a case study, not a validated measure of general scientific competence. The [synthesis article](aether-flow-ontology/aether_flow_manuscript-sets/PDF/aether_flow_exact_closure_flagship_article.pdf) gives the full protocol; it reports no benchmark scores or completed evaluation runs.

## Reading the manuscripts

The [comprehensive PDF](aether-flow-ontology/aether_flow_ontology.pdf) and its [self-contained TeX source](aether-flow-ontology/aether_flow_ontology.tex) are the **canonical versions**. The eight standalone manuscripts remain available for focused reading and reference. Their source assumptions, outcome categories, and scientific claims are synchronized with the comprehensive document.

Start with the [overview](aether-flow-ontology/aether_flow_manuscript-sets/PDF/aether_flow_exact_closure_sequence_overview.pdf) for the research sequence, or the synthesis article for the conceptual argument and AI evaluation design. [Foundations](aether-flow-ontology/aether_flow_manuscript-sets/PDF/aether_flow_foundations.pdf) defines the source proposal. The technical papers supply the adopted GR calculations and their limits.

## Project overview video

The video communicates the project's physical intent: a deeper account of spacetime through intrinsic ordered motion, with observers inside the proposed source and GR retained as the target. Its statements that the flow generates the metric or supplies a complete physical explanation describe the intended outcome, not an established derivation. The AI research objective and its evaluation protocol are specified separately in the manuscripts.

The technical papers also qualify the video's geometric shorthand. An observer congruence is a family of worldlines defined within an existing spacetime, not yet a reconstruction of that spacetime. The [Geometry paper](aether-flow-ontology/aether_flow_manuscript-sets/PDF/aether_flow_geometry.pdf) distinguishes frame dragging from congruence vorticity, tidal curvature from shear, and local inertial coordinates from vanishing curvature. The [Dynamics paper](aether-flow-ontology/aether_flow_manuscript-sets/PDF/aether_flow_dynamics.pdf) explains why coupling matter to one metric does not by itself verify the full source theory. Read the video as a conceptual introduction and the manuscripts as the statement of assumptions, calculations, and current research status.

<p align="center">
   The Æther-Flow Ontology Video:<br />
  <a href="https://www.youtube.com/watch?v=psbk97rd9T8">
    <img src="https://github.com/user-attachments/assets/7134da9c-977c-4312-8e2a-10a51bb2db28" alt="The Æther-Flow">
  </a>
</p>

## File map

Only files and folders at the repository root are shown here. The ontology folder's README maps its contents.

```text
Sys4AI-The-AEther-Flow/
├── .gitignore               # Git exclusions for local and generated files
├── README.md                # Purpose, research status, outcomes, and reading guide
├── LICENSE                  # Repository licensing notice
├── LICENSE-CODE             # License terms for code
├── LICENSE-DOCS             # License terms for documentation
└── aether-flow-ontology/    # Canonical manuscript and eight standalone manuscripts
```
