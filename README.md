<!-- ════════════════════════════════════  HERO  ════════════════════════════════════ -->
<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Venkata Vahini Chilukamarri — Software & AI Engineer"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=800&color=A78BFA&center=true&vCenter=true&width=780&lines=%3E+morph.integrate(api_a%2C+api_b)++%E2%86%92+tests+shipped+with+the+code+%E2%9C%93;%3E+trace.recover(payment)++%E2%86%92+%2B42%25+revenue+vs+rules+%E2%9C%93;%3E+ledger.post(txn)++%E2%86%92+balanced+per+currency+%E2%9C%93;%3E+retry(txn)++%E2%86%92+replayed%2C+not+re-applied+%E2%9C%93;%3E+agentshield.patch(iac)++%E2%86%92+paper+accepted+%E2%9C%93;%3E+vahini.status()++%E2%86%92+open+to+SWE+%2B+AI+internships_" alt="Typing SVG"/></a>

<a href="https://vahini-dev.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-vahini--dev-A78BFA?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/venkata-vahini-chilukamarri-2b5064314/"><img src="https://img.shields.io/badge/LinkedIn-Connect-38BDF8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/></a>
<a href="mailto:vahinivenkatac@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-F472B6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/></a>
<img src="https://komarev.com/ghpvc/?username=vahinichilukamarri&label=Profile%20views&color=A78BFA&style=for-the-badge&labelColor=0D1117" alt="Profile views"/>

<br/><br/>

### Verified, not trusted.
<sub>Every agent I build proposes — deterministic code decides.</sub>

</div>

<br/>

<!-- ════════════════════════════════════  WHOAMI  ════════════════════════════════════ -->
<table>
<tr>
<td width="56%" valign="top">

```java
@Engineer
public final class Vahini {

    String   name     = "Venkata Vahini Chilukamarri";
    String   school   = "KMIT · B.Tech CSE '27 · CGPA 9.12";
    String   recent   = "Salesforce Mentorship '26 · SWE Mentee";
    String   research = "AgentShield AI · accepted, Jan 2027";

    String[] builds   = { "LLM agents", "payment ledgers",
                          "eval pipelines", "observability tooling" };
    String[] believes = { "agents propose, code decides",
                          "tests that break things",
                          "negative results stay in" };

    Result ship(Idea idea) {
        return idea.design()
                   .test()
                   .breakOnPurpose()   // jqwik + fault injection
                   .gate()             // policy before execution
                   .deploy();
    }
}
```

</td>
<td width="44%" valign="top">

### ⚡ What I do

Final-year CSE at KMIT building **AI systems that are verified, not trusted** — agents that ship their own test suites, payment agents fenced by deterministic policy, and ledgers proven with property-based tests.

Most of my work sits where **LLM agents, testing and distributed systems** meet.

### 🛠️ Now building
**MORPH v0.6** — MCP policy layer

### 🎯 Open to
**Software Engineering · AI/ML** internships

</td>
</tr>
</table>

<!-- ════════════════════════════════════  NUMBERS  ════════════════════════════════════ -->
<div align="center">

| 🎓 **9.12** | 📈 **+42%** | 📄 **1** | 🧪 **38 / 15** |
|:---:|:---:|:---:|:---:|
| <sub>CGPA · B.Tech CSE, KMIT</sub> | <sub>more revenue recovered than a rules baseline (TRACE, 300 cases)</sub> | <sub>accepted research paper · AgentShield AI, Jan 2027</sub> | <sub>property tests / fault injections guarding LedgerGuard</sub> |

</div>

<!-- ════════════════════════════════════  EXPERIENCE  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%92%BC%20%20Experience%20%26%20Research&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Experience & Research"/>

<table>
<tr>
<td width="140" align="center" valign="top">
<img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce"/><br/>
<sub><b>Jun – Aug 2026</b><br/>Remote</sub>
</td>
<td valign="top">

#### Software Engineering Mentee — Salesforce Mentorship Program
**Microservice Health & API Performance Orchestrator**

