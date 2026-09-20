<h1 align="center">Hi 👋, I'm Om Jaiswal</h1>
<h3 align="center">AI Engineer · Agentic AI · RAG · Full-Stack</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&pause=1000&center=true&width=650&lines=Agentic+AI+%7C+RAG+%7C+MCP+%7C+LangGraph;Hybrid+Retrieval+%2B+Reranking+%2B+Evals;Production+AI+for+10%2C000%2B+real+cases;FastAPI+%7C+React+%7C+AWS+%7C+pgvector" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/omjaiswal45/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:omjai11022000@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://leetcode.com/u/jaiswal45/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
  <img src="https://komarev.com/ghpvc/?username=omjaiswal45&label=Profile%20views&color=6929C4&style=for-the-badge" />
</p>

---

## 👨‍💻 About Me

AI Engineer with **2.3+ years** building agentic AI, RAG and full-stack systems that hold up in production.

- 🧠 Built the **AI layer of a live internal CRM** serving **10,000+ vehicle-transfer cases** for **8,000+ customers**
- 🔍 Semantic case search: **5–10 min of manual lookup → under 1 second**
- 📈 Lifted end-to-end **RAGAS score from 0.60 → 0.93** with better chunking + cross-encoder reranking
- 🛡️ Ship behind **eval harnesses, guardrails and shadow-mode promotion gates**
- 🏗️ Own the full stack: async FastAPI on AWS → React / TypeScript / React Native

---

## 🏗️ How I Build AI Systems

```mermaid
flowchart LR
    U[User / Ops Team] --> A[ReAct Agent<br/>LangGraph state machine]
    A -->|MCP tools| S[Case Search<br/>pgvector]
    A -->|MCP tools| P[Policy RAG<br/>Hybrid BM25 + Dense]
    P --> R[Cross-Encoder<br/>Reranker]
    S --> A
    R --> A
    A --> G{Guardrails +<br/>Human Approval}
    G --> O[Answer / Action]
    O -.-> E[(RAGAS · Langfuse<br/>Shadow-mode evals)]
```

---

## 🛠️ Tech Stack

<details open>
<summary><b>🤖 Agentic & LLM</b></summary>
<br/>

