---
id: s1zbwa56inx5m3442zcb7
title: Visitor chip-design workstation
desc: ''
updated: 1783055910350
created: 1783055910350
---

## Description

An interactive workstation where a visitor gets to feel like they have actually **designed or customised a chip**, even though the real fabrication flow (if offered) happens later and off-site. A screen-and-input-device setup guides them through a simplified chip-design interface built on presets or templates, with a clear start and end state so a walk-up visitor can complete the experience without supervision.

The point of this piece is authorship: a visitor should leave having made a specific, personal decision about what their chip does — not just watched a demo.

## Linked concepts

- [[dacc.concept.open-silicon]]
- [[dacc.artefact.silicon-lab.chip-examples-and-outputs]] — the output categories a visitor can choose between at this workstation.
- [[dacc.artefact.silicon-lab.openpdk-tooling]] — the underlying open design toolchain this simplified interface is built on top of.
- [[dacc.artefact.silicon-lab.workshops-and-programmes]] — the same workstation format, in a more guided/scheduled form.

## Section

[[dacc.section.silicon-lab]]

## Curatorial notes

Design requirements to resolve:

- screen / workstation / input device specification;
- queueing, supervision, and reset-state behaviour for unattended walk-up use;
- accessibility of the interface for visitors with varying levels of dexterity, vision, and familiarity with technology;
- whether a submission flow exists (i.e. whether any visitor designs actually get fabricated, vs. simulated only).

Candidate visitor output types (see [[dacc.artefact.silicon-lab.chip-examples-and-outputs]] for how these are displayed):

- text-string USB chip;
- LED pattern chip;
- image/display chip;
- audio/synth chip;
- silicon art / easter egg.

## Ideas

- If a submission-to-fabrication flow is offered, it likely needs its own moderation/curation step before anything is sent to production — worth deciding who owns that decision.
- The "easter egg" / silicon-art output type could be the most memorable for casual visitors even if it's the least technically substantive — may be worth leading with it in the interface rather than burying it as a minor option.
- Reset-state design matters a lot for unsupervised walk-up use; consider a hard timeout that returns to a default/demo state rather than relying on staff to reset it.
