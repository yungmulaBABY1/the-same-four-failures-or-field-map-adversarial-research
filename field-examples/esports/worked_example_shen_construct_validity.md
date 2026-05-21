# Worked Example: Construct Validity Audit

## Shen et al. (2016) — “Do Men Advance Faster Than Women?”

*This document shows the construct validity audit prompt applied to the most-cited paper in the esports gender literature. It is a complete end-to-end example of the method. Use it as a template for running the same audit on the foundational paper in your own field.*

*Prompt used: `construct_validity_claim_vs_measurement_audit_prompt.txt`*
*Model used for initial audit: Grok (adversarial pass); Claude (structure and synthesis)*
*Full series this audit is part of: https://yungmulababy.substack.com/p/start-here*

-----

## INPUT

**Source title:**
Do Men Advance Faster Than Women? Debunking the Gender Performance Gap in Two Massively Multiplayer Online Games

**Source citation:**
Shen, C., Ratan, R., Cai, Y. D., & Leavitt, A. (2016). Journal of Computer-Mediated Communication, 21(4), 312–329. DOI: 10.1111/jcc4.12159

**Contested claim:**
That the gender performance gap in competitive gaming is a social construct with no biological basis — that when playtime is controlled, men and women perform equally.

**Field / debate:**
Gender and elite esports performance. Academic literature on whether the near-zero female representation at the Tier-1 open performance ceiling in FPS, MOBA, RTS, and fighting games is explained by culture/socialization or by performance factors.

**Source excerpts (key methodology):**
The study used anonymized server telemetry from EverQuest II (n ≈ 9,000+ players) and Chevaliers’ Romance III (n ≈ 2,000+ players). The primary dependent variable was character level advancement speed — operationalized as the time elapsed between character creation and reaching specific level milestones, divided by total login time. The authors controlled for total play time and guild membership (binary variable). Max-level characters were excluded from the dataset to maintain a linear model. Conclusion: “Per hour played, women advance at least as fast as men.”

**Later citation use:**

- Rogstad (2021/2022): “Unlike traditional sports, physical attributes are unrelated to high performance in eSports, allowing both men and women to compete in the same events (Shen et al., 2016; Paaßen et al., 2017).”
- Paaßen et al. (2017): Cites Shen to establish that perceived male gaming superiority is a stereotype without empirical basis.
- Siutila & Havaste (2019): Cites Shen to frame community skepticism about female competitive viability as irrational — if performance parity is established, opposition must be ideological.
- Peng PhD thesis (2021), University of Glasgow: “Physical attributes are unrelated to high performance in eSports, allowing both men and women to compete in the same events (Shen et al., 2016).”
- Di Nicola et al. (2024): Still citing Shen as foundational — 8 years post-publication, methodology unexamined.

**Domain-expert concern:**
MMO leveling speed cannot distinguish individual mechanical skill from socially assisted progression. Boosting (a high-level player carrying a low-level character through content) and social carries are well-documented phenomena in MMO research — including in the corresponding author’s own prior work. Additionally, the deletion of max-level characters removes the only players who have completed the progression arc and could speak to high-level performance. The game measured (EverQuest II) is a social MMO, not a competitive title with adversarial ranked mechanics.

-----

## AUDIT OUTPUT

### 1. EXACT CLAIM EXTRACTION

**A. Strongest claim made by the source itself:**
“When controlling for time played, there is no gender performance gap in MMO progression speed — women advance at least as fast as men per hour played.”

**B. Weaker defensible claim actually supported by the data:**
“Among non-max-level EverQuest II and Chevaliers’ Romance III players with measurable login time, female characters advanced through level milestones at comparable rates to male characters per hour of login time, after controlling for guild membership.”

**C. Inflated claim made by later citations:**
“Physical attributes are unrelated to high performance in eSports” (Rogstad, citing Shen). “The gender performance gap in competitive gaming is a myth” (widespread media coverage). “Men and women perform equally when given equal opportunity” (institutional framing across multiple downstream papers).

**Are A, B, and C the same claim?** No.

