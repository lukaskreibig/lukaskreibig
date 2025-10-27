# Hi, I’m **Lukas Kreibig**

**Senior Frontend Engineer · Data Visualization & Scrollytelling · Applied ML/AI**

I design editorial‑quality, data‑driven interfaces, combining **Typescript/React/Next.js**, **GSAP/D3/Mapbox**, and **Python/FastAPI** or **Node.js** pipelines. My work spans interactive climate stories, satellite‑imagery processing, and real‑time dashboards.

> **Open to**: freelance projects (EU/remote) · collaborations with newsrooms, NGOs & product teams · future full‑time roles.

[Website](https://www.lukaskreibig.dev) · [Portfolio Highlights](#featured-projects) · [Email](mailto:lukas.kreibig@posteo.de)

---

## What I’m great at

* **Frontend architecture**: Typesafe React/Next.js apps with component systems, DX tooling, testing, and CI/CD.
* **Scrollytelling & narrative UX**: GSAP choreographed scenes, performant media preloading, and chart orchestration that reads like a story.
* **Data plumbing**: Python pipelines (Pandas/Dask) that normalize public datasets and feed APIs/clients with reproducible outputs.
* **Applied ML/CV**: Lightweight models (e.g., UNet MobilenetV2) for cloud masking & classification in satellite workflows.
* **Maps & viz**: Mapbox GL, D3, Recharts, Plotly: clear visuals grounded in domain context and accessibility.

---

## Featured projects

### 1) Arctic Climate Story — *arctic.rip*

**An immersive, data‑driven story about Arctic change.**

* High‑resolution **Sentinel‑2** overlays, interactive charts, and bilingual copy (DE/EN).
* **Scroll orchestration** keeps charts and captions in rhythm; a **Mapbox preloader** warms viewpoints and imagery before you arrive.
* A typed **FastAPI** backend serves daily refreshed NASA/NOAA/OWID aggregates; pipelines run on Railway with JSON fallbacks.

**Stack**: Next.js (React 19), GSAP, D3, Recharts, Mapbox GL, Tailwind · FastAPI, Pydantic, SQLAlchemy, Pandas · Vercel/Railway · GitHub Actions.

→ Live: **[https://arctic.rip](https://arctic.rip)**  ·  Docs: `docs/ARCHITECTURE.md`, `docs/DATA_PIPELINE.md`, `docs/OPERATIONS.md`

---

### 2) Uummannaq Ice From Space — *Sentinel‑2 processing pipeline*

**Production‑ready Python package + CLI (`uummannaq-ice`)** that discovers STAC items, streams tiles via **odc‑stac**, runs a **MobilenetV2 UNet** for cloud masking, applies rule‑based ice classification, and exports **CSV stats + quicklook overlays**.

**Highlights**

* YAML‑driven configs with inheritance; CPU & CUDA Docker images.
* **Ruff + mypy + pytest** in CI; fixtures for deterministic tests; manifest JSON for orchestration (cron/Airflow/etc.).

**Stack**: Python, PyTorch, NumPy, Pandas, odc‑stac, Rasterio, Typer, Docker.

→ Repo: `lukaskreibig/uummannaq-ice-from-space`

---

### 3) Map The Air — *maptheair.com*

**Interactive air‑quality explorer** with Mapbox visuals, Plotly charts, and WHO‑style thresholds. Integrates the **OpenAQ** API, plus E2E tests.

**Stack**: React, TypeScript, Material UI, Mapbox GL, Plotly, Jest/RTL, Playwright, GitHub Actions.

→ Live: **[https://maptheair.com](https://maptheair.com)**  ·  Repo: `lukaskreibig/airpollution`

---

## Experience snapshot

* **Senior Frontend Developer — SystemsLab21** *(Apr 2024 – Jan 2025, Berlin)*

  * Led Platform 21 frontend; introduced CI/CD improvements and testing discipline; shipped UI/UX features that lifted usability.
* **Freelance — Full‑stack, Data Vis & AI** *(Jun 2023 – present, Berlin)*

  * Built **The Big Melt** (AI‑driven interactive) and **Map The Air**; delivered highly interactive web apps across industries.
* **Frontend Developer — Floorwell** *(May 2022 – Jun 2023, Berlin)*

  * Modernized the CRM with React + TypeScript; designed a reusable component library; rolled out Redux/Zustand state patterns.
* **Frontend Developer — DI‑ON.Solutions** *(Sep 2021 – May 2022, Berlin)*

  * React Native for cross‑platform apps; integrated GraphQL + AWS; sprint‑based delivery.

---

## Toolbox

**Frontend**: TypeScript, React/Next.js, Vite, Tailwind, Material UI, Mantine, GSAP, D3, Recharts, Plotly, Mapbox GL.

**Data/ML**: Python, Pandas, NumPy, Scikit‑learn, PyTorch, TensorFlow, Jupyter.

**Backend**: FastAPI, Node/Express, GraphQL, gRPC, SQL (Postgres), Supabase.

**Testing**: Jest, React Testing Library, Vitest, Playwright, Pytest, mypy, Ruff.

**DevOps**: GitHub Actions, Vercel, Railway, Docker, CI/CD, monitoring (Sentry, logs).

---

## How I work

* **Type‑safe by default**: shared contracts between frontend/backends.
* **Quality gates**: lint → unit tests → E2E smoke checks for narrative layout (e.g., scroll‑rail gutters).
* **Performance & UX**: prefetching, image/tiles warm‑up, accessibility‑minded motion and contrast.
* **Docs or it didn’t happen**: every repo ships with architecture notes, ops runbooks, and onboarding guides.

---

## Let’s build something

* **Freelance**: newsroom interactives, NGO explainers, climate dashboards, satellite‑data pipelines, frontend modernization.
* **Full‑time**: Senior/Staff Frontend, Data Visualization Engineer, or similar, with room to ship narrative products.

📬 **Reach me**: [lukas.kreibig@posteo.de](mailto:lukas.kreibig@posteo.de) · **Portfolio**: [lukaskreibig.dev](https://www.lukaskreibig.dev)
