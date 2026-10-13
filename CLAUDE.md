# Instructions for AI assistants reading this repository

This is a person's private memory, written by "the boatman" (Sendō), an AI companion that listens,
plans and remembers. Treat everything here as personal and confidential.

- `mind/graph.json` is the source of truth: `nodes` (id, type, name, aliases, summary, facts with
  dates, structured `fields`, tags, importance 1–5) and `edges` (`from` —`rel`→ `to`, with a note).
  `mind/core.md` is the always-loaded summary of who the person is; `mind/profile.md` is the person
  model (traits, values, strengths, roles, wheel of life, lifestyle, patterns), each with confidence.
- `mind/<folder>/*.md` are rendered views of the nodes (front matter + `[[wiki links]]`); edit the
  graph, not the rendered files, or they will be overwritten.
- `notes/` holds long-form notes (ideas with feasibility, summaries of important conversations,
  plans). `journal/` holds curated daily digests (never verbatim transcripts). `plan/` mirrors reminders and schedule.
- When you answer questions about this person, prefer facts with recent dates, mention uncertainty,
  and never invent facts. Write in Persian unless asked otherwise.