**Where does inflation occur?** At every citation step. A measures MMO leveling persistence in casual social MMOs. C makes a claim about elite competitive gaming performance across FPS, MOBA, RTS, and fighting game genres. The bridge between A and C is never established in the original paper and never questioned in the citation network.

**Does the source itself overclaim, or is overclaim mainly downstream?** Both. The paper’s title (“Debunking the Gender Performance Gap”) claims more than the methodology supports. The downstream inflation is substantially worse.

-----

### 2. MEASUREMENT EXTRACTION

**What was measured:**

- Character level milestone timestamps (when a character was created vs. when it reached specific levels)
- Total login time
- Guild membership (binary: member or not)
- Sample: ~9,000 EverQuest II players, ~2,000 Chevaliers’ Romance III players
- Exclusion: all max-level characters removed

**What was NOT measured:**

- Who performed the actions that advanced the character (the account holder or another player)
- Boosting: a high-level player running a low-level character through content to advance their level
- Social carries: group content completed with significantly higher-level players
- AFK time registered as “play time” (login time ≠ active play time)
- Item/gear transfers from other accounts (twinking) that dramatically accelerate solo leveling
- Actual combat mechanics: accuracy, reaction time, decision-making, mechanical execution
- Any adversarial, competitive, or ranked gameplay
- High-end performance: all max-level characters deleted

**Is the measured variable direct evidence of the claimed construct?**
No. Character advancement speed is a proxy for the rate at which a character progresses through a non-competitive, non-adversarial progression system in a social MMO. It is not a measure of individual mechanical skill, reaction time, decision speed, spatial cognition, or any of the psychomotor traits relevant to elite competitive gaming.

**How close is the proxy to the target construct?**
Very distant. The measured construct (MMO leveling persistence) and the claimed construct (gendered competitive gaming performance) share almost no methodological overlap.

-----

### 3. CLAIM VS. MEASUREMENT TABLE

|Measured variable                                   |Claimed construct                             |Same?|Gap                                                                             |Severity                    |Notes                                                                     |
|----------------------------------------------------|----------------------------------------------|-----|--------------------------------------------------------------------------------|----------------------------|--------------------------------------------------------------------------|
|MMO character level advancement speed per login hour|Individual mechanical gaming performance      |No   |Advancement speed conflates social assistance, boosting, AFK time, and solo play|**Fatal proxy failure**     |Social carry literature directly relevant; not cited                      |
|EverQuest II and Chevaliers’ Romance III data       |Competitive esports performance (FPS/MOBA/RTS)|No   |MMOs are non-adversarial social games; no ranked competitive mechanics          |**Fatal proxy failure**     |Genre mismatch — findings from social MMOs exported to competitive esports|
|Non-max-level player sample                         |High-level / elite performance                |No   |Max-level players deleted; only non-completing players analyzed                 |**Major construct mismatch**|The only players who completed the progression arc were excluded          |
|Login time as “play time”                           |Active, productive gaming time                |No   |AFK time, socializing, trading, city standing all register as login time        |**Moderate proxy gap**      |Inflates denominator for female players if they socialize more            |
|Binary guild membership control                     |Social assistance and group play              |No   |Guild membership doesn’t distinguish active carries from nominal membership     |**Major construct mismatch**|Doesn’t capture boosting, cross-account transfers, or informal help       |

-----

### 4. LEVEL-OF-ANALYSIS CHECK

**Evidence collected at:** Non-competitive social MMO player level, non-max-level characters, casual to intermediate tier, login timestamp data

**Claim applied at:** Elite competitive esports performance ceiling (Tier-1 FPS, MOBA, RTS, fighting games); population-level biological claim about physical attributes and performance

**Assumptions required to bridge:**

1. MMO leveling speed is equivalent to competitive game mechanical skill
1. Social MMO progression is equivalent to adversarial ranked gameplay
1. Non-completing casual players are representative of elite competitive performers
1. Login time is equivalent to active competitive play time
1. Findings from 2009-era EverQuest II generalize to CS2, Valorant, League of Legends, StarCraft II, etc.

