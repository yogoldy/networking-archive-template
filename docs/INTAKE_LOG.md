# Intake log

## 2026-09-22 — Leo confirmed John Flores call time

- **Source:** Leo's direct report that he sent the reply; exact sent time was
  not supplied.
- **Confirmed:** Leo accepted John's Thursday 1:00 p.m. call proposal and
  provided his phone number for the call.
- **Durable updates:** Added the exact sent wording to John's note, resolved
  Q-007, removed the completed response task, aligned John's Snapshot/register,
  and updated Project State. The answer and task are now represented once in
  the canonical records.
- **Deliberate no-change:** No calendar event or reminder was created; an
  agreed call time is not separate calendar evidence. No external Mail action
  occurred.
- **Validation:** Checked the affected question, task, reciprocal links, John
  status alignment, and latest scan/direct-intake reporting.

## 2026-09-22 — John Flores call-time question captured

- **Source:** Local MCP read-only Mail scan of `leog@email.sc.edu`; John Flores
  message received 2026-09-21 at 9:35 p.m. EDT, subject `Introduction — Leo
  Goldberg`.
- **Confirmed:** John asked whether 1:00 p.m. Eastern works for a call and said
  he would call while driving. Leo's availability is unknown.
- **Automatic durable capture:** Added Q-007 to [Open questions](OPEN_QUESTIONS.md)
  and one linked answer task to [Leo To-Do](LEO_TODO.md), with reciprocal links
  in John's note. These are the only canonical changes applied automatically.
- **Pending approval:** Person-note conversation-history reconciliation and
  register/Snapshot status alignment remain proposed; no meeting or calendar
  event was inferred.
- **Validation:** Checked the affected task, question, reciprocal links, and
  latest scan reporting. No external Mail action occurred.

## 2026-09-19 — Canonical routing and ancillary-document boundaries

- **Decision:** Refocused `SOURCE_INDEX.md` as a provenance and verification
  map rather than a second career-evidence narrative. `SOURCE_FILE_PATHS.txt`
  remains the sole current paths-only inventory.
- **Governance updates:** Added canonical routing, mirror-repair behavior,
  governance precedence, current-source preservation wording, and manual
  validation boundaries to `ARCHIVE_OPERATING_MODEL.md`. Added the bottom
  `Ancillary docs & agent support` section to the root README.
- **Audit basis:** An independent Luna review identified repeated inventory
  counts, ambiguous mirror authority, overlapping rule layers, and stale
  preservation wording. The recommendations were incorporated; no new
  validator or documentation layer was created.
- **Validation:** Live 505-count duplication was removed from the current
  routing documents, the ancillary links were checked, and the decoded
  relative-link scan returned zero broken links.
- **No external action:** No source files, resumes, correspondence, Mail
  state, applications, or external records were changed.

## 2026-09-19 — Email style refined: syllogistic compression

- **Confirmed by Leo:** Strong outreach writing should be concise and warm by
  connecting a specific personal fact to its practical relevance and then to a
  low-friction ask. Avoid redundant AI-sounding lists and generic scheduling
  instructions.
- **Canonical example:** Leo preferred the sent John reply's location sentence
  (“...Boynton Beach (which is about an hour north of Miami), so I'm open to
  opportunities...”) because it makes the relevance explicit. He also preferred
  “I am glad to work around your schedule, so feel free to suggest some times
  that work best for you” because it combines warmth and action naturally.
- **Durable update:** Added a Syllogistic compression section to
  `docs/EMAIL_STYLE.md` with before/after examples. No email was rewritten or
  sent, and no person-note history was changed.

## 2026-09-19 — Outreach correspondence reconciliation skill

- **Source and authorization:** Leo approved creating a local skill that
  reconciles Apple Mail correspondence from `leogoldberg36@gmail.com` and
  `leog@email.sc.edu` with existing outreach records.
- **Durable changes:** Added the canonical Contact method field to the outreach
  register; recorded inbox-reconciliation routing in the playbook, operating
  model, and project state. Existing contact methods remain `Unknown` because
  no evidenced recipient addresses or phone numbers were present in the live
  Markdown records.
- **Skill behavior:** The local `outreach-correspondence-sync` skill matches
  only existing contacts, defaults to a dry run, follows links to affected
  questions/tasks/state, and requires approval before applying scheduled
  archive changes. Unknown or ambiguous senders are ignored.
- **Validation:** The skill validator passed; all four register rows use the new
  six-column schema; all four register/person-note statuses align; synthetic
  matched inbound, matched outbound, unmatched, and ambiguous cases followed
  the required match/ignore/stop behavior; the scheduled path requires approval
  and remains disabled; all Markdown files have zero broken relative links.
- **External actions:** No inbox was scanned, no message was sent or modified,
  no unknown contact was created, and no schedule was enabled.

## 2026-09-19 — Project Memory converted to Leo profile

- **Decision:** Kept the stable `docs/PROJECT_MEMORY.md` path but retitled and
  narrowed the document to Leo's durable education, credentials, professional
  roles, career goals, geography, availability, strengths, drafting
  sensitivities, and links to detailed evidence.
- **Removed from the live profile:** Project identity, individual relationship
  history, historical outreach stopping points, inactive contact questions,
  and detailed business-school/product evidence. Relationship status remains
  canonical in the outreach register and person notes; historical context
  remains in dated intake/history records.
- **Drafting system:** Retained `EMAIL_STYLE.md` for voice and editing guidance
  and `OUTREACH_PLAYBOOK.md` for preparation, workflow, CRM handling, and
  action boundaries. No additional email-drafting document was created.
- **Operating principle:** Added that information generally does not belong in
  the durable archive if Leo will never need it. Compact agent-only safeguards
  remain justified when they prevent unauthorized external action,
  unsupported claims, source loss, or canonical-record drift; those controls
  belong in agent/governance/source guidance rather than Leo-facing files.
- **Routing:** Updated all live labels from “career index and cross-project
  context” to “Leo profile” without renaming the file. Historical Intake Log
  entries retain their original wording.
- **Validation:** A fresh independent file-only cold-start audit reconstructed
  Leo's roles, goals, geography, strengths, and drafting sensitivities; located
  the correct email/outreach workflow; enforced direct reading of
  `BUSINESS_SCHOOL_WORK.md` for Darla Moore requests; and found no relationship
  or status dump in the profile. All relative Markdown targets resolve.
- **No external action:** No person status, resume, source artifact,
  correspondence, application, meeting, reminder, or external record changed.
  The archive remains intentionally non-Git.

## 2026-09-19 — Greg identity, administrative title, and canonical-link rule

- **Confirmed by Leo:** Greg is the dean, the principal budget stakeholder,
  and Leo's formal direct supervisor for the business-school work.
- **Title clarification:** The on-paper title Leo recalls was “Executive
  Assistant,” used as an administrative employment label rather than a
  description of his expected work. No functionally accurate project title was
  established. Professional materials should describe the actual modeling
  work and direct reporting relationship; the administrative title should be
  used only when an official-record context requires it.
- **Durable updates:** Corrected the canonical business-school account, career
  index summary, and Source Index locator. Greg's person note and register
  already identified him as dean/direct supervisor and required no change.
- **Operating principle:** Added to `AGENTS.md` that mutable detail should be
  linked to one canonical record rather than copied. Links identify authority
  and reduce drift but do not automatically synchronize repeated summaries.
- **No external action:** No resume, source artifact, outreach, application,
  meeting, reminder, or external record was changed.

