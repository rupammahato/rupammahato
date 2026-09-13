<div align="center">

# Rupam Mahato

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=0E75B6&center=true&vCenter=true&random=false&width=600&lines=Backend+%26+AI+Systems;RAG+pipelines+and+distributed+systems;IIT+Kharagpur+Dual+Degree" alt="Typing SVG" />

<img src="https://komarev.com/ghpvc/?username=rupammahato&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="profile views" />

</div>

## About

Dual degree student at IIT Kharagpur (B.Tech Civil, M.Tech Environmental Engineering) who spends most of his time writing backend and AI infrastructure. Recent work: multi-tenant RAG corpora, an org-hierarchy access layer, agentic marketing pipelines, and a consistent-hashing load balancer built from scratch.

- Currently: scalable RAG pipelines, and drafting an open-source proposal for the Internet Archive (GSoC 2026)
- Reading into: knowledge graphs, document parsing, and FastAPI orchestration under load
- Reach me: rupammahato593@gmail.com

## Experience

| | | |
|---|---|---|
| **Neosophical Labs** | Full Stack Developer Intern | May 2026 – Jul 2026 |
| **Datsol Solutions** (client: Posterity Consulting) | Full Stack Developer Intern | Nov 2025 – May 2026 |
| **10X Analysts** | Backend Engineering Intern | May 2025 – Jul 2025 |
| **Zyke** | Founding Member | Oct 2024 – Jan 2025 |

Agentic marketing digests and a UK payroll SLA engine at Neosophical. Sole author of the hiring pipeline and org-hierarchy access control on a 360-feedback HR platform at Datsol. Knowledge-base APIs over a pgvector RAG corpus, plus a cross-origin session auth rebuild across 95 endpoints, at 10X.

## Projects

### Consistent Hashing Load Balancer

An HTTP load balancer built on Express with a hash ring written from scratch.

- 32-bit MD5 keyspace with weighted virtual nodes and `O(log R)` binary-search lookup
- Node failure remaps 19.66% of keys, against roughly 80% for naive modulo hashing
- Health checker evicts a backend after 3 failed polls and re-adds it on recovery
- Two coordinator-free instances run behind nginx via Docker Compose
- Tracked down a proxy regression by benchmarking direct against proxied load: a single keep-alive agent took p99 latency from 2,459ms to 1.6ms and errors from 3.7% to zero

`Node` · `Express` · `Docker Compose` · `nginx` · `Prometheus`

### Zyke — AI content automation

Founding member on a three-person team. An agent read a brand's website, ranked live trends against that voice, and produced finished social posts with editable images.

- Metered per-request AI spend across 7 providers, modelling each pricing scheme so a generation debits a USD balance. Finished cost landed at $0.05 a post
- The money path end-to-end: Razorpay orders, HMAC webhook verification, replay-safe idempotency, atomic credit increments
- An async onboarding crawler that learned 4 brand voices from a URL alone, with semaphore-bounded concurrency and Retry-After backoff
- One live trend produced 3 ideas, 9 posts and 13 images in 4 minutes

Archived. Ran on $50k+ in platform credits and never took cash revenue. Write-up and demo: [zyke.in](https://zyke.in/)

`Flask` · `MongoDB` · `Razorpay` · `FLUX 1.1 Pro` · `o1-mini`

### Megalith 2025 — IIT Kharagpur

The website for Megalith, the civil engineering technical fest at IIT Kharagpur.

- Next.js/TypeScript, 42.7% year-over-year user growth, 5K+ concurrent at peak
- JWT/bcrypt role-based auth, running `jose` in Edge Middleware where Node crypto is unavailable, on MongoDB/Mongoose
- Recharts admin dashboard over Mongo aggregations, automating Razorpay orders, pdf-lib certificates and Nodemailer mail

`Next.js` · `TypeScript` · `MongoDB` · `Razorpay`

### Membition — NGO chatbot platform

Client work. Three services that take a nonprofit from a 7-step intake form and one PDF to a live hosted chatbot in a single request.

- Every nonprofit gets its own dedicated Pinecone index
- PDFs chunked at 2,000 characters with 100 overlap, embedded with `text-embedding-3-large`, upserted in batches of 100
- The `gpt-4o-mini` prompt is scoped to nonprofit context by 13 rules, refusing off-topic queries with each org's own fallback message

`Next.js` · `Flask` · `Pinecone` · `OpenAI` · `Streamlit`

## Stack

**Languages** Python · C++ · JavaScript · TypeScript · SQL

**Backend** Node · Express · FastAPI · Django · Flask

**Data** PostgreSQL · MongoDB · pgvector · Pinecone · Neo4j

**AI** RAG · LangChain · LangGraph · LlamaIndex · OpenAI API

**Infra** AWS · GCP · Docker · nginx · GitHub Actions

**Frontend** Next.js · React · Redux · Tailwind · D3.js · Recharts

## Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=rupammahato&theme=tokyonight" alt="GitHub Streak" />

<img src="https://github-readme-stats.vercel.app/api?username=rupammahato&show_icons=true&theme=tokyonight" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rupammahato&layout=compact&theme=tokyonight" alt="Top Languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rupammahato&theme=react-dark" alt="GitHub Activity Graph" />

</div>

## Elsewhere

<div align="center">

<a href="https://linkedin.com/in/rupammahato"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://codeforces.com/profile/DarkKnight05"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
<a href="https://leetcode.com/u/DarkKnight_05"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
<a href="https://stackoverflow.com/users/22391033/rupam-mahato"><img src="https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stackoverflow&logoColor=white" alt="Stack Overflow" /></a>
<a href="https://twitter.com/rupam593"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white" alt="Twitter" /></a>

</div>
