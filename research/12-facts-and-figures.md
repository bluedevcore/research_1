# 12. Facts and figures

_Compiled 2026-11-06 from the "Numbers for the facts file" tables in track files 02 to 11. Every row has a source, URL and date. Read the reliability note before using any number._

## How to read this file

- **Basis.** This session's network policy blocked page fetches for most hosts. Rows whose reliability note says "search summary", "search extract" or "snippet" were taken from search-engine extracts that cite the URL, not from reading the page. Rows from anthropic.com, microsoft.com and raw.githubusercontent.com were read directly.
- **Verification.** 29 of the most striking figures were re-checked in `verification.md`: 9 confirmed by re-fetching the page, 17 corroborated by an independent search, 2 corrected, 1 not confirmed. The corrected and unconfirmed ones are listed in DO NOT CITE at the end.
- **Labels.** Vendor and consultancy survey numbers are weak evidence at best. Exposure measures and analyst predictions are forecasts. The track files carry the EVIDENCE / FORECAST / OPINION labels for each finding.
- **Duplicates.** Some figures appear in more than one track table (e.g. Humlum and Vestergaard, MIT NANDA). They are left in place because each track notes a different use.

## Headline figures at a glance (all verified or corroborated in the verification pass)

| Figure | What it measures | Source | URL | Date | Status |
|---|---|---|---|---|---|
| 5% | Custom enterprise GenAI tools reaching production with P&L impact (self-selected sample) | MIT NANDA, GenAI Divide | https://www.theregister.com/2025/08/18/generative_ai_zero_return_95_percent | Jul-Aug 2025 | Corroborated; weak source |
| 46% | AI POCs progressed to production, n=3,120 | IDC for Lenovo CIO Playbook 2026 | https://www.businesswire.com/news/home/20260127255538/en/ | Jan 2026 | Corroborated; vendor-sponsored |
| 37% | Respondents attributing any EBIT impact to AI, n=1,719 | McKinsey State of AI 2026 | https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai | Aug 2026 | Corroborated; self-report |
| 27% to 40% | $1B+ firms scaling AI agents, 2025 to 2026 | McKinsey State of AI 2026 | https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai | Aug 2026 | Corroborated; self-report |
| 46% / 7% | Small employer firms using AI / users "fully integrated" | Fed Small Business Credit Survey | https://www.fedsmallbusiness.org/2026-report-on-employer-firms | 2026 | Corroborated (7% via secondary) |
| ~10% to ~17% | US firms using AI before/after BTOS wording change, Nov 2025 | St Louis Fed on Census BTOS | https://www.stlouisfed.org/on-the-economy/2026/jun/measuring-ai-adoption-firms-how-you-ask-matters | Jun 2026 | Corroborated; corrected from 9-18% |
| 2.8% (about 3%) | Self-reported time savings; earnings and hours effects precisely zero | Humlum and Vestergaard, NBER w33777 | https://econpapers.repec.org/RePEc:nbr:nberwo:33777 | May 2025 | Corroborated |
| 0.8% vs 1.5% | US private nonfarm TFP growth 2025 vs 2024 | BLS | https://www.bls.gov/news.release/archives/prod3_03192026.pdf | 19 Mar 2026 | Corroborated |
| ~9% / ~80% | Junior employment fall after six quarters / fewer junior hires per quarter at GenAI adopters | Hosseini and Lichtinger | https://raw.githubusercontent.com/s-mahdihosseini/Website/b99fa2962dcc4c165bbc3c41dd283afa99c5ccfb/GenAI_SenBTC_May_2026.pdf | May 2026 | Confirmed (re-fetched) |
| ~19% | 22-25 year olds in AI-exposed jobs below counterfactual (ADP) | Stanford Digital Economy Lab | https://digitaleconomy.stanford.edu/news/canariesaug26/ | 12 Aug 2026 | Corroborated; descriptive |
| 86% | Analysts following an agent's coin-flipped lean, n=50 | Anthropic RCT | https://www.anthropic.com/research/agents-judgment-calls | 27 Oct 2026 | Confirmed; vendor research |
| 0.692 to 0.462 | Agent success, one try vs all four tries (tau-bench retail, 2024 model) | Sierra tau-bench | https://raw.githubusercontent.com/sierra-research/tau-bench/main/README.md | 2024 | Confirmed |
| ~58% to ~35% | LLM agent success single-turn vs multi-turn CRM tasks | Salesforce CRMArena-Pro | https://arxiv.org/abs/2505.18878 | May 2025 | Corroborated; vendor benchmark |
| 17.0% vs 91.2% | Enterprise text-to-SQL vs academic benchmark success | Spider 2.0 | https://arxiv.org/abs/2411.07763 | Nov 2024 | Corroborated |
| 78% / 52% / 53% | AI users bringing own AI / reluctant to admit use / worry about looking replaceable, n=31,000 | Microsoft and LinkedIn WTI 2024 | https://www.microsoft.com/en-us/worklab/work-trend-index/ai-at-work-is-here-now-comes-the-hard-part | May 2024 | Confirmed; vendor survey |
| 10% vs 5% | Skilled AI users blocked by org vs ready orgs with unready people, n=20,000 | Microsoft WTI 2026 | https://www.microsoft.com/en-us/worklab/work-trend-index/agents-human-agency-and-the-opportunity-for-every-organization | May 2026 | Confirmed; vendor survey |
| 59% / 0-20% | Share of work using Claude / share engineers can fully delegate | Anthropic internal study | https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic | Dec 2025 | Confirmed; vendor self-study |
| 57% | Employees hiding AI use, n=48,000+, 47 countries | KPMG and University of Melbourne | https://mbs.edu/news/global-study-reveals-trust-of-ai-remains-a-critical-challenge | Apr 2025 | Corroborated |
| 52% | US adults more concerned than excited about AI, n=3,488 | Pew Research Center | https://www.pewresearch.org/short-reads/2026/08/18/young-adults-in-the-us-are-increasingly-wary-of-ai/ | Aug 2026 | Corroborated |
| 30M+ | Paid Microsoft 365 Copilot seats | Microsoft FY26 Q4 call | https://www.uctoday.com/unified-communications/microsoft-365-copilot-passes-30-million-paid-seats-as-cloud-and-ai-growth-power-record-quarter | 29 Jul 2026 | Corroborated; secondary |
| 5,527 to 3,422 | Klarna full-time employees, end-2022 to end-2024 | Klarna F-1 | https://www.bankingdive.com/news/klarna-buy-now-pay-later-bnpl-ai-workforce-ipo/742703/ | Mar 2025 | Corroborated |
| ~1,600 | Court decisions involving AI-hallucinated content, 35 countries | Charlotin database via AFP | https://www.malaymail.com/news/tech-gadgets/2026/06/16/do-your-job-global-courts-face-rising-tide-of-ai-generated-fake-cases-and-quotes/223865 | Jun 2026 | Corroborated; crowd-sourced |

## Track 1. AI-native definitions (from `02-ai-native-definitions.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| 77% vs 12% | Share of Anthropic first-party API transcripts showing automation vs augmentation patterns | Anthropic Economic Index | https://www.anthropic.com/research/anthropic-economic-index-september-2025-report | 2025-09-15 | Vendor data, 1M transcripts (Aug 2025), classifier-based. Fetched + grep-verified |
| 0.38 | Elasticity of output to input token length (basis for the "context bottleneck" inference) | Anthropic Economic Index | same | 2025-09-15 | Inferential; author interpretation. Fetched |
| 59% (from 28%) | Share of their work Anthropic engineers use Claude for, self-reported | Anthropic | https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic | 2025-12-02 | Self-report, n=132. Fetched + grep-verified |
| 0-20% | Share of work most Anthropic engineers say they can "fully delegate" | Anthropic | same | 2025-12-02 | Self-report. Fetched + grep-verified |
| 27% | Claude-assisted work that "wouldn't have been done otherwise" | Anthropic | same | 2025-12-02 | Self-estimate. Fetched + grep-verified |
| 844 of 31,000 | Leaders classed as Frontier Firm, of total respondents | Microsoft WTI 2025 | https://www.microsoft.com/en-us/worklab/work-trend-index/2025-the-year-the-frontier-firm-is-born | 2025-04-23 | Vendor survey (Edelman); self-classification. Fetched |
| 24% / 12% | Leaders reporting org-wide AI deployment / still in pilot | Microsoft WTI 2025 | same | 2025-04-23 | Vendor survey. Fetched + grep-verified |
| 19% | AI users in the "Frontier" zone (high individual and organisational readiness) | Microsoft WTI 2026 | https://www.microsoft.com/en-us/worklab/work-trend-index/agents-human-agency-and-the-opportunity-for-every-organization | 2026-05-05 | n=20,000 AI users, 10 markets, self-report. Fetched |
| 67% vs 32% | Share of modelled "AI impact" from organisational vs individual factors | Microsoft WTI 2026 | same | 2026-05-05 | Random-forest importance on self-report; associational. Fetched |
| 13% | AI users rewarded for reinventing work with AI even if results aren't met | Microsoft WTI 2026 | same | 2026-05-05 | Self-report. Fetched |
| 15x | Year-on-year growth in active agents in Microsoft 365 | Microsoft WTI 2026 | same | 2026-05-05 | Vendor telemetry, no absolute counts. Fetched |
| 25% vs 14% | Frontier vs other professionals saying agent workflows/handoffs are documented at org level | Microsoft WTI 2026 | same | 2026-05-05 | Self-report. Fetched |
| 700 | FTE customer service agents Klarna said its AI assistant replaced | Klarna via eMarketer | https://www.emarketer.com/content/klarna-backtracks-ai-customer-service-plans | 2024-02 (claim) | Company claim; search summary only |
| ~9,000 to ~5,000 | Salesforce support headcount, per Benioff | Fortune | https://fortune.com/2025/09/02/salesforce-ceo-billionaire-marc-benioff-ai-agents-jobs-layoffs-customer-service-sales/ | 2025-09-02 | CEO podcast remark; no timeframe; search summary only |
| "a couple of hundred" | IBM HR roles replaced by AI | Entrepreneur citing WSJ | https://www.entrepreneur.com/business-news/ibm-ceo-ai-replaced-hundreds-of-human-resources-staff/491341 | 2025-05 | CEO statement; search summary only |
| $400,000 ($225k + $175k) | SEC civil penalties, Delphia and Global Predictions AI-washing settlements | SEC press release 2024-36 | https://www.sec.gov/newsroom/press-releases/2024-36 | 2024-03-18 | Regulatory action; search extract |
| >70% | Share of Presto Voice orders needing human intervention, per SEC case | SEC settlement via law-firm summaries | https://www.dandodiary.com/2025/01/articles/artificial-intelligence/sec-files-ai-washing-enforcement-action-against-restaurant-technology-company/ | 2025-01-14 | Regulatory finding as reported; SEC primary not seen |
| $40M+ / ~0% | Raised by Nate on AI claims / alleged real automation rate | DOJ SDNY press release | https://www.justice.gov/usao-sdny/pr/tech-ceo-charged-artificial-intelligence-investment-fraud-scheme | 2025-04-09 | Allegations in an indictment, not findings |
| 5 | Companies in FTC Operation AI Comply | FTC press release | https://www.ftc.gov/news-events/news/press-releases/2024/09/ftc-announces-crackdown-deceptive-ai-claims-schemes | 2024-09-25 | Regulatory action; search extract |
| ~130 | Vendors with genuine agentic capability, of thousands claiming it | Gartner press release | https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027 | 2025-06-25 | Analyst estimate, no method |
| 5,527 to 3,422 | Klarna full-time employees, end-2022 to end-2024 | Klarna F-1, via press | https://www.sec.gov/Archives/edgar/data/2003292/000162828025012824/klarnagroupplcf-1.htm | 2025-03 | Filing figure seen only in secondary reports |
| 2.3M / two-thirds | Chats handled by Klarna's assistant in first month / share of all service chats | Klarna via Euronews | https://www.euronews.com/2024/02/28/klarnas-ai-bot-is-doing-the-work-of-700-employees-what-will-happen-to-their-jobs | 2024-02-28 | Company claim |
| ~10% | Decline in Duolingo US daily active users linked to the AI-first memo | Morgan Stanley via iTiger | https://www.itiger.com/news/2549526150 | 2025 | Sell-side analyst attribution |
| 721 | Firms in MIT CISR AI maturity survey (2022) | MIT CISR | https://cisr.mit.edu/sites/default/files/2024-12/EnterpriseAIMaturityModel_CISRpressrelease_121924_0.pdf | 2024-12-19 | Pre-genAI; search summary only |

