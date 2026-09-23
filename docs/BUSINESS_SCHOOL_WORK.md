# Business-school analytical work

Updated 2026-09-18. This is the canonical detailed account of Leo's work with
the University of South Carolina Darla Moore School of Business. Select the
accomplishments relevant to the request; this is not an email formula or a
required narrative. Other experience is indexed in the
[Leo profile](PROJECT_MEMORY.md).

## Origin and ownership

**Confirmed by Leo's direct correction, 2026-09-18:** The assignment began in
March 2026 with a question: determine the incremental costs and revenues of
enrolling additional students. Leo recognized that the university's financial
mechanisms made this a broader planning problem. The school lacked the
formula-based connection between its financial information, university
allocation policies, and forward decision analysis that he needed to answer it.
He built the model to supply that capability.

Leo researched the rules, reconstructed historical calculations, designed the
financial relationships and scenarios, directed formula/dependency analysis,
reviewed findings, and used AI to implement and test the architecture. It is
accurate to attribute model creation and analytical/design ownership to him.
This does not establish that he manually typed every formula or wrote every
macro unaided. AI-assisted implementation does not reduce his contribution to
documenting somebody else's model. [S-006](SOURCE_INDEX.md#S-006%20%E2%80%94%20Leo%27s%20corrections%20and%20approved%20work%20account)

**Superseded framing:** The initial 2026-09-18 synthesis said Leo "helped turn"
an existing model into a controlled tool and described an "AI-assisted redesign
and documentation effort." It captured a later refinement phase but omitted
the origin and creation of the model. Do not reuse that as the overall account.
The historical John drafts preserve that earlier wording solely as draft history.

## Timeline and working relationship

- **Confirmed by Leo, 2026-09-18:** March 2026–present is the project date range
  he approves for networking. He reported limited activity for roughly the last
  six weeks; the range does not establish continuous paid employment.
- **Confirmed by Leo, updated 2026-09-19:** Greg is the dean, the principal
  budget stakeholder, and Leo's formal direct supervisor. The work involved
  repeated presentations and live scenario discussions with him, followed by
  attempts to establish an authorized arrangement to finish it. “Reporting
  directly to the dean” is accurate resume language.
- **Confirmed by Leo, 2026-09-19:** The on-paper administrative title he recalls
  was “Executive Assistant.” It was used because a title had to be entered for
  employment paperwork and did not define the work he was expected to perform.
  No functionally accurate project title was established. For professional
  descriptions, lead with the actual financial-modeling work and reporting
  relationship; do not present “Executive Assistant” as the substantive role
  unless reproducing an official employment record requires it.
- **Unknown:** the precise employment classification and compensation record,
  and whether a new employment arrangement will be approved.
