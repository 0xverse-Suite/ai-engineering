# AIPL-14 — Developer Code Assistant

## Product

Explain code, trace unfamiliar repositories, generate learning-oriented walkthroughs, and answer questions with citations to the exact files and symbols.

- Primary track: AI Engineering
- Supporting tracks: Backend, Fullstack, Frontend
- Target users: students, junior developers, and engineering teams onboarding to codebases
- Status: Discovery

## MVP workflow

Connect/upload approved repository → parse symbols/dependencies → index code → ask question → retrieve relevant context → cited explanation → feedback and follow-up.

## Technical shape

Use language-aware parsing, repository-scoped retrieval, secret scanning before indexing, replaceable coding models, citation validation, and strict tenant/repository boundaries. Begin read-only.

## Delivery phases

1. One language, local sample repository, symbol search, and cited explanations.
2. Multi-file dependency tracing, onboarding guides, and evaluation tasks.
3. Approved private-repository integration and team knowledge workflows.

## Success and safety

Measure citation validity, task correctness, retrieval recall, latency, and learner comprehension. Do not execute untrusted code, expose proprietary repositories, leak secrets, or present generated code as verified.

## Portfolio evidence

Code-retrieval benchmark, architecture explorer, cited answer UI, security threat model, red-team results, and a demo on an open-source repository.

