INCOMPLETE: the shared web-search budget ran out part way through this track, and page fetching (WebFetch and curl) was blocked for every host tried (gartner.com, mckinsey.com, fortune.com, mlq.ai, aigl.blog, arxiv.org, sec.gov, wikipedia.org). Covered: the pilot-to-production statistics (MIT NANDA, Gartner x3, IDC/Lenovo 2025 and 2026, S&P Global, McKinsey 2025 and 2026, Deloitte 2026, BCG, RAND, Wharton/GBK) and vendor disclosures from Salesforce, Microsoft and ServiceNow. NOT covered: bank and retailer agent deployments (JPMorgan, Goldman, Bank of America Erica, Walmart), incident reports and post-mortems, the technical shared-context problem (RAG, semantic layers, MCP security, agent memory), procurement and governance timelines, and controlled ROI studies. Every finding below rests on search-engine summaries of the named pages, not on full reads of the reports. No quote could be verified.

# Track 3: Enterprise
_Last updated: 2026-11-06. Labels: EVIDENCE = measured/primary data; FORECAST = projection; OPINION = argument, vendor or consultancy view._

## Summary

- **There is no single "share of pilots reaching production" figure.** The widely cited numbers range from 5% to about 46%. They measure different things: organisations or projects, "reached production" or "showed P&L impact", custom tools or any GenAI. They come from different samples, most of them vendor-sponsored or self-selected. Stacking them as if they agree ("88 to 95% of pilots fail") is a category error.
- **The MIT NANDA "95%" figure is weak.** It comes from a self-described preliminary report built on 52 interviews, 153 survey responses and a review of about 300 public initiatives. It counts success only as measurable P&L impact from embedded or task-specific GenAI tools within roughly six months. The 5% applies to organisations getting custom enterprise tools into production with P&L impact. It does not measure "AI pilots" in general.
- **The Gartner figures are forecasts, not measurements.** "30% of GenAI projects abandoned after PoC by end of 2025" (July 2024) and ">40% of agentic AI projects cancelled by end of 2027" (June 2025) are routinely quoted as findings. The agentic forecast sits on a January 2025 poll of 3,412 webinar attendees. The press release does not say how the "only about 130 real agentic vendors" estimate was produced.
- **The IDC/Lenovo "88% of POCs don't reach production" (4 in 33) was contradicted a year later by the same sponsor-and-research-firm pair.** The Lenovo CIO Playbook 2026, with IDC fieldwork in September and October 2025 and n=3,120, says 46% of AI POCs have progressed into production. It is unclear whether the jump is real, a change of question, or a change of sample.
- **The stated causes of failure only partly support the thesis.** IDC blames organisational readiness (data, processes, IT infrastructure). RAND's interviews put "stakeholders misunderstand what problem needs solving" first. Gartner and S&P Global, however, put cost, unclear business value, risk controls, data privacy and security at the top. Those are economic and risk-governance problems, not workforce resistance.
- **Adoption keeps rising but profit impact is flat.** McKinsey's 2025 survey (n=1,993) found only 39% attribute any EBIT impact to AI, most of them less than 5%. The 2026 edition (n=1,719) reportedly puts positive EBIT impact at about 37%, essentially unchanged, while the share of $1B+ firms scaling agents rose from 27% to 40%.
- **Vendor disclosures show real paid production use, at a small share of the installed base.** Microsoft reported over 30 million paid M365 Copilot seats in July 2026 (secondary estimates: about 6 to 7% of paid commercial seats). Salesforce reported more than 9,500 paid Agentforce deals and Agentforce ARR above $500M by October 2025. ServiceNow raised its 2026 AI net-new-ACV target from $1B to $1.7B. These figures are real but are also each vendor's chosen metric.
- **Counter to the "pilot purgatory" story,** Wharton/GBK (n>800 US enterprise decision-makers, June to July 2025) reports 74% positive ROI and 72% formally tracking ROI. That is self-reported and unaudited, as are the failure statistics.

## Key findings

### The "pilot purgatory" statistics, report by report