- 🕸️ **Dependency-graph engine** that auto-discovers service dependencies from **OpenTelemetry** trace spans, using **Tarjan's SCC** to detect and collapse circular dependencies before analysis
- 🎯 **Root-cause analysis** combining topological root-finding with time-correlation ranking, plus cycle-safe BFS/DFS **blast-radius** computation to predict cascading failures
- 🔔 **Deduplicated Slack/Discord alerting** with flap suppression and retry/fallback logging, backed by a SQLite incident store and a live **Cytoscape.js** dependency dashboard

`FastAPI` `OpenTelemetry` `SQLite` `Cytoscape.js` `Slack API` `Graph Algorithms`

</td>
</tr>
<tr>
<td width="140" align="center" valign="top">
<img src="https://img.shields.io/badge/Paper-Accepted-A78BFA?style=for-the-badge&labelColor=0D1117" alt="Accepted paper"/><br/>
<sub><b>To appear<br/>Jan 2027</b></sub>
</td>
<td valign="top">

#### 🛡️ AgentShield AI — Co-author
**Multi-agent LLMs for cloud infrastructure security**

- Extends LLM-based IaC vulnerability remediation from **AWS-only to Azure and GCP** across Terraform, Kubernetes and Helm
- An **8-agent LangGraph pipeline** over Checkov, tfsec and KICS scans with RAG retrieval
- Patches validated in a **LocalStack sandbox**; Claude / GPT-4o **ensemble voting** routes low-confidence fixes to human review

`Python` `LangGraph` `RAG` `FastAPI` `Checkov` `tfsec` `KICS` `LocalStack`

<sub>📎 Preprint link coming soon</sub>

</td>
</tr>
</table>

<!-- ════════════════════════════════════  FLAGSHIP PROJECTS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%9A%80%20%20Flagship%20Builds&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Flagship Builds"/>

### 🧬 MORPH — Autonomous AI Integration Engineer &nbsp;<img src="https://img.shields.io/badge/NEW-A78BFA?style=flat-square" alt="New"/>
> *Agent-written integration code — verified, not trusted.*

Given two independently built systems' API contracts, MORPH discovers their schemas, proposes how the data maps, writes the integration — and pairs **every generated module with a generated test suite**, run inside a locked-down sandbox.

```mermaid
flowchart LR
    A[Discover<br/>OpenAPI → system model] --> B[Map<br/>model proposes, code validates]
    B --> C[Review<br/>human gate]
    C --> D[Generate<br/>code + its own tests]
    D --> E[Gate<br/>G1–G5 · AST · ruff · mypy strict]
    E --> F[Sandbox<br/>locked-down Docker]
    F -->|fail| G[Repair<br/>bounded LangGraph loop]
    G -->|≤ 3 attempts| E
    G -->|exhausted| C
    F -->|pass| H[Expose<br/>capabilities as MCP tools]
```

<table>
<tr>
<td width="25%" align="center"><b>≤ 3</b><br/><sub>bounded repairs, then a human</sub></td>
<td width="25%" align="center"><b>5</b><br/><sub>guards that never loosen</sub></td>
<td width="25%" align="center"><b>413</b><br/><sub>hidden oracle checks</sub></td>
<td width="25%" align="center"><b>60 s</b><br/><sub>sandbox time limit</sub></td>
</tr>
</table>

**Honest by design** — correctness is judged by a hand-written oracle the pipeline never sees. A run that passes every gate MORPH controls can still fail the oracle, and that gets reported. Conditions that never reached READY stay in every denominator, and a source-level test forbids the repair loop from importing oracle code.

`Python` `FastAPI` `LangGraph` `MCP` `PostgreSQL` `pgvector` `Docker` `Groq` `Ollama`

<!-- TODO: replace the link below with the MORPH repo URL -->
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Explore_MORPH-%E2%86%92-A78BFA?style=for-the-badge&logo=github&labelColor=0D1117" alt="Explore MORPH"/></a>

<br/><br/>

### 🧠 TRACE — Transaction Recovery Agent with Contextual Evaluation &nbsp;<img src="https://img.shields.io/badge/LIVE-22C55E?style=flat-square" alt="Live"/>
> *A failed payment isn't a lost customer — and an agent shouldn't get the last word.*

