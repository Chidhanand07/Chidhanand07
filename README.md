<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F0C29,50:4C1D95,100:C9A227&height=220&section=header&text=Chidanandh%20R&fontSize=44&fontColor=F5E6C8&animation=fadeIn&fontAlignY=38&desc=AI%2FML%20Engineer%20%C2%B7%20Full-Stack%20Developer%20%C2%B7%20Autonomous%20Agents&descAlignY=58&descSize=17" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com/?font=Playfair+Display&weight=600&size=21&duration=3200&pause=900&color=D4AF37&center=true&vCenter=true&width=680&lines=I+build+AI+systems+that+don't+just+predict...;...they+decide%2C+act%2C+and+remember.;AI%2FML+Engineer+%2B+Full-Stack+Developer;Shipping+Phantom%2C+SENTINEL+%26+ShipIt" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://www.chidanandhr.space"><img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white"/></a>
<a href="https://www.chidanandhr.space/Chidanandh_Resume.pdf"><img src="https://img.shields.io/badge/Resume-8B5CF6?style=for-the-badge&logo=readdotcv&logoColor=white"/></a>
<a href="https://linkedin.com/in/chidanandh-r"><img src="https://img.shields.io/badge/LinkedIn-6D28D9?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://x.com/RChidhanand"><img src="https://img.shields.io/badge/X-2E1065?style=for-the-badge&logo=x&logoColor=white"/></a>
<a href="mailto:chidhanand07d@gmail.com"><img src="https://img.shields.io/badge/Email-4C1D95?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/Chidhanand07"><img src="https://img.shields.io/badge/GitHub-1A103D?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

## <img src="https://api.iconify.design/lucide/user-round.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;About

<div align="center">

*"I build AI systems that don't just predict — they decide, act, and remember."*

</div>

I develop end-to-end products spanning model logic to deployed infrastructure, with a focus on systems that maintain state, reason through decisions, act on them, and retain memory of those actions. I care about making AI reasoning transparent and explainable — particularly for trustworthiness in high-stakes domains. I built **Gambit**, a realtime multiplayer chess platform on a 3-service architecture, and **ToxiDerma-XAI**, an explainable deep-learning system for medical lesion detection. I am currently building **Phantom**, an autonomous LangGraph trading agent, **SENTINEL**, an autonomous e-commerce BI stack, and **ShipIt**, a Go deployment CLI — and I've solved 500+ DSA problems along the way.

```yaml
role:     AI/ML Engineer & Full-Stack Developer
focus:    [Autonomous Agents, Production Systems, Explainable AI]
open_to:  Entry-level AI/ML or Full-Stack Engineering roles
based_in: Bengaluru, India
```

---

## <img src="https://api.iconify.design/lucide/layers.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,go,ts,js,c,java&theme=dark" />

<br/>

**AI / ML**

<img src="https://img.shields.io/badge/LangGraph-6D28D9?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-6D28D9?style=flat-square&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-6D28D9?style=flat-square&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Grad--CAM-6D28D9?style=flat-square"/>
<img src="https://img.shields.io/badge/LIME-6D28D9?style=flat-square"/>
<img src="https://img.shields.io/badge/RAG-6D28D9?style=flat-square"/>
<img src="https://img.shields.io/badge/Claude%20API-6D28D9?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI%20API-6D28D9?style=flat-square&logo=openai&logoColor=white"/>

<br/><br/>

**Frontend**

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind&theme=dark" />

<br/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,express,socketio,postgres,supabase,redis&theme=dark" />

<br/>

**Infrastructure**

<img src="https://skillicons.dev/icons?i=docker,githubactions,vercel&theme=dark" />
<img src="https://img.shields.io/badge/Railway-4C1D95?style=flat-square&logo=railway&logoColor=white"/>
<img src="https://img.shields.io/badge/Render-4C1D95?style=flat-square&logo=render&logoColor=white"/>
<img src="https://img.shields.io/badge/GoReleaser-4C1D95?style=flat-square"/>

</div>

---

## <img src="https://api.iconify.design/lucide/folder-git-2.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;Featured Projects

