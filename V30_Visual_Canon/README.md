---
document: V30 Visual Canon
repository: The Earth Will Hear Story Bible
project: The Earth Will Hear (زمین خواهد شنید)
version: 1.0.0
status: Active
phase: Creative Production
maintainer: Creative Director
documentation_engineer: Repository Documentation Engineer
last_updated: 2026-07
---

# V30 — Visual Canon

## Purpose

The Visual Canon defines the permanent visual language of **The Earth Will Hear**.

Unlike the Story Bible, which preserves narrative canon, and the Production Bible, which organizes production knowledge, the Visual Canon establishes the approved artistic standards that govern every visual representation of the fictional world.

Its purpose is to ensure that all future visual assets remain internally consistent across different artists, AI systems, software, and production stages.

This includes:

- AI image generation
- AI video generation
- Storyboards
- Concept art
- Character sheets
- Environment design
- Film production
- Animation
- Games
- Marketing material

The Visual Canon is the bridge between written canon and visual production.

---

# Repository Position

```
Novel
    │
    ▼
Story_Bible
    │
    ▼
Production_Bible
    │
    ▼
Production_Dashboard
    │
    ▼
Visual_Canon
    │
    ▼
Reference Images
    │
    ▼
Storyboard
    │
    ▼
Shot Bible
    │
    ▼
AI Production
    │
    ▼
Video Production
```

---

# Scope

The Visual Canon defines visual standards only.

It does **not** modify the Story Bible.

It does **not** rewrite canon.

It does **not** introduce narrative facts.

Whenever canonical information is unavailable, the missing element is resolved through an explicit **Design Decision**, which is always documented separately from canon.

---

# Canon Hierarchy

1. Story_Bible (highest authority)
2. Production_Bible
3. Production_Dashboard
4. Visual_Canon

If any conflict exists, the higher layer always takes precedence.

---

# Canon vs Design

The project distinguishes between two independent layers.

## Canon

Narrative facts documented in the Story Bible.

Canon is immutable.

Examples:

- characters
- events
- locations
- objects
- relationships

---

## Design Decision

Creative decisions required for visual production.

Examples include:

- facial structure
- costume tailoring
- material finish
- camera language
- lighting style
- color palette
- rendering standards

Design Decisions never replace canon.

They exist only to enable consistent visual production.

---

# Design Philosophy

Every approved visual element should satisfy the following principles.

## Archaeological Plausibility

The world should feel believable within its Neo-Elamite setting.

Historical inspiration is welcome.

Historical invention is not.

---

## Material Authenticity

Every object should appear handcrafted.

Materials should show age, wear, texture, and physical reality.

---

## Environmental Realism

Nature is an active part of the world.

Mountains, rivers, oak forests, wind, dust, sunlight, and weather should always feel physically present.

---

## Human Realism

Characters are ordinary human beings shaped by life, responsibility, grief, work, leadership, and environment.

They are never idealized fantasy heroes.

---

## Emotional Restraint

Power is expressed through silence, posture, architecture, and atmosphere—not excessive ornament.

---

# Design Decision Policy

Every design decision must:

- have a unique identifier
- be versioned
- specify its approval date
- identify its author
- identify its reviewer
- remain fully reversible
- never overwrite canon

---

# Repository Structure

```
V30_Visual_Canon/

README.md

00_Design_Principles.md

01_Color_System.md

02_Material_System.md

03_Lighting_System.md

04_Camera_Language.md

05_Character_Framework.md

Characters/

Locations/

Objects/
```

---

# Future Expansion

Future visual production files may include:

- Reference Images
- Character Locks
- Environment Locks
- Costume Libraries
- Material Libraries
- Storyboards
- Shot Guides

These are separate production layers and are not part of the Visual Canon itself.

---

# Validation

- Story_Bible remains the only narrative authority.
- Production_Bible remains the production authority.
- Production_Dashboard remains the management authority.
- Visual_Canon defines approved artistic standards only.
- Canon and Design Decisions are permanently separated.