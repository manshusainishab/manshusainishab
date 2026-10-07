<div align="center">

# MANSHU SAINI

**Full-Stack & Backend Engineer.** Cloud-native backends, edge-native AI, and the open source plumbing in between.

<p>
  <a href="https://omnitrixporfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=vercel&logoColor=22C55E" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/manshusainishab"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logoColor=22C55E&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMDEtMi4wNjMtMi4wNjUgMi4wNjQgMi4wNjQgMCAxMTIuMDYzIDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjI1IDB6Ii8+PC9zdmc+" alt="LinkedIn" /></a>
  <a href="https://medium.com/@manshusainishab"><img src="https://img.shields.io/badge/Medium-0D1117?style=for-the-badge&logo=medium&logoColor=22C55E" alt="Medium" /></a>
  <a href="https://www.youtube.com/@ManshuNSTian"><img src="https://img.shields.io/badge/YouTube-0D1117?style=for-the-badge&logo=youtube&logoColor=22C55E" alt="YouTube" /></a>
  <a href="https://x.com/manshusainishab"><img src="https://img.shields.io/badge/Twitter-0D1117?style=for-the-badge&logo=x&logoColor=22C55E" alt="Twitter" /></a>
  <a href="https://www.instagram.com/my_nst_daze"><img src="https://img.shields.io/badge/Instagram-0D1117?style=for-the-badge&logo=instagram&logoColor=22C55E" alt="Instagram" /></a>
  <a href="mailto:manshupallav@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=22C55E" alt="Email" /></a>
</p>

<p>
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2600&pause=700&color=22C55E&center=true&vCenter=true&width=620&lines=GSoC+2026+%40+OWASP+OpenCRE;Running+LLMs+at+the+edge+with+zero+inbox+leakage;Forecasting+grid+load+with+ARIMA+%2B+deep+nets;In+a+race+to+try+everything+and+explore" alt="Typing SVG" />
  <br />
  <img src="https://komarev.com/ghpvc/?username=manshusainishab&label=Profile%20Views&color=22c55e&style=flat-square" alt="Profile Views" />
</p>

</div>

---

## About

I build full-stack applications where the backend is the hard part, and I like the hard part.

Right now that means a Google Summer of Code 2026 project at OWASP OpenCRE: a multi-stage ingestion filter that decides what security content is worth harvesting, from regex gates through an LLM relevance classifier, with an evaluation harness to prove the recall. Before that, a privacy-first AI inbox that runs inference entirely on Cloudflare's edge, and a Node backend deployed on ECS Fargate with Terraform.

What I care about:

- Architectures that stay simple as they grow
- Backends measured by latency and reliability, not feature count
- AI that respects the data boundary: on-device, at the edge, or not at all
- Open source, and writing down what I learn so the next person goes faster

---

## Open Source

I contribute where the plumbing is: data pipelines, UI migrations, CI, and docs.

