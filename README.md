<h2>William Hideki Nakata</h2>

AI Automation Engineer & Full Stack Developer · Brazil (GMT-3)

<a href="https://www.linkedin.com/in/whnakata"><img src="https://img.shields.io/badge/LinkedIn-whnakata-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://williamnakata.dev"><img src="https://img.shields.io/badge/Portfolio-williamnakata.dev-111111?style=flat-square" alt="Portfolio" /></a>
<a href="mailto:whnakata@gmail.com"><img src="https://img.shields.io/badge/Email-whnakata%40gmail.com-555555?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>

I build AI agents and automation that run inside real business systems, backed by solid backend and data engineering. Currently at Toledo Piza, where I've shipped two production agents (LangChain, LangGraph, Azure AI Foundry) with tracing and guardrails, automated 6+ manual processes, and maintained ETL pipelines handling millions of rows per day.

Before that I spent two years teaching Computational Numerical Methods at UNESP, where I earned my BSc in Computer Science. I still care about understanding things from first principles.

### Stack

<img src="https://skillicons.dev/icons?i=py,cs,dotnet,ts,nodejs,angular,fastapi,docker,azure&perline=9" alt="Python, C#, .NET, TypeScript, Node.js, Angular, FastAPI, Docker, Azure" />

**AI & Automation**: LangChain · LangGraph · RAG · Azure AI Foundry · OpenAI API · Vector DBs · LangSmith · n8n<br />
**Backend**: C# (.NET, EF Core) · Python (FastAPI) · TypeScript · Node.js · REST APIs<br />
**Data & Infra**: SQL Server (T-SQL) · ETL · Power BI · Docker · Azure · CI/CD

<details>
<summary><b>How I usually structure an agent system</b></summary>
<br />

```mermaid
flowchart LR
    A[Business data<br/>SQL Server / APIs] --> B[ETL & processing<br/>Python]
    B --> C[Embeddings<br/>Vector DB]
    C --> D[Agent<br/>LangGraph]
    D <--> E[Tools<br/>.NET / REST APIs]
    D --> F[Tracing & guardrails<br/>LangSmith]
```

</details>

### Selected work

| Project | What it shows |
|---|---|
| [**starkbank-challenge**](https://github.com/hidekinakata/starkbank-challenge) | Python webhook service, hexagonal architecture, idempotent payments, signature verification, retries. `mypy --strict`, 78 tests. |
| [**NeuralNet-from-scratch**](https://github.com/hidekinakata/NeuralNet-from-scratch) | A complete neural network using only NumPy. |

<sub>Most of my professional work lives in private corporate repositories.</sub>
