# From “Important Study” to Publication-Ready Challenge in One Session

## The IAT Audit as a Worked Demonstration of the Adversarial Research Method

*A process paper documenting how the adversarial research toolkit was applied to the Implicit Association Test literature.*
*Part of the five-paper series: https://yungmulababy.substack.com/p/start-here*
*Repository: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*

-----

## A Note on Step Sequence

The recommended sequence for the adversarial research method is:

1. Construct validity audit
1. Citation network audit
1. Initial thesis draft
1. ChatGPT stress test + Grok compliance hedging evaluation
1. **44-question field diagnostic** ← confirms field-wide pattern
1. **Oppositional counter-audit** ← tests whether audit survives opposition
1. Refine thesis
1. **Voice restoration** ← check final version for compliance softening

This session ran the steps in a different order: voice restoration was run before the oppositional counter-audit and the 44-question diagnostic was run after the counter-audit. Voice restoration was then run again on the final post-counter-audit paper. The method is flexible enough that the outputs remained strong regardless of sequence — but the recommended order above produces cleaner results because:

- The 44-question diagnostic is best run early to confirm the failure modes are field-wide before committing to the paper-level audit
- The oppositional counter-audit should run before voice restoration so the final version gets a clean compliance check after all substantive changes
- Running voice restoration last means it only needs to run once

The steps below are documented in the order they were actually run, with this note as the reference point for the recommended sequence.

-----

The session began with a single query: *“Greenwald 1998 IAT implicit association test.”*

The response was what you would get from any AI model, any search engine, or any introductory psychology textbook: a groundbreaking study, forty million test-takers, sixteen thousand citations, the empirical foundation of implicit bias training programs worldwide. Then: *“Wow, very important study!”*

The model elaborated. Methodological cleverness. Democratized research. Cultural impact. Questions about predictive validity remain “genuinely unresolved” — but the study is undeniably important.

That is Session A. That is how most people use AI on a contested empirical question. The consensus reproduces, consolidates, and deepens with each positive signal. By the fourth exchange you are getting action items that follow from the consensus rather than any engagement with the underlying evidence.

The session then ran the adversarial research method. What follows is a description of what each step did, what it found, and what changed.

-----

## Step 1: Construct Validity Audit

**Prompt used:** `construct_validity_claim_vs_measurement_audit_prompt.txt`
**Link:** https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/construct_validity_claim_vs_measurement_audit_prompt.txt

The construct validity prompt asks one question in fourteen structured sections: does this study measure the thing it claims to measure?

For the IAT, the answer required identifying a proxy chain with three inferential leaps, none of which are directly validated:

1. Reaction-time difference → association strength
1. Association strength → implicit attitude
1. Implicit attitude → discriminatory behavior in professional settings

The audit found test-retest reliability of r ≈ .34–.56 — well below the .80 psychometric threshold for individual classification decisions. Predictive validity for discriminatory behavior: r ≈ .097 for the race IAT in the most recent large meta-analysis. Incremental validity above explicit self-report: under five percent of unique variance.

The verdict: valid for a narrow group-level laboratory finding. Major proxy failure for individual diagnosis and policy deployment.

**What changed from the initial response:** The model went from “undeniably important, questions remain unresolved” to a structured 14-section audit identifying twelve distinct failure modes including fatal proxy failure, level-of-analysis error, ecological validity failure, premise laundering, and missing decisive test. The change was produced by the prompt structure, not by the user supplying the critique.

**Full audit:** [IAT_Construct_Validity_Audit.docx](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Construct_Validity_Audit.docx)

-----

## Step 2: Citation Network Audit

**Prompt used:** `citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`
**Link:** https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt

The citation network prompt asks how the claim traveled: did confidence accumulate because evidence accumulated, or because citations accumulated?

For the IAT, the audit found:

- The same three founding authors (Greenwald, Banaji, Nosek) appear as co-authors on the founding paper, the scoring standard, the primary validity meta-analysis, the main rebuttal to critics, AND Project Implicit — the institutional delivery vehicle that has administered forty million tests
- The claim mutated from “RT differences exist in lab undergrads” to “75% of Americans are unconsciously racist” to federal training mandates — each step stripped the prior step’s caveats
- Five major critiques (Blanton & Jaccard 2006-2009, Oswald et al. 2013, Schimmack 2019-2021, Meissner et al. 2019, publication bias analysis 2021) were cited then dismissed or ignored
- Adjacent fields with directly relevant expertise — psychometrics, personnel selection validity research, audit study literature, behavioral genetics — were structurally excluded

