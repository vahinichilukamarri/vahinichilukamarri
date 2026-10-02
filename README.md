<!-- ════════════════════════════════════  HERO  ════════════════════════════════════ -->
<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Venkata Vahini Chilukamarri — Backend · Distributed Systems · AI Engineering"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=800&color=A78BFA&center=true&vCenter=true&width=760&lines=%3E+ledger.post(txn)++%E2%86%92+balanced+per+currency+%E2%9C%93;%3E+retry(txn)++%E2%86%92+replayed%2C+not+re-applied+%E2%9C%93;%3E+agent.recover(payment)++%E2%86%92+%2B42%25+revenue+%E2%9C%93;%3E+tarjan(trace_spans)++%E2%86%92+cycles+collapsed+%E2%9C%93;%3E+vit.detect(road)++%E2%86%92+90%25%2B+accuracy+%E2%9C%93;%3E+vahini.status()++%E2%86%92+open+to+SWE+%2B+AI+roles_" alt="Typing SVG" /></a>

<a href="https://vahini-dev.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-vahini--dev-A78BFA?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/venkata-vahini-chilukamarri-2b5064314/"><img src="https://img.shields.io/badge/LinkedIn-Connect-38BDF8?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/></a>
<a href="mailto:vahinivenkatac@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-F472B6?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email"/></a>
<img src="https://komarev.com/ghpvc/?username=vahinichilukamarri&label=Profile%20views&color=A78BFA&style=for-the-badge&labelColor=0D1117" alt="Profile views"/>

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
                         "observability tooling", "vision models" };
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
Transactional outbox · idempotency keys · bounded LLM agents · Tarjan's SCC on trace spans · Vision Transformers

</td>
</tr>
</table>

<img src="./assets/impact.svg" width="100%" alt="Impact: +42% revenue recovered, +23% recovery rate, exactly one effect per idempotency key, 9.12 CGPA"/>

<!-- ════════════════════════════════════  EXPERIENCE  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%92%BC%20%20Experience&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Experience"/>

<table>
<tr>
<td width="130" align="center" valign="top">
<img src="https://img.shields.io/badge/Salesforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce"/><br/>
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
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%9A%80%20%20Flagship%20Builds&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Flagship Builds"/>

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

<!-- TODO: replace the link below with the LedgerGuard repo URL -->
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Explore_LedgerGuard-%E2%86%92-A78BFA?style=for-the-badge&logo=github&labelColor=0D1117" alt="Explore LedgerGuard"/></a>

<br/><br/>

### 🧠 TRACE — Transaction Recovery Agent with Contextual Evaluation
> *An AI agent for failed payments that's smart enough to adapt and disciplined enough to stay in bounds.*

<img src="./assets/trace.svg" width="100%" alt="TRACE recovery loop diagram"/>

- 🎛️ The agent picks recovery actions from a **controlled option set**, in a **bounded reassessment loop** that learns from prior outcomes without runaway execution
- 🛡️ An **independent policy layer** approves, blocks or flags every recommendation before anything runs
- 📈 Benchmarked against a fixed-rules baseline on **300 synthetic failed transactions**: **42% more revenue recovered** and a **23% higher relative recovery rate** on identical data
- 🧯 Idempotency protection for repeated payment events, and automatic **fallback to a safe/flagged state** when LLM classification times out or fails

`Python` `FastAPI` `React` `LLM APIs` `Agent Design`

<!-- TODO: replace the two links below with the TRACE live-demo and repo URLs -->
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Live_Demo-%E2%97%8F-38BDF8?style=for-the-badge&labelColor=0D1117" alt="TRACE live demo"/></a>
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Explore_TRACE-%E2%86%92-38BDF8?style=for-the-badge&logo=github&labelColor=0D1117" alt="Explore TRACE"/></a>

<!-- ════════════════════════════════════  MORE PROJECTS  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%AA%20%20More%20Things%20I've%20Built&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="More Things I've Built"/>

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ EvalEngine
**LLM Evaluation & Improvement System**

