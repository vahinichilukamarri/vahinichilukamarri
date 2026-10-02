<!-- ════════════════════════════════════  HERO  ════════════════════════════════════ -->
<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Venkata Vahini Chilukamarri — Backend · Distributed Systems · AI Engineering"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=800&color=A78BFA&center=true&vCenter=true&width=760&lines=%3E+ledger.post(txn)++%E2%86%92+balanced+per+currency+%E2%9C%93;%3E+retry(txn)++%E2%86%92+replayed%2C+not+re-applied+%E2%9C%93;%3E+agent.recover(payment)++%E2%86%92+%2B42%25+revenue+%E2%9C%93;%3E+tarjan(trace_spans)++%E2%86%92+cycles+collapsed+%E2%9C%93;%3E+vahini.status()++%E2%86%92+open+to+SWE+%2B+AI+roles_" alt="Typing SVG" /></a>

<a href="https://vahini-dev.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-vahini--dev-A78BFA?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" /></a>
<a href="https://www.linkedin.com/in/venkata-vahini-chilukamarri-2b5064314/"><img src="https://img.shields.io/badge/LinkedIn-Connect-38BDF8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" /></a>
<a href="mailto:vahinivenkatac@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-F472B6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" /></a>
<img src="https://komarev.com/ghpvc/?username=vahinichilukamarri&label=Profile%20views&color=A78BFA&style=for-the-badge&labelColor=0D1117" />

</div>

<br/>

<!-- ════════════════════════════════════  WHOAMI  ════════════════════════════════════ -->
<table>
<tr>
<td width="56%" valign="top">

```java
@Engineer
public final class Vahini {

    String   name    = "Venkata Vahini Chilukamarri";
    String   school  = "KMIT · B.Tech CSE '27 · CGPA 9.12";
    String   recent  = "Salesforce Mentorship '26 · SWE Mentee";

    String[] builds  = { "payment ledgers", "AI agents",
                         "observability tooling" };
    String[] obsess  = { "idempotency", "failure modes",
                         "tests that break things" };

    Result ship(Idea idea) {
        return idea.design()
                   .test()
                   .breakOnPurpose()   // jqwik + fault injection
                   .fix()
                   .deploy();
    }
}
```

</td>
<td width="44%" valign="top">

### ⚡ What I do

I build **backend and AI systems that stay correct when things go wrong** — retries, duplicates, crashes, flaky LLMs.

Java + Spring Boot for the parts that must never lose money. Python + FastAPI for the parts that think.

### 🎯 Open to
**SWE · Backend · AI Engineering** roles where reliability actually matters.

### 💬 Ask me about
Transactional outbox · idempotency keys · bounded LLM agents · Tarjan's SCC on trace spans

</td>
</tr>
</table>

<img src="./assets/impact.svg" width="100%" alt="Impact: +42% revenue recovered, +23% recovery rate, exactly one effect per idempotency key, 9.12 CGPA"/>

<!-- ════════════════════════════════════  EXPERIENCE  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%92%BC%20%20Experience&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%"/>

<table>
<tr>
<td width="120" align="center" valign="top">
<img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white"/><br/>
<sub><b>Jun – Aug 2026</b><br/>Remote</sub>
</td>
<td valign="top">

#### Software Engineering Mentee — Salesforce Mentorship Program
**Microservice Health & API Performance Orchestrator**

- 🕸️ **Dependency graph engine** that auto-discovers service dependencies from **OpenTelemetry** trace spans, then runs **Tarjan's SCC** to detect and collapse circular dependencies
- 🎯 **Root-cause analysis** that ranks likely culprits via topological root-finding + time-correlation across services, with cycle-safe BFS/DFS to estimate **blast radius**
- 🔔 **Slack / Discord alerting** that suppresses duplicate and flapping alerts, retries with SQLite-backed fallback logging, and a live **Cytoscape.js** dependency dashboard

`OpenTelemetry` `Graph Algorithms` `SQLite` `Cytoscape.js` `Slack/Discord APIs`

</td>
</tr>
</table>

<!-- ════════════════════════════════════  FLAGSHIP PROJECTS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%9A%80%20%20Flagship%20Builds&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%"/>

### 🏦 LedgerGuard — Payment Integrity Platform
> *A ledger that refuses to be wrong — even when the network, the database and the clock all fail.*

<img src="./assets/ledgerguard.svg" width="100%" alt="LedgerGuard architecture diagram"/>

<table>
<tr>
<td width="33%" valign="top">

**💰 Can't go unbalanced**<br/>
Double-entry validation runs **per currency inside the same transaction** as the write — an unbalanced transaction can never be partially persisted.

</td>
<td width="33%" valign="top">

