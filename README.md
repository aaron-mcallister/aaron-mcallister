# Aaron McAllister

**Field CTO | AI Security & Zero Trust**

Twenty-plus years across DoD, ISP, higher education, and enterprise tech have taught me that the most interesting problems sit at the intersection of security, performance, and emerging technology. Right now, that intersection is AI security.

I'm particularly focused on how large language models and AI agents are reshaping enterprise risk: securing AI interactions, governing MCP-connected tools, detecting threats in real-time AI traffic, and building policy frameworks for agentic workflows. As AI moves from experimentation to production, the security and governance layer is where the hardest problems live.

CISSP · GICSP · 8+ years at Palo Alto Networks · 4+ years at Cloudflare

## Projects

**[cf-user-activity-report](https://github.com/aaron-mcallister/cf-user-activity-report)**
A per-user activity report for Cloudflare One that joins Gateway, Access, and WAF data by identity, the kind of cross-dataset view Log Explorer can't produce today. Runs on the Workers free plan. Built to fail closed: it verifies the signed Access token instead of trusting headers, ships strict security headers and a CSP, and has a regression test suite and CI.

## How I build in public

- Fail closed by default. Never trust a header the client can send.
- Least-privilege CI, SHA-pinned actions, Dependabot, secret scanning with push protection.
- Protected `main` (pull requests and required checks), plus private vulnerability reporting via `SECURITY.md`.
- Public demos use synthetic data only.

## Connect

[LinkedIn](https://www.linkedin.com/in/aaron-mcallister-mba/)

<sub>Personal projects. Code and opinions here are my own and not those of my employer.</sub>
