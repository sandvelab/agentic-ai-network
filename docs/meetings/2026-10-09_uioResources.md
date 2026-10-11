# 9 October 2026 — National and UiO resources for agentic AI

[← Back to overview](../../README.md)

**Time and place:** Friday 9 October 2026, 14:00–15:20, Informatikksalen, 5th floor, Ole-Johan Dahls hus (IFI). Moved from 2 October because of the autumn break.

Theme: what UiO and national infrastructure already offer for agentic AI, and how far that gets you. One introduction, followed by discussion. Notes below are based on the slides.

## Lex Nederbragt — UiO resources for agentic AI

*How far can you get without a subscription to Claude Code?* · [Slides (PDF)](../slide%20decks/261009_Lex_TRUST_Agentic_AI_study_group_en.pdf)

- **Starting point.** Nederbragt (teaching professor, Dept. of Biosciences) set out to see what can be done *within UiO's framework*, since that makes it easier to bring the IT department, management and more colleagues on board.
- **Two layers.** Agentic AI is a language model plus a *harness* that governs how the model is used (Claude Code, Codex, Antigravity, OpenCode, Hermes agent and others). Harnesses have mostly targeted programmers but work well for knowledge work too.
- **Models available through UiO.** Three API routes: the **GPT UiO API** (OpenAI models plus open models such as Kimi, GLM, Qwen, Gemma, Mistral and the Norwegian Borealis and NorMistral, mostly hosted at NTNU or on Educloud); **Microsoft Foundry** (OpenAI, Anthropic and many other providers); and **Google Cloud Platform** (Gemini, some Claude models). Harnesses available at UiO include Codex, Antigravity and OpenCode, with Claude Code coming. The landscape changes quickly.
- **Connecting to UiO services.** Agents can talk to UiO services that have APIs, such as Nettskjema, Canvas, Panopto, Vortex, TP, WiseFlow and NVA. Examples: reading Nettskjema results, building a new form, creating Canvas content, messaging all students in a course. Workflows written as *skills* (markdown files) can be shared between staff, which helps scaling.
- **Sensitive data and compute.** Red data is possible with models from gpt.uio.no, or with local models. OpenCode runs on Fox (Educloud), for example to write and parallelise Slurm scripts or inspect disk usage. Models can also be run on Educloud (Fox), Sigma2 (Olivia) and NREC.
- **Costs.** The GPT UiO API gives a monthly token budget per model (5M–30M tokens) and never sends a bill. Microsoft Foundry and Google Cloud are charged to a UiO project account (Foundry invoices above NOK 500). Local models via e.g. Ollama are free beyond the hardware and can handle red data, but are often only good enough for simple, well-defined tasks.
- **His own setup.** ChatGPT/Codex with OpenAI models for complex tasks, data analysis and overviews; OpenCode with GPT UiO models (Kimi, GLM) for improving teaching material; Hermes agent for Canvas, Nettskjema and repetitive tasks; Antigravity for occasional testing. Examples included checking field data files and building a course overview.
- **Getting started.** [Agent School (Agent-skolen)](https://pages.github.uio.no/alexajo/agent-skolen), and the AI companies' support programmes for researchers.
- **Conclusion.** How far can you get without a Claude Code subscription? Far enough.
