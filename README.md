<h1 align="center">Hi, I'm Pedro Ribeiro 👋</h1>

<p align="center">
  <b>Final-year CS student at ISEP · building backend systems for industrial IoT</b><br/>
  Clean Architecture · Domain-Driven Design · PostgreSQL · NestJS · C#/.NET<br/>
  📍 Porto, Portugal
</p>

<p align="center">
  <a href="mailto:pedroribeiro4702@gmail.com"><img src="https://img.shields.io/badge/Email-pedroribeiro4702@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/pedroribeiro47"><img src="https://img.shields.io/badge/LinkedIn-pedroribeiro47-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/1241244-PedroRibeiro"><img src="https://img.shields.io/badge/GitHub-1241244--PedroRibeiro-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

### 👨‍💻 About me

- 🎓 Final-year **B.Sc. in Computer Science / Informatics Engineering** at **ISEP** (Porto).
- 🔧 I build **backend systems for industrial problems** — Clean/Onion Architecture, DDD, and tests that actually run, not just slides.
- 🏭 Currently shipping two industrial-side personal projects: **FlowGuard** (real-time IoT anomaly engine, NestJS) and **OEE-Sentinel** (OEE analytics engine, C#/.NET 10).
- 🌐 **Cisco-certified network technician** — comfortable down to IPv4/IPv6, subnetting, and the protocol side of IoT.
- 🎶 Co-founder and clarinetist at **PIMBAND** when I'm not writing code.
- 🤖 I use AI as an accelerator, never as a substitute — every output is validated against domain rules before it ships.

---

### 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### [FlowGuard](https://github.com/1241244-PedroRibeiro/flow-guard-engine) — *Industrial IoT telemetry & anomaly detection*
Real-time backend ingesting conveyor telemetry, computing moving statistics over in-memory circular ring buffers, and detecting predictive mechanical anomalies in **sub-milliseconds**. Clean Architecture with NestJS IoC, explicit mappers, Joi boundary validation, and PostgreSQL pessimistic row-level locking.

`NestJS` `TypeScript` `PostgreSQL` `Jest` `Bruno`  
✅ **144 Jest tests + 78 Bruno E2E assertions** at 100% pass rate · 8 ADRs

</td>
<td width="50%" valign="top">

#### [OEE-Sentinel](https://github.com/1241244-PedroRibeiro/oee-sentinel) — *Industrial OEE & production-log analytics*
Post-hoc OEE analytics engine for legacy manufacturing. Streams **200k-row CSV shift logs** with bounded memory via `IAsyncEnumerable` + CsvHelper, batches inserts with `EFCore.BulkExtensions`, and computes Availability / Performance / Quality in a pure, unit-tested domain service. Immutable `ProductionShift` facts; partial unique index enforces "one current shift per (machine, window)".

`C#/.NET 10` `Blazor Server` `PostgreSQL` `EF Core` `xUnit`  
✅ **25+ xUnit tests** · 7 ADRs · C4 diagrams · 23h roadmap

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [LaPrizza](https://github.com/1241244-PedroRibeiro) — *Enterprise restaurant back-end*
Clean/Onion back-end for restaurant order management (ISEP LAPR5 / ARQSI). NestJS IoC modules, repository patterns, bidirectional data mappers, JWT + RBAC, Joi validation, and a normalized PostgreSQL schema with `ON DELETE RESTRICT` guards and dynamic size-dependent pricing.

`NestJS` `TypeScript` `PostgreSQL` `PlantUML`

</td>
<td width="50%" valign="top">

#### Other things I've built
- **[Logistics On Rails](https://github.com/Departamento-de-Engenharia-Informatica/sem3-pi-25-26-g094-repo)** — Java + C/RISC-V + PL/SQL railway platform. 2D-Tree over 64k+ stations, Dijkstra / Bellman-Ford / Edmonds-Karp / HubScore, IoT safety modules.
- **[Facial Reconstruction](https://github.com/1241244-PedroRibeiro/1stsemester_project)** — Eigenfaces in Java. Eigendecomposition, covariance optimization, MAE-tracked reconstruction.
- **[PIMBAND Budget Engine](https://github.com/1241244-PedroRibeiro/orcamentador-pimband)** — Automated PDF contract generator. TypeScript, REST APIs, DGEG fuel-price integration.
- **[GMEA](https://github.com/1241244-PedroRibeiro/gmea.github.io)** — Full-stack institutional portal for a music academy.

</td>
</tr>
</table>

---

### 🛠 Tech stack

**Languages**  
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=dotnet&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square)

**Backend & frameworks**  
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor_Server-512BD4?style=flat-square&logo=blazor&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Databases & persistence**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DBMS-F80000?style=flat-square&logo=oracle&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Testing, DevOps & tooling**  
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![FluentAssertions](https://img.shields.io/badge/FluentAssertions-2196F3?style=flat-square)
![Bruno](https://img.shields.io/badge/Bruno_API_Client-FF6B35?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![PlantUML](https://img.shields.io/badge/PlantUML-2B579A?style=flat-square)

**Architecture & methods**  
`Clean / Onion Architecture` · `Domain-Driven Design` · `REST (OpenAPI 3.0)` · `JWT / RBAC` · `Ports & Adapters` · `CQRS read views` · `AI-augmented engineering (Human-in-the-loop)`

---

### 📊 GitHub in numbers

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=1241244-PedroRibeiro&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=transparent&v=2" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=1241244-PedroRibeiro&layout=compact&hide_border=true&langs_count=8&count_private=true&theme=transparent&v=2" alt="Top languages" />
</p>

---

### 📫 Get in touch

- 📧 **Email** — [pedroribeiro4702@gmail.com](mailto:pedroribeiro4702@gmail.com)
- 💼 **LinkedIn** — [linkedin.com/in/pedroribeiro47](https://linkedin.com/in/pedroribeiro47)
- 🐙 **GitHub** — [github.com/1241244-PedroRibeiro](https://github.com/1241244-PedroRibeiro)
- 📍 **Location** — Porto, Portugal · open to **junior backend / distributed systems / industrial IoT** roles

---

<p align="center">
  <i>“The math is the product. Everything else is a delivery mechanism.”</i>
</p>
