# Veridical data science and agentic AI

[← Back to overview](../README.md)

## Why this belongs in the series

We want our agentic AI work to be **reproducible**, and we want it to **reflect reality in a stable way**. The first asks whether a result can be regenerated. The second asks whether the result would survive if we had made other reasonable choices along the way. Both become more pressing when much of an analysis is planned and executed by an agent, and both become more achievable.

## Veridical data science in brief

Veridical data science (VDS), developed by Bin Yu and colleagues, organises the trustworthiness of data-driven results around three principles, the **PCS framework**:

- **Predictability.** A result should connect to reality, typically by predicting well on data it was not fitted to.
- **Computability.** The analysis should be computationally sound and reproducible.
- **Stability.** Conclusions should hold up under reasonable perturbations of the data, the methods and the judgement calls made along the way. Instability under reasonable analytic choices is often the dominant, and least visible, threat to a conclusion.

The book *Veridical Data Science: The Practice of Responsible Data Analysis and Decision Making* (Yu & Barter, MIT Press) is freely available at [vdsbook.com](https://vdsbook.com).

## What changes with agentic AI

- **Reproducibility gets cheaper.** Much of what made rigorous reproducibility costly was human effort and forgetfulness: tracking how every result was produced, pinning software versions, recording random seeds, keeping intermediate results. An agent can be instructed to do all of this systematically, and to check that an analysis reruns from a clean slate.
- **Stability becomes testable at scale.** Exploring how a conclusion changes across alternative, equally reasonable analysis choices used to be prohibitively laborious. With an agent it becomes practical to vary those choices systematically and report how stable the result is.
- **New sources of instability appear.** The agent is itself a source of variation: different runs, models or phrasings of an instruction can lead to different analytic paths. An agent can also ignore an instruction it was given. Treating the agent's own choices as perturbations to be examined is part of doing veridical work with agents.
- **Provenance needs to cover the agent.** A result should be traceable not only to data and code but to the instructions and decisions that produced it.

## How this connects to the series

VDS will be a recurring thread in the meetings, not a separate track: how people make agent-driven analyses reproducible in practice, how they check that conclusions are stable, and where agentic workflows make trustworthy results easier or harder. The same questions are also being pursued in TRUST research on veridical and reproducible agentic AI.