## Track 2. SMB (from `03-smb.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| ~10% to ~17% (corrected in verification) | US firms using AI, before vs after BTOS question change (17 Nov 2025) | Ramp AI Index; Census wording note | https://ramp.com/data/ai-index-january-2026 | 14 Jan 2026 | Level shift is a wording artefact. Search-summary only |
| ~18% | US firms using AI, year-end 2025 (new wording) | Fed FEDS Note | https://www.federalreserve.gov/econres/notes/feds-notes/monitoring-ai-adoption-in-the-u-s-economy-20260403.html | 3 Apr 2026 | Official staff analysis of BTOS. Search-summary only |
| ~19.8% | US firms using AI, period ending 3 May 2026 | Census Bureau story | https://census.gov/library/stories/2026/05/ai-use-businesses.html | May 2026 | Official. Search-summary only |
| <20% | US firms with 1-4 employees using AI (ceiling, not point) | Census Bureau story | https://census.gov/library/stories/2026/05/ai-use-businesses.html | May 2026 | Census publishes as a band |
| 46% | US small employer firms whose business or employees use AI | Fed SBCS 2026 Report on Employer Firms | https://www.fedsmallbusiness.org/2026-report-on-employer-firms | Mar 2026 (fieldwork Sep-Nov 2025) | Convenience sample, weighted. Includes employees' use |
| 7% | Share of SBCS AI-using firms "fully integrated" (~3% of all employer firms, my arithmetic) | Fed SBCS 2026 | https://www.fedsmallbusiness.org/2026-report-on-employer-firms | Mar 2026 | Self-assessed. Search-summary only |
| 71% | SBCS AI users reporting higher productivity | Fed SBCS 2026; Cook speech | https://www.federalreserve.gov/newsevents/speech/cook20260624a.htm | 24 Jun 2026 | Self-report |
| >50% / 30% | Of SBCS firms with no AI plans: "not applicable" / "prefer not to use" | Fed SBCS 2026 | https://www.fedsmallbusiness.org/2026-report-on-employer-firms | Mar 2026 | Search-summary only |
| 24% | US small employers using AI (21% of <10 employees; 48% of >50) | NFIB Small Business and Technology Survey | https://www.nfib.com/?p=38888 | 25 Jun 2025 | Random draw of 20,000 members by email. Size split from secondary summary |
| 98% | NFIB AI users reporting no change in employee numbers | NFIB | https://www.nfib.com/?p=38888 | 25 Jun 2025 | Search-summary only |
| 58% | US small businesses saying they use generative AI | US Chamber / Teneo 2025 | https://www.uschamber.com/technology/the-impact-of-technology-on-u-s-small-business | 2025 | n and method not found |
| 98% | US small businesses using any AI-enabled tool | US Chamber 2024 edition | https://www.uschamber.com/technology/the-impact-of-technology-on-u-s-small-business | Sep 2024 | Measures software features, not adoption. Do not cite as adoption |
| 55% (from 39%) | Small businesses "currently using" AI | Thryv | https://investor.thryv.com/news/news-details/2025/AI-Adoption-Among-Small-Businesses-Surges-41-in-2025-According-to-New-Survey-from-Thryv/ | 17 Jul 2025 | Vendor, n=540, revenue floor $100k |
| 76% | Goldman 10KSB participants using AI | Goldman Sachs 10KSB Voices (Babson / David Binder) | https://www.businesswire.com/news/home/20260317141697/en/Survey-Small-Businesses-Embrace-AI-But-Need-Training-and-Support-to-Fully-Harness-It | 17 Mar 2026 | n=1,256 programme alumni. Not representative |
| 46.6% | US businesses with paid AI spend on Ramp | Ramp AI Index | https://ramp.com/data/ai-index-january-2026 | 14 Jan 2026 | Ramp customers only, tech-forward |
| 69% | Firms using AI, executive panels in US/UK/DE/AU | NBER w34836 | https://www.nber.org/papers/w34836 | Feb/Mar 2026 | n about 6,000. Working paper |
| >80% | Firms in that panel reporting no AI impact on employment or productivity | NBER w34836 | https://www.nber.org/papers/w34836 | Feb/Mar 2026 | Search-summary only |
| ~12% to ~35% | UK firms with 10+ employees using AI, late 2023 to mid-2026 | ONS AI in UK businesses 2023-2026 | https://www.ons.gov.uk/businessindustryandtrade/business/businessservices/articles/artificialintelligenceinukbusinesses/2023to2026 | 20 Jul 2026 | Official. Search-summary only |
| 29% / 28% / 49% | UK firms using AI, June 2026: all / 0-9 employees / 250+ | ONS (BICS) | same as above | Jul 2026 | Official. Search-summary only |
| 1.6 | AI tools per UK adopter | TNW on ONS | https://thenextweb.com/news/uk-ai-adoption-widening-not-deepening-ons-2026 | Jul 2026 | Not confirmed in ONS tables |
| 4% | UK AI-using firms reporting headcount fell due to AI | ONS BICS | https://www.ons.gov.uk/businessindustryandtrade/business/businessservices/bulletins/businessinsightsandimpactontheukeconomy/8january2026 | 8 Jan 2026 | Attribution to bulletin inferred |
| 39% / 21% / 16% | UK barriers 2023: use cases / cost / skills | ONS management practices article | https://www.ons.gov.uk/economy/economicoutputandproductivity/productivitymeasures/articles/managementpracticesandtheadoptionoftechnologyandartificialintelligenceinukfirms2023/2025-03-24 | 24 Mar 2025 | Official. Search-summary only |
| 16% overall; 14% micro | UK businesses using AI, 2025 | DSIT AI Adoption Research (IFF / Technopolis, n=3,500 CATI) | https://assets.publishing.service.gov.uk/media/6960f3924343a0da370869ba/AI_Adoption_Research_Report.pdf | 2025 (pub. ~Jan 2026) | Official-commissioned. Search-summary only |
| 32% (vs 16%) | UK businesses using at least one AI technology, 2026 | DSIT AI Adoption Survey 2026 (n=3,503 CATI) | https://www.gov.uk/government/publications/ai-adoption-survey-2026/ai-adoption-survey-report-2026-executive-summary | 29 Oct 2026 | Micro figure not obtained |
| 20.0% (13.5% in 2024) | EU enterprises with 10+ employees using AI, 2025 | Eurostat | https://ec.europa.eu/eurostat/statistics-explained/index.php/Use_of_artificial_intelligence_in_enterprises | Dec 2025 | Excludes <10 employees |
| 17.0% / 30.4% / 55.0% | EU AI use 2025: small / medium / large | Eurostat | same | Dec 2025 | Search-summary only |
| 26.7% | Scottish businesses using AI, Sep 2025 (14.0% Sep 2023) | Scottish Government BICS | https://www.gov.scot/publications/scottish-economic-bulletin-december-2025/pages/6/ | Dec 2025 | Scotland only |
| ~11% / 21% / 41% | EU AI use 2024: small / medium / large (so +6 vs +14 points to 2025) | Eurostat via secondary | https://ioplus.nl/en/posts/ai-usage-soars-in-european-companies | Dec 2025 | Secondary; check isoc_eb_ai table |
| 31% (24% JP to 39% DE) | SMEs using generative AI, 7 OECD countries, late 2024 | OECD, Generative AI and the SME Workforce, n>5,000 | https://www.oecd.org/en/publications/generative-ai-and-the-sme-workforce_2d08b99d-en.html | Dec 2025 | Official IO survey; frame not seen. Search extract |
| 57% | Non-adopting SMEs citing poor fit with their work | OECD, same | same | Dec 2025 | Search extract |
| 83% / 9% / 6% | Adopting SMEs: no staffing effect / decrease / increase | OECD, same | same | Dec 2025 | Search extract |
| $10,600/yr | Mean SMB spend on AI tools, services and initiatives (n=241) | Clarify Capital | https://clarifycapital.com/small-business-ai-spending | Apr 2026 | Lender survey; mean skewed by big spenders |
| 71% (from 41%) | SMBs paying for AI (n=363) | Clarify Capital | https://clarifycapital.com/small-business-ai-spending | Jul 2026 | Lender survey. Search extract |
| £93 to £288 | Mean AI spend per UK small business, Q2 2024 to Q2 2026 | Capital on Tap via PPC Land | https://ppc.land/one-in-three-small-business-owners-raided-personal-savings-to-pay-for-ai/ | 2026 | Card provider; method not seen; secondary |
| ~€160/month | Average AI tool bill per UK/EU SMB customer, 2024 | Spendesk | https://ffnews.com/blog/2024/12/13/spending-on-ai-tools-by-uk-smbs-grows-fivefold-in-past-two-years-according-to-spendesk-data | Dec 2024 | Vendor customer data |
| $1,500-$25,000 + $50-$2,000/mo | Agency-quoted SMB AI automation build + running cost | Agency blogs | https://www.solulab.com/ai-automation-cost-for-small-businesses/ | 2025-26 | OPINION; sellers' price lists |
| 48% / 13% | MSPs ranking AI as clients' top need / earning meaningful AI revenue | Kaseya State of the MSP (n>1,000) | https://www.itpro.com/technology/artificial-intelligence/ai-demand-soars-as-traditional-deal-sizes-shrink-kaseya-reports | 2025-26 | Vendor survey of MSPs. Search extract |
| ~50% | MSPs feeling ready to guide SMBs in AI deployment | OpenText (n>1,000 MSPs) | https://s23.q4cdn.com/197378439/files/doc_news/OpenText-Cybersecurity-Finds-92-of-Managed-Service-Providers-See-AI-Driven-Growth-But-Readiness-Gap-Widens-2025.pdf | 2025 | Vendor survey. Search extract |
| 42% to 28% | SMBs using AI, 2024 to 2025 | NEXT Insurance (n=1,500) | https://stacker.com/stories/small-business/small-business-ai-adoption-declines-just-28 | Apr 2025 | Insurer survey; conflicts with all official series |
| 14% | Goldman 10KSB owners with AI embedded across core operations | Goldman 10KSB via Fortune | https://fortune.com/2026/03/18/small-business-ai-slow-integration-across-operations/ | Mar 2026 | Programme panel |
| 74% / 22% | SMBs using or testing AI / fully confident AI can do routine tasks alone | Bluevine (n=942) | https://www.bluevine.com/newsroom/bluevine-study-shows-ai-is-saving-nearly-half-of-smbs-4-hours-a-week | Apr 2026 | Lender survey |
| +15% / -8% | Performance effect of GPT-4 mentor on high / low baseline performers; average effect not distinguishable from zero | Otis et al., Management Science (RCT, n=640 Kenyan entrepreneurs) | https://pubsonline.informs.org/doi/10.1287/mnsc.2024.06909 | 2025 | Peer-reviewed RCT; figures vary by version |

