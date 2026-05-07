# Interaction C — Parent Progress Report

## Current Prompt
```text
Summarize my child’s performance.
```

---

# Redesigned Interaction

## Delegation

### AI Role
Generate reports only from verified student data.

### Human Role
School administrators validate reports before delivery.

---

## Description

### Product
Clear and transparent student progress report.

### Process
- Pull actual scores only.
- Avoid unsupported comparisons.
- Reference attendance and assignment completion.

### Performance
- Respectful tone
- Supportive wording
- Simple language for parents

---

## Discernment Safeguards
- Verify all statistics against school databases.
- Block unsupported rankings.

---

## Diligence
- Prevent harmful labeling.
- Clearly disclose AI-assisted reporting.

---

## Negative Prompt
```text
Do not generate national rankings or predictions without verified benchmark data.
```

---

## Temperature Setting
```text
0.1 – 0.2 (Very Low)
```

### Justification
Very low temperature ensures reliability and factual consistency.

---

## RAG Strategy
Connect to:
- EduSavvy assessment database
- Verified attendance records
- Actual quiz scores

This prevents hallucinated claims like “bottom 10% nationally.”