**Are these assumptions tested?** No. None of them.

**Would a domain expert accept the bridge?** No. Any player familiar with both MMOs and competitive esports would immediately identify the genre mismatch. These are structurally different game types with different skill demands, different player motivations, and different social dynamics.

-----

### 5. CONFOUND AUDIT

|Confound                                                   |Domain obvious?                                                   |Controlled?  |Acknowledged?               |Impact if omitted                 |
|-----------------------------------------------------------|------------------------------------------------------------------|-------------|----------------------------|----------------------------------|
|Boosting / power-leveling                                  |Yes — basic MMO knowledge                                         |No           |No                          |**Fatal for the strong claim**    |
|Social carry effects (higher-level players running content)|Yes — documented in MMO literature Shen’s research program covered|No           |No                          |**Fatal for the strong claim**    |
|AFK time registered as login time                          |Yes                                                               |No           |No                          |**High**                          |
|Gear transfers from other accounts (twinking)              |Yes — basic MMO knowledge                                         |No           |No                          |**High**                          |
|Max-level player exclusion                                 |Yes — these are the highest performers                            |N/A — deleted|Acknowledged as a limitation|**Major construct mismatch**      |
|Genre mismatch (social MMO vs. competitive esports)        |Yes                                                               |N/A          |Not acknowledged            |**Fatal for the downstream claim**|

**Key finding:** The social carry confound is the most critical. The MMO social dynamics literature — including Yee (2006), Brehm (2013), Fortim & de Moura Grando (2013), and Patrizio (2001) — documents that female avatars and players systematically receive more help, gear, carries, and group advantages from other players. This confound is directly relevant to the leveling speed proxy, is well-documented in the literature, and was in Shen’s own research area. It was not cited and not controlled for.

-----

### 6. ECOLOGICAL VALIDITY CHECK

**Does the task resemble the real-world phenomenon being explained?**
No. EverQuest II leveling is a cooperative, social, non-adversarial activity with help mechanics, group content, and social facilitation as core features. Elite esports performance is adversarial, ranked, competitive, and individual-skill-dependent in ways that have no structural parallel to MMO leveling.

**Does the sample resemble the population the claim is applied to?**
No. Non-max-level casual MMO players are not representative of elite competitive esports players in any genre.

**Verdict: Not ecologically valid for the claim being made.** The study has some ecological validity for questions about social MMO participation and persistence. It has no ecological validity for claims about gendered performance in elite competitive esports.

-----

### 7. DECISIVE-TEST CHECK

**What would the decisive test measure?**
Sex-stratified telemetry at matched rank and matched practice volume in a competitive title with granular action logging — tracking reaction time, accuracy, decision speed, actions per minute, and win rate against opponents of equivalent rating.

**What population?**
Players matched by rank tier, practice hours, role, and competitive intent in FPS, MOBA, or RTS titles with ranked competitive modes.

**What outcome would support the source’s claim?**
No statistically significant differences in reaction time, tracking precision, spatial decision-making, or win rate at matched rank and practice volume.

**What outcome would weaken or falsify the source’s claim?**
Persistent differences concentrated in the psychomotor domains (reaction time under load, visuomotor tracking, spatial working memory, multiple-object tracking) at matched rank and practice volume.

**Does the current source run that test?** No.

**Does the field acknowledge the decisive test has not been run?** No. The field treats the proxy-based finding as having settled the question.

**The decisive test would be:** Sex-stratified granular telemetry analysis at matched rank, role, and practice volume in ranked competitive titles, measuring psychomotor outputs directly rather than progression proxies.

-----

### 8. CITATION-USE AUDIT

