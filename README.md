<h1 align="center">Guilherme Pantoja</h1>
<p align="center">
  <b>Backend engineer · Go first · Laravel when the product needs it</b><br>
  Software Engineering @ UFAM
</p>

<p align="center">
  I build APIs and domain-heavy systems: real-time sync, fiscal, inventory, and back-office.<br>
  Primary focus is <b>Go</b> (services, concurrency, tooling). I also ship products and ERPs in <b>Laravel / PHP</b>.
</p>

<p align="center">
  <a href="mailto:guilhermepantoja@icomp.ufam.edu.br"><img src="https://img.shields.io/badge/email-contact-111111?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/guilherme-pantoja-martins-8244802b3/"><img src="https://img.shields.io/badge/linkedin-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" />
</p>

---

## What I focus on

| | |
|---|---|
| **Go** | High-throughput APIs, WebSocket, offline→cloud sync, TUIs, networking and concurrency (`context`, worker pools, Kafka) |
| **Laravel / PHP** | Back-office, multi-tenant apps, queues, fiscal (NFS-e / NFC-e), AR/AP, inventory, and ops dashboards |
| **Infra** | Docker, Postgres, Redis, Traefik, observability |

---

## Recent work

### Flow Sistemas — POS + back-office (fuel / retail)

Offline-first point-of-sale ecosystem with a cloud back-office.

- **Operational hub in Go** — PDV sync API (REST + WebSocket), outbox, events, and domain integration over Kafka/Redpanda
- **Back-office in Laravel (PHP 8.4)** — microservices for tenant, people, catalog, inventory, fiscal, and finance behind Traefik
- **Clients** — desktop POS (Tauri) and mobile satellite sharing the same contracts

Typical stack: Go · Laravel · Postgres · Redis · Kafka · Docker

### G2M Fiscal — fiscal SaaS / light ERP

Multi-company platform for fiscal issuance and management (national NFS-e, NFC-e AM), commercial documents, inventory, finance, and POS.

- Laravel 12 · Blade · Alpine · async queues · A1 certificate

→ [g2mfiscal](https://github.com/guilhermepantoja789/g2mfiscal)

### Construtec Obras — construction site diary (PWA)

Web app for daily work logs and document control, deployed with Docker (Nginx + PHP-FPM + queue worker + Cloudflare Tunnel).

→ [obras_construtec](https://github.com/guilhermepantoja789/obras_construtec)

---

## Go — personal projects

Tools and labs where I deepen the language (stdlib, concurrency, protocols, TUI).

| Project | What it is |
|---------|------------|
| [**docker-tui**](https://github.com/guilhermepantoja789/docker-tui) | Bubble Tea TUI for container metrics and lifecycle; viewport-priority one-shot stats (scales to large fleets) |
| [**mini-redis**](https://github.com/guilhermepantoja789/mini-redis) | In-memory key-value server compatible with `redis-cli` — RESP2, TTL, AOF, `go test -race` |
| [**terminal-toolkit**](https://github.com/guilhermepantoja789/terminal-toolkit) | Shell utilities that make terminal work less painful |
| **mini-dag-scheduler** *(in progress)* | DAG workflow orchestrator with cascading cancellation via `context` |

```bash
go install github.com/guilhermepantoja789/docker-tui/cmd/docker-tui@latest
```

---

## Laravel / PHP — still in the mix

I keep shipping full business products in PHP: fiscal, multi-tenant, queues, Blade/Alpine.

- [g2mfiscal](https://github.com/guilhermepantoja789/g2mfiscal) — fiscal SaaS issuance & management  
- [obras_construtec](https://github.com/guilhermepantoja789/obras_construtec) — construction diary / PWA  
- [visor_financeiro](https://github.com/guilhermepantoja789/visor_financeiro) — personal spending and investments tracker  

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
</p>

<details>
<summary>Also in the toolbox</summary>

Bubble Tea · Alpine.js · Blade · Nuxt (consumer) · Tauri/Rust (POS client) · GitHub Actions · Traefik

</details>

---

## Stats

<p align="center">
  <img src="https://github-stats-extended.vercel.app/api?username=guilhermepantoja789&show_icons=true&theme=transparent&hide_border=true&title_color=00ADD8&icon_color=00ADD8&text_color=c9d1d9&bg_color=00000000" height="165" alt="GitHub stats" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=guilhermepantoja789&layout=compact&theme=transparent&hide_border=true&title_color=00ADD8&text_color=c9d1d9&bg_color=00000000" height="165" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=guilhermepantoja789&theme=dark&hide_border=true&ring=00ADD8&fire=00ADD8&currStreakLabel=00ADD8" height="150" alt="GitHub streak" />
</p>

---

<p align="center">
  <i>I prefer code that compiles, passes the race detector, and ships with a clear contract.</i><br>
  <a href="mailto:guilhermepantoja@icomp.ufam.edu.br">guilhermepantoja@icomp.ufam.edu.br</a>
</p>