## Track 3. Enterprise (from `04-enterprise.md`)

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
| ~17% to 21.3% (vs 91.2% Spider 1.0) | Best model success on 632 real enterprise text-to-SQL tasks | Spider 2.0, arXiv 2411.07763 | https://arxiv.org/abs/2411.07763 | Nov 2024 / v2 Mar 2025 | Peer-reviewed benchmark; leaderboard later ~41%; search extract |
| ~30% | Accuracy drop of commercial assistants and long-context LLMs on long-term memory | LongMemEval, arXiv 2410.10813 (ICLR 2025) | https://arxiv.org/abs/2410.10813 | 2024-25 | Relative to oracle retrieval; search extract |
| 7.2% / 5.5% | Open-source MCP servers with general vulnerabilities / tool poisoning (n=1,899) | Hasan et al., arXiv 2506.13538 | https://arxiv.org/pdf/2506.13538v2 | 2025 | Academic scan; search extract |
| 9.3 | CVSS score of EchoLeak (CVE-2025-32711), zero-click M365 Copilot prompt injection | Microsoft / Aim Security | https://thehackernews.com/2025/06/zero-click-ai-vulnerability-exposes.html | Jun 2025 | Vendor CVE; fixed, no known exploitation; search extract |
| ~1,000 | Asana customers potentially exposed by MCP server bug | Asana spokesperson to BleepingComputer | https://bleepingcomputer.com/news/security/asana-warns-mcp-ai-feature-exposed-customer-data-to-other-orgs/ | Jun 2025 | Company statement via press; Asana declined to confirm to other outlets |
| >10,000 / ~97M | Active public MCP servers (Dec 2025) / monthly SDK downloads (Mar 2026) | Anthropic, via secondary blogs | https://nordicapis.com/10-interesting-mcp-statistics/ | 2025-26 | Primary not seen; downloads are not production use |
| ~200,000 | JPMorgan employees onboarded to LLM Suite | Bloomberg via American Banker | https://www.americanbanker.com/news/how-jpmorganchase-democratized-employee-access-to-gen-ai | 2025 | Company figure via press; ~half active daily |
| 3B+ / ~50M | Erica cumulative client interactions / users since 2018 | Bank of America press release | https://newsroom.bankofamerica.com/content/newsroom/press-releases/2025/08/a-decade-of-ai-innovation--bofa-s-virtual-assistant-erica-surpas.html | 20 Aug 2025 | Company-reported, cumulative |
| ~46,000 | Goldman staff given GS AI Assistant (after 10,000 pilot) | Goldman via press | https://www.americanbanker.com/news/goldman-sachs-staff-now-write-a-million-gen-ai-prompts-a-month | 24 Jun 2025 | Company figure via press |
| +70% / +40% | Walmart Sparky users YoY / spend per order of Sparky users | Walmart Q2 FY27 call via CIO Dive | https://www.ciodive.com/news/walmart-AI-wins-sparky-john-furner/812606/ | Aug 2026 | Company-reported; correlation, not causal; Feb 2026 figure was 35% |
| 82.9% | Organisations with AI projects delayed by security/compliance review | Protegrity / EMA | https://securitybrief.co.uk/story/enterprise-ai-deployments-slowed-by-security-reviews | Jul 2026 | Vendor-sponsored; n not seen |
| ~30% | Of delayed projects, share stalled 4+ months | Protegrity / EMA | same | Jul 2026 | As above |
| ~25% (~3 hrs/week) | Reduction in email time from Copilot; no change in meeting time | Dillon et al., NBER WP 33795, RCT, 66 firms, 7,137 workers | https://www.nber.org/system/files/working_papers/w33795/w33795.pdf | 2025 | Randomised; Microsoft-affiliated authors; search extract |
| 21% to 75% | Weekly Copilot use among treated workers, range across firms | Dillon et al. | same | 2025 | Randomised access, so variation is organisational |
| 14-15% (34% novices) | Resolutions per hour from AI assistant, customer support | Brynjolfsson, Li, Raymond, QJE 2025 (n=5,172) | https://www.nber.org/system/files/working_papers/w31161/w31161.pdf | 2025 | Peer-reviewed quasi-experiment |
| 26 min/day | Self-reported time saved, UK cross-government Copilot experiment (20,000 staff) | GDS findings report | https://www.gov.uk/government/publications/microsoft-365-copilot-experiment-cross-government-findings-report/microsoft-365-copilot-experiment-cross-government-findings-report-html | Jun 2025 | Self-report, not randomised |
| No evidence of productivity gain | DBT Copilot pilot (~1,000 licences) | UK DBT via The Register | https://www.theregister.com/2025/09/04/m365_copilot_uk_government | Sep 2025 | Government evaluation; primary not seen |
| 7,600+ / 1 in 3 daily | Australian public servants in Copilot trial / share using daily | DTA, Nous Group evaluation | https://www.digital.gov.au/initiatives/copilot-trial/summary-evaluation-findings/cts-executive-summary | Oct 2024 | Non-random sample |
| 122%-408% | Projected ROI range, Teams with M365 Copilot | Forrester TEI commissioned by Microsoft | https://tei.forrester.com/go/Microsoft/TeamsandCopilot/ | 2025 | OPINION: vendor-commissioned projection on a composite org |

## Track 4. Inertia and education (from `05-inertia-and-education.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| 0 valid studies | Empirical support for "70% of change initiatives fail" found by Hughes across 5 cited sources | Hughes, J. Change Mgmt 11(4) | https://research.brighton.ac.uk/en/publications/do-70-per-cent-of-all-organizational-change-initiatives-really-fa/ | 2011 | Peer-reviewed; contested by Burnes & Jackson 2011. [search-summary] |
| 78% | AI users bringing their own AI tools to work (80% at SMBs) | Microsoft/LinkedIn WTI 2024, n=31,000 | https://www.microsoft.com/en-us/worklab/work-trend-index/ai-at-work-is-here-now-comes-the-hard-part | 8 May 2024 | Vendor survey, online knowledge workers. Verified curl+grep. |
| 52% | AI users reluctant to admit using it for their most important tasks | WTI 2024 | same | 8 May 2024 | Vendor survey. Verified. |
| 53% | AI users worried that using it on important tasks makes them look replaceable | WTI 2024 | same | 8 May 2024 | Vendor survey. Verified. |
| 39% | AI users who have received AI training from their company | WTI 2024 | same | 8 May 2024 | Vendor survey. Verified. |
| 67% vs 40% | Leaders vs employees familiar with AI agents | WTI 2025, n=31,000 | https://www.microsoft.com/en-us/worklab/work-trend-index/2025-the-year-the-frontier-firm-is-born | 23 Apr 2025 | Vendor survey. Verified. |
| 43% | Workers globally who fear AI will take their jobs | WTI 2025 | same | 23 Apr 2025 | Vendor survey. Verified. |
| 77% | AI-using employees saying AI added to their workload | Upwork Research Institute | https://investors.upwork.com/news-releases/news-release-details/upwork-study-finds-employee-workloads-rising-despite-increased-c | 23 Jul 2024 | Vendor; base is about 1,250 non-executives in 4 countries. [search-summary] |
| 52% / 36% | US workers worried / hopeful about AI at work | Pew, n=5,273, Oct 2024 | https://www.pewresearch.org/internet/2025/02/25/u-s-workers-are-more-worried-than-hopeful-about-future-ai-use-in-the-workplace/ | 25 Feb 2025 | Probability panel; strong. [search-summary] |
| 50% / 28% | US employees using AI at work at all / frequently | Gallup, n=23,717, Feb 2026 | https://www.tomshardware.com/tech-industry/artificial-intelligence/half-of-all-us-employees-now-use-artificial-intelligence-at-work-crossing-landmark-threshold-for-first-time-gallup-data-shows-daily-and-weekly-usage-hitting-all-time-high-of-28-percent-in-q1-2026-with-65-percent-feeling-positive-about-its-impact-on-productivity | Q1 2026 | Strong panel; secondary report. [search-summary] |
| 54.6% | US adults 18–64 who have used generative AI | Bick, Blandin & Deming, St Louis Fed | https://www.stlouisfed.org/on-the-economy/2025/nov/state-generative-ai-adoption-2025 | 13 Nov 2025 | Nationally representative. [search-summary] |
| 4.1% to 5.7% | Share of all US work hours spent using generative AI, Nov 2024 to Aug 2025 | same | same | 13 Nov 2025 | [search-summary] |
| about 3% | Average time saved by chatbot users in Denmark; earnings and hours effects about 0 | Humlum & Vestergaard, NBER w33777 | https://econpapers.repec.org/RePEc:nbr:nberwo:33777 | 2025 | Survey linked to registers; strong. [search-summary] |
| about 20% | How much less likely women are than men to use generative AI | Otis, Cranney, Delecourt & Koning | https://www.hks.harvard.edu/centers/cid/publications/global-evidence-gender-gaps-and-generative-ai | Oct 2024 (rev.) | Meta-analysis of 16–18 studies, more than 140,000 people. [search-summary] |
| 51% | Frontline (white-collar) employees who are regular AI users; stalled | BCG AI at Work 2025 | https://www.bcg.com/press/26june2025-beyond-ai-adoption-full-potential | 26 Jun 2025 | Consultancy survey. [search-summary] |
| 15% to 55% | Positive sentiment toward generative AI, without vs with strong leadership support | BCG AI at Work 2025 | same | 26 Jun 2025 | Cross-sectional. [search-summary] |
| 27% to 22% | Global manager engagement, 2024 to 2025 | Gallup State of the Global Workplace 2026 | https://www.unleash.ai/strategy-and-leadership/analysis/gallups-state-of-the-global-workplace-2026-report-three-key-decisions-for-hr-leaders | Apr 2026 | Secondary. [search-summary] |
| 21% | Generative AI users who have fundamentally redesigned at least some workflows | McKinsey State of AI | https://artificialintellitools.blogspot.com/2025/04/briefing-document-state-of-ai-how.html | Mar 2025 | Consultancy; secondary blog. [search-summary] |
| 15.9% | US TFP level above official figures by end-2017 after adjusting for IT intangibles | Brynjolfsson, Rock & Syverson, AEJ Macro | https://www.aeaweb.org/doi/10.1257/mac.20180386 | 2021 | Peer-reviewed. [search-summary] |
| 69% | Professionals interviewed who mentioned social stigma of AI use at work | Anthropic Interviewer, n=1,250 | https://www.anthropic.com/research/anthropic-interviewer | 4 Dec 2025 | Vendor; crowdworker-recruited sample. Verified. |
| 57% | Employees who hide AI use and present AI output as their own | KPMG / Univ. of Melbourne 2025, n≈48,000, 47 countries | https://mbs.edu/news/global-study-reveals-trust-of-ai-remains-a-critical-challenge | Apr 2025 (fieldwork Nov 2024 to Jan 2025) | Academic-led, Big Four sponsor. Search extract |
| ~50% | Employees using AI in ways that contravene company policy | same | same | 2025 | "Almost half". Search extract |
| 47% / 40% | Employees with AI training / with a workplace genAI policy | same | same | 2025 | Search extract |
| 80% vs 44% | Frequent AI use where managers actively support vs low support (private sector, AI-adopting orgs) | Gallup | https://www.gallup.com/workplace/699689/ai-use-at-work-rises.aspx | late 2025 | Cross-sectional. Search extract |
| 1.7x / 36% | Frequent-use multiplier with strong manager support / share with strong support | Gallup AI indicator | https://www.gallup.com/699797/indicator-artificial-intelligence.aspx | May 2026 | Search extract |
| 21% to 75% | Weekly Copilot use among treated workers, range across 66 firms | Dillon et al., NBER w33795, n=7,137 | https://www.nber.org/system/files/working_papers/w33795/w33795.pdf | 2025 | Randomised access; firm effects. Microsoft co-authors |
| 68% | Gap RCT participants at maximum quality score (all arms), so no ITT difference was detectable | arXiv 2604.08678, n=388 | https://arxiv.org/abs/2604.08678 | Apr 2026 | Preprint, Microsoft authors, no IRB |
| 10.9 to 12.1 | Average direct reports per manager, 2024 to 2025 | Gallup via Fast Company | https://www.fastcompany.com/91601567/the-great-flattening-rolls-on-as-uber-lays-off-middle-managers | 2025-26 | Secondary |
| -42% | Middle-manager job postings, Apr 2022 peak to Oct 2025 | Revelio Labs via secondary | https://pipedot.org/6SNX5 | late 2025 | Postings, not employment. Secondary |
| 40% | US employees feeling lack of direction due to fewer middle managers | Korn Ferry 2025 | https://www.cfodive.com/news/cuts-middle-management-stressing-72-percent-senior-executives-korn-ferry-HR-WFH/745822/ | 2025 | Consultancy survey |
| 7 / 0.27 | Claude usage per working-age capita relative to expected (Israel / India) | Anthropic Economic Index | https://www.anthropic.com/research/anthropic-economic-index-september-2025-report | 15 Sep 2025 | One vendor's consumer users. Verified. |

