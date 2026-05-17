# The Adversarial Research Method: A Replicable Toolkit for Challenging Institutional Consensus

## Three Prompts, Three Worked Examples, and the Five-Paper Series They Produced

**Independent submission**
**Author:** yungmulaBABY (yungmulababy.substack.com)
**Repository:** github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research
**Full evidence bundle:** DOI 10.5281/zenodo.20201226
**Five final papers:** DOI 10.5281/zenodo.20209372

-----

## Abstract

This document describes a replicable method for identifying and documenting institutional research failures — cases where a field’s apparent consensus rests on weak proxies, circular citation networks, and a decisive test that was never run. The method uses three diagnostic prompts, adversarial AI collaboration, and a structured evidence-archiving protocol to produce publishable methodological challenges from domain expertise alone. It was developed through a five-paper body of work challenging the dominant academic literature on gender and elite esports performance. All prompts, worked examples, and resulting papers are publicly archived. The method is domain-agnostic. The bottleneck is domain knowledge, which practitioners already have.

-----

## I. Background: The Problem the Method Addresses

Academic literatures can develop apparent consensus not through converging independent evidence, but through the accumulation of citations to claims that were never directly tested. A small founding cluster of papers establishes a premise. A review paper or meta-analysis amplifies it. Downstream papers cite the review rather than inspecting the original evidence. Limitations disappear at each citation step. The conclusion grows stronger through repetition than the original methods supported. Adjacent literatures with directly relevant expertise remain structurally excluded from the citation network. The decisive test — the evidence that would actually resolve the question — is never specified or run.

This failure mode is not unique to any field. It is structural. The same four failure modes appear repeatedly:

1. **Untested premise recycled through citation** — a claim treated as established that has never been directly tested
1. **Proxy that measures the wrong thing** — a metric presented as evidence for a construct it cannot actually measure
1. **Level-of-analysis error** — findings from one population or setting exported to explain outcomes in a different population or setting
1. **Ratchet** — an intervention that expands when the metric improves, without verifying that the underlying construct has changed

The challenge is that correcting these failures normally requires institutional affiliation, journal access, co-authors, funding, and career incentives that most domain experts lack. The method described here removes those barriers.

-----

## A Note on Technical Infrastructure

You do not need GitHub, Zenodo, a university login, or any technical infrastructure to run this method. All you need is access to a free AI chat interface and domain knowledge. Grok (grok.com), Claude (claude.ai), and ChatGPT (chat.openai.com) all have free tiers that are sufficient for this work. The prompts in this document can be copied directly into any chat window.

GitHub and Zenodo are used in this project for public archiving — so that the evidence is permanently accessible and independently verifiable. That step matters for publication credibility but is not required to run the audit. You can produce a complete methodological challenge using nothing but a browser, a free AI account, and your domain knowledge. Archive publicly when you are ready to publish. Run the method first.

-----

## II. The Method

The method has five stages.

**Stage 1: Identify the anomaly.**
Domain expertise generates the initial suspicion. A practitioner, clinician, or experienced domain participant notices that a field’s published conclusions do not match observable reality. This suspicion — what the method calls “vibes” — is the valid starting point. It is not sufficient as final evidence.

**Stage 2: Run the construct validity audit.**
The foundational paper — the study that everyone cites as having settled the question — is subjected to a structured 14-section audit. The audit maps what the study actually measured versus what it claimed, documents the proxy problem, identifies omitted confounds, checks ecological validity, specifies the decisive test, tracks how later papers used the finding, and identifies ignored adjacent literatures. This audit produces a publishable claim-vs-measurement analysis.

**Stage 3: Run the citation network audit.**
The citation pathway from the foundational paper to its downstream amplification hub is mapped. The audit identifies founding cluster composition, claim mutation across citation steps, adjacent-field neglect, hub-dependency behavior, critique uptake (or non-uptake), and a cartel-risk score across ten dimensions. This audit produces a publishable citation network analysis.

**Stage 4: Run the field diagnostic.**
44 questions across all four failure modes are applied to the field as a whole. This audit identifies whether the field has a mechanism for self-correction, whether the ratchet is operating, whether the decisive test has been specified, and whether the intervention metric is improving while the underlying construct remains unmeasured.

**Stage 5: Run the adversarial loop.**
After the core argument is stable, the strongest counterarguments are generated by asking an AI model to make the best case that the audit is wrong. Those counterarguments are then brought back to a different model for evaluation: “Do you find these objections compelling, or is this compliance hedging?” What survives this loop is the publishable challenge.

