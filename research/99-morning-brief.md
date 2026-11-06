# 99. Morning brief

_6 November 2026. All ten tracks, the synthesis files, verification and PDFs are done and pushed._

**Caveat.** The environment blocked page fetches for almost every site, so most findings rest on search extracts citing the primary source, not on reading it. I re-checked 29 key numbers (2 corrected, 1 dropped) and all 42 quotes. Every quote comes from Anthropic or Microsoft, the only reachable sites. See verification.md.

## Five findings that should change how you write

**1. Workers are not the blocker. Employers are.** In Microsoft's 2024 survey (n=31,000), 78% of AI users brought their own tools and 52% hid using them on important work. The 2026 edition (n=20,000) found twice as many skilled users blocked by their organisation (10%) as ready organisations held back by their people (5%). Only 13% are rewarded for redesigning work. Where resistance exists it looks rational: 53% worry AI use makes them look replaceable, and at Commonwealth Bank the union was right that the voice bot hadn't cut call volumes. Drop "people resist" and write about permission, incentives and trust.

**2. The tech is not the easy part for agents.** On business-shaped tasks, reliability collapses with repetition and turns: Salesforce's own CRMArena-Pro falls from about 58% single-turn to 35% multi-turn. On tau-bench, success drops from 69% on one try to 46% when all four tries must succeed. Half the named failures (Air Canada, NYC MyCity, Deloitte, about 1,600 hallucinated-citation rulings, EchoLeak) are the technology failing, not the business. Anthropic's own engineers can fully delegate only 0 to 20% of their work. Write "both have to move", not "the tech is solved".

**3. The gain may be small, not the readiness low.** In Danish administrative data covering about 25,000 workers in exposed jobs, adoption plus employer encouragement produced about 3% time savings and precisely zero effect on earnings or hours. US TFP growth slowed to 0.8% in 2025. McKinsey's EBIT-impact share is flat at about 37% while agent scaling rose. "The business isn't ready" can be a comforting misdiagnosis when the honest answer is "this use case doesn't pay yet".

**4. Shared context: plausible, but only human-written context is shown to help.** The best support is vendor inference: Anthropic's 1M-transcript analysis says complex deployment is "constrained more by access to information than on underlying model capabilities". The only controlled test (Gloaguen et al., 2026, coding agents) found LLM-generated context files reduced success and raised cost over 20%, while developer-written files helped slightly. That favours a Studio framing of context curated by the people who do the work, not auto-ingested data. No framework defines "AI-native" by shared context, so present it as your definition, which is a positioning asset.

**5. "Freedom to be more human" has the evidence against it so far.** An eight-month ethnography (Berkeley Haas, 2026) found AI time savings turned into task expansion and longer hours. Four experiments (n=3,562) found AI raised performance but lowered intrinsic motivation afterwards. In a 2026 RCT, analysts followed an agent's coin-flipped lean 86% of the time. And the job guarantee in Marienthal showed work itself supplies structure, status and contact. You can argue rote-work removal *should* free people. You cannot yet say it *does*, and saying so invites an easy rebuttal.

## Strongest evidence against your thesis

The official barrier data don't name your causes. UK firms cite "can't identify a use case", cost and skills. OECD non-adopters cite "poor fit with our work" (57%). A third of US small employers have no plans to use AI, mostly because it's not applicable or they'd rather not. That is choosing not to adopt, not failing to adopt. In enterprise, Gartner and S&P put cost, unclear value and risk controls first. Meanwhile harm is arriving before transformation: GenAI adopters hired about 80% fewer juniors per quarter, possibly in anticipation of capabilities that haven't materialised.

## Viral numbers to stop using

"95% of pilots fail" (self-selected, preliminary, measures something narrower), "70% of change programmes fail" (no empirical basis), "80% of AI projects fail" (RAND attributes it to "some estimates"), "UK lost 8% of jobs to AI" (not a labour-market statistic). Full list: 12-facts-and-figures.md.

## Three questions to answer next

1. **Does inability to describe the workflow predict failure?** It's your central causal claim and nothing found tests it. Your own client data (process maps before and after, time to production, what broke) could be the first evidence anyone has.
2. **Does shared business context improve agent outcomes outside coding?** Run a controlled comparison in Studio: no context, auto-generated context, human-curated context, on real finance or ops tasks.
3. **Is the junior-hiring drop permanent?** If AI-native firms are removing the apprenticeship layer, that's the human consequence most worth writing about, and the evidence is moving fast.