## Track 5. What goes wrong (from `06-what-goes-wrong.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| 65 | Data scientists/engineers interviewed for RAND root-cause study | RAND RR-A2680-1 | https://www.rand.org/pubs/research_reports/RRA2680-1.html | 2024-08-13 | Qualitative interviews; seen via search summary |
| >80% | "Some estimates" of AI project failure, cited by RAND | RAND RR-A2680-1 | https://www.rand.org/pubs/research_reports/RRA2680-1.html | 2024-08-13 | Secondhand within RAND; not a RAND measurement |
| 30 to 50% | "As many as" this share of *initial* RPA projects fail | EY, Get ready for robots | https://www.eyfinancialservicesthoughtgallery.ie/wp-content/uploads/2016/11/ey-get-ready-for-robots.pdf | 2016 | Consultancy opinion, no method; origin of viral stat |
| ~1,598 | Court decisions noting AI-hallucinated content (cumulative, worldwide) | Charlotin database via HAQQ write-up | https://haqq.ai/blog/ai-legal-hallucination-audit.html | 2026-06-09 | Third-party count; check live database |
| ~8/day | New hallucination cases added (implied rate) | HAQQ write-up | https://haqq.ai/blog/ai-legal-hallucination-audit.html | 2026-06 | Third-party estimate |
| A$440,000 | Deloitte DEWR report contract value (final instalment refunded) | The Register | https://www.theregister.com/2025/10/06/deloitte_ai_report_australia/ | 2025-10-06 | Seen via search summary; refund amount unconfirmed |
| 45 | CBA roles cut then reinstated after FSU challenge | Bloomberg | https://www.bloomberg.com/news/articles/2025-08-21/commonwealth-bank-reverses-job-cuts-decision-over-ai-chatbots | 2025-08-21 | Seen via search summary |
| ~2,000/week | Call reduction CBA claimed for voice bot (disputed by FSU) | ACS Information Age | https://ia.acs.org.au/article/2025/cba-reverses-ai-driven-job-cuts--admits--error-.html | 2025-08 | Company claim, disputed |
| ~100 | McDonald's restaurants in IBM voice-ordering test, ended by 26 Jul 2024 | Nation's Restaurant News | https://www.nrn.com/quick-service/mcdonald-s-is-ending-its-ai-drive-thru-test-with-ibm | 2024-06 | Seen via search summary |
| 500+ / 2m+ | Taco Bell drive-thrus with voice AI / orders handled | Jalopnik (citing WSJ) | https://www.jalopnik.com/1956939/taco-bell-drive-through-18000-waters/ | 2025-08 | Secondary of WSJ |
| ~$304m | Zillow Offers inventory write-down, Q3 2021 | Inman | https://www.inman.com/2021/11/02/zillow-to-shut-down-ibuying-program-zillow-offers/ | 2021-11-02 | Some reports say $340m |
| ~25% | Zillow workforce cut with Offers wind-down | CNN | https://edition.cnn.com/2021/11/09/tech/zillow-ibuying-home-zestimate | 2021-11-09 | Seen via search summary |
| $62.1m | MD Anderson spend on Watson Oncology Expert Advisor (IBM ~$39.2m, PwC ~$23m) | The Register on UT System audit | https://www.theregister.com/2017/02/20/watson_cancerbusting_trial_on_hold_after_damning_audit_report/ | 2017-02-20 | Audit figure; PwC split varies by outlet |
| ~1.1 billion | Applications Workday said were rejected using its tools in the class period | Holland & Knight | https://www.hklaw.com/en/insights/publications/2025/05/federal-court-allows-collective-action-lawsuit-over-alleged | 2025-05-27 | Scale figure from filings, not a discrimination finding |
| 9.3 | CVSS score of EchoLeak (CVE-2025-32711) | The Hacker News | https://thehackernews.com/2025/06/zero-click-ai-vulnerability-exposes.html | 2025-06 | Microsoft rating |
| 0.692 → 0.462 | τ-bench retail pass^1 → pass^4, best listed model (claude-3-5-sonnet-20241022) | tau-bench repo | https://raw.githubusercontent.com/sierra-research/tau-bench/main/README.md | 2024 to 2025 | Fetched; primary |
| 0.604 → 0.383 | τ-bench retail pass^1 → pass^4, gpt-4o | tau-bench repo | https://raw.githubusercontent.com/sierra-research/tau-bench/main/README.md | 2024 | Fetched; primary |
| 75+ | Task fixes Sierra made to its own benchmark tasks in τ³-bench | tau2-bench repo | https://raw.githubusercontent.com/sierra-research/tau2-bench/main/README.md | 2026 | Fetched; primary |
| 30.3% | Best full-task completion on TheAgentCompany (Gemini 2.5 Pro), v2 | alphaXiv listing of arXiv 2412.14161v2 | https://www.alphaxiv.org/abs/2412.14161v2 | 2025-05 | Seen via search summary |
| ~7 months | METR 50% time-horizon doubling time (2019 to 2025) | METR repo README | https://raw.githubusercontent.com/METR/eval-analysis-public/main/README.md | 2025 | Fetched; primary |
| 4x to 10x | Ratio of 50% to 80% time horizon across 20 models | My refit of METR TH1.1 runs | https://raw.githubusercontent.com/METR/eval-analysis-public/main/reports/time-horizon-1-1/data/raw/runs.jsonl | computed 2026-11-06 | Own approximate analysis; not METR's published figures |
| $5,000 | Rule 11 sanction in Mata v. Avianca (total vs per lawyer disputed in reports) | S.D.N.Y. Opinion and Order on Sanctions | https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1:2022cv01461/575368/54 | 2023-06-22 | Primary court document; search extract, not fetched |
| ~50-60% | Average conformance between designed and actual purchase-order process | Mavim vendor case study | https://www.mavim.com/hubfs/Assets/Miscellaneous/Case%20study%20-%20Conformance%20checking%20-%20EN.pdf?hsLang=en | n.d. | Vendor case; search extract |
| 600+ | Variants of one process in one business group | Mavim, same | same | n.d. | Vendor case; depends on log granularity |
| 18% / ~38 FTE | P2P transactions with manual changes / staff tied up in top-5 rework activities | Celonis / AkzoNobel case (IEEE TF PM site) | https://www.win.tue.nl/ieeetfpm/casestudies/celonis_akzonobel_-_customer_success_story.pdf | n.d. (c. 2010s) | Vendor case; search extract |
| 75+ / 50+ | Contributors / organisations behind the Process Mining Manifesto | IEEE Task Force on Process Mining | https://research.wu.ac.at/en/publications/process-mining-manifesto-3/ | 2011 | Bibliographic; search extract |
| 84% → 51% | GPT-4 prime-identification accuracy, March vs June 2023 | Chen, Zaharia, Zou | https://arxiv.org/abs/2307.09009 | 2023-07 | Seen via search summary; interpretation contested |

## Track 6. Working with agents (from `07-working-with-agents.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| 86% | Share of analytical choices where analysts followed a coin-flipped agent lean (50% = no effect) | Anthropic, Herdağdelen, Joren, Tamkin | https://www.anthropic.com/research/agents-judgment-calls | 2026-10-27 | RCT, n=50 analysts, vendor-run, lab task |
| 60% vs 6% | Switch rate away from own stated preference when agent disagreed vs agreed | Same | https://www.anthropic.com/research/agents-judgment-calls | 2026-10-27 | Only 38 cases; CI on gap 24 to 82 pp |
| 77% / 15% | Analysts reusing agent arguments / crediting the agent | Same | https://www.anthropic.com/research/agents-judgment-calls | 2026-10-27 | Self-reported explanations |
| 93% | Share of manual permission prompts users accept in Claude Code | Anthropic engineering | https://www.anthropic.com/research/claude-code-auto-mode | 2026-03-25 | Vendor product data, method not detailed |
| 17% | False-negative rate of auto-mode classifier on real overeager actions | Same | https://www.anthropic.com/research/claude-code-auto-mode | 2026-03-25 | n=52 real cases, small |
| ~20% to >40% | Sessions with full auto-approve, new (<50 sessions) vs experienced (750) Claude Code users | Anthropic | https://www.anthropic.com/research/measuring-agent-autonomy | 2026-02-18 | Vendor telemetry; default is manual approval |
| 5% to ~9% | Per-turn interrupt rate, new vs experienced users | Same | https://www.anthropic.com/research/measuring-agent-autonomy | 2026-02-18 | Vendor telemetry |
| 73% / 80% / 0.8% | API tool calls with a human in the loop / with at least one safeguard / irreversible | Same | https://www.anthropic.com/research/measuring-agent-autonomy | 2026-02-18 | Inferred by Claude from single tool calls; cannot see downstream review |
| ~50% | Software engineering share of agentic tool calls on Anthropic public API | Same | https://www.anthropic.com/research/measuring-agent-autonomy | 2026-02-18 | n=998,481 tool calls |
| 70% / 20% | User share of planning / execution decisions in Claude Code sessions | Anthropic | https://www.anthropic.com/research/claude-code-expertise | 2026-06-16 | ~400k sessions, classifier-based |
| 88% vs 89% | At least partial success, non-software vs software occupations, code-producing sessions | Same | https://www.anthropic.com/research/claude-code-expertise | 2026-06-16 | Success partly user-confirmed |
| 77% vs 12% | Automation vs augmentation share of 1P API transcripts | Anthropic Economic Index | https://www.anthropic.com/research/anthropic-economic-index-september-2025-report | 2025-09-15 | Share of transcripts, not of businesses; later reports show decline |
| 27% to 39% | Directive (full delegation) share of Claude.ai conversations, late 2024 to Aug 2025 | Same | https://www.anthropic.com/research/anthropic-economic-index-september-2025-report | 2025-09-15 | Reversed by Nov 2025 data |
| 52% / 45% | Augmented / automated share of Claude.ai conversations, Nov 2025 | Anthropic Economic Index | https://www.anthropic.com/research/anthropic-economic-index-january-2026-report | 2026-01-15 | Vendor telemetry |
| 0.24 SD | Team advantage over individuals without AI; closed by individual with AI | Dell'Acqua et al., NBER 33641 | https://www.nber.org/papers/w33641 | 2025-03 | n=776, one-day task; snippet only this session |
| 12-16% | Time saved by AI groups, P&G experiment | Same | https://www.nber.org/papers/w33641 | 2025-03 | Snippet only |
| 14% (WP) / 15% (QJE) | Productivity gain, customer support agents | Brynjolfsson, Li, Raymond | https://econpapers.repec.org/RePEc:nbr:nberwo:31161 | 2023 / 2025 | One firm, ~5,170 agents; snippet only |
| 3 hours, 25% | Weekly email time reduction for Copilot users (ITT 1.4 h); no change in meetings | Dillon et al., Microsoft | https://www.microsoft.com/en-us/research/publication/shifting-work-patterns-with-generative-ai/ | 2025-04 | RCT, 6,000 workers, 56 firms; Microsoft authors |
| 46.1% | Tasks where workers were positive about agent automation | Shao et al., Stanford WORKBank | https://arxiv.org/abs/2506.06576 | 2025-06 | Survey, 1,500 workers; snippet only |
| >20% | Inference cost increase from repository context files, with lower or no better success | Gloaguen et al. | https://arxiv.org/abs/2602.11988 | 2026-02-12 | Snippet only; check full paper for effect sizes |
| -28.64% | Median agent runtime with AGENTS.md (124 PRs, 10 repos) | Lulla et al. | https://arxiv.org/abs/2601.20404 | 2026-01-28 | Small, efficiency only; snippet only |
| 60,000+ | Projects reported to use AGENTS.md | AAIF launch coverage | https://sdtimes.com/ai/linux-foundation-forms-agentic-ai-foundation-to-be-new-home-for-mcp-goose-and-agents-md/ | 2025-12-09 | Self-reported by backers; another outlet said 40,000 |
| 1M / ~280M | Agent Skills published / installed | Anthropic | https://www.anthropic.com/news/donating-agent-skills-to-the-agentic-ai-foundation | 2026-10-22 | Vendor claim, no method |
| 10,000+ / 97M+ | Active public MCP servers / monthly SDK downloads | Anthropic | https://www.anthropic.com/news/donating-the-model-context-protocol-and-establishing-of-the-agentic-ai-foundation | 2025-12-09 | Vendor claim; downloads include CI |
| ~9,000 to ~5,000 | Salesforce support headcount per CEO | Benioff on Logan Bartlett Show via Fortune | https://dc.fortune.com/2025/09/02/salesforce-ceo-billionaire-marc-benioff-ai-agents-jobs-layoffs-customer-service-sales | 2025-09-02 | Spoken claim, no timeframe; snippet only |
| "hundreds" | IBM HR roles replaced by AI agents | Krishna to WSJ via Entrepreneur | https://www.entrepreneur.com/business-news/ibm-ceo-ai-replaced-hundreds-of-human-resources-staff/491341 | 2025-05 | CEO statement; snippet only |
| 33% / 78% | Leaders considering headcount cuts / AI-specific hires | Microsoft WTI 2025 | https://www.microsoft.com/en-us/worklab/work-trend-index/2025-the-year-the-frontier-firm-is-born | 2025-04-23 | Vendor survey, n=31,000, intentions only |
| CAD ~812 | Total award in Moffatt v Air Canada | 2024 BCCRT 149 via McCarthy Tétrault | https://www.mccarthy.ca/en/insights/blogs/techlex/moffatt-v-air-canada-misrepresentation-ai-chatbot | 2024-02 | Snippet only; not binding precedent |
| >=6 months | Minimum log retention for deployers of high-risk AI (AI Act Art. 26) | Regulation (EU) 2024/1689 via Mishcon de Reya | https://mishcon.com/eu-uk-ai-navigator/article-26 | 2024 (applies Dec 2027 for Annex III after omnibus) | Search extract; check EUR-Lex |
| 9 Dec 2026 | Transposition deadline, Product Liability Directive 2024/2853 (software and AI as products) | Norton Rose Fulbright | https://connections.nortonrosefulbright.com/post/102jpjp/revised-product-liability-directive-introducing-rules-on-strict-liability-for-ai | OJ 18 Nov 2024 | Search extract |
| 6 Oct 2025 | Reported OJ date of formal AI Liability Directive withdrawal (announced Feb 2025) | EAPIL | https://eapil.org/2025/10/09/european-commission-withdraws-two-proposals-assignments-of-claims-regulation-and-ai-liability-directive/ | 9 Oct 2025 | Single source for the exact date |
| $25m | Per-insured limit, Armilla Lloyd's-backed AI liability cover (launched 30 Apr 2025) | Armilla | https://www.armilla.ai/resources/armilla-ai-raises-lloyds-backed-coverage-to-25m-as-traditional-insurers-retreat-from-ai-risk | 2025-2026 | Vendor announcement; no claims data |
| 50 (11 in 2025) | ISO/IEC 42001 certificates issued by BSI | BSI | https://www.bsigroup.com/en-GB/insights-and-media/media-centre/press-releases/2026/november/bsi-awards-its-50th-iso-iec-42001-certificate/ | Nov 2026 | One certifier only; no global registry |
| ~1.19M / ~1.03M | GitHub code-search hits for files named AGENTS.md / CLAUDE.md | GitHub search API, queried by this agent | https://api.github.com/search/code?q=filename:AGENTS.md | 2026-11-06 | DO NOT CITE: GitHub's total_count is approximate and includes forks and vendored copies; same query gave ~7M for SKILL.md, which looks implausible |

