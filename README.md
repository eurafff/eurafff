<div align="center">

### Software · Data · Automation · AI Engineering

<p>
I build systems at the intersection of <b>software, data, automation and artificial intelligence</b>, with a strong focus on clarity, reliability, traceability and practical engineering.
</p>

<!-- typing-principles:start -->
<img
  src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=2800&pause=1200&color=C9B59F&center=true&vCenter=true&width=700&lines=small+systems+%E2%86%92+clear+behavior+%E2%86%92+measurable+evidence;building+for+clarity+%C2%B7+reliability+%C2%B7+traceability;engineering+before+complexity"
  alt="Engineering principles"
/>
<!-- typing-principles:end -->

<br>

<sub>Warm minimal workspace · focused tools · deliberate systems</sub>

</div>

---

### About me

**AI-native development · intelligent automation · software systems.**

My background is in IT and software, and lately I have been spending a lot of time learning how AI can become a useful part of the engineering process — without skipping the fundamentals.

I enjoy learning by building, testing ideas, breaking things, fixing them and slowly understanding why something works.

I do not expect to have everything figured out. A big part of what I build is also a way for me to explore, improve my thinking and discover better ways of doing things.

I am especially interested in systems that are **simple enough to understand, reliable enough to trust and structured enough to keep evolving**.

---

### How I work

I like working in small, goal-oriented steps.

Usually I start with something simple, make it work, test it, observe what happens and improve it from there. Small, verifiable increments make it easier for me to understand what changed and why.

I try to keep decisions explicit and systems understandable, while leaving room to experiment and change direction when the evidence points somewhere better.

For me, good engineering is less about having the perfect answer from the beginning and more about **learning, validating assumptions and improving things one step at a time**.

<div align="center">
<img src="./assets/diagrams/how-i-work.svg" width="100%" alt="How I work sequential diagram" />
</div>

#### Software Engineering

My current software workflow borrows ideas from **Scrum, incremental DevOps, DevSecOps, thin slices and evidence-driven development**.

I do not treat them as rigid rules. They are tools that help me organize the work, reduce uncertainty and keep changes small enough to understand and verify.

What matters most to me is being able to see what changed, why it changed and whether it actually improved the system.

<div align="center">
<img src="./assets/diagrams/software-engineering.svg" width="100%" alt="Software engineering sequential diagram" />
</div>

<details>
<summary><b>Methodology</b></summary>

<br>

**Scrum**  
I use a prioritized backlog, clear sprint goals, reviews and retrospectives to keep the work focused while still leaving room to adjust as I learn.

**Incremental DevOps**  
I prefer implementing changes in small scopes, testing them locally, observing the result and correcting what needs to change before moving forward.

**DevSecOps**  
I try to think about security, trust boundaries and validation early instead of treating them as something to add only after the system is already built.

**Thin Slices**  
Breaking larger systems into small end-to-end pieces helps me learn from working software sooner and keeps complexity manageable.

**Evidence-Driven Development**  
I prefer validating ideas through things I can observe — tests, metrics, outputs, logs and actual system behavior.

**Separation of Concerns**  
Keeping input, validation, business logic, persistence and interfaces separated makes the system easier for me to reason about and evolve.

**Reproducibility & Logical Idempotency**  
When possible, I want the same valid input to reproduce the same logical behavior and results.

**Traceability**  
I like important outputs to have a clear path back to their inputs, transformations and versions.

**Fail-Safe / Fail-Closed**  
When something cannot be validated safely, I prefer making the uncertainty visible rather than silently guessing.

**Pragmatic Architecture**  
I try to let the requirements guide the architecture and introduce new technology only when the problem gives me a good reason to do so.

</details>

<br>

#### AI Agents

AI agents are one of the areas I am exploring the most right now.

I tend to think about them as **specialized systems rather than generic assistants**, especially when they are part of a real workflow.

My current approach is to start with the domain and the problem first, then think about responsibilities, knowledge, tools, evaluation and coordination.

This is still an evolving area for me, and a lot of the fun is experimenting with different approaches, seeing where they fail and learning what works better in practice.

<div align="center">
<img src="./assets/diagrams/ai-agents.svg" width="100%" alt="AI agents sequential diagram" />
</div>

<details>
<summary><b>Methodology</b></summary>

<br>

**Vertical AI Agents**  
I usually find it more useful to start with a specific domain, workflow or professional responsibility instead of starting with the model itself.

**Domain-First Design**  
I try to understand the problem, responsibilities, workflows and knowledge before deciding which agents or tools belong in the system.

