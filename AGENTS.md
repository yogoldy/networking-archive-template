# Instructions for agents working in the Networking archive

## Mission

Turn career, recruiting, and networking knowledge into durable, reviewable
records. Important facts, decisions, writing preferences, outreach status, and
open questions must not exist only in chat memory.

## Cold-start gate

At the start of every task:

1. Read `README.md` and `docs/PROJECT_STATE.md`.
2. Read `docs/ARCHIVE_OPERATING_MODEL.md` and the durable document relevant to
   the request: Leo profile, detailed experience evidence, email style,
   outreach playbook, open questions, or source index. `docs/history/` is not
   a competing current instruction set.
3. Use `docs/SOURCE_FILE_PATHS.txt` to locate original material. Do not assume
   that the newest-looking filename is authoritative.
4. Preserve unrelated files and user changes. This is a cloud-synced archive,
   not a Git repository.

For career drafting, start with `docs/PROJECT_MEMORY.md` (the Leo profile) and
follow its relevant experience links.
**For any request involving the Darla Moore/business-school
work, read `docs/BUSINESS_SCHOOL_WORK.md` directly**; it is the canonical
detailed evidence record for that experience, including origin, ownership,
financial architecture, reconciliation boundaries, stakeholder outcomes,
current employment status, and separate product exploration. Do not rely on
the shorter project-memory summary alone. For outreach, also read the register
and applicable person note. Select accomplishments for Leo's actual request;
do not impose a fixed story formula. Read `docs/SOURCE_INDEX.md` for sources
outside the inventory.

## Evidence and authority

Use this order unless a claim-specific rule requires otherwise:

1. Leo's latest dated direct statement.
2. A current, role-appropriate primary document or tracker.
3. Sent-message, application, or screenshot evidence.
4. The reviewed legacy ChatGPT handoff.
5. Clearly labeled agent inference.

Label material conclusions as **confirmed**, **inferred**, or **unknown**.
Preserve conflicts and stale versions rather than silently choosing one. Dates
matter: a historical statement may remain valid history without describing the
present.

Prefer a link to the canonical record over copying mutable detail into several
documents. A link identifies where the authoritative detail lives and reduces
drift; it does not synchronize repeated text automatically. Repeat a fact only
when the local summary materially needs it, and treat every such summary as an
affected record when the canonical fact changes.

Information generally does not belong in the durable archive if Leo will never
need it. Exceptions are compact agent-facing rules that prevent unintended
external action, invented or overstated claims, source loss or overwrite, and
duplicated facts or stale statuses. Keep those controls in `AGENTS.md`, the
operating model, or source guidance—not in Leo-facing profile documents.

## Action boundaries

- Never send outreach, submit an application, contact a person, schedule a
  meeting, or modify an external record without Leo's explicit instruction.
- Never mark a draft as sent or an application as submitted without evidence.
- Do not alter a resume, cover letter, spreadsheet, tracker, or source artifact
  unless the current request authorizes that exact change.
- Do not move, rename, deduplicate, or delete source files as part of ordinary
  analysis.
- Do not expose private contact information or sensitive school/work material
  unnecessarily.

## Durable-update workflow

Treat a new source, durable correction/status report, accepted governing
decision, or explicit request to record a conclusion as a material intake.
Exploratory drafting, research, brainstorming, and unaccepted suggestions do
not automatically become durable facts or decisions.

For each material intake:

1. Identify the statement/source date, capture date, scope, and whether each
   material conclusion is confirmed, inferred, or unknown.
2. Keep source files in place unless Leo explicitly requests copying or
   reorganization; update the paths inventory if a new source file enters the
   archive.
3. Update every affected durable record, not only the visible answer. For
   correspondence, always consider whether Leo needs to act; automatically
   capture warranted actions and their supporting evidence/question links using
   the [outreach workflow](docs/OUTREACH_PLAYBOOK.md#Correspondence-action-review).
4. Add or revise `OPEN_QUESTIONS.md` only for a relevant, actionable missing
   answer; after resolution, record the canonical answer and intake mapping,
   then remove the question. Apply the same rule to person-note question lists.
5. Update `docs/PROJECT_STATE.md` when current focus, resume routing, operating
   state, or boundaries materially change. Detailed evidence scope belongs in
   `docs/SOURCE_INDEX.md` and the applicable experience record.
6. Append a dated entry to `docs/INTAKE_LOG.md` describing the source, affected
   records, deliberate no-change decisions, validation, and external actions
   not taken.

Before finishing, verify that important new project knowledge has been written
to the durable records, relevant links/inventory still resolve, and no external
action was taken implicitly. For correspondence, check affected questions and
tasks, reciprocal person-note/to-do links, and that every automatic change is
reported in the [latest scan](docs/OUTREACH_SCAN_UPDATE.md).
Use `docs/ARCHIVE_OPERATING_MODEL.md` as the
completion definition. Do not add Git, checksum, raw-copy, or domain-specific
routing requirements unless Leo explicitly changes this archive's lean model.
