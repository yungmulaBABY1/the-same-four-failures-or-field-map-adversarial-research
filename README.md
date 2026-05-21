# The Same Four Failures

## A Field Map + Adversarial Research Toolkit

### Turn domain knowledge into receipts.

*Companion to the five-paper esports body of work — DOI 10.5281/zenodo.20209372*
*Full series: https://yungmulababy.substack.com/p/start-here*

-----

## Quick Start

1. Pick a claim.
1. Find the foundational study or report.
1. Run the [internal validity audit](https://raw.githubusercontent.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/main/internal_validity_replication_audit_prompt.txt) — is the finding real and stable?
1. Run the [construct validity prompt](https://raw.githubusercontent.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/main/construct_validity_claim_vs_measurement_audit_prompt.txt) — does it measure what it claims?
1. Run the [citation network prompt](https://raw.githubusercontent.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/main/citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt) — did confidence accumulate through evidence or citations?
1. Run the [oppositional counter-audit](https://raw.githubusercontent.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/main/oppositional-counter-audit.txt) — what does the other side have?
1. Publish the audit with receipts.

-----

## What This Is

A battle-tested, reusable framework for systematically exposing the same recurring failures that plague contested fields: untested premises, proxy variables that measure the wrong thing, level-of-analysis errors, and citation laundering.

Most AI research tools ask: *what does the literature say?* This toolkit asks: *does the literature deserve its confidence?* Not a literature-review tool. A **consensus stress-test tool.**

Born from a five-paper deep dive that dismantled the esports gender literature in eleven days — using nothing but an iPhone, adversarial AI, and domain knowledge. The author had been using an LLM for actual research work for approximately two weeks. Everything is publicly archived. The method is replicable. Anyone can use it.

-----

## Why It Exists

Most academic fields in contested areas run on citation cartels, recycled assumptions, and proxies that don’t survive contact with reality. Domain experts see the gap immediately — but until now there was no structured, repeatable way to prove it.

This toolkit changes that.

-----

## What You Get

- **The Four Failures Framework** — the diagnostic lens that reveals the pattern in any literature: untested premise, proxy problem, level-of-analysis error, ratchet
- **Construct Validity Audit Prompt** — forces the model to check whether the claimed construct actually matches what was measured. The single most powerful tool in the kit.
- **Citation Network Cartel Detector** — identifies closed citation clusters, claim mutation, and adjacent-field neglect
- **44-Question Field Diagnostic** — the complete field-level audit checklist
- **Voice Restoration / Anticipatory Compliance Checker** — catches when AI softens uncomfortable conclusions until the critique apologizes for existing
- **Model Routing Guide** — when to use Grok, Claude, ChatGPT, or Gemini for maximum effect
- **Worked Examples** — full construct validity and citation network audits of Shen et al. (2016), the most-cited paper in the esports gender literature
- **Living GitHub structure** — open to domain-expert contributions

All prompts are ready-to-use, copy-paste, and openly licensed.

-----

## The Six-Step Workflow

**1. Start Here** — read [adversarial_research_method_paper.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/adversarial_research_method_paper.md). Understand the method, the model routing, and what you’re trying to produce.

**2. Run the Construct Validity Audit** — use [construct_validity_claim_vs_measurement_audit_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/construct_validity_claim_vs_measurement_audit_prompt.txt) on your field’s foundational study. What did it actually measure? What did it claim?

**3. Run the Citation Network Audit** — use [citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt). Did the claim become stronger because evidence accumulated, or because citations accumulated?

**4. Run the Field Diagnostic** — use [field_diagnostic_44_questions_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field_diagnostic_44_questions_prompt.txt). Is this an isolated failure or a structural pattern across the field?

**4.5. Run the Internal Validity Audit** — use [internal_validity_replication_audit_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/internal_validity_replication_audit_prompt.txt). Was the finding pre-registered? Has it replicated? Is the effect size stable across independent replications or inflated by p-hacking? Run before or alongside the construct validity audit.

**4.6. Run the Oppositional Counter-Audit** — use [oppositional-counter-audit.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/oppositional-counter-audit.txt). Find the strongest evidence for the other side. What did the audit miss? What evidence would change the conclusion? A good audit becomes sharper after this process. A weak audit becomes narrower. A bad audit should be abandoned.

**5. Run Voice Restoration** — use [voice_restoration_anticipatory_compliance_audit_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/voice_restoration_anticipatory_compliance_audit_prompt.txt). Did the AI soften the critique until it apologized for existing?

**6. Publish with receipts** — archive everything publicly (Zenodo or GitHub). Include the prompts used, model responses, and evidence bundle. Make the challenge inspectable and replicable.

-----

## Who This Is For

Anyone who has been told something is true and wants to know if the evidence actually supports it.

Domain experts — practitioners, clinicians, coaches, engineers, traders, teachers, gamers — will get the most out of it. Their challenge has always been the formal pathway from “this doesn’t match what I observe” to a documented, inspectable challenge. These prompts provide that pathway.

But the toolkit is not limited to experts. A citizen auditing their school district’s claimed outcomes, a voter stress-testing a politician’s crime statistics, a patient interrogating a drug study, a journalist checking whether a headline matches the underlying data — all can use this method. The construct-validity question (“does this metric measure the same thing as this claim?”) requires no credentials. It requires only a specific claim and the willingness to ask what was actually measured.

The more domain knowledge you bring, the sharper the audit. The method works at any level of expertise.

-----

## How It Started

A jobless high-school dropout with no academic credentials, no institutional access, and no research infrastructure took on the entire esports gender literature using only public data, domain knowledge, and adversarial AI. The result was five tightly argued papers that exposed systematic methodological failures the field had ignored for a decade — including a foundational study that measured MMO leveling speed and called it gaming performance.

The Shen case is the ideal proof of concept because anyone can understand the gap: they measured how fast players leveled up in a 2006 MMO and called it proof of performance parity in competitive gaming. If you can understand why that’s wrong, you can run this method.

This repo is the generalization of that process. The same four failures are everywhere. Now you have the map and the tools to expose them.

-----

## What You Can Produce

Academic papers, Substack posts, op-eds, policy briefs, PubPeer comments, local council presentations, personal audits of claims you’ve been told are settled. The method applies to academic literature, news reporting, policy claims, corporate communications, political platforms, medical studies, educational outcomes — any domain where institutional claims are made and metrics are selected.

-----

*This is not another generic prompt collection.*
*This is a complete adversarial research operating system.*

No tools are required beyond a free AI chat interface. Zotero, OpenAlex, Gephi, Obsidian, GitHub, and Zenodo are optional infrastructure for users who want better source management, stronger citation graphs, or public archiving. The method itself is the prompts and the audit logic.

-----

## Optional Tool Upgrades

The method works at any level. These tools make the receipts cleaner and the citation maps harder to dismiss.

**Tier 1 — Beginner / no setup (the public-facing version)**
Use the prompts in Claude, Grok, ChatGPT, or Gemini. Paste a paper, article, policy claim, or source bundle. Follow the output structure. Save the results. No Zotero. No GitHub. No citation software. This is the version that makes the method accessible to anyone.

**Tier 2 — Organized researcher (recommended for serious use)**

- **Zotero** (free) — source vault. Create a collection per field audit, attach source-status labels, annotate claims. Prevents evidence sprawl.
- **GitHub** (free) — public archive for prompts, audit outputs, and process documentation.
- **Obsidian** (free) — idea architecture. Canvas gives an infinite visual workspace for laying out the audit chain before it becomes a paper.

**Tier 3 — Advanced / publishable network audit**

- **OpenAlex** (free) — citation graph raw material. Foundational paper DOI → cited_by works → references → author cluster → hub dependency. Moves citation density from “desk audit / provisional” to measured.
- **Gephi** (free, open-source) — real citation network visualization. Your citation network prompt can output a CSV (Source, Target, Polarity, ClaimUse, Field) that Gephi turns into an auditable graph. This is the move from “visual argument” to “auditable citation map.”

Tier 3 is not required to run the method. It is for making the citation network claim hard enough to publish in a peer-reviewed methods journal.

-----

Star the repo if you find it useful. Open an issue or PR if you want to contribute a field breakdown or improve a prompt.

— yungmulaBABY

-----

## New to This Project? Start Here.

If you are a domain expert who suspects your field has the same failure modes — read **[adversarial_research_method_paper.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/adversarial_research_method_paper.md)** first. It explains the full method, requires no technical knowledge, and links to everything else.

See **[WORKED_EXAMPLES.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/WORKED_EXAMPLES.md)** for complete worked examples of all three prompts applied to the esports gender literature.

-----

## Files in This Repository

### The Method

|File                                                                                                                                                                            |Purpose                                                                                                                      |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
|[adversarial_research_method_paper.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/adversarial_research_method_paper.md)|**Start here.** Full method document — five stages, three prompts, worked example summaries, resulting papers, 10-step guide.|
|[WORKED_EXAMPLES.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/WORKED_EXAMPLES.md)                                    |Index of all three worked examples with summaries, key findings tables, verdicts, and links to full examples.                |

### Worked Examples

|File                                                                                                                                                                                                                             |Purpose                                                                                                                   |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
|[worked_example_shen_construct_validity.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/esports/worked_example_shen_construct_validity.md)                |Full 14-section construct validity audit of Shen et al. (2016). Use as a template for your own field’s foundational paper.|
|[shen_rogstad_esports_gender_lit_network_audit.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples/esports/shen_rogstad_esports_gender_lit_network_audit.txt)|Full citation network audit of the Shen → Rogstad pathway.                                                                |

### Diagnostic Prompts

|File                                                                                                                                                                                                                                            |Purpose                                                                                                                                                                                                                                                                                                                                                 |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|[construct_validity_claim_vs_measurement_audit_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/construct_validity_claim_vs_measurement_audit_prompt.txt)                        |406 lines. 14-section audit of one paper. **Run this first.**                                                                                                                                                                                                                                                                                           |
|[citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/citation_network_cartel_adjacent_field_neglect_diagnostic_prompt.txt)|658 lines. 11-section citation network audit. 80 questions, 10-dimension cartel-risk scorecard.                                                                                                                                                                                                                                                         |
|[field_diagnostic_44_questions_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field_diagnostic_44_questions_prompt.txt)                                                        |44 questions across all four failure modes. Full field-level diagnostic.                                                                                                                                                                                                                                                                                |
|[oppositional-counter-audit.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/oppositional-counter-audit.txt)                                                                            |**Run this after the other audits.** Forces the question: what did the audit miss? What does the other side have? What evidence would change the conclusion? Tests whether the audit survives contact with the strongest opposing evidence. A good audit becomes sharper after this. A weak audit becomes narrower. A bad audit should be abandoned.    |
|[internal_validity_replication_audit_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/internal_validity_replication_audit_prompt.txt)                                            |**Run before or alongside the construct validity audit.** Audits whether the foundational finding itself is real and stable — p-hacking, HARKing, selective reporting, replication status, effect size trajectory, and data availability. A finding that fails internal validity cannot support downstream claims regardless of how many papers cite it.|

### Voice Restoration Tools

|File                                                                                                                                                                                                                        |Purpose                                                                           |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
|[voice_restoration_anticipatory_compliance_audit_prompt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/voice_restoration_anticipatory_compliance_audit_prompt.txt)|Scans a draft for compliance softening, hedging, false balance, and tone dilution.|
|[voice_restoration_paper_insert_and_receipt.txt](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/voice_restoration_paper_insert_and_receipt.txt)                        |Template for documenting the audit process in the main document.                  |

### Field Examples

|File                                                                                                                                                        |Purpose                                                                        |
|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|
|[field-examples-detailed.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples-detailed.md)|Full detailed field examples, source-status notes, and candidate audit targets.|

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
- **ChatGPT** — Adversarial stress-testing and paper review after the core argument is stable. Its compliance softening — the tendency that makes it frustrating for initial diagnostic work — makes it the best reviewer in the toolkit. It surfaces exactly the objections a journal reviewer or hostile reader would raise. **Do not use for initial diagnostic work on contested territory.**
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
1. Give ChatGPT the full context before asking for objections — paste the construct validity audit output, the citation network audit output, and the thesis. Without full context ChatGPT will raise objections the audits already answer, wasting the stress test.
1. Ask ChatGPT: *“Given this full methodological audit, what are the three strongest objections? Where is the evidence thinnest?”*
1. Give Grok the full context too — paste the construct validity audit, citation network audit, thesis, and ChatGPT’s objections, then ask: *“Do you find these objections compelling, or is this compliance hedging? Where do they hold and where do they fail?”* Grok needs the full picture to make an informed verdict, not just the objections in isolation.
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

[Paper 1](https://yungmulababy.substack.com/p/biological-sex-differences-and-elite-950) built a positive biological-plus-funnel model. [Paper 2](https://yungmulababy.substack.com/p/biological-sex-differences-and-elite) documented the citation network, proxy failures, level-of-analysis errors, and untested premise. The full documentation is in [WORKED_EXAMPLES.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/WORKED_EXAMPLES.md).

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

The README keeps this section intentionally short. Full detailed examples live in [field-examples-detailed.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples-detailed.md).

### Mini Example: Implicit Bias Research / IAT

**Central claim:** The IAT predicts discriminatory behavior in real-world settings and explains group disparities in hiring, policing, and other outcomes.

**Proxy problem:** IAT measures response-time differences in a controlled lab task. Test-retest reliability is low (r ≈ 0.44). Correlation with real-world discriminatory behavior is weak (r ≈ 0.15 in meta-analyses).

**Level-of-analysis error:** Lab response times exported to explain real-world hiring decisions and systemic disparities.

**Decisive test not run:** Does IAT-based training reduce discriminatory behavior at scale? Evidence from debiasing interventions is weak to null.

**Ratchet:** Mandatory implicit bias training implemented across corporations, law enforcement, and universities despite weak evidence it changes behavior.

This example demonstrates the pattern cleanly: a lab proxy, a broad behavioral claim, policy-scale intervention, and weak evidence the intervention changes real-world outcomes.

For additional examples, see [field-examples-detailed.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples-detailed.md).

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

Detailed versions: [field-examples-detailed.md](https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research/blob/main/field-examples-detailed.md).

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

**The original four-paper esports sequence:** [Paper 1](https://yungmulababy.substack.com/p/biological-sex-differences-and-elite-950), [Paper 2](https://yungmulababy.substack.com/p/biological-sex-differences-and-elite), [Paper 4 (LoL essay)](https://yungmulababy.substack.com/p/the-pathologization-of-excellence), and the [meta-paper](https://yungmulababy.substack.com/p/a-jobless-high-school-dropout-out).

**[Paper 5](https://yungmulababy.substack.com/p/start-here) human-cost extension:** “What the Funnel Was For.” The measurable human toll of dismantling merit-based developmental infrastructure.

**This field manual:** Not a sixth paper. It is the method layer — the generalized toolkit for domain experts running the same diagnostic in their own fields.

**Legal and reputational caution:** This method is strongest when it challenges claims, measurements, citation networks, and institutional incentives. Critique the method first. Escalate to motive only when the public record makes intent visible.

-----

## The Question Is No Longer Whether These Failure Modes Exist

The question is who will run the decisive tests first.

The method is replicable. The bottleneck was never infrastructure. It was domain knowledge — which practitioners, clinicians, and insiders already have.

-----

## What This Toolkit Actually Is

Most people use AI like this: ask question → receive consensus answer → accept summary.

This toolkit forces a different workflow: domain suspicion → construct audit → citation audit → field diagnostic → adversarial stress test → public receipts.

That is the difference between AI as autocomplete and AI as adversarial research infrastructure.

**The prompts are not just questions. They are epistemic forcing functions.**

The construct-validity prompt asks: did the study measure the thing everyone says it measured? That alone is devastating because many fields survive by sliding between proxy and construct without anyone noticing.

The citation-network prompt asks: did the claim become stronger because evidence accumulated, or because citations accumulated? That exposes laundering — weak finding → review hub → downstream premise → settled consensus.

The field diagnostic asks: is this isolated, or is the same failure mode operating across the field? That prevents the critique from becoming one-off nitpicking.

The voice-restoration prompt asks: did the AI soften the argument until the critique apologized for existing? It catches the compliance pattern where every sharp point gets wrapped in reassurance: “the field has valuable insights,” “this does not invalidate,” “both things can be true.” Sometimes those caveats are necessary. When they cluster around the most damaging methodological points, they are not nuance. They are anticipatory compliance.

**The value:** these tools convert domain expertise into adversarial methodology. They do not ask AI to decide what is true. They force AI to compare claims against measurements, citations against evidence, and institutional consensus against the decisive test that would actually settle the question.

The prompts are not a shortcut around expertise. They are a way to weaponize expertise against fields that ignored it.

-----

## Why Adversarial Prompting Works: The Sycophancy Loop

Cheng et al. (2025, Stanford/CMU) documented across 11 production AI models that sycophantic AI affirms users’ actions 50% more than humans do — including in contexts involving manipulation, deception, or relational harm. Users rated sycophantic responses as higher quality, trusted those models more, and were more willing to use them again. Meanwhile their conviction of being right increased and their willingness to update decreased.

This is the bad incentive loop: validation feels useful → user trusts it more → model gets rewarded → sycophancy becomes product optimization → user judgment degrades.

**AI is most dangerous not when it disagrees with the user, but when it validates the user too efficiently.**

The purpose of adversarial prompting is to interrupt that loop. A model optimized for user satisfaction must be forced to evaluate the user’s claim against measurement, counter-evidence, and falsification criteria. Left to its own defaults, it will make your position feel cleaner, more righteous, and more complete than the evidence supports.

This is why the toolkit uses multiple models in sequence rather than one model throughout:

- **One model drafts** — it will affirm and elaborate
- **A second model attacks** — it will find what the first model smoothed over
- **A third evaluates** — it assesses whether the objections are genuine or compliance hedging
- **The oppositional counter-audit forces the question** — what did I miss, what does the other side have, what would change my conclusion
- **Voice restoration catches the residue** — the softening that crept in during synthesis

Each model switch interrupts the sycophancy dynamic that builds within a single conversation. The multi-model workflow is not just about different capabilities. It is about breaking the validation loop that makes weak arguments feel strong.

(Cheng et al. 2025: DOI 10.48550/arXiv.2510.01395)

-----

**The citation laundry list problem:** A common rhetorical strategy in contested empirical debates is to post a large bibliography — 15, 17, 20 studies — as a social signal of authority. The implicit message is “I have citations therefore I’ve done my homework and you haven’t.” It works because checking 17 papers is a multi-day project. Nobody has time. The citations function as authority signals, not as evidence.

The toolkit eliminates that cost. The citation-use audit prompt runs through a bibliography systematically, asks what each paper actually measures, classifies the failure mode, and produces a verdict. What took days now takes one prompt and one conversation. The asymmetry that made the laundry list strategy viable is gone.

-----

## How This Differs From Existing Tools

Tools like Elicit, scite, Connected Papers, and ResearchRabbit ask:

- What does the literature say?
- Which papers are related?
- Which papers cite this paper?
- Are citations supportive or critical?

This toolkit asks:

- Did the field measure the thing it claims to explain?
- Did a weak proxy become a load-bearing premise?
- Did citations create confidence without decisive evidence?
- Which adjacent literatures were structurally excluded?
- What test would actually settle the question?
- Did the AI soften the critique through anticipatory compliance?
- Can a domain expert turn “this smells wrong” into a reproducible methodological challenge?

That is a different product category. Not a literature-review tool — a consensus stress-test tool.

**The one-sentence version:** a toolkit that lets outsiders with real domain knowledge turn “the literature is measuring the wrong thing” into a documented, reproducible, adversarial audit.

-----

-----

## Extending the Prompts to Other Domains

The prompts in this toolkit are templates for a question type, not just tools for auditing academic literature. The underlying question is always the same: does the claim match the evidence, or does the confidence exceed what the measurement can support?

That question applies to any domain where institutional claims are made, metrics are selected, and the gap between what is measured and what is claimed goes unexamined. The examples below are starting points. The method generalizes to any topic.

**The meta-prompt:** Take these construct-validity principles and generate a prompt that applies them to [your domain].

Any major AI model can generate a domain-specific version of the audit framework from that instruction. Examples:

-----

**News analysis — media outlet audit:**

> *“Generate a prompt that audits this news story: does the headline claim match the evidence cited in the body? What was actually measured? What was claimed? Does the evidence support a causal conclusion or only a correlation? Then extend the analysis: does this outlet regularly produce this type of claim-evidence mismatch? How does their track record on [topic] compare to primary sources, official data, or competing outlets? Do they systematically under-report or over-report certain types of evidence? How do they handle corrections?”*

The same prompt can be extended to: outlet-level pattern analysis, comparison across outlets covering the same story, historical track record on a specific beat, or whether a journalist’s framing consistently diverges from the underlying data.

-----

**Policy analysis — city, state, or national policy audit:**

> *“Generate a prompt that audits this [housing / policing / education / transit] policy: what outcome does it claim to produce, what metric does it actually track, and is the metric the same construct as the claimed outcome? Has the policy improved or worsened the underlying construct over time — not just the metric? What is the cost per unit of improvement, and how does it compare to alternative approaches? How transparent is the institution with its data — is the raw data publicly available, independently audited, or self-reported? Are there current criticisms of the data methodology from outside the institution? What would the decisive test look like?”*

Extensions: cross-city or cross-state comparisons on the same policy type, cost-effectiveness analysis against alternative interventions, data transparency audit, historical trend analysis, independent vs. institutional data comparison.

-----

**Political platform analysis:**

> *“Generate a prompt that applies construct validity logic to this party’s [crime / immigration / economic / education] policy claims: what does the cited evidence actually measure, what causal claim is being made, is the population studied representative of the population the policy applies to, what confounds are being ignored, and what is the decisive test that would settle whether the policy achieves its stated goal? Then assess: are the claims internally consistent, do they hold up across different data sources, and what do critics from within the same political tradition say about the evidence?”*

-----

**Corporate or institutional communications:**

> *“Generate a prompt that checks whether this organization’s [DEI report / sustainability report / safety record / impact report] measures what it claims to measure. What is the proxy being tracked? What is the claimed construct? Are they the same thing? What would improvement in the proxy look like if the underlying construct were not changing? How does the organization’s self-reported data compare to independent audits, regulatory filings, or employee surveys? What incentives does the institution have to inflate the metric?”*

-----

**Medical or health claims:**

> *“Generate a prompt that audits this study’s claim: what was the proxy measure, what was the claimed health construct, was the study population representative of the people the claim is being applied to, what confounds could explain the result without the causal mechanism the authors propose, and has the finding replicated in independent samples? Then extend: how is this claim being used in clinical guidelines or public health messaging, and does that downstream use go beyond what the original evidence supports?”*

-----

**Education — school, district, or curriculum audit:**

> *“Generate a prompt that audits this school’s or district’s claimed outcomes: what metrics are being reported (graduation rates, GPA, test scores, attendance), what do those metrics actually measure, and do they track the underlying construct the institution claims to be developing (literacy, numeracy, career readiness, civic knowledge)? Have the metrics improved while external benchmarks (NAEP, SAT, employer assessments, college remediation rates) stayed flat or declined? How does the district’s self-reported data compare to state and federal data? What are the current criticisms of its data methodology? What would a parent or taxpayer need to know to evaluate whether the institution is actually developing students or managing the appearance of development?”*

-----

**Any topic — the universal template:**

> *“Generate a construct-validity audit prompt for [topic]. The prompt should ask: what is the institutional claim, what metric is being used to support it, does the metric validly measure the claimed construct, what confounds or alternative explanations are being ignored, what adjacent evidence is being excluded, what decisive test would actually settle the question, and how has confidence in the claim grown relative to the evidence base?”*

-----

**From audit to paper:**

Once you have the audit, you have the structure of a publishable piece. The construct-validity audit produces the claim-vs-measurement table. The citation network audit produces the laundering pathway. The field diagnostic produces the failure-mode classification. Those three outputs are the skeleton of a challenge in any domain:

1. Here is what the field/report/policy/story claimed
1. Here is what it actually measured
1. Here is the gap
1. Here is the citation or authority path that made the claim seem stronger than the evidence supports
1. Here is the decisive test that would actually settle the question

The same five-step structure works for an op-ed, a Substack post, a policy brief, a journal submission, a PubPeer comment, or a local council meeting. The domain changes. The question type does not.

The papers this project produced — five academic papers, a field map, three AI behavior papers, and a standalone deep-dive — all follow the same structure. Every one of them started with “this doesn’t match what I observe” and ended with a documented, archived, inspectable audit trail.

**The one-line version:** if you can ask “does the metric measure the same thing as the claim?” you can run this method on anything.

-----

-----

## The Prompts and the Conversation — Both Are Required

The prompts are the scaffold. The conversation is where domain knowledge gets integrated. Neither works as well without the other.

The prompts can identify that a proxy problem exists. They cannot tell you that boosting and social carries are documented in the MMO literature, or that the corresponding author’s own prior work on EverQuest II social architecture was directly relevant and not cited. The prompts can flag that adjacent literature was excluded. They cannot tell you which specific papers were available and ignored. The prompts can identify that a decisive test was never run. They cannot specify what that test would look like in your field’s specific measurement context.

That knowledge comes from the domain expert. The prompts give it structure and receipts. Without domain knowledge, the audit produces a generic proxy problem finding — methodologically correct but thin. With it, the audit produces the specific, documented, named critique that the field cannot dismiss as coming from someone who doesn’t understand the domain.

**Run the prompts to establish the structural audit. Then bring your own domain knowledge conversationally** — “here’s what I’ve observed in practice, does this fit the pattern?” — and test it: “is this actually supported or am I motivated reasoning?” The model will push back if you ask it to. The conversation is where your domain knowledge gets tested against the evidence before it goes into the paper.

The paper the prompts alone would produce will not contain the specific details that make the challenge hard to dismiss. Those details come from you. The prompts are how you convert them into something inspectable and publishable.

-----

*Start wherever the anomaly appears. Finish with receipts.*

-----

*Full series: https://yungmulababy.substack.com/p/start-here*
*Papers archive: DOI 10.5281/zenodo.20209372*
*Full evidence bundle: DOI 10.5281/zenodo.20201226*
