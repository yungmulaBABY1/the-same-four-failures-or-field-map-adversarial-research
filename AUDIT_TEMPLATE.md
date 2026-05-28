# Adversarial Research Toolkit — Audit Template

Use this file as a starting point for producing your own structured audit. Copy the blank template, fill in the fields, and work through the prompts in order. Three worked examples follow the blank template showing different prompt combinations and failure modes.

-----

## Blank Template

**Title:**
[Short descriptive title of the claim or paper being audited]

**Source:**
[Link to paper, thread, report, or policy document]

**Claim Being Audited:**
[1–2 sentences. What is this source being used to prove?]

**Field / Debate:**
[What field or institutional dispute is this source part of?]

**Entry Point:**
[ ] Domain expert entry — specific study triggered the suspicion
[ ] Discovery entry — 44-question field diagnostic surfaced this as a high-risk target

**Prompts Used:**

- [ ] Construct Validity Audit
- [ ] Internal Validity & Replication Audit
- [ ] Citation Network Audit
- [ ] 44-Question Field Diagnostic
- [ ] Oppositional Counter-Audit
- [ ] Voice Restoration
- [ ] Off-Label Use Audit (if applicable)

**Key Findings:**

*Construct Validity:*
[What was actually measured vs. what was claimed. State the proxy gap.]

*Internal Validity:*
[Pre-registration status, replication, effect size, data generation concerns.]

*Citation Network:*
[Author cluster concentration, claim mutation, adjacent-field neglect.]

*Decisive Test:*
[What test would directly measure the claimed construct? Has it been run?]

*Other Issues:*
[Level-of-analysis error, ecological validity, omitted confounds, off-label concerns.]

**Source-Status Assessment:**
[What tier is the load-bearing evidence resting on? Where are the tier jumps?]

**Verdict:**
[Direct assessment using the verdict scale: Valid / Partial / Narrower claim only / Major proxy failure / Fatal construct-validity failure / Citation-laundered premise]

**What Would Change This Assessment:**
[What evidence would upgrade or downgrade the verdict?]

-----

## Worked Example 1: The IAT’s 27-Year Proxy Problem

**Title:** A Login Timestamp Became Proof of Racism: The IAT’s Proxy Problem

**Source:** Greenwald, Banaji & Nosek (1998). “Measuring individual differences in implicit cognition: The Implicit Association Test.” *Journal of Personality and Social Psychology, 74*(6), 1464–1480. (~22,000 citations)
Full audit: https://yungmulababy.substack.com/p/a-login-timestamp-became-proof-of

**Claim Being Audited:**
Individual IAT scores diagnose personal implicit bias and predict discriminatory behavior in real professional settings. This justifies mandatory implicit bias training at corporations, federal agencies, universities, and healthcare systems.

**Field / Debate:**
Social psychology / implicit bias / diversity training

**Entry Point:**
Domain expert entry — construct validity suspicion: reaction-time differences in a lab task were being used to justify individual-level HR interventions.

**Prompts Used:**

- [x] Construct Validity Audit
- [x] Citation Network Audit
- [x] Oppositional Counter-Audit
- [x] Voice Restoration

**Key Findings:**

*Construct Validity:*
The IAT measures reaction-time differences between compatible and incompatible category pairings in a controlled lab task. The institutional deployment requires four inferential leaps — RT difference → association strength → implicit attitude → discriminatory behavior — none of which were directly validated at the level of analysis where the test is deployed. Test-retest reliability: r ≈ .34–.56 (threshold for individual classification: r ≥ .80). Predictive validity for discriminatory behavior has shrunk across corrected meta-analyses from r ≈ .27 (2009) to r ≈ .097 (2019). At r ≈ .097, the IAT explains under 1% of unique variance in discriminatory behavior above explicit self-report.

*Internal Validity:*
The decisive prospective pre-registered study — IAT scores at baseline tracked to actual discriminatory outcomes longitudinally in professional populations — has not been conducted in 27 years. Forscher et al. (2019), 492 studies, 87,418 participants: implicit measures can be changed, but those changes do not mediate changes in explicit measures or behavior. The training-to-behavior causal chain is directly falsified by the largest and most rigorous test conducted.

*Citation Network:*
Cartel-risk score: 28/30. The same three founding authors (Greenwald, Banaji, Nosek) control the founding paper, the D-score scoring standard, the primary validity meta-analysis, the main rebuttal to critics, and Project Implicit — the institutional delivery vehicle. Five major critiques were cited then dismissed without updating the consensus.