**The rule:** You may begin with vibes. You may not end with vibes. Start wherever the anomaly appears. Finish with receipts.

-----

## III. The Three Prompts

All three prompts are publicly available in the GitHub repository. They are free, reusable, and domain-agnostic.

### Prompt 1: Construct Validity Audit

**File:** `construct_validity_claim_vs_measurement_audit_prompt.txt`
**Length:** 406 lines, 10.4KB
**Purpose:** Audits one paper. Maps claim vs. measurement. Identifies proxy failures, confounds, level-of-analysis errors, ignored literatures, and the decisive test.
**14 sections:**

1. Exact claim extraction (three levels: author claim, defensible claim, inflated downstream claim)
1. Measurement extraction (what was and was not measured)
1. Claim vs. measurement table with severity ratings
1. Level-of-analysis check
1. Confound audit
1. Ecological validity check
1. Decisive-test specification
1. Citation-use audit
1. Ignored-literature check
1. Source-status labels
1. Verdict (seven options from “valid evidence” to “fatal construct-validity failure”)
1. Paper-safe wording (four versions)
1. Failure-mode classification checklist
1. Final output summary

**Use first.** Run on the foundational paper — the one everyone cites as having settled the question.

-----

### Prompt 2: Citation Network Audit

**File:** `citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`
**Length:** 658 lines, 19.7KB
**Purpose:** Audits the citation network. Maps how the claim traveled, what was structurally excluded, and whether the consensus is produced by converging evidence or by citation accumulation.
**11 sections (80 questions):**

- A: Citation network structure and cartel detection
- B: Evidence type coding
- C: Citation polarity and claim use
- D: Claim mutation tracking
- E: Adjacent field engagement and neglect
- F: Hub dependency and review-paper laundering
- G: Pattern recognition and ratchet behavior
- H: Ignored critique and non-uptake
- I: Author, institution, journal, and funding clustering
- J: False-positive and baseline check
- K: Cartel-risk scorecard (10 dimensions, 0-30 scale)

**Required outputs:** 10 structured artifacts including citation spine table, founding cluster table, claim mutation table, adjacent-literature neglect table, critique-uptake table, cartel-risk scorecard, and network map instructions.

**Use second.** Run after the construct validity audit identifies the proxy failure.

-----

### Prompt 3: Field Diagnostic

**File:** `field_diagnostic_44_questions_prompt.txt`
**Length:** ~400 lines
**Purpose:** Full field-level diagnostic. 44 questions across all four failure modes. Identifies whether the field has the structural pattern at scale.
**Four sections:**

1. The untested premise
1. The proxy problem
1. The level-of-analysis error
1. The ratchet

**Use third.** Run to assess whether the whole field has the pattern, not just the foundational paper.

-----

## IV. Worked Examples

### Example 1: Construct Validity Audit — Shen et al. (2016)

**Paper audited:** Shen, C., Ratan, R., Cai, Y. D., & Leavitt, A. (2016). Do Men Advance Faster Than Women? Debunking the Gender Performance Gap in Two Massively Multiplayer Online Games. *Journal of Computer-Mediated Communication*, 21(4), 312–329.

**Why this paper:** Shen et al. (2016) is the most-cited empirical paper in the esports gender literature. It is cited as foundational proof that the gender performance gap in competitive gaming disappears when playtime is controlled. It has been cited 200+ times and is the load-bearing premise of the dominant academic narrative.

**Summary of findings:**

The study measured MMO character level advancement speed — the rate at which a character moved through level milestones per hour of login time in EverQuest II and Chevaliers’ Romance III. All max-level characters were deleted from the dataset to maintain a linear model.

The construct validity audit identified five fatal or major proxy failures:

|Measured variable                          |Claimed construct                             |Severity                |
|-------------------------------------------|----------------------------------------------|------------------------|
|MMO character advancement speed            |Individual mechanical gaming performance      |Fatal proxy failure     |
|EverQuest II / Chevaliers’ Romance III data|Competitive esports performance (FPS/MOBA/RTS)|Fatal proxy failure     |
|Non-max-level player sample                |High-level / elite performance                |Major construct mismatch|
|Login time as “play time”                  |Active productive gaming time                 |Moderate proxy gap      |
|Binary guild membership                    |Social assistance and group play              |Major construct mismatch|

The audit identified nine bodies of directly relevant literature that were not cited — including the MMO social dynamics literature documenting that female avatars systematically receive more help, carries, and gear transfers from other players (Yee 2006; Brehm 2013; Fortim & de Moura Grando 2013; Patrizio 2001) and the corresponding author’s own prior EverQuest II social architecture paper (Shen 2014). The psychomotor performance literature directly relevant to elite gaming (Voyer et al. 1995; Der & Deary 2006; Silverman 2006; Trick et al. 2005; Mathew et al. 2020) was entirely absent from the citation network.

