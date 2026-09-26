# Test the essay in an interactive session

Begin with the full essay for your setting: [PME](../../the-irreducible-officer.md), [higher education](../../essays/he.md), or [high-school educators](../../essays/k12.md). All three are included in the portable context. The protocol maps original case anchors to the selected edition.


Bring **The Irreducible Officer** into your AI assistant and test one of its failure modes. Make a judgment, examine a constructed AI contribution, defend or revise your decision, then consider what the experience changes about your teaching.

This is the testing edition of the Judgment Lab refresh. It extends the existing workbench's guided-session approach. The assistant runs the conversation; you make the decisions. The refreshed site and downloads use the same sources. Educator and classroom testing remain pending.

## Start

1. Download or attach [the complete session context](../../artifacts/judgment-lab-interactive-context.md) to your assistant. It contains the essay, claim map, source notes, practice cases, and facilitation instructions.
2. Paste the prompt below, choosing your setting. If the assistant cannot read attachments, paste the context file into a fresh conversation first.

```text
Run the interactive failure-mode lab in the attached judgment-lab-interactive-context.md.
My setting is [PME / higher education / high school]. I am an educator.
Use labs/failure-mode-lab/facilitator.md as the session protocol.
Begin with the essay and help me choose one failure mode to test. Ask one question
at a time and wait for my response. Do not supply my judgment or reveal the
practice case's diagnosis before I respond. After the test, help me transfer the
method to my setting and save a short decision record.
```

The first session uses the essay as the shared practice object. High-school teachers practice with the essay themselves before deciding what students should encounter. No student AI account or reading of the officer essay is assumed.

## What you can test

| Failure mode | Decision you will practice |
| --- | --- |
| Frame capture | Which problem and success standard should govern the work? |
| Fluency substitution | What judgment does polished prose actually establish? |
| Premature synthesis | Which connections can you justify, and which remain open? |
| Uncalibrated reliance | Which contribution can you accept, check, revise, or refuse? |
| Invisible delegation | Which choices did a seemingly helpful request hand over? |
| Institutional monoculture | What assumptions remain shared beneath different answers? |
| Responsibility laundering | Who must authorize and defend the consequential decision? |

You can challenge the essay, ask for a hint, inspect the case notes, or pause. Help is recorded so a coached answer is not mistaken for independent evidence. The cases are constructed teaching examples, not measured model failures or tests that certify competence.

## What you leave with

A short record of your initial position, the contribution you accepted or changed, your response to a changed condition, and a proposed teaching adaptation. Unmade decisions stay open. The assistant's notes are provisional; educator review and evidence from actual use are separate steps.

For authors: [facilitation protocol](facilitator.md), [case bank](cases.md), [constructed walkthrough](walkthrough.md), and [review record](review.md). Rebuild the portable context with `python3 scripts/build_failure_mode_lab.py`; check it with `python3 scripts/build_failure_mode_lab.py --check`.
