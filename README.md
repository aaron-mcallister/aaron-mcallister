# Aaron McAllister

**Field CTO | AI Security & Zero Trust**

Twenty-plus years across DoD, ISP, higher education, and enterprise tech have taught me that the most interesting problems sit at the intersection of security, performance, and emerging technology. Right now, that intersection is AI security.

I'm particularly focused on how large language models and AI agents are reshaping enterprise risk: securing AI interactions, governing MCP-connected tools, and building policy frameworks for agentic workflows. As AI moves from experimentation to production, the security and governance layer is where the hardest problems live.

CISSP · GICSP · 8+ years at Palo Alto Networks · 4+ years at Cloudflare

## Projects

**[agent-security-evals](https://github.com/aaron-mcallister/agent-security-evals)**
Deterministic security evals for tool-using LLM agents: indirect prompt injection, MCP-style tool poisoning, excessive agency, and secret handling, mapped to the OWASP LLM Top 10. Runs in seconds against scripted agents, compares defenses (spotlighting, a policy gate) side by side, and can be pointed at a real model.

**[claude-code-governance](https://github.com/aaron-mcallister/claude-code-governance)**
A reference architecture for governing Claude Code in an enterprise: a managed-settings policy, a fail-closed policy hook, and a linter, with tests and CI that check the rendered policy against the real `claude doctor`. Documents its own known gaps instead of overclaiming.

**[hardened-mcp-server](https://github.com/aaron-mcallister/hardened-mcp-server)**
A small MCP server where every security control is a tested behavior mapped to the MCP authorization spec: OAuth resource-server auth, per-tool scopes with step-up, team isolation, and hardened output against prompt injection. A mutation check breaks each control and requires the tests to notice.

## How I build in public

- Fail closed by default. Never trust a header the client can send.
- Least-privilege CI, SHA-pinned actions, Dependabot, secret scanning with push protection.
- Protected `main` (pull requests and required checks), plus private vulnerability reporting via `SECURITY.md`.
- Public demos use synthetic data only.
- Every project says what it did not test (see each repo's `docs/VALIDATION.md` or results limits).
- AI-assisted, human-owned. I build with Claude as a pair programmer, and most commits it helped write carry a `Co-Authored-By: Claude` trailer. I review, test and take responsibility for everything that ships.

## Connect

[LinkedIn](https://www.linkedin.com/in/aaron-mcallister-mba/)

<sub>Personal projects. Code and opinions here are my own and not those of my employer.</sub>