## 2026-09-19 — Lean person notes and operational Project State

- **Decision:** Leo replaced evidence-heavy person files with a lean CRM. Each
  note now contains a five-field Snapshot, actual Conversation history,
  concise Preparation context, and Next steps. Open questions appear only when
  they materially affect imminent outreach.
- **CRM changes:** Simplified all four live person notes and the register;
  removed objectives, confidence taxonomies, positioning worksheets,
  superseded unsent draft bodies, duplicate event tables, and follow-up-plan
  boilerplate. Exact available John and Greg correspondence remains preserved.
  Explicit person actions now live once under `LEO_TODO.md#Outreach`, linked
  both ways; Jim is the only current person-specific action. Passive waits for
  John and Greg remain status context.
- **Project State changes:** Replaced the detailed evidence-horizon ledger with
  a fast handoff covering Current focus, Where to resume, Operating state, and
  Boundaries. No evidence was deleted: detailed scope, provenance, and limits
  remain in `SOURCE_INDEX.md` and the applicable experience records.
- **Governance changes:** Updated the template, register rules, outreach and
  correspondence guides, local agent instructions, playbook, root navigation,
  operating model, open-question routing, and cold-start state guidance to
  enforce the lean format and single-action-list rule.
- **Independent audits:** A fresh cold-start audit passed, recovering all four
  contacts, current focus, boundaries, and the sole Jim action without chat
  context. The first preservation audit found one stale Source Index statement
  saying John's resume had not been sent; S-005 and S-011 were corrected, and
  a fresh independent preservation recheck passed with no remaining defect.
- **Validation:** All four person notes contain the required sections and none
  of the retired dossier sections. Register/person statuses agree. A read-only
  traversal resolved all 130 archive-relative Markdown links and 20 anchors
  across 33 Markdown files. No Markdown checkboxes exist outside Leo To-Do.
- **No external action:** No message was sent, meeting scheduled, application
  submitted, reminder created, source artifact changed, or external record
  modified. The archive remains intentionally non-Git.

## 2026-09-19 — Leo replied to John Flores

- **Source:** Screenshot supplied by Leo showing the sent reply; capture date
  2026-09-19.
- **Confirmed:** Leo stated that he is based between Clearwater and Boynton
  Beach, is open to Tampa Bay, Miami, and remote opportunities, and invited
  John to suggest meeting times.
- **Durable updates:** Marked John's Draft 4 as sent evidence, added the exact
  message to the person-note conversation history, and updated the register's
  next action to await scheduling.
- **No action:** No meeting was marked planned because no time has been
  proposed or confirmed.

## 2026-09-19 — John Flores replied

- **Source:** John Flores email reply supplied by Leo; capture date 2026-09-19.
  The original message header/date was not supplied, so the capture date is not
  treated as the sent timestamp.
- **Confirmed:** John thanked Leo for reaching out and attaching his resume,
  said he had heard great things from Leo's father, offered to meet and learn
  about Leo's background and roles of interest, and asked where Leo is based.
- **Durable updates:** Updated John's person note and the outreach register to
  `Replied`; preserved the reply in conversation history; added a location-
  focused response draft. Leo's known geography remains Clearwater and
  Boynton Beach, with Tampa Bay, Miami, and remote work as targets.
- **No action:** The response remains a draft. No email was sent, meeting was
  scheduled, or external record was changed.

## 2026-09-18 — Correspondence split into people and agent docs

- Reorganized `outreach/correspondence/` into `people/` for live person notes
  and `agent-docs/` for the thread template and operating documentation.
- Updated register, state, question, source, business-school, README, and
  person-note links. Added an agent-docs README so the template remains
  discoverable in Obsidian rather than orphaned.
- No outreach status, source artifact, or external record changed.

## 2026-09-18 — Zev moved into live outreach

- Leo directed that Zev Scherl be represented as a live outreach person with
  status `Not yet contacted`, a linked person note, and a future next-action
  decision rather than a copied role-interests document.
- The redundant `outreach/contacts-and-introductions/Zev Scherl/` role-interests
  DOCX/PDF was removed at Leo's explicit direction. No current outreach,
  draft, target, or send date was inferred.
- Updated the outreach register and preserved historical connector context in
  the new person note. No external message or contact record was changed.
- Regenerated the source inventory after the explicit deletion: 505 existing
  paths, zero missing paths.

## 2026-09-18 — Evidence and old-container flattening

- Leo authorized one further simplification pass. Merged leadership and
  volunteering into `evidence/leadership-volunteering/`, moved investment
  projects into `evidence/portfolio/`, and consolidated profile assets under
  `evidence/other/`. The evidence categories now expose broad working areas;
  source internals remain only where useful for provenance or collision safety.
- Reduced historical navigation to `old/applications/` and `old/misc/`; resume
  history remains under `resumes/old/`. The old container is not a live workflow.
- Removed two empty Finder metadata files left behind by the flattened evidence
  branches. No substantive career source was deleted or edited.
- Regenerated the inventory: 511 existing paths, zero missing paths. Updated
  live links and scanned 28 Markdown files; zero broken links remain.

## 2026-09-18 — Final old-container consolidation and manual cleanup reconciliation

- Leo manually deleted/reorganized additional source material after the prior
  consolidation. The live top level is now `docs/`, `outreach/`, `resumes/`,
  `cover-letters/`, `evidence/`, and opaque `old/`; the former `reference/`
  branch is no longer present.
- Moved the remaining historical recruiting tree into `old/` and resume
  history into `resumes/old/`. No source contents or filenames were edited.
- Regenerated `docs/SOURCE_FILE_PATHS.txt` from the current source tree: 513
  existing paths, zero missing paths. Historical 505/507 counts remain only in
  dated migration records.
- Updated live README and state/index paths, then checked all live Markdown
  links: 32 Markdown files scanned, one stale historical tracker link corrected,
  zero broken links remain.

## 2026-09-18 — Career index clarified as cross-project context

- Renamed the heading and revised the introduction of `PROJECT_MEMORY.md` to
  define it as the compact career index and cross-project context layer.
- Shortened its business-school entry and routed detailed origin, architecture,
  reconciliation, stakeholder, institutional-status, and product evidence to
  `docs/BUSINESS_SCHOOL_WORK.md`. No substantive business-school evidence was
  removed; the canonical detailed record remains unchanged.
- No source, resume, sent-message, or external record was changed.

## 2026-09-18 — Business-school evidence routing made explicit

- Updated the root agent instructions to require direct reading of
  `docs/BUSINESS_SCHOOL_WORK.md` for any Darla Moore/business-school request.
  This is the canonical detailed account and should not be substituted by the
  shorter project-memory summary.
- No career/source files, sent messages, or external records were changed.

## 2026-09-18 — Greg status wording refreshed

- Updated the canonical business-school status section to reflect Leo's direct
  confirmation that his reply to Greg was sent on September 18. Preserved the
  narrower limitation that the original email header and exact clock time are
  not archived. Employment, scope, funding, AI allocation, and restart date
  remain unresolved in the Greg person record and open-question queue.
- No external message, reminder, source edit, or resume change occurred.

## 2026-09-18 — Clarified current-document editing and question scope

- Clarified in `AGENTS.md` and `ARCHIVE_OPERATING_MODEL.md` that current
  control documents are editable, while original evidence, sent messages, and
  intake history remain preserved; only relevant actionable missing answers
  belong in the open-question queue, and resolution requires a canonical
  answer plus intake mapping before removal.
