<div align="center">

<img src="./assets/hero-setup.jpg" width="620" alt="Paulo Rafael workspace" />

<br><br>

### Software · Data · Automation · AI Engineering

<p>
I build systems at the intersection of <b>software, data, automation and artificial intelligence</b>, with a strong focus on clarity, reliability, traceability and practical engineering.
</p>

<sub>Warm minimal workspace · focused tools · deliberate systems</sub>

</div>

---

### About me

**AI-native development · intelligent automation · software systems.**

My foundation is in IT and software. I use AI as an additional engineering layer — not as a replacement for fundamentals.

I am especially interested in building systems that are **small enough to understand, reliable enough to trust, and structured enough to evolve**.

---

### How I work

I organize work in short, goal-oriented cycles and prefer to develop systems through **small, verifiable increments**.

```mermaid
flowchart LR
    A[Understand] --> B[Build a small increment]
    B --> C[Validate with evidence]
    C --> D[Improve]
```

#### Software Engineering

My software workflow combines **Scrum, incremental DevOps, DevSecOps, thin slices and evidence-driven development**.

```mermaid
flowchart LR
    A[Understand] --> B[Design]
    B --> C[Build]
    C --> D[Test]
    D --> E[Observe]
    E --> F[Verify]
    F --> G[Version]
    G --> H[Improve]
```

<details>
<summary><b>Methodology</b></summary>

<br>

**Scrum**

```mermaid
flowchart LR
    A[Backlog] --> B[Sprint Goal]
    B --> C[Execution]
    C --> D[Review]
    D --> E[Retrospective]
```

**Incremental DevOps**

```mermaid
flowchart LR
    A[Understand] --> B[Implement]
    B --> C[Test]
    C --> D[Observe]
    D --> E[Correct]
    E --> F[Version]
    F --> G[Advance]
```

**DevSecOps**  
Security, trust boundaries and validation are considered from the beginning instead of being added after implementation.

**Thin Slices**  
Large systems are developed through small end-to-end increments that can already be executed, tested and evaluated.

**Evidence-Driven Development**  
A solution is accepted through evidence: tests, metrics, outputs, logs and observed behavior.

**Separation of Concerns**  
Input, validation, business logic, persistence and interfaces remain separated so each layer can evolve independently.

**Reproducibility & Logical Idempotency**  
The same valid input should reproduce the same logical behavior and results.

**Traceability**  
Important outputs should be traceable back to their inputs, transformations and versions.

**Fail-Safe / Fail-Closed**  
When something cannot be validated safely, preserve it, isolate it and make the failure visible instead of guessing.

**Pragmatic Architecture**  
Requirements determine architecture. Technology is introduced only when the problem justifies it.

</details>

<br>

#### AI Agents

I approach AI agents as **specialized systems**, not generic assistants. The goal is to create vertical agents with clear responsibilities, domain knowledge, controlled tools and measurable quality.

```mermaid
flowchart LR
    A[Vertical] --> B[Domain]
    B --> C[Manager]
    C --> D[Specialists]
    D --> E[Skills]
    E --> F[Tools]
    F --> G[Evals]
    G --> H[Governance]
```

<details>
<summary><b>Methodology</b></summary>

<br>

**Vertical AI Agents**  
Start from a specific domain, workflow or professional function instead of starting from the model.

**Domain-First Design**

```mermaid
flowchart LR
    A[Domain] --> B[Problems]
    B --> C[Responsibilities]
    C --> D[Workflows]
    D --> E[Knowledge]
    E --> F[Agents]
    F --> G[Tools]
```

**Agents by Function**  
Agents are defined by responsibility — such as Planner, Researcher, Evaluator or Visual Director — rather than by the application they use.

**Factory over Assistant**

```mermaid
flowchart LR
    A[Human] --> B[Manager]
    B --> C[Specialized Agents]
    C --> D[Skills]
    D --> E[Tools]
    E --> F[Artifacts]
    F --> G[Evaluation]
```

**Manager + Specialists**  
A manager interprets, decomposes, delegates and integrates work while specialized agents execute bounded responsibilities.

**Skills Architecture**  
Reusable capabilities are documented, tested and versioned independently from the agent using them.

**Human-in-the-loop AI**

```mermaid
flowchart LR
    A[Problem] --> B[AI Proposal]
    B --> C[Human Review]
    C --> D[Execution]
    D --> E[Evidence]
    E --> F[Adjustment]
```

AI contributes to the work, but does not become the source of truth.

