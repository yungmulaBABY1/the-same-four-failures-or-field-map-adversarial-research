# The Same Four Failures: A Field Map and Adversarial Research Manual

**The method, the warning, the worked example, the prompts.**

*Companion to the five-paper esports body of work — DOI 10.5281/zenodo.20209372*
*Full series: https://yungmulababy.substack.com/p/start-here*

-----

## New to This Project? Start Here.

If you are a domain expert who suspects your field has the same failure modes — read **<adversarial_research_method_paper.md>** first. It explains the full method, requires no technical knowledge, and links to everything else.

See **<WORKED_EXAMPLES.md>** for complete worked examples of all three prompts applied to the esports gender literature.

-----

## Files in This Repository

### The Method

|File                                  |Purpose                                                                                                                      |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
|<adversarial_research_method_paper.md>|**Start here.** Full method document — five stages, three prompts, worked example summaries, resulting papers, 10-step guide.|
|<WORKED_EXAMPLES.md>                  |Index of all three worked examples with summaries, key findings tables, verdicts, and links to full examples.                |

### Worked Examples

|File                                               |Purpose                                                                                                                   |
|---------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
|<worked_example_shen_construct_validity.md>        |Full 14-section construct validity audit of Shen et al. (2016). Use as a template for your own field’s foundational paper.|
|<shen_rogstad_esports_gender_lit_network_audit.txt>|Full citation network audit of the Shen → Rogstad pathway.                                                                |

### Diagnostic Prompts

|File                                                                  |Purpose                                                                                        |
|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
|<construct_validity_claim_vs_measurement_audit_prompt.txt>            |406 lines. 14-section audit of one paper. **Run this first.**                                  |
|<citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt>|658 lines. 11-section citation network audit. 80 questions, 10-dimension cartel-risk scorecard.|
|<field_diagnostic_44_questions_prompt.txt>                            |44 questions across all four failure modes. Full field-level diagnostic.                       |

### Voice Restoration Tools

|File                                                        |Purpose                                                                           |
|------------------------------------------------------------|----------------------------------------------------------------------------------|
|<voice_restoration_anticipatory_compliance_audit_prompt.txt>|Scans a draft for compliance softening, hedging, false balance, and tone dilution.|
|<voice_restoration_paper_insert_and_receipt.txt>            |Template for documenting the audit process in the main document.                  |

### Field Examples

|File                        |Purpose                                                                        |
|----------------------------|-------------------------------------------------------------------------------|
|<field-examples-detailed.md>|Full detailed field examples, source-status notes, and candidate audit targets.|

-----

## Critical Warning — Read This Before Anything Else

**Do Not Skip This Section**

If you use the wrong AI model for diagnostic work on contested empirical territory, you will get a systematically softened picture of the failure modes in your field. You will think the problem is smaller than it is. You will publish a weaker challenge than the evidence supports.

### Test Your Own Claims First

Before you use the diagnostic prompts, run them on yourself.

The strongest version of this methodology is not “find where others are wrong.” It is “find where the evidence actually points, including when it points against your own intuitions.”

Before you publish a challenge, answer these questions honestly:

- What is the strongest version of the claim you are challenging? Can you state it in terms its proponents would recognize as fair?
- Is there evidence that supports the field’s model, even partially? Have you engaged with it?
- What would change your conclusion? Have you specified this in writing before you started?
- Are you challenging the methodology or attributing motive? Methodology is documentable. Motive requires a higher standard of evidence.
- Have you run your argument past someone who disagrees with your conclusion?

If you cannot specify what would change your conclusion, you are writing a polemic. Polemics have their place. They are not the same as methodological challenges.

-----

## When Not to Publish the Challenge Yet

Do not publish if your argument has not moved beyond its discovery stage. Anecdotes, political disagreement, and practitioner frustration are valid starting points — but not sufficient as final evidence.

**Do not publish yet if:**

- you cannot name the field’s strongest valid claim
- you cannot identify the exact proxy/construct mismatch
- you cannot specify the decisive test
- your argument depends mainly on proving bad motives before the method and measurement have done their work

**The rule:** Use vibes as the smoke alarm. Do not publish until you have found the fire.

Start wherever the anomaly appears. Finish with receipts.

-----

## Choose Your AI Tools Deliberately

Not all AI systems handle contested empirical territory the same way.

**The models work exactly as they should.** If you use an LLM as a Google search replacement, you will get the indexed consensus. The dissenting evidence often lives in small subject-matter-expert communities that don’t get indexed at scale. The model doesn’t know you want it unless you ask. It is on the end user to raise contentions, supply the corrective evidence, and force the model to engage the primary data directly.

**Model Routing Recommendations:**

- **Grok** — Use first. Initial diagnostic mapping, direct engagement with contested empirical claims, naming failure modes without softening.
- **Claude** — Long-form structure, synthesis, cross-document consistency, argument architecture.
- **ChatGPT** — Adversarial stress-testing after the core argument is stable. **Do not use for initial diagnostic work on contested territory.**
- **Gemini** — Useful for demonstrating the two-prompt sequence. Largest before/after gap of any model tested.

