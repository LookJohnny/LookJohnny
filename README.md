<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Johnny%20Liu&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=I%20give%20AI%20a%20body.&descAlignY=60&descSize=20" width="100%"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=8ECAE6&center=true&vCenter=true&width=720&lines=Physical+AI+%7C+Embodied+Agents+%7C+AI+Toys;LLM+%E2%86%92+3D+Avatar+%E2%86%92+Servos+%E2%86%92+Silicone+Face;Founder+%40+SoulForge+%C2%B7+Running+a+plush+factory+on+AI;USC+MS+CS+%C2%B7+RecSys+%C2%B7+Full-stack" alt="Typing SVG" /></a>

<br/>

[![Visitors](https://komarev.com/ghpvc/?username=LookJohnny&style=for-the-badge&color=8ECAE6)](https://github.com/LookJohnny)
[![Website](https://img.shields.io/badge/lovelyjoy.cn-live-DDB892?style=for-the-badge&logo=vercel&logoColor=black)](https://lovelyjoy.cn)
[![Location](https://img.shields.io/badge/LA%20%E2%86%94%20Yiwu-🌏-2c5364?style=for-the-badge)](#)

</div>

---

## 🧠 Who I am

**AI engineer, hardware tinkerer, and founder.** USC M.S. in Computer Science — but most of my learning happens in the loop between a terminal, a soldering iron, and a factory floor.

I run **[SoulForge](https://github.com/LookJohnny/soulForge)** — a *soul-injection platform* that turns any object (a VRM avatar on a screen, an ESP32 toy, a 17-servo silicone face) into a character with a persistent personality, memory and emotions. In parallel I'm digitizing a real plush-toy factory (LovelyJoy / 爱儿采) with LLMs, computer vision and MES integrations — so every idea gets tested against real users, real machines and real margins.

```text
 LLM ──▶ Planner (3-tier + event replanning) ──▶ PAD emotion ──▶ Body
                                                                  ├── three.js / VRM avatar   (web · Tauri)
                                                                  ├── ESP32 voice toy  (小智)  (WebSocket · TTS/ASR)
                                                                  └── MG90S×17 silicone face  (PCA9685 · ESP8266)
```

---

## 🚀 What I'm building

| Project | One-liner | Stack |
|---|---|---|
| **[SoulForge](https://github.com/LookJohnny/soulForge)** | AI-toy soul engine: `.soul` packs, multi-agent conversations (turn-taking, memory, relationships), latency observability, Unity/MuJoCo sims | Python 3.12 · FastAPI · WebSocket · Prisma · pnpm/turbo monorepo · Docker |
| **[Soul_Forge Physical](https://github.com/LookJohnny/Soul_Forge)** | Physical AI system — robot face with self-supervised expression learning (Eva-paper reproduction, real silicone deformation, no screens) | ESP8266/ESP32 · PCA9685 · PyTorch · MuJoCo |
| **[lovelyjoy.cn](https://github.com/LookJohnny/lovelyjoy-website)** | 14-language B2B factory site with a 3D VRM brand ambassador that talks (plan-then-infill gesture animation, LLM + Edge TTS, Feishu CRM) | Next.js 16 · React 19 · three-vrm · next-intl · Tailwind v4 · Vercel |
| **[plush-cost](https://github.com/LookJohnny/plush-cost)** | Vision-based manufacturing cost estimator — image → materials/labor → quote; 700+ real cases, LOO error ~14% | Python · CV · scikit-learn · Docker |
| **Blacklake MES × Feishu** | Reverse-engineered internal APIs, 6 sync pipelines, webhooks, auto reports for a live factory | Python · REST · cron · Feishu Bitable |
| **[yuelao-match](https://github.com/LookJohnny)** | Two-sided matchmaking scoring engine → B2B matchmaker workbench | FastAPI · Neon Postgres · Vercel |
| **[OTTO RecSys](https://github.com/LookJohnny/OTTO-Multi-Objective-Recommendation-System)** | Multi-objective session recommendation (clicks / carts / orders) | PyTorch · Pandas · Kaggle |

---

## 🛠 Tech stack

<details open>
<summary><b>🤖 AI / Agents</b></summary>
<br>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenAI-compatible LLMs](https://img.shields.io/badge/LLM%20APIs-DeepSeek·Qwen·Claude-412991?style=for-the-badge&logo=openai&logoColor=white)
![Agents](https://img.shields.io/badge/Multi--Agent-Planner·Memory·PAD-8ECAE6?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Embeddings·Vector-DDB892?style=for-the-badge)
![TTS/ASR](https://img.shields.io/badge/Voice-Edge%20TTS·Fish%20Audio·ASR-6C63FF?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-Sim-000000?style=for-the-badge)
![Claude Code](https://img.shields.io/badge/Claude%20Code-Agentic%20Dev-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
</details>

<details open>
<summary><b>🦾 Hardware / Embodied</b></summary>
<br>

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-000000?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Servos](https://img.shields.io/badge/PCA9685·MG90S-Servo%20Control-2c5364?style=for-the-badge)
![Unity](https://img.shields.io/badge/Unity-URP-000000?style=for-the-badge&logo=unity&logoColor=white)
![VRM](https://img.shields.io/badge/VRM·three.js-3D%20Avatar-049EF4?style=for-the-badge&logo=three.js&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)
</details>

<details open>
<summary><b>🌐 Full-stack</b></summary>
<br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js%2016-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React%2019-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Java](https://img.shields.io/badge/Java·Spring-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
</details>

<details open>
<summary><b>☁️ Infra / Data</b></summary>
<br>

![PostgreSQL](https://img.shields.io/badge/PostgreSQL·Neon-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Spark](https://img.shields.io/badge/Spark·Kafka·Hadoop-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Feishu](https://img.shields.io/badge/Feishu%20Open%20API-3370FF?style=for-the-badge)
![SEO/GEO](https://img.shields.io/badge/SEO·GEO·i18n-14%20locales-DDB892?style=for-the-badge)
</details>

---

## 🧭 How I work

- **Ship to reality.** Every model I train has a customer, a servo, or a P&L waiting on the other end.
- **Own the whole stack.** Prompt → planner → API → 3D render → firmware → PCB wiring. No hand-offs.
- **Agentic development.** I build my own Claude Code skills (e.g. `wholesale-site-builder`: design mock-ups → multilingual B2B site → SEO/GEO → Vercel, in one run).
- **Bilingual, bicontinental.** Los Angeles ↔ Yiwu. Fluent in both "let's ship" and "让我们上线".

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=LookJohnny&show_icons=true&hide_border=true&theme=tokyonight&bg_color=00000000" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=LookJohnny&layout=compact&hide_border=true&theme=tokyonight&bg_color=00000000&hide=jinja,html,css,scss,tex,shell&langs_count=6" height="165" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=LookJohnny&theme=tokyo-night&hide_border=true&area=true" width="100%"/>

<br/>

**Building something at the intersection of AI × hardware × manufacturing? Let's talk.**

[![Email](https://img.shields.io/badge/Email-ly2217839211%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ly2217839211@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Johnny%20Liu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
