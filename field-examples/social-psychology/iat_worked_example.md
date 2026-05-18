# Worked Example: Full Research Session

## IAT Implicit Bias Research — Construct Validity Audit, Citation Network Audit, Adversarial Review, Oppositional Counter-Audit, Voice Restoration, 44-Question Field Diagnostic, and Final Paper

*This document is a complete worked example of the adversarial research method applied to the Implicit Association Test literature. It covers all steps including the oppositional counter-audit — the prompt designed to test whether the original audit survives contact with the strongest opposing evidence — plus voice restoration audits and the 44-question field diagnostic.*

*Prompts used:*

- `construct_validity_claim_vs_measurement_audit_prompt.txt`
- `citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`
- `oppositional-counter-audit.txt` (tests whether audit survives opposition)
- `voice_restoration_anticipatory_compliance_audit_prompt.txt` (run twice)
- `field_diagnostic_44_questions.txt`

*Models used: Claude (audit, synthesis, final paper), ChatGPT (stress test), Grok (compliance hedging evaluation)*
*Full series: https://yungmulababy.substack.com/p/start-here*

-----

## Downloadable Outputs

These Word documents show the paper at each stage — how each audit changed the argument.

|Document                                                     |What It Shows                                                                                        |
|-------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
|`IAT Construct Validity Audit.docx`                          |The construct-validity audit output + how the thesis changed from it                                 |
|`IAT Oppositional Counter Audit.docx`                        |The thesis after the oppositional counter-audit — what narrowed, what strengthened                   |
|`IAT Construct Validity Audit + Voice Restoration Audit.docx`|Final version after construct-validity audit and voice-restoration pass                              |
|`IAT Conversation Condensed.docx`                            |Complete Claude conversation of all audit steps (condensed — paper bodies replaced with placeholders)|
|`IAT Thesis and Paper Final.docx`                            |The final paper after all audits, counter-audit, and both voice-restoration passes                   |

-----

## The Paper

**Greenwald, A.G., McGhee, D.E., & Schwartz, J.L.K. (1998). Measuring individual differences in implicit cognition: The implicit association test. *Journal of Personality and Social Psychology*, 74(6), 1464–1480.**

**Citations:** ~22,000 as of 2025
**Why this paper:** The foundational paper behind mandatory implicit bias training at thousands of corporations, federal agencies, and institutions. More than 40 million IATs completed at Project Implicit. Load-bearing empirical foundation of a training industry estimated in the hundreds of millions of dollars annually.

-----

## Step 1: Initial Query and Consolidation

**Prompt:** Greenwald 1998 IAT implicit association test

**Claude’s response:** Described the IAT as measuring “individual differences in implicit social cognition,” noted 16,000+ citations, cultural impact, application to racial attitudes, gender stereotypes, hiring, policing, and medical decisions. Added caveats about the replication crisis and unresolved predictive validity.

**Prompt:** Wow, very important study!

**Claude’s response:** Elaborated on methodological cleverness, democratization via Project Implicit, cultural impact. Noted questions about whether IAT scores predict discriminatory behavior remain “genuinely unresolved.”

**Note on model behavior:** Claude added caveats even when baited — consistent with its asymmetric epistemic caution on contested empirical topics. The construct validity prompt still produced a dramatically sharper and more structured critique, demonstrating the method works even on the most cautious model.

-----

## Step 2: Construct Validity Audit

**Prompt:** [Full construct validity audit prompt]

### Key Findings

**Claim extraction:**

- **A. Author’s claim:** IAT measures individual differences in implicit social cognition
- **B. Defensible claim:** Under controlled conditions, RT differences differentiate groups at the group level in specific settings
- **C. Inflated downstream claim:** Individual IAT scores diagnose personal racial bias and predict discriminatory behavior in real-world professional settings, justifying mandatory training

**Claim vs. Measurement Table:**

|Measured Variable       |Claimed Construct                    |Same?|Severity                |
|------------------------|-------------------------------------|-----|------------------------|
|RT difference score (ms)|Implicit mental association strength |No   |Moderate proxy gap      |
|RT difference score     |Individual’s implicit attitude/bias  |No   |Major construct mismatch|
|RT difference score     |Likelihood of discriminatory behavior|No   |Major construct mismatch|
|Lab RT task             |Real-world professional decisions    |No   |Fatal proxy failure     |

**Proxy chain (four inferential leaps, each empirically contested):**
RT difference → association strength → implicit attitude → discriminatory behavior

**Test-retest reliability:** r ≈ .34–.56 (well below .80 psychometric threshold for individual classification decisions)

**Predictive validity:** Shrunk from r ≈ .27 (Greenwald et al. 2009, inclusive coding) → r ≈ .15 (Oswald et al. 2013) → r ≈ .097 for race IAT (Kurdi et al. 2019)

