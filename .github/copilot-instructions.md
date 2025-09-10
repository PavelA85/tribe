# Copilot Instructions for this Repository

Purpose: This repo is a knowledge & process base for the Gentys men growth community (Lithuanian). It is NOT a typical code project; most artifacts are domain frameworks, meeting plans, method guides, and templates. Agents should optimize for information structuring, cross‑file synthesis, and producing new facilitation material consistent with existing formats.

## Core Domain Concepts
- Stages: Registracija → Įvadinis kursas (8 sav.) → Savarankiška gentis (ilgalaikė).
- Meeting Cadence: Weekly 3h standard circle; monthly “Raudonas” (mandatory, metrics + iteration); quarterly strategy; annual ritual.
- Accountability Stack: Metinis tikslas → Ketvirtinis fokusas → Savaitinis „Poelgis dėl savęs“. Tracked in a sheet structure (see `sablonai.md`). Penalties (euros) reinforce time & commitment norms.
- Roles (rotuojamos): Vedėjas, Laiko sargas, Raštininkas, Atsakomybės sergėtojas, Ryšio kurstytojas, Sveikatos pulso sergėtojas (see `framework.md`). Simpler earlier docs also use Šeimininkas / Vedėjas pairs (`PRATIMAI_IR_METODAI.md`).
- Inner Work (Vidinis darbas) 7-step protocol: topic surfacing → request from group → share → reflective paraphrase (“Ar gerai suprantu, kad…”) → reactions (no advice unless asked) → initiator response → optional expansion (`PRATIMAI_IR_METODAI.md`).

## File Landscape & When to Use
- `framework.md`: Current integrated operating model (roles, timing, decision process, conflict handling, metrics). Treat as source of truth for structure.
- `PRATIMAI_IR_METODAI.md`: Canonical methods library (inner work, poelgiai system, confrontation, emotions drill, crisis handling). Reuse phrasing & sequencing when generating new exercises.
- `sablonai.md`: All template blocks (Metinis tikslas, Q fokusas, Poelgis, 1:1, Konfliktas, Sheets schema). When adding a new template keep code‑fence style, concise Lithuanian labels, version note at bottom.
- `SUSITIKIMO_PLANAS_3S2E.md`: Example full 3h agenda with time-budget rationale—mirror its sectioning (targets, agenda, preparation, possible decisions) for new plans.
- `gentys.md`: External/public narrative & stats; use for copy alignment (mission wording, impact metrics) but do not mix internal penalties or raw process into outward-facing summaries.
- Long chat transcript: `chat.gpt.md` contains historical guidance—mine for phrasing but prefer consolidated frameworks above if conflicts.

## Style & Language Conventions
- Primary language: Lithuanian with occasional English role labels; keep original diacritics. When introducing an English term first, pair: Vedėjas (Facilitator). Avoid translating established ritual phrases.
- Structural lists use ordered numbering for time-sequenced steps, bullet lists for attributes, tables only when mirroring existing role or sheet schemas.
- Time formats: Use minutes with apostrophe (e.g., 5'). Durations for blocks: "12' + 3'" pattern.
- Emphasize key process verbs with caps only sparingly (e.g., PROBLEMA -> KODĖL SVARBU -> PASIŪLYMAS in decision format) following `framework.md` patterns.

## Accepted Patterns (Replicate)
- Decision proposal structure: Problema → Kodėl svarbu → Pasiūlymas → Eksperimentinė trukmė.
- Iteration limit: Max 1–2 concurrent experiments per month (“Ką iteruojam kitą mėnesį?”). Honor this constraint when suggesting improvements.
- Accountability consequences: Keep existing euro penalty magnitudes unless a new explicit policy doc introduces change.
- Feedback reception norm: Receiver responds only “Ačiū” (see transcript in `chat.gpt.md`).

## What NOT to Do
- Do not invent software build/test commands—this repo is content only.
- Do not alter historical metrics or research citations without source update; append clarifications instead.
- Avoid generic self-help additions; ground any new content in existing framework sections or explicit gaps the user states.
- Don’t merge public-facing (`gentys.md`) and internal procedural language in one document unless a new “mixed” artifact is requested.

## Typical Agent Tasks & Guidance
- Adding a new meeting plan: Clone structure of `SUSITIKIMO_PLANAS_3S2E.md`, keep total 180 min budget, include goals, detailed agenda with minute math validating 180, prep checklist, and optional decision recommendations.
- Creating a new exercise: Start from closest section in `PRATIMAI_IR_METODAI.md`; include: Kada naudoti / Tikslas / Etapai / Pavyzdžiai / Dažnos klaidos (if genuinely evidenced in other docs).
- Updating templates: Modify `sablonai.md` by adding a numbered section; preserve existing version footer (increment version if substantial structural change).
- Synthesizing a summary: Distinguish external impact (from `gentys.md`) vs internal mechanics (from `framework.md`).

## Quality & Consistency Checks
- Cross-reference roles, penalties, time blocks against `framework.md` before finalizing.
- Ensure Lithuanian phrasing matches prior sections (e.g., “Poelgis dėl savęs” not alternate casing).
- Keep new sections ≤ ~120 lines unless explicitly a long-form guide.
- Append version note (e.g., `V1.1 – pridėtas naujas pratimas X`) when evolving existing files.

## Escalation / Ambiguity Handling
If framework vs. methods doc conflict: prioritize `framework.md` for structure, `PRATIMAI_IR_METODAI.md` for micro-process detail. If unclear or proposing a novel system (e.g., new metric), flag with a brief “PASIŪLYMAS” section and mark as eksperimentas 4–8 sav.

---
Last updated: 2025-09-10