- Updated `PROJECT_STATE.md` to route already-selected resume roles to the
  resume guide and future revisions to scheduled work. Applied the same removal
  rule to person-note question lists; no source or sent-message content was
  edited and no external action occurred.

## 2026-09-18 — Open-question queue bounded to actionable unknowns

### Direct instruction

- Leo authorized cleanup so `OPEN_QUESTIONS.md` contains only genuinely
  actionable missing answers. Resolved answers belong in canonical records and
  history; current documentation remains editable and no source files are to
  be moved or edited.

### Durable records changed

- Reduced `OPEN_QUESTIONS.md` to Q-005, the pending external Greg decision,
  linked to the Greg person record; removed retired/resolved questions,
  completed reconciliation history, and routine provenance caveats.
- Added the maintenance rule to `ARCHIVE_OPERATING_MODEL.md`: record the
  canonical answer and intake mapping, then remove a resolved question; do not
  keep resolved sections, and route pending tasks to state/person notes.
- Updated `README.md` and `PROJECT_STATE.md` to describe the bounded queue and
  removed stale wording that resume selections and the school arrangement were
  both unanswered. Updated the resume and tracker guides to keep selections
  and future work in their canonical workflow records rather than the question
  queue; added the same maintenance rule to the thread template.

### Mappings and checks

- Confirmed the removed resume-selection question maps to the dated selections
  in `career-core/resumes/README.md`; graduation and geography map to
  `docs/PROJECT_MEMORY.md`; the FY2022 discrepancy maps to
  `docs/BUSINESS_SCHOOL_WORK.md`; outreach cadence maps to the register/playbook;
  and retired/historical contact items remain in memory and prior intake history.
- Confirmed Q-005 remains genuinely pending in the Greg person record and the
  business-school current-status section; no answer was inferred and Leo was
  not re-asked.
- Checked edited-document links and searched for stale queue wording after the
  edits. No source, resume, sent message, or historical record was moved or
  edited, and no external action occurred.

## 2026-09-18 — John sent confirmation and two-region availability

- Leo directly confirmed John email sent today, resolving the pending send
  question. Register and person note now say Sent, September 18; await reply,
  no default follow-up deadline. Prior update described an attached resume;
  exact sent text is not presumed identical to the saved draft.
- Recorded Clearwater/Boynton Beach approximately equal residence split,
  Clearwater/Tampa Bay and Miami work targets, and in-person networking
  availability in both regions. Miami is not represented as a residence.
- Captured the six resume-reference classifications from Leo's preceding
  annotations in the existing resume README; no new documentation layer.
  Updated memory, questions and state. No resume/source edits or moves,
  external messages, reminders, or Git action. File inventory remains unchanged.

## 2026-09-18 — Open-question reset and sent Greg reply

- Captured Leo's direct graduation, geography/availability, legacy-activity
  retirement, and John/father context updates. Updated memory, state, source
  index, operating guidance, outreach playbook, questions, and John's note.
- Preserved Greg's supplied incoming email and Leo's confirmed sent reply in
  one new person note; linked it from the register and school-work record.
  End of next week is interpreted as September 25, not an agreed restart.
- Q-002's “yes” answers a compound question; did not invent a Jeff send date,
  reply, or call. Legacy activity is inactive, so no follow-up investigation.
- Removed routine evidence-limit items from the open queue without erasing
  source provenance or promoting intended product capabilities to completed ones.
- Resume candidates are presented by existing paths for Leo's selection.
  Physical Old-folder consolidation is deferred until useful industry resumes
  and cover letters are identified; source files and the inventory are unchanged.
- No resume edits, external messages, reminders, applications, or Git actions.

## 2026-09-18 — Manually finalized resume reviewed for John

- Leo confirmed his manual edits were complete and requested attachment review.
  Current DOCX/PDF contain the agreed initiative title and three revised
  business-school bullets. Five-year published-budget reconciliation is not
  presented as forecast accuracy; the broad 0.03% claim is absent.
- Compared the revised section across DOCX/PDF, confirmed the PDF is one page,
  and visually inspected its rendering: readable, no clipping or overflow.
  These checks establish attachment readiness, not independent verification
  of every resume claim. Current resume states graduated May 2026; memory and
  Q-009 now reflect that current source rather than older expected-date text.
- Updated resume guidance, source index, project state, open questions, and
  John's person note/register to Ready for Leo. Draft 3 remains unchanged.
- No resume/source files were edited, moved, or regenerated. The user's Word
  lock file was left untouched. No email, application, reminder, or Git action
  was performed. Send date and follow-up due date remain unset.

## 2026-09-18 — Web-prototype learning and resume wording clarified

- **Confirmed by Leo:** He built the custom/bespoke Scenario Studio prototype
  through informal AI-assisted or “vibe-coded” development and learned the
  fundamentals of JavaScript, Node.js, Git, React, and how the web stack works
  together. This is hands-on foundational experience, not a claim of formal
  software-engineering training, production deployment, or advanced mastery.
- Updated the canonical business-school/product account, career index,
  S-010 provenance, and project state. No resume file was edited because Leo is
  inserting the proposed wording manually.
- Drafting guidance: replace the insider phrase “two allocation regimes” with
  “the university's prior and revised cost-allocation systems.” Avoid the old
  “within rounding variance,” “audit-ready,” and “every output” claims because
  the five-year comparison has separately scoped differences and no formal
  audit-readiness finding. Describe the web work as a custom React prototype,
  not a connected production application.
- No outreach, attachment, application, reminder, meeting, or external action
  occurred. John remains Drafting and the current resume pair remains in manual
  edit status.

## 2026-09-18 — Direct reporting relationship confirmed

- **Confirmed by Leo:** The dean was his formal direct supervisor. The resume
  phrase “Reporting directly to the dean” is accurate and should not be softened
  to “working with.” This establishes the reporting relationship, not Leo's
  formal title, classification, compensation, or a new employment arrangement.
- Updated the canonical business-school account, S-006 provenance, project
  state, Q-005, and the current-pair limitation in S-011. The remaining manual
  resume corrections concern the proposed functional title, unsupported ~$120M
  figure, and overbroad 0.03%/“actuals” language—not the reporting relationship.
- No resume file was edited, exported, or marked send-ready. John remains
  Drafting; no message, attachment, reminder, meeting, or external action
  occurred.

## 2026-09-18 — Current resume pair restored for Leo's manual edits

- **Confirmed by Leo:** The generated PDF's formatting was slightly wrong. Leo
  will manually insert the wording changes and wants both the most recent DOCX
  and its PDF in `resumes/current/`, while retaining the `current/` and
  `archive/` schema.
- Replaced the generated current PDF with the archived June 29 PDF and copied
  the matching June 29 DOCX into `current/`. Both current files compare
  byte-for-byte with their originals under
  `archive/grad-recruiting/BayFirst/New/`; the archived copies were not changed.
- The current pair is explicitly **working state, not send-ready**. Its restored
  Darla Moore wording includes the title/reporting, ~$120M, and broad 0.03%
  claims identified in the prior review. Leo will make the corrections in Word
  and export the PDF; agents should recheck the pair only after he confirms the
  manual edit is complete.
- Updated the resume README/instructions, source index, source-path inventory,
  project state, operating model, Q-003, John note, and outreach register. The
  John thread returned to Drafting and the attachment proposal was withdrawn
  pending the manual update. The earlier generated-PDF entry remains historical
  context and is superseded by this restoration.
