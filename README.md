# SeiKai Kyo

**Shingon Buddhist priest who codes. 25 years on the factory floor.**

I sit with factory managers, figure out what breaks, and build systems that fix it. Over the past two and a half years, I independently delivered 30+ enterprise systems for a semiconductor materials manufacturer — MES, AI visual inspection (YOLO11), IoT automation, enterprise AI chatbot — all following ISO 27001:2022 principles.

Before that, I ran a software company for 19 years, delivering factory systems across 4 TSMC fabs and managing teams of up to 30 engineers.

---

### Now

- Building **[Shukuyodo](https://shukuyo.dashai.dev)** — production on Nuxt 3, migrating to Next.js 16 + React 19
- Targeting **Manufacturing AI Engineer / FDE / Engineering Manager** roles in Japan (Randstad / ExecutiveSearch.AI)
- Maintaining **4 Go industrial repos** — SECS/GEM driver, edge gateway, OT security scanner, shared API gateway

---

## Highlights

| | |
|---|---|
| **30+** enterprise systems delivered solo (MES, quality, IoT, AI vision) | Following ISO 27001:2022 |
| **4** TSMC fabs, **19** years running a software company | Up to 30 engineers managed |
| **Shingon priest** + semiconductor developer | Rare domain crossover |
| **11** production languages | ZH (Native) / EN (Professional) / JA (JLPT N2, taking N1 July 2026) |

---

## Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### [Smart Factory Demo](https://factory.dashai.dev)

25 years of factory knowledge, in one interactive system.

![Dashboard](assets/smart-factory-dashboard.png)

| | |
|---|---|
| **54** CRUD APIs | **9** Production Stages |
| **15** AI Tools | **3** Languages |

DashAI reads live factory data, flags NCRs with ranked options, and schedules orders. BCM simulation with cascading impacts and RTO/RPO matrix. 5 factory agents in a collaboration network.

```
Vue 3 + PrimeVue + TypeScript
FastAPI + SQLModel + Neon PostgreSQL
Claude AI (Tool Use) / Vercel + Render
```

</td>
<td width="50%" valign="top">

### [Shukuyodo](https://shukuyo.dashai.dev)

A 1200-year-old sutra turned into software.

![Today's Fortune](assets/shukuyo-today.png)

| | |
|---|---|
| **27** Lunar Mansions | **6** Relationship Types |
| **HR** & Headhunter Mode | **3** Languages |

Kukai brought the Shukuyodo sutra from Tang Dynasty to Japan in 806 AD. I translated the original scripture into a working engine. Every result links back to the Taisho canon source text. Rule-based, no LLM. Personal data stays in your browser.

```
Nuxt 3 (SSR) + Vue 3 + PrimeVue
Go (Chi + pgx) / Vercel + Render
```

</td>
</tr>
</table>

---

## Go Industrial Platform

**4 repos forming a complete industrial edge stack. All single Go binaries. Cross-compile to ARM64.**

<table>
<tr>
<td width="50%" valign="top">

### [go-factory-io](https://github.com/seikaikyo/go-factory-io)
SECS/GEM driver — 12 SEMI standards, 5 protocols, IEC 62443 SL4, single binary

</td>
<td width="50%" valign="top">

### [go-edge-gateway](https://github.com/seikaikyo/go-edge-gateway)
Device bridge + Modbus scanner — plugin architecture, scan-to-config, ARM64

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [go-ot-security](https://github.com/seikaikyo/go-ot-security)
OT/ICS security scanner — CVE detection, IEC 62443 + NIST CSF 2.0 compliance

</td>
<td width="50%" valign="top">

### [dashai-go](https://github.com/seikaikyo/dashai-go)
Shared Go API gateway — Chi + pgx + JWT/Logto, embedded monitoring dashboard

</td>
</tr>
</table>

---

## What I Build

<table>
<tr><th>Category</th><th>Projects</th></tr>
<tr>
<td><b>Enterprise AI & Manufacturing</b></td>
<td>

[Smart Factory Demo](https://factory.dashai.dev) — 30+ enterprise systems, MES, quality, IoT, AI vision<br>
[GoTech Demo](https://gotech.dashai.dev) — Interactive enterprise architecture for 10K-1M users (Go + React + K8s)<br>
[secsgem-mcp-server](https://github.com/seikaikyo/secsgem-mcp-server) — Control semiconductor equipment via Claude Code<br>
Enterprise AI chatbot (Claude API structured tool use) / YOLO11 visual inspection / Modbus TCP / AMR / RFID

</td>
</tr>
<tr>
<td><b>Language Learning</b></td>
<td>

[ai-english-tutor](https://english.dashai.dev) — Voice-first speaking practice with AI grammar correction<br>
[jlpt-n1-learner](https://github.com/seikaikyo/jlpt-n1-learner) — Adaptive JLPT study (N5-N1)<br>
[toeic-practice](https://github.com/seikaikyo/toeic-practice) — TOEIC Reading drill app

</td>
</tr>
<tr>
<td><b>Developer Tooling</b></td>
<td>

[dash-devtools](https://github.com/seikaikyo/dash-devtools) — Validation, E2E, AI vision CLI<br>
[dash-skills](https://github.com/seikaikyo/dash-skills) — Claude Code custom Skills<br>
[claude-code-skills](https://github.com/seikaikyo/claude-code-skills) — 7 reusable skills pack<br>
[ai-red-team](https://ai-red-team.dashai.dev) — LLM adversarial testing, 177 templates across 12 categories<br>
[git-security-hooks](https://github.com/seikaikyo/git-security-hooks) — Pre-commit secret scanning

</td>
</tr>
</table>

---

## Tech Stack

| Area | Technologies |
|------|-------------|
| **AI/LLM** | Claude API (Tool Use), YOLO11, OpenCV |
| **Enterprise** | MES, Digital Transformation, Solution Architecture |
| **SECS/GEM** | HSMS, OPC-UA, MQTT, Modbus TCP |
| **Security** | ISO 27001:2022, IEC 62443, OWASP Top 10, AI Red Teaming |
| **Frontend** | Nuxt 3, Vue 3, React 19, Next.js 16, Angular 21, TypeScript, PrimeVue, shadcn/ui, PrimeNG |
| **Backend** | Go (Chi + pgx), FastAPI + SQLModel, Node.js |
| **Database** | PostgreSQL (Neon), Prisma ORM |
| **IoT** | Modbus TCP, OPC UA, RFID, WebSocket, SECS/GEM |
| **Cloud** | Vercel, Render, Neon, GitHub Actions |

---

## Languages

Chinese (Native) / English (Professional) / Japanese (JLPT N2, BJT J3 — taking N1 in July 2026)

---

[Portfolio](https://portfolio.dashai.dev) / [LinkedIn](https://linkedin.com/in/seikaikyo)

*AI-assisted development with Claude Code.*
