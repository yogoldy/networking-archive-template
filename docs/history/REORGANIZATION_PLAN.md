# Source reorganization plan

Historical migration record, moved to `docs/history/` on 2026-09-18. Its
description of root control-file placement is the 2026-09-16 layout; use the
[current home](../../README.md) and [operating model](../ARCHIVE_OPERATING_MODEL.md)
for today's documentation layout. Source-file routes and the migration record
remain unchanged.

Status: **Phase 2 completed and validated 2026-09-16**.

Leo approved a two-phase reorganization on 2026-09-16. This document records
the implemented information architecture and documentation rules. The complete
file-level old-path → new-path manifest was reviewed, Leo explicitly approved
Phase 2, and all 505 inventoried items were moved with original filenames
preserved.

## Design principles

1. Organize by purpose and working context, not merely by file extension.
2. Keep application bundles together when a resume, cover letter, screenshot,
   and supporting material belong to the same company or opportunity.
3. Separate reusable career identity documents from opportunity-specific
   submissions.
4. Preserve every original filename during the first move. Renaming is a
   separate decision after provenance is stable.
5. Do not deduplicate by filename. Repeated basenames may represent distinct
   versions or submissions.
6. Route ambiguous material to `legacy-unclassified/` with a review note rather
   than guessing.
7. Preserve old → new paths in a migration manifest and update durable path
   references after the move.
8. Treat Finder metadata, Office lock files, and saved-webpage support files as
   inventory items with limited evidentiary value, not substantive career
   records.

## Implemented top-level schema

```text
career-core/
  resumes/
  cover-letter-templates/
  transcripts/
  certifications/
  recommendations/
  profile-assets/

recruiting/
  applications/
  trackers/
  interview-prep/

outreach/
  correspondence/
  contacts-and-introductions/
  events/

experience-and-portfolio/
  employers/
  investment-projects/
  technical-training/
  volunteering/

education-and-leadership/
  coursework/
  organizations/

reference-materials/
  resume-examples/
  personal-statement-examples/
  career-guides/

legacy-unclassified/
  needs-review/
  system-metadata/
```

The root keeps only the archive-control layer: `AGENTS.md`, `README.md`,
`LEGACY_CHATGPT_KNOWLEDGE_EXTRACTION_PROMPT.md`, and `docs/`.

## README policy

Every top-level functional folder receives a concise `README.md` explaining:

- what belongs there and what does not;
- how its subfolders are organized;
- which records are authoritative, historical, or still unresolved;
- applicable naming and version-preservation rules; and
- links back to the root project state and relevant durable guidance.

Additional READMEs should exist at workflow boundaries where a user or agent
could otherwise misroute material:

- `career-core/resumes/`
- `recruiting/applications/`
- `recruiting/trackers/`
- `outreach/correspondence/`
- `legacy-unclassified/`

Do not add a README to every company, contact, or small leaf directory unless
that directory needs context that its parent cannot provide.

Distributed `README.md` and `AGENTS.md` files are control files, not career
source evidence. They must be excluded from the source-file inventory while
remaining covered by link and instruction review.

## Nested AGENTS.md policy

The root `AGENTS.md` remains the default. Add nested instructions only where a
folder has a materially different risk boundary:

| Folder | Additional rule focus | Decision |
| --- | --- | --- |
| `career-core/` | Do not declare a resume/template authoritative or overwrite a version without evidence and explicit authorization. | Added in Phase 2. |
| `recruiting/` | Do not submit applications, change tracker state, or infer `Applied`/`Active`; preserve opportunity bundles. | Added in Phase 2. |
| `outreach/` | Do not send, contact, schedule, or infer `Sent`; protect contact information and distinguish drafts from evidence. | Added in Phase 2. |
| `experience-and-portfolio/` | Root evidence and source-preservation rules are sufficient. | README only. |
| `education-and-leadership/` | Root evidence and source-preservation rules are sufficient. | README only. |
| `reference-materials/` | Root evidence rules plus README classification are sufficient. | README only. |
| `legacy-unclassified/` | Root rules plus a README review queue are sufficient. | README only. |

Nested instructions must supplement, not repeat or weaken, the root rules.

## Initial routing blueprint

[`REORGANIZATION_BLUEPRINT.tsv`](../REORGANIZATION_BLUEPRINT.tsv) mapped every
pre-migration root source file and top-level source subtree to a proposed
destination. More-specific rows override broader subtree rows. The blueprint
is a historical design input; the file-level manifest is the execution
authority, including its explicit metadata-quarantine overrides.

[`PROPOSED_PATH_MANIFEST.tsv`](../PROPOSED_PATH_MANIFEST.tsv) is the historical
execution record containing one literal old-to-new route for every inventoried
source file. Its `current_path` column records the pre-migration location.

Notable routing decisions:

- `Grad Recruiting/` is split by function rather than moved as one opaque
  folder. Company folders go to graduate-cycle applications; its trackers,
  certifications, resume area, interview drafts, Zev material, and portfolio
  analysis route separately.
- `GAM & CL/` remains an application-cycle bundle under recruiting rather than
  being split merely because it contains cover letters.
- `Resume/` remains a historical resume-version collection under career core.
- Employer and portfolio evidence is separated from applications to those
  employers.
- Formerly ambiguous root images, schedules, letters, and generic filenames
  were content-reviewed and assigned specific destinations. Finder metadata,
  Office temporary/lock files, and one stale personal shortcut are routed to
  metadata quarantine rather than treated as career evidence.

## Migration phases

### Phase 1 — Design and manifest

1. Approve this schema and routing policy.
2. Resolve each blueprint row into a literal file-level manifest containing the
   current path, proposed path, disposition, confidence, routing rule, and
   rationale. **Completed 2026-09-16.**
3. Flag collisions, ambiguous files, temporary/metadata files, and any path
   referenced by a durable document. **Completed 2026-09-16.**
4. Review the complete manifest with Leo. No moves occur in this phase.

### Phase 2 — Authorized move

1. Create the approved folder and documentation structure.
2. Add the planned READMEs and selective nested agent instructions.
3. Move only manifest-approved source files while preserving filenames.
4. Update `SOURCE_FILE_PATHS.txt` and all durable path references.
5. Record every unresolved or deliberately unmoved item.
6. Verify manifest coverage, source counts, old-path/new-path mapping, links,
   and absence of unapproved edits or external actions.

**Completed 2026-09-16.** Leo explicitly authorized execution. The migration
moved 476 substantive source items and 29 metadata-quarantine items, created
the planned READMEs and three selective nested `AGENTS.md` files, updated the
current-path inventory and durable references, and validated all 505 new
paths. No filename, source content, application status, tracker, or external
record was changed.

Renaming, deduplication, deletion, authoritative-version selection, and
content edits are outside this migration unless separately authorized.

## Continuing boundary

Phase 2 authorization is exhausted. Future moves, renaming, deduplication,
deletion, authoritative-version selection, and content edits require separate
task-specific authorization.