| Org | What I work on |
| :-- | :-- |
| **[OWASP OpenCRE](https://github.com/OWASP/OpenCRE)** | GSoC 2026 Module B: harvest input and knowledge-queue models, regex and sanitize filter stages, LLM relevance classifier, recall-first evaluation harness |
| **[Palisadoes Foundation](https://github.com/PalisadoesFoundation/talawa-admin)** | Talawa Admin: table loader migration, unreachable-code and UI fixes |
| **[Kestra](https://github.com/kestra-io/kestra)** | Migrating Vue UI components to TypeScript |
| **[Fastify](https://github.com/fastify/fastify)** | Core plugin docs and CITGM coverage for `@fastify/sse` |

**[All merged PRs](https://github.com/search?q=author%3Amanshusainishab+is%3Apr+is%3Amerged&type=pullrequests)**

---

## Projects

**[VaultMail](https://github.com/manshusainishab/VaultMail)** · `Cloudflare Workers` `Workers AI` `Llama 3.1` `Durable Objects` `R2` `KV` `React` `Tailwind` `TypeScript`

Privacy-first AI email triage that never sends a byte of your inbox to a third-party AI vendor. Priority, category, summary and suggested action are inferred at the edge, summaries are AES-GCM-256 encrypted before storage, and every AI call lands in an auditable gateway log. **[Live](https://vaultmail.manshupallav.workers.dev)**

**[Theta E-Learning Platform](https://github.com/manshusainishab/Elearning-platform)** · `Node.js` `Express` `MongoDB` `AWS ECS Fargate` `S3` `Terraform` `GitHub Actions` `React` `Vite` `Playwright`

Course platform with lecture video delivery, JWT auth, Razorpay payments and progress tracking. The API runs as a Fargate task behind an ALB in a custom two-AZ VPC, with all infrastructure in Terraform and secrets injected from Secrets Manager at launch. **[Live app](https://elearning-bice.vercel.app)** · **[Frontend repo](https://github.com/manshusainishab/Elearning-FrontEnd)**

**[Hybrid Temporal Forecaster](https://github.com/manshusainishab/Hybrid-temporal-forecasting-Energy)** · `Python` `PyTorch` `ARIMA` `CNN-BiLSTM` `Attention`

Three-phase study forecasting hourly electricity demand on 145k rows of PJM East load data. An ARIMA baseline, then a CNN-BiLSTM with additive attention cutting MAE by 67%, then residual and stacked hybrids benchmarked on the same split.

**[Aadhaar Document Classifier](https://github.com/manshusainishab/Pre-Visa-ADHAR-VALIDATION)** · `PyTorch` `Vision Transformer` `EasyOCR` `XGBoost` `scikit-learn`

Two-stage pipeline for pre-visa document validation: a pretrained ViT extracts visual embeddings, OCR text becomes handcrafted features, and XGBoost classifies on the concatenation.

---

## Writing

I write on **[Medium](https://medium.com/@manshusainishab)** about things I had to figure out the hard way.

- **[The day RSA stops feeling unbreakable, and why we should act before it happens](https://medium.com/@manshusainishab/the-day-rsa-stops-feeling-unbreakable-and-why-we-should-act-before-it-happens-23a846c030ab)** · quantum computing, Shor's algorithm, and the case for migrating to post-quantum cryptography now
- **[Wiring a filter into a living pipeline: my GSoC 2026 final chapter with OWASP OpenCRE](https://medium.com/@manshusainishab/wiring-a-filter-into-a-living-pipeline-my-gsoc-2026-final-chapter-with-owasp-opencre-module-b-1b491649d198)** · shipping Module B into a production ingestion pipeline

---

## Stack

<div align="center">

**Languages** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=java,python,ts,js" height="32" />

**Backend & Frontend** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=spring,nodejs,express,react,vite,tailwind" height="32" />

**ML & Data** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,postgresql,mongodb,redis" height="32" />

**Cloud & Ops** &nbsp;·&nbsp; <img src="https://skillicons.dev/icons?i=aws,cloudflare,azure,docker,kubernetes,terraform,githubactions,linux,git,postman" height="32" />

</div>

---

## Stats

<div align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=manshusainishab&show_icons=true&include_all_commits=true&count_private=true&hide=stars&hide_border=true&bg_color=0D1117&title_color=22C55E&icon_color=3B82F6&text_color=F8FAFC" alt="GitHub Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=manshusainishab&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=22C55E&text_color=F8FAFC" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=manshusainishab&hide_border=true&background=0D1117&stroke=1F2937&ring=22C55E&fire=22C55E&currStreakLabel=F8FAFC&sideLabels=F8FAFC&currStreakNum=22C55E&sideNums=3B82F6&dates=94A3B8" alt="Contribution Streak" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=manshusainishab&theme=github_dark" alt="Profile Details" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=manshusainishab&theme=github_dark&utcOffset=5.5" alt="Commit Activity" />
</div>

---

<div align="center">

**Got a backend that needs to scale, or an inbox that needs to stay private?** &nbsp;·&nbsp; [Let's talk](mailto:manshupallav@gmail.com)

<sub>In a race to try everything and explore. Star anything you find useful.</sub>

<a href="https://holopin.io/@manshusainishab"><img src="https://holopin.me/manshusainishab" alt="Holopin badges" /></a>

</div>
