---
dual: true
name1: Bill Malloy
website1: https://www.linkedin.com/in/bmalloyiii/
email1: bill@thirdpath.com
name2: Sam Howard
website2: https://www.linkedin.com/in/samuel-j-howard/
email2: sam@thirdpath.com
photo1:
photo2:
domain: D09

title: "Option A: Comparables and Coverage in Private Markets: finding the managers and companies we don't know / Option B: When to commit, and to whom: do public market signals lead private-markets vintage returns?"

bio: |
  Bill Malloy leads Thirdpath's technology efforts as Fellow of AI and Machine Learning and acting CTO, and is a member of the firm's GP Seeding & Stakes team. He began his investment career at Draper Fisher Jurvetson (DFJ) Zone Ventures, and his investment experience includes board-level roles and investments in companies such as Uber, Twilio, Lyft, SendGrid, Addepar, Fetch Robotics, Affinity and Zanbato. Earlier he held product and business development roles at Listen.com (acquired by RealNetworks) and MusicMatch (acquired by Yahoo). He holds an MBA from the University of Southern California and a B.S. in Chemical Engineering from Clemson University, and completed computer science coursework at Stanford University.

  Sam Howard is VP, Investments & Products at Thirdpath, where he spearheads Beacon, the firm's investment platform, and supports portfolio monitoring, reporting and analytics across the private credit platform. He has over a decade of experience across venture, technology and investment operations, including co-founding MiP.O.V. Technologies (EvoNexus-backed) and conducting diligence on early-stage technology and life sciences companies with Tech Coast Angels. He holds a B.S. in Mechanical Engineering from the University of Kentucky, where he played wide receiver on the football team, and a Venture Capital Certificate from UC Berkeley. He also serves on the Marketing Advisory Board at Point Loma Nazarene University.

description: |
  We are proposing two options for this domain.

  Option A: Comparables and Coverage in Private Markets: finding the managers and companies we don't know
  We believe private-markets investors often decide with incomplete maps. Given one fund manager or one private company, the questions an allocator asks first are "who are its true peers?" and "which of them are we not tracking?" Answering them today is largely manual: an analyst searches PitchBook, filings and press, and can still miss names. In this domain, students build the map. Working from public sources (SEC Form ADV and Form D filings, public pension private-equity disclosures such as CalPERS and CalSTRS, company registries, press and company websites), teams build an entity-resolution pipeline that links the same manager or company across sources, a cohort model that returns comparables by strategy, vintage, fund size and geography for managers and by sector, stage, geography and size for companies, and a coverage map that shows an allocator which peers exist that it has never looked at. In Quarter 2, teams test their pipeline against a de-identified slice of Thirdpath's own coverage data under NDA and measure what the firm may be missing. The output is intended to inform a real tool: Thirdpath expects its investment platform, Beacon, to ask these questions through an AI interface, currently planned for 2027.

  Option B: When to commit, and to whom: do public market signals lead private-markets vintage returns?
  In private markets, we believe returns are largely shaped by when capital goes in, but whether a vintage was good is typically known only about a decade later. Public markets, by contrast, price new information every day. This project asks whether public markets give allocators an early read: when a public market indicator moves, does that help predict how private funds committed in the following months will perform, and does the effect differ across asset classes and strategies (buyout, growth equity, venture, direct lending, distressed credit, real estate, infrastructure)? Students assemble a broad set of candidate indicators covering equity valuations, earnings, interest rates and the yield curve, credit spreads, volatility, IPO and M&A activity, leveraged loan pricing, and fund flows. They then search for the ones that appear to lead vintage returns, and by how long. Thirdpath's own credit-cycle score, built from public data, is a starting benchmark to beat. The data is deliberately small, and that is the core challenge: each strategy has perhaps 25 usable vintages, their time windows overlap, recent vintages are still largely unrealized and often reported at smoothed valuations, and testing hundreds of indicators against so few observations is likely to produce convincing correlations that mean nothing. The work is to separate real signals from noise, using out-of-sample backtests, corrections for multiple testing, uncertainty bands and adjustments for interim valuations. Market history comes from FRED, the Federal Reserve and public market sources. Fund and vintage returns come from public pension disclosures (CalPERS, CalSTRS, Washington State, Oregon) and, where licensing permits, benchmark data provided under NDA. In Quarter 2, teams turn the indicators that hold up into a research-stage, forward-looking commitment signal for each strategy, test it on held-out recent vintages, and then ask the second question: in the conditions the signal favors, which features of a manager's prior track record, if any, are most associated with the performance of its next fund? The work is intended to inform Beacon's market dashboard and the commitment questions Thirdpath expects its AI analyst to address, currently planned for 2027.

summer: |
  No required reading or pre-work over the break. Students who want a head start can browse the public data the work draws on: SEC Form ADV and Form D filings, public pension private-equity disclosures (CalPERS, CalSTRS) and FRED. Topics worth reviewing: entity resolution and record linkage for Option A; time series, backtesting and multiple-testing corrections for Option B. On the technology side, we expect to use React, Next.js and other web app libraries, which students may not have used before, so some familiarity with them will help.

time: 3:00PM Pacific (to be confirmed)

modality: Hybrid (in person and Zoom)

industry: true

style: |
  We (Bill and Sam) will run the section together, and both of us plan to be there every week. Students work as their own project team rather than being folded into a larger group, and the weekly one-hour hybrid section is used to review progress, answer questions and agree on the next week's work. We will be hands-on about the domain: how allocators actually use this information, which public sources can be trusted, and what a useful result looks like to an investment team. We expect students to be independent on the data science: choosing methods, building the pipeline and defending their choices. Between sections we are reachable by email when the team is blocked.

seats: 4

tag: app

goal: |
  In both options, the halfway point is a reproducible baseline built on public data plus a scoped Quarter 2 proposal.

  Option A: (1) two or three public sources (for example SEC Form ADV and Form D filings plus one public pension disclosure) ingested into a clean, documented dataset; (2) a baseline entity-resolution pipeline that links managers across those sources, with precision and recall measured on a hand-labeled sample; (3) a first cohort model that returns comparables for a given manager, with a simple check on whether the peers make sense; (4) a written Quarter 2 proposal covering private companies, the coverage map and the test against Thirdpath's de-identified coverage data.

  Option B: (1) an assembled, documented dataset of candidate public market indicators and of vintage returns by strategy from public pension disclosures; (2) a baseline test of a small set of indicators against vintage returns for one or two strategies, compared with Thirdpath's credit-cycle score; (3) a working evaluation framework (out-of-sample backtests, multiple-testing corrections, uncertainty bands, treatment of unrealized vintages) that shows which early results hold up; (4) a written Quarter 2 proposal for the forward-looking commitment signal and the manager track-record question.

notes: |
  We have described two options (A and B) and are glad to run whichever is the better fit for the program and for student interest. Both options start from public data. Parts of the work use Thirdpath data shared under NDA (a de-identified slice of our coverage data in Option A, benchmark data in Option B, where licensing permits), so students would sign an NDA before working with it.
---
