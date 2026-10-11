# PROJECT STATE

Last updated: 2026-10-11, session 2 (resume checkpoint, written before coding).

## Honest status at the start of session 2
Session 1 ran out of budget before it saved everything. Its docs listed P7–P9 as DONE, but the code was never committed.

Present and reviewed: `backend/app/{settings,db,http}.py`, `schema.sql`, `connectors/{gleif,opensanctions}.py`,
`resolution/{normalize,matcher}.py`, `graph/{paths,analytics}.py`, `backend/.env.example`, `requirements.txt`.

Missing (session 2 is building these, in this order):
1. `backend/legacy_ai/` (your `auth.py` verbatim + `config.py` env shim)
2. `backend/app/ai/{manager,providers,assistant,cli}.py`
3. `backend/app/{reports,api,cli}.py`
4. `backend/tests/*`
5. Frontend pages + `lib/api.ts` + `next.config.mjs` rewrite
6. `AI_INTEGRATION.md`

If this file still says "resume checkpoint", session 2 also stopped early. Check which of the files above exist, then continue from the first one that's missing.