- Current institutional status is recorded [below](#Current%20institutional%20status),
  not inferred from the open-ended project date range.

## Policy research and financial architecture

**Confirmed as Leo's approved account:** He brought together the Budget Model
User Guide, FY2022–FY2026 University budget documents, and internal school
spreadsheets/projections. He translated written policy into formula
requirements, traced workbook dependencies, and tested reconstruction against
published figures. Internal data were not all complete or consistent.
[S-006](SOURCE_INDEX.md#S-006%20%E2%80%94%20Leo%27s%20corrections%20and%20approved%20work%20account)

**Confirmed in the reviewed FY2026 guide:** revenue-dollar timing and
allocation-metric timing differ. The FY2026 budget generally uses prior-year
revenue and a two-year average of FY2023/FY2024 allocation metrics. Undergraduate
tuition allocation is 70% college of instruction and 30% college of record.
The guide specifies a 16.8% participation fee on particular unrestricted
revenue streams and a separate fixed-amount participation fee. Graduate tuition
has its own implementation; do not assume every revenue line uses undergraduate
pool mechanics. Guide pages 3–4 and 7 support these distinctions.
[S-007](SOURCE_INDEX.md#S-007%20%E2%80%94%20University%20budget%20primary%20documents)

**Confirmed as Leo's account of his model design:** Immediate staffing and
instructional costs, later recurring revenue, and still later allocation
effects had to be modeled on separate clocks. The resulting decision analysis
connected enrollment and faculty hiring to tuition/appropriations, retained
revenue after participation fees, salary/fringe and one-time costs, delayed
support allocations, central bridge items, and multiyear margin relative to a
zero-scenario baseline.

He investigated the participation fee's actual revenue base rather than merely
applying 16.8% to every revenue line. His supplied audit account identifies
exclusions such as budget transfers, academic fees, direct state appropriations,
and some restricted revenue, and distinguishes workbook convention from policy.
The exact workbook fee-base formula was not independently inspected here.
Future pool growth, credit-hour baselines, student-to-credit-hour conversion,
instructional capture, staffing capacity, and revenue-per-credit-hour proxies
were explicit modeling assumptions, not asserted university policy.
[S-008](SOURCE_INDEX.md#S-008%20%E2%80%94%20VM%20reconciliation%20evidence%20supplied%20by%20Leo)

## Reconstruction across two allocation regimes

**Confirmed by Leo:** He reconstructed five published fiscal-year budgets,
FY2022–FY2026, across two university allocation rule systems before using the
logic for decision projections. The absence of that decision-analysis link at
the school is his direct account, not a university-wide systems audit.

**Confirmed in the primary appendices:** FY2022–FY2025 use the older 15
support-cost categories; FY2026 uses seven cost pools and two-year-average
shares. Refer to this precisely as the FY2026 budget-model transition. Leo
described the change as occurring "in 2025"; calendar-year timing may explain
the wording, but that interpretation is not independently established.
[S-007](SOURCE_INDEX.md#S-007%20%E2%80%94%20University%20budget%20primary%20documents)

The supplied regime crosswalk is derived analysis, not official policy. It
distinguishes comparable allocation drivers from comparable cost-pool
composition: matching a driver does not prove that old cost pools can simply
be summed into a new one. This matters when comparing hiring or enrollment
effects across regimes.

## Historical reconciliation results

**Confirmed as supplied by Leo from the VM audit; arithmetic checked here.**
The following compares published UWBD **proposed-budget** figures with the
reconstructed final margin **after model allocations and before Expense Budget
Net (EBN)**. These are not realized year-end actuals, forecast-accuracy scores,
or proof that every workbook formula is correct.

| Fiscal year | Published proposed budget | Rebuilt model | Model minus published | Absolute variance / absolute published margin |
| --- | ---: | ---: | ---: | ---: |
| FY2022 | $1,437,181.00 | $1,425,753.80 | −$11,427.20 | 0.7951% |
| FY2023 | $706,931.00 | $720,598.08 | +$13,667.08 | 1.9333% |
| FY2024 | −$2,404,301.00 | −$2,422,695.23 | −$18,394.23 | 0.7651% |
| FY2025 | $7,655,099.00 | $7,660,470.89 | +$5,371.89 | 0.0702% |
| FY2026 | $3,570,983.00 | $3,570,555.31 | −$427.69 | 0.0120% |

Absolute annual differences range from $427.69 to $18,394.23. FY2023's smaller
published margin yields the largest percentage difference. No overall
"99.97% accurate model" claim follows from these results.

Supplied workbook locator: `C:/Repos/Excel Development/excel/current/Model 6.7.xlsm`,
sheet `Actual Model Audit - Filled`, ranges `B38:T38` and `W2:X7`.
This VM workbook was not opened or recalculated in Networking.
[S-008 and audit transcript locators](SOURCE_INDEX.md#S-008%20%E2%80%94%20VM%20reconciliation%20evidence%20supplied%20by%20Leo)

### FY2022 support allocations

This is a separate, narrower reconciliation. Positive numbers below represent
allocation burdens; the workbook represents these as negative expenses.

| Scope | Published | Modeled | Modeled minus published | Share of variance |
| --- | ---: | ---: | ---: | ---: |
| O4 — Central Services & Administration | $12,074,194.00 | $12,084,747.58 | +$10,553.58 | 92.3% |
| Other allocations, O1–O3 and O5–O15 | $25,794,780.00 | $25,795,665.84 | +$885.84 | 7.7% |
| Reported total | $37,868,974.00 | $37,880,413.43 | +$11,439.43 | 100.0% |

The reported total difference is **0.0302079%, or 0.0302%**, of published support
allocations. The displayed modeled component rows sum to $37,880,413.42, one
cent below the supplied total. Preserve that precision note if quoting the
detailed table; it does not change the stated percentage.

**Inferred explanation in the supplied audit:** approximately 92.3% of the
residual is concentrated in the employee-FTE-driven O4 allocation, consistent
with reconstructing from publicly displayed rounded drivers rather than the
institution's underlying fractional values. The appendices warn of rounding
differences, but original unrounded driver data would be needed to establish
that explanation conclusively. The supplied audit reports no unexplained
balancing plug; this is not an independently rerun workbook finding.

### FY2022 margin bridge and resolved source discrepancy

The supplied component bridge is +$15.90 student revenue, −$2.67 participation
fee, and −$11,439.43 support allocations: net **−$11,426.20**.

**Resolved by Leo's 2026-09-18 source clarification:** the published final
margin is $1,437,181, while its displayed components sum to $1,437,180. That
one-dollar source inconsistency explains why comparison to the published final
margin yields **−$11,427.20**. Retain $1,437,181 as the published comparison
baseline. Which value governed the institution's underlying calculation is
unknown and is not a blocker or an open reconciliation task. This resolution
is distinct from the one-cent table precision note above.

## Scenario development and technical proof

**Confirmed as documented historical workflow results, not rerun here:**

- Faculty Hire and Student Growth scenarios connect operating choices to
  credit-hour attribution, student/faculty FTE, direct expense, timing, and
  multiyear pre-EBN margin effects.
- A dependency trace found 693 downstream reference occurrences into 24 MSB2
  handoff cells, including 288 references to the effective-year gate. The
  architecture preserved that handoff while separating user-facing scenarios
  from technical plumbing.
- Saved inputs in an inactive scenario were designed to be harmless; dual
  activation failed closed. Five-state testing covered baseline, Student
  Growth, Faculty Hire, conflict, and repeated baseline.
- The 5% Student Growth case recorded 6,007.878 new school-of-record credit
  hours, 4,505.908 school-taught credit hours, 1,501.969 record-only credit
  hours, 201 student FTE, 1.502 faculty FTE, and $706,481.38 direct expense.
- The Faculty Hire case used 1.0 faculty FTE, $50,000 salary, $15,000 fringe,
  and $65,000 direct expense.
- Leo personally created the experimental 6.7 copy and duplicated the bridge
  sheet. The later architecture/testing work involved Leo, Codex, and the
  Excel agent. Reports of tested 6.7/6.6 parity do not certify every scenario.

The exports distinguish scenario-induced deltas from absolute final margins
and include limits around the tested workbook package identity. They describe
6.6 as canonical and 6.7 as experimental at that historical point; the supplied
6.7 audit table does not establish a later production promotion.
[S-004, specific export locators](SOURCE_INDEX.md#S-004%20%E2%80%94%20Business-school%20repository%20conversation%20exports)

## Leadership engagement and outcomes

**Confirmed as Leo's reviewed and approved transcript-based account:**

- August 25, 2026: Greg described support allocation as one module in a broader
  budget decision model. A $100,000 salary example needed salary, fringe,
  support allocations, and overall budget effect to flow together. He discussed
  possible demand from Audrey and graduate/undergraduate divisions; a small
  internal analytical group was an idea, not an approved organization.
- September 4: Greg reaffirmed wanting the Excel budget model completed.
- September 9: Greg sought the entire budget implications of faculty hiring
  and additional students, including multiyear forecasts. During a live
  demonstration he supplied a $100,000 salary and asked about 30 more students.
  These demonstrate engagement with decision logic, not independent user
  acceptance testing.
- Charles Kerns observed the September 9 demonstration, recognized advanced
  AI use, and raised maintenance/succession concerns. This is not financial
  validation. Patricia was discussed as a possible finance user/steward;
  independent use or acceptance is unestablished. Heather and Tawana were
  administrative/employment stakeholders, not analytical validators.
- The work challenged carrying an approximately $42,000 historical hire-support
  benchmark into the new regime, broadened requested analyses, and prompted
  discussion of summer enrollment, added students, a statement of work,
  possible $9,999 consulting contract, hourly rehire, remote-work permission,
  and AI access. None of those discussions proves an executed contract.

**Unknown / not established:** a changed approved enrollment/hiring/budget
decision, formal adoption, independent operation of the latest workbook by
Greg, or quantified realized institutional savings. Leadership wanted an Excel
deliverable usable without requiring the end user to interact with AI.
[S-009, meeting locators](SOURCE_INDEX.md#S-009%20%E2%80%94%20Stakeholder%20account%20and%20Greg%27s%20email)

## Current institutional status

**Confirmed from the email Leo supplied on 2026-09-18:** Greg checked in,
reported no progress toward getting Leo employed to finish the project, and
said he would work on it "next week." Leo directly confirmed sending his reply
on September 18, requesting a decision by the end of the following week. The
email header itself is not archived, so the exact clock time is unavailable.
This confirms renewed communication and stated intent, not employment approval
or a restart date.

Earlier reported blockers included authorization/contracting or rehire,
compensation, vendor/SOW steps, remote permission, AI approval, internal-data
integration, independent user review, maintenance, and leadership time. Greg's
new email updates the employment-status evidence; it does not prove resolution
of every other blocker. Leo's approved account also says Heather had instructed
that work could not continue before an authorized arrangement existed.

**Supported interpretation:** continuing stakeholder interest with unresolved
institutional execution. There is no documented rejection on the merits, and
no basis to claim completed implementation.

**Update — Leo, 2026-09-18:** Leo confirmed sending a reply requesting a
decision by the end of next week on continuation, approved scope, funding,
AI usage allocation, and the anticipated restart date. He reported roughly
six weeks since his last submitted billable hours and more than a month since
his last paycheck. He prefers completing the work but will prioritize other
paid opportunities without a confirmed path forward. Employment remains
unresolved. The [Greg conversation record](../outreach/correspondence/people/greg--business-school.md)
preserves the sent text and requested deadline. No reminder was created.
[S-009](SOURCE_INDEX.md#S-009%20%E2%80%94%20Stakeholder%20account%20and%20Greg%27s%20email)

## Adjacent product exploration

**Confirmed by Leo:** The experience led him to explore a web interface over
Excel, obtain his own AI account, and pursue a more durable Excel-centered
visualization/decision experience. Subscription/API-supported service and
operation while the analyst's computer is off or Excel is closed are ambitions
he sees as a potential opportunity, not delivered capabilities.

**Confirmed in the separately reviewed product records, 2026-09-18:** Scenario
Studio has an AI-assisted React browser prototype with fictional data. Its
scenario board supports five element kinds (metric, trend, comparison,
assumptions, notes), editable context, reordering, three prepared enrollment
cases, and recipient preview. An earlier eight-screen task-pane prototype also
exists. This demonstrates interface experimentation, not a connected financial
service or independent proof of Leo's coding mastery.

**Confirmed by Leo, 2026-09-18:** He built the custom prototype through
AI-assisted, informal “vibe-coded” development and, in doing so, learned the
fundamentals of JavaScript, Node.js, Git, React, and how the parts of a modern
web stack work together. This supports hands-on foundational experience, not a
claim of formal software-engineering training or production-level mastery.

**Not implemented at that review:** workbook access, Excel execution, genuine
financial calculations, persistence, authentication, API/AI calls, actual
publishing, and independently available calculation while the author is offline.
Current direction keeps Excel as calculation authority and the analyst as
author; remote execution and commercial validation remain unresolved. Do not
assert superiority over Abacum, HiBob, or other competitors from Leo's
tentative comparisons. This product is distinct from the school's model.
[S-010](SOURCE_INDEX.md#S-010%20%E2%80%94%20Scenario%20Studio%20product%20work)

## Using this evidence

Leo can ask to emphasize any accomplishment or part of the work. Choose facts
for the actual recipient, purpose, and requested format; omit irrelevant
technical or administrative detail. There is no required order, set of
experiences, stock paragraph, or fixed audience taxonomy.

**Inferred professional framing:** financial planning and analysis, financial
modeling, and decision support fit the work described. Leo explicitly offered
FP&A as a guide, not a canonical title. Accuracy should preserve his ownership
without upgrading historical reconstruction into forecast guarantees, interest
into adoption, or product ambitions into implemented features.

For exact remaining uncertainties, see [Open questions](OPEN_QUESTIONS.md).
