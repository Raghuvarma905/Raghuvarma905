<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey,%20I'm%20Raghuvarma%20👋&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Backend%20Engineer%20·%20Python%20·%20PostgreSQL%20·%20React&descAlignY=55&descSize=18"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Backend+Engineer+%F0%9F%90%8D;Python+%7C+FastAPI+%7C+PostgreSQL;React+%7C+TypeScript+%7C+Supabase;I+build+BI+migration+tooling;Compilers%2C+schemas%2C+and+auth+systems" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://raghuvarma-portfolio.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-raghuvarma--portfolio.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
</p>

<p align="center">
  <a href="mailto:raghukuduka10@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-raghukuduka10@gmail.com-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/Raghuvarma-kuduka">
    <img src="https://img.shields.io/badge/LinkedIn-Raghuvarma--kuduka-0077B5?style=flat&logo=linkedin"/>
  </a>
  &nbsp;
  <a href="tel:+919059946190">
    <img src="https://img.shields.io/badge/Phone-+91 9059946190-25D366?style=flat&logo=whatsapp&logoColor=white"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Hyderabad,%20India-FF6B6B?style=flat&logo=googlemaps&logoColor=white"/>
</p>

---

## About Me

- 🐍 **Backend engineer** — Python, FastAPI, PostgreSQL, and the security layer around them
- 🔄 I build **BIMigrator**, a platform that migrates BI dashboards between Tableau, Qlik, Power BI and Superset
- 🗄️ I design **PostgreSQL schemas** and multi-tenant security — row-level security, RBAC, tenant isolation
- ⚛️ I ship the **React + TypeScript** front ends for what I build
- 🎓 B.Tech in **AI & Machine Learning** — CMR Technical Campus, Hyderabad
- 📫 Most of my work lives in private company repos — happy to walk through any of it

---

## Currently Building

### 🔄 BIMigrator — BI Dashboard Migration Platform

Point it at a Tableau or Qlik dashboard and it rebuilds the whole thing in Power BI or
Superset — parsing the source into a canonical intermediate representation and
regenerating from there.

**What I built in it:**

- **Qlik-expression → DAX translator** — a small compiler: parse one expression language, emit another
- **Power BI layout generator** — maps chart types to native visuals (funnel, treemap, scatter, combo, box plot, waterfall, pivot)
- **Offline `.pbix` generation** — writing the Power BI file format directly, building the package XML by hand
- **Multi-fact relationship validation** using a directed filter graph, with fail-loud reporting
- **Auth layer** — JWT verification, allowlist enforcement, clock-skew tolerance
- **Org-level migration quota** — atomic DB-side reservation with row locks, so concurrent runs can't oversubscribe
- Found and fixed an **auth-bypass bug** where a prefix check on `/` silently disabled every guard on the API
- pytest coverage matrices for the visual mapping and relationship validation

`Python` `FastAPI` `SQLAlchemy` `Alembic` `Supabase` `DuckDB` `React` `TypeScript` `Docker`

---

### 🏢 people.samyama.work — Multi-Tenant HR Platform

Internal HR platform. The project I own outright.

- **67 SQL migrations** — schema designed and evolved over time
- **RBAC on row-level security** — roles in their own table, checked through a `SECURITY DEFINER` function so policies can't be bypassed from the client
- **Multi-tenant isolation** via a tenant-scoping function
- **26 serverless functions** — GPS-verified punch in/out, break tracking, the full leave approval workflow, AI-generated training quizzes on Gemini, scheduled reporting jobs

`React` `TypeScript` `PostgreSQL` `Supabase` `Deno` `Gemini API`

---

## Featured Projects

| Project | What I built | Stack |
|---|---|---|
| **BIMigrator** | Qlik→DAX translator, Power BI layout generator, offline `.pbix` writer, auth layer, atomic migration quota | Python, FastAPI, Supabase, React |
| **people.samyama.work** | 67-migration schema, RBAC on RLS, 26 edge functions, GPS attendance, leave workflow, Gemini quiz generation | React, TypeScript, PostgreSQL, Supabase |
| **Qorro** | Hand-written history-based router; demo-request pipeline with OAuth, templated email from object storage, DB persistence | React, TypeScript, Supabase, Firebase |
| **Samyama Design System** | Design-system site with a component generator that emits code and packages it as a ZIP client-side | React, TypeScript, Tailwind, Radix, MUI |
| **samyama.ai** | Multi-model LLM chatbot — OpenAI Assistants threads/runs, conversation persistence, rate limiting, CORS allowlist | JavaScript, Supabase Edge Functions, OpenAI |

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Deno](https://img.shields.io/badge/Deno-000000?style=flat&logo=deno&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat&logo=alembic&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Radix UI](https://img.shields.io/badge/Radix_UI-161618?style=flat&logo=radixui&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=flat&logo=mui&logoColor=white)

**AI & LLM**

![ChatGPT](https://img.shields.io/badge/OpenAI_API-74aa9c?style=flat&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=flat&logo=google&logoColor=white)

**Tooling & Testing**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)

---

## Areas of Focus

```
Python Backend        ████████████████████  FastAPI, auth, concurrency, data pipelines
PostgreSQL & Schema   ███████████████████░  migrations, RLS, RBAC, multi-tenancy
React + TypeScript    ████████████████░░░░  SPA product interfaces
API Security          ██████████████░░░░░░  JWT, allowlists, access control
Testing               ████████████░░░░░░░░  pytest, Playwright, Vitest
LLM Integration       ████████████░░░░░░░░  OpenAI, Claude, Gemini APIs
Rust                  ████░░░░░░░░░░░░░░░░  learning, alongside a graph-DB team
```

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Raghuvarma905&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="60%"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Raghuvarma905&theme=tokyonight&hide_border=true" width="60%"/>
</p>

---

## Contact Me

| Channel | Details |
|---|---|
| Email | [raghukuduka10@gmail.com](mailto:raghukuduka10@gmail.com) |
| Phone / WhatsApp | [+91 9059946190](tel:+919059946190) |
| LinkedIn | [linkedin.com/in/Raghuvarma-kuduka](https://linkedin.com/in/Raghuvarma-kuduka) |
| Portfolio | [raghuvarma-portfolio.vercel.app](https://raghuvarma-portfolio.vercel.app) |
| GitHub | [github.com/Raghuvarma905](https://github.com/Raghuvarma905) |
| Location | Hyderabad, Telangana, India |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Raghuvarma905&color=0e75b6&style=flat" alt="profile views"/>
</p>

<p align="center">
  <i>Open to Backend, Python, and Full Stack roles — remote or Hyderabad</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer"/>
</p>
