<div align="center">

# Leandro Arévalo

<a href="https://github.com/leaarevalo">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=D97706&center=true&vCenter=true&width=700&lines=Senior+Full-Stack+Developer;Node.js+%C2%B7+NestJS+%C2%B7+React+%C2%B7+Next.js;I+build+AI-powered+products+that+run+in+production;Open+to+remote+Full-Stack+%26+AI+Engineering+roles" alt="Typing animation" />
</a>

📍 San Miguel de Tucumán, Argentina &nbsp;·&nbsp; 🗣️ Spanish (native) · English (advanced) &nbsp;·&nbsp; 📫 [leaarevalotuc@gmail.com](mailto:leaarevalotuc@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/leaarevalo/)

</div>

---

## 👋 About me

Senior Full-Stack Developer with **6+ years** building production systems with **TypeScript, Node.js/NestJS and React/Next.js** on Azure, GCP and Docker.
By day I lead an engineering team on a high-traffic **airline commerce platform**. On my own time I build and operate **AI products with real users**.
I use Claude Code and Gemini daily, and I care about tested, maintainable code.

---

## 🚀 Projects in production

> Both projects are built solo, run with real users, and live in **private repositories**. Code walkthroughs available on request.

### 💬 WA Platform: WhatsApp assistants for businesses

Multi-tenant platform that lets clinics and schools run a WhatsApp assistant: it books appointments in Google Calendar, answers institutional questions, and hands off to a human when needed.

```mermaid
flowchart LR
    U([WhatsApp user]) --> W[Webhook<br/>FastAPI]
    W --> T{Tenant<br/>resolver}
    T --> S[(Redis<br/>sessions)]
    S --> B[Bot engine<br/>medical / school]
    B --> AI[Claude triage<br/>+ Whisper audio]
    B --> G[Google Calendar]
    B --> DB[(PostgreSQL)]
    P[Next.js admin panel] --> API[REST API · JWT]
    API --> DB
```

- 🤖 **LLM integration:** Claude with structured output classifies intent and urgency; Whisper transcribes voice notes. Enabled per client, with a daily cap and automatic fallback to classic menus.
- 🏢 **Multi-tenant by design:** per-client config, roles (client / superadmin) and a self-serve WhatsApp connection flow.
- ✅ **60+ pytest tests**, Alembic migrations, Docker, Railway.

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,redis,nextjs,react,ts,docker&theme=dark" alt="WA Platform stack" />
</p>

### 🎓 ICE: Management & Learning Platform

Church management and academic platform, delivered as **two independently deployable apps** that share one core library (one login across both).

```mermaid
flowchart LR
    V[Vue 3 frontend] --> G[Management app<br/>NestJS]
    V --> E[Learning app<br/>NestJS]
    G --> C[[Shared core lib<br/>auth · users · roles]]
    E --> C
    C --> M[(MongoDB)]
    E --> R2[Cloudflare R2<br/>videos · PDFs]
```

- 🔐 **Security:** role-based authorization, JWT, rate limiting, AES-256-GCM encryption for sensitive records.
- 📚 **Learning features:** signed-URL video delivery, PDF materials, server-scored quizzes.
- ✅ Jest test suites, DTO validation, monorepo architecture.

<p>
  <img src="https://skillicons.dev/icons?i=nestjs,ts,vue,mongodb,cloudflare,jest&theme=dark" alt="ICE stack" />
</p>

---

## 🛠️ Tech stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,python,fastapi,react,nextjs,vue,tailwind&theme=dark" alt="Languages and frameworks" /><br/>
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,redis,rabbitmq,docker,azure,gcp,aws,jest&theme=dark" alt="Data and cloud" />
</p>

| | |
|---|---|
| **AI** | LLM integration (Claude API structured output, Whisper), Claude Code, Gemini Code, MCP |
| **Backend** | TypeScript, Node.js, NestJS, Python (FastAPI), REST, microservices, RabbitMQ |
| **Frontend** | React, Next.js, Vue.js (Pinia), Tailwind CSS |
| **Cloud & DevOps** | Azure (API Management, Key Vault), GCP, AWS (fundamentals), Docker, CI/CD |
| **Testing** | Jest, pytest |

---

## 💼 Experience

<details>
<summary><b>Senior Full-Stack Developer · Sky Airline (Ancillaries Platform)</b> &nbsp;|&nbsp; 2021 – present</summary>
<br/>

Engaged through ACID Labs (2021–2025) and Qurable (2025–present).

- Built **NDC** flows (shopping, order management, servicing) in a company-wide migration between two airline reservation providers.
- Optimized purchase flows (seats, baggage) for latency under high concurrency.
- Designed third-party integration APIs secured with Azure API Management and Key Vault.
- Automated loyalty point accreditation based on customer purchase behavior.
- Lead the engineering team since 2025.

</details>

<details>
<summary><b>Full Stack Developer · Plerk</b> &nbsp;|&nbsp; 2020 – 2021</summary>
<br/>

- Frontend of a B2B corporate-benefits platform (Vue.js, Node.js).
- Secure onboarding with automated KYC validations.

</details>

---

## 📊 GitHub activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=leaarevalo&show_icons=true&theme=transparent&title_color=D97706&icon_color=D97706&text_color=8b949e&hide_border=true&include_all_commits=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=leaarevalo&layout=compact&theme=transparent&title_color=D97706&text_color=8b949e&hide_border=true" alt="Top languages" />
</p>

<sub>Stats include private contributions only if enabled in the profile settings.</sub>

---

<div align="center">

**Open to remote Full-Stack and AI Engineering roles.** &nbsp; 📫 [Email](mailto:leaarevalotuc@gmail.com) &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/leaarevalo/)

<img src="https://komarev.com/ghpvc/?username=leaarevalo&label=Profile+views&color=D97706&style=flat" alt="Profile views" />

</div>
