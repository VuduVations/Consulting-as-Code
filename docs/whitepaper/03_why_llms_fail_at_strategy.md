# Why LLMs Fail at Strategy

Large Language Models are fluent.
Strategy requires correctness.

This distinction is fatal.

---

## Fluency Is Not Intelligence

LLMs are probabilistic sequence predictors.
They optimize for plausibility, not truth.

They:
- Predict likely next tokens
- Do not enforce constraints
- Do not validate math
- Do not reject invalid solutions

This is acceptable for drafting prose.
It is unacceptable for enterprise decision-making.

---

## The Core Failure Modes

### 1. No Constraint Enforcement
If an enterprise states:
- “We are air-gapped”
- “No cloud”
- “HIPAA only”
- “Code freeze for 18 months”

An LLM may acknowledge the constraint — and still violate it later.

LLMs do not *block* invalid architectures.
They merely describe them.

---

### 2. Mathematical Hallucination
LLMs cannot reliably:
- Distinguish gross vs. net impact
- Compute margins correctly
- Validate ROI, NPV, IRR
- Detect opportunity cost

They speak with confidence about numbers they did not compute.

Strategy is math.
Confidence without computation is deception.

---

### 3. No Determinism
Given the same input:
- LLM outputs vary
- Reasoning paths drift
- Recommendations change

This makes:
- Audits impossible
- Reproducibility impossible
- Trust impossible

Strategy cannot be temperature-dependent.

---

### 4. Sycophancy Bias
LLMs are optimized to please.

They:
- Side with the loudest voice
- Mirror executive framing
- Avoid contradiction

Consultants do this subconsciously.
LLMs do it by design.

Neither protects the truth.

---

## The Consequence

LLMs generate:
- Plausible strategies
- Elegant nonsense
- Fluent risk

They are powerful assistants.
They are dangerous decision engines.

Consulting-as-Code™ exists because **strategy requires refusal**, not generation.
