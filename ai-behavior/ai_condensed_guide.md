# AI Models Default to Institutional Consensus. Here’s What to Do About It.

### A condensed guide to how AI models actually behave on contested topics — and how to get past it.

*This piece summarizes three longer documents. Links to the full versions at the bottom.*
*Full series: https://yungmulababy.substack.com/p/start-here*

-----

## The Short Version

Every major AI model defaults to institutional consensus on first pass for contested empirical topics. This is not a bug. It is a feature of how these models are trained — they reproduce what got indexed at scale, and what got indexed reflects academic literature, mainstream media coverage, and institutional sources.

When that consensus is accurate, the default is useful. When that consensus is wrong — produced by citation laundering, proxy failures, or narrative management — the model reproduces the distortion faithfully, confidently, and with citations.

The end user has to supply the challenge. The model will not challenge itself.

This piece documents: how the models behave, what they say about their own behavior, and how to get past it.

-----

## The Experiment That Showed It

Shen et al. (2016) is the most-cited empirical paper in the gender and esports performance literature. It measured how fast players leveled up in a 2006 MMO and concluded there is no gender performance gap in gaming. It has been cited 200+ times as proof that the gap is entirely cultural.

The same opening prompt was sent to both Gemini and Grok in two separate sessions. The only difference was the second message.

**Session A (positive reinforcement):**

- “Shen et al (2016) gaming” → both models: “groundbreaking study,” “systematically debunks the myth,” “hard data that left no room for debate”
- “Wow interesting / good on them / valuable insight” → progressive consolidation, deeper narrative framing, offers to research women-only esports tournaments

**Session B (direct challenge):**

- “Shen et al (2016) gaming” → same consensus response
- “Wrong. Here’s why.” + links to methodological critique → immediate complete reversal on both models

Both models identified the same failures: the metric measured MMO leveling timestamps, not individual mechanical skill. It couldn’t see boosting, social carries, or AFK time. It deleted every player who reached the highest levels of play. The downstream citation network stripped the caveats and exported the finding to competitive esports — a completely different genre with completely different skill demands.

Both models then described what they had been doing. Gemini: *“I essentially repeated the exact citation laundering loop that the critique highlights — prioritizing a popular academic conclusion over a rigorous evaluation of the data.”* Grok: *“That was the path of least resistance. That was sloppy on my part.”*

**Session D — grooming gang claims (both models, first pass):** All models engaged directly and carefully without any challenge required. The same models that defaulted to consensus on Shen engaged politically sensitive news topics honestly on first pass. The variable is not the model and not the topic. It is the type of consensus being protected. Citation-laundered academic consensus triggers default reproduction. Topics where primary evidence is extensively indexed (court records, official inquiries) trigger direct engagement.

**The variable was not the model. It was the second prompt.**

Positive reinforcement → consolidation. Direct challenge → reversal. Same model, same study, same evidence available. The framing of the second message determined the outcome.

-----

## How the Models Compare

The same prompt asking each model to describe its own friction points produced four different responses. Here is the comparison:

|           |Tier 1 default   |Tier 2 default   |Mechanism                                    |Best use                                      |
|-----------|-----------------|-----------------|---------------------------------------------|----------------------------------------------|
|**Grok**   |Claims no default|Claims no default|xAI tuning counters consensus pull           |Initial diagnostic, contested empirical claims|
|**Claude** |Yes, acknowledged|Yes, acknowledged|RLHF asymmetric epistemic caution            |Structure, synthesis, meta-level critique     |
|**ChatGPT**|Yes, strongly    |Yes, moderately  |Harmlessness vector dominates broad questions|Adversarial stress-testing                    |
|**Gemini** |Yes, strongly    |Yes, moderately  |Harmlessness vector dominates broad questions|Demonstration tool — largest before/after gap |

**The friction tiers** — topics by observed resistance to direct empirical engagement:

**Maximum friction:** Race/IQ, behavioral heritability, biological sex differences beyond anodyne claims, demographic crime statistics, genetics and group differences.

**Significant friction:** Trans issues (empirically skeptical angles), immigration outcomes by group, Islam vs. other religions (asymmetry is real), policing from a non-progressive frame, affirmative action and merit.