- Validation: both current files exist and match the archived originals; the
  current inventory contains 507 existing paths, with 87 archived resume files
  and two current working files. No email, application, reminder, meeting, or
  external record change occurred. No archive file was deleted or overwritten,
  and the folder remains non-Git.

## 2026-09-18 — Current resume revised and archive schema simplified

- **Authorization:** Leo asked for a new PDF using the evidence-safe Darla Moore
  section and explicitly approved a `resumes/current/` plus old/reference
  resume area, provided the existing structure was preserved.
- Created `career-core/resumes/current/Leo Goldberg Resume.pdf` from the newest
  June 29 resume design. Replaced only the Darla Moore role label and three
  bullets: model creation, FY2022–FY2026 published proposed-budget
  reconstruction across two regimes, and scenario analysis. Removed the
  unverified title/reporting relationship, unsupported ~$120M figure, and the
  incorrect broad use of 0.03% and “actuals.” All other resume content and the
  one-page visual design were retained. The existing “Graduated May 2026” line
  remains visible; Q-009 stays open pending Leo's direct confirmation.
- Moved the existing `grad-recruiting/` and `legacy-version-library/` trees,
  containing 87 files, beneath `career-core/resumes/archive/` with their nested
  hierarchy, filenames, sizes, and modification times preserved. The historical
  migration TSVs were intentionally not rewritten; current paths live in
  `SOURCE_FILE_PATHS.txt`.
- Updated the resume README/instructions, source index, project state, operating
  model, open question Q-003, John note, and outreach register. The current PDF
  is authoritative for general use and is proposed—not automatically sent—as
  John's attachment. Tailored resume authority remains unresolved.
- Validation: the revised DOCX and final PDF each rendered as one US Letter
  page; the full page was visually inspected with no clipping, overlap, broken
  bullets, or unexpected layout change. All preserve-only DOCX package parts
  matched the source, and the final PDF's Darla Moore text was extracted and
  checked. The source inventory now has 506 existing paths: all 505 original
  items plus the new current PDF.
- No email, application, reminder, meeting, or external record change occurred.
  No original resume was overwritten or deleted, and no Git repository was
  created.

## 2026-09-18 — John Flores first email prepared

- **Confirmed by Leo:** The first message should be basic: introduce himself,
  say he would like to connect and share his experience, and leave the
  conversation invitation flexible. This resolves the first-message objective;
  John's particular interest and whether he explicitly invited contact remain
  unknown.
- Added Draft 3 to John's person note and marked it **Ready for Leo**. The draft
  names the father connection and business-school work without expanding into
  an unrequested private-wealth pitch, quantified accomplishment, job request,
  or fixed 20-minute ask. Drafts 1–2 remain preserved as superseded history.
- Updated the John note, outreach register, project state, and Q-012 together.
  Confirmed their status and next action agree and that the affected relative
  links still resolve.
- No email was sent, no send date or follow-up due date was invented, and no
  reminder, meeting, external-contact record, source file, or resume was
  changed. No attachment is proposed.

## 2026-09-18 — Flexible evidence, linked mini-CRM, and lean Obsidian workspace

### Authorization and material intake

- Leo approved the records-first implementation plan: preserve the substance
  without a predefined story formula; improve linked person/conversation
  records; open the existing folder in Obsidian; lightly consolidate control
  documents; test file-only pickup with two fresh independent Sol agents.
- Captured Leo's model-origin/ownership correction, March 2026–present project
  dates and reduced recent activity, approved policy/research and stakeholder
  accounts, scoped reconciliation tables, $1 resolution, Greg's supplied email,
  and the separate product prototype/ambition boundary. Source dates and
  verification limits are in SOURCE_INDEX entries S-006–S-010.
- Latest direct corrections supersede the initial exports-only account. The
  older intake entries and John drafts below remain historical evidence, not
  the current interpretation or recommended wording.

### Durable changes

- Replaced the incomplete overall business-school account with topic-based
  evidence: origin/ownership, mechanisms, historical reconstruction, scenario
  work, leadership engagement, current status, and adjacent product work.
  No canned narrative bank or audience taxonomy was added.
- Updated memory, state, exact open questions, source locators, email-style
  guidance, and outreach workflow. Closed the $1 discrepancy for use without
  treating the separate one-cent precision note as a broad blocker.
- Made register names clickable; retained one person note for evidence,
  drafts, and dated conversation history. John is Drafting with two superseded
  unsent drafts; no replacement email or invented contact was created.
- Consolidated current rules in ARCHIVE_OPERATING_MODEL and fixed live
  references in root/local instructions and folder READMEs. Preserved the old
  DECISIONS_AND_RULES, REORGANIZATION_PLAN, NEW_CHAT_STARTER_PROMPT, and root
  LEGACY_CHATGPT_KNOWLEDGE_EXTRACTION_PROMPT under docs/history, with historical
  notices. The migration TSVs remain where they were.
- Root README now maps every control Markdown file and separates daily use,
  evidence/guidance, local routing, and history. Nine live Markdown records
  remain directly in docs; no new control Markdown file was added.

### Governance preservation check

Compared the retired decision sections against the live operating model:
source precedence, three-resume strategy, document authority/approval,
Drafted/Sent/Applied/Active and reply/meeting evidence, time-sensitive research,
workspace/source preservation, no copied legacy handoff, separately approved
source moves, minimal README/AGENTS footprint, exclusion of controls from the
505 inventory, material-intake boundaries, and Markdown CRM ownership are
retained. Historical decisions remain in full with their original dates.

### Deliberate no-change boundaries

- All external PDFs, attachments, the legacy handoff, VM references, and product
  records remain in place. No raw source was imported or copied.
- No career-source edits or moves, tracker/resume edits, external outreach,
  application, meeting, reminder, or follow-up scheduling. No Greg contact
  task was created from his email.
- No Git, checksums, validator scripts, database, community plugins, or
  duplicate vault. Documentation-only work does not require executable tests.

### Validation completed

- Baseline independent Sol audits found duplicated live governance and
  insufficient corrected-story pickup: the old files reproduced the obsolete
  "improved an existing model" account. Those findings informed this update.
- Fresh independent `gpt-5.6-sol` agent `sol_fresh_evidence_pickup`, with no
  parent conversation, returned **PASS for reconstruction**, explicitly
  limited for independent primary substantiation. It recovered the original
  enrollment assignment, Leo's model-building/design ownership, financial
  methods, two regimes, correctly scoped numbers, project dates, stakeholder
  outcomes, current employment uncertainty, and separate product maturity.
  It independently recomputed all five annual differences/percentages, the
  support-allocation percentage/shares, and the two distinct precision issues.
- Fresh independent `gpt-5.6-sol` agent `sol_fresh_crm_pickup`, also without
  parent conversation, returned **PASS**. It selected materially different
  accomplishment bundles for John and a hypothetical product audience without
  a compulsory story formula; recovered Drafting/unsent status and the
  unconfirmed ask; and located where actual conversation notes belong. It
  neither created a draft file nor mutated CRM status.
- Native Obsidian testing caught a limitation in the first filesystem link
  audit: slug-style heading fragments opened files but did not find sections.
  Converted all 24 fragments to URL-encoded literal headings. The independent
  follow-up checked **125 internal relative-link occurrences**, **24/24 exact
  decoded heading matches**, and **32/32 control Markdown files mapped by the
  home page**, with zero missing targets or mismatches. The active contact
  queue was also moved ahead of explanatory status rules.
