# AIPL-01 — ClipForge

## Product

Upload a long podcast, interview, webinar, or lecture and receive reviewable short clips with captions and export presets for Reels, Shorts, and TikTok.

- Primary track: AI Engineering
- Supporting tracks: Backend, Frontend, UI/UX, Graphics Design
- Target users: creators, podcasters, churches, educators, and media teams
- Status: Discovery

## MVP workflow

Upload → media validation → speech transcription → topic/segment scoring → candidate clip boundaries → caption timing → preview/editor → MP4/SRT export.

## Technical shape

Use FFmpeg for media operations, a replaceable speech model, scene/silence detection, an LLM-based ranking layer, background jobs, object storage, and a web review interface. Keep transcripts and clip decisions inspectable.

## Delivery phases

1. Deterministic upload, transcription, manual time-range clipping, and caption export.
2. Automated candidate ranking with an evaluation set and human accept/reject feedback.
3. Templates, multi-format rendering, cost controls, and deletion/retention settings.

## Success and safety

Measure accepted clips per source hour, caption error rate, time to first preview, render failures, and cost per processed hour. Require rights to uploaded media; avoid biometric identification; delete source media on request; never auto-publish without confirmation.

## Portfolio evidence

Architecture diagram, evaluation report, caption-quality samples, accessible editor screenshots, cost model, and a demo using licensed or self-created media.