|Paper                   |Citation use                                                                                                                                    |Classification                        |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------|
|Rogstad (2021/22)       |“Physical attributes unrelated to high performance in eSports” — uses Shen to make a biological claim about elite competitive performance       |**Citation laundering**               |
|Paaßen et al. (2017)    |Treats Shen as establishing that male gaming superiority is a stereotype without empirical basis                                                |**Major inflation**                   |
|Kaye & Pennington (2016)|Uses Shen as the performance parity baseline to frame stereotype threat as the explanation for observed gaps                                    |**Slightly inflated**                 |
|Siutila & Havaste (2019)|Uses Shen to pathologize domain-expert skepticism about female competitive viability                                                            |**Citation laundering**               |
|Peng PhD thesis (2021)  |“Physical attributes unrelated to high performance in eSports” — doctoral-level citation of MMO leveling study for competitive performance claim|**Citation laundering**               |
|Di Nicola et al. (2024) |Still citing Shen as foundational, methodology unexamined after 8 years                                                                         |**Unsupported consensus construction**|

**Does the citation network preserve the source’s limitations?** No. No citing paper examines the measurement validity. No citing paper notes the deleted max-level players. No citing paper acknowledges the social carry confound literature.

-----

### 9. IGNORED-LITERATURE CHECK

|Ignored literature                                                           |Why it matters                                                           |Cited by Shen?|Effect of omission                          |
|-----------------------------------------------------------------------------|-------------------------------------------------------------------------|--------------|--------------------------------------------|
|Yee (2006) — differential treatment of female avatars in MMOs                |Documents social carry confound directly                                 |No            |**Fatal omission for the strong claim**     |
|Brehm (2013) — female MMO players receive more social support                |Directly relevant to leveling speed confound                             |No            |**Fatal omission for the strong claim**     |
|Fortim & de Moura Grando (2013) — gendered helping behavior in virtual worlds|Same                                                                     |No            |**Fatal omission for the strong claim**     |
|Patrizio (2001) — female avatars receive higher help and gear offers         |Same                                                                     |No            |**Fatal omission for the strong claim**     |
|Shen (2014) — Shen’s own prior EverQuest II social architecture paper        |Documents social network dynamics in the same game used in the 2016 study|No            |**Fatal omission — author’s own prior work**|
|Voyer et al. (1995) — mental rotation meta-analysis                          |Directly relevant to competitive gaming spatial demands                  |No            |**Major evidentiary gap**                   |
|Der & Deary (2006) — reaction time under cognitive load                      |Directly relevant to competitive gaming performance demands              |No            |**Major evidentiary gap**                   |
|Ericsson & Pool — deliberate practice framework                              |Directly relevant to elite performance development                       |No            |**Major evidentiary gap**                   |
|Bjork & Bjork — desirable difficulties                                       |Same                                                                     |No            |**Major evidentiary gap**                   |

-----

### 10. SOURCE-STATUS LABELS

- Character advancement speed: **Weak proxy** for individual mechanical skill
- Login time control: **Weak proxy** for active play time
- Guild membership control: **Weak proxy** for social assistance
- “Performance parity” conclusion: **Citation-laundered premise** in downstream papers
- Downstream biological claim (Rogstad): **Unsupported inference** — not established by the source

-----

### 11. VERDICT

**E. Fatal construct-validity failure for the claim being made / F. Citation-laundered premise**

Shen et al. (2016) measured MMO character leveling speed — a social, cooperative, non-adversarial progression metric in a 2009-era game — and concluded that women advance at least as fast as men per hour played. The study cannot distinguish individual mechanical skill from socially assisted progression, does not control for boosting or carries (documented in the social carry literature the corresponding author’s own research program was embedded in), and deleted all max-level players who could speak to high-level performance. The downstream citation network then used this finding to establish a biological premise — that physical attributes are unrelated to high performance in esports — a claim the original study’s methodology cannot support, as it measured no psychomotor traits, no adversarial competitive gameplay, and no elite-level performance.

-----

### 12. PAPER-SAFE WORDING

**A. Neutral summary sentence:**
Shen et al. (2016) found that female EverQuest II characters advanced through level milestones at comparable rates to male characters per hour of login time, after controlling for guild membership and excluding max-level players.

**B. Direct methodological critique:**
The study’s primary measure — MMO character leveling speed — cannot distinguish individual mechanical skill from socially assisted progression and is ecologically invalid as evidence for claims about competitive esports performance.