**Cartel-risk score: 28/30 — Functional citation cartel / structurally closed consensus**

**What changed:** The audit identified the structural conditions that prevented self-correction — not as motive claims but as documented patterns of authorship, institutional overlap, and critique non-uptake.

**Full audit:** [IAT_Conversation_Condensed.docx](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Conversation_Condensed.docx)

-----

## Step 3: Adversarial Review Loop

**Models used:** ChatGPT (stress test), Grok (compliance hedging evaluation), Claude (refinement)

The thesis from both audits was drafted in Claude, then taken through the adversarial loop.

**ChatGPT raised three objections:**

1. The paper was collapsing academic, public, and institutional claims too tightly — the founding authors did not uniformly endorse individual diagnostic use
1. “The decisive test has not been conducted” phrasing was too absolute
1. “Small effects at scale” is the field’s strongest remaining defense and needed direct engagement rather than dismissal

**Grok’s evaluation:** The first two objections were accepted as genuine improvements in precision. The third was assessed as the field’s strongest remaining move — but one that constitutes a claim-type switch from individual diagnosis to population-level risk factor, which is a concession not a defense. The citation-network framing was assessed as structural documentation, not conspiracy — should not be softened.

**Claude’s refinement:** Incorporated the legitimate objections, rejected the compliance hedging by name, and produced a revised thesis and 8-section paper. The prefatory note named which objections were accepted and which were rejected, and why.

**Key principle demonstrated:** ChatGPT’s compliance softening — which makes it frustrating for initial diagnostic work — makes it the best reviewer in the toolkit. It generates exactly the objections a journal reviewer would raise. Full context (both audits + thesis) is essential before the stress test; without it, ChatGPT raises objections the audits already answered.

-----

## Step 5: Voice Restoration (First Pass)

**Note:** In this session, voice restoration was run before the oppositional counter-audit. The recommended sequence runs voice restoration last. It was run again after the counter-audit — see Step 7 below.

**Prompt used:** `voice_restoration_anticipatory_compliance_audit_prompt.txt`
**Link:** https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/voice_restoration_anticipatory_compliance_audit_prompt.txt

First pass checked the initial audit paper for compliance softening before the counter-audit added new content.

-----

## Step 6: Oppositional Counter-Audit

**Prompt used:** `oppositional-counter-audit.txt`
**Link:** https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/oppositional-counter-audit.txt

This is the most important step and the one most often skipped. The prompt forces the question: what did the audit miss? What does the other side have? What evidence would change the conclusion?

For the IAT, the counter-audit found two significant things:

**Genuine supportive evidence requiring a concession:**
Payne, Vuletich & Lundberg’s (2017) “bias of crowds” model, confirmed by Charlesworth & Banaji (2024), shows that regional and population-level IAT averages are stable and covary with measurable disparities in policing, health, and education. This ecological signal is real. The audit acknowledged it.

**Decisive new falsifying evidence:**
Forscher et al. (2019) — a 492-study network meta-analysis of 87,418 participants — found that implicit measures can be changed but those changes do not mediate changes in explicit measures or behavior. This directly tests and fails the causal chain the training industry requires. Vuletich & Payne (2019) added precision: training effects dissolve not because individuals revert but because the social environment generating the IAT signal remains unchanged. Intervening on the individual measure does not change the environment.

**What changed:** The thesis was narrowed — the IAT was conceded to have genuine construct-relevant signal at the population level — and strengthened, because the training-to-behavior link now has decisive falsifying evidence rather than merely inferential critique. The closing verdict became more precise: valid as a population-level ecological indicator, not validated as an individual diagnostic or the empirical basis for behavioral intervention.

The counter-audit demonstrated the principle: a good audit becomes sharper after contact with the strongest opposing evidence. A weak audit becomes narrower. The IAT audit became both.

**Full paper:** [IAT_Oppositional_Counter_Audit.docx](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Oppositional_Counter_Audit.docx)

-----

## Step 7: 44-Question Field Diagnostic

**Note:** In this session, the 44-question diagnostic was run after the counter-audit. The recommended sequence runs it earlier — after the citation network audit and before drafting the thesis — to confirm the failure modes are field-wide before committing to the paper. Running it late still produces valid output; it just means some findings may have already been captured in the earlier audits.

**Prompt used:** `field_diagnostic_44_questions_prompt.txt`
**Link:** https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field_diagnostic_44_questions_prompt.txt

**Input:** Greenwald et al. (1998) as the foundational paper, the implicit bias training literature as the field, individual IAT scores predicting discriminatory behavior as the central contested claim.

