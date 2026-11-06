# 01. Thesis stress test

_Written 2026-11-06 after all ten track files existed. Every claim below links to a source; the track files carry fuller context, sample sizes and caveats. Labels: EVIDENCE, FORECAST, OPINION._

**Read this caveat first.** This session's network policy blocked page fetches from almost every source site. Only anthropic.com, microsoft.com and raw.githubusercontent.com pages could be opened. Everything else rests on search-engine extracts that name and link the primary source. Treat numbers from non-fetched sources as "reported, not yet read in the original". `verification.md` lists what was re-checked and how.

## The thesis, split into testable parts

> The tech is the easy part; the transformation is the hard part. AI fails in businesses because the business isn't ready: nobody can describe the real workflow, there's no shared context humans and agents both work from, and people resist a whole new way of working.

The thesis bundles six claims. They fare very differently.

| # | Claim | Verdict |
|---|---|---|
| A | The tech is the easy part | **Breaks** for agents. Partly holds for chat assistants. |
| B | Transformation is the hard part | **Holds**, with good evidence |
| C | AI fails because the business isn't ready | **Partly holds.** One cause among several. Cost, unclear value, risk and tech reliability are cited as often. |
| D | Nobody can describe the real workflow | **Plausible, thinly evidenced.** One strong source (RAND); no measurement. |
| E | No shared context for humans and agents | **Plausible, vendor-evidenced.** Only human-written context is shown to help, and only slightly, for coding agents. Auto-generated context hurt. |
| F | People resist a whole new way of working | **Mostly breaks.** Workers adopt faster than employers. Where resistance exists it is often rational. |

## What holds

**B. Transformation is the hard part: holds.**
- Breadth of adoption is rising while depth and profit impact are flat. US Fed Small Business Credit Survey (fieldwork Sep to Nov 2025): about half of small-employer AI users are "experimenting" and 7% "fully integrated", roughly 3% of all employer firms. EVIDENCE (search extract). <https://www.fedsmallbusiness.org/2026-report-on-employer-firms>
- ONS (2026): UK adoption roughly tripled since 2023, while its depth proxy (AI technologies per firm) barely moved. EVIDENCE (search extract). See 03-smb.md.
- McKinsey State of AI: share reporting any EBIT impact about 39% in 2025 and about 37% in 2026, while the share of $1B+ firms scaling agents rose from 27% to 40%. Self-reported consultancy survey. EVIDENCE (weak). <https://www.mckinsey.com/~/media/mckinsey/business%20functions/quantumblack/our%20insights/the%20state%20of%20ai/the-state-of-ai-in-2026-on-the-road-to-roi-aug-2026.pdf>
- Microsoft's 6,000-worker Copilot RCT: email time fell, meeting time did not. Changes that need several people to change together did not happen on their own. This is the cleanest evidence for the transformation half of the thesis. EVIDENCE. <https://www.microsoft.com/en-us/research/publication/shifting-work-patterns-with-generative-ai/>

**D. "Can't describe the workflow": the best support comes from one interview study.**
- RAND (Aug 2024, 65 experienced data scientists and engineers, interviews) names as root cause one: stakeholders misunderstand or miscommunicate the problem AI should solve. EVIDENCE (qualitative). <https://www.rand.org/pubs/research_reports/RRA2680-1.html>
- IDC attributes POC failure to organisational readiness (data, processes, infrastructure). Vendor-sponsored. OPINION. See 04-enterprise.md.
- No study I found measures how often clients cannot describe their workflow, or how much that predicts failure. The process-mining literature (06-what-goes-wrong.md) documents gaps between designed and actual processes, but not as an AI failure cause. This is a gap you could fill with your own client data.

**Over-automation for cost, and the reversals that follow, are well documented.**
- Commonwealth Bank of Australia cut 45 roles citing a voice bot, then reversed after the union showed call volumes were rising (Aug 2025). EVIDENCE (search extract). <https://ia.acs.org.au/article/2025/cba-reverses-ai-driven-job-cuts--admits--error-.html>
- Klarna headcount fell from 5,527 to 3,422 per its F-1, and the CEO later conceded "lower quality" service and rehired for quality (see 02 and 06). This supports "transformation is hard", but the failure was management's business case, not workers' readiness.

## What breaks

