My whole career has been the same job in different clothes: find the manual process holding a
system together, and replace it with something that scales. A securities firm, a hardware company's
sales team, and my own work.

What that means right now is agent tooling. I build compound engineering systems for coding
agents — the workflows, review passes, and context that have to survive between sessions — and
that is what everything else gets built with.

## Public work

**[antigravity-compound-engineering-plugin](https://github.com/salavender/antigravity-compound-engineering-plugin)**
— a non-official Antigravity IDE plugin that turns agent sessions into a persistent knowledge
system: what got fixed, what was learned, and what the next piece of work starts from. MIT licensed.

It is the only repository I publish. Most of what I build is proprietary to the work it serves —
multi-source market-data pipelines, agent context infrastructure, the plumbing behind a regulated
financial product. I am glad to talk about those: what they do, which constraints shaped them, what
broke, what it cost. The source is not mine to hand over.

## What the domain forces

Software that touches money has constraints most agent tooling never meets. They set the design.

- **In finance, an AI agent that is 95% right is 100% wrong.** So verification is not a stage at
  the end of a pipeline. It is the shape of the pipeline.
- **Money is not a float.** A ledger in binary floating point rounds away real value, and someone
  is left holding the difference. Decimal arithmetic, idempotent writes, and state you can replay
  from the log are the product, not hygiene.
- **A regulatory constraint is an engineering input.** When a product cannot be launched in its
  current form, the constraint belongs in the specification rather than in a discussion afterwards.
  Reshaping a product so the money flow stays auditable end to end is a design job, not a
  paperwork job.

## The other half

I work on retail lending products on the business side of a securities firm in Vietnam: the case
that justifies the product, its policy, the campaign, the UX, and getting the thing live with real
customers. One product I took from first draft to launch reached about VND 1 trillion with thousands
of customers within three weeks.

My dates have a two-year gap in them. From 2024 to early 2026 I served in the Vietnam People's Army,
combat engineers, clearing unexploded ordnance on the northern border. I came back to the same work.

## Reach

**[LinkedIn](https://www.linkedin.com/in/salavender-nguyen)** is the fastest way to reach me about
any of this. Hà Nội, Việt Nam — UTC+7.