**Evals & QA**  
Agent behavior is evaluated for correctness, completeness, tool selection, hallucination, policy adherence and output quality.

**Governance**  
Permissions, policies, logs, approvals, auditing and versioning control how the system evolves.

**Controlled Release**

```mermaid
flowchart LR
    A[Sandbox] --> B[Eval]
    B --> C[Human Approval]
    C --> D[Production]
    D --> E[Monitoring]
```

</details>

<br>

#### Automation

I prefer to understand and validate a process manually before automating it. Automation should remove friction from a process that already makes sense — not hide a process that is still unclear.

```mermaid
flowchart LR
    A[Manual] --> B[Understand]
    B --> C[Map]
    C --> D[Standardize]
    D --> E[Automate]
    E --> F[Observe]
    F --> G[Improve]
```

<details>
<summary><b>Methodology</b></summary>

<br>

**Manual Before Automation**  
Execute the process manually first, understand its decisions and automate only the stable parts.

**Process Mapping**

```mermaid
flowchart LR
    A[Trigger] --> B[Input]
    B --> C[Rules]
    C --> D[Decision]
    D --> E[Action]
    E --> F[Output]
    F --> G[Failure Path]
```

**Incremental Automation**  
Automation grows one validated step at a time instead of becoming a large opaque workflow.

**Event-Driven Workflows**  
APIs, webhooks, files, schedules, databases and user actions can trigger repeatable flows.

**Idempotency**  
Reprocessing the same valid event should not create inconsistent state.

**Retry & Recovery**  
Temporary failures should have controlled retries and clear escalation paths.

**Rollback**  
When a workflow changes state, recovery to a previous safe state should be considered.

**Human Fallback**  
Ambiguous or low-confidence situations can return to human review instead of forcing an automated decision.

**Observability**  
A workflow should make execution, inputs, outputs, errors, retries and duration visible.

**Evidence-Driven Automation**  
Automation is evaluated by measurable improvement, not simply by the fact that it runs automatically.

</details>

<br>

#### Shared principles

<div align="center">

`Scrum` · `Systems Thinking` · `Evidence over Assumption` · `Security by Design` · `Traceability` · `Human Review` · `Incremental Improvement`

<br><br>

<sub>Technology should support the process — not become the process.</sub>

</div>

---

### My daily driver

<div align="center">

<img src="https://skillicons.dev/icons?i=windows,vscode,github,powershell,docker&theme=dark" height="42" alt="Daily driver" />
&nbsp;
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/codex.png">
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/codex.png" width="42" height="42" alt="Codex" title="Codex">
</picture>

<br/><br/>

Windows · VS Code · GitHub · PowerShell · Docker · Codex

</div>

---

### Core Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,ts,nodejs,react,astro,tailwind,git&theme=dark" height="42" alt="Core stack" />

<br/><br/>

Python · TypeScript · Node.js · React · Astro · Tailwind CSS · Git

</div>

---

### Tools & Technologies

<div align="center">

<h4>development</h4>

<img src="https://skillicons.dev/icons?i=js,html,css,linux,npm,vite&theme=dark" height="42" alt="Development tools" />

<br/><br/>

JavaScript · HTML5 · CSS · Linux · npm · Vite

<br/><br/>

<h4>data & backend</h4>

<img src="https://cdn.simpleicons.org/postgresql/4169E1" width="40" height="40" alt="PostgreSQL" title="PostgreSQL" />
&nbsp;
<img src="https://api.iconify.design/mdi:database.svg?color=%238B949E" width="40" height="40" alt="SQL" title="SQL" />
&nbsp;
<img src="https://cdn.simpleicons.org/supabase/3FCF8E" width="40" height="40" alt="Supabase" title="Supabase" />
&nbsp;
<img src="https://cdn.simpleicons.org/firebase/FFCA28" width="40" height="40" alt="Firebase" title="Firebase" />
&nbsp;
<img src="https://cdn.simpleicons.org/duckdb/FFF000" width="40" height="40" alt="DuckDB" title="DuckDB" />
&nbsp;
<img src="https://cdn.simpleicons.org/pandas/150458" width="40" height="40" alt="pandas" title="pandas" />
&nbsp;
<img src="https://cdn.simpleicons.org/apacheparquet/50ABF1" width="40" height="40" alt="Apache Parquet" title="Apache Parquet" />

<br/><br/>

PostgreSQL · SQL · Supabase · Firebase · DuckDB · pandas · Parquet