**A. "The tech is the easy part" breaks for agents.**
- Agent reliability collapses on repeated, multi-turn, policy-bound work, which is what business processes are. Salesforce's own CRMArena-Pro: about 58% single-turn success falling to about 35% multi-turn, and weak handling of confidential data (secondary summaries say near zero without prompting; check the paper). EVIDENCE. <https://arxiv.org/html/2505.18878v1>
- tau-bench retail: best listed model 69% on one try, 46% when it must succeed on all four (pass^4). EVIDENCE (fetched). Caveat: these are 2024 models (Claude 3.5 Sonnet, GPT-4o); current models score higher, but the pass^k drop pattern is the point. <https://raw.githubusercontent.com/sierra-research/tau-bench/main/README.md>
- Spider 2.0: best models solved about 17 to 21% of real enterprise text-to-SQL tasks, against about 91% on the older academic benchmark. Even with the data in place, querying it is hard. EVIDENCE (search extract). <https://arxiv.org/abs/2411.07763>
- At least half the named failures in 06-what-goes-wrong.md are the technology failing: hallucination (Moffatt v. Air Canada, NYC MyCity, Deloitte Australia, about 1,600 court decisions involving hallucinated citations by June 2026), prompt injection (EchoLeak, CVSS 9.3), destructive agent actions (Replit). A business with perfectly documented workflows would still have hit these. <https://www.canlii.org/en/bc/bccrt/doc/2024/2024bccrt149/2024bccrt149.html>
- Even inside Anthropic, an organisation as AI-native as any, engineers use Claude in about 59% of their work but say they can "fully delegate" only 0 to 20% of it. Supervision, not readiness, is the binding constraint. EVIDENCE (vendor self-study, n=132 survey, 53 interviews; fetched). <https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic>

**F. "People resist" mostly breaks.**
- Workers adopt ahead of employers. Microsoft/LinkedIn 2024 (n=31,000): 78% of AI users bring their own tools, 52% are reluctant to admit using it for important tasks. EVIDENCE (vendor survey; fetched). <https://www.microsoft.com/en-us/worklab/work-trend-index/ai-at-work-is-here-now-comes-the-hard-part>
- Microsoft Work Trend Index 2026 (n=20,000 AI users): 10% are skilled workers blocked by their organisation against 5% in ready organisations whose people are not ready; 13% are rewarded for redesigning work. Microsoft's own summary is that people are ready and the systems around them are not. EVIDENCE (vendor survey, self-report; fetched). <https://www.microsoft.com/en-us/worklab/work-trend-index/agents-human-agency-and-the-opportunity-for-every-organization>
- Where resistance exists, it looks rational: 53% of AI users worry that using AI on important work makes them look replaceable (same 2024 source). The CBA case shows staff being right about the bot.
- Many small firms are declining AI, not failing at it. Fed SBCS: a third of small employers have no plans to use AI; of those, over half say it is not applicable and 30% prefer not to. EVIDENCE (search extract). <https://www.fedsmallbusiness.org/2026-report-on-employer-firms>

**The official barrier data do not name the thesis's causes.** When ONS asks UK firms why they don't adopt AI, the top answers are difficulty identifying a use case (39%), cost (21%) and skills (16%). No official survey found asks about undocumented workflows or shared context. EVIDENCE (search extract). <https://www.ons.gov.uk/economy/economicoutputandproductivity/productivitymeasures/articles/managementpracticesandtheadoptionoftechnologyandartificialintelligenceinukfirms2023/2025-03-24> The OECD's December 2025 SME survey finds 31% of SMEs using generative AI, and the top barrier among non-adopters is "poor fit with our work" (57%). EVIDENCE (search extract). <https://www.oecd.org/en/publications/generative-ai-and-the-sme-workforce_2d08b99d-en.html>

**Training and encouragement do not reliably transfer.** A Kenyan RCT with 640 entrepreneurs found no average gain from an AI business mentor: it helped high-performing owners and hurt low performers. A Microsoft-authored training RCT at Gap found no average effect. Readiness programmes are not a proven fix either. EVIDENCE (search extract). See 03-smb.md and 05-inertia-and-education.md.

**Enterprise failure causes are as much economic and risk as readiness.** Gartner's forecast of over 40% of agentic projects cancelled by end-2027 cites cost, unclear business value and inadequate risk controls (FORECAST, poll of 3,412 webinar attendees). S&P Global's 2025 survey cites cost, privacy and security. <https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027> <https://www.ciodive.com/news/AI-project-fail-data-SPGlobal/742590/>

## What's contested

**C. "AI fails" itself is contested.** "Share of pilots reaching production" runs from 5% (MIT NANDA: 5% of organisations got custom tools into production with P&L impact; 52 interviews, 153 surveys, self-described preliminary) through 12% (IDC 2025) to 46% (IDC/Lenovo 2026, n=3,120). The same sponsor nearly quadrupled its own figure in a year. Wharton/GBK (n>800) reports 74% positive ROI. All are self-reported. The "95% of AI pilots fail" headline does not measure what it is quoted as measuring. <https://getdx.com/blog/the-ai-divide/> <https://www.businesswire.com/news/home/20260127255538/en/>

**Magnitude may be the real constraint, not readiness.** In Denmark (about 25,000 workers in 11 exposed occupations, administrative data), wide adoption with employer encouragement produced average time savings of about 3% and precise zero effects on earnings and hours. If the value of today's tools for typical tasks is small, "the business isn't ready" may be the wrong explanation for disappointing results. EVIDENCE (search extract). <https://econpapers.repec.org/RePEc:nbr:nberwo:33777> US TFP growth slowed to 0.8% in 2025 from 1.5% in 2024. EVIDENCE (search extract). Fair counters: TFP grew 1.0% a year over 2019-25, faster than 0.6% over 2007-19, and the productivity J-curve predicts measured gains lag intangible investment. <https://www.bls.gov/news.release/archives/prod3_03192026.pdf>

