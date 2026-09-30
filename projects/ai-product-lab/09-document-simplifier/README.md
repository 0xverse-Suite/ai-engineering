# AIPL-09 — Document Simplifier

## Product

Explain contracts, tenancy agreements, employment documents, insurance policies, and terms in plain language while preserving citations to the original text.

- Primary track: AI Engineering
- Supporting tracks: Backend, Frontend, UI/UX
- Target users: individuals and small businesses reviewing complex documents
- Status: Discovery

## MVP workflow

Upload → OCR/text extraction → section mapping → clause classification → cited plain-language explanation → dates/obligations/questions → human review → report export.

## Technical shape

Preserve page/section provenance, use structured outputs, extract facts separately from explanations, flag unreadable/ambiguous text, and include jurisdiction-neutral limitations. Do not rank legal risk as fact.

## Delivery phases

1. One document class with section summaries and citations.
2. Dates, obligations, comparison view, and question prompts.
3. Additional document types and approved professional-review handoff.

## Success and safety

Measure citation correctness, omission rate, factual consistency, readability, and user correction. Clearly state “not legal advice,” protect documents, avoid definitive legal conclusions, and encourage qualified review for consequential decisions.

## Portfolio evidence

Citation evaluation, redacted examples, accessible comparison UI, limitation language, threat model, and extraction architecture.

