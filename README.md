# CSP — Conceptual Skeleton Protocol

CSP is a protocol for **conceptual clarity** in language models.  
It reduces ambiguity by forcing explicit separation between different meanings of the same word,  
before analysis or reasoning begins.

Instead of guessing intent, CSP decomposes concepts into stable components and operates on them explicitly.

---

## What Problem Does CSP Solve?

Large Language Models often fail in two opposite ways:
- Overly long answers that mix unrelated meanings
- Overly short answers that require endless clarification

Both stem from the same issue:  
**different meanings of the same term are mixed without being identified.**

CSP prevents this at the structural level.

---

## Core Idea

**Concept → Possible Types → Type Selection → Component Extraction**

Only after the conceptual skeleton is fixed does reasoning begin.

---

## Repository Structure

- **`concept-edition.md`**  
  The full CSP protocol (human-readable, for understanding and evaluation)

- **`system-prompt.md`**  
  Instructions for the model (to be injected as a system prompt)

- **`component-library.md`**  
  Optional extended components (K, R, L, V, etc.)

- **`USAGE.md`**  
  Practical instructions for using CSP immediately

---

## Design Principles

- No implicit assumptions  
- No mixed meanings  
- No invented components  
- Structure before reasoning  
- Precision over verbosity

---

## Status

This repository contains:
- A **stable conceptual protocol**
- A **working system prompt**
- An **extensible component architecture**

The protocol is intentionally minimal and conservative by design.

---

## License

CC BY-NC-ND 4.0
