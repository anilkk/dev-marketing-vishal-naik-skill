# Developer marketing skill for Claude

Stop marketing to "developers" as one person. Segment them, map what they feel at each funnel stage, and win the internal buy-in that makes the plan actually ship.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Works with Claude Code](https://img.shields.io/badge/Works%20with-Claude%20Code-6C3EF5)](https://claude.com/claude-code)
[![Works with Cowork](https://img.shields.io/badge/Works%20with-Cowork%20%26%20claude.ai-1f6feb)](https://claude.ai)
[![Source: Vishal Naik](https://img.shields.io/badge/Source-Vishal%20Naik%20playbook-0b7285)](https://sharebird.com/h/product-marketing/playbooks/how-docusign-increased-their-developer-marketing-conversion-rates-by-50)

Built on the published playbook of **Vishal Naik**, who ran developer marketing at DocuSign and lifted developer marketing conversion rates by 50 percent. He later led developer marketing for Google Assistant and product marketing at Google, and is now Head of Product Marketing, Platform and Integrations at Box.

## 10-second demo

**You ask:**

> Our API signups are flat. Write me a developer marketing plan.

**Claude answers (truncated):**

> Before the plan, one question the data has to settle: who is actually signing up?
>
> At DocuSign this exact assumption was wrong. The team believed enterprise developers were the audience. Q4 2021 signup data showed a near even split with SMB. The plan had been aimed at half the funnel. Fixing the split is what produced the 50 percent lift.
>
> **Step 1, hypothesis.** You believe signups are flat because awareness is low. The competing hypothesis is that awareness is fine and one persona is dropping out at Evaluate.
>
> **Step 2, data to pull.** Signups by company size, by language or framework, by first endpoint called. Trial to first successful call. Trial to live integration.
>
> **Step 3, personas to map (his four):**
>
> | Persona | What they feel at Evaluate | What answers it |
> |---|---|---|
> | SMB developer | "I have two hours and no teammate to ask." | Copy paste quickstart, no sales call |
> | Enterprise developer | "Will security and procurement kill this?" | Compliance page, SSO docs, sandbox |
> | "Doer" developer | "Does this work in my framework, today?" | Language specific codelab |
> | ISV partner | "Can I resell what I build on this?" | Partner terms, multi tenant docs |
>
> **Step 4, buy in.** None of this ships without product, corporate marketing, and sales. Build the opportunity deck: lead with the revenue in the underserved persona, name each team's win.
>
> **Step 5, project plans.** A bought in strategy with no owners is a slide.
>
> Metrics to commit to: trial signups per persona, trial to live integration rate, integrations in production, speed to first integration.

That is the skill running in Diversify mode. Four other modes are listed below.

## Install

### Claude Code

```bash
git clone https://github.com/anilkk/dev-marketing-vishal-naik-skill.git
cp -r dev-marketing-vishal-naik-skill/dev-marketing-vishalnaik ~/.claude/skills/
```

For a single project instead of every project, copy into `.claude/skills/` inside that repo.

### Cowork and claude.ai

1. Open [dev-marketing-vishalnaik/SKILL.md](dev-marketing-vishalnaik/SKILL.md) and copy the whole file.
2. Paste it to Claude and say: "Save this as a skill."
3. Claude saves it to your account. It persists across sessions.

## Usage

| You say | Mode it triggers |
|---|---|
| "Build a developer marketing plan for our API" | **Diversify** |
| "I need a deck to get the COO to fund this" | **Pitch** |
| "How should we launch the new SDK to developers?" | **Launch** |
| "What should we actually measure?" | **Measure** |
| "Why do we keep marketing to developers as one group?" | **Coach** |

## What is inside

| Mode | What it does |
|---|---|
| **Diversify** | Builds a persona segmented plan: four personas, journey and emotion maps, channels and content per persona |
| **Pitch** | Structures the opportunity deck and the buy in deck, plus the prioritization matrix for annual planning |
| **Launch** | Designs a drip delivery launch with the day one materials slate |
| **Measure** | Defines the funnel and business impact metrics stack, from trial signup through live integrations |
| **Coach** | Teaches the framework using your product as the example |

Also in the repo: [REFERENCE.md](REFERENCE.md) is a one page cheat sheet of every framework, and [examples/](examples/) holds two full worked runs.

## What it is built on

The skill encodes Naik's published material:

- The **Principles of Developer Marketing**, seven principles covering audience, messaging, segments, tangible value, paths of usage, launch timing, and channels
- The **four developer personas**: SMB developer, enterprise developer, "doer" developer, ISV partner
- The **5 step diversified developer PMM process**: hypothesis, data, journey map, buy in, project plans
- The **two pitch decks**, opportunity and buy in, plus democratic prioritization
- His **metrics stack**, measured through to integrations running in production

## What it deliberately refuses to do

- It will not hand you a plan for "developers" as one audience. Personas first, always.
- It will not accept your stated audience without asking what the signup data says.
- It will not call a launch ready if docs, codelabs, and samples are not shipping on day one.
- It will not stay in its lane's neighbours. DevRel program design, segmentation research method, positioning theory, and content engine operations get handed off, not half done.
- It does not reproduce Naik's playbook text. It encodes the frameworks and cites the source.

Parts of the source playbook sit behind a free Sharebird account. The skill carries a fidelity note marking which details are summarized and which are extrapolation.

## Source and credits

Every framework in this skill comes from **Vishal Naik's** own published work. Read the originals:

- **Playbook:** [How DocuSign Increased Their Developer Marketing Conversion Rates By 50%](https://sharebird.com/h/product-marketing/playbooks/how-docusign-increased-their-developer-marketing-conversion-rates-by-50) on Sharebird. This is the primary source for the principles, the four personas, the 5 step process, the pitch deck structure, and the 50 percent result.
- **AMA:** [Vishal Naik on Developer Product Marketing](https://sharebird.com/h/product-marketing/ama/google-assistant-developer-maarketing-lead-vishal-naik-on-developer-product-marketing). Source for the metrics stack, channel guidance, sales enablement, and how he separates developer marketing from DevRel.
- **More AMAs:** [his Sharebird profile](https://sharebird.com/profile/vishal-naik) covers market research and product launches.
- **His writing at DocuSign:** [docusign.com/blog/author/vishal-naik](https://www.docusign.com/blog/author/vishal-naik)
- **Interview:** [Influencing the Product Roadmap](https://thecompetenetwork.com/episode/vishal-naik-product-marketing-lead-at-google-on-influencing-the-product-roadmap), Compete Network
- **Where he is now:** [Head of Product Marketing, Platform and Integrations at Box](https://theorg.com/org/box/org-chart/vishal-naik)

The frameworks belong to Vishal Naik. This repository contains original text that encodes them for use with Claude. It reproduces no source content. The MIT license covers the repository text only. See [LICENSE](LICENSE).

Packaged by [Anil Kumar Krishnashetty](https://github.com/anilkk).