**E. Shared context: plausible, but "write it down for the agent" is not proven.**
- For: Anthropic's analysis of 1M API transcripts says complex enterprise deployment may be "constrained more by access to information than on underlying model capabilities". Vendor, inferred from input-length patterns. EVIDENCE (weak; fetched). <https://www.anthropic.com/research/anthropic-economic-index-september-2025-report>
- Mixed: a Feb 2026 study (Gloaguen et al., ETH Zurich) found that context files (AGENTS.md style) tended to reduce coding-agent task success and raised cost by more than 20%. But the drop came from LLM-generated files; developer-written files slightly improved success, and the authors advise short human-written files stating only minimal requirements. A Jan 2026 study found faster runs with no change in completion. This is closer to your thesis than it first looks: context written by people who know the work helps a little; context generated wholesale hurts. EVIDENCE (search extract, coding agents only). <https://arxiv.org/abs/2602.11988>
- Against: shared context is also a shared attack surface. MCP tool poisoning, the GitHub MCP exploit and Asana's MCP exposure of about 1,000 customers (2025) show that one store both humans and agents read and write is a security problem as well as a productivity one. See 04-enterprise.md.

**Human oversight is weaker than "humans and agents work together" implies.** In a 2026 RCT, 50 trained analysts followed a coin-flipped agent "lean" on 86% of analytical choices; experience did not protect them. Users accept 93% of Claude Code permission prompts. A shared context does not guarantee shared judgment. EVIDENCE (vendor research; fetched). <https://www.anthropic.com/research/agents-judgment-calls>

**Harm can arrive before the transformation does.** Firms adopting generative AI hired about 80% fewer juniors per quarter, and junior employment fell about 9% after six quarters while seniors were unaffected. The authors suggest firms may be cutting in anticipation, and the drop "may ultimately prove temporary". So "the business isn't ready" does not mean "nothing happens to people". EVIDENCE (working paper; fetched). <https://raw.githubusercontent.com/s-mahdihosseini/Website/b99fa2962dcc4c165bbc3c41dd283afa99c5ccfb/GenAI_SenBTC_May_2026.pdf> Aggregate unemployment effects remain undetectable (Anthropic CPS analysis; Dallas Fed: at most about 0.1 point of the unemployment rise). <https://www.anthropic.com/research/labor-market-impacts> <https://www.dallasfed.org/research/economics/2026/0106>

**"Freedom to be more human" has weak or negative early evidence.** An eight-month ethnography (Berkeley Haas, HBR Feb 2026) found AI time savings turned into task expansion and longer hours. Four experiments (Scientific Reports 2025, N=3,562) found AI collaboration raised performance but lowered intrinsic motivation on return to solo work. A job guarantee in Marienthal raised wellbeing, structure and status, suggesting work itself supplies things people miss when it goes. See 09 and 11. <https://newsroom.haas.berkeley.edu/ai-promised-to-free-up-workers-time-uc-berkeley-haas-researchers-found-the-opposite/> <https://docs.iza.org/dp16088.pdf>

## The working definitions

- **AI-native = one shared stored context both humans and agents read and write.** No framework found defines it this way. Telecom defines it by architecture (Nokia Bell Labs, from 2020), VCs by origin or dependency on models, consultancies by deployment breadth and self-reported ROI. Your definition is distinctive, which is useful for positioning, but you should present it as your definition, not the industry's. See 02-ai-native-definitions.md.
- **Legacy = humans only.** Close to an empty category among knowledge-work firms in the survey data; every maturity model starts at "some AI use". But it is not empty among small firms: a third of US small employers have no plans to use AI. "Legacy" is real in SMB, rare in enterprise.
- **Spectrum.** Matches all published maturity models. They measure position on it by breadth of use or self-reported readiness, not by context architecture.

## A thesis the evidence would support

Suggested rewrite, for you to test further:

> The technology is not the easy part, but it is improving faster than organisations change. Most firms are using AI widely and shallowly. Gains so far are small and mostly kept by workers as time, not by firms as profit. Agents fail on the multi-step, rule-bound work that business processes consist of, and humans defer to them more than they should. Moving from shallow to deep use needs coordinated changes to how work is organised, a store of shared context, and proof that it pays. Workers are usually ahead of their employers on adoption, and their caution is often justified.

Where to be careful in public writing:
1. Don't cite "95% of pilots fail", "70% of change programmes fail", "80% of AI projects fail" or "30 to 50% of RPA projects fail" as evidence. All four trace to weak or unscientific origins (see 12-facts-and-figures.md, DO NOT CITE).
2. Don't claim workers are the blocker. The evidence says the opposite more often.
3. Don't claim freed time makes people more human. The early evidence points to intensification. You can argue it should, and what it would take, but not that it does.