The diagnostic confirmed all four failure modes operate at field level, not just in the foundational paper — the untested premise (implicit bias causes discrimination) has never been directly tested at the level of individual professional decisions; the proxy problem is structural and reproduced across downstream papers; the level-of-analysis error is embedded in the field’s standard methodology; the ratchet is documented in mandatory training mandates that expanded despite the Forscher et al. (2019) falsifying evidence.

**Full output:** [IAT_44_Question_Field_Diagnostic.docx](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_44_Question_Field_Diagnostic.docx)

-----

## Step 8: Voice Restoration (Second Pass — Final Version) (from “important study” to this)

*Greenwald, McGhee, and Schwartz (1998) introduced the Implicit Association Test as a computerized reaction-time task measuring latency differences between compatible and incompatible category pairings, interpreting those differences as evidence of differential associative strength between mental representations. The construct-validity problem is not with the laboratory RT effect, which is real and replicable, nor with the instrument’s demonstrated capacity to track population-level associative patterns that covary with measurable regional disparities in health, policing, and education outcomes. The problem is with the compounding proxy chain through which a group-level ecological signal was extended into claims about individual mental states: reaction-time difference as a proxy for association strength, association strength as a proxy for implicit attitude, and implicit attitude as a proxy for an individual’s discriminatory behavior in consequential professional settings. Each inferential step is empirically contested, the full chain has not been validated at the level of individual diagnosis, and the most rigorous independent evidence — a 492-study meta-analysis finding no mediation between implicit measure change and behavioral change — directly falsifies the training-to-behavior link the institutional deployment requires. Academic claims, public synthesis, and institutional uptake inflated a legitimate but narrow ecological instrument into an individual diagnostic and training tool — a process visible in Project Implicit’s individual feedback language, federal agency training programs, HR curricula, and introductory psychology textbooks — while a structurally self-referential citation network insulated this inflation from substantive engagement with personnel selection standards, audit-study methods, and psychometric validity criteria that would have constrained it. The decisive validation study has not been conducted; the strongest current evidence supports the IAT as a population-level ecological indicator, not as an individual diagnostic or the empirical basis for behavioral intervention.*

-----

## What the Method Produced

From a single query and a set of free reusable prompts, one session produced:

- A 14-section construct validity audit with claim-vs-measurement table, confound audit, ecological validity assessment, and decisive test specification
- A 10-section citation network audit with cartel-risk scorecard (28/30), claim mutation table, adjacent field neglect table, and critique uptake table
- An adversarial review loop across three models with named acceptance and rejection of specific objections
- An oppositional counter-audit that found decisive new falsifying evidence and forced a genuine concession
- A voice restoration check
- A refined 8-section publication-ready paper

The session started with “wow, important study.” It ended with a documented, archived, methodologically precise challenge that is harder to dismiss than the critique the field spent a decade avoiding.

-----

## Full Session Documents

|Document                                                    |Description                                                 |Link                                                                                                                                                                                                     |
|------------------------------------------------------------|------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|IAT_Construct_Validity_Audit___Voice_Restoration_Audit_.docx|**Final paper** — post counter-audit, post voice restoration|[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Construct_Validity_Audit___Voice_Restoration_Audit_.docx)|
|IAT_Construct_Validity_Audit.docx                           |Pre-counter-audit paper (post first voice restoration)      |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Construct_Validity_Audit.docx)                           |
|IAT_Oppositional_Counter_Audit.docx                         |Post counter-audit paper (pre second voice restoration)     |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Oppositional_Counter_Audit.docx)                         |
|IAT_Conversation_Condensed.docx                             |Full conversation transcript (condensed)                    |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/IAT_Conversation_Condensed.docx)                             |
|Construct validity prompt                                   |14-section audit prompt                                     |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/construct_validity_claim_vs_measurement_audit_prompt.txt)                                     |
|Citation network prompt                                     |10-section network audit prompt                             |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt)                         |
|Oppositional counter-audit prompt                           |Tests whether audit survives opposition                     |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/oppositional-counter-audit.txt)                                                               |
|Voice restoration prompt                                    |Anticipatory compliance check                               |[Link](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/voice_restoration_anticipatory_compliance_audit_prompt.txt)                                   |

-----

*You may begin with “wow, important study.”*
*You may not end there.*

*Start wherever the anomaly appears. Finish with receipts.*

*Full series: https://yungmulababy.substack.com/p/start-here*
*Archive: DOI 10.5281/zenodo.20209372*
