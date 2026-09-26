# Refresh pass 01: review record

Date: 2026-09-22
Scope: C1 argument draft and early C2 exercise sketches, compared against the existing spine.
Review type: assistant editorial/design review plus bounded source verification. No educator review, classroom pilot, or live-model exercise trial performed.

Subsequent direction: the classroom sketches remain candidate transfer material. Jack corrected the print-first implementation; the [interactive essay lab](../../labs/failure-mode-lab/README.md) is now the active prototype. Preserve this record as the earlier pass, not the current delivery plan.

## Deliverables

- [Foundation brief](foundation-brief.md): shared argument for educator review.
- [Spine comparison](spine-comparison.md): all eight named claims, dependency order, source boundaries, qualifications, and remaining objections.
- [Exercise sketches](exercise-sketches.md): PME strategy, HE history, and high-school science, with prerequisites, support, learner choices, useful AI assistance, independent checks, and educator reuse.

## Starting sources and baseline

Read the canonical claim map, source spine, essay in the conversation, Vendrell/Johnston source note, workflow patterns, objections, cyber transfer case, trace template, and the two refresh planning documents. Rechecked the Bastani paper, EEF guidance, and National Research Council material linked in the comparison.

The companion is at `76742b7`; sibling workbench is at `b5daad9`. Git ancestry confirms site checkout `3ba5a4b` is an ancestor of `69ba124`. Subsequent commits include layout/accessibility/performance work and documentation. The companion essay and both site essay sources match byte-for-byte, SHA-256 prefix `92e65d59bd51af95`.

Use the newer sibling site checkout as the implementation review baseline, with explicit companion/workbench paths. The older workspace's canonical-location instruction still needs reconciliation with current deployment configuration before any release. No production deployment version was established by this content pass. No repositories were pulled, switched, or rewritten.

## Checks defined for the pass

| Check | Result and evidence |
| --- | --- |
| Preserve all eight claims and their dependencies | Pass, editorial scope. Each named claim is mapped; dependency order is separately explained because its numbering differs. |
| Preserve AI-enabled performance as a real target | Pass, design scope. Each sketch names useful assistance and an observable candidate benefit; none claims a measured improvement. |
| Keep purpose, frame, reliance, accountability, and transfer distinct | Pass. The brief identifies authorization; sketches specify learner-owned choices, review responsibility, and a changed task. |
| Include inherited AI-shaped inputs | Pass. PME summary, HE synthesis, and teacher-selected school materials are inspected, including when students never operate AI. |
| Teach foundations without treating readiness as age or credentials | Pass, proposed design. Each sketch has a task-specific check and a support response. Educational suitability remains unreviewed. |
| Preserve effort that develops the intended capability | Pass. Strategic causal analysis, direct source reading, and scientific inference remain learner work; teacher support is available. |
| Make learning observable without a compliance packet | Pass as a proposal. Short starting work, consequential revision/reliance evidence, and a changed task replace full prompt logs. Workload remains to be measured. |
| Keep faculty practice and institutional reuse visible | Pass. Every sketch includes educator rehearsal, colleague comparison, and a reviewed reusable artifact. |
| Distinguish the audiences substantively | Pass, design scope. Different framing authority, prerequisites, discipline standards, and transfer tasks are specified in the comparison table. |
| Bound source claims and examples | Pass. Synthetic data and constructed outputs are labeled; primary sources, repo summaries, proposed extensions, and unreviewed evidence are distinguished. |
| Produce complete classroom packets | Not claimed. Authentic HE sources, fuller PME case conditions, school teacher key/transfer materials, and educator review remain outstanding. |
| Establish learning benefits or general validity | Needs external evidence. No pilot result exists for these sketches. |

## Challenge and revision

The initial design risk was making all three activities a generic “spot the AI error” exercise. The final sketches require directing or accepting a useful contribution as well as explaining its limits. The PME case tests changing strategic priorities; HE tests a revised interpretation; high school tests what a changed comparison permits. Each has a response to missing prerequisite knowledge.

The source check also required preserving both arms of the Bastani finding: unrestricted assistance and teacher-informed scaffolding had different consequences. The brief avoids claiming either that AI generally harms learning or that safeguards prove learning gains.

Strongest unresolved question: could a learner perform the explanation of ownership while still lacking transferable understanding? These sketches include a changed task, but delayed transfer and durable learning remain future observations. Educator review should also test whether the added activity reveals anything beyond existing course practice worth its time cost.

## Decision

Pass for a reviewable argument and differentiated exercise sketches. Keep the shared pedagogy labeled proposed. Keep the canonical essay, claims, and source spine unchanged in this pass; proposed additions and qualifications are available for deliberate review.

C1 is drafted and checked against the spine, pending Jack's editorial judgment. C2 has concrete sketches, not finished packets. C0's local checkout relationship is established; deployment authority remains to verify before implementation/release. Jev stays separate and untested.

## Verification and next task

The foundation brief passed the writing-as-Jack mechanical checker and the documented judgment review. The saved prose matches the scanned scratch draft verbatim; its editorial check appears afterward. Local document links, Markdown fence balance, claim coverage, and unchanged canonical files are checked during delivery verification. No application tests were run because this pass changes only planning and draft documents.

Next bounded task: convert the reviewed sketches into usable educator packets, beginning with the common readiness/evidence template and then the high-school worked example. Select and review the actual HE source packet; complete PME case conditions and alternative defensible answers. Carry educator disagreements into the next cycle record. Site implementation follows stable content; public release and learning validation retain their separate checks.