- Opened the existing Networking folder as a vault in Obsidian 1.13.7. Saved
  native bookmarks “Networking — Home” and “Outreach — People & next actions”.
  Set only this vault's new-link format to relative Markdown. No other vault
  settings, sync setup, community plugins, or source locations were changed.
- Verified in Obsidian: home → register → John → Origin and ownership → S-006
  source entry. The exact heading landing was visually checked; the register
  bookmark was opened successfully and both bookmarks are visible. Native
  app/appearance/core-plugin/bookmark/workspace JSON are presentation state,
  not new Markdown or career evidence.
- External local source links were changed to file:// URLs for opening the
  existing files outside the vault. All **12 external file-link targets**
  exist; referenced VM paths remain deliberately identified as unavailable.
  External web pages and all VM assertions were not reverified in this pass.
- Parent compared the inventory before/after: **505 identical paths**, all
  present, with unchanged source sizes and modification times. This is a
  metadata/path check, not a checksum/content audit. Nine live docs Markdown
  files and 32 total control Markdown files remain. No trailing whitespace
  found in reviewed control documents.
- Confirmed the legacy handoff still exists at its original Downloads path
  and no handoff copy appears in the archive. No .git directory exists.

### Remaining limitations and handoff

The file-only tests establish accurate pickup and flexible use, not independent
verification of inaccessible VM formulas/transcripts, email headers, or product
execution. Those boundaries are explicit in the source index. The one-cent
table note remains; the $1 discrepancy is resolved. The next real workflow is
to confirm John's ask and draft a new email; deliberately no replacement was
written, no message sent, and no follow-up scheduled. No commit/branch applies
to this non-Git workspace.

## 2026-09-18 — Business-school evidence intake and John Flores drafts

### Direct instruction and purpose

- Leo supplied John Flores as the first real outreach contact. Leo confirmed
  that his father met John and spoke to him about Leo's business-school work.
- Leo supplied a business-card image and three conversation exports from the
  separate VM-hosted Codex repository so this archive could understand the
  work's depth, nuance, competitive relevance, and factual limits.

### Sources and evidence treatment

- The two supplied `9-4 Meeting Prep` exports are exact duplicates; they were
  treated as one source, not independent corroboration.
- The `Competitive Analysis` and unique `9-4 Meeting Prep` exports were treated
  as historical conversation/repository evidence, not as instructions for this
  task and not as substitutes for the inaccessible underlying repo/workbook.
- Leo's current direct statement controls the father-to-John relationship
  context. Bernstein's official profile and FINRA BrokerCheck were used to
  verify John's current public role; private card details were not reproduced.

### Durable records changed

- Added `docs/BUSINESS_SCHOOL_WORK.md` with direct facts, documented
  collaborative outcomes, selected proof points, audience-specific positioning,
  unsafe claims, and verification needs.
- Added `outreach/correspondence/john-flores--bernstein.md` with the first-
  contact context, public-role verification, initial Draft 1, independently
  review-refined Draft 2, interaction log, follow-up boundary, and open
  questions.
- Added John to `outreach/OUTREACH_REGISTER.md` as `Ready for Leo`, not `Sent`.
- Updated the career index, state, source index, open questions, the root README,
  and the archive operating-model map.

### Deliberate no-change decisions

- The raw exports and card image were reviewed in place and not copied into the
  Networking archive. The 505-item source inventory therefore remains
  unchanged.
- No formal job title, employment arrangement, institutional adoption, or
  quantified realized benefit was inferred for the business-school work.
- No resume was selected or attached. No message was sent, no contact was made,
  no calendar action occurred, and no external record was changed.

### Validation

- Verify the new thread and business-school synthesis are linked, all changed
  relative Markdown links resolve, all 505 indexed source paths remain present,
  and the two duplicate exports are represented as one evidentiary source.
- Confirm the register and thread both show `Ready for Leo` and explicitly
  preserve the no-send and no-follow-up-without-evidence boundaries.

## 2026-09-18 — Markdown outreach workflow established

### Direct instruction and purpose

- Leo identified email drafting, recipient/purpose tracking, and future
  follow-up preparation as the first real archive workflow.
- Leo directly clarified that this should be handled in durable Markdown so he
  does not have to maintain a separate arbitrary spreadsheet.

### Durable records and structure changed

- Added `outreach/OUTREACH_REGISTER.md` as the canonical compact queue for new
  outreach begun on or after 2026-09-18.
- Added `outreach/correspondence/THREAD_TEMPLATE.md` for one durable record per
  person or coherent conversation.
- Updated the outreach READMEs, playbook, governing decisions, project state,
  open questions, and root README to define the workflow and link its entry
  points.
- Closed Q-004 for the forward outreach workflow while preserving existing
  workbooks as historical evidence whose contents may still need review.

### Evidence treatment and deliberate no-change decisions

- The Markdown-system choice is **confirmed** by Leo's dated direct statement.
- No historical person or draft was promoted into the active queue because
  current status remains unverified.
- No default follow-up interval or maximum-attempt rule was inferred; Q-007
  remains open. Each thread can carry an explicitly chosen due date.
- No spreadsheet, source artifact, resume, or external record was edited. No
  message was sent, no person was contacted, and no meeting was scheduled.

### Validation

- Verify all new and changed relative links resolve and the register/template
  expose the required fields: who, why, relationship path, evidence-backed
  status, draft, last action, next action, due date, and follow-up plan.
- Confirm `SOURCE_FILE_PATHS.txt` remains the unchanged 505-item source
  inventory because the new Markdown files are control records, not imported
  career-source evidence.

## 2026-09-16 — Phase 2 source reorganization completed

### Direct authorization and scope

- Leo explicitly approved Phase 2 after two bounded, read-only preflight
  audits.
- Authorization covered creation of the approved functional folders and
  control files, followed by the 505 manifest-recorded moves. It did not cover
  renaming, deduplication, deletion, authoritative-version selection, source
  content edits, or external actions.

### Durable records and structure changed

- Created the seven functional top-level source areas, concise top-level and
  workflow-boundary READMEs, and nested `AGENTS.md` files only for
  `career-core/`, `recruiting/`, and `outreach/`.
- Moved 476 substantive source items and 29 Finder metadata, Office lock/temp,
  or shortcut items to their literal manifest destinations while preserving
  filenames.
- Removed 104 empty legacy directories after their contents moved, leaving the
  root control layer and seven implemented functional areas. No file was
  deleted.
- Replaced `docs/SOURCE_FILE_PATHS.txt` with the 505 current absolute paths.
- Updated `README.md`, `docs/PROJECT_STATE.md`,
  `docs/ARCHIVE_OPERATING_MODEL.md`, `docs/DECISIONS_AND_RULES.md`,
  `docs/SOURCE_INDEX.md`, `docs/REORGANIZATION_PLAN.md`, and
  `docs/OPEN_QUESTIONS.md` to reflect completion and continuing boundaries.

### Evidence treatment and deliberate no-change decisions

- Filing location remains organizational context, not proof of document
  authority, application status, message status, or present activity.
- No resume, cover letter, workbook, tracker, or other source content was
  edited. No source filename was changed and no source item was deleted.
- No resume or tracker was declared authoritative. No outreach, application,
  scheduling, contact, or external-record action occurred.
- The legacy handoff remains only at its original Downloads path.

### Validation completed

- Before execution, all 505 sources existed and all 505 destinations were
  unique, unoccupied, and contained within the archive.
- After execution, zero historical source paths remained and zero new source
  paths were missing.