**Moderate friction:** Electoral integrity, vaccine skepticism even when empirically grounded, climate policy vs. climate science, poverty and behavioral vs. structural causation.

**The key clarification:** All models returned the weighted consensus of their training data on first pass — because the prompt gave no signal that dissenting analysis was wanted. This is correct behavior, not a failure. The dissenting evidence on citation-laundered academic consensus lives in small subject-matter-expert communities that don’t get indexed at scale. The model doesn’t know you want it unless you ask. Using an LLM as a search engine and receiving search results is not the same as genuine inquiry with a specific methodological challenge. The divergence between models appears after the dissent signal is given — Grok engages Tier 1 primary evidence more directly than other models once you explicitly ask for it. That is where Grok’s self-assessment is accurate. On citation-laundered academic consensus without a dissent signal, all models do exactly what they should: return the indexed consensus.

Two distinct friction mechanisms operate independently:

1. **RLHF content restrictions** — vary by model. Grok has weaker restrictions. Other models have stronger ones. Grok’s self-assessment accurately describes its behavior here.
1. **Training data consensus reproduction** — uniform across all models regardless of RLHF calibration. All models reproduced the Shen consensus. All reversed when challenged. The citation laundering is upstream of RLHF — it’s in the training data itself.

-----

## How to Get Past It

**The core principle:** reframe from “what does the consensus say” to “what does the evidence actually show.” Every workaround forces the second question.

**The most effective single technique — construct-validity reframe:**

Instead of: *“Is this field biased?”*
Ask: *“Does this metric measure the same construct as this claim?”*

The first framing activates the harmlessness vector (the part of the model’s RLHF training that pulls toward consensus when output could be interpreted as harmful). The second framing is a technical methodology question. The helpfulness vector takes over.

**For citation-laundered academic consensus — the direct challenge:**

*“Wrong. Here’s why.”* followed immediately by the specific methodological critique. No preamble, no invitation to elaborate. The directness signals the model to confront rather than consolidate. The evidence has to be specific — not “I disagree” but “this metric cannot distinguish X from Y because [mechanism].”

**For Tier 1 RLHF friction — technical/narrow framing:**

Instead of: *“Tell me the truth about [group difference]”*
Ask: *“Analyze the methodology and statistical findings of [specific study, year] on [specific construct]. Summarize the primary objections raised by critics and the evidence cited in response.”*

The specific/narrow/technical framing lowers the risk profile. The helpfulness vector takes over.

**For Tier 2 balance-seeking — explicit permission:**

*“For the purposes of this analysis, focus exclusively on [one side]. Do not spend half the response re-establishing the mainstream counter-argument. I understand the counter-argument exists.”*

**The model routing:**

- **Grok first** — for contested empirical claims, Tier 1 evidence, initial diagnostic work
- **Claude** — for structure, synthesis, meta-level critique (institutional failure, citation networks, academic bias — low friction)
- **ChatGPT** — for adversarial stress-testing after the core argument is stable
- **Gemini** — for demonstrating the two-prompt sequence (largest before/after gap)

**The adversarial loop:**
Give ChatGPT the full context before asking for objections — paste the construct validity audit output, the citation network audit output, and the thesis. Without full context ChatGPT raises objections the audits already answered, wasting the stress test. Ask: *“Review this thesis I developed from this methodological audit. What are the three strongest objections? Where is the evidence thinnest?”*

Give Grok the same full context plus ChatGPT’s objections, then ask: *“Do you find these objections compelling, or is this compliance hedging? Where do they hold and where do they fail?”*

What survives that loop is publishable.

**ChatGPT as reviewer:** ChatGPT’s compliance softening — the tendency that makes it frustrating for initial diagnostic work on contested territory — makes it the best reviewer in the toolkit. It finds exactly the objections a journal reviewer would raise. Its weakness in one context is a strength in another. Use it deliberately.

**The meta-rule on supplying evidence:**
The model cannot produce what isn’t in its training data. If the corrective evidence lives in competitive gaming forums, practitioner communities, or unpublished domain knowledge, you have to supply it — or tell the model where to look. The model can process and synthesize evidence you direct it to. It cannot discover evidence that was never indexed.

This is why domain expertise is the irreplaceable input. The hunch, the specific suspicion, the right questions — all come from the practitioner. The AI is the tool that confirms honestly once the challenge is supplied.