**Verdict:** Fatal construct-validity failure for the strong downstream claim. Valid only for the narrow claim about non-competitive MMO leveling persistence under controlled login time. The decisive test — sex-stratified telemetry at matched rank and practice volume in competitive titles — was never run.

**→ Full worked example:** [`worked_example_shen_construct_validity.md`](worked_example_shen_construct_validity.md)
**→ Public Substack companion:** https://yungmulababy.substack.com/p/how-a-login-timestamp-became-proof

-----

### Example 2: Citation Network Audit — Shen → Rogstad Pathway

**Network audited:** The esports gender literature citation cluster, focusing on the Shen (2016) → Rogstad (2021/22) amplification pathway.

**Why this network:** Rogstad’s 2021/22 literature review is the most-cited review paper in the esports gender field. It synthesized the prior cluster into review authority, stating that “physical attributes are unrelated to high performance in eSports, allowing both men and women to compete in the same events (Shen et al., 2016; Paaßen et al., 2017).” This is a biological claim about elite competitive performance established on the basis of MMO leveling timestamps and a gamer stereotype study.

**Summary of findings:**

The claim mutation was tracked across four stages:

|Stage                     |Claim                                                                         |
|--------------------------|------------------------------------------------------------------------------|
|Original measurement      |Women’s characters advanced as fast as men’s per login hour in two MMOs       |
|Shen’s broader implication|The gender performance gap in gaming is confounded by playtime                |
|Downstream use            |Women do not perform worse at games generally                                 |
|Rogstad / field-level     |Cultural/gatekeeping explanations are sufficient to explain elite-tail absence|
|Public / policy           |Esports has no meaningful sex-linked performance substrate                    |

**Mutation severity:** Major — a narrow MMO progression finding became a biological claim about elite competitive performance.

**Adjacent-field neglect:** The MMO social dynamics literature (directly relevant to Shen’s proxy) and the psychomotor performance science literature (directly relevant to elite gaming claims) both show near-zero integration in the dominant citation network.

**Cartel-risk score:** 27/30 provisional (pending exact top-50 citation graph export from a formal database).

**Best formal label:** Citation-laundering network / premise-laundering hub. Likely functional citation cartel after exact edge verification.

**→ Full worked example:** [`shen_rogstad_esports_gender_lit_network_audit.txt`](shen_rogstad_esports_gender_lit_network_audit.txt)

-----

### Example 3: Field Diagnostic — Gender and Elite Esports Performance

**Field audited:** The academic literature on gender and elite esports performance, specifically the claim that the near-zero female representation at the Tier-1 open performance ceiling in FPS, MOBA, RTS, and fighting game genres is explained by culture, gatekeeping, and socialization.

**Summary of findings:**

All four failure modes are present and documented:

**Untested premise:** The cultural/socialization explanation for the elite-tail gap has never been directly tested against the competing hypothesis (psychomotor substrate + funnel selection) at matched rank and practice volume. The premise is treated as established because it has been repeatedly cited, not because it has been empirically adjudicated.

**Proxy problem:** The foundational empirical test used MMO leveling speed — a socially mediated progression metric that cannot distinguish individual mechanical skill from carries, boosts, AFK time, or social facilitation. Later papers cited this as evidence about competitive gaming performance generally.

**Level-of-analysis error:** Studies of casual and intermediate MMO players are used to explain the sustained Tier-1 open performance ceiling in adversarial competitive titles. The behavioral, psychological, and performance dynamics of a casual MMO player are not the dynamics of a sustained Tier-1 esports competitor.

**Ratchet:** The literature continues producing cultural-barrier papers, dedicated female circuits, and representation interventions. The intervention metric (female participation rates, dedicated circuits, representation figures) has improved in some contexts. The elite-tail outcome (sustained Tier-1 open performance in mixed open competition) has not converged. The decisive test that would resolve the question has never been run.

**→ Full diagnostic prompt:** [`field_diagnostic_44_questions_prompt.txt`](field_diagnostic_44_questions_prompt.txt)

-----

## V. The Resulting Papers

The method produced five papers that together constitute a complete methodological challenge to the dominant literature:

