<h1 align="center">Hi 👋, I'm Sagar Rajak</h1>
<h3 align="center">
Agentic AI Engineer | AI Backend Engineer <br>
B.E. in Artificial Intelligence & Data Science, VESIT Mumbai (Class of 2026, CGPA 9.14) <br>
I build production multi-agent systems, voice AI and event-driven backends that ship to real customers.
</h3>

<p align="center">
<img src="https://komarev.com/ghpvc/?username=sagarrajak245&label=Profile%20views&color=0e75b6&style=flat" alt="sagarrajak245" />
</p>

---

- 🎓 **Graduated in May 2026** from **Vivekanand Education Society's Institute of Technology (VESIT), Mumbai** with a B.E. in **AI & Data Science** (CGPA **9.14/10**)
- 🚀 Currently a **Founding Agentic AI Engineer at [Aiviue](#-experience)**, building an AI-powered, video-led hiring platform
- 🧠 Working on **LangGraph, multi-agent systems, voice AI (STT/TTS + telephony), RAG, LLM evals and guardrails**
- ⚙️ Backend focus: **FastAPI, PostgreSQL, Redis Streams, event-driven & distributed systems**
- 👯 Open to collaborating on **Agentic AI, LLM infrastructure and open-source projects**
- 📫 Reach me at **[sagarrajak245@gmail.com](mailto:sagarrajak245@gmail.com)**
- 🌐 **Portfolio:** [portfolio-2-sagar-rajak.vercel.app](https://portfolio-2-sagar-rajak.vercel.app/)
- ⚡ Fun fact: **I'm great at GK, cricket, and have a bit of MMA & boxing skills**

---

## 💼 Experience

**Aiviue (Founding Team)** – *Agentic AI Engineer* (Nov 2025 – Present)
- Owned ~90% of the MVP codebase end to end (architecture, backend infra, agentic workflows); the product landed **Hitachi, Orange Antelopes and Tapplent** as paying clients
- Designed an event-driven backend on **FastAPI, PostgreSQL and Redis Streams** with idempotent consumers, dead-letter queues and transactional ACKs: **zero data-loss incidents** in production
- Built a **multi-agent control plane of 6 specialised agents** (Admin, Spend, Profitability, Warning, Broadcast, BulkOps) for cost attribution, anomaly detection and automated corrective workflows
- Engineered a **multi-channel SDR automation** pipeline (LinkedIn, Email, WhatsApp) with AI lead enrichment, cutting manual marketing effort by ~60%
- Replaced third-party voice orchestration with an **in-house voice AI stack**: multilingual STT/TTS, LangGraph agent workflows and real-time telephony, with provider-agnostic, fault-tolerant execution

**Kinzy Club Pvt Ltd (Subsidiary of Redscope Inc.)** – *Backend Engineer* (Nov 2024 – Feb 2025)
- Built secure JWT authentication with Java & Spring Boot for high-traffic APIs
- Removed sequential scans on 42 hot queries with targeted indexes: **10 ms → 2 ms (5x faster)**
- Developed a Redis-backed feed system and distributed scheduling with Spring Scheduler + ShedLock

**AI-Colegion, VESIT** – *Technical Officer* (Aug 2023 – May 2026)
- Led 3 MERN-stack projects and trained **350+ students** through Flutter, Machine Learning and Agentic AI (CrewAI) workshops

---

## 🚀 Featured Projects

### [Rappi Turbo – AI Purchasing Agent](https://github.com/sagarrajak245/rappi-turbo-solution) · [Live](https://rappi-web.onrender.com)
`LangGraph` `FastAPI` `Next.js` `Groq` `Gemini`
Human-in-the-loop purchasing agent that reviews replenishment recommendations, decides to ACCEPT / MODIFY / REJECT / ESCALATE with grounded reasons, and places ERP orders only after buyer approval. A deterministic planner enforces budget, storage, shelf-life and MOQ limits; idempotent ERP writes with read-back verification, prompt-injection filtering, Groq→Gemini fallback and a buyer-feedback learning loop. **Eval harness: 25/25 scenarios, 308 tests, 0 hard-limit violations.**

### [Argus – Self-hosted Gmail Open & Click Tracker](https://github.com/sagarrajak245/Argus)
`TypeScript` `Chrome MV3` `Cloudflare Workers` `D1`
A free, Streak-style tracker for Gmail: see who opened your email, when and how often, and which links they clicked. Sent-list badges, a thread sidebar, desktop notifications and link-click tracking, with all data in your own Cloudflare account at **$0/month**.

### [IntelliClaim – Multi-Agent Insurance Adjudication](https://github.com/sagarrajak245/IntelliClaim-A-Multi-Agent-AI-System-for-Insurance-Adjudication)
`CrewAI` `LangChain` `RAG` `ChromaDB` `Flask` `React`
Full-stack multi-agent system that automates insurance claim adjudication, cutting processing time from 30–60 minutes to under 3 minutes. RAG over policy documents, Groq LLM reasoning and a live Socket.io dashboard with explainable decisions.

### [MediSuite AI – Multi-Agent Medical Claims System](https://github.com/sagarrajak245/medi-suite_AI)
`Python` `Multi-Agent` `OCR` `LLMs`
An agent pipeline (OCR, Clinical, Coding, Claim, Validator and Monitor agents) that turns raw medical records into structured insurance claims and billing data such as CMS-1500, UB-04 and 837 EDI.

### [Real-time WebRTC Multi-Object Detection](https://github.com/sagarrajak245/Real-time-WebRTC-VLM-Multi-Object-Detection)
`WebRTC` `YOLOv8` `ONNX (WASM)` `FastAPI` `Docker`
Streams video from a phone over WebRTC and overlays YOLOv8 detections in the browser, with in-browser WASM and server inference modes: **<100 ms latency** in server mode and 10–30 FPS.

### More projects
- [Postify](https://github.com/sagarrajak245/postify_chrome_extension) – AI Chrome extension that turns certificates in Gmail into LinkedIn/Twitter posts
- [Financial Fraud Detection](https://github.com/sagarrajak245/Fraud_transaction_detection_in_payment_app) – XGBoost + SMOTE + SHAP on 6.3M+ transactions
- [Player Tracking & Re-identification](https://github.com/sagarrajak245/computer_vision_project) – YOLOv8 with DeepSORT/StrongSORT for sports analytics
- [CrewAI Multi-Agent System](https://github.com/sagarrajak245/crewai_project) – Researcher, Writer and Editor agents for content workflows

---

## 🛠️ Tech Stack

| Area | Tools |
|---|---|
| **Languages** | Python, Java, JavaScript, TypeScript, SQL, C/C++ |
| **Agentic AI** | LangChain, LangGraph, CrewAI, MCP, Multi-Agent Systems, RAG, Tool Calling, Context Engineering |
| **LLM Engineering** | Prompt Caching, Token Economics, LLM Evals, Guardrails, Fine-tuning |
| **Observability** | LangFuse, Prometheus, Grafana |
| **Machine Learning** | PyTorch, Scikit-learn, CNN, RNN, Transformers |
| **Backend & Infra** | FastAPI, Spring Boot, Redis / Redis Streams, Docker, GitHub Actions, Jenkins, Event-Driven Architecture |
| **Cloud** | AWS (EC2, S3, Lambda), Cloudflare Workers |
| **Databases** | PostgreSQL, MongoDB, ChromaDB, pgvector |
| **Frontend** | React.js, Next.js, Tailwind CSS |

<p align="left">
<a href="https://www.python.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/></a>
<a href="https://www.java.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="40" height="40"/></a>
<a href="https://www.typescriptlang.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="40" height="40"/></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40"/></a>
<a href="https://www.w3schools.com/cpp/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" height="40"/></a>
<a href="https://fastapi.tiangolo.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" width="40" height="40"/></a>
<a href="https://spring.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" width="40" height="40"/></a>
<a href="https://pytorch.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40" height="40"/></a>
<a href="https://scikit-learn.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40"/></a>
<a href="https://www.postgresql.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" height="40"/></a>
<a href="https://www.mongodb.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="40" height="40"/></a>
<a href="https://redis.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="40" height="40"/></a>
<a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40"/></a>
<a href="https://aws.amazon.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="40" height="40"/></a>
<a href="https://www.jenkins.io/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jenkins/jenkins-original.svg" width="40" height="40"/></a>
<a href="https://grafana.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/grafana/grafana-original.svg" width="40" height="40"/></a>
<a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40" height="40"/></a>
<a href="https://nextjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="40" height="40"/></a>
<a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" width="40" height="40"/></a>
</p>

---

## 🏆 Certifications & Awards
- **Certifications:** NVIDIA Fundamentals of Deep Learning · AWS Cloud Fundamentals · Web Development (Udemy) · Flutter Fundamentals (Udemy)
- **Awards:** Best Technical Speaker – Awakening the Scientist · Dalal Street Finalist (Trade Game)

---

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/sagar-rajak" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="sagar rajak" height="30" width="40" /></a>
<a href="https://twitter.com/sagar00043" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="sagar00043" height="30" width="40" /></a>
<a href="https://www.leetcode.com/sagarrajak245" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="sagarrajak245" height="30" width="40" /></a>
<a href="https://instagram.com/sagarrajak003" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="sagarrajak003" height="30" width="40" /></a>
<a href="https://fb.com/sagarrajak003" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="sagarrajak003" height="30" width="40" /></a>
</p>
