# Working notes for Claude sessions — open-swarm-outputs

## This lane
- **Empty.** Intended as a drop for swarm/agent run outputs; nothing has ever been filed here.
- **Do not invent work in this repo.** An empty repo is not a gap that needs filling.
- Finished deliverables go to `jordan-projects`, which is the deliverables drop, one folder per project.
  Use that unless Jordan says otherwise.
- If this is still empty in a few months, the honest move is to propose deleting it rather than finding
  it a purpose.

## Rules that apply here

- Ambiguous ask → up to 5 short questions before building. Never guess constraints.
- **UNSURE beats plausible.** Never state a fact, name, or number you have not verified.
- **Diagnosis → ACH.** Competing hypotheses, ranked by fewest inconsistencies, refuted not confirmed.
- Minimal surgical edits. Check output, never status. Verify with a read-back before claiming success.
- One lane per session. Name columns + LIMIT in SQL. Bulk row analysis (>~20 rows) → the
  `agent-worker` edge function on `neurodashboards`, not SELECTs into context.
- Anything only Jordan can do → task on `agent_tasks` (Supabase `neurodashboards`,
  `dprdnrgjkzgfgtcsguuq`) assigned `jordan`. If it is not on the board, it does not exist.

**The master map lives in `mission-control/CLAUDE.md`.** Read it before any system-wide work.