<img src="./assets/trace.svg" width="100%" alt="TRACE recovery loop diagram"/>

TRACE decides whether a failed payment is worth recovering, picks the single best next action, executes it, adapts to the outcome — and knows when to stop. Built for the **Razorpay AI Buildathon**.

- 📈 Benchmarked against a fixed-rules baseline on **300 synthetic failed transactions**: **+42% revenue recovered** at a **23% higher relative recovery rate** on identical data
- ⚙️ **Dual-engine design** — a free deterministic heuristic scores every case; the LLM (Groq) is called only when one of four uncertainty signals fires
- 🛡️ A **9-rule, 100% deterministic policy layer** approves, blocks or flags every recommendation before execution; LLM timeouts fall back to a safe, flagged state

`React` `FastAPI` `SQLAlchemy` `Groq LLM` `PostgreSQL` `Vercel` `Render`

<a href="https://trace-xi-nine.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-%E2%97%8F-38BDF8?style=for-the-badge&labelColor=0D1117" alt="TRACE live demo"/></a>
<a href="https://github.com/vahinichilukamarri/TRACE"><img src="https://img.shields.io/badge/Explore_TRACE-%E2%86%92-38BDF8?style=for-the-badge&logo=github&labelColor=0D1117" alt="Explore TRACE"/></a>

<br/><br/>

### 🏦 LedgerGuard — Payment Integrity Platform
> *A ledger that refuses to be wrong — even when the network, the database and the clock all fail.*

<img src="./assets/ledgerguard.svg" width="100%" alt="LedgerGuard architecture diagram"/>

Built in **14 locked, tagged phases** — enforcing that debits equal credits for every transaction before it's persisted, then independently verifying, stress-testing and explaining anything that looks wrong.

<table>
<tr>
<td width="33%" valign="top">

**💰 Can't go unbalanced**<br/>
Double-entry invariant validated **per currency inside the same transaction** as the write — no half-committed unbalanced state is ever visible.

</td>
<td width="33%" valign="top">

**🔁 Exactly one effect**<br/>
Idempotency keys with **byte-identical replay** under concurrent duplicates; events published to Kafka via a **transactional outbox**.

</td>
<td width="33%" valign="top">

**💥 Broken on purpose**<br/>
**38 property-based tests** (jqwik) plus **15 deterministic fault injections** at the JDBC, broker and clock seams.

</td>
</tr>
</table>

Statistical + Isolation-Forest anomaly detection with grounded LLM explanations, scored against labelled data, and a React/TypeScript ops console over the whole system.

`Java` `Spring Boot` `PostgreSQL` `Kafka` `Flyway` `jqwik` `Testcontainers` `React` `TypeScript`

<a href="https://github.com/vahinichilukamarri/LedgerGuard"><img src="https://img.shields.io/badge/Explore_LedgerGuard-%E2%86%92-A78BFA?style=for-the-badge&logo=github&labelColor=0D1117" alt="Explore LedgerGuard"/></a>

<!-- ════════════════════════════════════  MORE PROJECTS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%AA%20%20More%20Things%20I've%20Built&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="More Things I've Built"/>

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ EvalEngine
**LLM Evaluation & Improvement Engine**

Modular **LLM-as-a-judge** pipeline that generates, scores and ranks AI responses across several metrics, then feeds results back as **refinement signals** — surfaced in an interactive Streamlit dashboard.

`Python` `Streamlit` `LLM APIs` `RAG`

<a href="https://github.com/vahinichilukamarri/llm-evaluation-engine"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-A78BFA?style=flat-square&logo=github&labelColor=0D1117" alt="EvalEngine repo"/></a>

</td>
<td width="50%" valign="top">

### 🧩 AskBI
**Plain-English Business Intelligence**

End-to-end **natural-language → SQL** pipeline: non-technical users query CSV data in plain English and get real-time visual insights — no SQL required.

`React` `FastAPI` `Pandas` `LLM APIs` `SQL`

<a href="https://github.com/vahinichilukamarri/AskBI"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-A78BFA?style=flat-square&logo=github&labelColor=0D1117" alt="AskBI repo"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛣️ SafeStreet
**Vision-Transformer Road Damage Detection**

