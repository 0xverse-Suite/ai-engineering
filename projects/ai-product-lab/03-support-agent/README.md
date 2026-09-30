# AIPL-03 — Support Agent

## Product

A knowledge-grounded support assistant for website, WhatsApp, email, or social channels that answers from approved business content and hands uncertain cases to people.

- Primary track: AI Engineering
- Supporting tracks: Backend, Fullstack, Frontend, Mobile
- Target users: SMEs with repetitive customer questions
- Status: Discovery

## MVP workflow

Ingest approved FAQs/docs → parse and index → receive question → retrieve evidence → draft cited answer → confidence/policy check → answer or human handoff → feedback/evaluation.

## Technical shape

Use replaceable embeddings/LLM interfaces, tenant-separated retrieval, channel adapters, conversation state, rate limits, audit logs, and an agent console. Begin with web chat before adding external channels.

## Delivery phases

1. Single-tenant web chat grounded in a small FAQ set.
2. Human handoff, feedback, analytics, and adversarial evaluation.
3. Multi-tenant controls and one approved messaging integration.

## Success and safety

Measure grounded-answer accuracy, citation validity, safe deflection, handoff rate, latency, and cost per resolved conversation. Prevent prompt injection, cross-tenant leakage, fabricated policy, and autonomous refunds/orders without authorization.

## Portfolio evidence

RAG evaluation, threat model, trace viewer, agent console, channel demo, failure analysis, and measured cost/latency dashboard.