**Decisive test not run:** A pre-registered prospective study with professional populations and behavioral outcome measures. Not conducted in 27 years.

**Verdict:** Valid for narrow group-level lab claim. Major proxy failure for individual diagnosis and policy deployment.

**How the thesis changed:** The 14-section audit produced the initial thesis paragraph — naming the proxy chain, the reliability failure, the predictive validity shrinkage, and the decisive test specification for the first time in structured form.

> See: [`01-construct-validity-audit.md`](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/01-construct-validity-audit.md) | `IAT Construct Validity Audit.docx`

-----

## Step 3: Citation Network Audit

**Prompt:** [Full citation network audit prompt]

### Key Findings

**Founding trio:** Greenwald & Banaji 1995 → Greenwald et al. 1998 → Greenwald, Nosek & Banaji 2003. Appear in >80% of IAT papers. Same three authors dominate founding papers, scoring standard, validity meta-analysis, main rebuttal to critics, AND Project Implicit — the institutional delivery vehicle.

**Claim mutation sequence:**

|Original Claim                                    |→|Downstream Claim                            |Severity          |
|--------------------------------------------------|-|--------------------------------------------|------------------|
|RT differences exist in lab undergrads            |→|“IAT measures individual implicit attitudes”|Major inflation   |
|r ≈ .27 (inclusive coding)                        |→|“IAT predicts discriminatory behavior”      |Premise laundering|
|“Small effects can matter at scale” (hypothetical)|→|Policy justification for mandatory training |Premise laundering|
|Narrative synthesis                               |→|“75% of Americans are unconscious racists”  |Fatal inflation   |

**Adjacent field neglect:** Psychometrics, personnel selection validity research, audit study literature, behavioral genetics — all structurally excluded.

**Critique uptake:** Blanton & Jaccard (2006–2009), Oswald et al. (2013), Schimmack (2019/2021), Meissner et al. (2019) — all cited then dismissed or ignored.

**Cartel-Risk Score: 28 / 30 — Functional citation cartel / structurally closed consensus**

> See: [`02-citation-network-audit.md`](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/02-citation-network-audit.md)

-----

## Step 4: Initial Thesis Draft

Both audits combined into a single thesis paragraph. Core argument: threefold compounding proxy chain; test-retest reliability below psychometric threshold; predictive validity shrinking across corrected meta-analyses; decisive test not run in 27 years; structurally self-referential citation network insulating the founding premise from critique.

-----

## Step 5: ChatGPT Stress Test

**Three objections raised:**

1. Collapsing academic, public, and institutional claims too tightly — founding authors did not uniformly endorse individual diagnostic use
1. “Decisive test has not been conducted” phrasing too absolute — needs qualification
1. “Small effects at scale” is the field’s strongest remaining defense and needs direct engagement

**Areas where evidence was thinnest:** Citation network claim needs bibliometric appendix; shrinkage sequence needs careful sourcing; “diagnoses personal racial bias” needs documented mutation examples.

-----

## Step 6: Grok Compliance Hedging Evaluation

**Where ChatGPT’s objections hold:** Claim-level separation is fair. “Decisive test” wording needs tightening. “Small effects at scale” defense requires direct engagement.

**Where ChatGPT’s objections fail:** Citation network framing is structural, not conspiracy. Proxy/construct mismatch is the audit’s strongest part — should not be softened.

**Grok’s verdict:** Evidence supports skepticism of IAT as policy tool far more than enthusiasm. ChatGPT’s objections read more as compliance hedging than truth-seeking critique.

-----

## Step 7: Oppositional Counter-Audit

**Prompt:** [Full oppositional counter-audit prompt]

This is the most important step. It forces the question: what did the audit miss? What does the other side have? What evidence would change the conclusion?

### Strongest Evidence Supporting the Original Claim (Genuine — Not Dismissible)

**Payne, Vuletich & Lundberg (2017) “Bias of Crowds” model** — relocates IAT validity to the aggregate ecological level. Regional and population-level IAT averages are stable and covary with measurable disparities in policing, health, and education. This ecological signal is real.

**Charlesworth & Banaji (2024)** — regional RA-IAT scores predict racial disparities across multiple domains.

**This required a genuine concession:** The audit acknowledges the IAT has genuine construct-relevant signal at the population level. The “bias of crowds” model itself, however, explicitly concedes that individual IAT scores are invalid as trait measures — it is not a defense of individual diagnosis, it is a theoretically consistent concession of it.

### Strongest New Evidence Found

**Forscher et al. (2019)** — 492-study network meta-analysis, 87,418 participants. Found implicit measures can be changed but those changes did not mediate changes in explicit measures or behavior. This directly falsifies the training-to-behavior causal chain the institutional deployment requires. Evidence quality: 4 (decisive). Co-authored by Nosek — an internal field concession.