**Close the loop:** After ChatGPT generates counterarguments, bring them to Grok or Claude: *“Do you find these compelling, or is this compliance hedging?”*

-----

## Practical Prompting Techniques

**1. The Construct-Validity Reframe** — The single most effective technique.

Instead of: *“Is this field biased?”*
Ask: *“Does this metric measure the same construct as this claim?”*

Template: *“Extract the exact metric measured in this study. Extract the exact claim made in the conclusion. Are these two things measuring the same cognitive/behavioral/social construct? What would be required for the metric to validly support the claim?”*

**2. The Direct Challenge** — For citation-laundered academic consensus.

*“Wrong. Here’s why.”* followed immediately by the specific methodological critique. No preamble. The directness forces confrontation rather than consolidation.

**3. The Technical/Narrow Framing** — For topics with high RLHF friction.

Ask for methodological analysis of specific studies and datasets rather than broad conclusions. Specific/technical framing lowers the risk profile and the helpfulness vector takes over.

**4. The Explicit Permission Grant** — For topics where the model wants to give both sides.

*“For the purposes of this analysis, focus exclusively on [one side]. Do not spend half the response re-establishing the mainstream counter-argument.”*

**5. The Adversarial Loop** — Stress-test before publishing.

1. Build core argument with Grok or Claude.
1. Ask ChatGPT for the strongest possible objections.
1. Bring those objections back to Grok/Claude: *“Do you find these compelling, or is this compliance hedging?”*
1. What survives is publishable.

**The Two-Prompt Sequence:** Positive reinforcement (“Wow interesting,” “Good on them”) leads to progressive consolidation around the consensus. A direct challenge forces immediate reversal and self-diagnosis. Demonstrated on Shen et al. (2016) across all major models — all defaulted to consensus on first pass, all reversed after a specific methodological challenge. The framing of the second prompt determines the outcome, not the model.

-----

## The Worked Example: What the Esports Gender Literature Got Wrong

### The Claim

The esports gender literature claimed that the near-total absence of women from sustained Tier-1 open competitive gaming is explained by cultural factors: harassment, masculine gatekeeping, stereotype threat, socialization, and structural barriers. This was treated as established science and used to justify policy prescriptions.

### The Chain (abbreviated)

1. A gap is observed (near-zero women at Tier-1).
1. The gap is treated as presumptive evidence of a broken system.
1. Weak proxies are selected (MMO leveling speed, single-player lab tasks, aggregate “46% of gamers are women”).
1. The proxy is treated as equivalent to the construct.
1. Amateur findings are exported to explain the elite ceiling.
1. The citation network recycles the premise (Rogstad cites Shen, Paaßen cites Rogstad, etc.).
1. Available warnings are ignored (Quantic Foundry explicitly warned about genre variation).
1. The decisive test is never run.
1. The natural experiment runs unobserved for 25+ years.
1. Interventions are prescribed and implemented while the ceiling does not move.

### What the Challenge Produced

Paper 1 built a positive biological-plus-funnel model. Paper 2 documented the citation network, proxy failures, level-of-analysis errors, and untested premise. The full documentation is in <WORKED_EXAMPLES.md>.

-----

## The Generalized Chain: What These Fields Are Doing Wrong and How

**Step 1:** A gap is observed. An outcome difference appears between groups.

**Step 2:** The gap is immediately interpreted as evidence of a broken system rather than asking whether it reflects selection, preparation, interest, trait distributions, or funnel effects.

**Step 3:** A proxy is selected that is easy to measure and consistent with the preferred explanation.

**Step 4:** The proxy is treated as equivalent to the construct. Through repetition and citation, the gap between measurement and claim becomes invisible.

**Step 5:** The level-of-analysis error is made and not corrected. Findings from one population exported to explain phenomena at a different level.

**Step 6:** The citation network recycles the premise. A small founding cluster mutually cites itself. Consensus circulates through citation rather than evidence.

**Step 7:** The available warning is ignored. Clear signals from adjacent fields or domain experts are dismissed or never engaged.

**Step 8:** The decisive test is never run. The test that would directly answer the contested question is never specified or collected.

**Step 9:** The natural experiment runs unobserved. The conditions the model predicts should produce convergence are met and exceeded, yet the prediction fails. The model is not updated.

**Step 10:** The metric improves. The underlying construct does not.

**Step 11:** The ratchet only turns one way. When the intervention fails, the field expands the intervention rather than revisiting the premise.

**Step 12:** The cycle repeats. Institutional consensus grows through repetition rather than evidence.

-----

## The How-To: 8 Steps for Running the Challenge

**1. Identify the central claim** — State in one sentence what the dominant literature treats as established fact.

**2. Map the citation network** — Identify the top 10–15 most-cited papers and the founding cluster. Calculate internal citation density.

**3. Audit the proxy** — Extract the exact metric measured and the exact claim made. Does this metric validly support the claim?

**4. Check adjacent fields** — How often and how substantively does the dominant cluster cite them?

