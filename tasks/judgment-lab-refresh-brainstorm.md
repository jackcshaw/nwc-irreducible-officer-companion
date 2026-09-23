# Judgment Lab refresh: working brainstorm

Date: 2026-09-22
Status: Direction agreed in conversation; proposed details remain open.
Companion document: [Objectives and update loop](prd-judgment-lab-refresh.md).

First drafting pass: [foundation brief](refresh-pass-01/foundation-brief.md), [comparison against the claim and source spines](refresh-pass-01/spine-comparison.md), and [PME / HE / high-school exercise sketches](refresh-pass-01/exercise-sketches.md). These make the direction reviewable; educator review and classroom testing are pending.

Current prototype: [interactive failure-mode lab](../labs/failure-mode-lab/README.md). Jack clarified that the workbench should be the primary experience: engage the essay, make a judgment, test a contribution, defend or revise, transfer, and save useful decisions. Earlier classroom sketches are possible transfer material. The print-first packet direction is superseded.

## What we are trying to build

Judgment Lab helps educators teach, practice, and assess human judgment in AI-enabled work. Its central question is:

> What must people learn to do themselves so they can use increasingly capable AI with understanding, judgment, and responsibility?

The refresh should make that question useful in professional military education, higher education, and K–12. Each view needs a recognizable educational problem, an appropriate starting point, a worked example, and something an educator can use. The work includes the argument, teaching materials, assistant context, and website together.

The Irreducible Officer remains the substantial PME application. A shorter shared argument should explain the common method and identify where each setting changes it. The shared argument is a new synthesis to develop and test; the essay is not evidence that the method has been validated across all three settings.

## Direction established in this conversation

- Judgment Lab becomes the umbrella, with distinct PME, higher education, and K–12 views.
- The differences extend to learning goals, examples, prerequisites, AI roles, assessment, and reusable materials.
- Learner readiness becomes explicit across all views. Age, degree level, or professional seniority does not establish readiness for a particular task.
- K–12 starts with a high-school pilot, then adapts downward to middle and elementary school. Jack confirmed this sequence on September 22.
- Educators need to practice the method themselves and compare judgments with colleagues.
- Jev belongs in a connected, separate workstream. The educational refresh can proceed without a Jev integration.
- Subsequent instructions authorized building and iterating the local work. Public release and external outreach remain separate from preparing a reviewable implementation.

Working assumptions: educators and education leaders are the primary visitors; student materials are reached through an educator's exercise. The high-school subject and specific exercise remain provisional. Each subsequent middle- or elementary-school adaptation must reconsider prerequisite knowledge, task complexity, teacher mediation, AI access, and evidence of learning, with educator review for that band.

## What carries over from the essay

Use [claims.md](../claims.md) for the existing argument. Keep adaptations traceable to it without silently expanding the essay's claims.

| Existing idea | Shared formulation to develop | Adaptation needed |
| --- | --- | --- |
| AI changes the performance standard | Education must consider both independent capability and capable AI-supported work. | Specify the actual learning or professional outcome; agent supervision is not a universal destination. |
| Finished products carry less evidence of ownership | A strong product alone may not establish what the learner understands or can do. | Identify additional evidence appropriate to the subject and task. |
| Purpose becomes visible through frame | Make consequential choices visible and progressively expand what learners can own. | A learner can reason meaningfully within a teacher-supplied frame. |
| Appropriate reliance is teachable | Practice accepting, checking, revising, redirecting, and refusing assistance. | Supply the knowledge, criteria, and checks needed to make those choices. |
| Developmental friction matters | Preserve effort that develops the intended capability. | Search, drafting, synthesis, and repetition may themselves be learning objectives. |
| Accountability remains human | Identify who authorizes the work and who is answerable for decisions. | Separate learner responsibility from educator and institutional responsibilities, especially for children. |
| Assessment should expose judgment and transfer | Observe explanation, revision, performance, and application under changed conditions. | Oral defense is one option; choose accessible, feasible evidence for the setting. |
| Faculty practice should compound | Save reviewed examples, teaching decisions, and revisions for reuse. | Make teacher/faculty learning visible alongside student learning. |

An editorial issue to address in the shared argument: distinguish AI proposing a purpose or frame from people authorizing it and accepting responsibility. Avoid making a durable educational argument depend on an absolute claim about what AI can never generate.

## Foundations: the missing developmental layer

The existing essay gives more detail on exercising and assessing judgment than on building the capacities that make judgment possible. The refresh should supply that layer without presenting all learning as a rigid staircase.

For each exercise, establish:

1. The subject knowledge and reasoning the activity assumes.
2. A short way to observe whether those foundations are present.
3. Modeling, examples, and guided practice when they are not.
4. The choices the learner can currently own.
5. Where AI helps, and where it would take over the learning objective.
6. The evidence that supports reducing assistance or changing the task.

Possible sequence: activate knowledge; model reasoning; practice with support; explain a decision; revise after challenge; apply it to a changed case. Revisit earlier steps when the task or domain changes. Learners can do demanding thinking with support; foundations are taught within meaningful work.

Separate two questions in every view: how fluent is the educator with AI, and how ready are the learners for this activity? A teacher may use an advanced workflow to prepare a lesson whose students never operate AI themselves.

## Three audience views