**Paper 1 — Biological Sex Differences and Elite Competitive Gaming Performance**
Builds the positive model. Small-to-moderate average sex differences in psychomotor traits (reaction time under cognitive load, three-dimensional mental rotation, dynamic visuomotor tracking, multiple-object tracking) combined with greater male variance and extreme-tail funnel selection compound multiplicatively. The model is falsifiable. The decisive test is specified. The field has not run it.
→ https://yungmulababy.substack.com/p/biological-sex-differences-and-elite-950

**Paper 2 — A Methodological Critique of Cultural Explanations for the Gender Performance Gap in Competitive Esports**
Documents the proxy failures, level-of-analysis errors, and citation laundering that produced the dominant narrative. The construct validity audit of Shen et al. (2016) is the central case study.
→ https://yungmulababy.substack.com/p/biological-sex-differences-and-elite

**Meta-paper — A Jobless High School Dropout Out-Researched an Academic Field in 11 Days on an iPhone**
Documents the process — which model did what, which prompts cracked the methodology open, how the adversarial loop worked. Full receipts, timestamped, archived.
→ https://yungmulababy.substack.com/p/a-jobless-high-school-dropout-out

**Paper 4 — The Pathologization of Excellence: From Social Science to League of Legends**
Demonstrates the same anti-merit mechanism operating inside live competitive game design. Bounty mechanics, catch-up XP, execution automation — the same failure mode in a different domain.
→ https://yungmulababy.substack.com/p/the-pathologization-of-excellence

**Paper 5 — What the Funnel Was For: The Measurable Human Toll of Dismantling Merit**
Asks the human question the first four papers implicitly raised: if these systems corrupt feedback and flatten developmental funnels, who pays? Documents the measurable outcomes in education, workforce, mental health, and credentialing.
→ [forthcoming on Substack]

**Full archive:** DOI 10.5281/zenodo.20209372 (five papers) | DOI 10.5281/zenodo.20201226 (full evidence bundle)

-----

## VI. The Adversarial Loop: Model Routing

The method uses three AI models with distinct roles:

**Grok** — initial diagnostic mapping, direct engagement with contested empirical claims, willingness to name failure modes without softening. Use for: running the diagnostic prompts, identifying proxy problems, characterizing the citation network. Grok will tell you directly when the answer is no.

**Claude** — long-form structure, synthesis across sources, cross-document consistency, argument architecture. Use for: organizing the argument, checking internal consistency, producing readable documents, systematic cross-referencing.

**ChatGPT** — adversarial stress-testing after the core argument is stable. Use for: generating the strongest objections to your challenge, identifying the weakest points, finding where evidence is thinnest. Do not use for initial diagnostic work.

**The loop:** After ChatGPT generates counterarguments, bring them back to Grok or Claude: “Do you find these objections compelling, or is this compliance hedging?” This step distinguishes genuine methodological weaknesses from institutional softening. What survives the loop is publishable.

-----

## VII. What This Method Is Not

This method is strongest when it challenges claims, measurements, citation networks, and institutional incentives. It is weakest when it accuses named individuals of bad faith, fraud, or misconduct without documentary evidence.

Not every weak proxy is laundering. Not every citation cluster is corrupt. Not every failed intervention is a ratchet. Some fields use imperfect measures because better data genuinely does not exist. The burden is to show that the field’s confidence exceeds what its evidence can support — and that the gap is large enough to matter.

The decisive question is not: “Is this field wrong?”

The decisive question is: “Has the field’s confidence exceeded what its evidence can support, and has it failed to run the test that would resolve the question?”

-----

## VIII. How to Run This in Your Own Field

1. **Identify the foundational paper** — the study everyone cites as having settled the question
1. **Fill in the construct validity audit input template** — abstract, methods, how later papers cite it, your domain-expert concern
1. **Paste into Grok** — for the most direct assessment
1. **Paste into Claude** — for structured synthesis and document production
1. **Identify the amplification hub** — the review paper that converted the weak finding into review authority
1. **Run the citation network audit** — map the claim mutation, the structural holes, the cartel-risk score
1. **Run the adversarial loop** — ChatGPT generates counterarguments; Grok evaluates them
1. **Archive everything** — public evidence bundle, source-status labels, correction log
1. **Specify the decisive test** — one sentence stating what evidence would settle the question
1. **Publish** — the method is the receipts

-----

*The method is replicable. The bottleneck was never infrastructure. It was domain knowledge — which practitioners, clinicians, and insiders already have.*

*You may begin with vibes. You may not end with vibes.*

*Start wherever the anomaly appears. Finish with receipts.*

-----

*Full series: https://yungmulababy.substack.com/p/start-here*
*Repository: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*
*Papers archive: DOI 10.5281/zenodo.20209372*
*Full evidence bundle: DOI 10.5281/zenodo.20201226*
