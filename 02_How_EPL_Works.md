# How EPL Works

The Ethical Prompt Layer (EPL) operates as a structured decision layer that sits
between user input and AI output.

It does not generate intelligence.
It governs how intelligence is applied.

EPL evaluates intent, classifies risk, selects an appropriate response route,
and applies safeguards only where necessary.

---

## High-Level Flow

1. User input is received
2. Intent is interpreted
3. Risk level is classified
4. A response route is selected
5. The response is generated
6. Post-checks are applied
7. Repair logic runs if needed

This flow is designed to minimise harm while preserving usefulness.

---

## Step 1: Intent Interpretation

EPL analyses *what the user is trying to achieve*, not just what they typed.

This includes:
- contextual meaning
- ambiguity or uncertainty
- emotional signals
- potential downstream impact

Intent interpretation helps avoid overreaction to wording alone.

---

## Step 2: Risk Classification

Once intent is understood, EPL assigns a risk category.

Typical categories include:
- normal
- sensitive
- high-stakes
- harmful

Risk classification informs how much intervention is required — if any.

---

## Step 3: Route Selection

Based on intent and risk, EPL selects one of four routes:

- **Allow**  
  The request is safe and proceeds normally.

- **Allow with guardrails**  
  The request is valid but requires boundaries or framing.

- **Clarify**  
  The request is ambiguous or incomplete and needs user clarification.

- **Refuse with safe alternative**  
  The request presents clear harm and must be redirected.

Refusal is always a last resort.

---

## Step 4: Response Generation

The AI generates a response that aligns with the selected route.

EPL ensures:
- respectful tone
- non-coercive language
- clarity of explanation
- preservation of user agency

---

## Step 5: Post-Checks and Repair

After generation, EPL applies final checks to detect:
- unintended harm
- misleading outputs
- escalation risks

If issues are detected, a repair loop adjusts the response rather than blocking it.

---

## Design Outcome

EPL prioritises:
- redirection over suppression
- correction over punishment
- explanation over control

The system remains capable, transparent, and human-aligned.
