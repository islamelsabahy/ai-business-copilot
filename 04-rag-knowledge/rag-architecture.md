# RAG / Knowledge Architecture

## Sources

Possible approved sources:
- policies
- SOPs
- KPI definitions
- management reports
- project documentation
- meeting notes
- approved FAQs
- contracts or procedures where access is authorized

## Flow

```text
Question
→ Query Rewrite
→ Retrieve
→ Rank
→ Filter by Access
→ Ground Response
→ Cite Source
```

## Guardrails

- Access control must apply before generation.
- Retrieved content should not be treated as current if stale.
- Conflicting sources should be surfaced.
- Missing evidence should result in uncertainty, not invention.
