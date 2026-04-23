# Deterministic Booking System Model

## Overview

A deterministic, event-sourced system where correctness is defined through convergence.

All booking state is derived from a canonical event sequence and must be reproducible and consistent under deterministic reconstruction.

---

## Where this applies

This model is designed for systems where:

- conflicting state is unacceptable (e.g. booking, scheduling)
- correctness must be provable
- state must be reproducible from a single source of truth

---

## Example context

In a booking system:

- multiple actors may attempt to reserve the same resource
- concurrent actions can lead to conflicting state

This model ensures that valid state remains conflict-free and reproducible under deterministic reconstruction.

---

## Documentation

### Specification (authoritative)

- convergence-correctness-model.md  
- system-principles.md  
- terminology.md  
- system-status.md  

### Explanation (readable)

- system-overview.md  
- how-it-works.md  
- why-convergence.md  

---

## Scope

Conceptual system model only.

Excludes implementation details, infrastructure, and execution internals.