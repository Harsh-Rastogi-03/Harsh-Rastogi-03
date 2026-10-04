<div align="center">

<img src="assets/hero.svg" alt="Harsh Rastogi, AI Product Engineer" width="100%">

<br><br>

<a href="https://linkedin.com/in/harsh2003"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=10b981"/></a>&nbsp;
<a href="mailto:harshrastogi0603@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=10b981"/></a>&nbsp;
<a href="https://www.harshrastogi.tech"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=safari&logoColor=10b981"/></a>&nbsp;
<a href="https://github.com/Harsh-Rastogi-03/carcode"><img src="https://img.shields.io/badge/carcode-0d1117?style=for-the-badge&logo=github&logoColor=10b981"/></a>

</div>

<br>

I'm an **AI Product Engineer** who builds generative-AI products and autonomous agents, and takes them from idea to production. Today that means AI fashion imagery at **Modelia**, multi-agent systems at **SelfAgentic**, which I co-founded, and a university learning platform I built solo for **GyanSathi**.

I care about the parts of AI products that rarely make the demo: correct billing, safe data pipelines, clean migrations, and agents that know when to hand over to a human.

<br>

<table>
<tr>
<td width="33%" valign="top" align="center">

### 🎨 [Modelia](https://modelia.ai)
**AI Product Engineer**

Generative-AI fashion imagery and video for e-commerce brands

</td>
<td width="33%" valign="top" align="center">

### 🤖 [SelfAgentic](https://selfagentic.in)
**Co-Founder & Developer**

Teams of autonomous AI agents that work inside your tools

</td>
<td width="33%" valign="top" align="center">

### 🎓 [GyanSathi](https://gyansathi.com)
**Delivered end to end**

University learning platform for 5,000+ learners, built solo

</td>
</tr>
</table>

<br>

## `Modelia` · AI Product Engineer