**MIT NANDA, "The GenAI Divide: State of AI in Business 2025"**
- **[EVIDENCE (weak)]** Authors: Aditya Challapally, Chris Pease, Ramesh Raskar and Pradyumna Chari. The report is labelled "Preliminary Findings" (v0.1) and was published July/August 2025. Method: a review of 300+ publicly disclosed AI initiatives, structured interviews with representatives of 52 organisations, and survey responses from 153 senior leaders, fielded January to June 2025. Sources: AI Governance Library summary of the report (https://www.aigl.blog/state-of-ai-in-business-2025/); Virtualization Review, 19 Aug 2025 (https://virtualizationreview.com/articles/2025/08/19/mit-report-finds-most-ai-business-investments-fail-reveals-genai-divide.aspx). The PDF is hosted by MLQ (https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf), not on an MIT domain. I could not fetch it this session.
- **[EVIDENCE (weak)]** The headline funnel covers embedded or task-specific ("enterprise-grade") GenAI tools. About 60% of organisations evaluated them, about 20% reached pilot, and about 5% reached production with measurable P&L impact or "marked and sustained" productivity. The same report says over 80% of organisations had explored or piloted general tools such as ChatGPT or Copilot, which mainly improved individual productivity. Sources: DX newsletter "The AI Divide" (https://getdx.com/blog/the-ai-divide/); RCP Mag, 25 Aug 2025 (https://rcpmag.com/articles/2025/08/25/only-1-in-20-ai-investments-deliver-roi.aspx).
- **[EVIDENCE]** Press coverage did not report the sample consistently. Fortune (18 Aug 2025) described 150 interviews, a survey of 350 employees and 300 public deployments. Other summaries give 52 interviews and 153 survey responses. https://fortune.com/2025/08/18/mit-report-95-percent-generative-ai-pilots-at-companies-failing-cfo/
- **[OPINION]** Critics' main points (from search summaries of the critiques, not full reads):
  - The success test (marked, sustained P&L impact within about six months) is narrow and undefined, so efficiency gains count as failure.
  - The sample is small and opaque.
  - The report promotes NANDA's own agentic-web agenda, and its "connection to MIT is rather loose".

  Futuriom, Aug 2025 (https://www.futuriom.com/articles/news/why-we-dont-believe-mit-nandas-werid-ai-study/2025/08); arnon.dk (https://arnon.dk/mits-95-ai-failure-rate-is-wrong/); aioperator.io, "What the MIT study actually measured" (https://aioperator.io/blog/do-95-percent-ai-projects-fail). Those critics' further claims (that NANDA sells $250,000 memberships, and that the report's own graph was misread) appeared only in summaries of podcast and blog commentary. I have not verified them.

**Gartner (forecasts)**
- **[FORECAST]** 29 July 2024: at least 30% of GenAI projects will be abandoned after proof of concept by end of 2025. Stated reasons: poor data quality, inadequate risk controls, escalating costs and unclear business value. Trade coverage of the release cites a GenAI deployment cost range of $5M to $20M. https://www.gartner.com/en/newsroom/press-releases/2024-07-29-gartner-predicts-30-percent-of-generative-ai-projects-will-be-abandoned-after-proof-of-concept-by-end-of-2025 (coverage: https://www.intelligentcio.com/eu/2024/08/05/gartner-predicts-30-of-generative-ai-projects-will-be-abandoned-after-proof-of-concept-by-end-of-2025/)
- **[FORECAST]** 25 June 2025: over 40% of agentic AI projects will be cancelled by end of 2027, due to escalating costs, unclear business value or inadequate risk controls. Analyst Anushree Verma described most current projects as early-stage, hype-driven experiments. https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027
- **[OPINION]** Same release: "agent washing" (rebranding assistants, RPA and chatbots as agentic) is widespread. Gartner estimates only about 130 of thousands of agentic AI vendors offer genuine agentic capability. The release gives no method for this number. Same URL.
- **[EVIDENCE (weak: self-selected webinar poll)]** The release's survey basis is a January 2025 Gartner webinar poll of 3,412 attendees. 19% said their organisation had made significant agentic AI investments. Same URL.

**IDC / Lenovo**
- **[EVIDENCE (weak: vendor-sponsored)]** IDC's 2025 CIO Playbook ("It's Time for AI-nomics"), sponsored by Lenovo and published Feb 2025, found 88% of observed POCs did not make it to widescale deployment: of every 33 POCs, 4 graduated to production. IDC attributed this to low organisational readiness in data, processes and IT infrastructure. CIO.com, 2025 (https://www.cio.com/article/3850763/88-of-ai-pilots-fail-to-reach-production-but-thats-not-all-on-it.html); Lenovo release (https://www.businesswire.com/news/home/20250205462134/en). A secondary source gives n=2,920, which I have not verified.
- **[EVIDENCE (weak: vendor-sponsored)]** Lenovo CIO Playbook 2026 ("The Race for Enterprise AI"): IDC surveyed 3,120 IT and business decision-makers between 16 Sept and 17 Oct 2025. 46% of AI POCs have already progressed into production. Respondents projected $2.78 to $2.86 return per dollar, depending on regional edition. Business Wire, 27 Jan 2026 (https://www.businesswire.com/news/home/20260127255538/en/).

**S&P Global Market Intelligence**
- **[EVIDENCE (moderate: independent research firm; full methodology not seen)]** The share of companies abandoning most of their AI initiatives rose to 42% in 2025 from 17% the year before. The average organisation scrapped 46% of AI proofs of concept before production. Top obstacles were cost, data privacy and security risks. The survey had over 1,000 respondents (reported as 1,006 mid-level and senior IT and line-of-business staff in North America and Europe, attributed to S&P / 451 Research). Fieldwork dates are reported inconsistently (Oct to Nov 2024 vs March 2025). CIO Dive, 2025 (https://www.ciodive.com/news/AI-project-fail-data-SPGlobal/742590/); Fortune, 11 June 2025 (https://fortune.com/2025/06/11/ai-companies-employee-fatigue-failure/). I could not locate the primary S&P report.

**McKinsey, The State of AI**
- **[EVIDENCE (moderate: large online survey, self-reported, consultancy)]** 2025 edition ("Agents, innovation, and transformation", Nov 2025): n=1,993 participants in 105 countries, fielded 25 June to 29 July 2025.
  - 39% attribute any level of EBIT impact to AI, and most of those say under 5% of EBIT.
  - 62% are at least experimenting with AI agents.
  - In no business function do more than 10% say they are scaling agents.
  - "High performers" (5%+ of EBIT from AI) are about 6% of respondents.

  https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai
- **[EVIDENCE (moderate)]** 2026 edition ("On the road to ROI", Aug 2026): n=1,719 in 97 countries, fielded 4 May to 8 June 2026.
  - Among organisations with $1B+ revenue, the share scaling AI agents rose to 40% from 27%. Smaller organisations were flat at 22%.
  - Agent scaling is most common in IT (12%) and knowledge management (11%), and lowest in manufacturing (3%).
  - Positive EBIT impact is about 37%, roughly unchanged.

  PDF: https://www.mckinsey.com/~/media/mckinsey/business%20functions/quantumblack/our%20insights/the%20state%20of%20ai/the-state-of-ai-in-2026-on-the-road-to-roi-aug-2026.pdf. The figures come from secondary summaries (https://idm.net.au/node/15761; https://digitalstrategy-ai.com/mckinsey-state-of-ai-2026), not from my own read of the PDF. Treat them as provisional.

**Deloitte, State of AI in the Enterprise 2026**
- **[EVIDENCE (moderate: consultancy survey)]** Over 3,000 director-to-C-suite leaders directly involved in AI (one summary says 3,235 in 24 countries). Only 25% of respondents have moved 40% or more of their AI pilots into production. https://www.deloitte.com/us/en/about/press-room/state-of-ai-report-2026.html
- **[EVIDENCE (weak: figures conflict)]** On agentic AI, summaries of the same report disagree:
  - 23% report at least moderate use today, and 46% expect that within two years (https://marketscale.com/industries/software-and-technology/enterprise-ai-moves-from-pilot-to-production-in-2026-but-gaps-in-governance-and-talent-persist).
  - Close to three-quarters plan to deploy agentic AI within two years (https://www.deloitte.com/nl/en/about/press-room/state-of-ai-in-the-enterprise-2026.html).

  The "only 21% have mature governance for agents" figure appears only in third-party summaries. Not verified.

**BCG, "The Widening AI Value Gap" (Build for the Future 2025)**
- **[OPINION / EVIDENCE (weak: consultancy survey with self-assessed maturity)]** Over 1,250 senior executives across nine industries, Sept 2025. 5% are "future-built" and achieving bottom-line value at scale. About 60% are laggards and about 35% "scalers" (the 60/35 split is from secondary summaries). BCG names agentic AI as the main accelerator of the gap. https://web-assets.bcg.com/35/20/636ea73746f8bc91f106ca56ee7c/jpr-2501023-widening-ai-value-gap-vf.pdf ; coverage: https://www.artificialintelligence-news.com/news/value-gap-ai-investments-widening-dangerously-fast/

**RAND, "The Root Causes of Failure for Artificial Intelligence Projects and How They Can Succeed" (13 Aug 2024)**
- **[EVIDENCE (qualitative: interviews)]** Authors: Ryseff, De Bruhl and Newberry. Secondary sources say the study is based on interviews with 65 experienced data scientists and engineers. The five root causes include:
  - stakeholders misunderstanding or miscommunicating what problem AI should solve;
  - inadequate data and deployment infrastructure;
  - a focus on the latest technology over real user problems.

  https://www.rand.org/pubs/research_reports/RRA2680-1.html
- **[EVIDENCE: provenance note]** RAND's "more than 80% of AI projects fail, twice the rate of non-AI IT projects" is attributed in the report to "some estimates". RAND did not measure it. Same URL.

**Wharton / GBK Collective, "Accountable Acceleration" (28 Oct 2025)**
- **[EVIDENCE (moderate: annual survey, self-reported ROI)]** Over 800 US enterprise decision-makers, June to July 2025. 82% use GenAI at least weekly, 46% daily, 72% track structured ROI metrics, and 74% report positive ROI (+9 points). https://knowledge.wharton.upenn.edu/special-report/2025-ai-adoption-report ; https://www.businesswire.com/news/home/20251028556241/en

### Agentic and GenAI systems in production: what vendors disclose

- **[EVIDENCE (company-reported metric)]** Microsoft:
  - Q2 FY26 (28 Jan 2026): 15 million paid M365 Copilot seats among about 450 million M365 commercial seats (about 3.3%). https://www.directionsonmicrosoft.com/blog/microsoft-claims-15-million-paid-m365-copilot-seats
  - Q3 FY26 (29 Apr 2026): 20 million.
  - Q4 FY26 (July 2026): over 30 million (secondary estimate: about 6.6 to 6.7% of paid commercial seats). https://www.uctoday.com/unified-communications/microsoft-365-copilot-passes-30-million-paid-seats-as-cloud-and-ai-growth-power-record-quarter

  Microsoft discloses seats, not usage depth or unit economics.
- **[EVIDENCE (company-reported metric)]** Salesforce Q3 FY26 (quarter to 31 Oct 2025, reported 3 Dec 2025):
  - more than 18,500 Agentforce deals since launch, of which over 9,500 paid (+50% quarter on quarter);
  - Agentforce plus Data 360 ARR nearly $1.4B (+114% YoY);
  - Agentforce ARR above $500M (+330% YoY).

  https://www.salesforce.com/news/press-releases/2025/12/03/fy26-q3-earnings/ ; PDF: https://s205.q4cdn.com/626266368/files/doc_financials/2026/q3/CRM-Q3-FY26-Earnings-Press-Release.pdf. I could not retrieve later quarters (search budget exhausted).
- **[EVIDENCE (company-reported metric)]** ServiceNow:
  - Now Assist net new ACV topped $600M in Q4 2025, against a $1B+ target for 2026.
  - The target was raised to $1.5B at Q1 2026 and to $1.7B at Q3 2026.
  - 19 deals over $5M net new ACV in Q3 2026.

  Form 8-K Q3 FY2026: https://www.sec.gov/Archives/edgar/data/0001373715/000137371526000092/erq3fy26.htm ; Q4 2025 call coverage: https://finance.yahoo.com/news/servicenow-q4-earnings-call-highlights-024438096.html
- **[OPINION]** Reading: these are real paid deployments at scale, which contradicts the strong form of "pilot purgatory". But "paid deal", "seat" and "ACV" are bookings metrics. None of the three vendors discloses active usage, task completion or customer-side ROI. The Salesforce paid-deal count (9,500) is small relative to its customer base.

### Not covered in this pass
JPMorgan, Goldman Sachs, Bank of America (Erica), Walmart, incident reports and post-mortems, the technical shared-context problem (vector stores, semantic layers, knowledge graphs, MCP adoption and its prompt-injection and tool-poisoning issues, agent memory), procurement and security review timelines, and controlled ROI studies. The search budget ran out before these could be sourced. No claims are made on them here; see Open questions.

## Viral statistics traced

| Statistic as quoted | Where people cite it from | Where it actually comes from | How solid |
|---|---|---|---|
| "95% of AI pilots fail" | MIT, via Fortune (18 Aug 2025) | MIT NANDA preliminary report. 5% of organisations got custom or embedded GenAI tools into production with measurable P&L impact within about 6 months. Based on 52 interviews, 153 surveys and about 300 public cases. | Weak. Narrow success definition, small non-random sample, preliminary, and the unit is organisations not pilots. It says nothing about general-purpose tools, which 80%+ had tried. |
| "88% of POCs never reach production" / "4 in 33" | IDC | IDC CIO Playbook 2025, sponsored by Lenovo. "Observed" POCs, reason given as low readiness. | Weak to moderate. Vendor-sponsored, and the same pair reported 46% reaching production a year later. |
| "42% of companies abandoned most AI initiatives" | S&P Global | S&P Global Market Intelligence survey of about 1,006 IT and LOB respondents in North America and Europe | Moderate. Independent firm, but the primary report was not found and fieldwork dates conflict. "Most of their initiatives" is a company-level measure. |
| "46% of POCs scrapped" | S&P Global | Same survey, average per organisation | Moderate, same caveats. Do not confuse with Lenovo/IDC's "46% progressed into production" (2026). |
| "30% of GenAI projects abandoned after PoC" | Gartner | July 2024 forecast for end-2025 | A forecast. Often misquoted as a measured outcome. No outcome check published that I found. |
| "Over 40% of agentic projects cancelled" | Gartner | June 2025 forecast for end-2027 | A forecast. The quoted survey is a self-selected webinar poll. |
| "Only ~130 real agentic vendors" | Gartner | Same June 2025 release | Analyst estimate, method not published. |
| "80% of AI projects fail, twice IT" | RAND | RAND attributes it to "some estimates" | Second-hand. RAND's own contribution is qualitative interviews, not a rate. |
| "87% of data science projects never make it into production" | VentureBeat, 19 Jul 2019 | Commentators find it hard to trace to underlying data. Variants: 85% (Gartner analyst, 2017), 85.4% (Forbes, 2020). | Very weak. A pre-GenAI figure recycled into GenAI discussions. Sources: https://towardsdatascience.com/the-gap-between-data-science-and-the-organization-7cfa8b0e2be5 ; https://builtin.com/articles/why-machine-learning-projects-fail-data-science-engineering |

## Strongest counter-evidence

**Against the thesis ("tech is the easy part; the business isn't ready")**
- Gartner's stated reasons for both abandonment forecasts are escalating cost, unclear business value and inadequate risk controls (plus poor data quality in 2024). S&P's respondents named cost, data privacy and security as top obstacles. These are economics and risk problems. Better workflow description or less staff resistance would not necessarily fix them. (Gartner URLs above; https://www.ciodive.com/news/AI-project-fail-data-SPGlobal/742590/)
- Even the MIT report, often cited for "organisational" failure, frames its divide around tools that do not deliver P&L impact in narrow windows. Its strongest critics argue the time window, not the organisation, drives the result. (https://aioperator.io/blog/do-95-percent-ai-projects-fail)
- Where the thesis does get support:
  - IDC attributes low conversion to data, process and IT readiness.
  - RAND's first root cause is stakeholders misunderstanding what problem to solve, which is close to "nobody can describe the real workflow". RAND's sample is data scientists and engineers, so this is the builders' view of their clients.

**Against the mainstream "pilot purgatory" reading**
- Wharton/GBK: 74% of 800+ US enterprise decision-makers report positive ROI, and 72% track it formally.
- Lenovo/IDC 2026: 46% of POCs reached production.
- McKinsey 2026: 40% of $1B+ firms scaling agents.
- Paid vendor metrics: 30M Copilot seats, 9,500+ paid Agentforce deals, ServiceNow AI ACV target raised 70%.

All are self-reported or vendor metrics, but they are no weaker than the failure statistics they contradict.
- The failure and success statistics use incompatible denominators. A 5% org-level P&L metric (MIT), a 12% POC-level conversion (IDC 2025) and a 46% POC-level conversion (IDC 2026) can all be "true" at once. The honest statement is that conversion and profit impact are low and poorly measured, not that "95% fail".

## Open questions
1. Does the MIT NANDA report itself say that purchased vendor tools succeed about twice as often as internal builds, and that the core barrier is a "learning gap" (tools that do not retain context or adapt)? Both are widely repeated. I could not verify either this session. If true, the second is a technology limitation, which cuts against "tech is the easy part".
2. Did Gartner ever publish an outcome check on its "30% abandoned by end of 2025" forecast?
3. Why did IDC/Lenovo's POC-to-production rate jump from 12% to 46% in one year? Same question, same sampling frame?
4. Salesforce Q1 and Q2 FY27 Agentforce paid-deal and ARR figures, and churn or renewal data. Not retrieved.
5. Banks and retail: JPMorgan (LLM Suite users, stated AI value), Goldman (coding agents), Bank of America (Erica volumes), Walmart (agents). Need primary investor-day or earnings sources.
6. Incident and post-mortem record for agents in production in 2025 and 2026 (public outages, data deletion, wrong customer commitments, legal rulings).
7. Shared-context technical evidence: measured RAG failure rates on enterprise corpora, MCP adoption numbers, published MCP vulnerabilities (prompt injection, tool poisoning), and benchmarks of agent memory.
8. Procurement and security review: any survey with real numbers on months from pilot to signed contract, and on how often security or legal review blocks deployment.
9. Controlled ROI evidence in enterprises (field experiments, filings) as opposed to vendor TEI studies.

## What's genuinely uncertain
- **The true production conversion rate.** Credible-looking sources put it anywhere between 5% and about 50%, depending on unit and definition. No source in this pass uses a random sample with audited outcomes.
- **Whether ROI is rising.** McKinsey shows flat EBIT impact (about 39% in 2025, about 37% in 2026) while Wharton shows rising self-reported ROI (74%, +9 points). Both are self-reports from different populations.
- **How much "agentic" production is real agents vs relabelled assistants.** Gartner's own 130-vendor estimate has no published method.
- **Whether vendor bookings metrics (seats, paid deals, ACV) translate into usage and customer value.** No vendor discloses usage depth.

## Numbers for the facts file

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| 5% (95% "fail") | Orgs whose custom or embedded GenAI tools reached production with measurable P&L impact (funnel 60% evaluated, 20% piloted, 5% production) | MIT NANDA, GenAI Divide | https://getdx.com/blog/the-ai-divide/ (summary); PDF at mlq.ai | Jul/Aug 2025 | Weak: preliminary, 52 interviews + 153 surveys + ~300 public cases, ~6-month P&L window |
| 30% | GenAI projects to be abandoned after PoC by end-2025 | Gartner press release | https://www.gartner.com/en/newsroom/press-releases/2024-07-29-gartner-predicts-30-percent-of-generative-ai-projects-will-be-abandoned-after-proof-of-concept-by-end-of-2025 | 29 Jul 2024 | FORECAST |
| >40% | Agentic AI projects cancelled by end-2027 | Gartner press release | https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027 | 25 Jun 2025 | FORECAST |
| ~130 | Vendors with genuine agentic capability, out of "thousands" | Gartner, same release | same | 25 Jun 2025 | Analyst estimate, no method |
| 19% (n=3,412) | Orgs with significant agentic investment | Gartner webinar poll, Jan 2025 | same | 25 Jun 2025 | Self-selected webinar audience |
| 88% / 4 of 33 | Observed AI POCs not reaching widescale deployment | IDC CIO Playbook 2025 (Lenovo-sponsored) | https://www.cio.com/article/3850763/88-of-ai-pilots-fail-to-reach-production-but-thats-not-all-on-it.html | Feb/Mar 2025 | Vendor-sponsored, n unverified |
| 46% | AI POCs progressed into production | Lenovo CIO Playbook 2026 (IDC, n=3,120, fieldwork 16 Sep-17 Oct 2025) | https://www.businesswire.com/news/home/20260127255538/en/ | 27 Jan 2026 | Vendor-sponsored |
| 42% (from 17%) | Companies abandoning most of their AI initiatives | S&P Global Market Intelligence (n≈1,006, NA + Europe) | https://www.ciodive.com/news/AI-project-fail-data-SPGlobal/742590/ | 2025 | Primary report not seen, fieldwork dates conflict |
| 46% | Average share of AI POCs scrapped before production | S&P Global MI | same | 2025 | As above |
| 39% | Respondents attributing any EBIT impact to AI (most <5%) | McKinsey State of AI 2025 (n=1,993) | https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai | Nov 2025 | Self-reported, consultancy |
| ≤10% | Max share scaling agents in any single function | McKinsey 2025 | same | Nov 2025 | Self-reported |
| 40% (from 27%) | $1B+ revenue orgs scaling AI agents | McKinsey State of AI 2026 (n=1,719) | https://www.mckinsey.com/~/media/mckinsey/business%20functions/quantumblack/our%20insights/the%20state%20of%20ai/the-state-of-ai-in-2026-on-the-road-to-roi-aug-2026.pdf | Aug 2026 | Via secondary summaries, verify in PDF |
| 25% | Respondents who moved 40%+ of AI pilots into production | Deloitte State of AI in the Enterprise 2026 (n>3,000) | https://www.deloitte.com/us/en/about/press-room/state-of-ai-report-2026.html | early 2026 | Consultancy survey |
| 5% | "Future-built" companies achieving AI value at scale | BCG Widening AI Value Gap (n>1,250) | https://web-assets.bcg.com/35/20/636ea73746f8bc91f106ca56ee7c/jpr-2501023-widening-ai-value-gap-vf.pdf | Sep 2025 | Consultancy maturity typology |
| 74% | Enterprise leaders reporting positive GenAI ROI | Wharton/GBK (n>800 US) | https://knowledge.wharton.upenn.edu/special-report/2025-ai-adoption-report | 28 Oct 2025 | Self-reported ROI |
| 80% | "AI projects fail", cited by RAND | RAND RRA2680-1 citing "some estimates" | https://www.rand.org/pubs/research_reports/RRA2680-1.html | 13 Aug 2024 | Second-hand estimate, not RAND's measurement |
| 30M+ | Paid M365 Copilot seats (~6.6-6.7% of paid commercial seats, analyst estimate) | Microsoft Q4 FY26 earnings call | https://www.uctoday.com/unified-communications/microsoft-365-copilot-passes-30-million-paid-seats-as-cloud-and-ai-growth-power-record-quarter | Jul 2026 | Company metric, secondary report |
| 15M | Paid M365 Copilot seats, of ~450M commercial | Microsoft Q2 FY26 | https://www.directionsonmicrosoft.com/blog/microsoft-claims-15-million-paid-m365-copilot-seats | 28-29 Jan 2026 | Company metric |
| 9,500+ / >$500M | Paid Agentforce deals / Agentforce ARR | Salesforce Q3 FY26 release | https://www.salesforce.com/news/press-releases/2025/12/03/fy26-q3-earnings/ | 3 Dec 2025 | Company metric |
| $1.7B | ServiceNow 2026 AI net new ACV target (raised from $1B) | ServiceNow Q3 2026 8-K | https://www.sec.gov/Archives/edgar/data/0001373715/000137371526000092/erq3fy26.htm | Oct 2026 | Company target, not revenue |

## Verbatim quotes
None. Page fetching was blocked for every host tried this session, so no wording could be confirmed against a fetched page. Search-result snippets contained candidate quotes (for example Satya Nadella on 30 million paid Copilot seats, and Gartner's Anushree Verma on hype-driven agentic experiments). Under the brief's rules these are paraphrased above, not quoted. Re-fetch the Gartner press release and the Microsoft FY26 Q4 transcript to capture them verbatim.

## Sources worth reading in full
1. MIT NANDA, "The GenAI Divide" PDF (https://mlq.ai/media/quarterly_decks/v0.1_State_of_AI_in_Business_2025_Report.pdf): the most cited and most misread source. Read the methodology page and funnel chart before using "95%".
2. McKinsey, "The state of AI in 2026: On the road to ROI" (PDF above): the largest repeated survey, with year-on-year agent-scaling and EBIT data.
3. RAND RRA2680-1 (https://www.rand.org/pubs/research_reports/RRA2680-1.html): the only qualitative, non-vendor study of root causes. The closest evidence on "can't describe the problem".
4. Gartner, 25 June 2025 press release: the source of the 40%, 130-vendor and agent-washing claims. Read it to see how thin the basis is.
5. Lenovo CIO Playbook 2025 vs 2026 (Business Wire links above): the same sponsor shows conversion moving from 12% to 46%, a useful case study in survey instability.
6. Wharton/GBK "Accountable Acceleration" (https://knowledge.wharton.upenn.edu/special-report/2025-ai-adoption-report): the strongest large-sample counterweight to the failure narrative.
7. Futuriom critique of MIT NANDA (https://www.futuriom.com/articles/news/why-we-dont-believe-mit-nandas-werid-ai-study/2025/08): a concise statement of the methodological objections.
8. ServiceNow Q3 2026 8-K (SEC link above): filing-grade figures on enterprise AI bookings.
