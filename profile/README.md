<div align="center">
  <img src="https://raw.githubusercontent.com/Refine-Technologies-Inc/.github/main/profile/assets/refine-logo.png" alt="Refine.ink" width="100" />
  <h3>Refine.ink</h3>
  <p><strong>Deep review for technical documents.</strong></p>

  <a href="https://www.refine.ink">www.refine.ink</a>
</div>

---

### What We Build

Refine is a deep-review engine for technical documents. It uses an agentic pipeline of frontier AI models to read a draft end-to-end, track detailed arguments, and surface the kinds of substantive issues an expert reviewer would flag.

- **Expert-level depth** — Feedback comparable to a careful 4–6 hour expert read-through, delivered in minutes
- **Order of magnitude deeper** — Coverage far more thorough than frontier models, even with expert use
- **Built for complexity** — Especially strong on long, technical, or complex documents where precision and internal consistency matter
- **Multimodal** — Reviews figures, charts, and tables alongside the prose, not just the text

Our core users are researchers at leading universities, think tanks, and central banks — working in fields like medicine, economics, computer science, and law.

### Our Stack

**Backend** — Python, FastAPI, Azure Functions, Redis for orchestrating multi-stage agentic pipelines at scale

**Frontend** — TypeScript, TanStack Start, React

**Infrastructure** — Azure, Pulumi IaC, containerized deployments

**AI** — Custom routing and orchestration across frontier LLMs — OpenAI, Claude, Gemini, and others

---

### Security & Compliance

Zero data retention with LLM providers — your documents are never stored by the models processing them, and never used for training. SOC 2 and ISO 27001 audits in progress. See our [trust center](https://trust.refine.ink/).

---

### For Developers

Refine ships an MCP server and a REST API, so you can run deep reviews directly from your editor or wire them into your own pipelines.

**[Get started →](https://www.refine.ink/developers)** — setup, REST API reference, and MCP server config (Claude, Cursor, VS Code).

> The developer APIs are in Alpha; contracts may change without versioning.

---

<div align="center">
  <a href="https://www.refine.ink">Try Refine.ink →</a>
</div>