## Track 7. Displacement (from `08-displacement.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| No significant rise; detectable effect about 1pp | Differential unemployment, top-quartile exposed vs zero-exposure US workers, post-ChatGPT | Massenkoff and McCrory, Anthropic | https://www.anthropic.com/research/labor-market-impacts | 2026-03-05 | Fetched. CPS DiD. Author is an AI vendor |
| -14% | Job-finding rate for 22-25 year olds into most exposed occupations vs 2022 | Same | https://www.anthropic.com/research/labor-market-impacts | 2026-03-05 | Fetched. "Just barely statistically significant" |
| 75% / 67% | Claude task coverage: computer programmers / customer service reps and data entry keyers | Same | https://www.anthropic.com/research/labor-market-impacts | 2026-03-05 | Fetched. Exposure, not effect |
| about 13% (Aug 2025) | Relative employment decline, 22-25 in most exposed occupations | Brynjolfsson, Chandar, Chen, as cited by Hosseini and Lichtinger | https://raw.githubusercontent.com/s-mahdihosseini/Website/b99fa2962dcc4c165bbc3c41dd283afa99c5ccfb/GenAI_SenBTC_May_2026.pdf | 2025-08 | Fetched secondary citation; ADP data; descriptive |
| 19% (by June 2026) | Same gap, Aug 2026 revision | Stanford Digital Economy Lab | https://digitaleconomy.stanford.edu/news/canariesaug26/ ; https://digitaleconomy.stanford.edu/app/uploads/2026/08/Canaries_August2026.pdf | 2026-08-12 | Search extract; now corroborated by a second result (PDF + aiweekly). Revision gives 15% for the July 2025 vintage. 4.6m workers |
| about 0.1pp | Max contribution of young exposed workers' employment decline to US unemployment rise since Nov 2022 | Dallas Fed, Atkinson and Yamco | https://www.dallasfed.org/research/economics/2026/0106 | 2026-01-06 | Search extract. Upper-bound scale check |
| about 1% / 35% | NY-region service firms reporting AI layoffs / AI-using service firms retraining | NY Fed regional surveys | https://libertystreeteconomics.newyorkfed.org/2025/09/are-businesses-scaling-back-hiring-due-to-ai/ | 2025-09-04 | Search extract. Regional firm self-report |
| 0.47-0.57 | Correlation of occupational AI exposure/adoption with unemployment increase 2022-25 | St. Louis Fed, Ozkan and Sullivan | https://fedinprint.org/item/l00001/101478 | 2025-08-26 | Search extract. Non-causal; summaries disagree on figure |
| 5.7% (Q1 2026) | US recent-graduate (22-27) unemployment | NY Fed college labor market | https://www.newyorkfed.org/research/college-labor-market | 2026 | Search extract; Q2 reported as 5.6% |
| about 7% of hires | New-grad share of hires at largest tech firms, down >50% vs 2019, about 25% vs 2023 | SignalFire State of Tech Talent 2025 | https://www.signalfire.com/blog/signalfire-state-of-talent-report-2025 | 2025-05 | Search extract. VC firm's own data |
| -15 to -16% | US entry-level postings on Handshake, Aug 2024 to Aug 2025; applications per post +26-30% | Handshake via Fortune | https://fortune.com/2025/11/19/next-level-leadership-gen-z-college-graduates-tough-market-how-to-stand-out-according-to-jobs-experts/ | 2025-11 | Search extract; secondary |
| 40% / 60% | Share of jobs exposed to AI, world / advanced economies | IMF SDN/2024/001 (Cazzaniga et al.) | https://wiki.ubc.ca/images/b/bd/IMF_GenAI_Future_of_Work.pdf | 2024-01-14 | FORECAST (exposure, not job loss). Search extract |
| 6-7% (range 3-14%) | Share of US workers eventually displaced by GenAI over adoption period; peak unemployment +0.5pp | Goldman Sachs (Hatzius; Briggs and Dong) | https://www.staffingindustry.com/news/global-daily-news/ais-impact-on-jobs-likely-temporary-goldman-sachs | 2025 | FORECAST. Secondary; Goldman primary not seen |
| -15% / -10% / -6% | UK online adverts over about 3 years, high / mid / low AI-exposure occupations | Bank of England staff (Bank Underground, Schlicht) | https://bankunderground.co.uk/2026/08/06/canaries-in-the-column-ai-exposure-and-the-uks-hiring-slowdown/ | 2026-08-06 | Search extract. Staff blog; postings; not causal; pre-ChatGPT trend disputed |
| -7% y/y | UK graduate postings, lowest for time of year since 2020 | Indeed Hiring Lab UK | https://www.hiringlab.org/uk/?p=14268 | 2026-08 | Search extract; postings |
| -31.9% | UK entry-level adverts since Nov 2022 | Adzuna | https://hrreview.co.uk/hr-news/recruitment/entry-level-jobs-have-declined-since-chatgpt-launch | 2025-06 | Search extract; vendor postings; no control group |
| -8% (2024/25), +4% (2025/26) | Graduate hiring by ISE member employers | Institute of Student Employers | https://ise.org.uk/_userfiles/pages/files/reports/student_recruitment_survey_2025.pdf | 2025 / 2026 | Search extract. 155 large employers, about 31k hires |
| 6% | UK AI-using firms (10+ staff) saying AI reduced headcount | ONS BICS via secondary site | https://www.ons.gov.uk/releases/aiinukbusinesses | 2026-09 | UNVERIFIED secondary figure; not seen in ONS bulletin |
| about 15% | Euro-area AI-using firms citing lower labour costs as a motive; AI-intensive firms more likely to hire | ECB blog, Lebastard and Sondermann (SAFE, about 5,000 firms) | https://www.ecb.europa.eu/press/blog/date/2026/html/ecb.blog20260304~d9e34fc95f.en.html | 2026-03-04 | Search extract. Firm self-report |
| +1.3pp | Expected 12-month employment growth, significant AI users vs non-users, euro area | ECB Economic Bulletin 2/2026 box | https://ecb.europa.eu/press/economic-bulletin/focus/2026/html/ecb.ebbox202602_06~c9f485c478.en.html | 2026 | Search extract. Expectations |
| about -9% after 6 quarters | Junior employment at GenAI-adopting firms vs non-adopters | Hosseini and Lichtinger | https://raw.githubusercontent.com/s-mahdihosseini/Website/b99fa2962dcc4c165bbc3c41dd283afa99c5ccfb/GenAI_SenBTC_May_2026.pdf | 2026-05-06 | Fetched. 66m workers, 281k firms; adoption proxied by postings |
| about 80% | Fall in junior hires per quarter at adopters vs pre-period mean (4.0 of 5.06) | Same | same | 2026-05-06 | Fetched |
| 3.7% / 16% | Share of firms classed as GenAI adopters / their share of employment | Same | same | 2026-05-06 | Fetched. Adoption by Mar 2025 |
| -5.5% | 22-25 employment in high-exposure occupations within Swedish employers | Lodefalk et al. 2026, cited by Hosseini and Lichtinger | same | 2026 | Fetched secondary citation; original not seen |
| >35% | Fall in US entry-level postings since Jan 2023 | Revelio Labs (Simon 2025), cited by Hosseini and Lichtinger | https://www.reveliolabs.com/news/macro/is-ai-responsible-for-the-rise-in-entry-level-unemployment/ | 2025 | Vendor data; secondary citation |
| -21% | Freelance writing and coding posts vs manual posts, 8 months after ChatGPT | Demirci, Hannane, Zhu, Management Science | https://spiral.imperial.ac.uk/entities/publication/88113a91-b994-4717-8526-dadac657f1cb | 2025 | Search summary; 1.39m posts |
| -5.2% | Monthly earnings of Upwork writing freelancers after ChatGPT | Hui, Reshef, Zhou | https://www.cesifo.org/DocDL/cesifo1_wp10601.pdf | 2023 WP | Search summary |
| <1% | Upper bound on earnings/hours effects, Danish exposed occupations | Humlum and Vestergaard, NBER 33777 | https://bfi.uchicago.edu/wp-content/uploads/2025/04/BFI_WP_2025-56-3.pdf | 2025 | Search summary; 25k workers, 7k workplaces |
| <2% | Same bound, two years after ChatGPT, 2026 version ("Still Waters, Rapid Currents") | Humlum and Vestergaard, RFBerlin DP 26078 | https://ideas.repec.org/p/crm/wpaper/26078.html | 2026-03 | Search extract (abstract) |
| 121,401 (about 20%) [DO NOT CITE: unconfirmed, see verification.md] | US announced job cuts citing AI, Jan-Oct 2026 | Challenger, Gray & Christmas | https://www.challengergray.com/blog/october-layoffs-at-three-year-low-seasonal-hiring-plans-up-26/ | 2026-11-05 | Search summary; announcements, company-stated reasons |
| 54,836 | US announced job cuts citing AI, full year 2025 | Challenger (via secondary) | https://aiunderstanding.org/news/challenger-says-employers-cited-ai-in-112-713-u-s-job-cuts-through-july-2026 | 2026-08 | Search summary; secondary |
| about 1.1%/month, 13.4% annualised | US layoffs and discharges rate, 12 months to Apr 2026 (BLS JOLTS) | Anthropic citing BLS | https://www.anthropic.com/research/economic-index-june-2026-report | 2026-06-26 | Fetched; check against BLS directly |
| net -8% (23% cut, 15% created) | Headcount change reported by UK firms using AI 1+ year, five sectors | Morgan Stanley via eWeek/ITPro | https://www.eweek.com/news/ai-job-losses-uk-morgan-stanley-report/ | 2026-01 | Search summary; non-representative firm survey; NOT 8% of UK jobs |
| 5.6% | Unemployment, US recent college grads 22-27, Q1 2026 | NY Fed via Bloomberg Law | https://news.bloomberglaw.com/new-york-brief/unemployment-for-recent-college-grads-remains-high-ny-fed-says | 2026 | Search summary |
| 12.2% | 2030 unemployment forecast by US workers expecting AI to do 80%+ of their work | Anthropic / Morning Consult, n=10,980 | https://www.anthropic.com/research/ai-expectations-gap | 2026-10-16 | Fetched. Expectation, not outcome |
| 10% | Claude users rating own job loss in next year likely/very likely | Anthropic Economic Index Survey, n≈9,700 | https://www.anthropic.com/research/economic-index-june-2026-report | 2026-06-26 | Fetched. Not representative |

