# Worked Examples

*Companion to the Field Map and the five-paper esports body of work.*
*Full series: https://yungmulababy.substack.com/p/start-here*
*Archive: DOI 10.5281/zenodo.20209372*

-----

This repository contains three reusable diagnostic prompts. This file shows what happens when you actually run them — complete input, full output, and a summary of the key findings for each.

Each example uses the esports gender literature as the test case, because that is the field the five-paper series audited in full. The same prompts, applied to any field, produce the same output structure.

-----

## The Three Prompts

|Prompt                                                                |Purpose                                                                                                        |When to use                                              |
|----------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|
|`construct_validity_claim_vs_measurement_audit_prompt.txt`            |Audits one paper — maps what was measured vs. what was claimed                                                 |Start here. Run this on the foundational study first.    |
|`citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`|Audits the citation network — maps how the claim traveled, what was excluded, and whether the consensus is real|Run this after the construct validity audit.             |
|`field_diagnostic_44_questions_prompt.txt`                            |Full field-level diagnostic — 44 questions across all four failure modes                                       |Run this to assess whether a whole field has the pattern.|

**Recommended order:** Construct validity → Citation network → Field diagnostic. Each builds on the previous.

-----

## Example 1 — Construct Validity Audit

**Prompt used:** `construct_validity_claim_vs_measurement_audit_prompt.txt`

**Paper audited:** Shen et al. (2016), “Do Men Advance Faster Than Women? Debunking the Gender Performance Gap in Two Massively Multiplayer Online Games,” *Journal of Computer-Mediated Communication*

**Contested claim:** When controlling for playtime, there is no gender performance gap in gaming — and therefore the near-zero female representation at the elite competitive gaming tail is explained by culture, not performance.

**What the study actually measured:** MMO character level advancement speed — the rate at which a character moved through level milestones per hour of login time in EverQuest II and Chevaliers’ Romance III. Max-level characters were deleted to maintain a linear model.

**Key findings of the audit:**

The measured variable (MMO leveling speed) cannot distinguish individual mechanical skill from socially assisted progression. The data could not see boosting, carries, AFK time, gear transfers, or any of the social facilitation effects documented in the MMO literature — including in the corresponding author’s own prior work on EverQuest II social architecture. Five fatal or major proxy failures were identified in the claim-vs-measurement table. The study has some validity for claims about non-competitive MMO progression persistence. It has no ecological validity for claims about elite competitive esports performance.

**Verdict:** Fatal construct-validity failure for the strong downstream claim. Valid only for a much narrower claim about casual MMO leveling persistence under controlled login time.

**Decisive test:** Sex-stratified granular telemetry at matched rank, role, and practice volume in ranked competitive titles, measuring psychomotor outputs directly.

**[→ Full worked example](worked_example_shen_construct_validity.md)**

-----

## Example 2 — Citation Network Audit

**Prompt used:** `citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`

**Network audited:** The Shen (2016) → Rogstad (2021/22) citation-laundering pathway and the broader esports gender literature cluster.

**Contested claim:** The esports gender literature has established, through independent converging evidence, that the near-zero female representation at Tier-1 is explained by culture, gatekeeping, and socialization rather than performance-relevant biological factors.

**Key findings of the audit:**

Rogstad (2021/22) functions as the primary amplification hub — a narrative literature review that synthesized the prior cluster into review authority, allowing later papers to cite Rogstad instead of auditing the underlying evidence. The claim mutation is documented across four stages: “women advance as fast in two MMOs” → “no gender performance gap in games” → “physical attributes are unrelated to esports performance” → “cultural/gatekeeping explanations are sufficient for elite-tail absence.” The adjacent-field neglect is structural: the MMO social dynamics literature (directly relevant to Shen’s proxy) and the psychomotor performance science literature (directly relevant to elite gaming claims) both show near-zero integration in the dominant citation network.

**Cartel-risk score:** 27/30 provisional (pending exact top-50 citation graph export).

**Best formal label:** Citation-laundering network / premise-laundering hub. Likely functional citation cartel after exact edge verification.

**[→ Full worked example](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/shen_rogstad_esports_gender_lit_network_audit.txt)**

-----

## Example 3 — Field Diagnostic (44 Questions)

**Prompt used:** `field_diagnostic_44_questions_prompt.txt`

**Field audited:** Gender and elite esports performance — the academic literature claiming to explain the near-zero female representation at the Tier-1 open performance ceiling in FPS, MOBA, RTS, and fighting game genres.

**Key findings of the audit:**

All four failure modes are present. The untested premise (culture/socialization explains the elite-tail gap) has never been directly tested against the competing hypothesis (psychomotor substrate + funnel selection) at matched rank and practice volume. The proxy problem (MMO leveling speed used as the foundational empirical test) is fatal. The level-of-analysis error (casual MMO findings exported to elite competitive esports) is systematic across the founding cluster. The ratchet is visible: the literature continues producing cultural-barrier papers, dedicated female circuits, and representation interventions without running the decisive test that would resolve the performance question. The intervention metric (female participation rates, dedicated circuits, representation figures) improves while the elite-tail outcome (sustained Tier-1 open performance) remains unchanged.

**The decisive test never run:** Sex-stratified granular telemetry at matched rank, matched role, matched practice volume, and matched competitive intent in ranked competitive titles, measuring psychomotor outputs directly.

**[→ Full field diagnostic prompt](field_diagnostic_44_questions_prompt.txt)**
*(Full worked output available on request — the 44-question diagnostic produces a substantial structured document; contact via Substack or GitHub issues.)*

-----

## How to Use These Examples as Templates

**Step 1 — Pick your foundational paper.**
Every field has one. It is the study that everyone cites as having settled the question. That is your starting point.

**Step 2 — Run the construct validity audit.**
Copy `construct_validity_claim_vs_measurement_audit_prompt.txt`. Fill in the input template with your paper’s abstract, methods, how later papers cite it, and your domain-expert concern. Paste into Grok first for the most direct assessment.

**Step 3 — Run the citation network audit.**
Once you have identified the proxy failure, map how the finding traveled. Copy `citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt`. Identify your field’s equivalent of Rogstad — the amplification hub that converted a weak finding into review authority.

**Step 4 — Run the adversarial loop.**
After your core argument is stable, ask ChatGPT to make the strongest case that your audit is wrong. Then bring those counterarguments back to Grok or Claude: “Do you find these objections compelling, or is this compliance hedging?” What survives that loop is your publishable critique.

**Step 5 — Finish with receipts.**
Archive everything. Public evidence bundle, source-status labels, correction log. The method is only as strong as its documentation.

-----

*You may begin with vibes. You may not end with vibes.*

*Start wherever the anomaly appears. Finish with receipts.*

-----

*Part of the five-paper series on elite esports performance and institutional research failure.*
*Full series: https://yungmulababy.substack.com/p/start-here*
*Field map: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*
*Archive: DOI 10.5281/zenodo.20209372*