| View | Educator's immediate task | Proposed first exercise | Evidence and reusable output |
| --- | --- | --- | --- |
| PME | Adapt a strategic assignment to expose framing, reliance, and accountable judgment. | Use the existing cyber strategy transfer pattern with a synthetic or approved misframed assessment, followed by a changed-condition challenge. | Initial frame, consequential reliance choice, revised recommendation, faculty questioning, calibrated rubric. |
| Higher education | Adapt one disciplinary assignment so the intended learning remains observable. | A history source-analysis task: compare a plausible AI synthesis with the supplied primary-source packet, revise the interpretation, and handle new evidence. | Source-to-claim reasoning, revision explanation, transfer task, assignment sequence and annotated exemplar. |
| K–12 | Decide what students must practice and where teacher-guided AI contributes. | High school first; science is a candidate subject: evaluate a teacher-selected explanation against a supplied observation/data set after making an initial explanation. Include a no-account classroom version. | Student explanation, identified discrepancy, revision, a related independent problem, teacher lesson and observation notes. |

These are pilot candidates, not completed or validated exercises. Use clearly labeled synthetic examples where necessary; source real disciplinary materials and review their suitability before distribution.

For education leaders, offer a small pilot brief: learning purpose, participating educators, access conditions, preparation and review time, evidence to collect, and a decision after the pilot. Preserve a route for teacher/faculty teams to diagnose the same example, compare differences, and revise criteria.

## A concrete site experience

Proposed journey:

> Choose setting → choose a task → see a worked example and expected output → use the materials on paper or with an assistant → review → save a teaching improvement.

Each audience view should answer:

- What can I do here, and what will I leave with?
- What does this activity assume about my learners?
- What do I do, what do learners do, and what does AI do?
- What should I observe to judge whether it helped?
- What can my colleagues reuse?

Three starting tasks: practice an example, adapt an assignment/lesson, or plan an educator-team pilot. Introduce attachment, browsing, and copy-prompt mechanics when the visitor chooses to begin.

Provisional paths: `/pme`, `/higher-education`, `/k12`, plus a shared method/evidence page. Exercises and templates should have stable links. Keep existing essay and asset links working. Preserve the site's restrained editorial character; navigation and content are the main design problem.

Audience choice must survive beyond the page: prompts, source bundles, downloads, examples, and facilitator instructions must all use the right setting. Shared guidance should be maintained once and combined with explicit audience adaptations. Keep the PME essay, shared claims, research notes, exercises, and assessment tools distinguishable.

## Jev: connected experiments

Jev raises a relevant instructional question: who chooses the criteria, categories, thresholds, and permitted actions inside AI-supported software? That can become a teaching case even before an integration is useful.

First proposed technical experiment:

> Given a synthetic learning artifact and an educator-authored set of follow-up questions, suggest the most useful next question or return “needs educator review.”

Begin with an explicit task definition and educator judgments. Compare a simple rule or fixed sequence, an existing general-model approach where available, and Jev. Establish acceptable mistakes and review requirements before interpreting results. Examine disagreement, missing context, paraphrases, and inappropriate confidence. Human reviewers retain assessment and progression decisions.

Keep the experiment's three possible outcomes legitimate: adopt a bounded use, revise and retest, or park it. A useful result may be learning which decisions should remain with the educator. The site refresh must not depend on positive Jev results.

## Questions to resolve through the loop

- Which educators can review the initial HE and K–12 examples, and what settings can they actually test?
- What should the high-school pilot teach, and what changes will middle- and elementary-school adaptations require?
- Which disciplinary HE example is most relevant to a reachable pilot partner?
- What learning evidence is worth the educator's time, and what is merely retrospective paperwork?
- When does a fluent explanation conceal a misconception? What independent performance would expose it?
- What is the smallest helpful shared argument, and where should detailed evidence live?
- Does a reusable workflow preserve useful variation, or export an unnoticed frame across classrooms?
- What would make an educator decide to stop using the exercise or change its AI role?

## First useful milestone

A reviewable shared argument, one readiness-aware exercise per audience, and a simple audience-navigation prototype. Each exercise includes an educator guide, learner task, worked example, review criteria, transfer check, and reusable note. Label the materials as drafts until the specified reviews occur.

This milestone precedes a large template library, an embedded tutor, automated assessment, or institutional memory infrastructure. The [update loop](prd-judgment-lab-refresh.md) defines how to reach it and what evidence is needed to go further.

## Starting sources for the next cycle

- [The essay](../the-irreducible-officer.md), [claim map](../claims.md), and [source spine](../sources/source-spine.md): current PME argument and its evidence boundaries.
- [Learning workflows](../patterns/nwc-ai-enabled-learning-workflows.md), [transfer case](../cases/cyber-group-strategy-transfer-case.md), and [trace artifact](../artifacts/traceable-learning-artifact.md): existing practice to adapt.
- [EEF metacognition guidance](https://educationendowmentfoundation.org.uk/education-evidence/guidance-reports/metacognition) and [How People Learn](https://www.nationalacademies.org/read/9853/chapter/7): starting references for explicitly taught reasoning, prior knowledge, and support. Check specific claims and age/task applicability during C1–C2.
- [TEQSA assessment reform](https://www.teqsa.gov.au/sites/default/files/2023-09/assessment-reform-age-artificial-intelligence-discussion-paper.pdf): reference for contextualized, varied evidence of learning in HE; not a local policy requirement.
- [UNESCO teacher framework](https://www.unesco.org/en/articles/ai-competency-framework-teachers?hub=66370) and [student framework](https://www.unesco.org/en/articles/ai-competency-framework-students?hub=66973): separate educator and learner competency references to compare with the proposed readiness model.
- [TypeSafe's Jev introduction](https://typesafe.ai/blog/introducing-system-one-models-and-jev): provider description and stated evaluation limits, not independent evidence of suitability for education.