<br/><br/>

<h4>ai & agents</h4>

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/openai.png">
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/openai.png" width="40" height="40" alt="ChatGPT" title="ChatGPT">
</picture>
&nbsp;
<img src="https://cdn.simpleicons.org/googlegemini/8E75B2" width="40" height="40" alt="Gemini" title="Gemini" />
&nbsp;
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/grok.png">
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/grok.png" width="40" height="40" alt="Grok" title="Grok">
</picture>
&nbsp;
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/dark/codex.png">
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-png/light/codex.png" width="40" height="40" alt="Codex" title="Codex">
</picture>
&nbsp;
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-svg/icons/claudecode-color.svg" width="40" height="40" alt="Claude Code" title="Claude Code" />
&nbsp;
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-svg/icons/geminicli-color.svg" width="40" height="40" alt="Gemini CLI" title="Gemini CLI" />

<br/><br/>

ChatGPT · Gemini · Grok · Codex · Claude Code · Gemini CLI

<br/><br/>

<h4>automation & orchestration</h4>

<img src="https://cdn.simpleicons.org/n8n/EA4B71" width="40" height="40" alt="n8n" title="n8n" />
&nbsp;
<img src="https://api.iconify.design/mdi:api.svg?color=%238B949E" width="40" height="40" alt="APIs" title="APIs" />
&nbsp;
<img src="https://api.iconify.design/mdi:webhook.svg?color=%238B949E" width="40" height="40" alt="Webhooks" title="Webhooks" />
&nbsp;
<img src="https://api.iconify.design/mdi:graph-outline.svg?color=%238B949E" width="40" height="40" alt="AI Workflows" title="AI Workflows" />

<br/><br/>

n8n · APIs · Webhooks · AI Workflows

<br/><br/>

<h4>thinking, design & knowledge</h4>

<img src="https://skillicons.dev/icons?i=figma&theme=dark" width="40" height="40" alt="Figma" title="Figma" />
&nbsp;
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/canva/canva-original.svg" width="40" height="40" alt="Canva" title="Canva" />
&nbsp;
<img src="https://cdn.simpleicons.org/pinterest/BD081C" width="40" height="40" alt="Pinterest" title="Pinterest" />
&nbsp;
<img src="https://cdn.simpleicons.org/obsidian/7C3AED" width="40" height="40" alt="Obsidian" title="Obsidian" />
&nbsp;
<img src="https://cdn.simpleicons.org/affine/FFFFFF" width="40" height="40" alt="AFFiNE" title="AFFiNE" />
&nbsp;
<img src="https://cdn.simpleicons.org/notion/FFFFFF" width="40" height="40" alt="Notion" title="Notion" />
&nbsp;
<img src="https://cdn.simpleicons.org/googledrive/4285F4" width="40" height="40" alt="Google Drive" title="Google Drive" />
&nbsp;
<img src="https://cdn.simpleicons.org/miro/FFD02F" width="40" height="40" alt="Miro" title="Miro" />

<br/><br/>

Figma · Canva · Pinterest · Obsidian · AFFiNE · Notion · Google Drive · Miro

</div>

---

### Direction

<div align="center">

I am strengthening the same technical foundation while moving deeper into **AI engineering, vertical agents, agentic development and intelligent automation**.

</div>

```mermaid
flowchart LR
    A[IT Foundation] --> B[Software Engineering]
    B --> C[Data]
    C --> D[Automation]
    D --> E[AI Engineering]
    E --> F[Agentic Systems]
```

<div align="center">

<sub>
The objective is not to collect tools — it is to connect them into systems that are easier to understand, verify and improve.
</sub>

</div>

---

### Analytics

<div align="center">

<img width="58%" src="https://streak-stats.demolab.com?user=eurafff&hide_border=true&background=1A120E&ring=D79A5B&fire=F0D2B3&currStreakLabel=D79A5B&sideLabels=C9B59F&currStreakNum=FFF7ED&sideNums=FFF7ED&dates=9C8876" alt="GitHub streak" />

<br/><br/>

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=eurafff&theme=github_dark" alt="GitHub stats" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=eurafff&theme=github_dark" alt="Top languages" />

<br/><br/>

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=eurafff&theme=github_dark" alt="GitHub profile details" />

</div>

---

<div align="center">

<a href="https://x.com/raffmehmc1">X · @raffmehmc1</a>

<br><br>

<sub>Warm minimal workspace · focused tools · clear systems</sub>

</div>