> [Modelia](https://modelia.ai) turns product photos into studio-quality fashion imagery and video with generative AI. I own systems across the product, from the billing engine under every generation to the agents that support customers.

<img src="assets/impact.svg" alt="367 merged pull requests in 2026" width="100%">

<br><br>

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Metering & billing for generative AI

Every image and video has a cost. I designed the engine that charges for it correctly.

- A **credit ledger and billing cycles in PostgreSQL**, built from transactional SQL functions, with an auditable pricing history kept by triggers
- **Stripe** webhooks drive each customer's cycle; plan changes and legacy-plan migrations are handled server-side
- **Generations pause at a zero balance and resume oldest-first**, with refunds when the engine fails, so users never pay for a failed job

`PostgreSQL` `Stripe` `TypeScript` `Event-driven`

</td>
<td width="50%" valign="top">

### 🎨 Modelia Studio platform

The workspace where brands turn their catalog into on-model photos, lifestyle shots and product video.

- A **catalog ingestion pipeline** for CSV, Google Drive and Dropbox, with an **SSRF-guarded fetcher** for untrusted image URLs
- **Catalog-to-generation orchestration**: one action seeds a studio project from any product
- **C2PA content credentials**, so generated media carries signed provenance

`TypeScript` `React` `Node.js` `PostgreSQL` `Azure`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Autonomous support agents

AI agents answer customers on chat and email, with humans in control.

- An **email agent with human-in-the-loop handoff** that stops the moment a person takes over
- An **embeddable chat widget** with a host API, so the studio can open support in context
- A **live knowledge base** the team edits from an admin console, plus an operations dashboard for every agent

`Python` `LLMs` `SQLAlchemy` `Agents`

</td>
<td width="50%" valign="top">

### 🛍️ Shopify platform

Modelia's AI fashion tools (virtual try-on, consistent character, outfit generation) inside Shopify.

- Drove the **cutover to a unified database and session layer**, rolled out behind feature flags, with a bulk data-migration pipeline and runbook
- **Security hardening**: expiring offline tokens, a framework upgrade, and **41 dependency vulnerabilities resolved**
- **Containerized for Azure Container Apps**

`Remix` `Shopify` `TypeScript` `Docker` `Azure`

</td>
</tr>
</table>

<br>

## `SelfAgentic` · multi-agent platform

<a href="https://selfagentic.in"><img src="assets/selfagentic.svg" alt="SelfAgentic: AI agents that work for you" width="100%"></a>

I co-founded and build **[SelfAgentic](https://selfagentic.in)**, a multi-agent platform (closed beta) where teams of autonomous agents collaborate, keep memory across runs, and take real actions in Slack, Google Workspace, LinkedIn and Meta Ads, with per-agent permissions and human approval on every outbound action.

<br>

## `GyanSathi` · delivered end to end

<a href="https://gyansathi.com"><img src="assets/gyansathi.svg" alt="GyanSathi: learning platform with AI-based evaluation" width="100%"></a>

I built **[GyanSathi](https://gyansathi.com)** end to end, solo: a production learning platform serving **5,000+ active learners at CCS University**, with course delivery, an examination engine, **AI-based evaluation of students**, automated certification, payments and real-time analytics.

<br>

## `journey`

<img src="assets/journey.svg" alt="Journey: Bharat Electronics → Asynq → GyanSathi → Modelia and SelfAgentic" width="100%">

<br><br>

## `open source`

<a href="https://github.com/Harsh-Rastogi-03/carcode"><img src="https://raw.githubusercontent.com/Harsh-Rastogi-03/carcode/main/assets/banner.svg" alt="carcode" width="100%"></a>

**[carcode](https://github.com/Harsh-Rastogi-03/carcode)** lets you **code from your car**: a voice interface to Claude Code. Say *"Hey Siri, Jarvis"* to review PRs, triage Slack and ship code changes hands-free over CarPlay. Under the hood, it keeps warm agent sessions, answers every turn within 8 seconds, holds long jobs in the background, and gates every outward action behind a spoken confirmation. It's tested, documented and set up in one command. **[Read how I built it →](https://harshrastogi.tech/blog/code-from-your-car-claude-code-carplay)** · **[Project page](https://harshrastogi.tech/projects/carcode)**

<br>

## `how I operate`

```diff
+ Own the outcome, not the ticket: product, platform and the billing underneath
+ Ship in small, reversible steps: 367 merged PRs this year, risky changes behind flags
+ Migrate without downtime: feature-flagged cutovers, data pipelines and written runbooks
+ Security is part of the feature: SSRF guards, token expiry, dependency hygiene
+ AI-native engineering: agents in my daily workflow, from code review to shipping by voice
```

<br>

## `stack`

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB)
![React](https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61DAFB)
![Remix](https://img.shields.io/badge/Remix-0d1117?style=flat-square&logo=remix&logoColor=ffffff)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=339933)
![FastAPI](https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=10b981)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![Stripe](https://img.shields.io/badge/Stripe-0d1117?style=flat-square&logo=stripe&logoColor=635BFF)
![Shopify](https://img.shields.io/badge/Shopify-0d1117?style=flat-square&logo=shopify&logoColor=7AB55C)
![Azure](https://img.shields.io/badge/Azure-0d1117?style=flat-square&logo=microsoftazure&logoColor=0078D4)
![AWS](https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED)
![Claude Code](https://img.shields.io/badge/Claude_Code-0d1117?style=flat-square&logo=anthropic&logoColor=D97757)
![OpenAI](https://img.shields.io/badge/OpenAI-0d1117?style=flat-square&logo=openai&logoColor=ffffff)

</div>

<br>

## `research & writing`

- 📚 **Book chapter:** *"6G Innovations: Healthcare & Medical Tech"*, Cambridge Scholars Publishing
- 📰 **Scopus-indexed paper:** *"Blockchain Technology in Bharat Judicial System"*

<br><br>

<div align="center">

### Building with generative AI? Let's talk.

<a href="https://linkedin.com/in/harsh2003"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-10b981?style=for-the-badge&logo=linkedin&logoColor=0d1117"/></a>&nbsp;&nbsp;
<a href="mailto:harshrastogi0603@gmail.com"><img src="https://img.shields.io/badge/Send_an_Email-10b981?style=for-the-badge&logo=gmail&logoColor=0d1117"/></a>&nbsp;&nbsp;
<a href="https://www.harshrastogi.tech"><img src="https://img.shields.io/badge/View_Portfolio-10b981?style=for-the-badge&logo=safari&logoColor=0d1117"/></a>

</div>
