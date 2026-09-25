# Frame-First Assignment Design

Use this when designing, choosing, or rating an assignment meant to build the judgment *The Irreducible Officer* describes: students who direct AI toward a purpose they own, rely on it selectively, and defend the result. It works for PME, HE, and high school. It is also the specification for a future workbench tool that generates candidate assignments and rates educator drafts.

The criteria came out of a September 2026 review of the HE and high-school essay examples. The first examples (a campus survey and two surface-temperature readings) were well built and still tested the wrong skill. Each had one right answer that a textbook rule could reach. The ratings at the end of this file show why, and what replaced them.

## The five tests

Rate every candidate assignment against all five. An assignment that fails test 1 or 2 is not a frame-first assignment, however polished the rest is.

### 1. The flaw is in the frame, not the facts

The flawed AI output should be competent on its own terms and wrong for the problem. Its numbers, dates, and summaries can be correct. What is wrong is the question it answered, the criterion it used, or whose interests it counted.

- **Ask:** could a student catch the flaw with a stock phrase such as "check for bias," "correlation isn't causation," "not a fair test," or "AI can be wrong"? If yes, the flaw is a template error, not a frame error.
- **Fails when:** the output contains an overclaim any careful reader would flag, or it is so obviously wrong that it is a strawman ("trees lower temperatures everywhere by 8°C").

### 2. The student owns a real framing choice

More than one coherent frame exists, and the student has to choose one and defend it. The educator can supply the topic and the materials. The consequential choice of standard, criterion, or question stays with the student.

- **Ask:** could two strong students reasonably frame this differently and both earn full credit?
- **Fails when:** the educator has already made every framing decision and the student only executes or corrects.

### 3. Directing AI actually helps

Somewhere in the sequence the student directs AI toward their own purpose and gets something useful back: a missed assumption, a perspective they had not considered, a sorted evidence base, an argument against their frame.

- **Ask:** would a student who directs AI well produce better work than one who refuses it?
- **Fails when:** the only AI activity is inspecting output someone else generated. That teaches critique, not direction.

### 4. Something deserves acceptance

At least one AI contribution should be worth accepting after a reasonable check. Students should practice warranted reliance, not only rejection.

- **Ask:** what would a student be right to accept, and what check justifies accepting it?
- **Fails when:** every AI contribution is a trap. Students learn that the exercise pattern is "find the flaw," and success measures recognition of the pattern.

### 5. The changed case tests whether the frame travels

The changed case should alter which evidence or criterion matters most, so the student has to re-apply their framing discipline. Fixing one error in a new setting is not enough.

- **Ask:** does the changed case make a different frame, or a different piece of evidence, decisive?
- **Fails when:** the changed case only removes the original error (a random sample instead of a self-selected one).

## Foundations inside the loop

Subject knowledge matters. Students cannot direct AI toward a purpose in a domain they do not understand yet. That knowledge belongs inside the sequence, not as a gate in front of it. The original five-step pilot carries it:

1. **Frame unaided.** The student names the question, the standard, the key assumptions, and the evidence needed. This is also the readiness check. If a student cannot frame at all, teach the concept here.
2. **Direct AI against the frame.** The student asks AI to find missed assumptions, argue other perspectives, or sort evidence, and records what they kept and why.
3. **Meet a misframed AI answer.** The answer is competent and answers a different question than the one that matters.
4. **Diagnose and revise.** The student names the hidden frame, what it suppressed, and where it fails, then revises their own recommendation.
5. **Defend.** The student explains their reliance decisions and what would change their answer, then meets the changed case.

## Directing AI well, by level

Section V of the original essay describes a progression of where human judgment enters an AI workflow. Use it to set a level-appropriate target instead of a universal one.

| Level | What the student does | Typical fit |
| --- | --- | --- |
| Minimal prompting | Asks a bare question and inherits the model's frame | The failure to move students past |
| Structured prompting | States the purpose, the criteria, and what a good answer must include | High school; introductory HE |
| Evaluator loops | Has AI argue assigned perspectives or critique a draft, then weighs the disagreement | High school with teacher support; most HE |
| Reusable workflows and multiple agents | Assigns agents distinct roles, moderates disagreement, and synthesizes | Advanced HE; PME |

Where students cannot hold individual AI accounts, the student can still direct: they write the task, the criteria, and the check, and the teacher runs it on a shared screen.

## Grading a defended frame

Frame-first assignments often have no single correct answer, so the rubric grades the defense, not the conclusion. Give credit when the student:

- states the standard they used and why it fits the question's purpose;
- names at least one coherent alternative frame and why they did not adopt it;
- uses evidence that actually bears on their chosen standard;
- identifies an AI contribution they accepted and the check that justified it;
- explains what evidence or changed condition would change their answer.

Do not award credit for suspicion alone, for balance alone ("there are many perspectives"), or for changing one's mind as an end in itself.

## Calibration set

These ratings are the anchor examples for the future rater. Strong means the test is clearly met; weak means partly met; fails means not met.

| Example | 1 Frame flaw | 2 Student choice | 3 Directing helps | 4 Worth accepting | 5 Frame travels | Verdict |
| --- | --- | --- | --- | --- | --- | --- |
| Campus shuttle survey: AI treats 80 of 100 respondents as 80% of students | Fails: nonresponse is a textbook error | Fails: the question is supplied | Fails: inspect-only | Strong: the arithmetic | Fails: random sample only removes the error | Replaced |
| Asphalt vs. shaded grass: AI says trees cool everything by 8°C | Fails: confound, and close to a strawman | Fails | Fails | Strong: the subtraction | Fails: matched tiles only remove the confound | Replaced |
| Bus-stop shade: AI answers "how much cooler?" when the question is who is exposed and for how long | Weak: near the fair-test template | Weak | Weak | Strong | Weak | Possible lower-grade science case; needs its own design and review |
| Return-to-office research memo (HE) | Strong: "productivity" silently means short-run individual output | Strong: purpose depends on the firm's workforce | Strong: sorting studies by design, arguing firm and new-hire sides | Strong: accurate study summaries, checked against abstracts | Strong: an experienced call-center workforce makes different evidence decisive | Adopted for HE |
| "Was the New Deal a success?" (high school) | Strong: a balanced essay quietly judges success by economic recovery | Strong: success by what standard, for whom | Strong: assigned historical perspectives, weighed against primary sources | Strong: dates, figures, and program facts, checked against the packet | Strong: the same standard-setting move on a current local policy | Adopted for high school |
| PME misframed strategic assessment (original essay, Step 3) | Strong: internally coherent, grounded in the wrong understanding of the situation | Strong | Strong: Step 2 AI challenge | Varies by case | Strong | Reference design |

## Notes for an assignment generator

A generator should ask for the subject, level, learning objective, and the source materials the educator will actually use before proposing anything. It should return:

- the question and at least two coherent frames a student could defend;
- a misframed AI answer that is factually sound and passes test 1;
- one AI contribution worth accepting and the check that justifies it;
- a level-appropriate directing task from the table above;
- a changed case that passes test 5;
- a defended-frame rubric following the section above.

It should rate its own output against the five tests and show the ratings, and it should never invent facts, sources, or student responses. Any factual claim in a generated case needs checking against the educator's materials before use.
