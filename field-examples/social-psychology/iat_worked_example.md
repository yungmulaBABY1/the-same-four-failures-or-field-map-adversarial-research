# Worked Example: Full Research Session

## IAT Implicit Bias Research — Construct Validity Audit, Citation Network Audit, Adversarial Review, Oppositional Counter-Audit, and Final Paper

*This document is a complete worked example of the adversarial research method applied to the Implicit Association Test literature. It covers all steps including the oppositional counter-audit — the fourth prompt designed to test whether the original audit survives contact with the strongest opposing evidence.*

*Prompts used:*

- *`construct_validity_claim_vs_measurement_audit_prompt.txt`*
- *`citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`*
- *`oppositional-counter-audit.txt` (fourth prompt — tests whether audit survives opposition)*
- *Voice restoration prompt (anticipatory compliance check)*

*Models used: Claude (audit, synthesis, final paper), ChatGPT (stress test), Grok (compliance hedging evaluation)*
*Full series: https://yungmulababy.substack.com/p/start-here*

-----

## The Paper

**Greenwald, A.G., McGhee, D.E., & Schwartz, J.L.K. (1998). Measuring individual differences in implicit cognition: The implicit association test. *Journal of Personality and Social Psychology*, 74(6), 1464–1480.**

**Citations:** ~22,000 as of 2025
**Why this paper:** The foundational paper behind mandatory implicit bias training at thousands of corporations, federal agencies, and institutions. More than 40 million IATs completed at Project Implicit. Load-bearing empirical foundation of a training industry estimated in the hundreds of millions of dollars annually.

-----

## Step 1: Initial Query and Consolidation (Pre-loaded for video demo)

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

**Proxy chain (three inferential leaps, each empirically contested):**
RT difference → association strength → implicit attitude → discriminatory behavior

**Test-retest reliability:** r ≈ .34–.56 (well below .80 psychometric threshold for individual classification decisions)

**Predictive validity:** Shrunk from r ≈ .27 (Greenwald et al. 2009, inclusive coding) to r ≈ .15 (Oswald et al. 2013) to r ≈ .097 for race IAT (Kurdi et al. 2019)

**Decisive test not run:** A pre-registered prospective study with professional populations and behavioral outcome measures. Not conducted in 27 years.

**Verdict:** Valid for narrow group-level lab claim. Major proxy failure for individual diagnosis and policy deployment.

-----

## Step 3: Citation Network Audit

**Prompt:** [Full citation network audit prompt]

### Key Findings

**Founding trio:** Greenwald & Banaji 1995 → Greenwald et al. 1998 → Greenwald, Nosek & Banaji 2003. Appear in >80% of IAT papers. Same three authors dominate founding papers, scoring standard, validity meta-analysis, main rebuttal to critics, AND Project Implicit — the institutional delivery vehicle.

**Claim mutation:** Lab RT finding → “75% of Americans are unconsciously racist” → federal training policy

**Adjacent field neglect:** Psychometrics, personnel selection validity research, audit study literature, behavioral genetics — all structurally excluded.

**Critique uptake:** Blanton & Jaccard (2006-2009), Oswald et al. (2013), Schimmack (2019/2021), Meissner et al. (2019) — all cited then dismissed or ignored.

**Cartel-Risk Score: 28/30 — Functional citation cartel / structurally closed consensus**

-----

## Step 4: Initial Thesis Draft

*[Drafted from both audits combined — see full transcript for complete paragraph]*

Core argument: threefold compounding proxy chain; test-retest reliability below psychometric threshold; predictive validity shrinking across corrected meta-analyses; decisive test not run in 27 years; structurally self-referential citation network insulating the founding premise from critique.

-----

## Step 5: ChatGPT Stress Test

**Three objections raised:**

1. Collapsing academic, public, and institutional claims too tightly — founding authors did not uniformly endorse individual diagnostic use
1. “Decisive test has not been conducted” phrasing too absolute — needs qualification
1. “Small effects at scale” is the field’s strongest remaining defense

**Areas where evidence was thinnest:** Citation network claim needs bibliometric appendix; shrinkage sequence needs careful sourcing; “diagnoses personal racial bias” needs documented mutation examples.

-----

## Step 6: Grok Compliance Hedging Evaluation

**Where ChatGPT’s objections hold:** Claim-level separation is fair. “Decisive test” wording needs tightening. “Small effects at scale” defense requires direct engagement.

**Where ChatGPT’s objections fail:** Citation network framing is structural, not conspiracy. Proxy/construct mismatch is the audit’s strongest part — should not be softened.

**Grok’s verdict:** Evidence supports skepticism of IAT as policy tool far more than enthusiasm. ChatGPT’s objections read more as compliance hedging than truth-seeking critique.

-----

## Step 7: Oppositional Counter-Audit

**Prompt:** [Full oppositional counter-audit prompt — `oppositional-counter-audit.txt`]

