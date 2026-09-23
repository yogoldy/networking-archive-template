# Archive operating model

This document defines how the Networking archive turns source material and
direct updates into durable project knowledge. It applies a lean,
first-principles approach suited to career records, source provenance, and
external-action risk.

This is the single detailed live governance record. On 2026-09-18 it absorbed
the current rules from [the historical decisions record](history/DECISIONS_AND_RULES.md).
Root and local `AGENTS.md` files remain concise action/cold-start gates.

**Last reviewed:** 2026-09-19.

The operating model governs cross-archive policy. Root `AGENTS.md` governs
execution gates and safety; local agent files govern folder-specific handling;
playbooks govern domain workflows. If guidance appears to conflict, preserve
the conflict and apply the higher-level rule until the canonical policy is
updated.

## First principles adopted

1. **Durable state beats chat memory.** A material fact, correction, accepted
   decision, status change, or unresolved conflict should be written to the
   applicable durable record rather than left only in conversation.
2. **Authority depends on the claim.** Preferences and intent, document facts,
   and proof of external action have different controlling sources. Apply the
   precedence in [Source authority](#Source%20authority); do not use one universal
   newest-file rule.
3. **Source, interpretation, and action are separate.** A source file can show
   what it contains; an agent can interpret it with an evidence label; neither
   proves that outreach was sent, an application was submitted, or a tracker
   was updated.
4. **Preserve evidence, edit current controls.** Original source evidence,
   sent messages, and `INTAKE_LOG.md` are preserved historical records; current
   control documents may be edited to reflect the latest accepted state. Never
   rewrite preserved evidence as though an earlier claim never existed.
5. **Only actionable unknowns are queue state.** A missing or conflicted fact
   belongs in `OPEN_QUESTIONS.md` only when a relevant answer is needed for a
   current decision, message, status, or next action. Once resolved, record the
   canonical answer and intake mapping, then remove the question.
6. **One input can affect several records.** A material intake is not complete
   until every affected durable record is updated, or the intake log explains
   why a normally relevant record did not change.
7. **The state page is a fast operational handoff.** `PROJECT_STATE.md` should
   show current focus, where to resume, operating state, and action boundaries.
   Detailed evidence scope and limitations belong in `SOURCE_INDEX.md` and the
   applicable experience record.
8. **Completion is observable.** The archive should be able to show which
   source was used, how claims were classified, which records changed, which
   questions remain, and that no external action occurred implicitly.
9. **Preserve originals and provenance.** Career-source contents and original
   filenames remain unchanged. Index and interpret them; do not move again,
   overwrite, or declare a version authoritative without evidence and
   task-specific authorization. The authorized 2026-09-16 reorganization is
   recorded by its old-to-new manifest.
10. **Use proportional controls.** This archive should adopt only controls that
    reduce a real evidence or continuity risk. Complexity is not a goal.
11. **Keep only useful durable knowledge.** Information generally does not
    belong in the archive if Leo will never need it. Compact agent-facing
    safeguards remain justified when they prevent unauthorized external action,
    unsupported claims, source loss, or canonical-record drift. Keep those
    controls in agent/governance/source guidance rather than Leo-facing files.

## Source authority

1. Leo's latest dated direct statement controls preferences, intent, and
   present-status corrections.
2. A current, role-appropriate primary document or tracker controls its own
   facts and workflow.
3. Sent-message, application, or screenshot evidence establishes external
   actions; Leo's dated direct confirmation is also sufficient.
4. The reviewed legacy handoff preserves historical context, not current status.
5. Agent inference must be labeled and yields to stronger evidence.

Label material conclusions confirmed, inferred, or unknown, with source and
date. Preserve conflicts and historical versions; absence of evidence is not
a negative fact. "Confirmed as Leo's account" does not mean an inaccessible
workbook or transcript was independently inspected.

## Document selection and status

Leo's 2026-09-18 reset makes old recruiting applications/contacts inactive;
do not investigate or revive them by default. Industry-specific resumes and
cover letters remain reference exceptions. Identify these before moving old
materials. Keep routine verification notes in source records, not recurring
questions or qualifications on established accomplishments. Product-market
validation remains a known development stage, not a rebuttal to prototype work.

- Retain the historical three-resume strategy: S&T/finance,
  consulting/business-general, and insurance. These are document-selection
  buckets, not mandatory narrative categories for every message.
- Confirm audience, factual currency, Leo's approval, and the actual
  authoritative file before using or attaching a career document. Neither
  filename polish nor latest modification time decides authority. Do not
  silently overwrite approved wording or merge incompatible narratives.
- Drafted is not Sent. Applied/Submitted require submission evidence or Leo's
  dated confirmation; Active requires a dated current-status source. Replied
  and Meeting planned likewise require evidence or dated confirmation.
- Reverify time-sensitive contact roles before outreach; research compensation,
  hiring, and program information afresh when requested.
- New outreach uses the [Markdown register](../outreach/OUTREACH_REGISTER.md)
  and a corresponding person/conversation note, kept consistent. Historical
  spreadsheets remain evidence and are not silently migrated or synchronized.
  A queue row never authorizes sending, contacting, scheduling, or an external
  record change.

## Workspace and documentation boundaries

- Project home: `/Users/leogoldberg/Documents/School folders/Networking`.
  Cloud-synced and intentionally non-Git. Leo authorized consolidating sources
  into root `resumes/`, `cover-letters/`, `evidence/`, and opaque `old/` areas
  on 2026-09-18, followed by later manual cleanup. The current source inventory
  is maintained only in [Source File Paths](SOURCE_FILE_PATHS.txt); historical
  counts and migration mappings do not establish current contents. Future
  source moves, renames, deletion, deduplication, or edits need specific
  authorization.
- The legacy handoff stays at its original Downloads path; do not copy it.
- The approved 2026-09-16 migration used reviewed routes and separate approval
  before physical moves; it does not authorize further source reorganization.
  The [historical plan](history/REORGANIZATION_PLAN.md) and migration TSVs retain
  that decision trail.
- Use concise READMEs at functional/workflow boundaries, not every leaf folder.
  Nested instructions are justified only by distinct risk: evidence, archive,
  outreach. All such control files are excluded from the source
  inventory.
- Leo approved light control-document consolidation and use of the existing
  folder as an Obsidian vault on 2026-09-18. Native Markdown links and built-in
  bookmarks are sufficient; no second archive, community plugins, scripts,
  databases, required properties/tags, or new dashboard layer.

## Durable record roles

| Record | Governing purpose |
| --- | --- |
| `AGENTS.md` | Mandatory cold-start, authority, action-boundary, intake, and completion behavior. |
| `README.md` | Human entry point and map of the durable layer. |
| `PROJECT_STATE.md` | Current focus, resume routing, operating state, and action boundaries. |
| `PROJECT_MEMORY.md` | Leo profile: durable background, roles, goals, geography, strengths, drafting sensitivities, and links to detailed evidence. |
| `BUSINESS_SCHOOL_WORK.md` | Detailed, evidence-bounded synthesis of the complex business-school model experience for future positioning and outreach. |
| `EMAIL_STYLE.md` | Accepted drafting preferences and their limits. |
| `OUTREACH_PLAYBOOK.md` | Approved process and proposed workflow, never authorization to act. |
| `ARCHIVE_OPERATING_MODEL.md` | Sole detailed current source, document, status, workspace, and intake rules. |
| `OPEN_QUESTIONS.md` | Bounded queue of genuinely actionable unresolved conflicts and missing decisions. |
| `SOURCE_INDEX.md` | Provenance, scope, authority, and limitations of important source families. |
| `SOURCE_FILE_PATHS.txt` | Paths-only inventory of source files already in the archive. |
| `INTAKE_LOG.md` | Dated audit trail of material inputs, affected records, and deliberate omissions. |
| `outreach/OUTREACH_REGISTER.md` and person notes | Lean contact index plus dated conversation history, preparation context, and links to explicit To-Do actions. |
| `docs/history/` | Retired setup and decision records; historical evidence, not live instructions. |

## Canonical routing and mirror rules

| Fact or workflow | Canonical record | Permitted summary/mirror |
| --- | --- | --- |
| Contact method and compact current outreach status | `outreach/OUTREACH_REGISTER.md` | Person Snapshot and Project State may summarize it; the register wins. |
| Detailed emails, calls, introductions, and relationship context | Person note under `outreach/correspondence/people/` | Register links to it; do not copy full history elsewhere. |
| Leo's personal actions, including warranted correspondence actions | `docs/LEO_TODO.md` | Person notes link to the single task; passive waiting is not mirrored as a task. |
| Current focus and resume routing | `docs/PROJECT_STATE.md` | Summary only; exact status and evidence remain canonical elsewhere. |
| Career accomplishments and source-bounded experience | Applicable detailed experience record | Leo profile and person preparation context link to relevant sections. |
| Current resume authority | `resumes/README.md` and Leo-approved current file | Drafting records may identify the selected file; old files remain reference evidence. |
| Provenance, source meaning, and verification limits | `docs/SOURCE_INDEX.md` | Detailed claims stay in the applicable experience record. |
| Current source paths | `docs/SOURCE_FILE_PATHS.txt` | Other documents link to it; they do not maintain a second inventory. |
| Historical durable changes and validation | `docs/INTAKE_LOG.md` | Not a current-state or task source. |

When a mirror disagrees with its canonical record, consult the canonical record
first, identify the scope and date of each claim, update the intentional mirror
only if it materially helps its local reader, and record a material correction
or deliberate no-change decision in the intake history. Links route agents but
do not synchronize repeated text automatically.

## Intake boundary and routing

A material intake occurs when Leo supplies a new source, gives a durable factual
correction or status update, accepts a governing decision, or asks that a
useful conclusion be recorded. For each material intake:

1. Identify the statement/source date, capture date, scope, and evidence level.
2. Preserve a supplied source at its indexed functional path unless Leo
   explicitly authorizes a copy or reorganization. Add its path to the
   inventory if it is a new archive source file.
3. Route the supported claims to the applicable durable records. Do not copy
   large source contents into the agent layer.
4. Preserve conflicts and update `OPEN_QUESTIONS.md` when uncertainty remains.
5. Update `PROJECT_STATE.md` when current focus, resume routing, operating
   state, or boundaries materially change. Update evidence scope in
   `SOURCE_INDEX.md` or the applicable experience record.
6. Append an `INTAKE_LOG.md` entry naming the source, changed records,
   deliberate no-change decisions, validation performed, and external actions
   not taken.

For inbox reconciliation, the outreach register is the canonical contact and
contact-method index; person notes remain canonical for detailed conversation
history. Only explicitly mapped existing contacts may be reconciled. Account-
scoped email evidence can support status and open-question updates, but scanning
does not authorize sending mail, changing Mail state, creating contacts, or
duplicating contact details across person notes.

After every successfully completed inbox reconciliation, refresh
`OUTREACH_SCAN_UPDATE.md` as the replaceable operational record of that run.
Include the scan date, accounts, method, external-action boundary, and result.
When nothing new matched, remove the prior correspondence delta and record an
explicit no-new-correspondence result. Always consider Leo's next action using
the [correspondence action review](OUTREACH_PLAYBOOK.md#Correspondence-action-review).
Automatically capture warranted tasks and supporting person-note evidence and
question links; report every applied change in the scan. Other canonical
reconciliation remains approval-gated. Verify reciprocal links and preserve
unaffected outstanding work, including during empty scans.

Keep experience substance in its canonical record, then link relevant sections
from person-note Preparation context. Draft freely in chat for Leo's chosen
accomplishment, recipient, and purpose; no stock narrative or compulsory
experience combination applies. Unsent drafts do not become a permanent CRM
layer. Preserve exact sent wording under dated Conversation history. Do not
copy detailed contact status into every memory/state summary; those pages
should route to the register and person note.

Maintain `OPEN_QUESTIONS.md` as a bounded working queue of genuinely actionable
missing answers only. When a question is resolved, write the canonical answer
to the applicable durable record, append the mapping and validation to
`INTAKE_LOG.md`, and remove the question from the queue. Do not keep resolved
or retired sections there. If none remain, state “No open questions.” Explicit
personal actions belong once in `LEO_TODO.md`; person notes link to its Outreach
section. Passive waiting remains status context, not a task. Immutable
historical sources remain evidence, not live documentation.

Exploratory drafting, brainstorming, research, and unaccepted suggestions are
not automatically durable career facts or decisions. They become durable when
Leo asks to record them, supplies them as a factual correction/status report,
provides a source that changes a material evidence record, or accepts a governing
decision. A draft never becomes `Sent`, and a discussed application never
becomes `Submitted`, without the required evidence.

## Completion definition

A material archive update is complete when:

- the input and its provenance are identified;
- every material conclusion is confirmed, inferred, or unknown;
- all affected durable records are updated or deliberate no-change reasons are
  recorded;
- conflicts and open questions remain visible;
- the state page reflects any changed current focus, routing, operating state,
  or boundary;
- the source inventory and internal links still resolve where affected; and
- no outreach, application, tracker change, document overwrite, or other
  external action was taken without explicit authorization.

Manual/read-only link and inventory checks are expected at completion.
Automated validator infrastructure, checksum systems, and exact-byte manifests
remain out of scope.

## Controls deliberately out of scope

- Git branches, commits, and repository-history recovery.
- Checksums, exact-byte manifests, automated validators, and test suites.
- Copying every external artifact into the workspace.
- Workout/session directories, per-session companion notes, metric ledgers,
  and workout-specific status tables.
- Mandatory structured rows for every exploratory conversation.

The Networking archive remains documentation-only, non-Git,
source-content-preserving, and proportionate to career-record risk.
