<!-- ===================================================== -->
<!--            SATVIK SHANKAR SINGH / PROFILE             -->
<!-- ===================================================== -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=230&color=0:0F172A,50:22D3EE,100:A78BFA&text=SATVIK%20SHANKAR%20SINGH&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Agentic%20AI%20%C2%B7%20LLM%20Systems%20%C2%B7%20Autonomous%20Agents&descAlignY=62&descSize=18" width="100%" alt="Header"/>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2400&pause=700&color=22D3EE&center=true&vCenter=true&width=950&lines=agents+that+plan+%E2%86%92+retrieve+%E2%86%92+code+%E2%86%92+test+%E2%86%92+ship;LangGraph+%C3%97+RAG+%C3%97+Multi-Agent+Orchestration;58+passing+tests+in+my+GitHub+issue-resolving+agent;Open-source+contributor+%40+Aden+Hive+(YC-backed);Prototype+%E2%86%92+Production.+Always." alt="Typing animation"/>
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/satvik1221"><img src="https://img.shields.io/badge/LinkedIn-satvik1221-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:sanu8800971634@gmail.com"><img src="https://img.shields.io/badge/Gmail-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="mailto:ss7225@srmist.edu.in"><img src="https://img.shields.io/badge/SRM%20Mail-ss7225-0F172A?style=for-the-badge&logo=gmail&logoColor=22D3EE"/></a>
  <a href="https://www.spazorlabs.com"><img src="https://img.shields.io/badge/SpazorLabs-Research-111827?style=for-the-badge&logo=googlechrome&logoColor=A78BFA"/></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Satvik12221as&label=PROFILE%20VIEWS&color=22d3ee&style=for-the-badge" alt="Profile views"/>
  <img src="https://img.shields.io/github/followers/Satvik12221as?style=for-the-badge&logo=github&color=A78BFA&labelColor=0F172A" alt="Followers"/>
</p>

---

# 🧠 `whoami`

```text
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║   NAME        →  Satvik Shankar Singh                            ║
║   ROLE        →  Agentic AI & LLM Engineer                       ║
║   BASE        →  Chennai, India  ·  SRM University (ECE + DS)    ║
║   GRAD        →  2028                                            ║
║   STACK       →  LangGraph · RAG · FastAPI · Docker · PyTorch    ║
║   OSS         →  Aden Hive (YC-backed agent framework)           ║
║   MODE        →  BUILD → BREAK → EVALUATE → SHIP                 ║
║                                                                  ║
║   STATUS      →  ██████████████████████████░░░  SHIPPING AGENTS  ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

I build **autonomous LLM systems**: agents that plan, retrieve, call tools, write code, run tests and open pull requests, with no hand-holding.

My focus is taking agentic systems from *research prototype* to *deployed product*, backed by a foundation in deep learning, NLP and computer vision.

---

# ⚡ `currently.log`

| 🔭 Now | 🧪 Researching | 🤝 Open to |
|:---|:---|:---|
| **Sherlock.ai**: ML datasets & detection for deepfake / AI-assisted-cheating detection in remote interviews | **SpazorLabs**: quantum-enhanced ML, variational circuits, hybrid benchmarking | Agentic AI products, RAG & eval infra, LLM dev tools, hackathons, OSS |

---

# 🚀 `featured_projects`

## 🤖 Multi-Agent GitHub Issue Resolver

> Give it an issue. It reads the repo, plans a fix, writes code, writes tests, runs them in a sandbox and opens a PR.

```mermaid
flowchart LR
    A([📌 GitHub Issue]) --> B[🔍 Code Reader]
    B --> C[🧭 Planner]
    C --> D[⌨️ Code Writer]
    D --> E[🧪 Test Writer]
    E --> F{🐳 Sandbox<br/>tests pass?}
    F -- no, retry ≤ 3 --> C
    F -- yes --> G[🚀 PR Opener]
    G --> H([✅ Pull Request])
```

`LangGraph` `LangChain` `Gemini API` `PyGithub` `Docker`

- Five specialized agents sharing a **TypedDict state graph** with conditional edge routing
- **RAG-lite** codebase traversal + structured fix planning
- Progressive retries (up to 3), **circuit breaker**, cost tracking
- Generated code runs **only inside Docker**, never on the host
- **58 passing tests**

<p align="center">
  <a href="https://github.com/Satvik12221as/Github-Agent-System">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Satvik12221as&repo=Github-Agent-System&theme=tokyonight&hide_border=true" alt="Github Agent System"/>
  </a>
</p>

## ✍️ Autonomous Blog Writing Agent

> Topic in, researched, illustrated Markdown blog out. Zero human input.

```mermaid
flowchart LR
    T([📝 Topic]) --> R{🧭 Router}
    R -->|closed-book| P[📋 Planner]
    R -->|hybrid| P
    R -->|open-book + Tavily| P
    P --> W1[✍️ Worker 1]
    P --> W2[✍️ Worker 2]
    P --> W3[✍️ Worker N]
    W1 --> X[🧩 Reducer]
    W2 --> X
    W3 --> X
    X --> I[🎨 Gemini Images]
    I --> M([📄 Markdown Blog])
