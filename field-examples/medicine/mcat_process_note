# Worked Example: Live X Argument Audit

## MCAT Admissions Debate — Construct Validity Audit and Citation-Use Audit in Real Time

*This document is a process note documenting how the adversarial research toolkit was applied to a live public argument on X (May 2026). It is the third worked example in the toolkit, after the Shen esports audit and the IAT audit.*

*Prompts used:*

- *`construct_validity_claim_vs_measurement_audit_prompt.txt`*
- *Citation-use audit (applied via the citation network prompt)*

*Full series: https://yungmulababy.substack.com/p/start-here*
*Repository: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*

-----

## The Situation

A physician posted a thread on X arguing that critics of diversity-based medical school admissions are scientifically illiterate. The central empirical claim:

*“Small MCAT differences among already highly capable applicants do NOT reliably predict who becomes the best clinician.”*

The thread invoked “the literature on medical education, physician performance, and diversity in medicine” as settled evidence. No specific studies were cited in the original thread.

**Why this is a toolkit target:** The claim makes a specific empirical assertion — MCAT does not predict clinical excellence — and uses it to delegitimize critics. The construct validity prompt asks exactly this question: does the metric measure the same thing as the claim?

-----

## Step 1: Construct Validity Audit

**Prompt used:** `construct_validity_claim_vs_measurement_audit_prompt.txt`

**Input:** The central claim, the metric (MCAT scores), the claimed construct (clinical excellence / “best clinician”), and adjacent literature summary.

**Key findings:**

**The proxy chain:**
MCAT → USMLE scores → residency program director ratings → clinical excellence

Each link is empirically contested. The full chain has not been validated at the level at which the claim is deployed.

**The numbers:**

- MCAT → USMLE: r ≈ .42–.49 (moderately strong — MCAT predicts board passage)
- MCAT → program director ratings: weak correlations
- MCAT → patient outcomes: not studied at scale

**The range restriction problem:**
The claim is specifically about “small differences among already highly capable applicants.” Correlations within a pre-selected qualified pool are structurally attenuated for any predictor. This is standard psychometrics. Finding modest within-range correlations is the expected finding regardless of MCAT’s actual validity.

**The decisive test:**
A pre-registered prospective study in professional populations, measuring MCAT scores at admission and tracking actual patient outcomes longitudinally. This study has not been conducted in 27 years of research.

**The critical finding:** The physician’s own framing acknowledges the decisive test hasn’t been run — then reasons as if it had been. That is the exact epistemic error he attributes to critics.

**Published audit:** https://yungmulababy.substack.com/p/the-mcat-debate-has-a-proxy-problem

-----

## Step 2: The Response — 17 Citations

After the audit post was published, the physician posted a list of 17 studies with the message: “Selected literature for those pretending this evidence does not exist.”

This is a specific rhetorical strategy — the citation laundry list. It works because the implicit message is “I have 17 citations therefore I’ve done my homework.” It relies on the cost of verification being prohibitive. Nobody has time to check 17 papers.

The toolkit eliminates that cost.

-----

## Step 3: Citation-Use Audit

**Prompt used:** Citation-use audit (via the citation network prompt framework)

**Input:** All 17 cited studies, organized by cluster, with the core question: does each paper actually measure what it’s being cited to support?

**The four clusters and verdicts:**

**Cluster 1 — MCAT Predictive Validity (5 papers):**
None measure patient outcomes. All study USMLE performance, training ratings, or academic progression. Proxy substitution error in every case.

Most damaging finding: **Donnon et al. (2007) — citation reversal.** The physician cited this paper to show MCAT doesn’t predict good doctoring. The paper shows MCAT does predict its downstream proxy (USMLE r ≈ .42–.49). He cited the wrong side of his own argument. This is the first paper on his list.

**Cluster 2 — Structural Bias & Admissions (4 papers):**
These address real problems — structural bias in admissions, disparate demographic impact. But disparate impact ≠ predictive invalidity. These are separate empirical questions. Using bias literature to settle a predictive validity question is a category error.

Lucey & Saguil (2020): **premise laundering** — policy advocacy cited as empirical settlement.

**Cluster 3 — Physician Diversity & Outcomes (4 papers):**
These come closest to the decisive test. Snyder et al. (2023) shows Black PCP representation → better outcomes for Black patients. Hill et al. (2023) shows Black physician supply → better Black patient outcomes.

Real findings. But they answer a different question. Race concordance and physician supply effects address healthcare access. They don’t stratify physicians by admissions MCAT scores. The mechanism (cultural competence, geographic distribution, patient trust) remains unresolved.

**Cluster 4 — Medical School Diversity Outcomes (4 papers):**
Address the value of diverse learning environments and physician workforces. Real findings. None address whether MCAT scores predict clinical excellence.

Morris et al. (2021): **prestige laundering** — NEJM perspective piece cited as if journal placement confers empirical weight.

**Master verdict:** 0 of 17 studies run the decisive test. The citation list is real literature. The studies exist. Many report genuine findings. Not one of them answers the question being claimed as settled.

**Published citation audit:** https://yungmulababy.substack.com/p/the-citation-audit-what-17-studies

-----

## What This Demonstrates

**The citation laundry list strategy fails when the verification cost is eliminated.**

The physician assembled 17 real studies from legitimate journals. The list looks authoritative. In any normal online argument, nobody checks. The citations function as social proof of expertise, not as evidence.

The citation-use audit prompt ran through all 17 in one session. The result: four distinct category errors, one citation reversal, one premise laundering, one prestige laundering, and zero decisive tests.

**The Donnon reversal is the key finding.** It’s immediately comprehensible to anyone:

- He cited a paper to prove MCAT doesn’t predict good doctoring
- The paper shows MCAT does predict its downstream proxy
- That’s the first citation on his list

No domain expertise required to understand why that matters.

**The timeline:** Original claim → construct validity audit → published post → physician posts 17 citations → citation-use audit → published follow-up. All within one day. The argument that used to take weeks to document properly now takes hours.

-----

## Key Quotes

**From the construct validity audit:**
*“The physician’s own framing acknowledges the decisive test hasn’t been run — then reasons as if it had been. That is the exact epistemic error he attributes to critics.”*

**From the citation audit:**
*“The accusation that critics are ‘pretending this evidence does not exist’ is a rhetorical move that relies on the audience not checking what the evidence actually measures.”*

**The one-line version:**
The citation laundry list strategy relies on the cost of verification being prohibitive. The toolkit eliminates that cost.

-----

## Prompts Used

**Construct validity prompt:**
https://raw.githubusercontent.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/main/construct_validity_claim_vs_measurement_audit_prompt.txt

**Citation network / citation-use prompt:**
https://raw.githubusercontent.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/main/citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt

-----

## Published Outputs

- Original construct validity audit post: https://yungmulababy.substack.com/p/the-mcat-debate-has-a-proxy-problem
- Citation audit post: https://yungmulababy.substack.com/p/the-citation-audit-what-17-studies
- Full toolkit: https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research

-----

## Notes on Step Order

This audit ran in a compressed real-time sequence rather than the full recommended workflow:

1. Construct validity audit ✅
1. Publish immediately (timely argument)
1. Citation-use audit on response ✅
1. Publish follow-up

Steps not run: 44-question field diagnostic, oppositional counter-audit, voice restoration. These would be appropriate if developing this into a full paper. For a live argument audit, the construct validity and citation-use prompts are sufficient to document the core finding.

*You may begin with vibes. You may not end with vibes. Start wherever the anomaly appears. Finish with receipts.*