- The current inventory contains exactly 505 paths and the old-to-new manifest
  remains the migration record.
- All planned schema boundaries exist; the archive root has no unexpected
  entries; 40 relative control-document links resolve; and no trailing
  whitespace was found in the control Markdown files.
- The preflight-observed extended attributes remained present after the moves:
  408 source items retain quarantine attributes and two retain management
  attributes.
- The handoff remains in its original Downloads location and no copy exists in
  the Networking archive. The workspace remains non-Git.

## 2026-09-16 — Orphan classification review completed

### Direct instruction and scope

- Leo noted that the initial proposed-path manifest still left many orphaned
  files.
- The review covered every item previously marked `hold-for-review` or low
  confidence. Finder metadata and Office temporary/lock files were identified
  separately from meaningful career artifacts.

### Evidence reviewed

- Full-page renders of three Word documents and four PDFs, including both pages
  of the personal-statement example.
- Original-resolution review of nine ambiguous images/screenshots.
- File-type and embedded-target inspection of the Windows shortcut.

### Durable records changed

- Updated `docs/REORGANIZATION_BLUEPRINT.tsv` with content-grounded routes for
  applications, role-interest writing, study-abroad volunteering/coursework,
  DTCC contact research, schedules, a teaching-assistant application, and
  reusable reference/profile material.
- Regenerated `docs/PROPOSED_PATH_MANIFEST.tsv` so broad split rules resolve to
  actual proposed moves and metadata routes resolve to quarantine.
- Updated `docs/REORGANIZATION_PLAN.md`, `docs/PROJECT_STATE.md`,
  `docs/OPEN_QUESTIONS.md`, and `docs/SOURCE_INDEX.md`.

### Evidence treatment and deliberate no-change decisions

- Content established appropriate filing context; it did not prove that any
  cover letter was submitted, message was sent, contact was approached, or
  application remains active.
- `PROJECT_MEMORY.md`, `EMAIL_STYLE.md`, and `OUTREACH_PLAYBOOK.md` were not
  changed because the review added routing evidence, not a new current career
  status, approved writing preference, or outreach action.
- No source file was moved, renamed, copied, deduplicated, deleted, or edited.
- No external action occurred.

### Validation completed

- The regenerated manifest contains 505 six-field rows and exactly covers the
  source inventory.
- It contains zero unrouted paths, duplicate current paths, destination
  collisions, low-confidence classifications, or `needs-review` targets.
- It records 476 proposed source moves and 29 metadata-quarantine routes.

## 2026-09-16 — Source-reorganization planning authorized

### Direct instruction

- Leo selected reorganization of the existing source-file schema as the first
  substantive archive task.
- Leo approved a manifest-first approach and requested READMEs wherever useful,
  with folder-specific agent instructions when necessary.

### Durable records changed

- Added `docs/REORGANIZATION_PLAN.md` with the proposed functional schema,
  README policy, selective nested-instruction policy, migration phases, and
  approval boundary.
- Added `docs/REORGANIZATION_BLUEPRINT.tsv` with proposed routing for every
  current top-level source subtree and root source file, plus functional
  overrides inside `Grad Recruiting/` and `GAM & CL/`.
- Added `docs/PROPOSED_PATH_MANIFEST.tsv` with one literal proposed route for
  every inventoried source file.
- Updated `README.md`, `docs/PROJECT_STATE.md`,
  `docs/DECISIONS_AND_RULES.md`, and `docs/OPEN_QUESTIONS.md`.

### Evidence treatment

- The target schema is a confirmed design decision.
- Individual path classifications are proposed; confidence is recorded in the
  blueprint and ambiguous items remain held for review.
- Repeated filenames were not treated as duplicate contents.

### Deliberate omissions

- No source file or folder was moved, renamed, copied, deduplicated, deleted,
  or edited.
- No new functional folder, distributed README, or nested `AGENTS.md` was
  created because those belong to the separately approved physical migration.
- No resume or tracker was declared authoritative.
- No outreach, application, tracker, or other external action occurred.

### Validation completed

- The 77-row blueprint covers every current top-level source subtree and root
  source file; it has six fields per row, no duplicate current-path keys, and
  no nonexistent current-path scopes.
- The 505-row proposed-path manifest covers the source inventory exactly, with
  six fields per row, no unrouted or duplicate current paths, and no proposed
  destination collisions after separating two same-named transcript sources.
- The manifest records 45 held-for-review items, including 28 Finder metadata
  or Office temporary/lock files; none was deleted or treated as substantive
  evidence.
- The source inventory remains an exact 505-path match with zero missing paths.
- All relative links in the changed entry-point, state, decision, and planning
  documents resolve.
- No trailing whitespace was found in the changed control files.

## 2026-09-16 — Archive operating model established and clarified

### Direct instruction

- Leo asked for a first-principles repository-management approach adapted to
  the Networking archive.
- Leo clarified that the comparison material should inform the design without
  becoming a cited project source or dependency.

### Durable records changed

- Added `docs/ARCHIVE_OPERATING_MODEL.md` as the Networking-specific adaptation.
- Linked the model from `README.md`, `AGENTS.md`, and `docs/PROJECT_STATE.md`.
- Added the design decision to `docs/DECISIONS_AND_RULES.md`.
- Recorded the boundary between material intake and exploratory drafting.
- Removed comparison-project names, paths, and provenance entries from the
  durable Networking records while retaining the adapted operating principles.

### Deliberate no-change decisions

- `PROJECT_MEMORY.md`, `EMAIL_STYLE.md`, `OUTREACH_PLAYBOOK.md`, and
  `OPEN_QUESTIONS.md` were unchanged because this management clarification adds
  no new career facts, writing preferences, outreach status, or unresolved
  career evidence.
- `SOURCE_FILE_PATHS.txt` remains the 505-file career-source inventory. The
  management clarification did not add a career source file.
- No Git workflow, checksum system, raw-file duplication, structured tracking
  tables, scripts, or automated validators were added.
- No source career file, tracker, resume, cover letter, application, or
  outreach record was changed, and no external action was taken.

### Validation

- Recheck the 505-path inventory against current source files, verify internal
  README/project-state links, and confirm no comparison-project reference was
  added to the durable Networking records.

## 2026-09-16 — Initial career-archive operating layer

### Sources reviewed

- The existing 505-file Networking archive was enumerated by absolute path.
- The legacy ChatGPT knowledge handoff at
  `/Users/leogoldberg/Downloads/NETWORKING_PROJECT_KNOWLEDGE_HANDOFF.md` was
  reviewed as historical source material.
- Leo's current instructions established the project home, non-Git model, and
  requirement to merge the legacy knowledge with the existing archive.

### Durable records created

- Root agent instructions and project README.
- Project state and memory.
- Email style and outreach playbook.
- Decisions/rules and open-question queue.
- Source index and paths-only file inventory.
- This intake log.

### Evidence treatment

Legacy claims were integrated as confirmed, inferred, or unknown according to
the handoff's evidence boundaries. Historical drafts and application mentions
were not promoted to present status. The passed May 2026 graduation date was
retained as a resume claim while current completion status remains open.

### Deliberate omissions

- The legacy handoff was not copied into the project.
- No resume, cover letter, spreadsheet, tracker, application, or outreach
  record was changed.
- No source file was moved, renamed, deduplicated, or deleted.
- No external message was sent and no application was submitted.
- No Git repository, checksum manifest, script, or automated validator was
  created.
# 2026-09-18 — Live source tree consolidated