Modular **LLM-as-a-judge** pipeline that generates, scores and ranks AI responses across several metrics, then feeds the results back as **refinement signals** — shown in an interactive Streamlit dashboard.

🔁 Feedback refinement loop · 🔍 RAG *(in progress)*

`Python` `Streamlit` `LLM APIs` `RAG`

<a href="https://github.com/vahinichilukamarri/llm-evaluation-engine"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-A78BFA?style=flat-square&logo=github&labelColor=0D1117" alt="EvalEngine repo"/></a>

</td>
<td width="50%" valign="top">

### 🧩 AskBI
**AI Business Intelligence Dashboard**

End-to-end **natural-language → SQL** pipeline: non-technical users query CSV data in plain English and get real-time visual insights — no SQL required.

💬 Natural language → SQL · 📊 Real-time viz

`React` `FastAPI` `Pandas` `LLM APIs` `SQL`

<a href="https://github.com/vahinichilukamarri/AskBI"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-A78BFA?style=flat-square&logo=github&labelColor=0D1117" alt="AskBI repo"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛣️ SafeStreet
**Road Damage Detection & Alert System**

A **Vision Transformer** classifies 4 road-damage types at **90%+ accuracy**; a mobile app geotags each report on a map and auto-alerts government authorities.

🎯 90%+ ViT accuracy · ⬇️ ~40% less manual work

`Vision Transformer` `React Native` `Node.js` `REST API`

<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-38BDF8?style=flat-square&logo=github&labelColor=0D1117" alt="SafeStreet repo"/></a>

</td>
<td width="50%" valign="top">

### 🧠 MoodAngels
**AI Psychiatric Diagnostic Support**

**Multi-agent** AI system that analyses patient symptoms and behavioural indicators; Pearson-correlation analysis improved diagnostic accuracy **~25%** over a rule-based baseline.

🤝 ~25% accuracy gain · 📋 500+ synthetic records

`Multi-Agent AI` `NLP` `Python` `MERN Stack`

<a href="https://github.com/AnishaPaturi/Mood-Angles"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-38BDF8?style=flat-square&logo=github&labelColor=0D1117" alt="MoodAngels repo"/></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚌 NextRide
**Smart School Bus Tracking & Route Optimization**

Real-time GPS tracking with **dynamic routing** that recalculates around daily student attendance — cutting route distance and redundant stops.

📡 Real-time GPS · 🔁 ~20% shorter routes · 🛑 ~30% fewer stops

`Node.js` `Leaflet.js` `Dynamic Routing Algorithms`

<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/View_Repo-%E2%86%92-F472B6?style=flat-square&logo=github&labelColor=0D1117" alt="NextRide repo"/></a>

</td>
<td width="50%" valign="top">

### 🤖 AI Recruiter Avatar Platform
**Centific Hackathon 2.0 — winning build**

An AI recruiter avatar platform built in **2 weeks** that earned an **AI Engineer internship offer**.

🏆 Hackathon win · ⏱️ Built in 2 weeks

`FastAPI` `React`

</td>
</tr>
</table>

<!-- ════════════════════════════════════  HOW I BUILD  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%AD%20%20How%20I%20Build&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="How I Build"/>

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
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%A7%B0%20%20Toolkit&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Toolkit"/>

<div align="center">

