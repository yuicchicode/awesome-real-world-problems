# Sales and marketing do not see the same lead and opportunity numbers

## Problem summary
Sales and marketing often operate with different lead and opportunity numbers, even when they are supposed to be talking about the same funnel. This creates mistrust, internal friction, poor funnel visibility, and weaker decisions about campaign investment and sales execution.

## Real-world report
One of the most frustrating problems is when marketing and sales are looking at different numbers and acting as if they are talking about the same reality. Marketing reports a certain number of captured leads, conversions, and campaign results, while sales sees fewer valid contacts, fewer real opportunities, or a completely different volume inside the CRM.

That creates a constant sense of misalignment. It feels like each team is describing a different version of the business.

In practice, marketing usually counts leads based on what entered through forms, campaigns, landing pages, or automation. Sales, on the other hand, looks at what actually arrived in the service flow, was validated, was contacted, and had real potential to become revenue. When definitions are unclear and systems are not well integrated, one side starts believing it is delivering strong results while the other feels it is receiving much less than expected.

This quickly turns into conflict. Marketing feels it is generating enough volume and that sales is not making proper use of the leads. Sales feels that many of those contacts are duplicated, incomplete, low-quality, or not even reaching the operation correctly. Instead of improving the funnel together, the teams start arguing about who is right.

## Why this is difficult
The difficulty is not only technical. It is also definitional and operational.

A lead can be counted at different moments depending on the system and the team: when it is captured, when it is validated, when it is assigned, when it is contacted, or when it becomes a qualified opportunity. If those definitions are not explicit and the underlying data is not aligned, each team ends up creating its own version of reality.

The funnel then becomes hard to trust because the counting logic is inconsistent across tools, reports, and processes.

## Why it matters
This affects much more than reporting. It damages trust between teams, weakens funnel management, and makes performance analysis harder. It becomes difficult to know how many leads truly entered, how many became opportunities, where drop-off happened, and which campaigns actually produced commercial impact.

It also hurts decision-making. Marketing may continue investing in channels that seem strong by volume, while sales sees little business value. At the same time, sales may stop trusting inbound demand and treat leads with less urgency, which makes the outcome even worse.

Without one shared truth, both teams optimize based on incomplete interpretations.

## Project opportunity
This is a very strong project problem because it combines data consistency, reporting logic, business definitions, funnel stage modeling, and cross-team trust.

A solution here could help organizations create shared definitions, align counting rules, reconcile lead and opportunity metrics, and build transparency between acquisition and revenue teams.

It is also a great portfolio problem because it mixes data modeling, analytics, workflow design, business logic, and stakeholder alignment in a very realistic way.

## Technical requirements
- Support a shared funnel model across marketing and sales
- Define and store clear stage transitions such as captured lead, validated lead, qualified lead, opportunity, lost, and won
- Allow configurable counting rules so teams can agree on what each number means
- Reconcile lead volume across multiple sources and internal systems
- Keep traceability of when and why a record changed stage
- Preserve ownership history, qualification status, and outcome notes
- Provide separate but connected views for marketing and sales
- Support reporting by campaign, source, stage, owner, and time period
- Surface discrepancies between raw captured leads and commercially validated leads
- Support auditability of funnel changes and counting logic
- Handle duplicate records and inconsistent stage mapping
- Allow teams to compare top-of-funnel and bottom-of-funnel numbers from the same data foundation

## Suggested MVP
- Shared funnel stage model
- Unified lead and opportunity dashboard
- Stage history timeline
- Difference view between captured leads and qualified opportunities
- Reporting by source and campaign
- Definition layer for funnel metrics

## Possible extensions
- SLA tracking between marketing and sales
- Qualification score or quality indicators
- Forecasting based on funnel conversion
- Alerts for stage mismatch or missing assignment
- CRM and ad platform integrations
- Team alignment reports and confidence metrics