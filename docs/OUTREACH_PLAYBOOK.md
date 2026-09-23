# Outreach playbook

This playbook records proven historical practices and clearly separates them
from proposed process. It does not authorize sending any message.

## Required first-touch workflow

1. Verify the recipient's identity, current role, company, relationship, and
   whether the contact is warm or cold.
2. Select the relevant document-positioning bucket: S&T/finance,
   consulting/business-general, or insurance when a resume is needed. These
   historical resume buckets do not prescribe a narrative. Confirm the actual
   authoritative file before attaching anything.
3. Research one genuine relevance hook: referral, desk/function, school tie,
   shared experience, or a specific prior conversation.
4. Read the [Leo profile](PROJECT_MEMORY.md) and relevant detailed evidence such
   as [business-school work](BUSINESS_SCHOOL_WORK.md). Select the accomplishment
   or parts of the work Leo wants emphasized and the facts useful to this
   recipient. Connection/context, relevant proof, a modest ask, and a flexible
   close are useful defaults, not a required order or formula. Do not impose a
   canned paragraph or compulsory combination of experiences.
5. Review against `EMAIL_STYLE.md` for repetition, defensiveness, unnecessary
   proof, and burden on the recipient.
6. Present the draft to Leo. Do not send or record it as sent without explicit
   authorization and evidence.

## Warm-introduction workflow

- Give the connector a concise, easy-to-forward note and the correct resume.
- Thank the connector separately when useful and minimize their effort.
- Contact the introduced person directly after the introduction.
- Copy the connector only when the context supports it.
- Record actual dated correspondence; never infer send status from the
  existence of a draft.

## Targeting principles

Historical targeting used firm/desk relevance, alumni or school ties, previous
employer connections, and trusted referrals. Email is the primary documented
channel; LinkedIn has also been used or planned. The correct order between
email and LinkedIn is not yet established.

## Durable Markdown workflow

**Confirmed 2026-09-18:** New outreach is managed in Markdown rather than by
requiring Leo to maintain a separate spreadsheet.

- `outreach/OUTREACH_REGISTER.md` is the canonical compact queue for outreach
  begun on or after 2026-09-18.
- Each person or coherent conversation gets one record under
  `outreach/correspondence/people/`, created from
  `outreach/correspondence/agent-docs/THREAD_TEMPLATE.md`.
- The register and each person's Snapshot use the same lean fields: Person,
  Organization, Role, Relationship path, and dated Current status.
- The register additionally holds the canonical Contact method as
  `Email: name@example.com`, `Phone: +1 ...`, or `Unknown`; do not duplicate
  mutable addresses or phone numbers in person notes.
- The person record holds actual Conversation history, useful Preparation
  context, and Next steps. Add Open questions only when an answer materially
  blocks or changes imminent outreach. Link specific accomplishment sections
  instead of copying the full story into each person's record.
- Conversation history uses dated headings for actual emails, calls, meetings,
  and introductions. Preserve exact sent/received wording when useful. Internal
  preparation and unsent drafts are not conversations.
- Review Next steps using the [correspondence action rule](#Correspondence-action-review).
  Store each action once in [Leo To-Do](LEO_TODO.md#Outreach), linked to its
  supporting person-note evidence, with a backlink from the note.
- Historical spreadsheets remain source evidence and are not modified or kept
  in sync unless Leo explicitly requests that work.

Current status should state the actor/event and relevant date after contact
begins, for example `Leo sent — YYYY-MM-DD`, `Reply received — YYYY-MM-DD`, or
`Meeting scheduled — YYYY-MM-DD`. `Not yet contacted` may remain undated.
Leo's dated confirmation or actual correspondence evidence is required for any
status that implies sending, receiving, replying, or scheduling.

Inbox reconciliation may inspect only account-scoped correspondence for an
existing register contact whose email identity is explicitly mapped. Unknown or
ambiguous senders do not create contacts. A scan defaults to a proposed change
set except for automatic task capture and its supporting evidence/question
links, plus the latest-scan refresh. Other canonical reconciliation requires
Leo's approval. Scans never authorize outbound mail or Mail-state changes.

Leo may instead supply real sent or received correspondence directly as text,
a screenshot, or a dated confirmation. When he asks to reconcile that evidence,
record it without redundantly accessing Mail. Keep visible header limitations
explicit, and never treat a draft or proposed wording as sent. A direct intake
received after a scan is not another Mail scan; preserve the latest scan's
method metadata and label the later intake separately.

The replaceable [outreach scan update](OUTREACH_SCAN_UPDATE.md) is the visible
latest-completed-scan record. Refresh it after every successful scan, including
when no new correspondence is found. Keep its header for the scan date,
accounts, method, and external-action boundary. A no-result scan removes the
prior correspondence delta and states that nothing new matched. When messages
match, handle each person separately under `New correspondence` using:
**Evidence → Record changes → Deliberate no-change**. If correspondence
resolves an open question, name the question, record the canonical answer and
affected record, and state that the question was removed. If it only confirms
a contact method or adds history, state exactly that. Refreshing the scan
snapshot alone does not authorize other canonical changes. Clearly identify
every automatic task and supporting evidence/question-link change as applied,
separately from proposed changes awaiting approval. Do not imply a status, task, meeting, follow-up, or resolved
question unless the message or Leo's direct instruction establishes it.

## Correspondence action review

Always consider whether the correspondence requires action from Leo. If it
does, automatically capture the action in the to-do list and link the relevant
records. If no action is required, leave Next steps as `None`. Reflect every
captured change in the latest scan update.

Apply judgment to the evidence rather than an exhaustive list of triggers.
Preserve existing outstanding actions when a new message does not affect them;
check for an existing action before adding another. Passive waiting is status
context. Empty scans refresh the snapshot without erasing outstanding work.

Automatically capture actionable unanswered questions in
[Open questions](OPEN_QUESTIONS.md), including correspondence questions, with
links to person-note evidence and the corresponding task. Person notes link
back to the central question rather than maintaining competing question lists. Other canonical
reconciliation, including question resolutions and status changes, remains
approval-gated. Capturing a local action does not send a reply, establish a
deadline, or schedule a meeting.

For scheduling correspondence, preserve three separate states: proposed time,
agreed time, and calendar event. Leo proposing a time can resolve his
availability question and complete his reply task, but it does not establish
the recipient's acceptance or create a meeting. While the recipient's
confirmation is the only next move, record that wait in the person/register
status; do not create a chase task or a central question merely asking whether
the recipient will agree. A recipient's explicit acceptance can establish an
agreed time, but calendar creation requires separate evidence.

Before finishing, consider Leo's next action, reconcile affected questions and
tasks within the authorized scope, check reciprocal links, and account for
every automatic change in the [latest scan](OUTREACH_SCAN_UPDATE.md).

Leo confirmed on 2026-09-18 that the priority is seeing how long it has been
since outreach, not a universal follow-up cadence. Keep actual dated
interactions and calculate elapsed days when reviewing; do not save a stale
day counter or create automatic reminders. Old applications and contacts are
inactive unless Leo explicitly reactivates them.

When a source correction affects an unsent draft, revise it in chat before
sending. Preserve sent wording in Conversation history. Preparation dates do
not establish send or conversation dates. A future date does not authorize a
reminder or external communication.

## Constraints

- Do not overstate experience, connection strength, or fit.
- Do not fabricate familiarity or current role information.
- Do not expose private contact information unnecessarily.
- Do not follow up repeatedly until Leo approves a cadence and stop rule.
- Do not contact anyone or modify a tracker without explicit instruction.
