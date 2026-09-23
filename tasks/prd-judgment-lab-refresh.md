# Judgment Lab refresh: objectives and update loop

Date: 2026-09-22
Status: Complete cross-surface testing edition built and checked; preview release prepared. Production publication requires approval; educator trials are next.
Direction and alternatives: [Working brainstorm](judgment-lab-refresh-brainstorm.md).

## Objective

Refresh Judgment Lab into a coherent resource for PME, higher education, and K–12 educators and leaders. Preserve the essay's strongest argument, make learner foundations explicit, and deliver an audience-appropriate route from a practical question to a usable exercise and inspectable learning evidence. Evaluate Jev separately against educational criteria.

## Completion objectives

| ID | Objective | Done when |
| --- | --- | --- |
| O1 | Establish the shared argument. | Each of the eight current claims is retained, qualified, or kept PME-specific with a reason; the shared argument distinguishes evidence, interpretation, and proposed practice. |
| O2 | Make foundations teachable. | Every initial exercise names prerequisite knowledge/reasoning, an observable readiness check, support if needed, learner-owned choices, and a transfer task. Readiness is not inferred from age or credentials. |
| O3 | Make each audience view useful. | PME, HE, and K–12 each have one complete exercise, an educator-practice task, and a leader pilot brief; their prompts and materials match the audience. |
| O4 | Deliver a coherent site and source package. | A visitor can reach a suitable example, obtain the correct materials, and return using a stable link. Site copy, source bundles, templates, and downloads agree. Existing entry links remain usable. |
| O5 | Establish a review-and-improvement practice. | Each exercise has a documented educator review, a pilot protocol, an evidence status, and a reusable revision record. Actual pilot observations remain distinct from simulations and plans. |
| O6 | Reach an evidence-based Jev decision. | A bounded experiment has documented criteria, baselines, cases, disagreements, failure handling, and an adopt/revise/park decision—or an explicit deferred status with the missing prerequisite. Deferral does not block O1–O5. |

There are separate completion states: **ready for educator review**, **released as provisional materials**, and **field-tested in a stated setting**. A working website does not establish a learning benefit. A small pilot can inform revision without establishing causal effectiveness or broad validity.

Confirmed K–12 sequence: high school first, then adapt downward to middle and elementary school. The first release's K–12 exercise is explicitly high-school scoped. Later adaptations repeat C2–C3 for prerequisite knowledge, task complexity, teacher mediation, AI access, and evidence of learning, with educator review for each band. High-school results do not establish suitability for younger learners.

## Work ownership and source boundaries

- Shared claims and evidence: editorial/educational work, with Jack owning the intended argument.
- Audience adaptations: assistant drafts; relevant educators review disciplinary and developmental suitability.
- Companion: facilitation instructions, claim inspection, practice prompts, and context bundles.
- Workbench: assignment/lesson design, observation criteria, worked examples, calibration and reuse materials.
- Website: navigation, presentation, downloads, stable links, and generated assets.
- Jev: experimental software and evaluation records, kept separate from published educational claims.

Use existing authorized source material. An assistant can prepare review packets, simulate walkthroughs, and record findings; it cannot invent educator participation, approvals, or pilot results. Arrange external reviews through Jack unless outreach is separately authorized.

## Baseline verified on September 22

- The live site is a five-view, hash-routed package under The Irreducible Officer: Overview, Essay, Companion, Workbench, Sources. Companion and Workbench facilitate sessions through copied prompts and downloadable context; they are not embedded AI applications.
- The workbench has nine templates and six concept notes. Its framework matrix identifies its status as a hypothesis awaiting NWC validation.
- This companion checkout is at `76742b7`; the sibling workbench is at `b5daad9`.
- Two site checkouts differ: sibling `nwc-irreducible-officer-site` is at `69ba124`; `nwc/site` is at `3ba5a4b`. Their essay files match, but build script and contract-test files differ. The `nwc/README.md` names that workspace canonical; resolve this against current repository/deployment state before implementation.
- The sibling site build accepts `COMPANION_REPO_PATH` and `WORKBENCH_REPO_PATH`. Its existing tests assert PME-specific homepage copy and bundle details, so refresh those contracts deliberately with the new behavior.
- Existing untracked `.specstory/` content was present before this planning work; leave it alone.

These are dated observations, not a substitute for checking the worktree and deployment state at the beginning of implementation.

## How each cycle runs

1. **Select:** one objective, a bounded deliverable, and the checks that decide whether it is ready.
2. **Inspect:** read the current source and previous cycle; identify assumptions and dependencies.
3. **Produce:** draft or build the smallest complete version that can be reviewed.
4. **Challenge:** test the strongest plausible failure against the agreed checks. Separate source/content checks, technical checks, and educator evidence.
5. **Revise:** fix the material findings together; rerun affected checks.
6. **Record:** save what changed, evidence, unresolved issues, and the next decision. Update the objective status.

Allow an initial review and one confirmation pass by default. If the same material issue survives both, narrow the task or record the decision needed; do not polish indefinitely. A failed check returns work to the relevant earlier cycle. Only dependent work waits: missing external review does not prevent preparing other drafts or tests.

