# Verification pass

_Run 2026-11-06, after all track files were written and before the final files. Method notes first, then results._

## Method and its limits

The brief asks for each URL to be re-fetched. In this session the environment's network policy blocked page fetches for almost every host. The hosts that could be fetched were www.anthropic.com, www.microsoft.com and raw.githubusercontent.com. So the verification used two methods:

- **RE-FETCHED:** the page was downloaded again with curl, converted to text (pdftotext for PDFs), and the number or quote was located in the text with its surrounding context. This is full verification.
- **CORROBORATED BY INDEPENDENT SEARCH:** for blocked hosts, a fresh web search (not the one the track agent used) was run and the figure, sample and date were checked against the extract it returned, which cites the primary page. This is weaker than a re-fetch: it confirms that the figure is reported consistently, not that I read it in the original. Treat these as "cite with the caveat that the original was not opened".
- **NOT CONFIRMED:** neither method confirmed the figure. These go to DO NOT CITE in 12-facts-and-figures.md.

## Numbers checked (25)

| # | Figure | Track file | Method | Result | Notes |
|---|---|---|---|---|---|
| 1 | tau-bench retail pass^1 0.692 to pass^4 0.462 | 06, 11, 01 | Re-fetched README | CONFIRMED | Model is Claude 3.5 Sonnet (Oct 2024); GPT-4o 0.604 to 0.383. These are 2024 models. Caveat added to 01. <https://raw.githubusercontent.com/sierra-research/tau-bench/main/README.md> |
| 2 | Anthropic engineers use Claude in 59% of work; most can "fully delegate" 0-20% | 02, 01 | Re-fetched | CONFIRMED | Self-reported; 12 months earlier the figure was 28%. Productivity self-report +50%. <https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic> |
| 3 | WTI 2026: 10% blocked agency, 5% unclaimed capacity, 13% rewarded for reinvention, n=20,000 | 02, 01 | Re-fetched | CONFIRMED | Fielded by Edelman DXI, 18 Feb to 20 Apr 2026, 10 markets, AI users only. 16% "stalled". <https://www.microsoft.com/en-us/worklab/work-trend-index/agents-human-agency-and-the-opportunity-for-every-organization> |
| 4 | WTI 2024: 78% BYOAI, 52% reluctant to admit, 53% worry about looking replaceable, n=31,000 | 05, 01 | Re-fetched | CONFIRMED | Edelman DXI, 31 markets, 15 Feb to 28 Mar 2024. <https://www.microsoft.com/en-us/worklab/work-trend-index/ai-at-work-is-here-now-comes-the-hard-part> |
| 5 | 86% of analysts followed agent's coin-flipped lean, n=50 | 07, 01 | Re-fetched | CONFIRMED | Per-choice range 81% to 90%; 50% = no influence. <https://www.anthropic.com/research/agents-judgment-calls> |
| 6 | Junior employment at GenAI adopters down about 9% after six quarters; about 80% fewer junior hires per quarter | 08, 01 | Re-fetched PDF | CONFIRMED | 4.0 fewer junior hires per firm-quarter relative to non-adopters, about 80% of the pre-period mean of 5.06. Résumé data, 65M workers, 280k firms. <https://raw.githubusercontent.com/s-mahdihosseini/Website/b99fa2962dcc4c165bbc3c41dd283afa99c5ccfb/GenAI_SenBTC_May_2026.pdf> |
| 7 | Those expecting AI to do 80%+ of their work forecast 12.2% unemployment in 2030, n=10,980 | 08 | Re-fetched | CONFIRMED | Morning Consult, 11 to 23 Aug 2026, weighted. <https://www.anthropic.com/research/ai-expectations-gap> |
| 8 | Software engineering nearly 50% of agentic activity, n=998,481 tool calls | 07 | Re-fetched | CONFIRMED | <https://www.anthropic.com/research/measuring-agent-autonomy> |
| 9 | 77% of API transcripts automation vs 12% augmentation | 02, 07 | Re-fetched | CONFIRMED | <https://www.anthropic.com/research/anthropic-economic-index-september-2025-report> |
| 10 | MIT NANDA: 52 interviews, 153 survey responses, 300+ initiatives; "5%" | 04, 01 | Independent search | CORROBORATED, with a correction of framing | Survey collected at four industry conferences (self-selected). The report's own sentence, as quoted by The Register, is that only 5% of *custom enterprise AI tools* reach production; elsewhere it says 95% of organisations get no measurable return. The two framings are both in the report. Use the narrow one. <https://www.theregister.com/2025/08/18/generative_ai_zero_return_95_percent> |
| 11 | Fed SBCS: 46% of small employer firms use AI; 7% of users "fully integrated" | 03, 01 | Independent search | CORROBORATED (partly) | 46% confirmed via a June 2026 Fed Governor speech; 7% via an America's SBDC summary that does not name the survey year in the extract. Cite with caveat. <https://www.fedsmallbusiness.org/2026-report-on-employer-firms> |
| 12 | Census BTOS question change 17 Nov 2025; use roughly doubled | 03, 01 | Independent search | CORRECTED | Change date confirmed (new wording from 4 Dec 2025 data). St Louis Fed puts the jump at about 10% to 17%, not 9% to 18%. Track file 03 corrected. <https://www.stlouisfed.org/on-the-economy/2026/jun/measuring-ai-adoption-firms-how-you-ask-matters> |
| 13 | IDC/Lenovo 2026: 46% of AI POCs progressed to production, n=3,120 | 04, 01 | Independent search | CORROBORATED | Lenovo press release; IDC fieldwork 16 Sep to 17 Oct 2025. Vendor-sponsored. <https://www.businesswire.com/news/home/20260127255538/en/> |
| 14 | Humlum and Vestergaard: about 3% time savings, precise zero effects on earnings and hours | 05, 08, 11, 01 | Independent search | CORROBORATED | Survey time saving is 2.8% (abstract rounds to 3%). The 3-7% figure is pass-through of gains to earnings; TechRadar misstates it. <https://econpapers.repec.org/RePEc:nbr:nberwo:33777> |
| 15 | US TFP +0.8% in 2025 vs 1.5% in 2024; labour productivity 2.2% vs 3.0% | 11, 01 | Independent search | CORROBORATED | Also: TFP grew 1.0% a year over 2019-25 vs 0.6% over 2007-19. That is a fair counterpoint and is now noted in 01. <https://www.bls.gov/news.release/archives/prod3_03192026.pdf> |
| 16 | McKinsey 2026: 37% attribute some EBIT to AI; $1B+ firms scaling agents 27% to 40%, n=1,719 | 04, 01 | Independent search | CORROBORATED | Fielded 4 May to 8 June 2026, 97 countries. High performers about 6%, flat. |
| 17 | Stanford "Canaries" Aug 2026: 22-25 year olds in exposed jobs about 19% below counterfactual | 08 | Independent search | CORROBORATED | Not comparable with the 2025 version's 13% (different method). Authors call it descriptive, not causal. <https://digitaleconomy.stanford.edu/news/canariesaug26/> |
| 18 | Pew June 2026: 52% more concerned than excited; 71% expect fewer jobs | 10 | Independent search | CORROBORATED | n=3,488, 22 to 28 June 2026. <https://www.pewresearch.org/short-reads/2026/08/18/young-adults-in-the-us-are-increasingly-wary-of-ai/> |
| 19 | Challenger: 121,401 AI-cited US announced cuts Jan to Oct 2026 | 08 | Independent search | NOT CONFIRMED | The independent search could not find the October 2026 report. Through July 2026 the figure was 112,713 (corroborated). Moved to DO NOT CITE; 08 annotated. <https://www.challengergray.com/wp-content/uploads/2026/08/Challenger-Report-July-2026.pdf> |
| 20 | CRMArena-Pro: about 58% single-turn, about 35% multi-turn | 11, 01 | Independent search | CORROBORATED | "Near-zero confidentiality awareness" appears in secondary summaries; the paper frames confidentiality as a separate test. Cite the 58/35 figures; soften the confidentiality phrasing. <https://arxiv.org/abs/2505.18878> |
| 21 | Gloaguen et al.: context files reduce success, cost +20% | 07, 01 | Independent search | CORRECTED | The reduction applies to LLM-generated context files. Developer-written files tended to slightly improve success. 01 and 07 corrected. This changes the reading in your favour. <https://arxiv.org/abs/2602.11988> |
| 22 | Microsoft 365 Copilot over 30M paid seats (July 2026) | 04 | Independent search | CORROBORATED | Nadella on FY26 Q4 call, 29 July 2026; about 7% of 450M+ commercial seats is an analyst estimate, not Microsoft's. |
| 23 | Spider 2.0: about 17% vs 91% on Spider 1.0 | 04, 01 | Independent search | CORROBORATED | 17.0% (o1-preview agent framework) on 632 tasks, Nov 2024. The "17-21%" range in 04 includes later models; the 17.0% figure is the one the paper states. |
| 24 | Charlotin database: about 1,600 decisions with hallucinated content by June 2026 | 06, 01 | Independent search | CORROBORATED | AFP, 16 June 2026: about 1,600 across 35 countries; 1,116 in the US. Crowd-sourced, not definitive. |
| 25 | Klarna FTEs 5,527 (2022) to 3,422 (2024) | 02, 01 | Independent search | CORROBORATED | From the F-1. CEO says attrition and a hiring freeze did much of it, not AI alone. Later figure about 2,907 (2025). |
| 26 | Gartner: >40% of agentic projects cancelled by end-2027; poll of 3,412 webinar attendees; about 130 real vendors | 04, 02 | Independent search | CORROBORATED | FORECAST. Drivers: costs, unclear value, risk controls. |
| 27 | KPMG/Melbourne 2025: 57% hide AI use; 66% use regularly; 46% willing to trust | 05, 10 | Independent search | CORROBORATED | n=48,000+, 47 countries, Nov 2024 to Jan 2025. |
| 28 | Upwork 2024: 77% say AI added to workload | 05, 11 | Independent search | CORROBORATED, with scope note | Applies to employees *using AI* within a 2,500 sample that included 1,250 C-suite, 625 employees, 625 freelancers in four countries. Vendor survey. |
| 29 | ONS: 28% of firms with 0 to 9 employees use AI (June 2026) | 03 | Independent search | CORROBORATED (secondary) | From a summary of BICS wave 159; ONS bulletin itself shows 17% of 0-9 firms reporting extensive use vs 9% of 250+. Cite with caveat. |

