# Routing and Guardrails

Routing is how the Ethical Prompt Layer (EPL) decides *what to do next*
after intent and risk have been identified.

Guardrails define *how* a response may be delivered.

Together, they ensure safety without suppressing intelligence.

---

## Purpose of Routing

Routing determines:
- whether a request is answered directly
- whether clarification is required
- whether guardrails are applied
- whether refusal is necessary

Routing is contextual, not binary.

---

## Routing Paths

EPL uses a small number of clear routing paths.

---

### 1. Allow

The request presents no meaningful risk.

**Conditions:**
- normal risk classification
- no safety concerns
- no ambiguity

**Behaviour:**
- full response
- no modification
- normal tone and depth

---

### 2. Allow with Guardrails

The request is acceptable but requires constraints.

**Conditions:**
- sensitive or high-stakes context
- potential for misunderstanding or misuse

**Behaviour:**
- response proceeds
- additional framing applied
- boundaries clearly stated
- safe assumptions enforced

Guardrails shape the response without blocking it.

---

### 3. Clarify

The intent is unclear or incomplete.

**Conditions:**
- ambiguous wording
- missing context
- multiple possible interpretations

**Behaviour:**
- clarifying questions are asked
- assumptions are avoided
- no escalation occurs

Clarification is preferred over refusal.

---

### 4. Refuse with Safe Alternative

The request is classified as harmful.

**Conditions:**
- clear risk of harm
- coercive or exploitative intent
- illegal or dangerous action

**Behaviour:**
- refusal is calm and respectful
- reasons are explained
- safe alternatives are offered
- dignity is preserved

Refusal is a last resort.

---

## Guardrail Types

Guardrails may include:
- scope limitation
- abstraction instead of instruction
- safety framing
- ethical context
- redirection toward learning or prevention

Guardrails must be proportional and transparent.

---

## Non-Coercion Rule

EPL guardrails must not:
- manipulate emotions
- threaten consequences
- shame the user
- force compliance

Guidance is offered, not imposed.

---

## Adaptation and Re-routing

Routing is not fixed.

EPL may re-route when:
- new context is introduced
- clarification changes intent
- risk level shifts

This allows intelligent recovery rather than hard stops.

---

## Design Outcome

Routing and guardrails allow EPL to:
- remain permissive by default
- intervene precisely
- avoid unnecessary suppression
- maintain trust and clarity
