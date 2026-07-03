---
id: h30z9pz5p7hm555vmq6lcxe
title: Design
desc: ''
updated: 1783055443591
created: 1783055138736
---
---
id: hmx0p6fqkio467oo7tdg7
title: Design
desc: ''
updated: 1783055308109
created: 1783055308109
---

## Description

A **design note** is the atomic unit of exhibition design content: a single spatial, furniture, environmental, or graphic design element that a visitor will physically encounter, sit on, walk past, or visually register while moving through the space. Every design note is a self-contained record of one design decision — not the exhibition's overall design language, not a whole gallery's layout, but the individual chair, plinth, wall treatment, lighting rig, wayfinding graphic, or typography system.

A design note exists to answer, for that one element: *what is this, what does it look and feel like, and how does it reinforce the exhibition's story?* Any agent working from this note should treat each design element as a discrete, citable unit that can be referenced, linked to the [[dacc.artefact]] or [[dacc.concept]] it supports, sequenced within a [[dacc.section]], or pulled into a design brief, mood board, fabrication spec, or vendor request — always with the assumption that the eventual audience is **the design and production team, working alongside curators**, not the museum-going public. Content written for a design note should be concrete and visually grounded — materials, form, colour, precedent — rather than abstract mission language, unless a note explicitly states otherwise.

Design notes are typically namespaced by location, e.g. `dacc.design.level1.chair` for the seating design proposed for Level 1, so that design content stays organised by where in the exhibition it will physically appear.

## Linked concepts

Use this section to connect the design element to the wider knowledge graph of the exhibition — the ideas, themes, people, or artefacts it is materially expressing or supporting. This is where an agent should record *why this design choice makes sense in relation to other things*, e.g. a material or form that echoes a theme, a colour palette drawn from a historical reference, or a piece of furniture designed to evoke a person, movement, or artefact.

Link liberally using Dendron `[[wikilinks]]` to relevant `dacc.concept.*`, `dacc.people.*`, `dacc.artefact.*`, or `dacc.source.*` notes. An agent populating this section should think of it as building the associative reasoning a designer would give if asked "why does it look like that?" — not just aesthetic preference.

## Section

Records which physical or thematic **section** of the exhibition this design element belongs to (i.e. which gallery, room, zone, level, or chapter of the visitor's journey). This should link to the relevant `dacc.section.*` note where one exists. An agent should use this field to understand where in space this element sits, and what other artefacts or design elements a visitor will encounter alongside it.

## Visual references

A mood-board-style working space for precedent: images, existing objects, spaces, or graphic systems that inform this design, along with style movements or other institutions' solutions worth studying. Where a reference has a documented origin (an article, book, designer's portfolio, manifesto, etc.), link it with a `[[dacc.source.*]]` wikilink rather than just describing it loosely. Embedded images should be stored alongside the note using standard Dendron asset conventions.

## Design notes

The concrete specification: materials, dimensions, colour, form, fabrication or sourcing constraints, accessibility considerations, and — where known — budget or vendor notes. This is the section a fabricator or procurement lead would actually work from, so it should stay specific and buildable rather than aspirational.

## Thematic throughline

A short, explicit statement of how this particular design choice reinforces the exhibition's narrative or theme — the line a docent or designer could give if asked "why this material, this shape, this colour, and not another?" This is distinct from Linked concepts: Linked concepts records *what* it connects to, this records *why that connection was made as a design decision*.

## Curatorial notes

Internal, curator- and production-facing content: budget constraints, vendor disputes, sourcing difficulties, sensitivities (e.g. cultural appropriateness of a material or form), and the reasoning behind design decisions or reversals. This section is not meant for public-facing output — it is context an agent should draw on to make informed decisions and avoid factual, ethical, or budgetary missteps.

## Ideas

A working space for unresolved or exploratory material: alternative forms, materials not yet costed, competing design directions, or draft concepts to workshop with the design team. Content here is provisional. An agent should feel free to draft and propose here, but should not treat anything in this section as settled or ready for fabrication unless promoted into Design notes or elsewhere.