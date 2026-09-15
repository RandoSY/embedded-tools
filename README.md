# Embedded Tools

Embedded Tools is the canonical home for reusable development infrastructure that supports the rest of the Intellectual Estate: programmers, debuggers, bridges, measurement protocols, and board-level utilities.

These are enabling tools rather than standalone curriculum branches. A tool belongs here when it serves multiple projects or makes low-cost hardware substantially easier to inspect, program, or reuse.

## Project families

### debugWIRE LIGHTENING

Low-cost AVR debugWIRE exploration centered on safe stepping, run/break behavior, breakpoints, and practical integration with ordinary development workflows.

### RP2040 common tools

RP2040-based utilities for observing and assisting other embedded targets, including logic/timing work and experimental multi-target tooling.

### Programmers and bridges

Small programmer, serial, BLE, USB, and board-interface utilities belong here when their value extends beyond one application.

### Human-readable protocols

YMP-style short ASCII measurement messages and related common transport conventions belong here when they become shared infrastructure across applications.

## Design rules

- Prefer one reusable tool over many nearly identical project-specific copies.
- Keep interfaces documented and inspectable.
- Separate stable utilities from experimental prototypes.
- Record target limitations and known-good hardware combinations.
- Preserve upstream attribution and licensing.
- Keep tools small enough that another person can understand why they work.

## Planned repository structure

- `debugwire-lightening/`
- `rp2040-tools/`
- `programmers/`
- `bridges/`
- `protocols/`
- `docs/`
- `validation/`

## Current state

**Lifecycle:** `active / preservation`

This repository currently establishes scope. Existing utilities and prototypes still need to be reviewed individually before migration so that experimental work is not mislabeled as validated infrastructure.