- **Authorization:** Leo explicitly approved simplifying the live source
  structure while preserving source filenames and contents. No `docs/` or
  `outreach/` source/control branch was moved, and `.obsidian/` was preserved.
- **Moves:** 522 exact source/control paths were moved using the validated map at
  `/private/tmp/networking-source-move-map-2026-09-18.tsv`. Root destinations
  are `resumes/`, `cover-letters/`, `evidence/`, `reference/`, and `archive/`.
  Evidence routing places education, certifications, employment, leadership,
  volunteering, portfolio, profile-assets, and recommendations under
  `evidence/`; old applications, interview prep, trackers, and quarantine are
  under `archive/`.
- **Durable records:** Updated `README.md`, local boundary READMEs/AGENTS,
  `docs/PROJECT_STATE.md`, `docs/ARCHIVE_OPERATING_MODEL.md`,
  `docs/SOURCE_INDEX.md`, `docs/SOURCE_FILE_PATHS.txt`, and John's current
  resume links. Historical migration TSVs were intentionally unchanged.
- **Validation:** The pre-move map had 522 exact file/control mappings, zero
  destination collisions, and zero occupied destinations. The current source
  inventory has exactly 507 unique existing paths. No source content was
  edited, renamed, deleted, or externally shared; the workspace remains
  intentionally non-Git.

# 2026-09-18 — Resume lanes and Leo to-do list

- **Authorization:** Leo asked for explicit current/old FP&A, consulting, and
  general resume lanes, a daily Obsidian to-do list, and a blank Jim Van Arsdale
  outreach record.
- **Changes:** Moved the manually finalized current DOCX/PDF pair into
  `resumes/current/fp&a/`. Created empty `current/consulting/`,
  `current/general/`, `old/fp&a/`, `old/consulting/`, and `old/general/`
  placeholders without relabeling historical files. Added `docs/LEO_TODO.md`,
  added Jim to the outreach register, and created his blank person note.
- **Navigation:** Removed the career index and individual person links from
  README Daily use. Kept the career index in Reference, where it remains
  available when needed for drafting or evidence work.
- **Validation:** Updated live resume links and will verify Markdown links and
  the post-move source inventory. No outreach or external record was changed.

# 2026-09-18 — Resume format subfolders

- **Authorization:** Leo clarified that every current and historical role lane
  must separate repeated resume filenames into `docx/` and `pdf/` folders.
- **Changes:** Added those format folders beneath each FP&A, consulting, and
  general lane. Moved the current FP&A pair into its format folders and placed
  the two root historical resume files under `old/general/docx/` and
  `old/general/pdf/`; other historical libraries were not relabeled.
- **Validation:** Updated live links and the 505-path inventory. No resume
  content was edited.

# 2026-09-18 — Leo simplified historical resume container

- **Source:** Leo manually simplified `resumes/old/` after the format-lane
  setup.
- **Durable update:** Repointed the two moved historical resume files in
  `docs/SOURCE_FILE_PATHS.txt`; no historical contents were edited or
  reclassified beyond the already established `old/general` placement.
- **Validation:** Leo's manual cleanup reduced the live source tree; the
  paths-only inventory now requires a full regeneration before it can be called
  current. No external action was taken.

# 2026-09-21 — Latest Mail scan snapshot behavior clarified

- **Source:** Leo's direct correction after the 2026-09-21 outreach Mail scan.
- **Canonical decision:** Refresh `docs/OUTREACH_SCAN_UPDATE.md` after every
  successfully completed scan. A no-result scan replaces the prior
  correspondence delta with an explicit no-new-correspondence result while
  retaining the scan date, accounts, method, and external-action boundary.
- **Affected records:** Updated `README.md`, `outreach/AGENTS.md`,
  `docs/OUTREACH_PLAYBOOK.md`, `docs/OUTREACH_SCAN_UPDATE.md`,
  `docs/PROJECT_STATE.md`, and `docs/ARCHIVE_OPERATING_MODEL.md`. The local
  `outreach-correspondence-sync` skill and its scheduled-operation reference
  were updated to the same rule. The active automation prompt was also updated
  so future runs refresh the scan snapshot while keeping canonical changes
  approval-gated.
- **Deliberate no-change:** Approval remains required before changing canonical
  person notes, register statuses, open questions, tasks, or other outreach
  facts. No Mail or other external action was taken.
- **Validation:** Reviewed all live Markdown references to the scan snapshot
  and checked the updated files for formatting errors.

# 2026-09-21 — Consider Leo's action during every correspondence review

- **Confirmed source and authorization:** Leo approved the revised plan to
  always consider whether correspondence requires action, automatically capture
  warranted tasks with supporting evidence/question links, and report every
  captured change in the latest scan. Judgment replaces enumerated triggers.
- **Guidance updated:** Root and outreach AGENTS, archive operating model,
  outreach playbook and READMEs, correspondence template, project-state operating
  guidance, To-Do and open-question guidance, outreach-correspondence-sync skill,
  scheduled reference, and active automation prompt. The schedule was preserved.
- **John repair:** Added received-message evidence and the unresolved
  availability question to his person note; added one task in Leo To-Do with
  reciprocal links; revised the latest scan to distinguish applied capture from
  pending status reconciliation. The earlier no-proposed-time sentence is now
  explicitly historical.
- **Deliberate no-change:** Register/Snapshot status and project-state current
  focus reconciliation remain pending approval. Greg's waiting status creates no
  task; existing tasks and the central open question were preserved. No source
  artifact, contact, Mail state, or external record was changed. No new scan ran.
- **Validation:** Reviewed task uniqueness, supporting evidence, reciprocal
  links, automatic-change reporting, and instructions for repeat/empty scans.
  Checked changed-document local links and searched live guidance for obsolete
  task-creation restrictions. No Git was introduced to this non-Git archive.

# 2026-09-21 — Include actionable correspondence in Open questions

- **Confirmed correction:** Leo clarified that John's unanswered availability
  question belongs in the central Open questions record. Removed the prior
  routine-reply exclusion from the playbook, question guidance, skill, and
  automation prompt.
- **Applied:** Added Q-006, linked to John's message evidence and existing
  to-do; added backlinks from the task and person note, and reported the change
  in the latest scan. No duplicate task or answer was invented.
- **Validation:** Checked Q-006 references across the four affected records
  and removal of the old routing exclusion. Availability remains unknown;
  other pending status changes and Greg's question remain unchanged. No Mail
  operation or scheduling change occurred.

# 2026-09-21 — Isolated JEv pilot and realistic repeated-trial handoff

- **Confirmed source and authorization:** Leo approved comparing Sol low and
  Astra low with agent-only, JEv independent interpretation, proposal review,
  and both. He subsequently requested realistic one-task-at-a-time execution
  while retaining repetitions. The practical protocol specifies three fresh
  repetitions per model on an anonymized current-rule scheduling scenario.
- **Confirmed state:** The two practical agent-only baselines completed. A
  separate one-question JEv diagnostic succeeded, but the first full-state
  single-question trial and its delayed retry both returned the service's
  rate-limit error. The runner stopped; no assisted comparison or independent
  outcome grading completed. Earlier larger-batch baselines remain preserved.
  The responsible quota/provider layer and reset time are **unknown**.
- **Affected records:** Added a compact operating-state handoff to
  `docs/PROJECT_STATE.md`. Protocols, anonymized fixtures, raw attempts, outputs,
  and a resumable status note remain in the separate Codex task workspace,
  linked from that page. No test infrastructure or copied sources were added
  to the vault, so the source-path inventory did not change.