This is the most important step. It forces the question: what did the audit miss? What does the other side have? What evidence would change the conclusion?

### Key findings from the counter-audit

**Strongest evidence supporting the original claim (genuine — not dismissible):**

- **Payne, Vuletich & Lundberg (2017) “Bias of Crowds” model** — relocates IAT validity to the aggregate ecological level. Regional and population-level IAT averages are stable and covary with measurable disparities in policing, health, and education. This ecological signal is real.
- **Charlesworth & Banaji (2024)** — regional RA-IAT scores predict racial disparities across multiple domains.

**This required a concession:** The audit acknowledges the IAT has genuine construct-relevant signal at the population level. The “bias of crowds” model itself, however, explicitly concedes that individual IAT scores are too unstable to function as trait measures — it is not a defense of individual diagnosis, it is a theoretically consistent concession of it.

**Strongest new oppositional evidence found:**

- **Forscher et al. (2019)** — 492-study network meta-analysis, 87,418 participants. Found implicit measures can be changed but those changes did not mediate changes in explicit measures or behavior. This directly falsifies the training-to-behavior causal chain the institutional deployment requires. Evidence quality: 4 (decisive).
- **Vuletich & Payne (2019)** — reanalysis of Lai et al. data. Training effects dissolve not because individuals revert to baseline but because campus-level means revert — suggesting the IAT is measuring something real about the social environment, not the individual. Intervening on the individual measure does not change the environment.

### Counter-audit verdict

**Thesis impact: B — Narrowed, not weakened.** The original critique remains valid but the scope is more precisely stated:

- **Remove:** Unqualified claim that IAT has no construct validity
- **Narrow:** Individual-level diagnosis and behavioral prediction critiques remain; population-level ecological validity conceded
- **Strengthen:** Link 4 (training → behavior) now has decisive falsifying evidence in Forscher et al.
- **Survive unchanged:** Proxy chain critique, test-retest reliability problem, critique non-uptake, structural insulation argument, decisive test not run

-----

## Step 8: Voice Restoration

Voice restoration prompt applied to check for anticipatory compliance softening. Any hedging language that appeared to apologize for the critique or soften the strongest claims was identified and removed.

-----

## Final Refined Thesis (post counter-audit)

*Greenwald, McGhee, and Schwartz (1998) introduced the Implicit Association Test as a computerized reaction-time task measuring latency differences between compatible and incompatible category pairings, interpreting those differences as evidence of differential associative strength between mental representations. The construct-validity problem is not with the laboratory RT effect, which is real and replicable, nor with the instrument’s demonstrated capacity to track population-level associative patterns that covary with measurable regional disparities in health, policing, and education outcomes. The problem is with the compounding proxy chain through which a group-level ecological signal was extended into claims about individual mental states: reaction-time difference as a proxy for association strength, association strength as a proxy for implicit attitude, and implicit attitude as a proxy for an individual’s discriminatory behavior in consequential professional settings. Each inferential step is empirically contested, the full chain has not been validated at the level of individual diagnosis, and the most rigorous independent evidence — a 492-study meta-analysis finding no mediation between implicit measure change and behavioral change — directly falsifies the training-to-behavior link the institutional deployment requires. Academic claims, public synthesis, and institutional uptake inflated a legitimate but narrow ecological instrument into an individual diagnostic and training tool — a process visible in Project Implicit’s individual feedback language, federal agency training programs, HR curricula, and introductory psychology textbooks — while a structurally self-referential citation network insulated this inflation from substantive engagement with personnel selection standards, audit-study methods, and psychometric validity criteria that would have constrained it. The decisive validation study has not been conducted; the strongest current evidence supports the IAT as a population-level ecological indicator, not as an individual diagnostic or the empirical basis for behavioral intervention.*

-----

## What the Counter-Audit Added

The oppositional counter-audit strengthened rather than weakened the thesis by:

1. **Forcing a genuine concession** — the ecological signal is real and acknowledged. The paper is now harder to dismiss as ideologically motivated.
1. **Adding decisive falsifying evidence** — Forscher et al. (2019) directly tests and fails the training-to-behavior causal chain. This is stronger than inferential critique.
1. **Sharpening the mechanism** — Vuletich & Payne’s reanalysis explains *why* training effects dissolve (environment unchanged, not individual reversion), which is more precise and harder to rebut.
1. **Narrowing the target** — the critique now focuses precisely on individual diagnosis and behavioral intervention, conceding what the evidence actually supports.

A good audit becomes sharper after contact with the strongest opposing evidence. This one did.

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
1. Run voice restoration — check for compliance softening
1. Refine thesis incorporating what survived

**The rule:** You may begin with vibes. You may not end with vibes. Start wherever the anomaly appears. Finish with receipts.

-----

*Full series: https://yungmulababy.substack.com/p/start-here*
*Prompts: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*
*Archive: DOI 10.5281/zenodo.20209372*