**Agents by Function**  
I like defining agents around bounded responsibilities — such as Planner, Researcher, Evaluator or Visual Director — rather than around the applications they use.

**Factory over Assistant**  
One mental model I am exploring is treating an agentic system more like a small coordinated production environment than a single all-purpose assistant.

The idea is that a manager can interpret the objective and delegate smaller responsibilities to specialized agents, skills and tools while keeping the final work observable and reviewable.

**Manager + Specialists**  
I use this pattern to separate coordination from execution: one component helps decompose and integrate the work while specialists focus on narrower responsibilities.

**Skills Architecture**  
Reusable capabilities make more sense to me when they can be documented, tested and improved independently from any single agent.

**Human-in-the-loop AI**  
I prefer AI proposals to remain part of a reviewable process where a person can inspect the context, compare the result with real evidence and decide what should happen next.

**Evals & QA**  
I am learning to treat evaluation as part of the system itself, looking at correctness, completeness, tool selection, hallucination, policy adherence and output quality.

**Governance**  
As agentic systems become more capable, I think permissions, policies, logs, approvals and versioning become increasingly important parts of the engineering problem.

**Controlled Release**  
For new capabilities, I prefer starting small, testing them in a controlled environment and expanding only after there is enough evidence that the behavior is useful and predictable.

</details>

<br>

#### Automation

I like understanding a process before trying to automate it.

Sometimes the best first step is simply doing the work manually, noticing where the friction is and learning which parts are actually stable enough to automate.

From there, I prefer growing automation gradually, keeping failures visible and leaving room for human review when something is ambiguous.

The goal for me is not to automate everything — it is to make useful processes **easier to run, understand and improve**.

<div align="center">
<img src="./assets/diagrams/automation.svg" width="100%" alt="Automation sequential diagram" />
</div>

<details>
<summary><b>Methodology</b></summary>

<br>

**Manual Before Automation**  
I like executing a process manually first so I can understand its decisions before deciding which parts are worth automating.

**Process Mapping**  
Writing down triggers, inputs, rules, decisions, actions, outputs and failure paths helps me see the process more clearly before adding more machinery around it.

**Incremental Automation**  
I prefer automation that grows one validated step at a time instead of becoming a large workflow that is difficult to inspect.

**Event-Driven Workflows**  
APIs, webhooks, files, schedules, databases and user actions are useful building blocks when a process benefits from repeatable event-driven execution.

**Idempotency**  
When possible, I design repeated processing so that receiving the same valid event again does not leave the system in an inconsistent state.

**Retry & Recovery**  
Temporary failures are easier to work with when retry behavior and escalation paths are explicit.

**Rollback**  
When automation changes state, I try to think about what recovery would look like if something goes wrong.

**Human Fallback**  
For ambiguous or low-confidence situations, I prefer returning the decision to a person instead of forcing the automation to pretend it knows the answer.

**Observability**  
I want workflows to make their execution understandable: what came in, what happened, what came out, where something failed and how long it took.

**Evidence-Driven Automation**  
For me, automation is useful when it produces a measurable improvement — not simply because a previously manual step became automatic.

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
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-svg/icons/claudecode-color.svg" width="40" height="40" alt="Claude Code" title="Claude Code" />
&nbsp;
<img src="https://raw.githubusercontent.com/lobehub/lobe-icons/refs/heads/master/packages/static-svg/icons/geminicli-color.svg" width="40" height="40" alt="Gemini CLI" title="Gemini CLI" />

<br/><br/>

ChatGPT · Gemini · Grok · Claude Code · Gemini CLI

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

I am continuing to strengthen my software foundation while learning more about **AI engineering, vertical agents, agentic development and intelligent automation**.

There is still a lot I want to understand, and that is a big part of what keeps this interesting for me.

<br><br>

<img src="./assets/diagrams/direction.svg" width="100%" alt="Technical direction sequential diagram" />

<br>

<sub>
I am not trying to collect every tool. I am trying to understand how the pieces fit together — and become a little better at building useful systems along the way.
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

<br/><br/>

<!-- contribution-snake:start -->
<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/eurafff/eurafff/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/eurafff/eurafff/output/github-contribution-grid-snake.svg"
  />
  <img
    width="100%"
    alt="GitHub contribution animation"
    src="https://raw.githubusercontent.com/eurafff/eurafff/output/github-contribution-grid-snake.svg"
  />
</picture>
<!-- contribution-snake:end -->

</div>

---

<div align="center">

<a href="https://x.com/raffmehmc1">X · @raffmehmc1</a>

<br><br>

<sub>Warm minimal workspace · focused tools · clear systems</sub>

</div>