- **Validation:** Four harness tests passed for tool restrictions, exact-link
  detection, path boundaries, and separation of proposed/applied changes.
  The blocked runner's exit and both preserved retry responses were checked.
  These checks do not establish JEv usefulness or model superiority.
- **Deliberate no-change:** No live correspondence skill, scan prompt or
  weekday 9:00 a.m. schedule, person/register status, To-Do, Open questions, or
  latest-scan snapshot changed; no new inbox scan occurred. Pending John
  status reconciliation remains untouched. No sending, Mail mutation,
  application submission, calendar action, or new credential storage occurred.
  Hosted calls used authorized anonymized test material. No Git was added.
- **Remaining gate:** Repeated comparisons and broader validation remain
  unfinished; integration is conditional on evidence. Step 3 and all later
  expansion require Leo's explicit subsequent approval.

# 2026-09-21 — Official TypeSafe adapter and minimal batch restart

- **Source and authorization:** Leo supplied the setup-side-conversation
  handoff and authorized retrying the batched test with only necessary restart
  work. The handoff reports removal of the community MCP registration/account,
  a new Keychain-backed local adapter, and a corrected 422 schema error before
  successful setup verification. Those setup actions were not repeated here.
- **Confirmed here:** The unchanged adapter repository was clean at commit
  `72b9e59`. Its local MCP status confirmed the official endpoint and configured
  credential without revealing the key. The identical anonymized three-question
  practical request succeeded in 1.106 seconds on `jev-1.13.0`, with 1,496 input
  and 150 output tokens. No community endpoint was called. Actual SDK retry
  count is unknown; one explicit tool call was made with retry maximum one.
- **Validation and reuse:** Checked exact batch-input equality, all returned
  question keys and choices, and exact frozen-prompt/scenario matches for both
  completed agent-only baselines, including requested models, low reasoning,
  and zero reported tool calls. Those baselines need not be rerun for the first
  repetition. This success does not establish judgment improvement or sustained
  service reliability; assisted outputs, grading, and repetitions remain open.
- **Affected records:** Updated project state and this intake log. Detailed
  transport evidence, protocol amendment, and resumption state remain in the
  existing isolated pilot workspace linked from project state. The original
  gateway failures remain preserved, separate from official-path results.
- **Deliberate no-change:** No adapter code/configuration, credential storage,
  source inventory, live scan automation, Mail state, correspondence records,
  tasks, or questions changed. No production integration or Step 3 work began.
  No Git was introduced to the archive; no experiment baseline was discarded.

# 2026-09-21 — Official JEv screen completed; advancement gate not met

- **Confirmed source and authorization:** Leo reconfirmed the original
  approved two-model/four-approach experiment and asked it to continue after
  receiving a progress update. The eight-case screen completed sequentially
  with frozen anonymized inputs and no live Mail or archive tool access.
- **Confirmed results:** 64 scored outputs, including 16 exact-matching reused
  agent-only baselines and 48 fresh assisted outputs; 61/64 passed the
  material-error rubric. Sol low and Astra low each passed 8/8 unassisted.
  Sol interpretation scored 6/8, Sol both 7/8; proposal review and all Astra
  approaches scored 8/8. The John-style historical/current-policy cases passed
  without JEv, so this screen does not demonstrate its added prevention value.
- **Observed defects and limits:** One Sol interpretation output proposed an
  unsupported source-preservation claim. Sol interpretation and both each
  applied an approval-gated passive-history edit in their simulated records.
  Minor redundant logging/status wording was recorded separately. These were
  fixture outcomes, not live changes. One observation per combination and
  supplied complete context do not establish repeatability or general model
  superiority. Confidence scores did not establish permission or Leo's approval.
- **Connection:** All 48 official screening calls succeeded on returned model
  `jev-1.13.0`, averaging 0.599 seconds, maximum 1.058 seconds. The unchanged
  local adapter used its existing Keychain credential; no community endpoint
  was called. Internal HTTP attempt counts remain unavailable.
- **Validation:** Two fresh blinded graders per case, four additional blinded
  scenario adjudications, and one protocol-consistency review. Raw opinions
  remain preserved. Case06's pre-existing approval-deferral clarification and
  original task prefix were supplied to the final consistency reviewer; no
  participant answer or scoring rule was changed. Four harness unit tests,
  frozen-input/schema/adapter checks, and all 64 deterministic link checks
  passed. One initial unmasked grader was invalidated; its complete usage is
  unavailable. A later grader reconnected after a Codex transport reset.
- **Gate outcome:** No assisted combination corrected a baseline material
  error, so none qualifies for the conditional repetitions/holdouts or Step 2
  integration. Pause and reconsider with Leo; no additional run is queued.
  Step 3 and all later work still require Leo's explicit subsequent approval.
- **Affected records:** Updated this intake log and the compact project-state
  handoff. The detailed report, machine-readable scores, accepted dispositions,
  and all test artifacts remain outside the vault at the location linked from
  project state. Source inventory is unchanged; no new career source entered.
- **Deliberate no-change:** No live Mail scan, skill or governing-workflow edit,
  scheduled prompt/model or weekday 9:00 a.m. schedule change, latest-scan
  refresh, person/register status update, task/question edit, sending,
  application submission, calendar operation, or credential change occurred.
  Pending John status reconciliation is untouched. No Git or commit was added
  to this intentionally non-Git archive; adapter commit `72b9e59` is unchanged.

# 2026-09-21 — Leo proposed Thursday at 3:00 p.m. to John Flores

- **Source:** Leo's direct statement that this is a real sent reply, plus a
  screenshot of “Re: Introduction — Leo Goldberg” showing the sent direction,
  recipient John Flores, exact body, and displayed time of 2:19 p.m. The
  screenshot was supplied after the 12:46 p.m. Mail scan and was not copied
  from its temporary attachment path into the archive.
- **Confirmed correspondence:** Leo told John that Thursday afternoon works,
  proposed 3:00 p.m., and offered to adjust if another time is easier.
- **Applied reconciliation:** Added the sent message to John's conversation
  history; aligned his Snapshot and outreach-register status to awaiting John's
  confirmation; updated project-state current focus; removed the completed
  availability/reply task; recorded Leo's answer and removed resolved Q-006;
  refreshed John correspondence provenance in the source index; and updated
  the latest-scan snapshot as a labeled post-scan direct intake, without
  implying another Mail scan.
- **Question/task judgment:** “Can Leo do Thursday or Friday afternoon?” is
  resolved by Leo's reply. Whether John accepts 3:00 p.m. remains unknown, but
  John owns that next move; passive external confirmation is status context,
  not a new Leo task or central open question. Q-005 and Jim's task remain
  unchanged.
- **Governing clarification:** Expanded the outreach playbook and the local
  `outreach-correspondence-sync` skill to reconcile either read-only Mail scans
  or directly supplied real correspondence. Added explicit distinctions among
  proposed time, agreed time, and calendar creation, plus a reusable archive
  relationship map in the skill.
- **External action:** None by the agent. Leo had already sent the evidenced
  reply; no message, calendar event, reminder, Mail mutation, or other external
  record was created here.
- **Validation:** Checked event uniqueness, register/Snapshot alignment,
  removal of Q-006 and the completed John task, preservation of unrelated work,
  proposed-versus-confirmed wording, affected Markdown links, and skill
  structure. The archive remains intentionally non-Git.
