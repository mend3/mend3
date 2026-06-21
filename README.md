<!--
  Palette (Color Hunt 2029404b40389a8678caaa98):
  #202940 navy  ·  #4B4038 brown  ·  #9A8678 taupe  ·  #CAAA98 sand
  Badge bg = 202940 / logo = CAAA98 / accent = 9A8678 / second tone = 4B4038
-->

<div align="center">

# Victor Mendonça

**Principal Software Engineer · Platform Architect · AI Systems**

Building ecosystems, data platforms, and AI-native products that matters.

<br/>

![Experience](https://img.shields.io/badge/15%2B%20years-building%20platforms-202940?style=flat-square&labelColor=202940&color=4B4038)
![Location](https://img.shields.io/badge/São%20Paulo-Brazil-202940?style=flat-square&labelColor=202940&color=4B4038)
![Focus](https://img.shields.io/badge/AI-Platforms%20·%20Data-202940?style=flat-square&labelColor=202940&color=4B4038)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mend3-202940?style=flat-square&logo=linkedin&logoColor=CAAA98&labelColor=202940&color=9A8678)](https://www.linkedin.com/in/vicmendonca/)

</div>

---

## About

Software engineer, platform architect, and technical leader with **15+ years** designing and operating scalable SaaS platforms, distributed systems, and AI-native products across **fintech, legaltech, retail intelligence, and data-intensive applications**.

My work is about turning fragmented systems, workflows, and data into cohesive platforms that support multiple products, domains, and business models. Lately my focus sits at the intersection of **AI systems** — agentic workflows, RAG, MCP — and the **data and integration infrastructure** that makes them dependable in production.

I move comfortably between hands-on engineering and technical strategy: leading teams and setting architecture, while still writing the code that proves the hard parts work.

---

## What I'm building now

A unified, white-label **SaaS ecosystem** that combines infrastructure control planes, multi-tenant runtimes, universal connectors, data acquisition at scale, workflow automation, and AI services — designed so a single platform can power many products and verticals.

<!-- KT:PROFILE:START -->
```mermaid
%%{init: {'theme':'base', 'themeVariables': {'primaryColor':'#202940','primaryTextColor':'#CAAA98','primaryBorderColor':'#9A8678','lineColor':'#9A8678','fontFamily':'ui-monospace, monospace'}}}%%
flowchart LR
  classDef plat fill:#202940,stroke:#CAAA98,color:#CAAA98,stroke-width:3px;
  classDef vis fill:#4B4038,stroke:#9A8678,color:#CAAA98,stroke-width:2px;
  classDef cap fill:#9A8678,stroke:#4B4038,color:#202940;
  classDef prod fill:#CAAA98,stroke:#9A8678,color:#202940;
  classDef dom fill:#202940,stroke:#9A8678,color:#CAAA98,stroke-dasharray:4 3;
  classDef proj fill:#4B4038,stroke:#CAAA98,color:#CAAA98,stroke-width:2px;
  c_local_llm["Local LLM"]:::cap
  c_multi_tenant["Multi-tenant"]:::cap
  c_page_builder_cms["Page Builder / CMS"]:::cap
  c_rag_cognition["RAG / Cognition"]:::cap
  c_universal_connectors["Universal Connectors"]:::cap
  d_ads["Ads"]:::dom
  d_ecommerce["Ecommerce"]:::dom
  d_personal_ai["Personal AI"]:::dom
  d_real_estate["Real Estate"]:::dom
  d_talent_intelligence["Talent Intelligence"]:::dom
  p_commerce_intelligence["Commerce Intelligence"]:::prod
  p_datahouse["datahouse"]:::proj
  p_devshell_one["DevShell One"]:::plat
  p_ella["ella"]:::proj
  p_ella_local_ai["Ella — Local AI"]:::prod
  p_hub["hub"]:::proj
  p_oracle["oracle"]:::proj
  p_saas_hub["SaaS Hub"]:::prod
  p_scraping_platform["Scraping Platform"]:::prod
  v_automation_layer["Automation Layer"]:::vis
  v_cognition_layer["Cognition Layer"]:::vis
  v_control_plane["Control Plane"]:::vis
  v_data_plane["Data Plane"]:::vis
  v_intelligence_layer["Intelligence Layer"]:::vis
  c_local_llm -->|provided-by| p_ella
  c_multi_tenant -->|provided-by| p_hub
  c_page_builder_cms -->|provided-by| p_hub
  c_rag_cognition -->|provided-by| p_ella
  c_rag_cognition -->|provided-by| p_hub
  c_universal_connectors -->|provided-by| p_hub
  d_ads -->|served-by| p_hub
  d_ecommerce -->|served-by| p_hub
  d_personal_ai -->|served-by| p_ella
  d_real_estate -->|served-by| p_hub
  d_talent_intelligence -->|served-by| p_hub
  p_commerce_intelligence -->|built-on| p_hub
  p_commerce_intelligence -->|serves| d_ads
  p_commerce_intelligence -->|serves| d_ecommerce
  p_devshell_one -->|built-on| v_control_plane
  p_devshell_one -->|contains| p_commerce_intelligence
  p_devshell_one -->|contains| p_ella_local_ai
  p_devshell_one -->|contains| p_saas_hub
  p_devshell_one -->|contains| p_scraping_platform
  p_ella_local_ai -->|built-on| p_ella
  p_ella_local_ai -->|serves| d_personal_ai
  p_saas_hub -->|built-on| p_hub
  p_scraping_platform -->|built-on| p_datahouse
  v_automation_layer -->|includes| p_hub
  v_cognition_layer -->|includes| p_ella
  v_cognition_layer -->|includes| p_hub
  v_control_plane -->|includes| p_oracle
  v_data_plane -->|includes| p_datahouse
  v_data_plane -->|includes| p_ella
  v_data_plane -->|includes| p_hub
  v_intelligence_layer -->|includes| p_hub
```
<!-- KT:PROFILE:END -->

<sub>↑ Auto-generated from the live system topology (vision → products → domains → capabilities → projects).</sub>

<table>
<tr>
<td valign="top" width="50%">

**Oracle** — `shared control plane`
<br/>Orchestration, shared databases, AI infra, vector search, observability.

**Hub** — `application runtime`
<br/>Multi-tenant SaaS runtime, universal connectors, page builder/CMS, workflow automation, vertical modules.

</td>
<td valign="top" width="50%">

**Datahouse** — `acquisition layer`
<br/>Large-scale scraping, anti-bot, proxy orchestration, data ingestion.

**Ella** — `AI companion`
<br/>Local-first AI companion — RAG, local LLM, cognition.

</td>
</tr>
</table>

---

## Core Expertise

| Area | Focus |
|---|---|
| **Platform Architecture** | SaaS · Distributed systems · DDD · Event-driven · System design |
| **AI & Intelligence** | LLMs · Agentic systems · RAG · MCP · Vector search · Knowledge systems |
| **Data Platforms** | Data engineering · ETL · Analytics · Warehousing · Observability |
| **Leadership** | Engineering strategy · Platform strategy · Product engineering · Mentorship |

---

## Industries

![Ecommerce](https://img.shields.io/badge/E-commerce-202940?style=flat-square&labelColor=202940&color=4B4038)
![Retail Intelligence](https://img.shields.io/badge/Retail-Intelligence-202940?style=flat-square&labelColor=202940&color=4B4038)
![Analytics](https://img.shields.io/badge/Retail-Analytics-202940?style=flat-square&labelColor=202940&color=4B4038)
![LegalTech](https://img.shields.io/badge/Legal-Tech-202940?style=flat-square&labelColor=202940&color=4B4038)
![FinTech](https://img.shields.io/badge/Fin-Tech-202940?style=flat-square&labelColor=202940&color=4B4038)
![AI Systems](https://img.shields.io/badge/AI-Systems-202940?style=flat-square&labelColor=202940&color=4B4038)
![Data Platforms](https://img.shields.io/badge/Data-Platforms-202940?style=flat-square&labelColor=202940&color=4B4038)
![Web Scraping](https://img.shields.io/badge/Web-Scraping-202940?style=flat-square&labelColor=202940&color=4B4038)

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-202940?style=flat-square&logo=typescript&logoColor=CAAA98)
![JavaScript](https://img.shields.io/badge/JavaScript-202940?style=flat-square&logo=javascript&logoColor=CAAA98)
![Java](https://img.shields.io/badge/Java-202940?style=flat-square&logo=openjdk&logoColor=CAAA98)
![Python](https://img.shields.io/badge/Python-202940?style=flat-square&logo=python&logoColor=CAAA98)
![SQL](https://img.shields.io/badge/SQL-202940?style=flat-square&logo=postgresql&logoColor=CAAA98)

**Frontend**

![React](https://img.shields.io/badge/React-202940?style=flat-square&logo=react&logoColor=CAAA98)
![Next.js](https://img.shields.io/badge/Next.js-202940?style=flat-square&logo=nextdotjs&logoColor=CAAA98)
![Angular](https://img.shields.io/badge/Angular-202940?style=flat-square&logo=angular&logoColor=CAAA98)
![Vite](https://img.shields.io/badge/Vite-202940?style=flat-square&logo=vite&logoColor=CAAA98)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-202940?style=flat-square&logo=tailwindcss&logoColor=CAAA98)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-202940?style=flat-square&logo=nodedotjs&logoColor=CAAA98)
![Express](https://img.shields.io/badge/Express-202940?style=flat-square&logo=express&logoColor=CAAA98)
![NestJS](https://img.shields.io/badge/NestJS-202940?style=flat-square&logo=nestjs&logoColor=CAAA98)
![Spring](https://img.shields.io/badge/Spring-202940?style=flat-square&logo=spring&logoColor=CAAA98)
![FastAPI](https://img.shields.io/badge/FastAPI-202940?style=flat-square&logo=fastapi&logoColor=CAAA98)
![BullMQ](https://img.shields.io/badge/BullMQ-202940?style=flat-square&logo=redis&logoColor=CAAA98)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-202940?style=flat-square&logo=postgresql&logoColor=CAAA98)
![Redis](https://img.shields.io/badge/Redis-202940?style=flat-square&logo=redis&logoColor=CAAA98)
![MongoDB](https://img.shields.io/badge/MongoDB-202940?style=flat-square&logo=mongodb&logoColor=CAAA98)
![MySQL](https://img.shields.io/badge/MySQL-202940?style=flat-square&logo=mysql&logoColor=CAAA98)
![ClickHouse](https://img.shields.io/badge/ClickHouse-202940?style=flat-square&logo=clickhouse&logoColor=CAAA98)
![BigQuery](https://img.shields.io/badge/BigQuery-202940?style=flat-square&logo=googlebigquery&logoColor=CAAA98)
![Qdrant](https://img.shields.io/badge/Qdrant-202940?style=flat-square&logo=qdrant&logoColor=CAAA98)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-202940?style=flat-square&logo=docker&logoColor=CAAA98)
![Kubernetes](https://img.shields.io/badge/Kubernetes-202940?style=flat-square&logo=kubernetes&logoColor=CAAA98)
![AWS](https://img.shields.io/badge/AWS-202940?style=flat-square&logo=amazonwebservices&logoColor=CAAA98)
![GCP](https://img.shields.io/badge/GCP-202940?style=flat-square&logo=googlecloud&logoColor=CAAA98)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-202940?style=flat-square&logo=githubactions&logoColor=CAAA98)
![Traefik](https://img.shields.io/badge/Traefik-202940?style=flat-square&logo=traefikproxy&logoColor=CAAA98)

**AI & Automation**

![Ollama](https://img.shields.io/badge/Ollama-202940?style=flat-square&logo=ollama&logoColor=CAAA98)
![MCP](https://img.shields.io/badge/MCP-202940?style=flat-square&logo=anthropic&logoColor=CAAA98)
![RAG](https://img.shields.io/badge/RAG-202940?style=flat-square&logo=databricks&logoColor=CAAA98)
![Vector Search](https://img.shields.io/badge/Vector%20Search-202940?style=flat-square&logo=qdrant&logoColor=CAAA98)
![n8n](https://img.shields.io/badge/n8n-202940?style=flat-square&logo=n8n&logoColor=CAAA98)

---

## Experience

```mermaid
%%{init: {'theme':'base', 'themeVariables': {
  'cScale0':'#202940','cScaleLabel0':'#CAAA98',
  'cScale1':'#4B4038','cScaleLabel1':'#CAAA98',
  'cScale2':'#202940','cScaleLabel2':'#CAAA98',
  'cScale3':'#4B4038','cScaleLabel3':'#CAAA98',
  'cScale4':'#202940','cScaleLabel4':'#CAAA98',
  'cScale5':'#4B4038','cScaleLabel5':'#CAAA98',
  'cScale6':'#202940','cScaleLabel6':'#CAAA98',
  'cScale7':'#4B4038','cScaleLabel7':'#CAAA98',
  'cScale8':'#202940','cScaleLabel8':'#CAAA98',
  'cScale9':'#4B4038','cScaleLabel9':'#CAAA98',
  'cScale10':'#202940','cScaleLabel10':'#CAAA98',
  'cScale11':'#4B4038','cScaleLabel11':'#CAAA98',
  'titleColor':'#9A8678',
  'textColor':'#9A8678',
  'lineColor':'#9A8678',
  'fontFamily':'ui-monospace, monospace'
}}}%%
timeline
    title Professional Journey
    2011 : CS-Consoft — Software Developer
    2012 : BLM — Ecommerce Manager : RS Websites — PHP Developer
    2014 : Orgamec — PHP Developer : Contalex — Java Fullstack
    2018 : Zoroastro — Fullstack Developer
    2019 : Intellibrand — Fullstack Developer
    2021 : Intellibrand — Technical Lead
    2023 : Ascential — Technology Manager : Stone — Senior SWE
    2024 : Jusbrasil — Senior SWE
    2025 : Visualitics — Senior SWE
    Now : Founder — Platform Architect
```

<br/>

<details>
<summary><b>Founder & Platform Architect</b> — White-Label SaaS Ecosystem · 2023–Present</summary>

<br/>

Designing and operating a unified SaaS ecosystem spanning AI, integrations, automation, data acquisition, and vertical applications. Ownership across platform architecture, product strategy, infrastructure, AI systems, data platforms, and engineering standards.

</details>

<details>
<summary><b>Senior Software Engineer</b> — Visualitics · 2025</summary>

<br/>

Unified commerce-intelligence platform consolidating operational data from marketplaces, ad networks, and analytics providers.

- Connector architecture and ETL pipelines across **ADS**, **Selling** and **Marketplace** apps
- Analytics engines with **BigQuery** warehousing and distributed processing
- Chrome Extension architecture for in-context data capture

</details>

<details>
<summary><b>Senior Software Engineer</b> — Jusbrasil · 2024–2025</summary>

<br/>

Large-scale infrastructure for reliable web access and data acquisition.

- Designed and optimized **proxy infrastructure and routing** for fast, dependable retrieval
- Strengthened **observability and reliability** across services
- Implemented cost-efficient strategies that reduced operational spend without sacrificing quality
- Built internal tooling that improved developer experience and throughput

</details>

<details>
<summary><b>Senior Software Engineer</b> — Stone · 2023–2024</summary>

<br/>

Fintech systems for payment processing, merchant acquiring, and financial services for SMEs.

- Backend services, APIs, and microservices for **high-volume transaction processing**
- Integrations with payment gateways, banking APIs, and fraud-detection systems
- Performance, latency, and scalability optimization under strict reliability and compliance standards

</details>

<details>
<summary><b>Technology Manager</b> — Ascential · 2023</summary>

<br/>

Led engineering for digital trade-marketing and e-commerce intelligence platforms serving global brands.

- Directed architecture, data pipelines, analytics platforms, and cloud infrastructure for large-scale retail data
- Defined roadmaps and established quality and operational standards
- Delivered across three solution areas: **retail analytics**, **content & compliance**, and **store locator** tooling

</details>

<details>
<summary><b>Technical Lead → Fullstack Developer</b> — Intellibrand · 2019–2023</summary>

<br/>

Drove the design and scalability of data-driven platforms for retail intelligence and digital trade marketing.

- Architected **real-time retail intelligence** for large-scale collection, processing, and analytics across thousands of digital touchpoints
- Integrated cloud, AI/ML, and data-pipeline tech to improve pricing intelligence and shelf visibility
- Mentored engineers and established engineering best practices

</details>

<details>
<summary><b>Earlier career</b> — 2011–2019</summary>

<br/>

| Company | Role | Focus |
|---|---|---|
| Zoroastro Advogados | Fullstack Developer | Legal ops, workflow automation, financial systems (Node, Angular, Mongo) |
| Contalex | Java Web Fullstack | ERP SaaS for accounting firms (Java, Spring, Hibernate) |
| Orgamec | PHP Developer | Internal business-process automation |
| RS Websites | PHP Developer | Web apps, systems, and ERP (PHP, Laravel, MySQL) |
| BLM | Ecommerce Manager | Digital commerce + a geolocation/Bluetooth Android app |
| CS-Consoft | Developer | Desktop / RIA software |

</details>

---

## How I think about engineering

> Simple scales.

> Architecture is a business decision.

> Operational excellence beats cleverness.

> Data is a platform, not a byproduct.

> AI should amplify humans.

> Build systems that are easier to operate than to explain.

---

<div align="center">

**Designing systems that outlive the applications built on top of them.**

Open to conversations with recruiters, partners, and prospective co-founders.

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-9A8678?style=for-the-badge&logo=linkedin&logoColor=202940)](https://www.linkedin.com/in/vicmendonca/)
[![Email](https://img.shields.io/badge/Get%20in%20touch-9A8678?style=for-the-badge&logo=maildotru&logoColor=202940)](mailto:victor.mendonca@live.com)

</div>

```txt
                                      _  _
                            _____*~~~  **  ~~~*_____
                         __* ___     |\__/|     ___ *__
                       _*  / 888~~\__(8OO8)__/~~888 \  *_
                     _*   /88888888888888888888888888\   *_
                     *   |8888888888888888888888888888|   *
                    /~*  \8888/~\88/~\8888/~\88/~\8888/  *~
                   /  ~*  \88/   \/   (88)   \/   \88/  *~
                  /    ~*  \/          \/          \/  *~
                 /       ~~*_                      _*~~/
                /            ~~~~~*___ ** ___*~~~~~  /
               /                      ~  ~         /
              /                                  /
             /                                 /
            /                                /
           /                    ___sws___  /
          /                    | ####### |
         /            ___      | ####### |             ____i__
        /  _____p_____l_l____  | ####### |            | ooooo |         qp
i__p__ /  |  ###############  || ####### |__l___xp____| ooooo |      |~~~~|
 oooo |_I_|  ###############  || ####### |oo%Xoox%ooxo| ooooo |p__h__|##%#|
 oooo |ooo|  ###############  || ####### |o%xo%%xoooo%| ooooo |      |#xx%|
 oooo |ooo|  ###############  || ####### |o%ooxx%ooo%%| ooooo |######|x##%|
 oooo |ooo|  ###############  || ####### |oo%%x%oo%xoo| ooooo |######|##%x|
 oooo |ooo|  ###############  || ####### |%x%%oo%/oo%o| ooooo |######|/#%x|
 oooo |ooo|  ###############  || ####### |%%x/oo/xx%xo| ooooo |######|#%x/|
 oooo |ooo|  ###############  || ####### |xxooo%%/xo%o| ooooo |######|#^x#|
 oooo |ooo|  ###############  || ####### |oox%%o/x%%ox| ooooo |~~~$~~|x##/|
 oooo |ooo|  ###############  || ####### |x%oo%x/o%//x| ooooo |_KKKK_|#x/%|
 oooo |ooo|  ###############  || ####### |oox%xo%%oox%| ooooo |_|~|~~|xx%/|
 oooo |oHo|  #####AAAA######  || ##XX### |x%x%WWx%%/ox| ooDoo |_| |Y||xGGx|
 ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```