## Track 8. What will people do (from `09-what-will-people-do.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| ~60% (some versions 63%) | Share of 2018 US employment in job titles that did not exist in 1940 | Autor, Chin, Salomons, Seegmiller, QJE | https://economics.mit.edu/sites/default/files/2026-04/New-Frontiers-QJE-v139%283%29-p1399-1465-Aug-2024.pdf | Aug 2024 | Peer-reviewed. Search summary only; not checked against PDF |
| 41% to 1.9% | Agriculture share of US workforce, 1900 to 2000 | USDA ERS (compiling HSUS and Census) | https://webharvest.gov/peth04/20041105150816/http://www.ers.usda.gov/publications/agoutlook/jun2000/ao272h.pdf | Jun 2000 | Official, but seen via repost; other series give 2.4% for 2000 |
| >25% fall; vs ~780 hrs | Fall in men's annual market hours 1931-2011, vs Keynes's implied target | Crafts, CEPR DP16140 | https://repec.cepr.org/repec/cpr/ceprdp/DP16140.pdf | 2021 | Working paper; search summary only |
| 47% | Share of US employment at "high risk" of computerisation | Frey and Osborne via ITIF | https://itif.org/publications/2022/09/30/oops-the-predicted-47-percent-of-job-loss-from-ai-didnt-happen/ | 2013 (forecast); 2022 (review) | Forecast; ITIF is an advocacy think tank |
| +16.4% | Employment growth 2013-2021 in insurance underwriters (highest F&O risk) | ITIF | same as above | Sep 2022 | Advocacy source using BLS data |
| -0.2 pp; -0.42% | Employment-to-population and wage effect per extra robot per 1,000 workers | Acemoglu and Restrepo, JPE | https://econpapers.repec.org/RePEc:ucp:jpolec:doi:10.1086/705716 | 2020 | Peer-reviewed; other versions give different magnitudes |
| >50% | Share of US phone network AT&T automated 1920-1940 | Feigenbaum and Gross, QJE | https://econpapers.repec.org/RePEc:oup:qjecon:v:139:y:2024:i:3:p:1879-1939. | Aug 2024 | Peer-reviewed; search summary only |
| ~1.3 hrs/week; ~2 pp | Fall in hours and employment, $1,000/month recipients vs controls | OpenResearch / Vivalt et al., NBER WP 32719 (via Fortune) | https://www.nber.org/system/files/working_papers/w32719/w32719.pdf | Jul 2024 | RCT; figures from secondary coverage; a conference version reports 3.9 pp participation fall; reconcile |
| 28% to 40% (control 32% to 37%) | Full-time employment, Stockton SEED recipients, Feb 2019 to Feb 2020 | Martin-West and Castro Baker | https://catalog.results4america.org/case-studies/guaranteed-income-stockton | Mar 2021 | n=125 treated; small |
| €560/month, ~2,000 people | Finland basic income experiment design | Finnish Ministry of Social Affairs and Health / Kela | https://stm.fi/en/-/perustulokokeilun-tulokset-tyollisyysvaikutukset-vahaisia-toimeentulo-ja-psyykkinen-terveys-koettiin-paremmaksi | May 2020 | RCT; employment effect "small" |
| 0 employment effect; +1.8 pp (17%) part-time | Alaska PFD labour effects | Jones and Marinescu, AEJ: Policy | https://www.aeaweb.org/doi/10.1257/pol.20190299 | 2022 | Peer-reviewed; synthetic control; part-time figure conflicts with one text fragment |
| 61 firms, ~2,900 staff; 56 continue, 18 permanent | UK four-day-week pilot | Autonomy / 4 Day Week Global, via WEF | https://www.weforum.org/stories/2023/03/four-day-work-week-uk-trial/ | Feb 2023 | Self-selected firms; advocacy-run |
| >2,500 workers, ~1% of workforce, 35-36 hrs | Iceland public-sector hours-reduction trials | Autonomy and Alda | https://issuu.com/4dayweekglobal/docs/iceland_4dw | Jun 2021 | Advocacy report; not a four-day week |
| 86% | Icelandic workers on contracts with shortened hours or the right to shorten | Autonomy and Alda | https://issuu.com/4dayweekglobal/docs/iceland_4dw | Jun 2021 | Advocacy report; size of cuts varies |
| 10-15% per year; 1.0-1.5 yrs | Mortality hazard increase 20 years after displacement; implied life-expectancy loss | Sullivan and von Wachter, QJE | https://econpapers.repec.org/RePEc:oup:qjecon:v:124:y:2009:i:3:p:1265-1306. | 2009 | Peer-reviewed; 50-100% first-year figure is from a draft only |
| ~30% vs ~1% | Share of lost work hours going to sleep plus TV vs job search, Great Recession | Aguiar, Hurst, Karabarbounis (NBER Digest) | https://www.nber.org/digest/nov11/time-use-during-recessions | Nov 2011 | ATUS-based; secondary summary |
| N=3,562; ~-11% motivation, ~+20% boredom | GenAI collaboration followed by solo work | Scientific Reports (4 experiments) | https://fortune.com/2025/06/03/ai-boost-worker-productivity-hurts-motivation-boredom | Apr 2025 (paper) | Online experiments; effect sizes from secondary coverage |
| 3-7% | Share of chatbot productivity gains passed through to earnings | Humlum and Vestergaard, NBER WP 33777 | https://econpapers.repec.org/RePEc:nbr:nberwo:33777 | 2025 | Danish register data, 25,000 workers; working paper |
| ~5,671,836 | US business applications, 2025 (annual record) | Census BFS (annual sum via secondary) | https://www.census.gov/econ/bfs/pdf/historic/bfs_2025m12.pdf | Jan 2026 | Official monthly data; annual total from secondary sum |
| 37.6% to 30.1% | High-propensity share of US business applications, 2019 to 2025 | Consultant calculation from Census BFS | https://founderreports.com/how-many-businesses-are-started-each-year/ | 2026 | Secondary calculation |
| 29.8m (2022); 30.4m (2023) | US nonemployer businesses | Census NES / NES-D | https://www.census.gov/library/stories/2025/07/nonemployer-business-growth.html | Jul / Nov 2025 | Official; search extract |
| 4.9%; 4.7% | Nonemployer growth 2021, 2022 (employer: 1.9%, 1.8%) | Census | https://www.census.gov/library/stories/2025/07/nonemployer-business-growth.html | Jul 2025 | Official; pre-AI period |
| ~4.38m vs ~5.0m | UK self-employed, Q4 2025 vs end-2019 | ONS LFS via Statista | https://statista.com/statistics/318234/united-kingdom-self-employed | 2026 | LFS volatile; series disagree |
| ~$401m; ~$65m | Medvi 2025 revenue; net profit | NYT via Dealroom | https://dealroom.co/news/127216-from-20k-to-1-8b-in-revenue-how-one-founder-built-a-telehealth-giant-wit/ | Apr 2026 | Journalist saw financials; contested; $1.8bn is a projection |
| ~$80m + earn-out | Wix purchase of Base44 (6-8 staff, ~6 months old) | Globes | https://en.globes.co.il/en/article-wix-acquires-israeli-vibe-coding-co-base44-1001513267 | Jun 2025 | Press report |
| 6.2%; ~96,000 | England adult social care vacancy rate and vacancies, 2025/26 | Skills for Care via LocalGov | https://www.localgov.co.uk/Social-care-vacancy-rate-falls-to-decade-low-but-challenges-ahead/64563 | Jun 2026 | Sector data body; secondary report |
| £12.60 (39p above NLW) | Median care worker hourly pay, England, Dec 2025 | Skills for Care via Healthcare Management | https://www.healthcare-management.uk/care-workers-pay-minimum-wage-reveals | 2026 | Sector data; NLW rose to £12.71 in Apr 2026 |
| $34,900; +17%; 765,800/yr | US home health and personal care aides: median pay 2024; growth 2024-34; annual openings | BLS OOH | https://www.bls.gov/ooh/healthcare/home-health-aides-and-personal-care-aides.htm | 2025 | Official; search extract |
| 45 firms, ~900 staff; ~73% continue | Germany four-day-week pilot 2024 | University of Münster / Intraprenör via The Local | https://www.thelocal.de/20241106/what-are-the-results-of-germanys-four-day-work-week-trial | Nov 2024 | Self-selected; ~20% reverted |
| 9.5% | Traffic fall during Valencia's four Monday holidays, 2023 | City-commissioned evaluation via The Mayor | https://www.themayor.eu/en/a/view/valencia-s-government-says-4-day-week-trial-was-good-for-the-people-and-the-city-12172 | 2023 | Four weeks; holidays not work redesign |