A **Vision Transformer** classifies 4 road-damage types at **90%+ accuracy**; a mobile app geotags each report and auto-alerts the authorities — cutting manual work by ~40%.

`Vision Transformer` `React Native` `Node.js` `REST API`

<!-- TODO: replace the link below with the SafeStreet repo URL -->
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-38BDF8?style=flat-square&logo=github&labelColor=0D1117" alt="SafeStreet repo"/></a>

</td>
<td width="50%" valign="top">

### 🧠 MoodAngels
**AI-Based Psychiatric Diagnostic Support**

**Multi-agent** system that analyses symptoms and behavioural indicators; Pearson-correlation analysis improved diagnostic accuracy **~25%** over a rule-based baseline on 500+ synthetic records.

`Multi-Agent AI` `NLP` `Python` `MERN Stack`

<a href="https://github.com/AnishaPaturi/Mood-Angles"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-38BDF8?style=flat-square&logo=github&labelColor=0D1117" alt="MoodAngels repo"/></a>

</td>
</tr>
</table>

<!-- ════════════════════════════════════  HOW I BUILD  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%AD%20%20How%20I%20Build&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="How I Build"/>

<table>
<tr>
<td width="25%" align="center" valign="top">

### 🧭
**Agents propose, code decides**<br/>
<sub>Bounded action sets and deterministic policy layers that can veto the model before anything runs.</sub>

</td>
<td width="25%" align="center" valign="top">

### 🧪
**AI code ships with its tests**<br/>
<sub>Generated modules come with generated test suites, gated and run in a sandbox.</sub>

</td>
<td width="25%" align="center" valign="top">

### 💥
**Break it before prod does**<br/>
<sub>Property-based tests and fault injection across the DB, the broker and the clock.</sub>

</td>
<td width="25%" align="center" valign="top">

### 📏
**Negative results stay in**<br/>
<sub>Hidden oracles and honest denominators — a pipeline shouldn't grade itself.</sub>

</td>
</tr>
</table>

<!-- ════════════════════════════════════  STACK  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%B0%20%20Toolkit&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Toolkit"/>

<div align="center">

<table>
<tr><td align="center" width="150"><b>💻 Languages</b></td><td>
<img src="https://skillicons.dev/icons?i=py,java,ts,js,cpp,html,css&theme=dark" alt="Languages"/>
</td></tr>
<tr><td align="center"><b>🧠 AI & LLMs</b></td><td>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" height="40" alt="LangGraph"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" height="40" alt="LangChain"/>
<img src="https://img.shields.io/badge/MCP-A78BFA?style=for-the-badge&logoColor=white" height="40" alt="MCP"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" height="40" alt="Groq"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" height="40" alt="Ollama"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" height="40" alt="Hugging Face"/>
<br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" alt="ML frameworks"/>
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" height="40" alt="Keras"/>
<img src="https://img.shields.io/badge/RAG_·_LLM--as--Judge_·_ViT-38BDF8?style=for-the-badge&labelColor=0D1117" height="40" alt="RAG, LLM-as-Judge, ViT"/>
</td></tr>
<tr><td align="center"><b>⚙️ Backend & Web</b></td><td>
<img src="https://skillicons.dev/icons?i=fastapi,spring,nodejs,express,kafka,react&theme=dark" alt="Backend and web"/>
<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" height="40" alt="React Native"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" height="40" alt="Streamlit"/>
</td></tr>
<tr><td align="center"><b>🗄️ Data</b></td><td>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite&theme=dark" alt="Databases"/>
<img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" height="40" alt="pgvector"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" height="40" alt="Flyway"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" height="40" alt="Pandas"/>
</td></tr>
<tr><td align="center"><b>🧪 Testing & Ops</b></td><td>
<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions&theme=dark" alt="DevOps"/>
<img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" height="40" alt="JUnit"/>
<img src="https://img.shields.io/badge/jqwik-F472B6?style=for-the-badge&logoColor=white" height="40" alt="jqwik"/>
<img src="https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logoColor=white" height="40" alt="Testcontainers"/>
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" height="40" alt="OpenTelemetry"/>
</td></tr>
</table>