<table>
<tr><td align="center" width="150"><b>💻 Languages</b></td><td>
<img src="https://skillicons.dev/icons?i=java,py,ts,js,cpp,html,css&theme=dark" alt="Languages"/>
</td></tr>
<tr><td align="center"><b>⚙️ Backend</b></td><td>
<img src="https://skillicons.dev/icons?i=spring,fastapi,nodejs,express,kafka&theme=dark" alt="Backend"/>
</td></tr>
<tr><td align="center"><b>🗄️ Data</b></td><td>
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite&theme=dark" alt="Databases"/>
<img src="https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white" height="40" alt="Flyway"/>
</td></tr>
<tr><td align="center"><b>🧠 AI / ML</b></td><td>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" alt="AI/ML"/>
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" height="40" alt="Keras"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" height="40" alt="Transformers"/>
<img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" height="40" alt="Groq"/>
<img src="https://img.shields.io/badge/LLM_Agents_%26_RAG-A78BFA?style=for-the-badge&logoColor=white" height="40" alt="LLM Agents and RAG"/>
</td></tr>
<tr><td align="center"><b>🎨 Frontend</b></td><td>
<img src="https://skillicons.dev/icons?i=react,nextjs&theme=dark" alt="Frontend"/>
<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" height="40" alt="React Native"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" height="40" alt="Streamlit"/>
</td></tr>
<tr><td align="center"><b>🧪 Testing & Ops</b></td><td>
<img src="https://skillicons.dev/icons?i=docker,git,github,githubactions&theme=dark" alt="DevOps"/>
<img src="https://img.shields.io/badge/JUnit-25A162?style=for-the-badge&logo=junit5&logoColor=white" height="40" alt="JUnit"/>
<img src="https://img.shields.io/badge/Testcontainers-291A3F?style=for-the-badge&logoColor=white" height="40" alt="Testcontainers"/>
<img src="https://img.shields.io/badge/jqwik-F472B6?style=for-the-badge&logoColor=white" height="40" alt="jqwik"/>
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
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%8F%86%20%20Trophy%20Shelf&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Trophy Shelf"/>

<div align="center">

| | | |
|:---:|:---:|:---:|
| 🥇<br/>**Centific Hackathon 2.0**<br/><sub>Awarded AI Engineer internship offer</sub> | ☁️<br/>**Salesforce Mentorship**<br/><sub>SWE Mentee · Summer 2026</sub> | 🎓<br/>**9.12 CGPA**<br/><sub>B.Tech CSE @ KMIT</sub> |
| 📐<br/>**97% Intermediate**<br/><sub>Top 3% statewide (MPC)</sub> | 🏫<br/>**10/10 SSC**<br/><sub>Perfect GPA</sub> | 🚀<br/>**PRAKALP Hackathon**<br/><sub>Bluetooth Talking Vehicle prototype</sub> |
| 🔬<br/>**GenAI Workshop**<br/><sub>Skilligence × IIT Hyderabad</sub> | 🤖<br/>**Generative AI**<br/><sub>GreatLearning Certified</sub> | 📜<br/>**SQL (Intermediate)**<br/><sub>HackerRank Certified</sub> |

</div>

<!-- ════════════════════════════════════  BEYOND THE CODE  ════════════════════════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1E1B4B,100:4C1D95&height=46&section=header&text=%F0%9F%8C%8D%20%20Beyond%20the%20Code&fontSize=22&fontColor=F0EEFF&fontAlignY=55" width="100%" alt="Beyond the Code"/>

<table>
<tr>
<td width="25%" align="center" valign="top">

### 👩‍💻
**Rewriting the Code**<br/>
<sub>Contributor to a nonprofit supporting women in tech · 2026 – now</sub>

</td>
<td width="25%" align="center" valign="top">

### 🛠️
**DBMS Workshop**<br/>
<sub>Facilitated a peer technical workshop at KMIT</sub>

</td>
<td width="25%" align="center" valign="top">

### 🫂
**NSS Volunteer**<br/>
<sub>5+ community drives · 40+ volunteer hours</sub>

</td>
<td width="25%" align="center" valign="top">

### 🎨
**Graphic Design Intern**<br/>
<sub>20+ digital & print assets reaching 2,000+ students</sub>

</td>
</tr>
</table>

<!-- ════════════════════════════════════  FOOTER  ════════════════════════════════════ -->
<br/>

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight&border=false" alt="Random dev quote"/>

### 💌 Building something where correctness matters? Let's talk.

<a href="https://vahini-dev.vercel.app/"><img src="https://img.shields.io/badge/View_Portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/venkata-vahini-chilukamarri-2b5064314/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:vahinivenkatac@gmail.com"><img src="https://img.shields.io/badge/Email_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://github.com/vahinichilukamarri"><img src="https://img.shields.io/badge/Follow_on_GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:A78BFA,30:4C1D95,65:1E1B4B,100:0D1117&height=130&section=footer&animation=twinkling" alt="footer"/>

</div>