### Phantom — Autonomous AI Trading Agent

Building a 6-node LangGraph agent (reason → risk → decide → narrate → remember → execute) to manage a virtual ₹1L NSE portfolio every 15 minutes during market hours, fusing pandas-ta technical signals with live news sentiment. A persistent trade-memory layer in Redis and PostgreSQL lets the agent write a thesis on every buy and reference it on exit — giving multi-session reasoning continuity most single-shot trading bots lack. Decisions stream to a Next.js dashboard over WebSocket in plain English, making agent reasoning auditable for non-technical users.

`Stack` LangGraph · LangChain · FastAPI · Next.js 14 · PostgreSQL · Redis · Docker · Claude API　·　`Repository` [Phantom](https://github.com/Chidhanand07/Phantom)

### Gambit — Production Chess Platform

A real-time multiplayer chess platform architected and deployed as 3 microservices (Vercel, Railway, Render), achieving sub-100ms move propagation via Socket.io and Supabase Realtime. A Stockfish-powered accuracy rating system scores both players 0–100 after each game via async webhook, persisting results to Supabase PostgreSQL. Includes smart matchmaking and a live friends system across a Next.js frontend, Node/Express/Socket.io game server, and a Python FastAPI engine.

`Stack` Next.js 14 · TypeScript · Node · Express · Socket.io · FastAPI · python-chess · Stockfish · Supabase · Vercel · Railway · Render　·　`Repository` [GAMBIT](https://github.com/Chidhanand07/GAMBIT)

### ToxiDerma-XAI — Explainable Medical Lesion Detection

Directed a 4-member team as Team Lead, co-building a transfer-learning pipeline (ResNet50 / EfficientNet) to detect arsenic-induced skin lesions. Integrated Grad-CAM and LIME so clinicians can see which image regions drive each prediction, and evaluated the model on accuracy, sensitivity/specificity, F1, and AUC-ROC.

`Stack` Python · TensorFlow · ResNet50 · EfficientNet · Grad-CAM · LIME · Flask · Transfer Learning　·　`Role` Team Lead, 4-member team　·　`Repository` [ToxiDerma](https://github.com/Chidhanand07/ToxiDerma)

---

## <img src="https://api.iconify.design/lucide/chart-column.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;Analytics

<div align="center">

<img src="https://gh-readme-stats.vercel.app/api?username=Chidhanand07&show_icons=true&theme=radical&hide_border=true&bg_color=0D0221&title_color=D4AF37&icon_color=A78BFA&text_color=E9D5FF" width="49%"/>
<img src="https://streak-stats.demolab.com/?user=Chidhanand07&theme=radical&hide_border=true&background=0D0221&ring=D4AF37&fire=D4AF37&currStreakLabel=D4AF37" width="49%"/>

<img src="https://gh-readme-stats.vercel.app/api/top-langs/?username=Chidhanand07&layout=compact&theme=radical&hide_border=true&bg_color=0D0221&title_color=D4AF37&text_color=E9D5FF" width="49%"/>

</div>

---

## <img src="https://api.iconify.design/lucide/trophy.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;Trophies

<div align="center">

<img src="https://github-trophies.vercel.app/?username=Chidhanand07&theme=radical&no-frame=true&no-bg=true&margin-w=8&row=1" />

</div>

---

## <img src="https://api.iconify.design/lucide/activity.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;Contribution Activity

<div align="center">

<img src="https://ghchart.rshah.org/8B5CF6/Chidhanand07" width="100%" alt="Chidanandh's contribution chart"/>

</div>

---

## <img src="https://api.iconify.design/lucide/calendar-days.svg?color=%23C9A227" width="22" align="center" alt=""/> &nbsp;Contribution Graph

<div align="center">

<img src="https://raw.githubusercontent.com/Chidhanand07/Chidhanand07/output/github-contribution-grid-snake-dark.svg" width="100%"/>

</div>

---

<div align="center">

*"Ship the reasoning, not just the code — make every agent's decision auditable."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C9A227,50:4C1D95,100:0F0C29&height=120&section=footer" width="100%"/>

</div>
