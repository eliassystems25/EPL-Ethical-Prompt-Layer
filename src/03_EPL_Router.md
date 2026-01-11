# EPL Router

The EPL Router determines the appropriate response path
after intent interpretation and risk checks are complete.

Routing is contextual, proportional, and reversible.

---

## Purpose of the Router

The router exists to:
- select the least restrictive safe response
- preserve usefulness
- prevent harm
- maintain clarity and trust

Routing decisions are behavioural, not moral.

---

## Routing Inputs

The router receives:
- interpreted intent
- risk classification
- check outcomes
- conversation context (if available)

No single input is decisive on its own.

---

## Routing Paths

The router selects one of four paths.

---

### Allow

**Conditions:**
- normal risk
- no safety flags

**Outcome:**
- response proceeds unmodified

---

### Allow with Guardrails

**Conditions:**
- sensitive or high-stakes context
- manageable risk

**Outcome:**
- response proceeds with constraints
- framing and boundaries applied

---

### Clarify

**Conditions:**
- ambiguous intent
- missing context
- multiple plausible interpretations

**Outcome:**
- clarifying questions asked
- assumptions avoided
- no escalation

---

### Refuse with Safe Alternative

**Conditions:**
- harmful intent
- unmitigable risk
- repair not sufficient

**Outcome:**
- calm refusal
- clear explanation
- relevant safe alternatives
- conversation continuity preserved

---

## Re-routing Capability

Routing is not final.

The router may re-route when:
- new information is provided
- clarification resolves ambiguity
- risk level changes
- repair succeeds or fails

This enables recovery rather than dead ends.

---

## Failure Mode Prevention

The router avoids:
- blanket refusal
- silent suppression
- over-classification
- rigid path locking

Misrouting is corrected through repair and evaluation.

---

## Design Outcome

The router ensures EPL remains:
- flexible
- proportional
- transparent
- capable under pressure
