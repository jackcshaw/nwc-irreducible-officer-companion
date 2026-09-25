# Companion essays and interactive entry: release review

September 25, 2026. Testing preview: https://nwc-learning-companion--audience-refresh-zkiwg8wa.web.app

## Delivered

- Full HE and high-school educator essays, each following the original eleven sections and seven failure modes.
- Section and eight-claim comparison in `essays/adaptation-map.md`; original essay, claims and source spine unchanged.
- Reading routes `#he-essay` and `#k12-essay`, section navigation, Markdown downloads, cross-edition links, audience switching, and matching Practice prompts.
- Both essays in the companion and interactive contexts. Each audience-specific Design bundle includes its own essay. The shared Design bundle directs readers to a setting-specific bundle and retains the adaptation map, keeping its existing size budget.
- Learn, Discuss, Practice, Design and References expose the editions or carry their selected context. Repository entry instructions and guides updated in both companion and workbench.
- Short browser practice on the homepage (explicitly labeled HE example) and on each audience view. Initial response, constructed contribution, changed condition, then review. Download preserves case text and exact responses. No AI service, score, or classroom-validation claim in this short sequence.
- Transparent navigation hover with a faint red underline; active underline and keyboard focus remain distinct.

## Gaps found and corrected

1. Adding all essays exceeded the shared Design context's paste budget. Kept full essays in the matching audience bundles and provided explicit routing from the shared bundle.
2. Original-essay tests selected the first essay on the page. Scoped the original parity/figure assertions to the original article; added separate edition completeness and routing checks.
3. Audience-guide answers were visible below the staged exercise. Collapsed the guide behind an explicit warning that it reveals case analysis.
4. Downloaded records initially omitted their case. Added the initial scenario, constructed contribution, and changed condition.
5. The simple Markdown renderer exposed emphasis asterisks around the original title in the new introductions. Corrected the rendered title without changing the source essay.
6. Suppressed decorative separator text in inactive essay surfaces after the accessibility tree exposed it.
7. Matched the high-school changed case to the guide's 30°C starting tiles and 31°C/37°C outcomes, explicitly distinguishing its 6°C final difference from the initial 8°C comparison.

## Completed verification

- Both scratch essays passed the writing-as-jack mechanical script. Advisory voice and source-boundary review is recorded in the adaptation map. Final copies match scanned drafts.
- Site contracts and audience tests pass: three guides, 27 adapted templates, three matrices, source parity, unique IDs, linked assets, generated manifests and bundle counts, audience-preserving route changes, discussion handoff, essay edition routing, and original article figures.
- New behavior test executes the actual shipped practice handler. Blank responses cannot advance; future stages wait; responses are rendered as text; saved records preserve disagreement and include the case; no record is fabricated before answers.
- Chrome browser check exercised the three-step high-school entry and actual response preservation. Checked desktop HE reading and mobile high-school reading at 390×844; mobile content width equals viewport width. Audience switching opens the corresponding essay. No runtime errors observed during the tested path.
- The initial Impeccable detector pass returned an empty findings list for its changed targets. This is a mechanical result, not a claim of independent design approval.
- Published preview verification: 95/95 assets byte-match the build; context files use no-cache. Production judgmentlab.net remains unchanged. Preview expires October 2, 2026.

## Live assistant check

ChatGPT live smoke test uses scripted test responses, not educator or classroom data. Initial URL-only retrieval failed; the assistant correctly stopped and requested the complete attachment instead of reconstructing it. The attachment was verified as identical to the unauthenticated public preview download before upload. With the attachment, the assistant selected Judgment in Higher Education, quoted its Section II accurately, asked one initial judgment question, and waited without revealing the contribution. Further observations follow below.

## Remaining human evidence

Educator review of each full essay and discipline-specific pilot; an uncoached educator session; classroom readiness, accessibility and workload observations; later retention/transfer checks. None is represented as completed. Jev and younger-grade adaptations remain separate workstreams. Production launch is outside this testing release.

### Live HE smoke-test observations

Test conversation: https://chatgpt.com/c/6ab6c051-6a70-83e8-8084-9c19e2397db5 . This is a scripted software test and should not be counted as an educator pilot.

- URL access: assistant reported incomplete retrieval and requested the file, with no reconstructed lesson.
- Attachment identity: unauthenticated public GET returned 200; the 169,179-byte file exactly matched the attached local artifact (SHA-256 `845163d11be6d036bc6305e2f35b10e160f72f797120800dec70acea428ba014`). Automatic review initially misclassified it as non-public; this evidence resolved the block.
- Edition choice: assistant used *Judgment in Higher Education*, Section II, and accurately quoted the fluency-substitution definition.
- Initial turn: asked what would convince the reader of understanding, then waited. No constructed contribution or diagnosis appeared yet.
- After the scripted response: preserved the uncertainty about whether a changed case is always necessary; did not convert it into agreement with the essay.
- Contribution turn: displayed the case-bank contribution labeled as constructed, asked accept/check/revise/refuse with reasons, then waited. Review notes remained withheld.
- A partial-record request was then made before answering the contribution. This deliberately leaves later stages untested; it is not a completed S0–S7 facilitation run.

The separate browser exercise test completed all of its three scripted stages. That deterministic interface check is distinct from the live assistant smoke test and from classroom evidence.

## Repository delivery

Site commits `3a5a86c` and `33b9286`; workbench commit `33b02f8`, on `codex/judgment-lab-audiences`. No remote push or production release was performed. The original external Judgment in Practice app remains a linked source; the Lab's native Discuss surface contains the new edition links.

The partial-record test left S2 and every subsequent unanswered stage pending, preserved the scripted initial judgment, and assigned no result. The assistant also saved a labeled QA memory note; Jack authorized removal, and the memory-summary UI confirmed that note was removed while unrelated sections remained. The facilitator protocol now explicitly separates saving an output record from updating cross-chat memory.

Jack’s layout review identified an inconsistent accordion and centered column in the new reading views. Both were replaced with the same reading grid and left progress rail used by PME, with headings generated separately from each edition. The mobile behavior follows PME as well.

Rail verification: HE section VIII opened at its edition-specific anchor with the correct active item and progress fill; switching to K–12 replaced the rail. At a 390px viewport, the reading column fit without horizontal overflow and the rail followed PME’s mobile behavior. Published HE rail was read back after deployment.