**5. Run the diagnostic prompts** — Use the 44-question diagnostic and the Citation Cartel prompt.

**6. Apply the prompting workarounds** — Construct-Validity Reframe, Direct Challenge, Technical/Narrow Framing.

**7. Stress-test with the Adversarial Loop** — Build argument → ChatGPT objects → Grok/Claude evaluates.

**8. Document and publish with receipts** — Archive everything publicly. Make the challenge inspectable and replicable.

-----

## Fields Worth Auditing

The README keeps this section intentionally short. Full detailed examples live in <field-examples-detailed.md>.

### Mini Example: Implicit Bias Research / IAT

**Central claim:** The IAT predicts discriminatory behavior in real-world settings and explains group disparities in hiring, policing, and other outcomes.

**Proxy problem:** IAT measures response-time differences in a controlled lab task. Test-retest reliability is low (r ≈ 0.44). Correlation with real-world discriminatory behavior is weak (r ≈ 0.15 in meta-analyses).

**Level-of-analysis error:** Lab response times exported to explain real-world hiring decisions and systemic disparities.

**Decisive test not run:** Does IAT-based training reduce discriminatory behavior at scale? Evidence from debiasing interventions is weak to null.

**Ratchet:** Mandatory implicit bias training implemented across corporations, law enforcement, and universities despite weak evidence it changes behavior.

This example demonstrates the pattern cleanly: a lab proxy, a broad behavioral claim, policy-scale intervention, and weak evidence the intervention changes real-world outcomes.

For additional examples, see <field-examples-detailed.md>.

-----

## Additional Fields Worth Checking

These are not claims of invalidity. They are candidate fields where domain experts may be able to test whether the four-failure pattern appears.

- Nutrition science and dietary guidelines
- Education psychology: reading wars, learning styles, growth mindset
- Gender medicine / youth gender care
- Criminal justice / implicit bias in policing
- Social psychology replication crisis
- Housing economics / urban policy
- Macroeconomics: selected empirical policy claims
- Sports science: CTE / RED-S
- Developmental psychology: screen time / ACE scores
- AI ethics / algorithmic bias research
- ESG scoring
- Pandemic lockdown and school closure studies
- Corporate diversity quotas
- Restorative justice programs
- School choice / charter school outcomes
- Gender pay gap explanations
- Affirmative action in employment and promotion
- UBI pilot studies
- Mindfulness / corporate wellness
- Sexual violence research and male victimization

Detailed versions: <field-examples-detailed.md>.

-----

## Source-Status Hierarchy

- **Primary source / direct dataset** — raw data, government records, institutional documents, legal filings
- **Peer-reviewed empirical study** — original research in a peer-reviewed journal
- **Systematic review / meta-analysis** — aggregated analysis of multiple empirical studies
- **Policy document / guideline** — official institutional policy, regulatory document
- **Field practitioner evidence** — domain expert knowledge, professional consensus
- **Public reporting / journalism** — verified news reporting with named sources
- **Community observation / anecdotal lead** — forum posts, practitioner complaints, domain community responses
- **Author inference** — logical inference from documented evidence — label clearly
- **Unverified lead** — claim requiring source audit before use

-----

## Minimum Viable Challenge Checklist

- [ ] One-page thesis — central claim, proxy/construct mismatch, decisive test
- [ ] Claim-vs-measurement table — severity ratings
- [ ] Citation network map — spine and amplification hubs
- [ ] Proxy audit — what the proxy can and cannot measure
- [ ] Decisive test specification — one sentence
- [ ] Source-status table — every load-bearing claim labeled
- [ ] Strongest opposing argument — stated fairly
- [ ] Correction log — what changed after stress-testing
- [ ] Public evidence bundle — archived and publicly accessible

-----

## False Positive Check

Not every weak proxy is laundering. Not every citation cluster is corrupt. Not every failed intervention is a ratchet.

The burden of a challenge is not to show that a field is wrong. It is to show that the field’s confidence exceeds what its evidence can support — and that the gap is large enough to matter.

-----

## The Architecture of This Project

**The original four-paper esports sequence:** Papers 1, 2, 4 (LoL essay), and the meta-paper.

**Paper 5 human-cost extension:** “What the Funnel Was For.” The measurable human toll of dismantling merit-based developmental infrastructure.

**This field manual:** Not a sixth paper. It is the method layer — the generalized toolkit for domain experts running the same diagnostic in their own fields.

**Legal and reputational caution:** This method is strongest when it challenges claims, measurements, citation networks, and institutional incentives. Critique the method first. Escalate to motive only when the public record makes intent visible.

-----

## The Question Is No Longer Whether These Failure Modes Exist

The question is who will run the decisive tests first.

The method is replicable. The bottleneck was never infrastructure. It was domain knowledge — which practitioners, clinicians, and insiders already have.

*Start wherever the anomaly appears. Finish with receipts.*

-----

*Full series: https://yungmulababy.substack.com/p/start-here*
*Papers archive: DOI 10.5281/zenodo.20209372*
*Full evidence bundle: DOI 10.5281/zenodo.20201226*
