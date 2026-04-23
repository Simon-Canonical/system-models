# Deterministic Booking Execution Platform

Designed for systems where:

- conflicting state is unacceptable (e.g. booking, scheduling)
- correctness must be provable
- state must be reproducible from a single source of truth

## Overview

A deterministic, event-sourced system where correctness is defined through convergence.

All booking state is derived from a canonical event sequence and must be reproducible and consistent under deterministic reconstruction.

Designed for systems where:

- conflicting state is unacceptable  
- correctness must be provable  
- state must be reproducible from a single source of truth  

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