*Decisive Test:*
A pre-registered prospective study in professional populations measuring IAT scores at baseline and tracking actual discriminatory outcomes longitudinally. Not conducted.

*Other Issues:*
Level-of-analysis error: a group-level laboratory finding exported to individual-level diagnosis and policy without validating the inferential chain. Ratchet: mandatory training expanded despite the Forscher et al. falsification.

**Source-Status Assessment:**
The load-bearing institutional claim rests on Tier 4 individual studies (with replication failures) and Tier 5 guidelines citing the same founding cluster. The decisive Tier 2 prospective evidence has not been produced. The Tier 3 meta-analytic evidence (Forscher et al.) falsifies the training-to-behavior chain. Citation laundering: the r ≈ .097 finding from Kurdi et al. (2019) is rarely preserved as the IAT propagates through policy documents.

**Verdict:**
C — Useful for a narrower claim, invalid for the stronger claim. The IAT has genuine signal at the population/ecological level (regional averages track measurable disparities). It has not been validated as an individual diagnostic tool or as the empirical basis for mandatory training interventions. The institutional deployment rests on a claim the evidence does not support.

**What Would Change This Assessment:**
A pre-registered prospective study in professional populations demonstrating that IAT scores predict discriminatory behavior at r ≥ .30 above explicit self-report, with replication by independent labs not involving the founding cluster.

-----

## Worked Example 2: The Donnon Reversal — Citation Audit of 17 Studies

**Title:** The Citation Audit: What 17 Studies Actually Measure

**Source:** Physician’s X thread citing 17 studies to support the claim that MCAT does not predict clinical excellence. First citation: Donnon et al., *Academic Medicine*, 2007 (PMID: 17198300).
Full audit: https://yungmulababy.substack.com/p/the-citation-audit-what-17-studies

**Claim Being Audited:**
MCAT scores do not predict clinical excellence or good doctoring. The literature supports removing or deprioritizing MCAT in medical admissions.

**Field / Debate:**
Medical admissions / MCAT debate / DEI in medicine

**Entry Point:**
Domain expert entry — a physician publicly cited 17 studies as evidence for the claim. The first citation triggered the audit.

**Prompts Used:**

- [x] Construct Validity Audit (applied to each citation)
- [x] Citation Network Audit

**Key Findings:**

*Construct Validity:*
Donnon et al. (2007) — the first citation in a list claiming MCAT doesn’t predict good doctoring — shows MCAT predicts USMLE Step 1 and Step 2 performance at r ≈ .42–.49. The study was cited to support the opposite of its finding. This is a citation reversal: the evidence runs against the claim it was cited to support. Across all 17 studies: none measure patient outcomes directly. The studies measure USMLE performance, program director ratings, academic progression, demographic disparities in admissions, and healthcare access outcomes for underserved populations. These are real findings with real implications — but none of them answer whether MCAT scores predict clinical excellence. The proxy substitution is consistent across the full citation list: “MCAT is associated with disparate demographic impact” (real) gets laundered into “MCAT doesn’t predict good doctoring” (not tested by these studies).

*Citation Network:*
The 17-study list conflates four distinct literatures — MCAT predictive validity, structural bias in admissions, physician diversity and patient outcomes, and medical school diversity — and presents them as a unified body of evidence for a single claim. Category errors compound across citation steps.

*Decisive Test:*
A prospective study tracking MCAT scores at admission through to patient outcome measures at career scale, controlling for residency program quality and specialty. Not present in the 17-study list.

*Other Issues:*
Prestige laundering: NEJM perspective pieces cited as if they were outcome studies. Scope mismatch: race concordance → patient outcomes is a real finding but answers a different question than admissions MCAT → physician excellence. Conflating them launders an access argument into a predictive-validity argument.

**Source-Status Assessment:**
The load-bearing claim rests heavily on Tier 5 (guidelines and policy documents) and Tier 7 (perspective pieces and advocacy summaries). The Tier 4 empirical studies cited either directly contradict the claim (Donnon) or answer a different question entirely. No Tier 1–3 evidence measuring patient outcomes stratified by admissions MCAT score appears in the list.

**Verdict:**
F — Citation-laundered premise. Weak and misread original evidence inflated into apparent consensus. The Donnon reversal is not an exceptional failure — citation integrity research documents 14–18% error rates across the literature. It is a documented pattern being used to support a specific policy conclusion.

