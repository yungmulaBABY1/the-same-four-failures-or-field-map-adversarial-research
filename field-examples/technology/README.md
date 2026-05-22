# Field Examples — Technology / Data Center Infrastructure

**Artifact type:** Worked example / demonstration artifact
**Purpose:** Demonstrate prompt output and audit workflow on activist propaganda claims about data center infrastructure
**Author role:** Claim selection, domain framing, adversarial review, final judgment
**AI role:** Structured audit generation, synthesis, counterargument generation, formatting

-----

This folder contains the full audit trail for the data center infrastructure worked example. It applies the adversarial research toolkit to a set of circulating activist infographics making empirical claims about data centers — power bills, cancer/death tolls, water consumption, noise, heat islands, and the Palantir government contracts graphic.

This example demonstrates that the toolkit applies equally to activist propaganda as to academic consensus. Same prompts, same failure modes, different domain. The toolkit is not politically selective — it asks the same questions regardless of which direction the overclaim is pointing.

## Documents in this folder

|Document                                   |Description                                                                                                                                     |
|-------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
|datacenter_doom_infographic_paper.md       |**Final paper** — post voice restoration, full seven-claim audit with Gallup, Sanders/AOC, visual rhetoric, force multiplier, and irony sections|
|datacenter_01_construct_validity_audit.md  |Construct validity audit output for all five infographic claims                                                                                 |
|datacenter_02_oppositional_counter_audit.md|Oppositional counter-audit — what the other side has, honest concessions                                                                        |
|datacenter_03_voice_restoration_audit.md   |Voice restoration pass on the final paper                                                                                                       |

## Prompts used

All prompts are available in the repository root:
https://github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research

## Key findings

- **Power bills (267%):** Cherry-picked extreme outlier. Documented impact in data-center-heavy territories is low single-digit percentages.
- **Cancer/deaths:** 2030 projections from marginal grid emissions presented as current death toll. Every qualifier stripped.
- **Water drain:** Real localized stress in arid regions during drought. Denominator (0.2-0.4% of national freshwater) omitted entirely.
- **Noise:** Real fence-line nuisance. The “2-mile pure hell” claim does not survive basic acoustic physics.
- **Heat islands:** 0.5-2°F near the facility. The “+16°F up to 6 miles” claim does not appear in any reputable study.
- **Palantir:** Normal government software contracts dressed in conspiracy aesthetics. Classic motte-and-bailey.
- **Nobody voted:** Not an empirical claim. A rhetorical frame designed to make any technology opposition feel like a democratic mandate.

## How to replicate

1. Take the foundational claim or infographic
1. Run the prompts in the recommended sequence (see README.md in root)
1. Bring your own domain knowledge conversationally between steps
1. The prompts structure the audit. The domain knowledge determines which claims are load-bearing.