Decision vocabulary: `pass`, `revise`, `needs external evidence`, `deferred`. Label a pass by its scope—for example, “source consistency passed” or “educator usability reviewed.” Never turn a simulated review into field evidence.

When Jack requests the full update, repeat this loop across all ready cycles within the authorized scope. Routine successful checks are continuation points, not requests for fresh permission. Maintain a queue of blocked dependencies and continue useful independent work. Stop when the requested release state is achieved, Jack stops the run, or no meaningful authorized work remains without a missing decision or external evidence. Report exactly which objectives are complete and which are still pending; do not call the full project complete merely because the site is ready.

## Cycles and key checks

| Cycle | Deliverable | Checks before moving on | If a check fails |
| --- | --- | --- | --- |
| C0 — Establish the baseline | Source/deployment map, existing behavior inventory, release scope | Identify authoritative checkouts and deployment source; preserve existing work; identify source-to-generated-asset relationships and legacy links. | Resolve source ambiguity before code edits; content analysis can continue. |
| C1 — Generalize the argument | Claim portability map and short shared argument | All eight claims accounted for; purpose vs authorization distinguished; task-dependent friction explicit; counterexamples and evidence limits recorded; no implied cross-domain validation. | Revise the relevant claim or keep it audience-specific. |
| C2 — Design the teaching | Essay-first interactive failure-mode lab with PME, HE, and high-school educator paths | Assistant collects the educator's judgment, waits at decisions, offers useful contestable assistance, changes conditions, and supports teaching transfer; foundations and human responsibilities explicit. | Revise the interaction or support; do not substitute a packet for the session. |
| C3 — Review audience fit | Audience walkthroughs and educator review packets | A visitor can recognize the problem and expected output; examples use the discipline's standards; K–12 specifies grade band and teacher mediation; accessible assessment alternatives and access constraints addressed. | Rewrite the task/materials; do not solve a pedagogical mismatch with labels. |
| C4 — Build one complete path per audience | Homepage, audience views, session pages, matching prompts and context bundles | Deep links and browser history work; correct prompt/context for each audience; copy/attachment path works; loading/fetch/copy failures are visible and recoverable; source tests and browser checks pass. | Fix the affected path and retest; return to C2 if the interaction is unusable. |
| C5 — Package and release | Reviewable release candidate, status labels, release notes, recovery method | Source and generated artifacts match; legacy links work; claims reflect actual evidence; required educator-review status is visible; public-release authorization exists for this phase. | Keep as a review candidate and finish the missing work; use existing authorization where applicable. |
| C6 — Observe and improve | Pilot records, revised teaching materials, updated evidence statuses | Compare intended with observed learning evidence; record educator workload and access friction; inspect an unsuccessful or ambiguous case; state what the observations do and do not support. | Revise C1/C2/C3 as needed. Schedule the next bounded iteration from evidence. |

For C4, run the project's relevant build and contract tests, then inspect representative desktop and mobile views plus keyboard operation. Verify copy/download content as well as visible pages. Test assistant facilitation with the actual generated bundle for each audience; record the assistant and date. Confirm missing-source behavior instead of accepting an invented exercise context. Do not add tests that merely freeze every sentence of the new copy.

## First work units

These are proposed implementation units, not work completed in this planning turn.

| Unit | User need and output | Acceptance criteria |
| --- | --- | --- |
| W1 | As a reader, I need to understand the shared argument and its limits. Produce the portability map and shared brief. | O1 checks pass; the PME essay remains identifiable and any proposed essay edits are listed explicitly. |
| W2 | As an educator, I need to judge learner readiness before choosing AI assistance. Produce a common exercise template. | Knowledge, readiness evidence, support, consequential choices, AI role, human review, transfer, and reusable note are all included. |
| W3a–c | As an educator in each setting, I need to experience the method. Run an essay-based failure-mode session, then adapt it to PME, HE, or high school. | Each path uses the source context, collects human judgment, tests a changed condition, and saves a reviewable record; no unmade decision is silently invented. |
| W4 | As a leader, I need to run a manageable trial. Produce a pilot brief and calibration activity for each setting. | Purpose, participants, time to measure, evidence collection, review responsibilities, and continue/revise/stop decision are explicit. |
| W5 | As a visitor, I need to find the right task. Build the homepage and audience navigation. | Audience paths and individual exercise links work, including refresh/back; verify in the browser. |
| W6a–c | As an educator, I need the chosen session and assistant context to agree. Connect each audience path to its guided session. | Correct copy/download, source bundle, fallback and visible error behavior; verify each full path in the browser and an actual assistant session. |
| W7 | As a returning reader, I need existing links and resources to remain useful. Prepare release verification. | Legacy essay/context links, source consistency, evidence labels, build/tests and release recovery are verified. |

## Jev experiment loop — separate dependency

J1: Define one educationally meaningful decision and educator-authored candidate questions. Specify inputs, allowed outputs, abstention/review path, and consequential error types.

J2: Build a small, documented set of synthetic or authorized examples with educator judgments. Include ambiguous, incomplete, paraphrased, and misleadingly polished responses. Record disagreements rather than forcing false consensus. Separate development cases from held-out evaluation cases.