**What Would Change This Assessment:**
A study measuring patient outcomes (morbidity, mortality, diagnostic accuracy, complication rates) stratified by physician admissions MCAT score, with adequate sample size and controlling for residency training quality. None of the 17 studies cited is that study.

-----

## Worked Example 3: Shen et al. (2016) — The Esports Gender Literature

**Title:** Construct Validity Audit — Shen et al. (2016), the Most-Cited Paper in the Esports Gender Literature

**Source:** Shen, J., et al. (2016). “Toward a model of gender differences in technology use.” Most-cited foundational paper in academic literature claiming gender performance gaps in esports reflect cognitive and socialization differences. Part of the five-paper esports series archived at DOI 10.5281/zenodo.20209372.

**Claim Being Audited:**
Gender performance gaps in esports reflect stable cognitive or socialization differences that justify institutional interventions in competitive structures.

**Field / Debate:**
Esports gender studies / competitive gaming performance / DEI in esports

**Entry Point:**
Domain expert entry — elite esports practitioner suspicion that published claims did not match observable competitive reality.

**Prompts Used:**

- [x] Construct Validity Audit
- [x] Citation Network Audit
- [x] 44-Question Field Diagnostic
- [x] Oppositional Counter-Audit
- [x] Voice Restoration

**Key Findings:**

*Construct Validity:*
The foundational studies measure self-reported playtime, survey-based technology attitudes, and casual/amateur performance proxies. The claimed construct is elite competitive performance difference. The proxy gap is severe: self-reported playtime in casual populations does not measure the deliberate practice intensity, coaching infrastructure, and selection pressure that determine elite performance. Studies conducted in casual and amateur populations are used to make claims about elite competitive structures — a level-of-analysis error that would be obvious to any competitive gaming practitioner.

*Internal Validity:*
Effect sizes in the foundational literature are small to moderate and based on non-elite, convenience-sampled populations. Pre-registration is largely absent. The decisive test — performance comparison of male and female players at equivalent ranked tiers with equivalent practice histories in elite competitive environments — has not been conducted.

*Citation Network:*
Small founding cluster controls foundational claims, primary reviews, and institutional recommendations. Adjacent literatures — deliberate practice research, expertise development, the esports performance literature, and economics of tournament participation — are systematically underrepresented despite directly addressing the constructs claimed. Claim mutation across citation steps: moderate effect in casual survey populations becomes “gender performance gap in esports” by the time it reaches policy recommendations.

*Decisive Test:*
Longitudinal performance tracking of male and female players at equivalent ranked tiers with equivalent practice histories and access to coaching in elite competitive environments, measuring actual ranked performance outcomes over time.

*Other Issues:*
Ecological validity failure: lab tasks and casual surveys do not resemble elite competitive environments. Ratchet: institutional interventions (modified competitive structures, separate divisions, bounty mechanics) expanded without the decisive test being run. The interventions modify the competitive signal rather than developing underlying capability.

**Source-Status Assessment:**
Load-bearing claims rest on Tier 4 individual studies (convenience samples, non-elite populations, self-report measures) with limited Tier 3 synthesis. Tier 6 practitioner evidence — the observable competitive reality at elite levels — is not incorporated. The Tier 5 policy recommendations go significantly beyond what the Tier 4 evidence supports.

**Verdict:**
C — Useful for a narrower claim, invalid for the stronger claim. Survey-based studies in casual populations may accurately describe technology attitudes and casual participation patterns in those populations. They do not support claims about elite competitive performance differences or justify interventions in elite competitive structures. The field’s confidence significantly exceeds its evidence.

**What Would Change This Assessment:**
Longitudinal performance data from elite competitive environments comparing players at equivalent ranked tiers with equivalent practice histories. This data exists in ranked ladder systems but has not been analyzed against the field’s foundational claims.

-----

## How to Produce Your Own Audit

1. Start with a specific claim that doesn’t sit right — a study, a thread, a policy document, a news article.
1. Copy the blank template above.
1. Run the prompts in order: construct validity first, then internal validity, then citation network, then field diagnostic if the problem appears structural.
1. Add your domain knowledge at Stage 6: state specific observations precisely, test them adversarially, label them as Tier 6 (practitioner evidence).
1. Run the oppositional counter-audit before publishing. What survives is what gets published.
1. Run voice restoration. Did the AI soften the critique until it apologized for existing?
1. Publish with receipts. Archive everything. Make the challenge inspectable and replicable.

**Toolkit:** https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research

*You may begin with vibes. You may not end with vibes.*

*Start wherever the anomaly appears. Finish with receipts.*