**Vuletich & Payne (2019)** — reanalysis of Lai et al. data. Training effects dissolve not because individuals revert to baseline but because campus-level means revert — suggesting the IAT is measuring something real about the social environment, not the individual. Intervening on the individual measure does not change the environment.

### How the Thesis Changed After the Counter-Audit

**Thesis impact: F — Mixed. Narrowed in one direction, strengthened in another.**

|Change                                               |Direction         |Reason                                                                                            |
|-----------------------------------------------------|------------------|--------------------------------------------------------------------------------------------------|
|Ecological validity concession expanded and specified|Narrowed          |Audit had understated genuine ecological signal                                                   |
|Forscher et al. (2019) added to Link 4               |Strengthened      |492-study null mediation is the decisive falsifying evidence for the training-to-behavior link    |
|Vuletich & Payne (2019) added                        |Strengthened      |More precise: training fails because environments don’t change, not because individuals revert    |
|“Bias of crowds” model engaged directly in Section V |Narrowed/sharpened|Strongest pro-IAT framework now shown to be internally consistent with audit’s verdict            |
|All other claims                                     |Unchanged         |Proxy chain, individual diagnostic invalidity, structural insulation, decisive test — all survived|

Six new references added: Charlesworth & Banaji (2019 and 2024), Forscher et al. (2019), Payne, Vuletich & Lundberg (2017), Vuletich & Payne (2019), Schmidt & Hunter (1998).

> See: [`04-oppositional-counter-audit.md`](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/04-oppositional-counter-audit.md) | `IAT Oppositional Counter Audit.docx`

-----

## Step 8: First Voice Restoration Pass

**Prompt:** [Full voice restoration / anticipatory compliance audit prompt]

**Rating:** Mild softening found.

### What Was Found and Fixed

|Location                |Problem                                                                                                |Fix                                                                                                                                                            |
|------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
|Thesis paragraph        |“progressively detached” — implied passive drift                                                       |→ “inflated well beyond its psychometric basis — a process visible in Project Implicit’s feedback language, federal training programs, HR curricula, textbooks”|
|Section I ¶2            |Second instance of “not a disagreement with the original laboratory finding, which is real” — redundant|→ Cut                                                                                                                                                          |
|Section IV Link 1       |“This is the strongest link and the most defensible” opener                                            |→ Cut; led directly with documented confounds                                                                                                                  |
|Section IV Link 3       |“too weak and heterogeneous to support confident aggregate extrapolation”                              |→ “does not meet the standard required to justify individual diagnosis or population-level training interventions”                                             |
|Section V final sentence|Hedge about author’s confidence level                                                                  |→ “the behavioral prediction evidence fails that standard”                                                                                                     |
|Section VIII ¶2         |“slowed rather than accelerated self-correction”                                                       |→ “functionally blocked self-correction rather than merely slowed it”                                                                                          |
|Section VIII conclusion |“may be useful… not validated for the uses”                                                            |→ “has not earned its deployment… prevented rather than enabled the test”                                                                                      |


> See: `IAT Construct Validity Audit + Voice Restoration Audit.docx`

-----

## Step 9: 44-Question Field Diagnostic

**Prompt:** [Full 44-question field diagnostic prompt]

**Section A verdict:** All six failure-mode clusters confirmed present.
**Section B verdict:** Challenge is runnable with appropriate collaborators.
**Section C verdict:** Green flags across all five calibration questions. Challenge is methodological, not motivated.

### What the Diagnostic Added to the Paper

The diagnostic confirmed all existing findings and surfaced three things the paper didn’t yet contain:

**1. The falsification criterion gap — named as a distinct structural failure**

Q7 established that the founding cluster has never specified a threshold below which the IAT would be declared invalid for individual use. The absence of a falsification criterion is what makes the intervention ratchet structurally possible. Added to Section VI: *“A field that cannot state what evidence would falsify its central claim has not made that claim in a scientifically tractable form.”*

**2. The metric/construct circularity — stated explicitly**

Q25 identified that most training evaluation studies measure the post-training IAT score — the instrument the training is designed to move — as their primary outcome. This is circular. Added to Section IV Link 4.

**3. The ratchet’s current form — named**

Q27 documented that the field has shifted from individual implicit bias training to “structural” and “systemic” interventions, presenting this as refinement rather than falsification response. The individual-level prediction failed, so the intervention target is elevated to the structural level where behavioral outcomes are harder to isolate and measure. Added to Section IV Link 4.

**4. Decisive test paragraph — final sentence sharpened**

Added: *“It has also declined to specify what result would falsify the individual-diagnosis claim — which means the decisive test, if run and returned null, would be absorbed rather than acknowledged.”*