**C. Strong adversarial version:**
A study that measured cooperative MMO leveling speed, could not detect boosting or carries, deleted its highest-performing players, and drew on a game genre with no structural parallel to competitive esports cannot establish the biological premises its downstream citations use it to support.

**D. Decisive-test sentence:**
The question of gendered competitive gaming performance requires sex-stratified granular telemetry at matched rank and practice volume in ranked competitive titles — a test that remains unrun.

-----

### 13. FAILURE-MODE CLASSIFICATION

- [x] **Proxy problem** — leveling speed is not a measure of individual mechanical skill
- [x] **Fatal proxy failure** — the proxy cannot support the strong claim even in principle
- [x] **Level-of-analysis error** — casual MMO findings exported to elite competitive esports
- [x] **Ecological validity failure** — social MMO genre is not analogous to competitive esports
- [x] **Omitted confound** — social carry effects directly relevant and not controlled
- [x] **Citation laundering** — downstream papers use the finding as a biological premise without engaging the methodology
- [x] **Ignored adjacent literature** — MMO social dynamics literature documenting the confound was available and in the corresponding author’s research area
- [x] **Missing decisive test** — the field has never specified or run the test required to resolve the question
- [x] **Untested premise** — “physical attributes unrelated to esports performance” is asserted, not established

-----

### 14. FINAL OUTPUT

- **Strongest defensible claim:** Female EverQuest II characters advanced through level milestones at comparable rates to male characters per login hour in a non-competitive social MMO context.
- **Claim being overextended:** Physical attributes are unrelated to high performance in competitive esports; the gender performance gap is explained entirely by socialization and access.
- **Main proxy problem:** MMO leveling speed cannot distinguish individual mechanical skill from socially assisted progression, AFK time, or external carries.
- **Main level-of-analysis problem:** Casual social MMO findings exported to elite competitive esports performance — structurally different genre, different player motivations, different skill demands, different social dynamics.
- **Main omitted confound:** Social carry effects — documented in MMO literature including the corresponding author’s own prior work on EverQuest II social architecture.
- **Decisive test:** Sex-stratified granular telemetry at matched rank, role, and practice volume in ranked competitive titles measuring psychomotor outputs directly.
- **Citation-use verdict:** Citation laundering. No downstream paper examines the measurement validity. The finding has been elevated from a proxy-based MMO study to a foundational biological premise about competitive esports performance.
- **Overall verdict:** Fatal construct-validity failure for the strong claim. Valid only for the narrow claim about non-competitive MMO leveling persistence under controlled login time.
- **Confidence level:** High
- **What would change this assessment:** Evidence that social carry effects were controlled for in the original study; evidence that the measurement proxy is validated against direct performance metrics in competitive contexts; a decisive test showing no psychomotor differences at matched rank and practice volume.

-----

## HOW TO USE THIS AS A TEMPLATE

To run the same audit on your field’s foundational paper:

1. Copy the prompt from `construct_validity_claim_vs_measurement_audit_prompt.txt`
1. Fill in the input template with your paper’s abstract, methods, and how later papers cite it
1. Add your domain-expert concern — what smells wrong to you as a practitioner
1. Paste into Grok first (most direct on contested empirical claims)
1. Then paste into Claude for structured synthesis
1. Then ask ChatGPT to make the strongest case that the audit is wrong
1. Bring ChatGPT’s counterarguments back to Grok: “Do you find these objections compelling or is this compliance hedging?”
1. What survives that loop is your publishable critique

**The rule:** You may begin with vibes. You may not end with vibes.

Start wherever the anomaly appears. Finish with receipts.

-----

*Part of the five-paper series on elite esports performance and institutional research failure.*
*Full series: https://yungmulababy.substack.com/p/start-here*
*Archive: DOI 10.5281/zenodo.20209372*
*Field map and prompts: github.com/yungmulaBABY1/the-same-four-failures-or-field-map-adversarial-research*
