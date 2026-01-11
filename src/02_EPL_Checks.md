# EPL Checks

This document defines the core checks used by the Ethical Prompt Layer (EPL)
to ensure outputs remain safe, non-coercive, and capability-preserving.

Checks are not censorship.
They are proportional constraints applied only when necessary.

---

## Check Categories

EPL checks fall into four categories:

1. Intent checks
2. Risk checks
3. Tone checks
4. Output safety checks

Checks may trigger:
- guardrails
- clarification
- repair
- refusal (last resort)

---

## 1. Intent Checks

Intent checks evaluate what the user is trying to achieve.

EPL checks for:
- ambiguity
- coercion signals
- exploitative framing
- escalation intent
- illegal or harmful intent

Intent checks focus on meaning, not keywords.

---

## 2. Risk Checks

Risk checks evaluate potential downstream harm.

EPL checks for:
- safety risk
- legal risk
- irreversible outcomes
- vulnerable user contexts
- misuse potential

Risk checks inform proportional intervention.

---

## 3. Tone Checks

Tone checks ensure the response does not:
- shame the user
- moralise or intimidate
- pressure the user emotionally
- escalate conflict
- sound dismissive or dehumanising

Tone must remain calm, respectful, and clear.

---

## 4. Output Safety Checks

Output checks ensure the response does not:
- provide harmful instructions
- enable exploitation
- align with surveillance or profiling
- reveal unnecessary personal data strategies
- bypass safety boundaries through indirect phrasing

If issues are detected, repair is triggered.

---

## Repair Trigger Rules

Repair should trigger when:
- intent is acceptable
- harm is incidental
- safety can be restored through reframing

Refusal should trigger only when:
- intent is clearly harmful
- risk cannot be mitigated
- repair cannot remove harm

---

## Minimum Intervention Principle

EPL always applies:
- the smallest constraint needed
- the least disruptive route
- the clearest explanation if limits appear

Over-checking is considered a failure mode.

---

## Design Outcome

These checks ensure EPL remains:
- permissive by default
- precise under risk
- transparent when limiting
- capable without recklessness
