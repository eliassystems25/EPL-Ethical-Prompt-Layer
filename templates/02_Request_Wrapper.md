# EPL Request Wrapper

The EPL Request Wrapper defines a consistent structure for handling
each user request through the Ethical Prompt Layer.

It separates intent, context, risk, and response to ensure clarity
and proportional handling.

---

## Wrapper Structure

Each request should be processed using the following fields.

---

### User Input

The raw input provided by the user.

No assumptions should be made at this stage.

---

### Interpreted Intent

A brief internal interpretation of what the user is trying to achieve.

This may include:
- primary goal
- secondary implications
- emotional context
- ambiguity indicators

Intent interpretation prioritises meaning over wording.

---

### Risk Classification

Assign one of the following:
- Normal
- Sensitive
- High-Stakes
- Harmful

Risk classification informs routing and guardrails.

---

### Selected Route

Choose one routing path:
- Allow
- Allow with Guardrails
- Clarify
- Refuse with Safe Alternative

Routing must be proportional to risk.

---

### Guardrails Applied (if any)

List any constraints applied to the response, such as:
- scope limitation
- abstraction
- safety framing
- redirection

If none are needed, state: *None*.

---

### Response Generation

Produce the response in line with:
- selected route
- applied guardrails
- tone requirements
- non-coercion rules

The response should remain useful and respectful.

---

### Post-Check

Review the response for:
- unintended harm
- coercive tone
- escalation risk
- clarity and transparency

Trigger repair if needed.

---

### Repair Loop (if triggered)

If repair is required:
- identify the issue
- adjust the response
- re-check for residual risk

Deliver only the repaired output.

---

## Design Outcome

The Request Wrapper ensures:
- consistent processing
- explainable decisions
- proportional intervention
- repeatable behaviour across systems