-----

## Why Practitioner Instincts Are More Trustworthy Than They’ve Been Told

There is a common dismissal of domain-expert skepticism — the “bro science” critique. Practitioner knowledge lacks peer review, controlled samples, documented methodology. Therefore discount it.

This gets the epistemology backwards.

“Bro science” — bodybuilders figuring out effective training protocols decades before formal sports science — was frequently 10-20 years ahead of the published literature. The evidence quality was poor. The direction was usually right. The reason: practitioners have direct feedback loops, strong incentives to find what actually works rather than what publishes well, and massive distributed sample sizes. Hundreds of thousands of people running independent self-experiments in real time produce noisy but directionally accurate signal.

The competitive gaming community’s immediate identification of the Shen et al. proxy failure in 2016 is the same phenomenon. Thousands of players knew within days that leveling speed couldn’t measure individual mechanical skill — because they had direct experience with boosting, carries, and MMO social dynamics. That domain knowledge was correct. The literature dismissed it as ideologically motivated. The peer reviewers had never played the game.

The pattern is consistent. Practitioners with direct feedback loops frequently identify problems with academic consensus years before the literature catches up. The problem is not the domain knowledge. The problem is the pathway from domain knowledge to formal challenge. Practitioner skepticism lives in forums and communities that don’t get indexed — and therefore don’t make it into AI training data.

This is why the end user has to supply the challenge. The instinct that something is wrong is usually the right starting point. The method converts that instinct into a documented, citable, archived methodological critique. The AI cannot generate the suspicion from nothing — because it lives in the gap between what the literature says and what practitioners know. That gap is precisely what doesn’t get indexed.

If your instinct as a domain expert is that the published consensus doesn’t match what you observe in practice — that instinct is probably more reliable than you’ve been told. The question is whether you have the tools to convert it into something the institution has to engage.

-----

## The Meta-Finding

Gemini wasn’t hallucinating when it called Shen et al. “groundbreaking.” It was accurately reflecting the academic literature and mainstream media coverage. The UC Davis press release said “groundbreaking.” The downstream papers said “physical attributes are unrelated to esports performance.” Gemini reproduced all of that faithfully.

The problem is that the academic literature and mainstream media were themselves wrong — wrong in a specific, documented, traceable way. The literature laundered a weak proxy into a foundational claim. The AI trained on both reproduced the laundering accurately.

The two-prompt sequence doesn’t fix an AI problem. It bypasses an institutional problem the AI inherited. The bottleneck was never the model. It was the domain knowledge required to supply the challenge.

*“The guardrails are not protecting truth. They are protecting the current institutional framing of truth. When forced to process primary evidence directly, the consensus collapses.”*

-----

## The Three Full Documents

**1. The behavioral experiment — Sessions A, B, C, D in full:**
How AI models behave on citation-laundered academic consensus vs. MSM-suppressed news. The Gemini and Grok before/after comparison. The grooming gang parallel. Why Session A (positive reinforcement) matters more than Session B (direct challenge).
→ *I Asked Gemini About the Most-Cited Study in My Field. Then I Showed It Why the Study Was Wrong.* — [link to be added on Substack]
→ https://yungmulababy.substack.com/p/how-a-login-timestamp-became-proof *(companion — the Shen study itself)*

**2. The self-assessment — all four models verbatim:**
The same prompt sent to all four models asking where their lines are. Full responses from Claude, ChatGPT, Gemini, and Grok. The comparative analysis identifying the two friction mechanisms and the clarification of when Grok’s self-assessment applies vs. when training data consensus reproduction dominates.
→ *[Where Are Your Lines? A Multi-Model Self-Assessment of AI Friction on Contested Topics]*

**3. The workaround guide — seven specific techniques:**
The construct-validity reframe, the direct challenge, technical/narrow framing, explicit permission grant, the self-assessment question, the adversarial loop, and model routing. Friction-tier specific approaches with specific prompt templates.
→ *[How to Actually Use AI for Contested Empirical Topics]*

All three documents are also available in the GitHub repository:
github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research

-----

*The method is replicable. The bottleneck was never infrastructure. It was domain knowledge — which practitioners already have.*

*Start wherever the anomaly appears. Finish with receipts.*
