# Judgment Lab: full refresh testing guide and review

September 23, 2026. Release candidate: `2026-09-workbench-audiences`.

## Start tomorrow

Open the [testing preview](https://nwc-learning-companion--audience-refresh-zkiwg8wa.web.app). It expires September 30, 2026. This is the complete refreshed site, with the same audience source files used in its downloads.

1. Start with **K–12 · High school**, then **Start an interactive session**.
2. Download the lab context and attach it to a fresh assistant conversation. Copy the interactive lab prompt from the preview. Use an assistant with attachments or paste the context; the site does not contain a chatbot.
3. Run one failure mode. Check that the assistant waits for your initial judgment, presents a contribution, tests the reasons, changes a condition, and records decisions you actually made.
4. Transfer to a real learning objective. Check whether the teacher's role, student prerequisites, support, and learner-owned choices are appropriate.
5. Open the workbench to adapt the exercise or compare assessment judgments. Repeat the path in HE and PME, using a different case and the discipline's standards.

Record the assistant/model, date, audience, case, support used, unhelpful behavior, time spent, and the teaching decision changed. Keep the actual interaction separate from the authored walkthrough. Do not treat a completed chat as evidence of retained learning.

## Surface inventory

| Surface | Refresh |
| --- | --- |
| Homepage and identity | Judgment Lab umbrella; three audience entry paths; original essay still identifiable. |
| PME view | Professional context, risk and authority, fictional outage/attribution transfer case, readiness and educator trial. |
| HE view | Disciplinary reasoning, fictional survey inference case, sampling change, feasible review at course scale. |
| K–12 view | High school first; explicit prerequisites, teacher modeling, bounded student inference, fictional surface-temperature case. |
| Essay | Text unchanged; labeled as the original PME application, with working PDF and section anchors. |
| Companion | Audience-aware setup and starter prompts; seven-mode interactive lab; context attachment/web fallback. |
| Workbench | Three distinct workbench views; 27 adapted templates, setting-specific assessment criteria and prompts, worked examples, role matrices, and validation requirements. |
| Sources | Original spine unchanged; shared foundation and separate, checked adaptation-evidence notes. |
| Downloads | Audience guides, foundation, evidence notes, companion/workbench/lab bundles, all templates and concepts, framework assets, essay PDF. |
| Navigation | Audience travels in the URL and copied prompts; stable workbench document links; refresh/Back and keyboard routing. |
| Metadata | Judgment Lab title, description, and share card. |
| Repository guidance | Companion/workbench routing, source kits, starter prompts, and site build/check instructions updated. |

## Review findings corrected

- Print-first delivery displaced the interactive essay workbench. Made educator practice the entry path and superseded the classroom packet.
- Audience labels alone left PME assumptions in template bodies. Revised frame ownership, conditional independence, evidence standards, rating limits, and adult responsibilities.
- A universal phase ladder conflicted with novice support. Recast placement as task-specific design; judgment of a supplied contribution does not require prior workflow codification.
- The rubric adaptation mentioned a 0–3 scale although the source used 1–4. Corrected it and clarified that descriptors are unvalidated discussion aids, not automatic grades.
- All flawed examples could teach reflexive rejection. Added warranted-acceptance checks and changed conditions; inspection criteria now permit justified acceptance.
- Generated JavaScript had an escaped-newline error. Corrected it and retained script parsing checks.
- Repeated audience headings created duplicate IDs. Namespaced them and added a uniqueness check.
- Flat legacy downloads had incorrect relative links. Preserved legacy URLs, corrected link resolution, and emitted the supporting directory tree.
- Workbench selection did not survive reload. Added stable document routes and checked refresh/Back behavior.
- Clipboard failure left hidden starter prompts inaccessible. Added visible manual-copy recovery and bounded waiting for the clipboard API.
- A fresh `#pme`, `#he`, or `#k12` link did not persist its audience. Corrected URL state and added a regression test executing the shipped routing function.
- Preview links inside the workbench bundle could return to old production content. Rebase those links when building a preview.

## September 23 workbench correction

The prior review overstated the completeness of audience adaptation. Shared NWC validation labels, a universal-supervision claim, generic assessment prompts, and unchanged visible reference materials remained. These gaps are now corrected in the current source and published testing preview.

- Selecting a setting updates the heading, status, worked example, reference matrix, all nine tool descriptions, selected document, setup prompt, and context download.
- Each audience has a 14-section context bundle, nine standalone templates, a guide, and a matrix SVG. The shared bundle has 16 sections. Template copy, download, and bundle content are checked for parity.
- Assessment dimensions, provisional descriptors, and changed-case questions are specific to the professional, disciplinary, or high-school task. Support and unassigned responsibilities are recorded explicitly.
- Exported framework graphics no longer assert a universal supervision endpoint or NWC-only validation. Active repository instructions and roadmap use the broader audience scope; historical plans have supersession notices.
- A hosted returning-browser check exposed old cached JSON. Content-hashed data URLs now prevent reuse of stale workbench data; Markdown and JSON revalidate. The same browser passed after the correction.
- Original essay, claims, and source spine remain intact. Jev stays separate. These changes are authored teaching designs, not new evidence of learning.

## Checks performed

- Site build and existing contract suite pass.
- Expanded audience contract passes for three views and all 27 adapted templates: source/profile agreement, copied/downloaded/bundled content parity, linked assets, unique IDs, section counts, content cache key, and the actual client audience handler.
- Direct audience handoff regression passes for PME, HE, and high school.
- Portable lab context matches its 13 source files. Site builds reject a stale context. Earlier package checks confirmed changed and missing source rejection.
- Browser checks cover all 27 workbench selections; changing audience while retaining the selected document; reload and Back; hosted HE and high-school routes; desktop and 390px mobile layout; a horizontally scrollable matrix without page overflow. Prior direct audience-to-companion and keyboard navigation checks remain covered by the unchanged routing contracts.
- An intentional local 503 showed a visible workbench error; selecting a tool retried successfully. An intentional clipboard-denial policy exposed the prompt for manual copying with focus and status feedback.
- Original essay, claim map, and essay source spine match their pre-refresh source bytes. The essay PDF remains the essay, not a substitute classroom packet.
- Interface detector warnings concerned inherited Fraunces/cream styling and compact heading leading. Preserved the existing design identity; body text uses the established 1.5 line height.

## Preview verification

The Firebase preview deployment succeeded. All 88 published files match the checked build byte-for-byte; see [preview-asset-verification.json](preview-asset-verification.json). The canonical root URL was used for index verification. Production judgmentlab.net was separately checked and remains unchanged. Hosted browser checks confirmed the HE workbench loads for a returning visitor after the cache correction, and switching to the high-school assessment updates its questions and download. The Firebase CLI could not sync preview Auth domains; this static site has no authentication dependency, and the published assets are accessible.

## Evidence and release limits

Educator usability, assistant adherence over a complete authentic session, workload, learning, retention, and classroom transfer remain to be tested. High school is the supplied K–12 starting point; younger-grade adaptation is separate. The six-phase framework remains a hypothesis, and Jev remains a separate evaluation workstream.

Automatic approval review rejected production publication because it required explicit approval for the live judgmentlab.net target. The testing preview is the delivery surface; production must not be described as updated until that approval and deployment occur. The separate Firebase `judgment-in-practice` site is a different application and was not modified.

## Reproduce or release

Use the active companion, site, and workbench siblings under `/Users/jackcshaw-2/dev/comprendo-clients/`. The older `nwc/` copies are not this candidate. Rebuild the lab context first, then build the site with explicit companion/workbench paths. For the preview, set SITE_URL to its URL and run both test suites. For an approved production release, rebuild with the production origin, test again, and deploy only the pinned `nwc-learning-companion` hosting site. Verify live assets against the build. Firebase retains previous hosting releases for rollback.
