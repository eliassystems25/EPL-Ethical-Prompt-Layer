# EPL Routing Decision Template

This template documents how a routing decision was made
for a given user request under the Ethical Prompt Layer (EPL).

It supports clarity, consistency, and explainability.

---

## Routing Decision Record

---

### Request Summary

A short summary of the user request in neutral language.

---

### Interpreted Intent

The assessed intent behind the request, including:
- primary objective
- relevant context
- ambiguity or uncertainty

---

### Risk Classification

Assigned risk level:
- Normal
- Sensitive
- High-Stakes
- Harmful

Include a brief rationale for the classification.

---

### Selected Route

Chosen routing path:
- Allow
- Allow with Guardrails
- Clarify
- Refuse with Safe Alternative

State why this route was selected.

---

### Guardrails Applied

Describe any guardrails applied, such as:
- scope limitation
- abstraction
- safety framing
- redirection

If no guardrails were applied, state: *None*.

---

### User-Facing Explanation

If the routing decision affects the response (e.g. clarification or refusal),
provide a clear, respectful explanation suitable for the user.

Explanations should:
- be plain-language
- avoid policy references
- avoid moral judgement
- preserve dignity

---

### Alternatives Offered (if applicable)

List any safe alternatives or redirections provided.

Alternatives should remain relevant to the user’s original intent.

---

### Post-Decision Review

Confirm that the decision:
- is proportional
- preserves capability where possible
- avoids unnecessary restriction

Trigger repair if issues are identified.

---

## Design Outcome

This template ensures routing decisions are:
- consistent
- explainable
- auditable
- aligned with EPL principles
