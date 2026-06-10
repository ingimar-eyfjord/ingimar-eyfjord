# Hey, I'm Ingimar

### Full-Stack Developer | Applied AI & Data Engineer | Copenhagen

I build production software end-to-end, and over the last 18 months I rebuilt how I work around AI agents: spec-and-plan-first, per-project agent libraries, custom Claude Code skills, MCP servers, and review gates that keep a human in the loop. My job is figuring out what the AI should do; the system I build around that decision is what ships.

The proof: I solo-built [Guide Connect](https://guideconnect.is), a B2B SaaS for the Icelandic travel market, shipping 1,400+ commits in five months with the entire financial layer in-house (invoicing, credit notes, VAT compliance, reconciliation, 7-year retention). The data discipline behind it comes from integrity work across 500+ regulated systems at Novo Nordisk.

## What I'm building right now

- **An AI allocation loop for a client's data platform.** Postgres warehouse (Medallion: raw, staging, reporting), five connected planning streams, and an AI that proposes staffing assignments. Every human override requires a structured rationale, so corrections accumulate as training data instead of vanishing. Operated through a custom MCP server, so a non-engineer runs it through Claude.
- **[Panel Todo](https://panel-todo.com)**, a VS Code extension with its own MCP server, live on the Marketplace. Task management your AI assistant can read and write.
- **Retrieval and evals**, the current learning track: a RAG-powered "ask me anything" for ingimar.dk.

## The repo to look at first

**[claude-code-agent-workflows](https://github.com/ingimar-eyfjord/claude-code-agent-workflows)**: my open-source AI orchestration framework. 10 specialized agents, 16 workflow skills, model tiering (Opus/Sonnet/Haiku by task), and an autonomous dev loop that picks tickets, implements, tests, and commits behind human review gates. It never pushes without approval. Battle-tested on a real SaaS, not a demo repo.

## How I work

- Spec first, plan second, code third. The agents do the typing, I do the deciding.
- AI proposes, humans approve. Every system I design keeps that order.
- If I do something twice, it becomes a skill. If an agent gets it wrong twice, that becomes a rule.
- Boring, auditable data layers underneath ambitious AI on top.

## Status

Open to full-time AI / product engineering roles in Copenhagen (available June 2026), employment or contract via my CVR. Fastest way to reach me: [ingimar@ingimar.dk](mailto:ingimar@ingimar.dk) | [ingimar.dk](https://www.ingimar.dk) | [LinkedIn](https://www.linkedin.com/in/ingimareyfjord)



[![Ingimar's GitHub stats](https://github-readme-stats.vercel.app/api?username=ingimar-eyfjord)](https://github.com/anuraghazra/github-readme-stats)
