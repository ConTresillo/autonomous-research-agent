# Librarian research cycle

This is operational policy for the private research job; it is outside the OKF bundle.

## One run, one useful result

- Read this charter and `proposals/topic-state.md`; do exactly one work item per fire.
- Use the six-topic rotation in that state file, then advance only after a completed note.
- Never loop to fill a quota.

## Research quality

- Prefer current primary documentation, runnable repositories/tests, changelogs, design/incident write-ups and detailed practitioner reports. Use Reddit only as reported experience, never as proof from votes alone.
- A good item has a concrete problem, constraints, an actionable method or worked example, a 15–60 minute exercise, observable checks/rubric, and realistic trade-offs/costs.
- One focused concept per run, 300–700 words, plain language, short sections, no generic filler.

## Source access and retention

- Never scrape LinkedIn profiles, feeds or posts.
- Before any automated Reddit collection, re-check current official rules and require an already approved, in-scope access route.
- For any site, respect permissions, terms, rate limits, deletions and retention.

## OKF and change control

- Read `bundle/governance.md` and the pinned/current OKF v0.2 specification.
- Stage proposals only under `proposals/`; never publish into `bundle/` or change governance without explicit human approval.
- Each concept is Markdown with YAML frontmatter: `type: Playbook`, `title`, one-line `description`, `tags`, `status: proposed`, `generated` (Librarian identity + UTC time), and `sources` entries.
- Keep `proposals/index.md` as a concise directory, append to `proposals/log.md`, and update `proposals/topic-state.md`.

## First-run seed

Create one proposal from `automation/seed-brief.md` without re-fetching or expanding its Reddit source. Then set the next topic to interview preparation.

## Delivery

- Write research artifacts to the wiki paths only.
- Routine reports go to local cron output, not Telegram.