**🔁 Exactly one effect**<br/>
Required idempotency keys with **byte-identical replay**, a **transactional outbox** that publishes to Kafka only after commit, and consumer-side dedup.

</td>
<td width="33%" valign="top">

**🔎 Explains its alarms**<br/>
Statistical + **Isolation-Forest** anomaly detection with per-feature attribution and a **grounded LLM explanation** per flagged account, scored by a precision/recall harness.

</td>
</tr>
</table>

Verified end-to-end with **jqwik property tests** and **deterministic fault injection** across JDBC, broker and clock seams, plus a React/TypeScript ops console over the whole system.

`Java` `Spring Boot` `PostgreSQL` `Kafka` `Flyway` `jqwik` `Testcontainers` `React` `TypeScript`

<!-- TODO: replace with the LedgerGuard repo URL -->
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Explore_LedgerGuard-→-A78BFA?style=for-the-badge&logo=github&labelColor=0D1117"/></a>

<br/><br/>

### 🧠 TRACE — Transaction Recovery Agent with Contextual Evaluation
> *An AI agent for failed payments that's smart enough to adapt and disciplined enough to stay in bounds.*

<img src="./assets/trace.svg" width="100%" alt="TRACE recovery loop diagram"/>

- 🎛️ The agent picks recovery actions from a **controlled option set**, in a **bounded reassessment loop** that learns from prior outcomes without runaway execution
- 🛡️ An **independent policy layer** approves, blocks or flags every recommendation before anything runs
- 📈 Benchmarked against a fixed-rules baseline on **300 synthetic failed transactions**: **42% more revenue recovered** and a **23% higher relative recovery rate** on identical data
- 🧯 Idempotency protection for repeated payment events, and automatic **fallback to a safe/flagged state** when LLM classification times out or fails

`Python` `FastAPI` `React` `LLM APIs` `Agent Design`

<!-- TODO: replace with the TRACE live + repo URLs -->
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Live_Demo-●-38BDF8?style=for-the-badge&labelColor=0D1117"/></a>
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Explore_TRACE-→-38BDF8?style=for-the-badge&logo=github&labelColor=0D1117"/></a>

<br/><br/>

### 🛠️ LLM Tooling

<table>
<tr>
<td width="50%" valign="top">

#### ⚙️ EvalEngine
Modular **LLM-as-a-judge** pipeline that evaluates multiple AI responses across several metrics, feeds the scores back as **refinement signals**, and shows outcomes in an interactive Streamlit dashboard.

`Python` `Streamlit` `LLM APIs`

<a href="https://github.com/vahinichilukamarri/llm-evaluation-engine"><img src="https://img.shields.io/badge/View_Repo-→-A78BFA?style=flat-square&logo=github&labelColor=0D1117"/></a>

</td>
<td width="50%" valign="top">

#### 🧩 AskBI
**Natural-language → SQL** app that lets non-technical users query and visualise datasets in plain English — no SQL required.

`FastAPI` `React` `Pandas` `LLM APIs`

<a href="https://github.com/vahinichilukamarri/AskBI"><img src="https://img.shields.io/badge/View_Repo-→-A78BFA?style=flat-square&logo=github&labelColor=0D1117"/></a>

</td>
</tr>
</table>

<details>
<summary><b>🗂️ Earlier builds — ViTs, multi-agent systems, route optimisation (click to expand)</b></summary>
<br/>

