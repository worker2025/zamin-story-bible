---
document: Production Bible - Master Index
project: "زمین خواهد شنید (The Earth Will Hear)"
phase: "PHASE 2 - Production Documentation"
source: "Story Bible (V00-V10) ONLY — the manuscript is not consulted in this phase"
role: "Production Documentation Engineer"
---

# Production Bible — Master Index

## Folder Structure

```
Production/
  Characters/   24 character cards (23 named + 1 composite for unnamed notables)
  Locations/    9 location sheets (8 major + 1 composite for minor named places)
  Objects/      7 object sheets (5 individual + 1 khig/mashk + 1 composite minor objects)
  Shots/        Scene_Index.md — SC-001 to SC-077, mapped 1:1 to Story Bible Event IDs
  Visual/       11 files: Architecture, Landscape, Lighting, Color_Palette, Costumes,
                Props, Animals, Plants, Food, Materials, Visual_Rules
  Film/         6 files: Scene_Numbering, Timeline_Continuity, Character_Continuity,
                Object_Continuity, Location_Continuity, General_Continuity_Rules
  AI/           3 reusable reference sheets (Character, Location, Object) —
                data-availability matrices, not prompts
  Prompts/      4 prompt templates (Character, Location, Object, Scene) —
                placeholder templates only, no invented descriptions
  Style_Guide.md
```

## Canon Hierarchy for This Phase
The Story Bible files (V00_README_Index.md through V10_VisualDesign.md) are
the ONLY source of truth for all documents in this Production Bible. The
manuscript itself was not re-consulted in producing these files. Every
factual claim in every Production file cites its source Story Bible file
(and, where useful, the underlying Event ID or Chapter reference already
present in that Story Bible file).

## Zero Invention Policy — Applied
Every file in this Production Bible ends with a Validation block confirming:
- No invented information
- Derived only from Story Bible
- UNKNOWN preserved
- Canon preserved

Wherever the Story Bible does not contain a fact needed for production
(e.g., a character's face, a building's height, a color palette), the
corresponding field is marked UNKNOWN rather than filled with a plausible
guess. This is by design: an incomplete but accurate Production Bible is
preferred over a complete but partially invented one.

## Known Structural Notes
- The "Shots" folder contains scene-level numbering only; it does not
  contain shot-by-shot (camera angle / coverage) breakdowns, since the
  Story Bible does not document such detail and this phase does not
  re-read the manuscript to derive it.
- The Style Guide separates rules directly sourced from the Story Bible
  from rules reasonably inferred as production-safety boundaries for the
  documented setting; the latter are explicitly flagged as such.

## Validation
- No invented information
- Derived only from Story Bible
- UNKNOWN preserved
- Canon preserved
