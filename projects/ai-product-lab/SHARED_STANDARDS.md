# Shared Product Standards

Every project README defines the customer, problem, MVP, system flow, track roles, milestones, success measures, risks, and portfolio evidence.

## Required engineering controls

- Keep providers and models replaceable behind interfaces.
- Record model/version, prompt/configuration, input provenance, latency, and cost for evaluations.
- Use asynchronous jobs for long media/document processing.
- Validate model output before export or downstream actions.
- Separate original uploads, derived artifacts, metadata, and logs.
- Apply retention/deletion policies and least-privilege access.
- Never use private customer material as training data without explicit permission.

## Required product controls

- Start with one target user and one finished outcome.
- Define fair-use and abuse controls from measured costs rather than marketing assumptions.
- Provide progress, failure recovery, editable results, export, and deletion.
- State limitations; human review remains required for legal, financial, medical, hiring, and other consequential decisions.

## Definition of MVP complete

One user can complete the core workflow end to end; a documented evaluation demonstrates acceptable quality; failure cases are visible; cost and latency are measured; privacy/security decisions are documented; and another student can reproduce the setup.