J3: Compare simple routing/fixed questions, a general-model baseline when available, and Jev. Measure useful-question selection, consequential errors, appropriate abstention, sensitivity to irrelevant wording, and cost/latency. Define operational thresholds before examining held-out results; a confidence score is not evidence of learner mastery.

J4: Decide adopt/revise/park. Any adoption starts as a bounded recommendation to the educator, with an inspectable record and override. Record model/version, criteria, case-set version, and limitations so later changes can be checked. Keep provider access, credentials, and experiment authorization as prerequisites to execution; none is assumed by this plan.

## Strongest counterexamples to use in review

- A novice benefits from a supplied frame; requiring independent framing first blocks rather than develops learning.
- A student explains an AI-produced answer fluently but cannot perform a related task.
- A student understands the subject but an oral-only assessment obscures that understanding.
- Teacher AI fluency rises while the lesson removes the practice students needed.
- A reusable template spreads a narrow interpretation across classes.
- Jev consistently selects a plausible follow-up that educators judge unhelpful or biased by writing style.
- A polished site passes technical checks while its copied prompt still asks a school teacher to act as an NWC instructor.

## Evidence to collect

For each pilot, record the starting work/readiness check, the support provided, the revised work, one meaningful reliance decision where applicable, and performance on a changed task. Record educator preparation/review time and practical access problems. Capture teacher/faculty disagreements and resulting revisions.

Set feasible targets with the pilot educator before the run. Do not invent improvement percentages. Stronger artifacts, reported satisfaction, and observed independent capability are different findings. A causal claim of improved learning requires an appropriate evaluation design beyond this initial usability/pedagogical pilot.

## Cycle record template

```text
Cycle / date:
Objective and deliverable:
Starting source versions:
Assumption being tested:
Checks defined before work:
What changed:
Evidence / artifact paths:
Review type: assistant walkthrough / technical / educator / classroom pilot
Results by check: pass / revise / needs external evidence / deferred
Strongest unresolved issue:
Decision and rationale:
Next bounded task:
```

## Current status and next run

Planning record P0: created the brainstorm and loop plan from the conversation and inspected repository/build context. No site, essay, or teaching-template changes made. No classroom validation or Jev evaluation performed.

Decision D1, September 22: Jack selected “High school, then adapt downward.” Recorded in both planning documents. Grade-band order is settled; subject, exercise details, and educator reviewers remain open.

Pass 01, September 22: [foundation brief](refresh-pass-01/foundation-brief.md), [spine comparison](refresh-pass-01/spine-comparison.md), and [three exercise sketches](refresh-pass-01/exercise-sketches.md) drafted. See the [cycle review](refresh-pass-01/cycle-review.md) for checks, source limitations, and next work. The local site ancestry and essay consistency are confirmed; deployed source remains to verify.

| Objective | Status |
| --- | --- |
| O1 | Shared argument and all eight claim mappings drafted; editorial/design check passed, Jack's review pending. |
| O2 | Readiness guide and audience-specific facilitation drafted; explicit foundations/support in teaching transfer. Educator validation pending. |
| O3 | Seven-mode lab, three complete audience guides/transfer cases/educator trial briefs, and all nine workbench adaptations implemented. Educator testing pending. |
| O4 | Full site integration and download consistency checks pass; browser paths checked. Testing preview delivered; production approval pending. |
| O5 | Lab review record distinguishes source/package verification from constructed walkthroughs and actual pilot evidence. Educators and pilot settings not yet confirmed. |
| O6 | Bounded Jev experiment proposed; execution deferred. |

Decision D2, September 22: Jack reaffirmed the interactive workbench. Educators test the essay's failure modes before transferring the method into teaching. The print-first high-school packet is superseded; its science material is an optional transfer draft. See the [interactive lab](../labs/failure-mode-lab/README.md) and [review record](../labs/failure-mode-lab/review.md).

Next run: use the [full-refresh testing guide](full-refresh-review.md) to run authentic educator sessions on the complete preview. Site integration, all nine template adaptations, source downloads, and browser/contract checks are complete. Inspect assistant adherence and instructional usefulness before making pilot claims. Production publication is separately gated by the automatic approval review. Keep Jev and younger-grade adaptations as separate workstreams.

## Reusable task prompt

> Read `AGENTS.md`, `tasks/judgment-lab-refresh-brainstorm.md`, `tasks/prd-judgment-lab-refresh.md`, `claims.md`, and the latest cycle record. Inspect current source state before editing. Run the next authorized bounded cycle in this plan; if asked to run the full update, continue through successive ready cycles using the continuation rule above. State the deliverable and pass checks, do the work, challenge it with the strongest relevant counterexample, revise once, and record the result and next task. Preserve the distinction between the shared argument, audience adaptations, research evidence, technical verification, and educator/pilot evidence. Continue independent work when a dependency is missing; ask only for the missing decision. Do not treat this planning document as authorization to publish, contact reviewers, or start provider-backed experiments. Use any subsequent explicit authorization already given in the session.