## Track 9. Social and political (from `10-social-political.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| 52% | US adults more concerned than excited about AI in daily life (37% in 2021) | Pew, n=3,488, Jun 22-28 2026 | https://www.pewresearch.org/short-reads/2026/08/18/young-adults-in-the-us-are-increasingly-wary-of-ai/ | 18 Aug 2026 | Probability panel; seen via search summary only |
| 71% | US adults expecting AI to mean fewer jobs over 20 years (64% in 2024) | Pew | same as above | 18 Aug 2026 | As above |
| 55% | US adults under 30 more concerned than excited | Pew | same as above | 18 Aug 2026 | As above |
| +17 pts | Rise in Democrats expecting fewer jobs from AI | Pew | https://www.pewresearch.org/short-reads/2026/09/16/democrats-are-now-more-worried-than-republicans-about-ai-and-its-impact-on-jobs/ | 16 Sep 2026 | Search summary only; base years not confirmed |
| 34% / 42% / 16% | 25-country median: more concerned / equally / more excited | Pew Global Attitudes, spring 2025 | https://www.pewresearch.org/global/2025/10/15/how-people-around-the-world-view-ai/ | 15 Oct 2025 | Strong method; search summary only |
| 50% vs 16% | More concerned than excited: US (and Italy) vs South Korea | Pew Global Attitudes | same as above | 15 Oct 2025 | As above |
| 39% | US adults saying AI does more harm than good (31% 2025, 40% 2023) | Gallup/Bentley | https://news.gallup.com/poll/712751/americans-cool-toward.aspx | Jul 2026 | Gallup web panel; Decrypt reports a conflicting higher figure |
| 79% | US adults expecting AI to reduce US jobs over 10 years (73% 2025) | Gallup/Bentley | same as above | Jul 2026 | As above |
| 27% | US adults trusting business to use AI responsibly (31% 2025, 21% 2023) | Gallup/Bentley | same as above | Jul 2026 | As above |
| 66% / 46% | Regular AI use / willing to trust AI, 47 countries | KPMG & Univ. of Melbourne, n>48,000 | https://figshare.unimelb.edu.au/articles/report/Trust_attitudes_and_use_of_artificial_intelligence_A_global_study_2025/28822919 | 2025 (fieldwork Nov 2024 to Jan 2025) | Large multi-country panel; consultancy co-author |
| 52% / 53% | Excited / nervous about AI products, 30-country average | Ipsos AI Monitor 2025 | https://www.ipsos.com/en-dk/ipsos-ai-monitor-2025 | Jun 2025 | Online panel; less representative in emerging markets |
| 72% vs 32% | Trust in AI, China vs US | Edelman 2025 tech report | https://www.edelman.com/sites/g/files/aatuss191/files/fr/2025-08/Top%20Findings_2025%20EdelmanTrust%20Barometer_Insights%20for%20the%20Technology%20Sector%20%281%29.pdf | Aug 2025 | PR-firm survey |
| >60% / 84% | Europeans positive on AI at work / want careful management | Eurobarometer via Commission | https://digital-strategy.ec.europa.eu/en/news/commission-survey-shows-most-europeans-support-use-artificial-intelligence-workplace | 13 Feb 2025 | Commission press framing |
| 95.04% | SAG-AFTRA video game agreement ratification vote, ending strike begun Jul 2024 | PC Gamer | https://www.pcgamer.com/gaming-industry/the-videogame-voice-actors-strike-officially-ends-as-performers-ratify-agreement-between-sag-aftra-and-publishers | Jul 2025 | Union-reported tally |
| 91.42% (19.25% turnout) | SAG-AFTRA 2026 TV/Theatrical ratification | Fortune | https://fortune.com/2026/06/05/sag-aftra-approves-four-year-contract-studios-streamers/ | 5 Jun 2026 | Union-reported tally |
| 45 roles | CBA customer-service jobs cut for voice bot, then reinstated | Bloomberg; FSU | https://www.bloomberg.com/news/articles/2025-08-21/commonwealth-bank-reverses-job-cuts-decision-over-ai-chatbots | 21 Aug 2025 | Volume claims disputed between bank and union |
| ~2,400 | Kaiser NUHW mental-health workers in one-day AI-related strike | KQED; NUHW | https://www.kqed.org/news/12076753/northern-california-kaiser-therapists-hold-1-day-strike-over-ai-patient-care-concerns | 18 Mar 2026 | Some outlets say "more than 2,000" |
| 60% / 69% | Nurses distrusting employer AI priorities / acuity scores mismatching own judgment | NNU survey, n>2,300 | https://www.nationalnursesunited.org/press/national-nurses-united-survey-finds-ai-technology-undermines-patient-safety | May 2024 | Union member survey, self-selected |
| 2 Dec 2027 / 2 Aug 2028 | New EU AI Act high-risk dates (standalone / embedded) after Digital Omnibus | Sidley; National Law Review | https://datamatters.sidley.com/2026/06/22/eu-lawmakers-reach-provisional-agreement-to-delay-key-eu-ai-act-obligations/ | Jun-Jul 2026 | Law-firm summaries; confirm on EUR-Lex |
| 423-57-174 | European Parliament vote on AI omnibus deal | Industry summary | https://www.europeanoutdoorgroup.com/members-knowledge-hub/european-parliament-adopts-provisional-agreement-on-ai-omnibus | 16 Jun 2026 | Secondary source; confirm on EP site |
| 0 | Known AI Act fines as of Nov 2026 | Negative search result | n/a | Nov 2026 | Absence of evidence; recheck |
| 99-1 | Senate vote to strip state-AI-law moratorium from budget bill | Nextgov/Route Fifty | https://www.nextgov.com/artificial-intelligence/2025/07/senate-overwhelmingly-passes-amendment-removing-state-ai-moratorium/406448 | 1 Jul 2025 | Search extract; roll call not checked on senate.gov |
| 1 Jan 2027 | Effective date of Colorado's replacement AI law (SB 26-189); original act never took effect | Ropes & Gray | https://www.ropesgray.com/en/insights/alerts/2026/05/colorado-scales-back-ai-law-with-targeted-implications-for-health-care | May 2026 | Search extract; signing date 14 May (one source 18 May) |
| $1,500 | Max NYC LL144 penalty per violation per day; enforcement found ineffective | NY State Comptroller; DLA Piper | https://www.osc.ny.gov/state-agencies/audits/2025/12/02/enforcement-local-law-144-automated-employment-decision-tools | 2 Dec 2025 | Search extract; audit PDF not read |
| $1m | Max SB 53 civil penalty per violation (large frontier developers, >$500m revenue) | FPF | https://fpf.org/blog/californias-sb-53-the-first-frontier-ai-law-explained/ | Effective 1 Jan 2026 | Search extract |
| 54.4% | US nonfarm business labour share, Q4 2025 (down 1.7% y/y); 2025 productivity +2.2% | BLS Productivity and Costs | https://www.bls.gov/news.release/archives/prod2_03242026.htm | 24 Mar 2026 | Official statistic, search extract; subject to revision |
| ~$700-745bn | Combined 2026 capex guidance, Microsoft, Alphabet, Amazon, Meta | Yahoo Finance; datacentres.com tracker | https://finance.yahoo.com/markets/article/magnificent-7-earnings-rush-reveals-ai-spending-surge-with-hyperscaler-capex-set-to-reach-725-billion-in-2026-224901707.html | Apr-Oct 2026 | Company guidance via aggregators; definitions differ; not from filings |
| 0 (CI rules out large effects) | Effect of AI chatbot adoption on earnings and hours, Denmark, 25,000 workers | Humlum & Vestergaard, NBER WP 33777 | https://econpapers.repec.org/RePEc:nbr:nberwo:33777 | 2025 | Strong design; early period (2023-24); search extract |
| <=0.66% | Upper bound on 10-year TFP gain from AI (0.53% adjusted) | Acemoglu, Economic Policy | https://www.nber.org/papers/w32487 | 2024/2025 | Academic forecast |
| $1.5bn (~$3,000/work) | Bartz v. Anthropic class settlement, final approval 20 Jul 2026 | JURIST | https://www.jurist.org/news/2026/07/judge-approves-record-1-5-billion-settlement-involving-anthropic/ | Jul 2026 | Search extract; docket not checked |
| 2,243 | Westlaw headnotes copied by Ross; Third Circuit: not fair use | Haynes Boone; LawNext | https://www.haynesboone.com/news/alerts/third-circuit-rejects-fair-use-for-rosss-copying-of-westlaw-headnotes | 29 Sep 2026 | Search extract; opinion not read |
| 415 TWh (1.5%) to ~945 TWh | Global data-centre electricity 2024 to 2030 (base case) | IEA, Energy and AI | https://www.iea.org/reports/energy-and-ai/executive-summary | Apr 2025 | Agency projection; search extract |
| 6.7-12% | Projected US data-centre share of electricity by 2028 | LBNL (Shehabi et al.) | https://energyanalysis.lbl.gov/publications/2024-lbnl-data-center-energy-usage-report | 19 Dec 2024 | Range reflects scenario uncertainty |
| $193,000 | DoNotPay FTC final order (5-0) | FTC via Slashdot | https://tech.slashdot.org/story/25/02/11/1932223/ | 11 Feb 2025 | Search extract |
| $25m / $15.9m / $14m | Alleged consumer losses: Ascend Ecom / FBA Machine / Click Profit | FTC complaints via press | https://siliconangle.com/2024/09/25/ftc-cracks-misleading-ai-powered-business-schemes-new-initiative/ | 2024-2025 | Allegations, not findings |
| $225k + $175k | SEC penalties, Delphia and Global Predictions (first AI-washing cases) | Baker McKenzie; Ropes & Gray | https://www.ropesgray.com/en/insights/alerts/2025/01/ai-washing-enforcement-in-the-final-days-of-the-gensler-administration | Mar 2024 | Search extract |

## Track 10. Contrarian (from `11-contrarian.md`)