```

`LangGraph` `Groq` `Tavily` `Gemini API` `Streamlit`

- **Adaptive router** picks closed-book / hybrid / open-book based on topic recency & complexity
- **Fan-out / fan-in** parallel section writers, merged by a Reducer stage
- Images generated and embedded contextually, deployed on Streamlit

<p align="center">
  <a href="https://github.com/Satvik12221as/Blog-Writing-AI-Agent">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Satvik12221as&repo=Blog-Writing-AI-Agent&theme=tokyonight&hide_border=true" alt="Blog Writing AI Agent"/>
  </a>
</p>

## 🌐 Open Source and Product

<p align="center">
  <a href="https://github.com/Satvik12221as/hive">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Satvik12221as&repo=hive&theme=tokyonight&hide_border=true" alt="Hive"/>
  </a>
  <a href="https://github.com/Satvik12221as/medibridge">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Satvik12221as&repo=medibridge&theme=tokyonight&hide_border=true" alt="Medibridge"/>
  </a>
</p>

- **Hive** (Aden): YC-backed autonomous agent framework with 9.5k+ stars and 183 contributors. I contribute to agent tooling, issue resolution and framework improvements across the Python multi-agent runtime and SDK-wrapped node ecosystem.
- **Medibridge**: JavaScript product build focused on practical user flows and clean interface structure.

---

# 🧬 `tech_loadout`

### 🤖 Agentic AI and LLM
<p>
  <img src="https://img.shields.io/badge/LangGraph-0F172A?style=for-the-badge&logo=langchain&logoColor=22D3EE"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tavily-0F172A?style=for-the-badge&logoColor=22D3EE"/>
  <img src="https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge&logoColor=white"/>
</p>

### ⚔️ Languages, Backend and Cloud
<p>
  <img src="https://skillicons.dev/icons?i=python,ts,js,cpp,fastapi,flask,django,postgres,firebase,docker,aws,vercel,git&theme=dark" alt="Languages, backend, cloud"/>
</p>

### 🧪 ML, Vision and Data
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,streamlit&theme=dark" alt="ML and vision"/>
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white"/>
  <img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white"/>
</p>

---

# 🏗️ `engineering_depth`

| 🧠 Agentic Systems | 🔎 RAG & LLM Pipelines |
|:---|:---|
| Multi-agent orchestration, ReAct / MRKL reasoning, stateful workflow graphs, conditional routing, fan-out execution, agent memory, retry loops, circuit breakers | Semantic search, retrieval routing, context composition, prompt engineering, structured outputs, vector stores (Pinecone, ChromaDB) |

| ⚙️ Backend & Delivery | 👁️ ML, CV & Audio |
|:---|:---|
| FastAPI, Flask, Django, REST, SQLAlchemy, PostgreSQL, Docker, AWS EC2/S3, Render, Vercel, Swagger | CNNs, Transformers, RNNs, OpenCV, segmentation, video/audio signal analysis, deepfake detection, model evaluation |

---

# 🛣️ `experience.log`

```text
2026-06 → 2026-08   AI Research Intern        Sherlock.ai    deepfake / proxy-candidate detection datasets
2026-03 → present   Open Source Contributor   Aden Hive      YC-backed autonomous agent framework
2025-11 → 2026-01   Research & Tech Intern    SpazorLabs     quantum-classical AI research
2025               Internship Selection       NIT Calicut    competitive national selection
```

---

# 📊 `developer_telemetry`

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Satvik12221as&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="Streak"/>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Satvik12221as&theme=tokyonight" width="100%" alt="Profile details"/>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Satvik12221as&theme=tokyonight" width="32%" alt="Repos per language"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Satvik12221as&theme=tokyonight" width="32%" alt="Stats"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Satvik12221as&theme=tokyonight&utcOffset=5.5" width="32%" alt="Productive time"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Satvik12221as&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Activity" width="100%" alt="Activity graph"/>
</p>

<p align="center">
  <img src="https://github.com/Satvik12221as/Satvik12221as/raw/output/github-snake-dark.svg" alt="Contribution snake"/>
</p>

---

# 🌐 `open_connection()`

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=1800&pause=600&color=A78BFA&center=true&vCenter=true&width=800&lines=Building+an+agentic+product%3F;Need+RAG+or+LLM+eval+infra%3F;Got+a+wild+automation+idea%3F;Let's+ship+it." alt="Connect"/>
</p>

<p align="center">
  <a href="mailto:ss7225@srmist.edu.in"><b>✉️ Build with me</b></a> ·
  <a href="https://www.linkedin.com/in/satvik1221"><b>🔗 LinkedIn</b></a> ·
  <a href="https://github.com/Satvik12221as?tab=repositories"><b>📦 Repositories</b></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=130&color=0:0F172A,50:22D3EE,100:A78BFA&section=footer&animation=twinkling" width="100%" alt="Footer"/>
</p>

<p align="center">
  <b>PLAN → RETRIEVE → CODE → TEST → SHIP → REPEAT</b><br/>
  <sub>Still building. Still learning. Still shipping.</sub>
</p>
