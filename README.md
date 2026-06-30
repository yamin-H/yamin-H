<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=220&section=header&text=Yamin%20Hossain&fontSize=62&fontColor=ffffff&fontAlignY=42&animation=fadeIn&desc=Full%20Stack%20%2B%20AI%20Engineer&descSize=20&descAlignY=62&descColor=58A6FF" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=620&lines=LangGraph+%7C+Multi-Agent+Systems+%7C+RAG;TypeScript+%7C+Node.js+%7C+Next.js+%7C+FastAPI;Building+AI+that+ships+to+production+%F0%9F%9A%80;Autonomous+agents+that+write+and+merge+PRs+%E2%9A%A1)](https://github.com/yamin-H)

<br/>

<p>
  <a href="https://www.linkedin.com/in/yamin-hossain-n/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/yamin-H">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://bug-reproducer-autonomous-ai-agent.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Project-22c55e?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

</div>

---

<img align="right" width="340" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yamin-H&layout=compact&theme=github_dark&hide_border=true&langs_count=8&card_width=320" />

### 👋 About Me

I'm a **Full Stack + AI Engineer** who builds systems that work — not just in demos, but in production.

I work across the full stack with **TypeScript, React, Next.js, and Node/Express**, backed by **PostgreSQL and Prisma**. On the AI side I design and ship **autonomous agents, LangGraph pipelines, and RAG architectures** wired into real infrastructure.

I think in schemas first, ship in Docker, and treat *deployed and working* as the only finish line that matters.

- 🤖 Currently building autonomous AI agents with **LangGraph + Groq**
- 🏗️ Focused on **multi-service backends** with real-time streaming & job queues
- 🌍 Open to **remote roles** at startups working on AI-integrated products
- 📬 Reach me at **[LinkedIn](https://www.linkedin.com/in/yamin-hossain-n/)**

<br clear="right"/>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Bug Reproducer — Autonomous AI Agent

An autonomous agent that ingests a GitHub issue URL and — with **zero human input** — reproduces the bug, writes a failing test, generates a fix, and opens a Pull Request.

Built as a **7-node LangGraph pipeline** with conditional retry loops: if the generated test fails for the wrong reason, the agent captures the error, feeds it back as context, and rewrites automatically.

**Architecture highlights:**
- Python FastAPI service owns all agent execution
- Node.js + BullMQ handles job orchestration
- Redis pub/sub + SSE streams live logs to browser
- PostgreSQL + Prisma persists all results

<p>
  <img src="https://img.shields.io/badge/LangGraph-FF6B35?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/BullMQ-FF0000?style=flat-square&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
</p>

[![Live Demo](https://img.shields.io/badge/Live%20Demo-22c55e?style=for-the-badge&logo=vercel&logoColor=white)](https://bug-reproducer-autonomous-ai-agent.vercel.app/)
[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yamin-H/Bug-Reproducer-Autonomous-AI-Agent)

</td>
<td width="50%" valign="top">

### 📊 NL Data Analyst — Natural Language to SQL

An AI application that **removes the SQL barrier from data analysis entirely**. Upload a CSV or Excel file, ask a question in plain English, and get back a SQL-generated result, a human-readable summary, and an auto-generated chart — in seconds.

The LangChain + Groq pipeline generates and executes SQL against real data via Pandas. The FastAPI backend uses a **strict service-based architecture** — each pipeline stage (parsing → SQL gen → execution → summarization → charting) has its own dedicated module.

**Architecture highlights:**
- LangChain + LLaMA 3 70B for query generation
- Pandas for in-memory SQL execution
- Matplotlib for auto-generated chart output
- Next.js + Zustand frontend with file upload UX

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zustand-764ABC?style=flat-square&logoColor=white"/>
</p>

[![Live Demo](https://img.shields.io/badge/Live%20Demo-22c55e?style=for-the-badge&logo=vercel&logoColor=white)](https://nl-data-analyst.vercel.app/)
[![Repository](https://img.shields.io/badge/Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yamin-H/nl-data-analyst)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=ts,js,react,nextjs,tailwind,html,css&perline=8)](https://skillicons.dev)

**Backend & Database**

[![Backend](https://skillicons.dev/icons?i=nodejs,express,postgres,prisma,redis,docker,nginx&perline=8)](https://skillicons.dev)

**AI Engineering**

<img src="https://skillicons.dev/icons?i=python,fastapi" height="48"/>
<img src="https://raw.githubusercontent.com/yamin-H/yamin-H/main/icons/langchain.svg" height="48" title="LangChain"/>
<img src="https://raw.githubusercontent.com/yamin-H/yamin-H/main/icons/langgraph.svg" height="48" title="LangGraph"/>
<img src="https://raw.githubusercontent.com/yamin-H/yamin-H/main/icons/rag.svg" height="48" title="RAG"/>
<img src="https://raw.githubusercontent.com/yamin-H/yamin-H/main/icons/agents.svg" height="48" title="AI Agents"/>
<img src="https://raw.githubusercontent.com/yamin-H/yamin-H/main/icons/groq.svg" height="48" title="Groq"/>

**Tools & Infrastructure**

[![Tools](https://skillicons.dev/icons?i=linux,github,githubactions,vscode&perline=8)](https://skillicons.dev)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=yamin-H&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" />
&nbsp;&nbsp;
<img height="170" src="https://streak-stats.demolab.com?user=yamin-H&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />

</div>

<div align="center">

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=yamin-H&theme=github-compact&hide_border=true&area=true&color=58A6FF&line=58A6FF&point=FFFFFF" />

</div>

---

<div align="center">

**Open to remote roles · AI-integrated products · Developer tooling · Real-time systems**

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yamin-hossain-n/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/>

</div>

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yamin-hossain-n/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/>

</div>

