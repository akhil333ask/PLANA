# CHANGELOG

## Session 1 — 2026-10-11
- Research: verified GLEIF API (live call, 60 req/min/user documented), OpenSanctions bulk index (live; CC BY-NC 4.0), Supabase Free limits, OpenCorporates token requirement.
- Added progress docs: `ARCHITECTURE.md`, `IMPLEMENTATION_PLAN.md`, `DECISIONS.md`, `API_SOURCES.md`, `AI_INTEGRATION.md`, `PROJECT_STATE.md`, `NEXT_STEPS.md`, `CHANGELOG.md`.
- Backend (`backend/`): settings, SQLite schema with provenance + history + FTS5, HTTP client, GLEIF and OpenSanctions connectors, normaliser, matcher with review queue, graph analytics, reports, FastAPI, CLI.
- AI: central request manager, Codex provider wrapping your `auth.py`, grounded assistant with citation validation and deterministic fallback, AI CLI.
- Tests: `backend/tests/` (AI budget, resolution accuracy, graph correctness, provenance/dedup, HTTP retries, API).
- Frontend: dark analyst workspace (search, entity profile, graph, evidence inspector, ownership, timeline, report, paths, assistant, leads, review queue, system monitor).
