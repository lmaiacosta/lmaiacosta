<!-- English · Português abaixo -->

<div align="center">

# Leonardo Maia Costa

**Senior Fullstack Engineer · Cloud Architect · DevOps · 20+ Years in Production**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/leonardo-maia-costa)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://arisecloudsolutions.com)
[![GitHub followers](https://img.shields.io/github/followers/lmaiacosta?style=for-the-badge&logo=github&logoColor=white)](https://github.com/lmaiacosta)

> **Turning complex distributed systems into reliable, scalable products — across AWS, GCP, Azure & DigitalOcean.**
>
> _Open to senior / staff remote positions worldwide_ 🌍

</div>

---

## 🏗️ Architecture at a Glance

```mermaid
graph LR
    subgraph Cloud["☁️ Multi-Cloud"]
        AWS["AWS"] --- GCP["GCP"]
        GCP --- Azure["Azure"]
        Azure --- DO["DigitalOcean"]
    end

    subgraph Infra["🛠 IaC & Orchestration"]
        OT["OpenTofu / Pulumi"] --> K8S["Kubernetes"]
        GHA["GitHub Actions CI/CD"] --> K8S
    end

    subgraph Backend["⚙️ Services"]
        NestJS["NestJS"] --> MongoDB["MongoDB"]
        Go["Go CLI Tools"] --> PG["PostgreSQL"]
        Laravel["Laravel"] --> Kafka["Apache Kafka"]
    end

    subgraph Frontend["🎨 UI Layer"]
        Next15["Next.js 15 App Router"] --> TW["Tailwind CSS 4"]
        Angular["Angular"] --> TS["TypeScript"]
    end

    subgraph Security["🔐 Auth & Security"]
        KC["Keycloak / OIDC"] --> JWT["JWT"]
    end

    subgraph AI["🤖 AI & Automation"]
        MCP["MCP Servers"] --> Claude["Claude AI"]
        Ollama["Ollama + FLUX"] --> ComfyUI["ComfyUI"]
    end

    Cloud --> Infra --> Backend --> Frontend
    Security --> Backend
    AI --> Backend
```

---

## ⭐ Featured Open Source

| Project | Stack | What it does |
|---|---|---|
| [🔑 say-goodbye-to-your-local-env](https://github.com/lmaiacosta/say-goodbye-to-your-local-env) | `Go` · `GitHub Actions` | Interactive CLI that syncs `.env` files to GitHub Secrets — no more lazy scripts |
| [📊 auth-and-load-testing-example-microservices](https://github.com/lmaiacosta/auth-and-load-testing-example-microservices) | `NestJS` · `Angular` · `Keycloak` · `Locust` | Reference architecture: full-stack auth + load testing from day one |
| [🏗️ opentofu-digitalocean-infra-core](https://github.com/lmaiacosta/opentofu-digitalocean-infra-core) | `OpenTofu` · `Kubernetes` · `DigitalOcean` · `Cloudflare` | Production IaC template — VPC + DOKS + MySQL + Registry + DNS |
| [🤖 ai-vetorial-image-generator](https://github.com/lmaiacosta/ai-vetorial-image-generator) | `Python` · `Ollama` · `ComfyUI` · `FLUX` · `K8s` | AI-powered print-ready image generation API, runs locally or on K8s |

---

## 💡 Expertise Map

```mermaid
mindmap
  root((Leonardo))
    Cloud
      Multi-cloud deployments
      Kubernetes orchestration
      Infrastructure as Code
      VPC · DNS · CDN · Cloudflare
    Backend
      Microservices architecture
      REST · GraphQL APIs
      Event-driven with Kafka
      Auth — OIDC / OAuth2 / JWT
    Frontend
      Next.js 15 App Router
      Angular SPAs
      SEO-first & Core Web Vitals
      Progressive Web Apps
    DevOps
      CI/CD pipelines
      Load testing — Locust
      Observability stacks
      Secret management automation
    AI
      MCP Servers
      Claude AI workflows
      Local inference — Ollama + FLUX
```

---

## 🛠 Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=flat-square)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white&style=flat-square)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white&style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square)

**Cloud & Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white&style=flat-square)
![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=white&style=flat-square)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white&style=flat-square)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?logo=digitalocean&logoColor=white&style=flat-square)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white&style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?logo=opentofu&logoColor=black&style=flat-square)
![Pulumi](https://img.shields.io/badge/Pulumi-8A3391?logo=pulumi&logoColor=white&style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white&style=flat-square)

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white&style=flat-square)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white&style=flat-square)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white&style=flat-square)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white&style=flat-square)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?logo=keycloak&logoColor=white&style=flat-square)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white&style=flat-square)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white&style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white&style=flat-square)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square)

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lmaiacosta&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" height="160" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lmaiacosta&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&count_private=true" height="160" alt="Top Languages"/>
</div>

---

## 🎯 Current Focus

- 🏗 **Production Kubernetes** — multi-cloud, cost-optimized workloads
- 🤖 **AI-driven workflows** — MCP servers, local inference with Ollama + FLUX
- 🔐 **Enterprise security** — OIDC, Keycloak, zero-trust patterns
- 📦 **Developer tooling** — Go CLIs that remove friction from CI/CD pipelines
- ⚡ **High-performance web** — Next.js 15 App Router, Core Web Vitals

---

## 🏢 Arise Cloud Solutions

I am the founder of **[Arise Cloud Solutions](https://github.com/arisecloudsolutions)** — a product & services company delivering:

- 🌐 **Production web apps** — Next.js 15, PWA, multi-language, SEO-first
- 🏛 **Cloud infrastructure** — IaC, Kubernetes, multi-cloud
- 💼 **Enterprise platforms** — Multi-tenant CRM, lead generation, document conversion
- 🛠 **AI & automation tools** — MCP servers, Claude AI integrations

---

## 🔗 Let's Connect

| | |
|---|---|
| 💼 **LinkedIn** | [linkedin.com/in/leonardo-maia-costa](https://linkedin.com/in/leonardo-maia-costa) |
| 🌐 **Website** | [fpinfo.com.br](https://fpinfo.com.br) |
| 🏢 **Company** | [Arise Cloud Solutions](https://github.com/arisecloudsolutions) |
| 📍 **Location** | Curitiba, Brazil · **Open to Remote Worldwide** |
| 🗣 **Languages** | Portuguese (native) · English (professional) |

---

<details>
<summary>🇧🇷 Português — Sobre mim</summary>

## Sobre mim

Desenvolvedor Fullstack Sênior e Arquiteto Cloud com mais de **20 anos de experiência** em soluções de TI de ponta a ponta — do frontend ao Kubernetes, passando por DevOps e integrações complexas.

Fundador da **[Arise Cloud Solutions](https://github.com/arisecloudsolutions)**, onde construo produtos reais para clientes reais: plataformas SaaS, sistemas de geração de leads, CRM multi-tenant e aplicações cloud-native.

**Especialidades:** TypeScript · Go · Next.js 15 · NestJS · Kubernetes · IaC (OpenTofu/Pulumi) · AWS · GCP · DigitalOcean · Keycloak · Kafka · AI/MCP

📍 Curitiba, PR — Aberto a trabalho remoto internacional.

</details>

---

<div align="center">

**Battle-ready solutions · Cloud-agnostic architectures · 20 years of turning complexity into elegant code**

_I survived COBOL. I'll survive your legacy system too._ 💻

</div>
