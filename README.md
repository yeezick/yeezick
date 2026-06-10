# Erick Manrique

<div align="center">
  <img src="https://raw.githubusercontent.com/yeezick/iNetwork/main/src/images/erick-cool.gif" alt="Erick's gif" width="100" height="100" />
  <div><sub>Thank you <a href="https://www.linkedin.com/in/zulays/" target="_blank">Zulay</a> for my awesome gif!</sub></div>
</div>

**Product and engineering.** VP of Product at JPMorgan Chase; self-taught engineer, no CS degree. Background spans full-stack development, DevOps, and product ownership of an enterprise API platform. Current focus: agentic AI and developer-automation systems.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
&nbsp;
![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![RAG / Evals](https://img.shields.io/badge/RAG_·_Evals-555555?style=flat-square)
&nbsp;
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## Selected work

<table>
<tr>
<td>

### Ambito &nbsp;<sub>backend built · pre-launch</sub>

A persistent context layer for enterprises. It captures and structures the knowledge an organization generates — meetings, email, calendar, chat — and serves it to two consumers: people get an ambient dashboard that surfaces stalling projects and dropped commitments before they're asked, and AI agents get a permission-aware MCP server so they stop guessing on company-specific questions. The bet is additive rather than competitive — frontier models supply the intelligence; Ambito supplies the organizational context they reason against.

Backend is built and tested (ingest → classify → extract → escalate → persist, 55 tests; FastAPI; Postgres/pgvector); the marketing site is live at [ambito.ai](https://ambito.ai). Capstone of the Maven AI PM certification; selected for the program's "Featured Five." No customers or revenue yet.

`FastAPI · Postgres/pgvector · Claude · MCP`

</td>
</tr>
</table>

<table>
<tr>
<td>

### OneLook &nbsp;<sub>private · pre-launch</sub>

A native iOS app (Swift/SwiftUI) that unifies calendar, tasks, and habits into one daily view, built solo through an AI-native workflow. Two pieces of supporting infrastructure built inside the project:

- **Orchestrator** — a small MCP server that routes build tasks between Cowork, the Claude Agent SDK, and a cursor-agent, so the hand-off between planning, backend, and Swift work isn't manual copy-paste. &nbsp;`TypeScript · MCP`
- **Feedback pipeline** — a Supabase edge function that embeds incoming feedback (pgvector), clusters near-duplicates, classifies severity and screen with Claude, and emails a digest. Validated end-to-end. &nbsp;`Supabase/Deno · pgvector · Claude`

</td>
</tr>
</table>

<table>
<tr>
<td width="33%" valign="top">

**[StudyBuddy](https://github.com/yeezick/StudyBuddy)** <sub>· public</sub>

Slack-native spaced-repetition tutor. SM-2 scheduling, confidence-rated recall, and Claude-generated quizzes filtered against a fixed concept set to reject hallucinated items.

`Node.js · Claude API · BullMQ`

</td>
<td width="33%" valign="top">

**career-ops fleet** <sub>· working</sub>

Two-agent job-application pipeline: a fact-constrained drafter and an adversarial verifier that red-teams every claim against a deny-list. Submission stays human.

`Node.js · Claude Code subagents`

</td>
<td width="33%" valign="top">

**Bootcampr** <sub>· closed Oct 2025</sub>

Platform pairing bootcamp graduates into cross-functional product teams over one-week sprints. Built-in Kanban, real-time chat, calendar integration.

`React/TS · MERN · webhooks`

</td>
</tr>
</table>

---

## Technical PM · API & microservices (JPMorgan)

![System of record](https://img.shields.io/badge/System_of_record-10%2B_apps-1f6feb?style=flat-square)
![Product setup](https://img.shields.io/badge/Product_setup-~4h_to_under_1h-2ea043?style=flat-square)

- Owns the roadmap for an API-orchestration platform that is the system of record for product onboarding; a single enrichment layer consolidates reference data from several downstream systems and drove the setup-time reduction above.
- Led the eBAM lifecycle migration to the **ISO 20022 ACMT** standard — manual PDF treasury workflows replaced by automated, bank-agnostic request processing.

---

## Experience

| Role | Company | |
|---|---|---|
| VP, Product Management | JPMorgan Chase | 2025 – present |
| Product Associate → Sr. Product Associate | JPMorgan Chase | 2023 – 2025 |
| Associate Software Engineer | JPMorgan Chase | 2022 – 2023 |
| Founder | Bootcampr | 2022 – 2025 |
| DevOps Engineer | MarketAxess | 2022 |
| Software Engineering Consultant | Lido | 2021 – 2022 |
| Instructional Associate, Software Engineering | General Assembly | 2021 – 2022 |
| Software Engineering Immersive (graduate) | General Assembly | 2021 |

---

## Writing

| Post | What it's about | |
|---|---|---|
| **Establishing a real git workflow for agentic development** | Moving from one-agent-straight-to-main to a proper branch-and-review flow for agent-built code. | [Read](https://www.linkedin.com/posts/erick-manrique_ambito-agentic-development-pdf-activity-7467611480960675840-KVoN) |
| **Building Ambito — the "AI context brain" as a category** | The thesis behind Ambito: why a company's unified context layer becomes its own product category. | [Read](https://www.linkedin.com/feed/update/urn:li:activity:7466175393260269569/) |
| **Why spec-driven development (SDD) clicked for me** | What spec-driven development is, and why it maps to how I was already building with agents. | [Read](https://www.linkedin.com/posts/erick-manrique_sdd-spec-driven-development-was-recently-activity-7455373757319380992-tSlU) |
| **Removing myself from the AI hand-off (the self-closing build loop)** | Cutting the manual copy-paste routing between Cursor and Claude Code out of my build loop. | [Read](https://www.linkedin.com/feed/update/urn:li:activity:7451978062612574208/) |
| **Closing Collabify after three years — an accountable exit** | Shutting down a three-year startup, with accountability to the people who built it. | [Read](https://www.linkedin.com/feed/update/urn:li:activity:7383023472912007168/) |

---

[Portfolio](https://erickmanrique.com) · [LinkedIn](https://linkedin.com/in/erick-manrique) · erickmanriqpro@gmail.com
