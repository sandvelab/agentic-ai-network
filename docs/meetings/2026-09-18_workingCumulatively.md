# 18 September 2026 — Working cumulatively with agentic AI

[← Back to overview](../../README.md)

**Time and place:** Friday 18 September 2026, 14:00–15:20, Informatikksalen, 5th floor, Ole-Johan Dahls hus (IFI). Presentations streamed on Zoom.

Theme: how to work *cumulatively* with agentic AI, so that what you build up over time makes the agent increasingly useful for your research. Two introductions, followed by discussion.

## Bjørn Høyland — AI agents in a research pipeline

*Strategic roll-call requests, a data resource, and six months with Claude Code.*

- **The research problem.** In the European Parliament, a roll-call vote is recorded only if a party group or 40 MEPs request it, so the recorded-vote sample is strategically selected. Høyland models the requests as a "best-shot" game solved as a quantal response equilibrium, with a likelihood that mixes two equilibria and is estimated by differential-evolution MCMC.
- **Two deliverables.** The `rollcalls` R/C++ package implementing the estimator, with a Monte Carlo study and a replication showing that earlier findings weaken or vanish once strategy is modelled. The **StREP** data resource, which covers votes from the Common Assembly in 1952 to today's EP, vote requests, speeches, committee reports and procedures, with every observation traceable to document, page and line.
- **Before and after.** Five years of commit history across four repositories, split at the first Claude Code prompt in March 2026. In six and a half months the estimator repository went from 139 to 368 commits and roughly tenfold in R code. Test code, design notes and documentation grew from almost nothing to thousands of lines. Work previously done by a research assistant on the data resource continued through the agent.

## Geir Kjetil Sandve — Using agentic AI to cumulatively improve what I make with agentic AI

*Six months of one person's substrate.*

- **The question has changed shape.** No longer "can AI do this?" but "is there a process I could invent that would make AI useful here?"
- **Every task leaves something the next task uses.** Converters, indexes over past material, a style guide, and so on, so the same kind of task needs less of him each time.
- **Eight things accumulate, in three groups.** *Material* (collect, index, recall), *self* (distil what he knows and believes, and store it as standing instruction and skills) and *work* (overviews, established work processes, tuning for specific products). Verification runs through all of them.
- **Aim at the periphery.** Most of what accumulates is peripheral work, and that is the point: researchers lack time more than ideas.
- **Costs and limits.** Licences on the order of NOK 30,000 a year and a large body of standing instructions that itself needs maintenance, all built while the work continued. The approach is personal, task-shaped and human-in-the-loop, and it does not cover autonomy, team use or programming-heavy data science.
- **Advice.** Judge the substrate, not the output. Write down what you realise where you will meet it again. Start with one small piece.
