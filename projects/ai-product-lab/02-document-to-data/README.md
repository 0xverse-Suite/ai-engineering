# AIPL-02 — Document-to-Data

## Product

Convert invoices, receipts, purchase orders, bank statements, tables, and forms into validated Excel, CSV, or JSON.

- Primary track: AI Engineering
- Supporting tracks: Backend, Data Analytics, Frontend
- Target users: operations, accounting, procurement, and small businesses
- Status: Discovery

## MVP workflow

Upload PDF/image → OCR/layout analysis → document classification → schema extraction → validation/confidence flags → human correction → XLSX/CSV/JSON export.

## Technical shape

Use a replaceable OCR/layout pipeline, schema-constrained extraction, deterministic validators, duplicate detection, a review table, and provenance linking every value to page/region. One engine may support several vertical templates, but each template needs its own evaluation set.

## Delivery phases

1. One document type and one export schema with manual correction.
2. Confidence scoring, batch processing, and reconciliation totals.
3. Additional templates, audit logs, and approved integrations.

## Success and safety

Measure field accuracy, table accuracy, correction time, failed-page rate, and cost per page. Never expose bank/customer data; encrypt uploads; use short retention; label low-confidence values; do not claim accounting correctness without review.

## Portfolio evidence

Sanitized test corpus, extraction benchmarks, data dictionary, correction UI, exported workbook, architecture diagram, and privacy threat model.