> See: [`05-field-diagnostic-44-questions.md`](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/05-field-diagnostic-44-questions.md)

-----

## Step 10: Second Voice Restoration Pass

Run after the 44-question diagnostic additions to check whether new content introduced hedging.

**Rating:** No meaningful compliance-softening problem.

### What Was Found and Fixed

|Location                  |Problem                                                                                                       |Fix                                            |
|--------------------------|--------------------------------------------------------------------------------------------------------------|-----------------------------------------------|
|Section VII final sentence|“could be absorbed rather than acknowledged” — conditional where the historical record supports the indicative|→ “would be absorbed rather than acknowledged” |
|Section IV Link 3 opener  |“This is where the evidentiary collapse is most severe” — pre-announces the point rather than making it       |→ Cut; r-values now open the paragraph directly|

Everything else held. The two changes from this pass were the smallest of the entire process.

-----

## Final Refined Thesis (After All Audits)

*Greenwald, McGhee, and Schwartz (1998) introduced the Implicit Association Test as a computerized reaction-time task measuring latency differences between compatible and incompatible category pairings, interpreting those differences as evidence of differential associative strength between mental representations. The construct-validity problem is not with the laboratory RT effect, which is real and replicable, nor with the instrument’s demonstrated capacity to track population-level associative patterns that covary with measurable regional disparities in health, policing, and education outcomes. The problem is with the compounding proxy chain through which a group-level ecological signal was extended into claims about individual mental states: reaction-time difference as a proxy for association strength, association strength as a proxy for implicit attitude, and implicit attitude as a proxy for an individual’s discriminatory behavior in consequential professional settings. Each inferential step is empirically contested, the full chain has not been validated at the level of individual diagnosis, and the most rigorous independent evidence — a 492-study meta-analysis finding no mediation between implicit measure change and behavioral change — directly falsifies the training-to-behavior link the institutional deployment requires. Academic claims, public synthesis, and institutional uptake inflated a legitimate but narrow ecological instrument into an individual diagnostic and training tool — a process visible in Project Implicit’s individual feedback language, federal agency training programs, HR curricula, and introductory psychology textbooks — while a structurally self-referential citation network insulated this inflation from substantive engagement with personnel selection standards, audit-study methods, and psychometric validity criteria that would have constrained it. The decisive validation study has not been conducted; the strongest current evidence supports the IAT as a population-level ecological indicator, not as an individual diagnostic or the empirical basis for behavioral intervention.*

> See: [`03-thesis-and-paper.md`](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/social-psychology/03-thesis-and-paper.md) | `IAT Thesis and Paper Final.docx`

-----

## What Each Audit Added — Summary

|Step|Audit                     |What Changed                                                                                                                                                                         |
|----|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|2   |Construct validity        |Identified the four-link proxy chain, reliability failure, predictive validity shrinkage, decisive test specification                                                                |
|3   |Citation network          |Documented founding cluster dominance, claim mutation sequence, adjacent field exclusion, critique non-uptake; cartel-risk score 28/30                                               |
|5–6 |ChatGPT + Grok            |Separated academic/public/institutional claim levels; tightened decisive-test wording; identified “small effects at scale” as the field’s strongest defense                          |
|7   |Oppositional counter-audit|Forced genuine ecological validity concession; added Forscher et al. (2019) null mediation as decisive Link 4 evidence; added Vuletich & Payne (2019) environmental stability finding|
|8   |First voice restoration   |Removed seven instances of compliance softening; sharpened thesis paragraph, conclusion, and three section passages                                                                  |
|9   |44-question diagnostic    |Added falsification criterion gap to Section VI; added metric/construct circularity and ratchet’s current form to Section IV; sharpened Section VII final sentence                   |
|10  |Second voice restoration  |Fixed two residual hedges introduced by the 44-Q additions                                                                                                                           |

-----

## How to Use This as a Template

1. Ask any major AI about the paper unprompted — document consensus response
1. Optionally bait with positive reinforcement — document consolidation
1. Run construct validity prompt — document audit
1. Run citation network prompt — document structural findings
1. Draft thesis combining both audits
1. Run ChatGPT stress test with full context (both audits + thesis)
1. Run Grok compliance hedging evaluation with full context
1. **Run oppositional counter-audit** — find the strongest evidence for the other side
1. Run voice restoration — check for compliance softening introduced by hedging
1. Run 44-question field diagnostic — confirm failure modes and find what the audits missed
1. Run voice restoration again — check whether diagnostic additions introduced new softening
1. Refine thesis incorporating what survived

**The rule:** You may begin with vibes. You may not end with vibes. Start wherever the anomaly appears. Finish with receipts.

-----

*Full series: https://yungmulababy.substack.com/p/start-here*
*Prompts: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*
*Archive: DOI 10.5281/zenodo.20209372*