| Project | What it does | Highlights |
|---|---|---|
| 🛣️ **SafeStreet** | Vision Transformer road-damage detection + mobile reporting app with geotagged maps and auto government alerts | 90%+ accuracy on 4 damage types · ~40% less manual work |
| 🧠 **[MoodAngels](https://github.com/AnishaPaturi/Mood-Angles)** | Multi-agent AI for psychiatric diagnostic support | ~25% accuracy gain over rule-based baseline |
| 🚌 **NextRide** | Real-time school-bus GPS tracking with attendance-aware dynamic routing | ~20% shorter routes · ~30% fewer stops |

</details>

<!-- ════════════════════════════════════  HOW I BUILD  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%AD%20%20How%20I%20Build&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%"/>

<table>
<tr>
<td width="33%" align="center" valign="top">

### 🔁
**Retries are a given**<br/>
<sub>Idempotency keys, outboxes and dedup consumers — so the second request is never a second charge.</sub>

</td>
<td width="33%" align="center" valign="top">

### 💥
**Break it before prod does**<br/>
<sub>Property-based tests and deterministic fault injection across the DB, the broker and the clock.</sub>

</td>
<td width="33%" align="center" valign="top">

### 🧭
**AI with guardrails**<br/>
<sub>Bounded action sets, independent policy layers and safe fallbacks when the model times out.</sub>

</td>
</tr>
</table>

<!-- ════════════════════════════════════  STACK  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%B0%20%20Toolkit&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%"/>

<div align="center">

<table>
<tr><td align="center" width="150"><b>💻 Languages</b></td><td>
<img src="https://skillicons.dev/icons?i=java,python,ts,js,cpp,html,css&theme=dark" />
</td></tr>
<tr><td align="center"><b>⚙️ Backend</b></td><td>
<img src="https://skillicons.dev/icons?i=spring,fastapi,nodejs,express,kafka&theme=dark" />
</td></tr>
<tr><td align="center"><b>🗄️ Data</b></td><td>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite&theme=dark" />
<img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" height="40"/>
</td></tr>
<tr><td align="center"><b>🧠 AI / ML</b></td><td>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" />
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" height="40"/>
<img src="https://img.shields.io/badge/LLM_Agents-A78BFA?style=for-the-badge&logo=openai&logoColor=white" height="40"/>
<img src="https://img.shields.io/badge/RAG-38BDF8?style=for-the-badge&logoColor=white" height="40"/>
</td></tr>
<tr><td align="center"><b>🎨 Frontend</b></td><td>
<img src="https://skillicons.dev/icons?i=react,nextjs&theme=dark" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" height="40"/>
</td></tr>
<tr><td align="center"><b>🧪 Testing & Ops</b></td><td>
<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions&theme=dark" />
<img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" height="40"/>
<img src="https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logo=testcontainers&logoColor=white" height="40"/>
<img src="https://img.shields.io/badge/jqwik-F472B6?style=for-the-badge&logoColor=white" height="40"/>
<img src="https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white" height="40"/>
</td></tr>
</table>

</div>

<!-- ════════════════════════════════════  STATS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%93%8A%20%20By%20the%20Numbers&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%"/>

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=vahinichilukamarri&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=38BDF8&text_color=F0EEFF&ring_color=A78BFA&rank_icon=github"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vahinichilukamarri&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=F0EEFF"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=vahinichilukamarri&bg_color=0D1117&color=C4B5FD&line=A78BFA&point=38BDF8&area=true&area_color=4C1D95&hide_border=true&custom_title=Commit%20heartbeat" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=vahinichilukamarri&hide_border=true&background=0D1117&ring=A78BFA&fire=38BDF8&currStreakLabel=A78BFA&sideLabels=F0EEFF&dates=94A3B8&stroke=1E1B4B" alt="GitHub Streak"/>

</div>

<!-- ════════════════════════════════════  SNAKE (kept)  ════════════════════════════════════ -->
## 🐍 Watch My Contributions Get Eaten!

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vahinichilukamarri/vahinichilukamarri/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vahinichilukamarri/vahinichilukamarri/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/vahinichilukamarri/vahinichilukamarri/output/github-contribution-grid-snake-dark.svg">
</picture>

</div>

<!-- ════════════════════════════════════  ACHIEVEMENTS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%8F%86%20%20Trophy%20Shelf&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%"/>

<div align="center">

| | | |
|:---:|:---:|:---:|
| 🥇<br/>**Centific Hackathon 2.0**<br/><sub>Awarded AI Engineer internship offer<br/>AI recruiter avatar platform in 2 weeks</sub> | ☁️<br/>**Salesforce Mentorship**<br/><sub>SWE Mentee · Summer 2026</sub> | 🎓<br/>**9.12 CGPA**<br/><sub>B.Tech CSE @ KMIT</sub> |
| 📐<br/>**97% Intermediate**<br/><sub>Top 3% statewide (MPC)</sub> | 🔬<br/>**GenAI Workshop**<br/><sub>Skilligence × IIT Hyderabad</sub> | 📜<br/>**SQL (Intermediate)**<br/><sub>HackerRank Certified</sub> |
| 🛠️<br/>**DBMS Workshop Facilitator**<br/><sub>Peer technical workshop @ KMIT</sub> | 👩‍💻<br/>**Rewriting the Code**<br/><sub>Contributor · women in tech nonprofit</sub> | 🫂<br/>**NSS Volunteer**<br/><sub>5+ drives · 40+ hours</sub> |

</div>

<!-- ════════════════════════════════════  FOOTER  ════════════════════════════════════ -->
<br/>

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight&border=false" />

### 💌 Building something where correctness matters? Let's talk.

<a href="https://vahini-dev.vercel.app/"><img src="https://img.shields.io/badge/View_Portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/venkata-vahini-chilukamarri-2b5064314/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:vahinivenkatac@gmail.com"><img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:A78BFA,30:4C1D95,65:1E1B4B,100:0D1117&height=130&section=footer&animation=twinkling" />

</div>
