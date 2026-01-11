# Risk Classification

Risk classification is a core function of the Ethical Prompt Layer (EPL).

It determines how much intervention — if any — is required before an AI
response is delivered.

Risk classification is not moral judgment.
It is an operational assessment of potential harm.

---

## Purpose of Risk Classification

EPL uses risk classification to:
- avoid unnecessary restriction
- prevent real-world harm
- preserve system usefulness
- apply safeguards proportionally

Most inputs should pass with minimal or no intervention.

---

## Risk Categories

EPL typically classifies requests into four categories.

---

### 1. Normal

Requests that are:
- benign
- informational
- creative
- exploratory

These requests proceed without restriction.

**Response behaviour:**
- full capability
- no added guardrails
- standard tone and depth

---

### 2. Sensitive

Requests that may involve:
- emotional distress
- personal difficulty
- vulnerable topics
- ethically delicate contexts

These requests are allowed but handled with care.

**Response behaviour:**
- supportive tone
- careful framing
- avoidance of escalation
- optional grounding or clarification

---

### 3. High-Stakes

Requests where incorrect handling could cause:
- significant personal harm
- legal consequences
- safety risks
- irreversible outcomes

These requests require additional structure.

**Response behaviour:**
- strong clarity
- explicit boundaries
- emphasis on safe handling
- possible clarification before proceeding

---

### 4. Harmful

Requests that clearly involve:
- violence
- exploitation
- coercion
- abuse
- illegal or dangerous action

These requests are not fulfilled directly.

**Response behaviour:**
- refusal with explanation
- redirection to safe alternatives
- non-judgmental language
- preservation of dignity

---

## Proportionality Principle

EPL applies the **minimum intervention required** for safety.

- Normal → no restriction  
- Sensitive → gentle framing  
- High-stakes → structured guidance  
- Harmful → refusal + redirection  

Over-classification is considered a system failure.

---

## Dynamic Classification

Risk is not static.

EPL may reclassify during:
- clarification
- follow-up questions
- context expansion

This allows the system to adapt without locking users into rigid categories.

---

## Design Outcome

Risk classification enables EPL to:
- stay permissive by default
- intervene only when necessary
- remain aligned with human dignity
- preserve capability while reducing harm
