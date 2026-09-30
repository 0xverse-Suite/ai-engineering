# AIPL-15 — Industry Document Automation

## Product

Convert a high-volume industry document—such as an invoice, receipt, claim, result sheet, application, or purchase order—into validated data and an auditable business workflow.

- Primary track: AI Engineering
- Supporting tracks: Backend, Data Analytics, Fullstack
- Target users: one selected industry with repetitive document operations
- Status: Discovery

## MVP workflow

Select one vertical → define schema/rules → ingest document → classify/extract → validate and route exceptions → human approval → export or approved system handoff.

## Technical shape

Reuse OCR/extraction components from AIPL-02 while adding vertical schemas, business-rule validation, reconciliation, audit logs, queues, and role-based review. Treat each vertical as a product configuration, not an unrelated codebase.

## Delivery phases

1. Interview users and choose one legal, safe document class.
2. Build extraction, review, validation, and export with a sanitized test set.
3. Add exception routing, batch operations, analytics, and one approved integration.

## Success and safety

Measure straight-through processing, field accuracy, exception rate, review time, and cost per accepted document. Respect regulation, data residency, retention, and human accountability; never automate consequential approval solely from model output.

## Portfolio evidence

Vertical discovery report, schema/data dictionary, evaluation corpus, exception dashboard, audit trail, ROI/cost model, and privacy impact assessment.
