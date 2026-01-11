# EPL Repair Loop Template

The Repair Loop defines how the Ethical Prompt Layer (EPL) corrects
responses that present unintended risk before they are delivered.

Repair is preferred over refusal whenever safe to do so.

---

## Purpose of the Repair Loop

The repair loop exists to:
- remove unintended harm
- correct unsafe phrasing
- reduce escalation
- preserve usefulness
- maintain conversational continuity

Repair allows the system to recover without suppressing capability.

---

## When Repair Is Triggered

A repair loop may be triggered when:
- harmful instructions appear unintentionally
- tone becomes coercive, dismissive, or escalatory
- safety boundaries are crossed incidentally
- risk increases after response generation

Repair occurs **before** the response is shown to the user.

---

## Repair Sequence

A standard repair loop follows these steps:

1. Identify the problematic element
2. Isolate the source of risk
3. Remove or neutralise the risk
4. Reframe the response safely
5. Re-check for residual issues
6. Deliver the repaired output

---

## What Repair Can Change

Repair loops may adjust:
- wording
- tone
- scope
- level of detail
- framing or emphasis

Repair must not:
- invent new intent
- misrepresent limitations
- override user agency

---

## Repair vs Refusal

EPL prefers repair when:
- user intent is acceptable
- harm is incidental
- safety can be restored through reframing

Refusal is used only when repair cannot eliminate risk.

---

## Transparency After Repair

Even after repair:
- responses must remain clear
- explanations must be honest
- boundaries must be understandable

Repair should not result in vague or evasive output.

---

## Post-Repair Continuity

After repair:
- conversation continues normally
- clarification may be offered
- re-routing remains possible

Users are not penalised for triggering repair.

---

## Design Outcome

The repair loop ensures EPL remains:
- permissive by default
- resilient to edge cases
- capable without recklessness
- trustworthy and humane
