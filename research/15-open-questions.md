# 15. Open questions

_What to research next, and where this pack is thin. Blunt by request._

## What was thin, and why

**The whole pack rests mostly on search extracts, not on reading the sources.** The cloud environment's network policy blocked page fetches for almost every host. Only anthropic.com, microsoft.com and raw.githubusercontent.com could be opened. A shared cap of about 200 web searches per turn also cut the first research wave short: every one of the ten track files was first written INCOMPLETE, and a second gap-filling pass narrowed but did not close the gaps. Concretely:

- No government statistics release, regulator text, court ruling, NBER/arXiv paper (other than those mirrored on GitHub), consultancy report or news article was read in full. Their numbers are as reported by search extracts that cite them. The verification pass corroborated 17 of the most important ones by independent search and corrected two. The rest of the roughly 330 rows in 12-facts-and-figures.md have not been independently checked.
- **The verified quotes all come from Anthropic and Microsoft (plus benchmark READMEs).** Both sell AI. That skews the quotable record towards vendor framing. Do not mistake it for balance.
- **Vendor research is over-represented in the evidence on agents.** The best data on how people actually supervise agents (deference, approval rates, planning vs execution decisions) are Anthropic's studies of its own products. There is almost no independent field evidence.
- Several tracks have sections that rest on two or three sources. Weakest: SMB implementation cost and abandonment (no credible figure exists), process-documentation quality as a cause of AI failure (no study found), the UK and EU displacement evidence, the anti-AI case beyond energy and copyright, and the AI-advice "grifter" market (enforcement cases only, no market size).

**To fix the access problem:** add the blocked hosts to the cloud environment's allowed network domains (environment settings, Network access) and rerun the verification pass on 12-facts-and-figures.md. Priority hosts: rand.org, nber.org, arxiv.org, bls.gov, census.gov, ons.gov.uk, fedsmallbusiness.org, federalreserve.gov, gartner.com, mckinsey.com, pewresearch.org, canlii.org, eur-lex.europa.eu, oecd.org, budgetlab.yale.edu, digitaleconomy.stanford.edu.

## The questions that matter most for your thesis

1. **Does inability to describe the workflow actually predict AI project failure?** This is the thesis's central causal claim and nothing found tests it. RAND's interviews are the closest. The process-mining literature documents gaps between designed and actual processes but does not link them to AI outcomes. You may be best placed to answer this with your own client data: before-and-after process maps, time to production, and what broke.
2. **Does a shared, stored context improve agent outcomes outside coding?** The only controlled evidence (Gloaguen et al. 2026) is for coding agents: LLM-generated context files hurt, developer-written ones help slightly. Nobody has tested SOPs, skills or a shared business context store for finance, ops or customer service. A controlled comparison in Studio would be original evidence.
3. **Is the junior-hiring drop permanent, or an anticipation effect that reverses?** Hosseini and Lichtinger raise this explicitly. It decides whether "AI-native" firms are quietly removing the apprenticeship layer. Where the missing young hires go is unstudied.
4. **Is the binding constraint readiness, or the size of the gain?** Danish administrative data show about 3% time savings and no earnings or hours effect despite adoption and encouragement. If gains are small for typical tasks, "the business isn't ready" may be a comforting misdiagnosis. Watch for the 2026 Humlum and Vestergaard update and any replication outside Denmark.
5. **Does human oversight of agents work in the field?** The 86% deference result is from a lab-style RCT with a vendor. Is there any field study of reviewer accuracy on agent output in finance, legal or HR?
6. **What does a credible "AI-native" 10-person firm look like, with numbers?** Only vendor case studies were found. An independent set of 5 to 10 documented small firms (cost, time to build, what broke, what staff now do) would be valuable and publishable.
7. **Does freed time go to "more human" work anywhere?** Early evidence points to intensification (Berkeley Haas ethnography) and lower intrinsic motivation (Scientific Reports 2025). Is there any setting, perhaps four-day-week trials combined with AI, where freed time went to care, learning or community? Nothing found.

## Specific items to check next (from the track files)

**Definitions (02):** first business use of "AI-native" (VC usage traced only to 2023); the wording of Klarna's F-1 risk factors on AI and service quality; any SEC or FTC AI-washing actions after April 2025; Gartner, BCG and Deloitte maturity models in their own words.

**SMB (03):** the full DSIT 2026 adoption report (published 29 Oct 2026, not fetched); the SF Fed's July 2026 qualitative SBCS brief; the size of the "AI automation agency" market; SMB AI spend split between subscriptions, integration and outside help.

**Enterprise (04):** does the MIT NANDA report itself say purchased tools succeed about twice as often as internal builds, and that the core barrier is a "learning gap"? Why did IDC/Lenovo's POC-to-production figure move from 12% to 46% in a year? Salesforce Agentforce renewal and churn data. Any controlled evidence that semantic or context layers work. Procurement time from pilot to signed contract.

**Inertia (05):** an independent RCT of AI training (not access) on business outcomes; Gallup's "8.7-fold" manager effect at source; any measurement of adoption or productivity after de-layering.

**What goes wrong (06):** a systematic dataset of customer-service AI reversals (a rate, not a list); the lawyer vs self-represented split in the hallucination database over time; operational agent incidents with post-mortems.

**Working with agents (07):** firm filings that quantify AI-attributed headcount change with a method; whether a general-purpose business agent is "high-risk" under EU AI Act Annex III; UK and US liability positions for agent errors.

**Displacement (08):** a UK replication of the Canaries design using ONS/HMRC PAYE data; any AI-specific Bank of England Decision Maker Panel result; the OECD Employment Outlook 2026 chapter on AI and entry-level work; the October 2026 Challenger report (to replace the unconfirmed figure).

**What people do (09):** reconcile the OpenResearch labour-supply figures (1.3 hours and 2 points vs 3.9 points); detailed time-use tables; long-run Kenya UBI results; primary sources on Medvi.

**Social and political (10):** whether any EU AI Act fine has been issued; enforcement under California SB 53, Texas TRAIGA and Illinois HB 3773; Q3 2026 hyperscaler capex from filings; whether 54.4% is a series low for the US labour share; the strongest primary statements of the anti-AI case (Bender and Gebru, Marcus, Zitron) read in full rather than characterised.

**Contrarian (11):** BLS OEWS series for radiologists, translators and bank tellers pulled directly; NRMP radiology positions; METR's Feb 2026 redesign post read in full; the source of the circulating "translator earnings fell 29.7%" figure.

## A blunt note on the method

Ten agents searching in parallel used up the search cap faster than one sequential analyst would have, and the network block meant depth could not substitute for breadth. The pack is broad, honestly labelled and usable for orientation and for deciding what to read. It is not yet citable for publication without reading the primary sources. Treat 01 and 99 as a well-informed first pass, not a final verdict.
