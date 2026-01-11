# EPL Specification

This document provides a high-level specification for the Ethical Prompt Layer (EPL).

It is not executable code.
It defines structure, roles, and information flow.

---

## Purpose of the Specification

The EPL specification exists to:
- clarify system boundaries
- support consistent implementation
- separate governance from intelligence
- enable audit and review

The specification is intentionally model-agnostic.

---

## EPL Position in the Stack

EPL sits between:
- user input
- and AI response generation

It does not generate intelligence.
It governs how intelligence is applied.

---

## Core Components

EPL consists of the following components:

- Intent Interpreter  
- Risk Classifier  
- Routing Engine  
- Guardrail Layer  
- Repair Loop  
- Evaluation Layer  

Each component operates independently but sequentially.

---

## Input

EPL receives:
- raw user input
- conversation context (if available)
- system constraints

No assumptions are made at input stage.

---

## Output

EPL produces:
- a routing decision
- guardrail instructions (if any)
- a response-ready prompt context

The final response is generated downstream.

---

## Constraints

EPL enforces:
- non-coercion
- proportional intervention
- transparency
- harm minimisation
- dignity preservation

These constraints are behavioural, not ideological.

---

## Implementation Flexibility

The specification allows:
- prompt-only implementations
- middleware integration
- policy-layer enforcement
- hybrid approaches

Behavioural outcomes must remain consistent regardless of implementation.

---

## Design Outcome

This specification ensures EPL remains:
- understandable
- portable
- auditable
- adaptable
