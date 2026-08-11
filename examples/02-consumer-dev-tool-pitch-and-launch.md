# Example 2: Pitch and Launch modes, prosumer transactional email API

**Product:** a transactional email API with a large base of indie developers, side projects, and small SaaS teams. Free tier is generous. Most users never talk to sales.

**The ask:** "I need to convince our COO to fund a developer marketing team, and then launch our new React email component library. Help with both."

**Note on numbers:** all figures are illustrative estimates for demonstration, not measured data.

---

# Part 1. Pitch mode

## The discrepancy

Marketing reports 60,000 signups this year and treats that as the headline. Finance reports that 92 percent of those accounts have never sent a single production email. The company is celebrating an input.

That gap is the pitch.

## The opportunity deck

**Rule from Naik: get to the point fast. The COO decides in the first three slides.**

### Slide 1. The number

> 60,000 signups. 4,800 sending in production. We are spending to fill a bucket with a hole in it.

### Slide 2. Where the hole is

Time from signup to first sent email, by persona. Illustrative:

| Persona | Share of signups | Median time to first send | Never sends |
|---|---|---|---|
| Indie or side project developer | 58 percent | 22 minutes | 71 percent |
| Small SaaS team | 24 percent | 2 days | 44 percent |
| Agency building for clients | 12 percent | 6 days | 61 percent |
| Enterprise evaluator | 6 percent | 3 weeks | 88 percent |

The indie developer activates fastest and still churns most. They activate and then leave, which means the product works and the follow through does not. That is a marketing problem, not an engineering one.

### Slide 3. The money

Estimate: moving the small SaaS segment from 56 percent activation to 70 percent, at an estimated 340 dollars annual value per activated account, is roughly 680,000 dollars of new annual recurring revenue. One segment. One number.

### Slide 4. Why this needs a team, not a campaign

Four personas need four content tracks, four email streams, and four onboarding paths. That is a program, not a project.

### Slide 5. The ask

Two headcount. One developer marketer, one technical content writer. Plus 40 hours of engineering time for onboarding instrumentation.

### Slide 6. What each team gets

| Team | Contribution | Their win |
|---|---|---|
| Product | Onboarding instrumentation | Activation becomes measurable, a metric they are already judged on |
| Engineering | Event tracking on first send | Fewer support tickets from stuck accounts |
| Support | Persona tagging on tickets | Deflection through better docs |
| Sales | 101 enablement on the agency use case | A segment they currently ignore |
| Finance | The activation model | A forecast input that is not signup count |

## The buy in deck

Different deck, different job. The opportunity deck sells the problem to the COO. The buy in deck sells the plan to the teams executing it.

Structure: the journey map, the plan, the owner per workstream, the timeline, and the prioritization matrix everyone voted on.

**Naik's rule on prioritization: run it democratically.** Put the twelve candidate initiatives in front of product, support, engineering, and sales. Have each team rank them. The plan that ships is the one they ranked, not the one marketing wrote alone.

Illustrative output of that vote: onboarding email rework ranked first by three of four teams. The conference sponsorship marketing had penciled in ranked eleventh. That is the process working.

---

# Part 2. Launch mode

**Launching:** a React email component library that lets developers build templates in JSX.

## What the traditional launch would do

Six weeks of teaser posts, a launch day blog announcement, a webinar the following month, and documentation "coming soon."

Naik's objection is direct. Developers want to see demos and jump into the code right away, not wait. A launch a developer cannot build against on day one is a broken launch.

## The drip, four weeks out

| Week | Drip action | Channel |
|---|---|---|
| Week 4 | "We are building this, here is why templates are painful" post | Blog, Reddit, Hacker News comment presence |
| Week 3 | Public alpha repository, issues open | GitHub |
| Week 2 | Short screen recording of the component API | YouTube, X, LinkedIn |
| Week 1 | Email to the developer list: "shipping next Tuesday, here is what to expect" | Email, the number one action driver |
| Launch | Full slate below | All |

The drip builds anticipation. It also surfaces API design problems while they are still cheap to fix.

## The day one slate, no launch without all of it

- [ ] Blog post with a working example, not a feature list
- [ ] Full component documentation
- [ ] Copy paste quickstart, under 5 minutes to a sent email
- [ ] Sample repository, deployable in one click
- [ ] Codelab for the two most common frameworks
- [ ] Migration guide from the previous template approach
- [ ] Updated developer center navigation
- [ ] Live demo session scheduled for launch week
- [ ] Support and sales briefed at the 101 level

If any box is unchecked on launch morning, the launch moves. That rule is the whole discipline.

## Per persona launch messaging

| Persona | The line that lands | The asset |
|---|---|---|
| Indie developer | "Write emails in JSX. No more HTML tables." | The 5 minute quickstart |
| Small SaaS team | "Your designer and your engineer can finally use the same file." | Sample repository with a design token setup |
| Agency | "Ship client templates without rebuilding them per client." | Multi tenant template example |
| Enterprise evaluator | "Version controlled, code reviewed, testable email templates." | Testing guide and CI example |

Same launch. Four different first sentences.

## Measure the launch

- Speed to first send using the new library
- Quickstart completions, by persona
- Sample repository clones and deploys
- Templates created per account in week one
- Trial to production send conversion, compared with the pre launch baseline

Not: launch day traffic, impressions, or webinar registrations. Those are inputs.

---

*Frameworks by Vishal Naik. [Source playbook](https://sharebird.com/h/product-marketing/playbooks/how-docusign-increased-their-developer-marketing-conversion-rates-by-50).*
