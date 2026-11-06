# Research brief: The AI-Native Transition

You are my research analyst. I want primary sources and organised, citable output, not a summary. You have a budget of roughly 1 to 2 hours. Spend it on breadth across all ten tracks, with depth where the evidence is strongest. Work unattended: do not stop to ask me questions. Where something is ambiguous, make a reasonable call and note it in `progress.log`.

## Who I am

I work at Actualisation (https://www.actualisation.ai/), which builds agentic AI teams and a platform ("Studio") that connects to a business's own data so humans and agents work from the same context. Their purpose: "we believe in the freedom to be more human." I write about AI platform strategy, enterprise and SMB AI adoption, and agentic teams, and I'm building authority on the shift from legacy to AI-native businesses and its human consequences. This is the research spine for months of content.

## Thesis to stress-test, not confirm

*The tech is the easy part; the transformation is the hard part. AI fails in businesses because the business isn't ready: nobody can describe the real workflow, there's no shared context humans and agents both work from, and people resist a whole new way of working.*

Find where this is wrong, overstated or contested. A brief that only agrees with me has failed.

Working definitions, also to be tested:
- **AI-native:** humans and agents work from one stored, shared business context. One platform both read from and write to.
- **Legacy:** humans only, no AI in the workflow.
- **Spectrum:** almost every business uses AI somewhere (e.g. personal ChatGPT accounts), so this is a spectrum. Fully AI-native is rare.

## Research tracks

Cover all ten. Prioritise primary sources: filings, earnings call transcripts, official labour statistics, peer-reviewed papers, regulatory documents, survey methodology and raw data.

1. **What "AI-native" means.** Definitions across industry, academia and vendors; who coined it; maturity models compared and where they disagree; named companies genuinely rebuilt around AI (what changed, cost, what broke); examples of the term used as marketing.
2. **SMB.** Real adoption vs claimed (interrogate survey samples); realistic build costs; failure and abandonment rates; who does implementation for SMBs; constraints (no data team, owner time, no documented processes). What "AI-native" plausibly means for a 10-person firm.
3. **Enterprise.** Production vs pilot purgatory (Gartner, McKinsey, MIT, Deloitte etc.: read the reports, name the limitations, especially any "share of pilots reaching production" figure and where it really comes from); agentic systems in production in 2026 vs demos, incidents and post-mortems; the shared-context problem technically (vector stores, context layers, MCP, memory); procurement, security and governance timelines; real cost and ROI.
4. **Inertia and education.** Change-management evidence on what works; the burden of teaching a new way of working, not a new tool; generational and cultural friction; middle management as blocker or lever.
5. **What goes wrong.** Named failure cases; the "client can't describe their own workflow" problem in process-mining and automation literature; abandonment rates and causes; automation debt, drift, evaluation gaps.
6. **Working with agents.** Human-agent teaming in practice in 2026: task allocation, oversight, escalation; roles reshaped vs eliminated (evidence, not forecasts); new job titles and org designs with real examples; machine-readable SOPs, context files, shared skills; accountability and audit when the agent is wrong.
7. **Displacement.** Measured employment effects so far (peer-reviewed or high-quality empirical); sector exposure; junior-role and hiring-pipeline effects; serious counter-evidence of no effect or role creation; UK and Europe vs US.
8. **"What will people do?"** Historical displacement (agriculture, manufacturing, clerical): predicted vs actual; UBI, four-day-week and job-guarantee trials and their findings; what people do with freed time (empirical); meaning, status and identity without work, including the strongest pessimistic arguments; whether evidence supports "removing rote work makes people more human"; solo operators with agent teams, micro-business, care and community work: what's real vs a story.
9. **Social and political fallout.** Public opinion by country and demographic with trend; union and collective bargaining cases; EU AI Act, UK, US federal and state regulation: enforced vs announced; who captures the productivity surplus; the anti-AI position at its strongest, and the "AI advice" grifter layer, both characterised fairly.
10. **Contrarian.** The strongest evidence that transformation is slower, narrower or less profitable than claimed; that agents are further from production than hyped; that displacement is task change not job loss; that "freedom to be more human" fails or backfires.

## Evidence rules (non-negotiable)

- **Every claim has a URL and a date.** No URL, no claim. Prefer primary sources. If a secondary source misrepresents its primary, say so.
- **Label everything** as EVIDENCE, FORECAST or OPINION. Vendor marketing and consultancy thought leadership are not evidence.
- **Quotes only from pages you fetched this session**, copied exactly, with URL. If you only saw it in a search snippet or remember it, paraphrase and say so.
- **Note sample size and method** for any study driving a big claim.
- **Trace viral statistics to their origin.** If a widely repeated number goes back to one weak source, say exactly that.
- **When credible sources conflict, present both.**
- **No filler.** I know what AI is. Go straight to evidence.

## Setup and working method

1. Work in `./research/`. If it isn't a git repository, run `git init`.
2. Keep `progress.log` updated: one line per completed step with a timestamp.
3. Complete one track at a time. Write each track file in full, then `git commit` it before starting the next. Never hold more than one track's findings in memory unwritten.
4. If you run low on time or context, write what you have, mark the file `INCOMPLETE` at the top, commit, and move on. A thin file for every track beats perfect files for half of them.

## Output files

Track files, each with: key findings (sourced, dated, labelled), strongest counter-evidence, open questions, and "what's genuinely uncertain".

- `02-ai-native-definitions.md`
- `03-smb.md`
- `04-enterprise.md`
- `05-inertia-and-education.md`
- `06-what-goes-wrong.md`
- `07-working-with-agents.md`
- `08-displacement.md`
- `09-what-will-people-do.md`
- `10-social-political.md`
- `11-contrarian.md`

Then, after all track files exist:

- `01-thesis-stress-test.md`: what holds, what breaks, what's contested. Honest.
- `12-facts-and-figures.md`: every hard number: figure, what it measures, source, URL, date, reliability note. Ends with a clearly marked **DO NOT CITE** section.
- `13-quotes.md`: verbatim quotes, each with speaker, source, URL, date, context.
- `14-reading-list.md`: sources worth reading in full, ranked, one line each on why.
- `15-open-questions.md`: what to research next and what was thin. Be blunt.

## Verification pass (do this before the final files)

Pick at least 10 numbers from `12-facts-and-figures.md`, prioritising the most striking. Re-fetch each URL and confirm the number, date and context match. Move anything you can't confirm to DO NOT CITE, and record the results in `verification.md`. Do the same for every quote in `13-quotes.md`.

## Final files

- `99-morning-brief.md`: max 800 words. The five findings that would most change how I write about this, the strongest evidence against my thesis, and the three questions I should answer next. Written for a busy person who trusts you to have read everything.
- `00-INDEX.md`: every file with a one-line description, plus a "start here" list of the 10 most important findings.

## PDF export (last step)

Keep the Markdown files as the source of truth. Then create `./research/pdf/` and convert each `.md` file to PDF. Try in order: `pandoc` with a PDF engine, then `npx md-to-pdf`, then Python (`markdown` + `weasyprint`). Install what's missing. Also produce one combined `AI-native-transition-full.pdf` in the order 99, 00, 01 to 15. Open one PDF to check it rendered (headings, links, tables) and commit.

## Style

Plain, direct prose. No em dashes. No hype words. Short paragraphs. Say where you're uncertain and where sources are weak. "This statistic is widely repeated but traces to one 2024 vendor survey with a self-selected sample" beats a confident number.

Start now.