| Figure | What it measures | Source | URL | Date | Reliability note |
|---|---|---|---|---|---|
| ≤0.66% (and <0.53%) | Upper-bound rise in US TFP over 10 years from AI | Acemoglu, Economic Policy | https://www.nber.org/papers/w32487 | May 2024 (journal 2025) | Model-based; excludes new tasks. Not re-read at source |
| 0.8% (vs 1.5% in 2024) | US private nonfarm TFP growth, 2025 | BLS | https://www.bls.gov/news.release/archives/prod3_03192026.pdf | 19 Mar 2026 | Official; seen in search excerpt |
| 2.2% (vs 3.0% in 2024) | US private nonfarm labour productivity growth, 2025 | BLS | https://www.bls.gov/news.release/archives/prod3_03192026.pdf | 19 Mar 2026 | Official; seen in search excerpt |
| 1.4% annualised; 2.2% y/y | US nonfarm business labour productivity, Q2 2026 | BLS | https://www.bls.gov/opub/ted/2026/productivity-up-2-2-percent-from-second-quarter-2025-to-second-quarter-2026.htm | Aug/Sep 2026 | Official |
| 2.1% a year | US labour productivity growth Q4 2019 to Q2 2026 | BLS | https://www.bls.gov/opub/ted/2026/productivity-up-2-2-percent-from-second-quarter-2025-to-second-quarter-2026.htm | 2026 | Official |
| -0.8% q/q; +0.7% y/y | UK output per hour, Q2 2026 | ONS via Trading Economics | https://tradingeconomics.com/united-kingdom/productivity/news/576075 | 18 Aug 2026 | Official, but RTI vs LFS measures disagree |
| 15.9% | TFP level above official, end-2017, after intangibles adjustment | Brynjolfsson, Rock, Syverson | https://www.aeaweb.org/doi/10.1257/mac.20180386 | 2021 | Peer-reviewed, model-based |
| 1.4% | Time saved by genAI as share of all US work hours | Bick, Blandin, Deming | https://www.nber.org/system/files/working_papers/w32966/w32966.pdf | Feb 2025 | n>10,000, self-reported |
| 1-5% / 1-7% | Share of all US work hours assisted by genAI | Bick, Blandin, Deming (two versions) | https://fedinprint.org/item/fedlwp/98805/102025 | Feb / Oct 2025 | Range changed between versions; cite version |
| ~3% (2.8%) | Average time savings among Danish chatbot users | Humlum & Vestergaard | https://bfi.uchicago.edu/wp-content/uploads/2025/04/BFI_WP_2025-56-3.pdf | Apr/May 2025 | Admin + survey data, ~25,000 workers |
| 3-7% | Share of productivity gains passed through to earnings | Humlum & Vestergaard | https://bfi.uchicago.edu/wp-content/uploads/2025/04/BFI_WP_2025-56-3.pdf | 2025 | Seen in coverage |
| >$1tn | Expected AI capex "in coming years" | Goldman Sachs Top of Mind 129 | https://www.goldmansachs.com/insights/goldman-sachs-exchanges/a-skeptical-look-at-ai-investment | 25 Jun 2024 | Opinion/forecast |
| $600bn / $500bn gap | Annual AI revenue needed to justify capex / gap | Sequoia (Cahn) | https://www.sequoiacap.com/article/ais-600b-question/ | 20 Jun 2024 | Heuristic (Nvidia rev x2 x2) |
| $2tn; $800bn | Annual revenue needed by 2030; shortfall after savings | Bain Global Technology Report | https://www.theregister.com/2025/09/24/bain_ai_costs | 23 Sep 2025 | Consultancy forecast |
| $803-828bn | 2026 capex of largest AI spenders | Hargreaves Lansdown | https://www.hl.co.uk/news/ai-hyperscalers-are-expected-to-finish-the-year-spending-a-whopping-828-billion-on-capex | Oct 2026 | Secondary; includes SpaceX; check filings |
| >$1tn in one week | Market value lost by top 20 AI/chip stocks, mid-Oct 2026 | Dealroom | https://dealroom.co/charts/ai-selloff | 30 Oct 2026 | Secondary analysis |
| 19% slower | Task time with AI, experienced OSS developers | METR RCT | https://arxiv.org/abs/2507.09089 | Jul 2025 | RCT, n=16, 246 tasks, early-2025 tools |
| ~20% faster (believed) | Developers' own post-hoc estimate of AI speedup | METR RCT | https://arxiv.org/abs/2507.09089 | Jul 2025 | Same study |
| 50%: ~14.5h vs 80%: ~1h | Claude Opus 4.6 METR time horizons | Wikipedia (METR) | https://en.wikipedia.org/wiki/METR | 2026 | Secondary; check metr.org |
| 24% / 30.3% | Best agent full task completion, TheAgentCompany v1/v2 | Xu et al. | https://www.alphaxiv.org/abs/2412.14161v2 | Dec 2024 / 2025 | Benchmark; older models |
| ~58% / ~35% | Best agents single-turn / multi-turn success, CRMArena-Pro | Salesforce AI Research | https://arxiv.org/html/2505.18878v1 | May 2025 | Vendor benchmark; generic agents |
| >60% to ~25% | GPT-4o retail pass^1 to pass^8 | tau-bench (Sierra) | https://arxiv.org/pdf/2406.12045 | Jun 2024 | Old model |
| 28.4% to 22.4% | Adenoma detection rate in non-AI colonoscopies before vs after routine AI use | Budzyń et al., Lancet Gastroenterol Hepatol | https://wrap.warwick.ac.uk/id/eprint/191005 | Oct 2025 | Observational, 19 endoscopists, 4 centres; confounded; search extract |
| 319 | Knowledge workers surveyed on GenAI and critical thinking | Lee, Sarkar et al., CHI 2025 | https://www.microsoft.com/en-us/research/?p=1135061 | Apr 2025 | Self-reported, cross-sectional |
| 54 | Participants in MIT "Your Brain on ChatGPT" EEG study | Kosmyna et al., arXiv 2506.08872 | https://arxiv.org/abs/2506.08872 | Jun 2025 | Preprint; small n |
| N=4,439 | Participants in four experiments on the social penalty for AI use | Reif, Larrick, Soll, PNAS | https://doi.org/10.1073/pnas.2426766122 | May 2025 | Preregistered vignette experiments |
| 77% (n=625 employees) | Employees saying AI added to their workload | Upwork Research Institute | https://investors.upwork.com/news-releases/news-release-details/upwork-study-finds-employee-workloads-rising-despite-increased-c | Jul 2024 | Vendor survey; 2,500 total incl. 1,250 C-suite |
| >6,000 firms | OECD employer survey on algorithmic management, 6 countries | OECD AI Papers no. 31 | https://ideas.repec.org/p/oec/comaaa/31-en.html | 2025 | Employer (manager) perceptions |
| ~30% | Amazon warehouse injuries above warehouse industry average, 2023 | US Senate HELP majority staff | https://www.help.senate.gov/imo/media/doc/amazon_investigation.pdf | Dec 2024 | Partisan report; Amazon disputes |
| +12% to 38,306 | Practising US radiologists, 2010 to 2022 | Radiology Business (reporting a study) | https://radiologybusiness.com/topics/healthcare-management/healthcare-staffing/radiologist-pipeline-barely-keeping-pace-population-growth | 2025 | Secondary; search extract |
| ~$571,000 (+9%) | Average US radiologist pay, 2025 | Medscape via Fortune | https://fortune.com/2026/05/04/godfather-of-ai-geoffrey-hinton-radiologists-future-of-work-tech-ai-job-anxiety/ | May 2026 | Secondary |
| 75,300; +2% | US interpreter/translator jobs 2024; projected growth 2024-34 | BLS OOH | https://www.bls.gov/ooh/media-and-communication/interpreters-and-translators.htm | 2025 | Official; search extract |
| -21% | Freelance platform posts for automation-prone (writing, coding) jobs, 8 months after ChatGPT | Demirci, Hannane, Zhu, Management Science | https://spiral.imperial.ac.uk/entities/publication/88113a91-b994-4717-8526-dadac657f1cb | 2025 | Peer-reviewed; 1.39m posts; one platform |
| 36%; 43% | UK translators who lost work / income to GenAI | Society of Authors | https://www.bookbusinessmag.com/aggregatedcontent/survey-finds-generative-ai-proving-major-threat-to-the-work-of-translators/ | 2024 | Self-selected, 787 respondents; secondary |
| ~20 to ~13 tellers; +43% branches | ATM effect per urban branch; urban branch growth | Bessen via Conversable Economist | https://conversableeconomist.com/2015/03/03/atms-and-a-rising-number-of-bank-tellers/ | Mar 2015 | Secondary report of IMF F&D article |
| >40% | Agentic AI projects Gartner predicts cancelled by end-2027 | Gartner | https://www.gartner.com/en/newsroom/press-releases/2025-06-25-gartner-predicts-over-40-percent-of-agentic-ai-projects-will-be-canceled-by-end-of-2027 | 25 Jun 2025 | Forecast, not measurement |
| ~130 | Genuine agentic vendors out of "thousands" | Gartner | same | 25 Jun 2025 | Opinion; method not disclosed |


---

## DO NOT CITE

These figures are widely repeated but either trace to a weak origin, are routinely misread, or failed verification in this session. Each line says what to use instead, where there is something.

**Failed or not confirmed in the verification pass**

| Figure | Problem | Use instead |
|---|---|---|
| 121,401 AI-cited US announced job cuts, Jan to Oct 2026 (Challenger) | Could not be confirmed by independent search; October 2026 report not found | 112,713 through July 2026 (Challenger July report), with the caveats in 08 |
| Census BTOS "9% to 18%" | Corrected: about 10% to about 17% per St Louis Fed | "Roughly doubled because the question changed" |
| "Context files make agents worse" (Gloaguen et al.) without qualification | Applies to LLM-generated files; developer-written files slightly helped | State the split |

**Viral statistics with weak or misread origins**

| Figure | Where it really comes from | Why not to cite it |
|---|---|---|
| "95% of AI pilots fail" | MIT NANDA, July 2025, self-described preliminary; 52 interviews, 153 conference-collected survey responses, 300 public initiatives | It measures custom enterprise tools reaching production with P&L impact in about six months, in a self-selected sample. Not a failure rate for "AI pilots". |
| "70% of change programmes fail" | Hammer and Champy's self-described "unscientific estimate"; Hughes (2011) found no valid empirical basis for any of five common sources | No empirical basis. Contested by Burnes and Jackson (2011), but nobody has measured it. |
| "More than 80% of AI projects fail" (RAND 2024) | RAND attributes it to "some estimates"; it is not RAND's finding | Cite RAND for its root causes (65 interviews), not for the 80%. |
| "30 to 50% of RPA projects fail" (EY) | One 2016 EY thought-leadership PDF: "as many as" 30 to 50% of *initial* projects, no method published | Hedge dropped and misdated in later citations. |
| "88% of AI POCs don't reach production" (IDC/Lenovo 2025) | 4 of 33 POCs in a vendor-sponsored study | Same sponsor reported 46% a year later. Neither is a stable estimate. |
| "30% of GenAI projects abandoned after PoC by end of 2025" and ">40% of agentic projects cancelled by 2027" (Gartner) | Gartner press releases, July 2024 and June 2025 | FORECASTS, routinely cited as findings or in the past tense. Cite only as Gartner's prediction. |
| "Only about 130 real agentic AI vendors" (Gartner) | Press release; method not stated | An analyst estimate with no published method. |
| "The UK lost 8% of jobs to AI" (Morgan Stanley, Jan 2026) | Survey of firms already using AI for a year, in five sectors, reporting own headcount changes | Not a labour-market statistic. |
| "40% of jobs will be affected by AI" (IMF 2024) | Exposure measure (task overlap), SDN/2024/001 | Exposure, not displacement; about half of exposed jobs judged likely to benefit. Cite only as exposure. |
| "47% of jobs at risk" (Frey and Osborne 2013) | Model-based automation probability by occupation | Not a forecast of job losses; task-based re-estimates are far lower. |
| "AI makes developers 19% slower" | METR RCT, July 2025, n=16 experienced maintainers, early-2025 tools | Solid but narrow; METR's 2026 redesign says newer data cannot give a reliable estimate. Never cite as a general claim. |
| "77% of employees say AI added to their workload" (Upwork) | Vendor survey; the 77% covers employees *using AI* among 625 employees in a 2,500 sample with 1,250 executives | Usable only with its scope. Do not drop "using AI". |
| "Big Tech cut new-grad hiring by 50%" (SignalFire) | VC firm's own talent data; change in new-grad share of hires vs 2019 | Comparison year chosen for effect; versus 2023 the fall is much smaller. |
| "UK entry-level jobs down a third since ChatGPT" (Adzuna) | Job-board adverts Nov 2022 to mid-2025 | Overlaps monetary tightening and NI and minimum-wage rises. Cannot be attributed to AI. |
| "98% of small businesses use AI" (US Chamber/Teneo 2024) | Counts any software with AI features | Not deliberate AI use. |
| "AI adoption among small businesses surged 41%" (Thryv 2025) | Relative growth 39% to 55% in a 540-person vendor panel | Misread as a level. |
| "68% / 76% of small businesses use AI" (Goldman Sachs 10KSB) | Alumni of Goldman's own programme | Not a general SMB sample. |
| "Klarna's AI does the work of 700 agents" | Klarna's own Feb 2024 announcement, unaudited | Use only with the 2025 quality reversal and the F-1 headcount figures attached. |
| "IBM fired 8,000 people and replaced them with AI" | Blend of separate events and viral posts | CEO said HR roles replaced were "in the hundreds"; total headcount rose. |
| "Salesforce cut 4,000 jobs because of AI" | Benioff podcast remark (support about 9,000 to 5,000), no timeframe or method | CEO statement, not a filing. Cite as his claim only. |
| "77% of businesses use AI for automation" (Anthropic) | 77% is the share of sampled API transcripts showing automation patterns | Not a share of businesses. |
| "Iceland's four-day week was an overwhelming success" | Advocacy report (Autonomy and Alda, 2021): 35-36 hour weeks for about 2,500 public-sector workers | Not a four-day week; about 1% of the workforce. |
| "92% of UK four-day-week firms kept it" | 56 of 61 self-selected firms continuing in some form; 18 permanent | Self-selected sample run by an advocacy organisation. |
| "The one-person billion-dollar company is here" (Medvi) | NYT profile, April 2026; $1.8bn is the founder's projection | About $401m 2025 revenue; FDA warning letter and class action. |
| "AI's $600B question" (Sequoia) | One partner's blog heuristic, June 2024 | Heuristic, not an accounting gap. |
| "AI will add only 0.66% to GDP" (Acemoglu) | 0.66% is a TFP upper bound over ten years, model-based, excluding new tasks | Do not conflate TFP with GDP. |
| "AI deskills doctors" | One observational study, 19 endoscopists, confounded | A signal, not a finding. |
| "ChatGPT rots your brain" (MIT Media Lab) | 54-person EEG preprint on essay writing | Not peer-reviewed at release; framing outran data. |
| "79% of Americans don't trust businesses to use AI responsibly" | 2023 Bentley-Gallup wave | Out of date; use the 2026 figure (27% trust). |
| "EU fined companies EUR 18.4m under the AI Act" | Low-quality web page; no official source | No AI Act fine found to date. |
| "UK introduced a frontier AI bill in May 2026" | Two low-quality sites | Law-firm sources say the King's Speech contained none. |
| "Data centres use 4.4% of US electricity" (LBNL) | Attributed to LBNL 2024; not confirmed in extracts | Check the report first. |
| "Record 1,208 radiology residency positions in 2025" | Single Substack post | Check NRMP data. |
| "Hundreds of millions of hours saved" style vendor ROI claims, including Forrester TEI studies | Vendor-commissioned models | OPINION, not evidence. |

**Unverified leads (named in track files but not sourced this session)**

- Sculley et al.'s "only a small fraction of a real ML system is ML code" (Figure 1): check the NeurIPS PDF.
- Any "process debt" origin claim: not traced.
- Keynes's "fifteen-hour week" wording, Covello's "$1tn problem" line, Gartner's "agent washing" definition, the Moffatt tribunal's "remarkable submission": fetch originals before quoting.