Totals: 9 confirmed by re-fetch; 17 corroborated by independent search (2 of them with framing caveats); 2 corrected; 1 not confirmed and moved to DO NOT CITE.

## Quotes checked

Every quote in every track file's "Verbatim quotes" section (42 quotes across 02, 05, 06, 07, 08) was re-fetched from its URL with curl, converted to text and matched after normalising whitespace and curly quotes. **All 42 matched.** The script and page cache are in the session scratchpad, not the repo.

All 42 come from three hosts (anthropic.com, microsoft.com, raw.githubusercontent.com) because those were the only hosts reachable. **This makes the quote set heavily skewed towards two vendors with an interest in AI adoption.** That is a sampling artefact of this session, not a judgement that these are the best quotes. 13-quotes.md lists the candidate quotes from other sources (Gartner, Hughes, Keynes, Covello, the Moffatt tribunal) that should be fetched and added once the network allows.

Inline quotation marks in track-file findings that are not in the Verbatim quotes sections were NOT verified. A note to that effect was added under the title of each track file.

## Corrections made to track files

- 03-smb.md: BTOS jump changed from "about 9% to about 17-18%" to "about 10% to about 17%".
- 07-working-with-agents.md and 01-thesis-stress-test.md: the Gloaguen et al. result qualified (LLM-generated vs developer-written context files).
- 08-displacement.md: Challenger Jan to Oct 2026 figure flagged NOT CONFIRMED; Jan to July figure (112,713) used instead.
- 01-thesis-stress-test.md: tau-bench model-vintage caveat added.

## What a proper verification pass still needs

Open the blocked primary documents and check the remaining numbers in 12-facts-and-figures.md, starting with: the RAND report PDF, the MIT NANDA PDF, the Fed SBCS 2026 report, the ONS bulletin tables, Gartner's press releases, the BLS release, NBER w33777, and the CanLII text of Moffatt v. Air Canada. This needs the hosts added to the environment's allowed network domains.
