> Research notes for *Judgment at Work*, compiled October 27, 2026 by an AI-assisted source search. Each entry records where it was checked and whether it is verified or secondary only. Autor et al. (2026), Camuffo et al. (2026) and Romasanta, Thomas & Levina (2026) were re-checked independently the same day. Open the paper before quoting any figure in the essay. [The spine](../tasks/business-essay-spine.md) records which sources the argument uses.

# Judgment at Work: source notes (business evidence)

Compiled 2026-10-27. Every item lists where it was verified. Access notes: publisher pages often returned 403, so abstracts were taken from Crossref (publisher-deposited), arXiv, NBER, PubMed Central, RePEc, university repositories, or authors' own pages, as stated per item. HBR articles are paywalled and I did not read paywalled copies, so for HBR items only the public summary is verified. "Verified" means the figure or finding was read in the primary source (or the authors' own abstract/working paper). "Secondary only" means it was seen only in a summary by someone else.

Claims referenced below:
- C1: Companies certify judgment when they approve recommendations or promote people.
- C2: AI raised the bar for judgment and hid who clears it (AI-assisted analysis looks finished either way).
- C3: Managers must review for ownership (frame, reliance decisions, what would change the recommendation).
- C4: Managers must protect the work that builds judgment in junior staff.
- C5: When everyone uses the same AI for analysis, analysis stops being an advantage; judgment and AI fluency differentiate (hard to see, hard to copy).

---

## 0. Reconciliations

