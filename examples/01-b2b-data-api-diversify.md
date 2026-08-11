# Example 1: Diversify mode, B2B web data API

**Product:** a web data platform selling scraping APIs, proxy infrastructure, and datasets, increasingly used to feed AI agents and LLMs.

**The ask:** "Signups are up but revenue is flat. Write us a developer marketing plan."

**Note on numbers:** every figure below is an illustrative estimate, not measured data from a real company. The point is the shape of the analysis, not the values.

---

## Step 1. Develop the hypothesis

The stated belief inside the company is that the audience is senior data engineers at large enterprises, because those are the accounts sales closes.

The competing hypothesis, and the one worth testing first: signups are flat in revenue because a fast growing persona is signing up, failing to reach a first successful call, and churning silently. AI application developers arriving from an agent framework tutorial look nothing like a data engineer running a nightly pipeline.

The discrepancy that triggered this: signup volume is up 40 percent year over year while revenue is flat. Either the new signups are the wrong people, or they are the right people who never got to a working integration.

## Step 2. Collect the data

Pull, before writing any plan:

- Signups by company size, self reported role, and country
- First endpoint called, and time from signup to first successful call
- Trial to live integration conversion rate, split by the above
- Drop off point for signups that never made a successful call
- Support and community questions clustered by theme

Illustrative finding: signups split roughly 45 percent solo and small team builders, 35 percent enterprise data teams, 20 percent agencies and ISVs. Enterprise converts to live integration at an estimated 3 times the rate of the solo segment, but the solo segment is the one growing. Nobody is marketing to them.

That gap is the opportunity, and it is the first slide of the deck.

## Step 3. Map the journey, per persona

### Persona A. SMB and indie developer

Wearing every hat. No teammate to ask. Evaluating on a weekend.

| Stage | What they do | What they think and feel | What answers it |
|---|---|---|---|
| Awareness | Hit a blocked page while building a side project | "There has to be a way around this" | A tutorial that solves the exact blocked page problem |
| Evaluate | Scan pricing, look for a free tier | "Is this going to cost me 500 dollars before I learn anything?" | Transparent per request pricing, real free tier |
| Trial | Copy a snippet into a terminal | "I have 30 minutes before I lose interest" | Quickstart that returns real data in under 5 minutes |
| Build | Wire it into their app | "Will this break when the site changes?" | Reliability docs, retry patterns, error message guidance |
| Production | Ship it | "Can I afford this at scale?" | Usage calculator, clear upgrade path |

### Persona B. Enterprise data platform engineer

Specialized, inside procurement and compliance constraints, evaluating on the clock.

| Stage | What they think and feel | What answers it |
|---|---|---|
| Awareness | "We are already paying three vendors for this" | Consolidation and TCO content |
| Evaluate | "Legal and security will kill this before I finish" | Compliance page, data governance docs, SOC 2 posture, DPA |
| Trial | "I need a sandbox my security team will approve" | Sandbox with SSO, scoped keys, audit logging |
| Build | "This has to survive a code review" | Reference architectures, SDKs, IaC examples |
| Production | "Who do I page at 3am?" | SLA, support tiers, named contact |

### Persona C. AI agent and application builder ("doer")

Needs a result this afternoon. Building an agent, not a pipeline.

| Stage | What they think and feel | What answers it |
|---|---|---|
| Awareness | "My agent needs live web data and hallucinates without it" | Content that lives in the agent framework ecosystem |
| Evaluate | "Will this work with my framework today?" | Framework specific quickstarts, MCP endpoint, agent tool docs |
| Trial | "Show me the snippet, not the webinar" | Copy paste snippet, no sales gate |
| Build | "Structured output or I have to write a parser" | Clean JSON schemas, typed SDKs |
| Production | "Latency budget" | Published latency benchmarks |

### Persona D. Agency and ISV partner

Building data products for their own clients.

| Stage | What they think and feel | What answers it |
|---|---|---|
| Evaluate | "Can I resell this and keep a margin?" | Partner program, volume pricing, white label terms |
| Build | "Multi tenant, per client isolation" | Multi tenant patterns, sub account API |
| Production | "Will my client's business survive a policy change?" | Roadmap transparency, change notice policy |

## Step 4. Get buy in

**Opportunity deck outline, six slides.**

1. The number. Signups up 40 percent, revenue flat. Here is why.
2. Who is actually showing up. The three way split, with the growth curve on the underserved segment.
3. Where they die. Time to first successful call, by persona.
4. The revenue at stake. Underserved segment volume times the conversion rate the enterprise segment already achieves.
5. The plan in one slide. Four personas, four journeys, four content tracks.
6. What each team is being asked for.

**Stakeholders and their win:**

| Team | What they are asked for | Their win |
|---|---|---|
| Product | Framework specific quickstarts, sandbox improvements | Activation rate rises, a metric they already own |
| Engineering | MCP and agent tool endpoints documented | Fewer malformed requests hitting the API |
| DevRel | Presence in agent framework communities | A clearly scoped audience instead of "all developers" |
| Corporate marketing | Persona segmented email streams | Better click through than a single broadcast list |
| Sales | 101 level enablement on the agent use case | Stops losing deals they did not know were technical |
| Docs and content | Per persona documentation tracks | A prioritized backlog instead of an open ended one |

Then run the prioritization matrix. Let each team weigh the opportunities. The plan that survives is the one they helped rank.

## Step 5. Translate to project plans

Four project plans, one per persona, each with an owner, a date, and a single primary metric:

1. Indie self serve track. Owner: growth. Metric: time to first successful call under 5 minutes.
2. Enterprise trust track. Owner: PMM plus security. Metric: trial to live integration rate.
3. Agent builder track. Owner: DevRel plus docs. Metric: framework quickstart completions.
4. Partner track. Owner: partnerships. Metric: sub accounts created.

## Measure

Report monthly in three dimensions:

- **Platform momentum:** trial signups per persona, speed to first integration
- **End user value:** integrations in production, integrations per customer
- **Business impact:** trial to live conversion rate, revenue per live integration

Followers and event attendance stay in the appendix. They are inputs.

---

*Frameworks by Vishal Naik. [Source playbook](https://sharebird.com/h/product-marketing/playbooks/how-docusign-increased-their-developer-marketing-conversion-rates-by-50).*