![LangGraph](https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7C3AED?style=flat-square)
![CrewAI](https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![A2A](https://img.shields.io/badge/A2A-4285F4?style=flat-square)
![Claude](https://img.shields.io/badge/Anthropic_Claude-D97757?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

ReAct tool-calling loops · agent state machines · structured outputs · guardrails · human-in-the-loop escalation · prompt engineering
</details>

<details open>
<summary><b>🔎 RAG & Retrieval</b></summary>
<br/>

![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![Cohere Rerank](https://img.shields.io/badge/Cohere_Rerank-39594D?style=flat-square)

Hybrid search (dense + BM25) · chunking strategies · cross-encoder reranking · semantic-layer RAG · NL2Query · embeddings
</details>

<details open>
<summary><b>📊 Evals, Observability & MLOps</b></summary>
<br/>

![RAGAS](https://img.shields.io/badge/RAGAS-00897B?style=flat-square)
![DeepEval](https://img.shields.io/badge/DeepEval-6929C4?style=flat-square)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square)
![Langfuse](https://img.shields.io/badge/Langfuse-E11D48?style=flat-square)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![W&B](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

Gold datasets · faithfulness / context precision / recall scoring · regression tracking · shadow-mode evaluation
</details>

<details>
<summary><b>⚙️ Backend, Full-Stack & Cloud</b></summary>
<br/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" width="32"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" width="32"/>

Django · Express · REST / GraphQL · React Native · Expo · AWS (EC2, S3, Lambda, RDS, SageMaker) · GCP · Modal · RunPod
</details>

<details>
<summary><b>🧪 ML, CV & Data</b></summary>
<br/>

PyTorch · TensorFlow · scikit-learn · XGBoost · LightGBM · Hugging Face · ViT · YOLO · OpenCV · MediaPipe · OCR · INT8/PTQ quantization · ExecuTorch · Airflow · Spark · dbt · Metabase
</details>

<details>
<summary><b>🤝 Automation</b></summary>
<br/>

n8n · Gumloop · Make · Power Automate · Playwright · Puppeteer · Scrapy · Selenium
</details>

---

## 🌟 Featured Projects

| Project | What it does | Stack | Link |
|---|---|---|---|
| 🤖 **Inbox Agent** | Multi-tenant LangGraph agent over Gmail & Calendar. Defense-in-depth guardrails (prompt-injection tagging, recipient re-verification before send), human-approval node, 13-case eval harness gating CI on safety violations | Python · FastAPI · LangGraph · Groq · MongoDB · OAuth 2.0 | [GitHub](https://github.com/omjaiswal45/MailCalendarAgent) |
| 🗄️ **QueryPilot** | Enterprise Text-to-SQL copilot. Multi-agent LangGraph pipeline; pgvector schema-retrieval narrows a 500-table / ~25k-column DB to the relevant tables per question; sqlglot validates SQL safety | FastAPI · PostgreSQL · pgvector · LangGraph · Claude API · sqlglot | [GitHub](https://github.com/omjaiswal45) |
| 🧠 **Syntrix-AI** | Production-grade multi-agent platform: agents plan, call tools, critique and synthesize, with a full RAG pipeline | FastAPI · LangGraph · LangChain · Qdrant · Redis · Celery · WebSockets · Docker | [GitHub](https://github.com/omjaiswal45/Syntrix-AI-platform) |
| 🎓 **CollegeHuntin** | Live college-discovery startup platform with streaming AI chatbot (Groq LLaMA 3.3 70B), JWT auth, admin routes | Node.js · React · Next.js · MongoDB · Groq · LangGraph | [Live](https://www.collegehuntin.com/) |
| 🎥 **VideoTube** | YouTube clone, infinite scroll, nested comments | React · Tailwind · Redux | [Live](https://video-tube-orpin.vercel.app/) |
| 💬 **VaaniSetu** | Real-time chat, online presence, Socket.io | MERN · Socket.io · Zustand | [Live](https://chat-app-qjn5.onrender.com/) |

<details>
<summary>More projects</summary>

| Project | Stack | Link |
|---|---|---|
| 📋 **ProjectPilot**: task manager, JWT, Google Auth, email alerts | MERN · Redux Toolkit · Nodemailer | [Live](https://project-pilot-om-jaiswals-projects-56697ee4.vercel.app/) |
| 📄 **CertiSure**: certificate generator with PWA | MERN · JWT | [Live](https://certisure.vercel.app/) |
</details>

---

## 💼 Experience

<details open>
<summary><b>Software Engineer (AI/ML Specialist), Car Wizard Pvt. Ltd. (VahanHelp)</b> · May 2024 – Aug 2026</summary>
<br/>

- Owned the **AI layer of the internal CRM**: agent runtimes, retrieval, evals and deployment, used by ops/support to process **10,000+ RC-transfer cases** for **8,000+ customers and dealers**
- Built **semantic case-similarity search** (OpenAI `text-embedding-3-small` → PostgreSQL/pgvector behind FastAPI): closest past cases in **<1s vs 5–10 min** of manual MongoDB lookup
- Shipped a **conversational RAG policy assistant** (RTO transfer rules + SOPs) via ReAct tool-calling agents and LangGraph state machines, exposed as **MCP tools**
- Fixed an underperforming retrieval layer with advanced chunking + cross-encoder reranking: **RAGAS 0.60 → 0.93**
- Built **ParivahanMitra CRM** (RBAC, BullMQ jobs, SLA-based routing, real-time React dashboards) and cut a slow query from **60s+ → under 2s** with compound indexes
- Owned architecture and AWS EC2 deployment of the live **VahanHelp Play Store app** (React Native, OTP auth, Razorpay)
</details>

<details>
<summary><b>AI/ML Intern, DigiLocker</b> · Mar 2024 – May 2024</summary>
<br/>

- Facial spoof-detection classifier via transfer learning: **96.4% accuracy**
- Anti-spoofing system (texture + depth cues): **EER under 2.5%** against photo/video/mask attacks
</details>

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=omjaiswal45&show_icons=true&theme=radical&hide_border=true" />
  <img height="170" src="https://streak-stats.demolab.com?user=omjaiswal45&theme=radical&hide_border=true" />
</p>
<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omjaiswal45&layout=compact&theme=radical&hide_border=true" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=omjaiswal45&theme=tokyo-night&hide_border=true" width="95%" />
</p>

---

## 🏆 Achievements

- 🥇 **National Finalist, KAVACH Cybersecurity Hackathon 2023** (Ministry of Education, GoI): phishing detection
- 🧩 **CodeChef max rating 1900+**, 250+ DSA problems on LeetCode/GeeksforGeeks
- 🚀 Multiple production apps live: VahanHelp (Play Store), CollegeHuntin, Syntrix-AI
- 🎓 B.Tech, Bundelkhand Institute of Engineering and Technology (2020–2024)

---

## 📫 Let's Connect

Open to **AI Engineer / Agentic AI / RAG** roles. Reach me at [omjai11022000@gmail.com](mailto:omjai11022000@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/omjaiswal45/).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=90&section=footer" /></p>
