<!-- ───────────────────────────────  HEADER  ─────────────────────────────── -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1E33,50:10304A,100:2E5D8A&height=180&section=header&text=Istiaq%20Ahmed%20Nabil&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=SaaS%20Engineer%20%C2%B7%20Multi-Tenant%20Systems%20%C2%B7%20AI-Native%20Software&descSize=16&descAlignY=58" width="100%" alt="Istiaq Ahmed Nabil — SaaS Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=900&color=5B9BD5&center=true&vCenter=true&width=640&lines=Designing+multi-tenant+SaaS+from+schema+to+API;Building+AI-native+business+software;Shipping+production+apps+on+web%2C+mobile+%26+embedded;Founder+%40+NetJet+Labs+%E2%80%94+engineer+first" alt="Typing SVG" />

<br/>

[![Website](https://img.shields.io/badge/netjetlabs.com-0B1E33?style=flat-square&logo=googlechrome&logoColor=5B9BD5)](https://netjetlabs.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0B1E33?style=flat-square&logo=linkedin&logoColor=5B9BD5)](https://www.linkedin.com/in/istiaqahmednabil)
[![Email](https://img.shields.io/badge/istiaqnabil@netjetlabs.com-0B1E33?style=flat-square&logo=maildotru&logoColor=5B9BD5)](mailto:istiaqnabil@netjetlabs.com)
![Location](https://img.shields.io/badge/Dhaka,_Bangladesh_·_UTC%2B6-0B1E33?style=flat-square&logo=googlemaps&logoColor=5B9BD5)
![Open to remote](https://img.shields.io/badge/Open_to_remote_roles-2E5D8A?style=flat-square&logo=rocket&logoColor=white)

</div>

<br/>

<!-- ───────────────────────────────  ABOUT  ─────────────────────────────── -->

### `$ whoami`

```yaml
name:      Istiaq Ahmed Nabil
role:      Software Engineer — SaaS & enterprise systems
studio:    NetJet Labs  # independent engineering studio
studying:  B.Sc. Computer Science & Engineering
languages: [Bengali, English, Arabic]

builds:
  - multi-tenant SaaS platforms (ERP, school & business ops)
  - REST APIs and service-layer backends
  - AI-native interfaces driven by function calling
  - cross-platform apps (Flutter) and embedded/IoT devices

principles:
  - tenant isolation is a design decision, not a filter clause
  - secure by default: prepared statements, CSRF, rate limiting, session hardening
  - targeted, well-reasoned changes over big-bang rewrites
  - ship to production, then measure and iterate
```

I'm an engineer first. Through **NetJet Labs** I design and ship production software for schools, institutions, and growing businesses — taking ideas from data model to deployed product, and increasingly putting an AI layer between people and the systems they run.

<br/>

<!-- ───────────────────────────────  PROJECTS  ─────────────────────────────── -->

### `$ ls ./projects`

<table>
<tr>
<td width="50%" valign="top">

#### ⬢ NetJet ERP
<sub><code>SaaS</code> · <code>Multi-tenant</code> · <code>REST</code></sub>

A modular ERP platform for institutions and businesses, built around a shared core with tenant-scoped modules.

`SIS` `HRM` `Payroll` `Finance & Accounting` `Attendance` `Inventory` `CRM` `RBAC` `REST API`

</td>
<td width="50%" valign="top">

#### ⬢ NetJet AI OS
<sub><code>R&D</code> · <code>LLM</code> · <code>Function calling</code></sub>

An AI-first business operating system — users state intent in natural language instead of navigating ERP menus; the model calls typed, permission-checked business functions.

`Function Calling` `Service Layer` `Repository Pattern` `Multi-Tenancy` `AI Memory` `Secure Automation`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⬢ SalafiaX
<sub><code>Production</code> · <code>Flutter</code> · <code>PHP API</code> · <code>Google Play</code></sub>

A school management app for students and teachers, live on Google Play and in daily use.

`Student & Teacher Portals` `Attendance` `Results` `Notices` `Holidays` `Fee Alerts` `Routines` `Push Notifications`

</td>
<td width="50%" valign="top">

#### ⬢ Embedded & IoT
<sub><code>ESP32</code> · <code>Arduino</code> · <code>RFID</code></sub>

Hardware that feeds software — RFID-based identity and attendance, sensor nodes, and device-to-API integrations.

`ESP32` `Arduino` `RFID` `IoT → REST`

</td>
</tr>
</table>

<br/>

<!-- ───────────────────────────────  ARCHITECTURE  ─────────────────────────────── -->

### `$ cat ai-os/architecture.md`

How NetJet AI OS turns a sentence into a safe business action:

```mermaid
flowchart LR
    U([User · natural language]) --> G[API Gateway<br/>auth · tenant resolution · rate limit]
    G --> L[LLM Orchestrator<br/>function calling]
    L -->|typed tool call| P{Policy & RBAC check}
    P -->|allowed| S[Service Layer]
    P -->|denied| R([Explain & refuse])
    S --> Repo[Repository Layer]
    Repo --> DB[(Tenant-scoped<br/>data store)]
    L <--> M[(AI Memory)]
    S --> A[Audit Log]
```

<br/>

<!-- ───────────────────────────────  STACK  ─────────────────────────────── -->

### `$ stack --list`

<table>
<tr><td><b>Languages</b></td><td>

![PHP](https://img.shields.io/badge/PHP-0B1E33?style=flat-square&logo=php&logoColor=777BB4)
![Dart](https://img.shields.io/badge/Dart-0B1E33?style=flat-square&logo=dart&logoColor=0175C2)
![Python](https://img.shields.io/badge/Python-0B1E33?style=flat-square&logo=python&logoColor=3776AB)
![JavaScript](https://img.shields.io/badge/JavaScript-0B1E33?style=flat-square&logo=javascript&logoColor=F7DF1E)
![C++](https://img.shields.io/badge/C++-0B1E33?style=flat-square&logo=cplusplus&logoColor=00599C)
![C](https://img.shields.io/badge/C-0B1E33?style=flat-square&logo=c&logoColor=A8B9CC)
![SQL](https://img.shields.io/badge/SQL-0B1E33?style=flat-square&logo=mysql&logoColor=4479A1)

</td></tr>
<tr><td><b>Backend & Data</b></td><td>

![REST](https://img.shields.io/badge/REST_APIs-0B1E33?style=flat-square&logo=openapiinitiative&logoColor=6BA539)
![MVC](https://img.shields.io/badge/MVC-0B1E33?style=flat-square&logo=databricks&logoColor=5B9BD5)
![MySQL](https://img.shields.io/badge/MySQL-0B1E33?style=flat-square&logo=mysql&logoColor=4479A1)
![MariaDB](https://img.shields.io/badge/MariaDB-0B1E33?style=flat-square&logo=mariadb&logoColor=C0765A)
![Redis](https://img.shields.io/badge/Redis-0B1E33?style=flat-square&logo=redis&logoColor=DC382D)

</td></tr>
<tr><td><b>Mobile</b></td><td>

![Flutter](https://img.shields.io/badge/Flutter-0B1E33?style=flat-square&logo=flutter&logoColor=02569B)
![Firebase](https://img.shields.io/badge/Push_Notifications-0B1E33?style=flat-square&logo=firebase&logoColor=FFCA28)
![Google Play](https://img.shields.io/badge/Google_Play-0B1E33?style=flat-square&logo=googleplay&logoColor=34A853)

</td></tr>
<tr><td><b>AI</b></td><td>

![Claude](https://img.shields.io/badge/Claude_API-0B1E33?style=flat-square&logo=anthropic&logoColor=D97757)
![OpenAI](https://img.shields.io/badge/OpenAI_API-0B1E33?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-0B1E33?style=flat-square&logo=googlegemini&logoColor=8E75B2)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-0B1E33?style=flat-square&logo=huggingface&logoColor=FFD21E)
![Function Calling](https://img.shields.io/badge/Function_Calling-0B1E33?style=flat-square&logo=probot&logoColor=5B9BD5)
![NLP](https://img.shields.io/badge/NLP-0B1E33?style=flat-square&logo=googletranslate&logoColor=5B9BD5)

</td></tr>
<tr><td><b>Infra & Tooling</b></td><td>

![Docker](https://img.shields.io/badge/Docker-0B1E33?style=flat-square&logo=docker&logoColor=2496ED)
![Git](https://img.shields.io/badge/Git-0B1E33?style=flat-square&logo=git&logoColor=F05032)
![Linux](https://img.shields.io/badge/Linux-0B1E33?style=flat-square&logo=linux&logoColor=FCC624)

</td></tr>
<tr><td><b>Embedded</b></td><td>

![ESP32](https://img.shields.io/badge/ESP32-0B1E33?style=flat-square&logo=espressif&logoColor=E7352C)
![Arduino](https://img.shields.io/badge/Arduino-0B1E33?style=flat-square&logo=arduino&logoColor=00979D)
![RFID](https://img.shields.io/badge/RFID-0B1E33?style=flat-square&logo=nfc&logoColor=5B9BD5)
![IoT](https://img.shields.io/badge/IoT-0B1E33?style=flat-square&logo=homeassistant&logoColor=5B9BD5)

</td></tr>
</table>

<br/>

<!-- ───────────────────────────────  NOW  ─────────────────────────────── -->

### `$ git log --since="this quarter" --oneline`

```diff
+ researching  LLM function calling & agentic workflows for business ops
+ designing    tenant isolation strategies for multi-tenant SaaS
+ learning     distributed systems · cloud infrastructure · DevOps
+ learning     advanced software architecture at SaaS scale
+ shipping     new features to SalafiaX in production
```

<details>
<summary><b>Areas of interest</b></summary>
<br/>

Artificial Intelligence · SaaS Architecture · Distributed Systems · Enterprise Software · Cyber Security · Computer Vision · NLP · Robotics & Embedded Systems · Space Technology · Open Source

</details>

<br/>

<!-- ───────────────────────────────  STATS  ─────────────────────────────── -->

### `$ gh stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=IstiaqAhmedNabil&show_icons=true&hide_border=true&bg_color=0B1E33&title_color=5B9BD5&icon_color=5B9BD5&text_color=C9D6E3&rank_icon=github" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=IstiaqAhmedNabil&layout=compact&hide_border=true&bg_color=0B1E33&title_color=5B9BD5&text_color=C9D6E3&langs_count=8" alt="Top languages" />

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=IstiaqAhmedNabil&bg_color=0B1E33&color=C9D6E3&line=5B9BD5&point=ffffff&area=true&area_color=2E5D8A&hide_border=true" alt="Contribution activity" />

</div>

<br/>

<!-- ───────────────────────────────  FOOTER  ─────────────────────────────── -->

<div align="center">

**Building software that survives contact with production.**

<sub>Open to remote software engineering roles · Collaborations welcome via <a href="mailto:istiaqnabil@netjetlabs.com">email</a></sub>

<br/><br/>

![Profile views](https://komarev.com/ghpvc/?username=IstiaqAhmedNabil&color=2E5D8A&style=flat-square&label=profile+views)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E5D8A,50:10304A,100:0B1E33&height=100&section=footer" width="100%" />

</div>