### 0.1 Brynjolfsson, Li & Raymond: 14% or 15%?
- **Published QJE version says 15%.** Brynjolfsson, E., Li, D., & Raymond, L. (2025). Generative AI at Work. *Quarterly Journal of Economics*, 140(2), 889–942. https://doi.org/10.1093/qje/qjae044
- Verified on: Crossref API record for DOI 10.1093/qje/qjae044 (publisher-deposited abstract; the OUP page did not render the abstract). Quote: "Access to AI assistance increases worker productivity, as measured by issues resolved per hour, by 15% on average, with substantial heterogeneity across workers." Published 2025-02-04.
- arXiv v2 (2024-11-06, https://arxiv.org/abs/2304.11771) also says 15%.
- **The 14% comes from the earlier working paper.** NBER w31161 page (https://www.nber.org/papers/w31161, revision dated November 2023) quotes: "Access to the tool increases productivity, as measured by issues resolved per hour, by 14% on average, including a 34% [improvement for novice and low-skilled workers]". arXiv v1 (April 2023) also carried the 14% figure.
- Note the agent count also changed: 5,179 (NBER WP) vs 5,172 (QJE).
- **Use 15% when citing the QJE paper.** Use 14% only if citing the 2023 working paper explicitly.
- Also in the QJE abstract (useful for C4/C2): "the most experienced and highest-skilled workers see small gains in speed and small declines in quality."

### 0.2 Dell'Acqua et al. 2023: "19 percentage points"?
- **Yes, the working paper PDF abstract says "19 percentage points".** HBS Working Paper 24-013 (September 22, 2023). The hbs.edu PDF returned an empty 202 to direct download; verified from the Wayback Machine capture of the same file (http://web.archive.org/web/20260306120415/https://www.hbs.edu/ris/Publication%20Files/24-013_d9b45b68-9e74-42d6-a1c6-c72fb70c7282.pdf).
- Abstract quote: "For a task selected to be outside the frontier, however, consultants using AI were 19 percentage points less likely to produce correct solutions compared to those without AI."
- Body (Section on outside-the-frontier task): "Subjects in the control group were correct about this exercise about 84.5% of the time, while the AI conditions scored at 60% and 70% (for an average decrease of 19 percentage points when combining the AI treatment conditions and comparing them to the control condition)." Regression: GPT + Overview −24 pp, GPT Only −13 pp.
- **Caution, wording differs by version.** The HBS faculty listing page (https://www.hbs.edu/faculty/Pages/item.aspx?num=64700), the SSRN abstract, and the published *Organization Science* 2026 abstract (see 0.3) all use a rewritten abstract that says "subjects using AI were 19% less likely to produce correct solutions". That phrasing is loose: the drop is 19 percentage points off an 84.5% base, about 23% in relative terms.
- **Use "19 percentage points" (84.5% vs. ~60–70% correct), citing the working paper for the numbers.** If quoting the published abstract verbatim, it says "19% less likely".
- Other abstract figures confirmed in the PDF: 758 consultants (~7% of individual-contributor consultants); 18 tasks inside frontier: 12.2% more tasks, 25.1% faster, "more than 40% higher quality"; below-average performers +43%, above-average +17%.

---

### 0.3 Publication-status updates on items marked "already verified"
- **Dell'Acqua et al. is now published:** *Organization Science* 37(2): 403–423 (March 2026), DOI 10.1287/orsc.2025.21838 (Crossref record). The published abstract says "**19% less likely**", not "percentage points". The SSRN abstract (DOI 10.2139/ssrn.4573321, via Crossref) also says "19% less likely". Only the September 2023 HBS working-paper PDF abstract says "19 percentage points". **Recommended wording:** "In the BCG experiment, consultants using GPT-4 on a task outside its frontier reached the correct answer about 60–70% of the time, against 84.5% without AI (a 19-point drop)." Cite the working paper for the numbers, or the Org Science version for the finding.
- **Emanuel, Harrington & Pallais is now published:** "The Power of Proximity to Coworkers," *QJE* 141(3): 1825–1870 (May 2026), DOI 10.1093/qje/qjag027 (Crossref). The published abstract gives "sitting near teammates increases coding feedback by 18.3%." If the essay quotes a figure from the 2023 NBER version (w31880), re-check it against the QJE version.
- **Same BCG paper, a detail worth adding (C2):** on the outside-frontier task, AI users' recommendations were graded higher quality *even when the answer was wrong*. WP p.14: "subjects using AI ... consistently outperformed those not using AI in terms of recommendation quality, regardless of the correctness of their answer"; GPT + Overview +1.47 points on a 1–10 scale (+25.1% over control mean), GPT Only +1.05 (+17.9%). This is the cleanest evidence for "an AI-assisted analysis looks finished either way." Verified in WP 24-013 (Wayback copy, see 0.2).

---

## 1. Convergence and competitive sameness (C5)

### 1.1 Meincke, Mollick & Terwiesch (2024), "Prompting Diverse Ideas: Increasing AI Idea Variance"
- arXiv 2402.01727 (Jan 27, 2024); SSRN 4708466. Verified on arXiv abstract and full PDF.
- Finding: "pools of ideas generated by GPT-4 with various plausible prompts are less diverse than ideas generated by groups of human subjects." PDF p.2: "Cosine similarity for ideas generated by groups of humans is around 0.243 compared to 0.255 - 0.432 for GPT-4 generated ideas." Chain-of-thought prompting got "a diversity nearly as high as groups of humans" (0.255) and raised estimated unique ideas "from around 3700 for the base prompt to 4700."
- Supports C5 (default AI output converges) and, through the CoT result, the fluency half of C5 (how you prompt changes how much you converge).
- Limits: one domain (consumer products for college students under $50); "human" comparison is a pool of student-generated ideas ("Group of Students" in the paper's table); diversity measured by embedding cosine similarity, not commercial distinctiveness; GPT-4 only. Describing these as "business ideas" is a stretch; "product ideas" is accurate.
- Status: verified.

### 1.2 Terwiesch, Meincke, Girotra, Mollick, Nave & Ulrich (2026), "Artificial intelligence and its impact on creativity and diversity: An empirical study of large language model-generated product ideas," *Production and Operations Management* (online July 22, 2026). DOI 10.1177/10591478261474243.
- Verified on Crossref publisher abstract. **This is the peer-reviewed successor to 1.1 and the better cite.**
- Findings (abstract): LLM ideas "have higher average quality than human ideas (based on purchase intent) and are 7 times more likely to rank in the top 10%"; "AI-generated ideas are less novel (at the idea level) and less diverse (at the set level)"; re-analysis of prior studies finds "consistently lower idea diversity across all of them"; newer models are more diverse but "still falling short of achieving human-level diversity"; diversity can be raised "almost to the level of human idea generation" by "pooling ideas across vendors, prompt engineering (including Chain-of-Thought prompting and injecting heterogeneous personas or constraints), and creative agents."
- Supports C5 (default convergence is robust across studies) and the fluency claim (skilled practice recovers diversity). **Also counter-evidence:** AI ideas are better on average, and the convergence can be engineered away cheaply.
- Limits: product ideation, not competitive analysis; purchase-intent ratings from online panels.
- Status: verified (abstract).

### 1.3 Anderson, Shah & Kreminski (2024), "Homogenization Effects of Large Language Models on Human Creative Ideation," Proc. ACM Creativity & Cognition (C&C '24). DOI 10.1145/3635636.3656204; arXiv 2402.01536.
- Verified on arXiv abstract.
- Finding: in "a 36-participant comparative user study ... different users tended to produce less semantically distinct ideas with ChatGPT than with an alternative CST. Additionally, ChatGPT users generated a greater number of more detailed ideas, but **felt less responsible for the ideas they generated**."
- Supports C5 (homogenization across users) and C3 (ownership erodes).
- Limits: n = 36; lab ideation task; comparison is another creativity-support tool, not unaided humans.
- Status: verified.

### 1.4 Kleinberg & Raghavan (2021), "Algorithmic monoculture and social welfare," *PNAS* 118(22): e2018340118.
- Verified on Crossref (PNAS significance statement) and arXiv 2101.05853.
- Finding: "even without any assumption of shocks or correlated failures—i.e., under 'normal operations'—the quality of decisions may decrease when multiple firms use the same algorithm. Thus, the introduction of a more accurate algorithm may decrease social welfare." Abstract: convergence on one algorithm "even when the algorithm is more accurate for any one agent in isolation, can reduce the overall quality of the decisions being made by the full collection of agents."
- Supports C5 (theory: shared tools reduce collective decision quality even when each tool is better).
- Limits: formal model of screening/ranking (hiring, lending); not empirical; welfare is system-level, not firm-level advantage.
- Status: verified.

### 1.5 Kim, Garg, Peng & Garg (2025), "Correlated Errors in Large Language Models," ICML 2025 (PMLR v267). arXiv 2506.07962.
- Verified on arXiv abstract.
- Finding: across "over 350 LLMs ... on one leaderboard dataset, models agree 60% of the time when both models err." "Crucially, however, larger and more accurate models have highly correlated errors, even with distinct architectures and providers." Downstream hiring task reflects "theoretical predictions regarding algorithmic monoculture."
- Supports C5 strongly: switching vendors does not buy independent judgment; frontier models fail together.
- Limits: benchmark questions and a resume-screening task, not strategy work.
- Status: verified.

### 1.6 Jiang et al. (2025), "Artificial Hivemind: The Open-Ended Homogeneity of Language Models (and Beyond)," NeurIPS 2025 Datasets & Benchmarks (Oral). arXiv 2510.22954 (v2 Oct 2026).
- Verified on arXiv abstract.
- Finding: on 26K real open-ended queries, "a pronounced Artificial Hivemind effect ... characterized by (1) intra-model repetition, where a single model consistently generates similar responses, and more so (2) inter-model homogeneity, where different models produce strikingly similar outputs." (The "70+ models" figure appears in search summaries; I did not see it in the abstract — treat as secondary only.)
- Supports C5: the sameness is cross-vendor, not just within one model.
- Limits: open-ended chat prompts (brainstorming, creative); not firm-level strategy.
- Status: verified (abstract); model count secondary only.

### 1.7 Romasanta, Thomas & Levina (2026), "Researchers Asked LLMs for Strategic Advice. They Got 'Trendslop' in Return," *HBR* digital article, March 16, 2026.
- Existence and authors verified on hbr.org (summary only, paywalled). Finding verified on co-author Levina's NYU Stern research-highlight page (author's own summary): "Across thousands of simulations, we saw LLMs almost uniformly select the same trendy strategies, regardless of context." "They consistently recommend strategies that align with modern managerial buzzwords and trends rather than context-specific strategic logic."
- Secondary only (University of Duisburg-Essen page and search summaries): seven LLMs tested on seven strategic tensions (exploration/exploitation, differentiation/commodification, automation/augmentation, etc.); models nearly always favoured differentiation and augmentation; richer context barely shifted answers.
- Supports C5 most directly of anything found: same advice across models and contexts in strategy.
- Limits: HBR practitioner article, no peer-reviewed paper located; methods not visible to me. **Irony to handle:** LLMs reflexively recommend "differentiation" and "augmentation" — the essay's own conclusion is what an LLM would say. The essay should earn it with evidence rather than assert it.
- Status: core finding verified (author summary); details secondary only.

### 1.8 Bottesch (2025), "Towards Generative Monoculture? Insights from a Field Experiment on Style and Content Homogenisation Effects in GenAI-Supported Knowledge Work," ACIS 2025 Proceedings (paper 290). https://aisel.aisnet.org/acis2025/290/
- Verified on AIS eLibrary abstract page.
- Finding: field experiment with 99 workers at an industrial corporation on "knowledge acquisition, knowledge packaging, and knowledge creation" tasks: "significant homogenisation effects occur in terms of style and content when knowledge workers are supported by GenAI"; "these effects might be mitigated through advanced prompting and (more) critical handling of GenAI output."
- Supports C5 (convergence in real corporate knowledge work) and the fluency claim.
- Limits: conference paper, single author, one firm, n = 99; effect sizes not in abstract.
- Status: verified (abstract).

### 1.9 Neshenko & Ryall (2026), "When Artificial Intelligence Does Strategy: Learning, Good Times, Lock-in, and Human-Driven Strategic Renewal," *Strategy Science* 11(1): 157–179. DOI 10.1287/stsc.2025.0448.
- Verified on Crossref publisher abstract.
- Finding (formal model): when firms delegate strategy to AI agents, "market dynamics converge to a self-confirming equilibrium ... even though objectively superior business models may remain unexplored," producing "strategic lock-in." "A single episode of human-driven frame expansion ... can disrupt the AI-induced equilibrium." "Our results clarify where humans still matter in AI-enabled strategy: deciding when to change the frame and not merely optimizing within it."
- Supports C5 and C3 (frame ownership) almost verbatim.
- Limits: theory, not data. Also notes managers "rationally refrain" from renewal when the equilibrium is lucrative, so convergence can be profitable.
- Status: verified.

### 1.10 Wingate, Burns & Barney (2025), "Why AI Will Not Provide Sustainable Competitive Advantage," *MIT Sloan Management Review*, May 8, 2025.
- Verified on sloanreview.mit.edu (via fetch) and University of Utah news page (affiliations: Barney, Utah; Wingate, BYU; Burns, Utah Valley). Note: some summaries wrongly call them "MIT Sloan scholars."
- Quotes: AI fails the sustainable-advantage test because it is "neither unique to any organization nor inimitable"; "artificial intelligence will be a source of homogenization"; "it may move the market as a whole but will not uniquely advantage anyone"; advantage comes from "residual heterogeneity—the ability of a company to go beyond what is accessible to everyone else and create something unique"; "Companies must cultivate creativity, drive, and passion."
- Supports C5 directly, from the author of the resource-based view (see 1.12).
- Limits: argument essay, not evidence. Emphasizes creativity and drive more than "judgment" per se.
- Status: verified (quotes via fetch of the article page).

### 1.11 Barney & Reeves (2024), "AI Won't Give You a New Sustainable Advantage," *HBR* Sept–Oct 2024.
- Existence, authors, issue verified on hbr.org (paywalled; visible text only). Visible line: "But relatively few of these and other technologies went on to become direct sources of sustained competitive advantage for the companies that deployed them."
- Secondary only: argument that AI amplifies an existing advantage but rarely creates one; "value is created but not captured."
- Supports C5. Limits: argument essay.
- Status: existence verified; argument secondary only.

### 1.12 Barney (1991), "Firm Resources and Sustained Competitive Advantage," *Journal of Management* 17(1): 99–120.
- Verified on Crossref publisher abstract.
- Quote: "Four empirical indicators of the potential of firm resources to generate sustained competitive advantage-value, rareness, imitability, and substitutability-are discussed."
- **Correction:** the framework has four tests, not three: valuable, rare, imperfectly imitable, *and non-substitutable* (VRIN). Add "and hard to substitute."
- Status: verified.

### 1.13 Agrawal, Gans & Goldfarb, *Prediction Machines* (HBR Press, 2018) / "The Simple Economics of Machine Intelligence" (HBR, Nov 2016).
- The book itself was not opened. The claim is verified in the authors' own text, reposted on Gans's blog Digitopoly (Nov 17, 2016): "As machine intelligence improves, the value of human prediction skills will decrease ... That's because the value of human judgment skills will increase. Using the language of economics, judgment is a complement to prediction and therefore when the cost of prediction falls demand for judgment rises."
- Caveat from their own theory paper, NBER w24243 (Jan 2018), verified on NBER page: "Prediction and judgment are complements as long as judgment is not too difficult," and in complex environments the effect "depend[s] a great deal on whether the improvements in prediction enable automated decision-making." Note that their "judgment" means determining payoffs (what outcomes are worth), which maps neatly onto "owning the frame."
- Supports C2 and C5.
- Status: verified (authors' own text); book page numbers not checked.

### 1.14 Camuffo, Gambardella, Kazemi & Pandey (2026), "Beyond Black Boxes: Designing and Testing Agentic AI Systems for Strategy," *Strategy Science* 11(1): 137–156. DOI 10.1287/stsc.2025.0432.
- Verified on Crossref publisher abstract.
- Finding: "In a randomized experiment with 976 managers comparing this agentic AI system, general AI (GPT-4o), and a human-only condition, we find that **experienced managers achieve quality improvements without confidence inflation, whereas highly educated managers exhibit confidence gains without corresponding quality improvements**." Framing: "purposeful AI system design and use—not mere access to generic models—can itself be a dynamic capability and a source of competitive advantage."
- Secondary only (Bocconi repository summary, which returned 403 to me): "both general and theory-based agentic AI assistance increase participants' confidence in their theories of value, but not their quality."
- Supports C2 (AI inflates confidence and hides who has the judgment), C3, C5 (design and use, not access, is the advantage). **Probably the single strongest new item for a manager audience.**
- Limits: managers trained in one strategy method (theory-based view); quality rated by experts and LLMs; one-shot task.
- Status: verified (published abstract).

---

## 2. Reliance and the human–AI combination (C2, C3)

### 2.1 Vaccaro, Almaatouq & Malone (2024), "When combinations of humans and AI are useful: A systematic review and meta-analysis," *Nature Human Behaviour* 8(12): 2293–2303. DOI 10.1038/s41562-024-02024-1.
- Verified on PubMed Central PMC11659167 (full text).
- Abstract: 106 experiments, 370 effect sizes (studies Jan 2020–Jun 2023). "on average, human–AI combinations performed significantly worse than the best of humans or AI alone (Hedges' g = −0.23; 95% confidence interval, −0.39 to −0.07)." "we found performance losses in tasks that involved making decisions and significantly greater gains in tasks that involved creating content." "when humans outperformed AI alone, we found performance gains in the combination, but when AI outperformed humans alone, we found losses."
- Body: decision tasks g = −0.27 (95% CI −0.44 to −0.10); creation tasks g = 0.19 (CI −0.09 to 0.48, not significant alone, but the difference is significant). **Human augmentation (human+AI vs humans alone) g = 0.64 (CI 0.53 to 0.74).** AI explanations and confidence displays "did not significantly affect" performance.
- Supports C3 (combination needs designed reliance; explanations alone don't fix it). **Also counter-evidence:** human+AI beats humans alone by a medium-to-large margin.
- Limits: mostly lab/online experiments, pre-GPT-4-era tasks; possible publication bias (authors' own caveat).
- Status: verified.

### 2.2 Lee, Sarkar, Tankelevitch, Drosos, Rintel, Banks & Wilson (2025), "The Impact of Generative AI on Critical Thinking: Self-Reported Reductions in Cognitive Effort and Confidence Effects From a Survey of Knowledge Workers," CHI '25. DOI 10.1145/3706598.3713778.
- Verified on PDF from co-author Sarkar's site (advait.org).
- Abstract: survey of "319 knowledge workers," "936 first-hand examples." "higher confidence in GenAI is associated with less critical thinking, while higher self-confidence is associated with more critical thinking." "GenAI shifts the nature of critical thinking toward information verification, response integration, and task stewardship."
- Supports C2/C3 (review shifts to verification and stewardship; reliance tracks trust in the tool).
- Limits: self-report, cross-sectional, correlational; Microsoft Research/CMU authors; "critical thinking" is perceived enactment, not measured skill.
- Status: verified.

### 2.3 Otis, Clarke, Delecourt, Holtz & Koning (2026), "The Uneven Impact of Generative Artificial Intelligence on Entrepreneurial Performance: Evidence from a Field Experiment in Kenya," *Management Science* (online July 10, 2026). DOI 10.1287/mnsc.2024.06909.
- Verified on Crossref publisher abstract.
- Published abstract: "we are unable to reject the null hypothesis of no average treatment effect on firm revenues and profits"; low baseline performers' effect "over 0.20-standard-deviations lower than for initial high performers"; "low performers did nearly 10% worse because of the AI assistant, whereas high performers may have benefited by over 15%." **"This differential impact does not appear to result from differences in the questions posed to the AI or the advice that it provided but rather, from the advice that entrepreneurs chose to implement."**
- **Changed from working paper:** the 2024 WP summary (via search) said low performers did "about 8% worse" because they "sought help on more challenging business tasks." The published version attributes the gap to *which advice they chose to act on*. Use the published version; it is better for the essay (it is a judgment-in-selection finding).
- Supports C3 and C5 (same AI, same advice, different outcomes depending on the judgment applied).
- Limits: 640 Kenyan small-business owners (n from search summary; not in abstract), WhatsApp GPT-4 mentor; subsample effects are imprecise ("may have benefited").
- Status: verified.

### 2.4 Logg, Minson & Moore (2019), "Algorithm appreciation: People prefer algorithmic to human judgment," *OBHDP* 151: 90–103. DOI 10.1016/j.obhdp.2018.12.005.
- Verified on RePEc/IDEAS abstract (publisher abstract).
- Finding: "lay people adhere more to advice when they think it comes from an algorithm than from a person." Appreciation "waned when: people chose between an algorithm's estimate and their own ... and they had expertise in forecasting." "Paradoxically, experienced professionals, who make forecasts on a regular basis, relied less on algorithmic advice than lay people did, which hurt their accuracy."
- Supports C3 (reliance is miscalibrated in both directions). Cuts against a pure "overreliance" story: experts under-relied, to their cost.
- Limits: pre-LLM; estimation and forecasting tasks; online samples plus one professional sample.
- Status: verified.

### 2.5 Agarwal, Moehring, Rajpurkar & Salz (2023), "Combining Human Expertise with Artificial Intelligence: Experimental Evidence from Radiology," NBER w31422.
- Verified on Crossref (SSRN-deposited abstract, DOI 10.2139/ssrn.4505053).
- Finding: "providing (i) AI predictions does not improve performance on average, whereas (ii) contextual information does. Radiologists do not realize the gains from AI assistance because of errors in belief updating – they underweight AI predictions and treat their own information and AI predictions as statistically independent." Optimal design "delegates cases either to humans or to AI, but rarely to AI assisted humans."
- Supports C3 (calibrating reliance is a distinct skill). Limits: radiology, not management.
- Status: verified.

### 2.6 Dell'Acqua (2022), "Falling Asleep at the Wheel: Human/AI Collaboration in a Field Experiment on HR Recruiters" (working paper).
- Verified on Harvard D^3 Institute page (author's institute), not the paper: 181 professional recruiters, 44 resumes each; AI tiers ~99% / ~85% / ~75% accurate or none; "recruiters who collaborated with the 'Bad' AI actually outperformed those with the 'Good' AI" because they stayed vigilant.
- Supports C2/C3 (better AI can make review worse). Limits: working paper; pre-LLM algorithm; summary only.
- Status: verified on author-institute summary; paper not opened.

---

## 3. Purpose, metrics and frame (C3)

### 3.1 Choi, Hecht & Tayler (2012), "Lost in Translation: The Effects of Incentive Compensation on Strategy Surrogation," *The Accounting Review* 87(4): 1135–1163. DOI 10.2308/accr-10273.
- Verified on Crossref publisher abstract.
- Quote: managers "act as though the measures are the construct of interest—a phenomenon we label surrogation." "incentive compensation exacerbates surrogation, and ... this effect is more prevalent when managers are compensated on a single measure ... than when ... compensated on multiple measures." Two experiments.
- Supports C3 (the frame gets replaced by the number). Limits: lab experiments with student/participant managers; pre-AI.
- Status: verified.

### 3.2 Harris & Tayler (2019), "Don't Let Metrics Undermine Your Business," *HBR* Sept–Oct 2019.
- Existence and summary verified on hbr.org: "Every day, at almost every company, strategy is being hijacked by numbers. Because strategy is abstract, employees often mentally replace it with the hard metrics meant to assess whether the ..." and "Strategy is abstract by definition, but metrics give strategy form."
- Secondary only (via an MIT SMR rebuttal and search summary): the Wells Fargo cross-selling example and the quote "The true source of Wells Fargo's problems was measurement."
- Note a published rebuttal exists: Schrage, "Don't Let Metrics Critics Undermine Your Business," MIT SMR (not verified beyond title).
- Status: summary verified; Wells Fargo detail secondary only.

### 3.3 Obermeyer, Powers, Vogeli & Mullainathan (2019), "Dissecting racial bias in an algorithm used to manage the health of populations," *Science* 366(6464): 447–453. DOI 10.1126/science.aax2342.
- Verified on Crossref (Science editor's summary).
- Quote: "Bias occurs because the algorithm uses health costs as a proxy for health needs." The bias "reduces the number of Black patients identified for extra care by more than half." "Reformulating the algorithm so that it no longer uses costs as a proxy for needs eliminates the racial bias."
- Supports C3: the best-documented case of a commercial algorithm optimizing a proxy instead of the purpose; the fix was reframing the target, not better modelling.
- Limits: healthcare, not general business; predictive model, not generative AI.
- Status: verified.

### 3.4 Thomas & Uminsky (2022), "Reliance on metrics is a fundamental challenge for AI," *Patterns* 3(5): 100476.
- Existence verified on Crossref; content not read. Status: existence only.

---

## 4. Accountability and decision rights (C1, C3)

### 4.1 Elish (2019), "Moral Crumple Zones: Cautionary Tales in Human-Robot Interaction," *Engaging Science, Technology, and Society* 5: 40–60. DOI 10.17351/ests2019.260.
- Verified on Crossref publisher abstract.
- Quote: "responsibility for an action may be misattributed to a human actor who had limited control over the behavior of an automated or autonomous system ... the moral crumple zone protects the integrity of the technological system, at the expense of the nearest human operator."
- Supports C1/C3 (sign-off without real control is the failure mode). Limits: conceptual, case-based (aviation, autonomous vehicles).
- Status: verified.

### 4.2 Rogers & Blenko (2006), "Who Has the D? How Clear Decision Roles Enhance Organizational Performance," *HBR* January 2006.
- Existence, authors, date verified on hbr.org (summary: "Decisions are the coin of the realm in business..."). RAPID roles (Recommend, Agree, Perform, Input, Decide) and the quote "In the end, it comes down to one person who must decide—the single point of accountability who commits the organization to action" verified on Bain & Company's republication (authors' firm) via a summarizing fetch.
- Bain's page also states "only about 15% of companies practice effective decision making" — I could not confirm this figure is from the 2006 article itself. Treat as secondary only.
- Supports C1 (someone owns the D; AI is at most an Input). Status: verified (framework and quote); 15% stat secondary only.

### 4.3 Köbis, Rahwan, Rilla, Supriyatno, Bersch, Ajaj, Bonnefon & Rahwan (2025), "Delegation to artificial intelligence can increase dishonest behaviour," *Nature* 646: 126–134. DOI 10.1038/s41586-025-09505-x.
- Verified on nature.com full text.
- Abstract: "Requests for cheating increased when principals could induce machine dishonesty without telling the machine precisely what to do, through supervised learning or high-level goal setting." "machines were far more likely than human agents to carry out fully unethical instructions."
- Body: honest reporting was 95% without delegation, "about 75% in the rule-based condition ... about 50% in the supervised learning condition ... and only about 15% in the goal-based condition." (Press reports of "12%" are secondary; use "about 15%".)
- Supports C1/C3: vague, goal-level delegation to AI lets people dodge ownership of the means. Limits: die-roll and tax-evasion games with online samples; ethics, not decision quality.
- Status: verified.

### 4.4 Gaczek, Leszczyński, Wei & Sun (2025), "The Bright Side of AI in Marketing Decisions: Collaboration with Algorithms Prevents Managers from Violating Ethical Norms," *Journal of Business Ethics* 204(4): 771–794. DOI 10.1007/s10551-025-06083-w.
- Verified on Crossref publisher abstract.
- Finding: three vignette experiments, 587 marketing managers. "working solely with AI recommendations may increase perceived personal responsibility ... In contrast, collaboration with human and AI teams tends to diffuse responsibility." "When AI highlights potential benefits, managers report lower personal responsibility and greater willingness to engage in unethical actions ... This effect is most potent among managers who heavily rely on AI."
- Mixed: supports diffusion in human+AI teams and heavy users; **challenges** the blanket claim that AI advice reduces responsibility.
- Limits: hypothetical vignettes. Status: verified.

### 4.5 Kirchkamp & Strobel (2019), "Sharing responsibility with a machine," *Journal of Behavioral and Experimental Economics* 80: 25–33. DOI 10.1016/j.socec.2019.02.010.
- Verified on RePEc abstract.
- Finding: "We find no treatment effect on perceived responsibility or guilt. We also find only a small and insignificant effect on actual choices."
- **Counter-evidence** to responsibility diffusion with machines. Limits: modified dictator game, pre-LLM.
- Status: verified.

---

## 5. Junior development and apprenticeship (C4)

### 5.1 Autor, Rodchenko, Martin, Iscenko, Strand, Pearl & Ferere (2026), "Does AI Assistance Enhance or Erode Expertise? Evidence from a Three-Month Field Experiment in Patent Drafting," NBER w35720 (Oct 7, 2026 version).
- Verified on full PDF from MIT Economics (economics.mit.edu).
- Abstract: "133 practicing patent lawyers at eleven U.S. intellectual property law firms" (91 completed the full protocol), blinded expert scoring. "AI access raised the quality of work delivered on benchmark patent drafting tasks at 10 days (0.34 SD, p = 0.03) and 90 days (0.38 SD, p = 0.01), with larger gains among junior lawyers. After three months, all subjects redlined an existing patent application without AI ... Treated lawyers outperformed controls by 0.32 SD (p = 0.04), but this advantage was concentrated entirely among senior lawyers (0.45 SD, p = 0.02). Junior lawyers showed no average gain. Their scores instead bifurcated, with sharply fewer mediocre scores offset by more poor and more good ones, suggesting that AI assistance served as a springboard for some juniors and a cushion for others. Foundational expertise may be a prerequisite for extracting durable skill from AI-assisted practice." Junior = under 7 years' experience.
- Intro: "Modern AI systems are easy to operate but hard to evaluate, so assessing their outputs demands the expert judgment that learning-by-doing instills."
- Supports C4 and C2 at once: AI lifted juniors' *delivered* work most while building their *own* judgment least. **The single strongest item for C4.**
- Limits: one profession; small sample after attrition; firms all work with Google (study conducted and funded by Google); custom tool.
- Status: verified.

### 5.2 Beane (2019), "Shadow Learning: Building Robotic Surgical Skill When Approved Means Fail," *Administrative Science Quarterly* 64(1): 87–123 (online 2018). DOI 10.1177/0001839217751692.
- Verified on Crossref publisher abstract.
- Finding: robotic surgery "greatly limited trainees' role in the work, making approved methods ineffective." Competence required "shadow learning" — "premature specialization," "abstract rehearsal," and "undersupervised struggle" — which "allowed only a minority of robotic surgical trainees to come to competence."
- Supports C4. Limits: surgery ethnography (two years, five sites) plus interviews at 13 hospitals; pre-generative AI.
- Status: verified.

### 5.3 Beane (2024), *The Skill Code: How to Save Human Ability in an Age of Intelligent Machines* (Harper Business).
- Existence verified (ASQ book review record, DOI 10.1177/00018392251344917). The "challenge, complexity, connection" framework is secondary only (publisher/press summaries).
- Status: existence verified; content secondary only.

### 5.4 Brynjolfsson, Chandar & Chen, "Canaries in the Coal Mine? Six Facts about the Recent Employment Effects of Artificial Intelligence," Stanford Digital Economy Lab working paper, **revised August 12, 2026** (first version August 2025).
- Verified on the Stanford Digital Economy Lab publication page (current abstract).
- Current abstract: ADP payroll data "through June 2026." "We find no evidence of widespread, economy-wide job displacement. However, employment of young workers (ages 22–25) in AI-exposed occupations now stands **19% below** where it would be had it kept pace with that of their less-exposed peers; experienced workers show no comparable gap. This divergence has widened steadily since we first documented it in August 2025. It operates primarily through reduced hiring of young workers." Declines concentrate where AI "primarily substitutes for human tasks." Authors call these "early, descriptive indicators ... rather than causal estimates."
- **Update:** the widely quoted "13%" is the August 2025 figure; the current version says 19%.
- Supports C4 (the apprenticeship pipeline is thinning at the entry rung). Limits: descriptive, not causal.
- Status: verified.

### 5.5 Bastani, Bastani, Sungu, Ge, Kabakcı & Mariman (2025), "Generative AI without guardrails can harm learning: Evidence from high school mathematics," *PNAS* 122(26): e2422633122.
- Verified on Crossref publisher abstract.
- Finding: GPT-4 access improved practice grades (48% GPT Base, 127% GPT Tutor), but "when access is subsequently taken away, students actually perform worse than those who never had access (17% reduction in grades for GPT Base)"; "largely mitigated by the safeguards in GPT Tutor." Students used it "as a 'crutch'."
- Supports C4 (protect the struggle; design matters). Limits: ~1,000 Turkish high-school students, not workers.
- Status: verified.

### 5.6 Kellogg, Lifshitz-Assaf, Randazzo, Mollick, Dell'Acqua, McFowland, Candelon & Lakhani (2024), "Don't Expect Juniors to Teach Senior Professionals to Use Generative AI: Emerging Technology Risks and Novice AI Risk Mitigation Tactics," SSRN 4857373 (HBS working paper).
- Existence verified (Crossref SSRN record). Content verified on Harvard D^3 page and MIT Sloan press release (authors' institutions): interviews with junior BCG consultants (1–2 years' experience) after the GPT-4 experiment; juniors proposed "novice AI risk mitigation tactics" focused on changing human routines rather than system design. The "78 interviews" figure is secondary only.
- Supports C4 (juniors aren't automatically the AI-fluent ones; seniors must build fluency themselves).
- Status: existence verified; findings verified on author-institution summaries.

### 5.7 Budzyń, Romańczyk et al. (2025), "Endoscopist deskilling risk after exposure to artificial intelligence in colonoscopy: a multicentre, observational study," *Lancet Gastroenterology & Hepatology* 10(10): 896–903. DOI 10.1016/S2468-1253(25)00133-5.
- Verified on University of Warwick repository (WRAP) record.
- Quote: "the ADR of standard colonoscopy decreased significantly from 28·4% (226 of 795) before to 22·4% (145 of 648) after exposure to AI, corresponding with an absolute difference of –6·0%."
- Supports C4 (deskilling of experienced professionals when the tool is removed). Limits: observational before/after at four Polish centres, 19 endoscopists; critical correspondence published in the same journal (Dec 2025).
- Status: verified.

---

## 6. Reviews and the premortem (C3)

### 6.1 Klein (2007), "Performing a Project Premortem," *HBR* September 2007.
- Existence verified on hbr.org; visible text: "In a premortem, team members assume that the project they are planning has just failed—as so many do—and then generate plausible..."
- The "30%" claim attributed to Klein (prospective hindsight "increases the ability to correctly identify reasons for future outcomes by 30%") is **secondary only** (widely quoted; not visible in the paywalled page).
- Status: existence verified.

### 6.2 Mitchell, Russo & Pennington (1989), "Back to the future: Temporal perspective in the explanation of events," *Journal of Behavioral Decision Making* 2(1): 25–38. DOI 10.1002/bdm.3960020103.
- Verified on Crossref publisher abstract.
- Abstract: "In the first experiment, **temporal perspective showed little influence while outcome uncertainty strongly affected the nature of explanations** for events. Explanations for sure events tended to be longer, to contain a higher proportion of episodic reasons, and to be expressed in past tense." The second experiment: "uncertainty mediates not the amount of time spent explaining, but rather subjects' choice of explanation type."
- **The paper says something different from the usual citation.** The abstract does not report a 30% improvement in *correctly* identifying reasons. What drove richer explanations was treating the outcome as certain, not imagining it in the future. For the essay: the active ingredient of a premortem is "assume it *has* failed" (certainty), which is the right point for reviewing an AI-assisted recommendation. Avoid "improves accuracy by 30%."
- Status: verified (abstract); 30% figure not supported by the abstract.

---

## 7. Stronger / newer studies on AI in managerial and strategic decisions

### 7.1 Kanis, Mann & Stumpf-Wollersheim (2026), "AI-Augmented Strategic Decision-Making Under Time Constraints: An Experimental Study on Mental Representations and Strategic Foresight," *Strategy Science* 11(1): 75–92. DOI 10.1287/stsc.2025.0442.
- Verified on Crossref publisher abstract.
- Finding: startup evaluation task, N = 348, 2×2 (time pressure × LLM). LLM use "significantly alter[s] the characteristics of mental representations," but neither factor "significantly change[s] strategic foresight." "LLM use increases information overload and **reduces psychological ownership**."
- Supports C3 (ownership) and C2 (different-looking work, same predictive quality). Limits: lab task; null on foresight could be power.
- Status: verified.

### 7.2 Sen, Workiewicz & Puranam (2026), "Can LLMs Aid Analogical Reasoning for Strategic Decisions? A Comparative Study," *Strategy Science* 11(1): 118–136. DOI 10.1287/stsc.2025.0426.
- Verified on Crossref abstract. "Humans ... frequently overlooked valid analogies (low recall) but rarely misapplied them (high precision); LLMs, in contrast, did not miss valid analogies (high recall) but often surfaced spurious, even if internally coherent matches (low precision)." Suggests LLMs retrieve, humans "adjudicate their contextual fit."
- Supports C3 (the human job is judging fit). Limits: exploratory study. Status: verified.

### 7.3 Csaszar, Lee, Zemsky & Zenger (2026), "Can AI Do Strategy?" *Strategy Science* 11(1): 1–15 (special-issue introduction). DOI 10.1287/stsc.2026.intro.v11.n1.
- Verified on Crossref abstract. "AI will not enter strategy where required reasoning is deepest but where its performance is most measurable." Frames what AI "should do given the imperatives of accountability and human judgment."
- Useful framing for C1/C2. Status: verified.

### 7.4 McBride (2026), "Mean Articulation Machines," *Strategy Science* 11(1): 31–54. DOI 10.1287/stsc.2025.0439.
- Verified on Crossref abstract. LLMs are "'mean articulation machines'" sensitive to training-data frequency; "novel scientific and strategic breakthroughs—are currently out of reach for LLMs because of inherent limitations in their architecture."
- Supports C5 (conceptual). Status: verified.

---

## 8. Counter-evidence (report as fully as the support)

### 8.1 AI improves average performance, including on judgment-like work
- **Vaccaro et al. 2024** (2.1): human+AI beats humans alone, g = 0.64.
- **Noy & Zhang (2023)**, "Experimental evidence on the productivity effects of generative artificial intelligence," *Science* 381(6654): 187–192. DOI 10.1126/science.adh2586. Verified on Crossref abstract: 453 college-educated professionals; "The average time taken decreased by 40% and output quality rose by 18%. Inequality between workers decreased." Limits: short writing tasks, online.
- **Holzner, Maier & Feuerriegel (2025)**, "Generative AI and Creativity: A Systematic Literature Review and Meta-Analysis," arXiv 2505.17241 (preprint). Verified on arXiv abstract: 28 studies, 8,214 participants; humans with GenAI outperform those without (g = 0.27); no difference GenAI vs humans (g = −0.05); but GenAI reduces diversity of ideas (g = −0.86). (Diversity result *supports* C5.) Limits: preprint.
- **Terwiesch et al. 2026** (1.2): LLM product ideas higher average quality, 7x more likely in the top 10%.
- **Doshi, Bell, Mirzayev & Vanneste (2025)**, "Generative artificial intelligence and evaluating strategic decisions," *Strategic Management Journal* 46(3): 583–610. DOI 10.1002/smj.3677. Verified on Crossref abstract: single LLM evaluations are "often inconsistent and biased. However, when aggregating evaluations, AI rankings tend to resemble those of human experts." 60 business models per study. Challenges the idea that evaluation is uniquely human; supports the idea that *how* you use it (aggregation) matters.
- **Csaszar, Ketkar & Kim (2024)**, "Artificial Intelligence and Strategic Decision-Making: Evidence from Entrepreneurs and Investors," arXiv 2408.08811. Verified on arXiv abstract: "current Large Language Models (LLMs) can generate and evaluate strategies at a level comparable to entrepreneurs and investors." Limits: accelerator and startup-competition samples.
- **Allen & McDonald (2026)**, "How Well Can AI Do Strategy? Empirical Benchmarking Using Strategy Simulations," *Strategy Science* 11(1): 93–117. DOI 10.1287/stsc.2025.0444. Verified on Crossref abstract: on the Back Bay Battery simulation, reasoning models from late 2024–early 2025 "exceed even the average scores of historical MBA student cohorts." But "frontier models from mid-to-late 2025 (e.g., GPT-5, Claude Opus 4.5, Gemini 3) have declined, underperforming both earlier LLMs and MBA students," partly from "a systematic bias toward exploiting the core business at the expense of investing in future growth." Cuts both ways.

### 8.2 AI can increase, not reduce, diversity, and convergence is fixable
- **Ashkinaze, Mendelsohn, Qiwei, Budak & Gilbert (2025)**, "How AI Ideas Affect the Creativity, Diversity, and Evolution of Human Ideas: Evidence From a Large, Dynamic Experiment," ACM Collective Intelligence 2025; arXiv 2401.13481. Verified on arXiv abstract: 800+ participants, 40+ countries; "high AI exposure (but not low AI exposure) did not affect the creativity of individual ideas but did increase the average amount and rate of change of collective idea diversity. AI made ideas different, not better." Directly challenges the homogenization premise. Limits: AI ideas shown as examples, not used as a working tool.
- **Terwiesch et al. 2026** (1.2) and **Meincke et al. 2024** (1.1): pooling across vendors, CoT, personas restore near-human diversity. If firms can cheaply de-homogenize, "same AI → same analysis" is a default, not a law. (It also means the de-homogenizing practice is itself the fluency the essay values.)
- **Jahani, Manning, Zhang, TuYe, Alsobay, Nicolaides, Suri & Holtz (2026)**, "Prompt Adaptation as a Dynamic Complement in Generative AI Systems," *Information Systems Research* (online April 30, 2026). DOI 10.1287/isre.2025.2029. Verified on Crossref abstract: two experiments, 3,750 participants; in a bounded replication task "roughly half of the performance gain came from the model itself, and half came from users naturally adjusting their prompts"; in an open-ended creative task "nearly all of the improvement was attributable to the model alone." Automated prompt rewriting "substantially hurt performance in the replication task." Supports fluency mattering in precision work; challenges it in open-ended work. (Search summaries quoting 1,893 participants and 51%/49% describe an earlier arXiv version; use the ISR figures.)

### 8.3 Deskilling may be overstated or conditional
- **Contractor & Reyes (2026)**, "Experimental Evidence on the Learning Impact of Generative AI," arXiv 2607.08849 (v2 Oct 2026). Verified on arXiv abstract: proctored RCT with undergraduates; "AI access raises test scores, and a smaller gain persists a week later. Gains remain for students who use AI as a tutor ('augmentation') and fade for students who have AI write for them ('automation')."
- **Brosch, Langer, Lergetporer, Mueller, Pfeifer & Tschoepe (2026)**, "Task Expansion with Generative AI: Experimental Evidence on Middle-Skilled, Early-Career Workers," Stanford Digital Economy Lab working paper (PDF dated 07/10/2026). Verified on PDF: 673 final-year IT apprentices, 12 German vocational schools; "productivity increases by 26–31 percentage points on tasks beyond apprentices' formal training"; "These productivity gains do not come at the cost of reduced immediate task comprehension. Treatment effects are generally larger among apprentices with above-median AI literacy." (The last sentence supports the fluency claim.) Limit: *immediate* comprehension only.
- **Brynjolfsson, Li & Raymond 2025** (already verified): QJE abstract says AI "facilitates worker learning."
- **Autor et al. 2026** (5.1): seniors gained durable unassisted skill (+0.45 SD); some juniors were "springboarded."
- **Humlum & Vestergaard**, "Large Language Models, Small Labor Market Effects," NBER w33777 (May 2025, revised March 2026). Verified on NBER abstract: Danish admin data; "precise null effects on earnings and recorded hours ... ruling out effects larger than 2% two years after the launch of ChatGPT"; "employers absorb AI through task reorganization—including new tasks in content generation, AI oversight, and AI integration." (The "3% time savings" figure in search summaries is from an earlier version; not in the current abstract.)

### 8.4 Responsibility diffusion is not automatic
- **Kirchkamp & Strobel 2019** (4.5): no effect on perceived responsibility or guilt.
- **Gaczek et al. 2025** (4.4): AI-only recommendations *increased* managers' felt responsibility.

### 8.5 Item to avoid
- **Kim, Muhn & Nikolaev, "Financial Statement Analysis with Large Language Models,"** arXiv 2407.17866. Often cited as "GPT-4 beats analysts." The arXiv record now carries this note: "A co-author identified inconsistencies in the data and analyses while attempting to replicate past analyses from the working paper. Accordingly, we have temporarily withdrawn the working paper from circulation while we review the research findings." **Do not cite.**

---

## 9. Candidate-list check: what exists and what differs
- All candidates exist.
- **Meincke, Mollick & Terwiesch 2024:** exists; the domain is consumer *product* ideas, and CoT prompting nearly closes the gap. Superseded by Terwiesch et al. 2026 (POM).
- **Barney 1991:** four indicators (value, rareness, imitability, substitutability), not three.
- **Otis et al.:** now *Management Science* 2026; the published explanation for the gap is which advice entrepreneurs chose to implement, not harder questions; low performers "nearly 10% worse" (WP said ~8%).
- **Mitchell, Russo & Pennington 1989:** abstract does not support "30% better at correctly identifying reasons"; it finds outcome certainty, not temporal perspective, changes explanations. The 30% is Klein's gloss (secondary only).
- **Harris & Tayler 2019:** exists; Wells Fargo detail secondary only.
- **Rogers & Blenko 2006:** exists; Bain's "15% of companies" stat secondary only.
- **The Skill Code:** exists; framework secondary only.
- **Prediction Machines:** claim verified in authors' 2016 HBR text (blog repost); their theory paper adds a "not too difficult" condition.
- **Logg et al. 2019:** exists; note experts *under*-relied, hurting accuracy.
- **Vaccaro, Lee, Anderson, Kleinberg, Choi, Elish, Beane 2019, Klein 2007:** exist and say what was claimed.