</div>

<!-- ════════════════════════════════════  STATS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%93%8A%20%20By%20the%20Numbers&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="By the Numbers"/>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=vahinichilukamarri&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=38BDF8&text_color=F0EEFF&ring_color=A78BFA&rank_icon=github" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vahinichilukamarri&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=F0EEFF" alt="Top languages"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=vahinichilukamarri&bg_color=0D1117&color=C4B5FD&line=A78BFA&point=38BDF8&area=true&area_color=4C1D95&hide_border=true&custom_title=Commit%20heartbeat" alt="Contribution activity graph"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=vahinichilukamarri&hide_border=true&background=0D1117&ring=A78BFA&fire=38BDF8&currStreakLabel=A78BFA&sideLabels=F0EEFF&dates=94A3B8&stroke=1E1B4B" alt="GitHub Streak"/>

</div>

## 🐍 Watch My Contributions Get Eaten!

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vahinichilukamarri/vahinichilukamarri/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vahinichilukamarri/vahinichilukamarri/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/vahinichilukamarri/vahinichilukamarri/output/github-contribution-grid-snake-dark.svg">
</picture>

</div>

<!-- ════════════════════════════════════  ACHIEVEMENTS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%8F%86%20%20Recognition&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Recognition"/>

<div align="center">

| | | |
|:---:|:---:|:---:|
| 🥇<br/>**Centific Premier Hackathon 2.0**<br/><sub>Winner · AI recruiter avatar platform built in 2 weeks · AI Engineer internship offer</sub> | 📄<br/>**AgentShield AI**<br/><sub>Co-author · accepted, to appear Jan 2027</sub> | ☁️<br/>**Salesforce Mentorship**<br/><sub>SWE Mentee · Summer 2026</sub> |
| 🎓<br/>**9.12 CGPA**<br/><sub>B.Tech CSE @ KMIT · 2023–2027</sub> | 📐<br/>**97.0% Intermediate**<br/><sub>Top 3% statewide (MPC)</sub> | 🚀<br/>**PRAKALP & GfG Hackathons**<br/><sub>Bluetooth Talking Vehicle · end-to-end prototype</sub> |
| 📜<br/>**SQL (Intermediate)**<br/><sub>HackerRank Certified</sub> | 🤖<br/>**Generative AI for Beginners**<br/><sub>GreatLearning Certified</sub> | 🔬<br/>**Generative AI Workshop**<br/><sub>Skilligence EdTech × IIT Hyderabad</sub> |

</div>

<!-- ════════════════════════════════════  BEYOND THE CODE  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%8C%8D%20%20Beyond%20the%20Code&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Beyond the Code"/>

<table>
<tr>
<td width="25%" align="center" valign="top">

### 👩‍💻
**Rewriting the Code**<br/>
<sub>Contributor to a nonprofit supporting women in tech · Jun 2026 – now</sub>

</td>
<td width="25%" align="center" valign="top">

### 🛠️
**DBMS Workshop**<br/>
<sub>Led a peer technical workshop on database systems at KMIT</sub>

</td>
<td width="25%" align="center" valign="top">

### 🫂
**NSS Volunteer**<br/>
<sub>5+ service drives · 40+ volunteer hours · since 2023</sub>

</td>
<td width="25%" align="center" valign="top">

### 🎨
**Graphic Designer Intern**<br/>
<sub>KMIT Student Council PR · 20+ assets, 2,000+ reach</sub>

</td>
</tr>
</table>

<!-- ════════════════════════════════════  FOOTER  ════════════════════════════════════ -->
<br/>

<div align="center">

### 💌 Let's build something real.
<sub>Looking for Software Engineering or AI/ML internships — or just say hi.</sub>

<br/><br/>

<a href="https://vahini-dev.vercel.app/"><img src="https://img.shields.io/badge/View_Portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/venkata-vahini-chilukamarri-2b5064314/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:vahinivenkatac@gmail.com"><img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:A78BFA,30:4C1D95,65:1E1B4B,100:0D1117&height=130&section=footer&animation=twinkling" alt="footer"/>

</div>
