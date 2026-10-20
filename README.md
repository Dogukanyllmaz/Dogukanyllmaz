<h1 align="center">Doğukan Yılmaz</h1>
<p align="center">
  <b>Process Development Specialist · Internal Audit</b><br/>
  Business Process Management · Workflow Automation · ERP Integration · .NET Backend
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/h%C3%BCseyindogukanyilmaz/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dogu_codeM@hotmail.com"><img src="https://img.shields.io/badge/Email-1F2937?style=flat-square&logo=maildotru&logoColor=white" alt="Email"/></a>
</p>

---

### About

I design, automate and audit end-to-end business processes in an industrial enterprise environment.
My work sits where **internal control**, **process engineering** and **software** meet: I map how work
actually flows, find where control and efficiency break down, and then build the workflows,
integrations and analytics that fix it.

- 🔎 **Internal audit & control:** risk–control mapping, segregation of duties, approval-chain design, data-driven audit testing
- 🗺️ **Process architecture:** As-Is / To-Be modelling, BPMN swimlane maps (macro & micro level), RACI, SLA and escalation design
- ⚙️ **Workflow automation:** enterprise BPM workflows covering procurement, invoicing, warehouse, goods receipt and service requests
- 🔗 **ERP integration:** automated document transfer between the BPM platform and the ERP, with retry, error states and alerting
- 📊 **Process analytics:** cycle-time, bottleneck and throughput analysis from workflow history (process-mining approach)
- 🧱 **Backend engineering:** ASP.NET Core APIs, layered / clean architecture, microservices with an API gateway, JWT authentication
- 📈 **Continuous improvement:** Lean Six Sigma (DMAIC, Kaizen), ISO 9001 quality management

---

### Selected Work

| Area | What I delivered |
|---|---|
| **Procure-to-Pay redesign** · [case study](https://github.com/Dogukanyllmaz/procure-to-pay-redesign-case-study) | Unified redesign of request → stock issue → transfer → purchasing → goods receipt → invoice as one module, with SLAs, escalation rules, decision tables, RACI and a status model. Model-driven: one JSON source generates the BPMN maps and the design documentation. |
| **Enterprise process mapping** · [toolkit](https://github.com/Dogukanyllmaz/process-mapping-toolkit) | Extracted and documented the As-Is state of **70+ production workflows across 30+ process groups** directly from platform packages, producing a navigable process atlas and a control-gap baseline. |
| **BPM ↔ ERP integration** · [pattern](https://github.com/Dogukanyllmaz/bpm-erp-integration-pattern) | Scheduled service that transfers pending purchase invoices from the workflow platform into the ERP, updates document status, retries failures and escalates persistent errors by email. |
| **Process performance analytics** | Read-only analytics layer over workflow history: step-level cycle times, working-day calendar, open-item survival analysis and end-to-end request-chain tracing. |
| **Vela: project & OKR management** | Full-stack web application for tasks, OKRs and process-improvement follow-up, linking audit findings to actionable tasks. |
| **.NET backend portfolio** | E-commerce microservices (product, order, auth) behind an Ocelot API gateway with resilient inter-service calls; reusable core layer with cross-cutting concerns; JWT authentication reference implementations. |

---

### Featured Repositories

| Repository | About |
|---|---|
| [procure-to-pay-redesign-case-study](https://github.com/Dogukanyllmaz/procure-to-pay-redesign-case-study) | Model-driven redesign of a multi-site procure-to-pay cycle: decision tables, built-in controls |
| [process-mapping-toolkit](https://github.com/Dogukanyllmaz/process-mapping-toolkit) | Swimlane maps and automated internal-control checks for BPM workflows (Python) |
| [bpm-erp-integration-pattern](https://github.com/Dogukanyllmaz/bpm-erp-integration-pattern) | Idempotent BPM → ERP document sync with retry and alerting (.NET, tested) |
| [ecommerce-microservices](https://github.com/Dogukanyllmaz/ecommerce-microservices) | .NET 8 microservices behind an Ocelot API gateway: clean architecture, JWT, Polly retries |
| [dotnet-core-layer](https://github.com/Dogukanyllmaz/dotnet-core-layer) | Reusable core layer with AOP cross-cutting concerns (Autofac interceptors) |
| [pharmacy-management-api](https://github.com/Dogukanyllmaz/pharmacy-management-api) | Layered API with Redis caching, Serilog/Seq and FluentValidation |
| [jwt-auth-dotnet9](https://github.com/Dogukanyllmaz/jwt-auth-dotnet9) | JWT access / refresh-token reference implementation on .NET 9 |
| [crypto-signal-bot](https://github.com/Dogukanyllmaz/crypto-signal-bot) | Graduation thesis: Gaussian-channel signal bot with Telegram alerts |

---

### Toolbox

**Process & governance:** BPMN 2.0 · RACI · RCM (risk-control matrix) · Lean Six Sigma · ISO 9001 · COSO-based internal control<br/>
**Platforms:** eBA (Bimser) BPM · Netsis ERP · Microsoft SQL Server<br/>
**Backend:** C# · ASP.NET Core 8/9 · Entity Framework Core · Ocelot · Polly · Autofac · FluentValidation · Serilog · Redis · Docker<br/>
**Other:** Python · SQL · TypeScript · React · Angular · Java / Spring · Supabase · draw.io

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/BPMN-1F2937?style=flat-square"/>
  <img src="https://img.shields.io/badge/Lean_Six_Sigma-0F766E?style=flat-square"/>
</p>

---

### How I work

1. **Map it as it really is:** from system data, not from assumptions.
2. **Find the control and flow gaps:** missing SLAs, hard-coded approvers, manual hand-offs, unreliable data.
3. **Redesign with control built in:** clear ownership, escalation and auditability by design.
4. **Automate and measure:** ship the workflow and the metrics that prove it works.

<sub>Most of my process, workflow and integration work is proprietary and kept in private repositories. Public repositories contain generalized case studies, process tooling and backend reference projects.</sub>
