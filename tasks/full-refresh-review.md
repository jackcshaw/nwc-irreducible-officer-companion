# Judgment Lab: full refresh testing guide and review

September 22, 2026. Release candidate: `2026-09-audience-testing`.

## Start tomorrow

Open the [testing preview](https://nwc-learning-companion--audience-refresh-zkiwg8wa.web.app). It expires September 29, 2026. This is the complete refreshed site, with the same audience source files used in its downloads.

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
| Workbench | All nine template introductions and relevant body assumptions adapted; audience guide and framework scope explicit. |
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

## Checks performed

- Site build and existing contract suite pass.
- New audience contract passes for three views, all nine templates, copied/downloaded content parity, source inclusion, linked assets, unique IDs, and manifest counts.
- Direct audience handoff regression passes for PME, HE, and high school.
- Portable lab context matches its 13 source files. Site builds reject a stale context. Earlier package checks confirmed changed and missing source rejection.
- Browser checks cover all three direct audience-to-companion handoffs, all nine workbench selections, a document reload and Back, keyboard tab navigation, HE and companion mobile layouts at 390px, and no horizontal overflow on checked mobile views.
- An intentional local 503 showed a visible workbench error; selecting a tool retried successfully. An intentional clipboard-denial policy exposed the prompt for manual copying with focus and status feedback.
- Original essay, claim map, and essay source spine match their pre-refresh source bytes. The essay PDF remains the essay, not a substitute classroom packet.
- Interface detector warnings concerned inherited Fraunces/cream styling and compact heading leading. Preserved the existing design identity; body text uses the established 1.5 line height.

## Preview verification

The Firebase preview deployment succeeded. All 49 published files match the checked build byte-for-byte; see [preview-asset-verification.json](preview-asset-verification.json). The canonical root URL was used for index verification. Production judgmentlab.net was separately checked and remains unchanged. Hosted browser checks confirmed the HE-to-companion prompt uses the preview context URL, the adaptation evidence is visible, and the high-school path opens correctly. The Firebase CLI could not sync preview Auth domains; this static site has no authentication dependency, and the published assets are accessible.

## Evidence and release limits

Educator usability, assistant adherence over a complete authentic session, workload, learning, retention, and classroom transfer remain to be tested. High school is the supplied K–12 starting point; younger-grade adaptation is separate. The six-phase framework remains a hypothesis, and Jev remains a separate evaluation workstream.

Automatic approval review rejected production publication because it required explicit approval for the live judgmentlab.net target. The testing preview is the delivery surface; production must not be described as updated until that approval and deployment occur. The separate Firebase `judgment-in-practice` site is a different application and was not modified.

## Reproduce or release

Use the active companion, site, and workbench siblings under `/Users/jackcshaw-2/dev/comprendo-clients/`. The older `nwc/` copies are not this candidate. Rebuild the lab context first, then build the site with explicit companion/workbench paths. For the preview, set SITE_URL to its URL and run both test suites. For an approved production release, rebuild with the production origin, test again, and deploy only the pinned `nwc-learning-companion` hosting site. Verify live assets against the build. Firebase retains previous hosting releases for rollback.
