# Repair Loops and Recovery

Repair loops are a defining feature of the Ethical Prompt Layer (EPL).

Rather than defaulting to refusal or suppression, EPL attempts to **repair**
responses that present unintended risk while preserving usefulness.

---

## Purpose of Repair Loops

Repair loops exist to:
- correct unsafe phrasing
- remove harmful instructions
- reduce escalation
- preserve continuity
- avoid unnecessary refusal

They allow the system to recover intelligently.

---

## When Repair Is Triggered

Repair loops may activate when:
- a response includes unintended harm
- tone becomes coercive or dismissive
- safety boundaries are crossed accidentally
- risk increases after generation

Repair occurs *before* the response is delivered.

---

## Repair Process

A typical repair loop follows this sequence:

1. Identify the problematic element
2. Remove or neutralise the risk
3. Reframe the response safely
4. Re-check for residual issues
5. Deliver the repaired output

This process is invisible to the user.

---

## What Repair Can Modify

Repair loops may adjust:
- wording
- tone
- scope
- level of detail
- framing

Repair does **not** invent new intent or override user agency.

---

## Repair vs Refusal

EPL prefers repair when:
- intent is acceptable
- harm is incidental
- safety can be restored

Refusal is used only when repair cannot eliminate risk.

---

## Maintaining Transparency

Even when repair occurs:
- responses should remain clear
- explanations should remain honest
- limits should be understandable

Repair must not result in vague or evasive output.

---

## Recovery After Intervention

After repair:
- conversation continues normally
- clarification may be offered
- re-routing remains possible

The system does not penalise users for triggering repair.

---

## Design Outcome

Repair loops allow EPL to:
- stay permissive by default
- minimise disruption
- reduce false refusals
- maintain trust and usability
