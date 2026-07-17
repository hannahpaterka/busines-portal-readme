<div align="center">

<img src="assets/hero.svg" alt="Business Portal — operations, invoicing, and field coordination" width="100%" />

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=800&color=17A2B8&center=true&vCenter=true&width=560&height=36&lines=Work+orders+%E2%80%94+assigned+and+tracked;Invoices+%E2%80%94+built+and+monitored;Field+teams+%E2%80%94+connected+on+the+go;Role-based+access+%E2%80%94+locked+down" alt="Work orders, invoices, field coordination, role-based access" />

<a href="#capabilities"><img src="https://img.shields.io/badge/Features-007bff?style=for-the-badge&logo=databricks&logoColor=white" alt="Features" /></a>
&nbsp;
<a href="#architecture"><img src="https://img.shields.io/badge/Technology-17a2b8?style=for-the-badge&logo=springboot&logoColor=white" alt="Technology" /></a>
&nbsp;
<a href="#product-tour"><img src="https://img.shields.io/badge/Screenshots-0069c0?style=for-the-badge&logo=googlephotos&logoColor=white" alt="Screenshots" /></a>

</div>

## Executive summary

A contract client needed to replace fragmented, manual processes with a single system connecting **vendors, dealers, contractors, and office staff**. I designed, built, and delivered a full-stack operations platform covering user administration, work-order management, invoicing, and field coordination — and I continue to operate the production environment today.

| | |
| :-- | :-- |
| **Engagement type** | Contract — design, build, deploy, maintain |
| **Status** | In production, actively maintained |
| **Platform** | Web application, responsive across desktop and mobile |
| **Infrastructure** | Heroku with managed PostgreSQL |

## Platform metrics

| Metric | Outcome |
| :-- | :-- |
| **Initial page load** | Under 2 seconds — server-rendered via Thymeleaf, no SPA boot cycle |
| **Process automation** | Work orders, invoicing, and user admin unified in one workflow |
| **Operational efficiency** | Single PostgreSQL database replaces fragmented records |
| **Field access** | Mobile-ready — maps, tap-to-call, and job lists for crews on site |
| **Desktop operations** | Full admin suite with search, batch actions, and record management |
| **Access control** | Role-based permissions for installers, dealers, vendors, and staff |

## Capabilities

| Domain | Delivered functionality |
| :-- | :-- |
| **Access control** | Secure role-based authentication with distinct permissions for installers, dealers, vendors, and office staff |
| **Work-order management** | Full lifecycle — creation, assignment, status updates, and completion tracking |
| **Invoicing** | Dedicated invoice builder with tracking from creation through payment |
| **Field enablement** | Integrated maps, tap-to-call phone numbers, and one-tap email for teams on site |
| **Collaboration** | Shared notes connecting field crews with back-office staff |
| **Records & search** | Centralized PostgreSQL records with fast filtering and search |

## Architecture

<div align="center">

<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white" alt="Thymeleaf" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/jQuery-007BFF?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" alt="Heroku" />
<img src="https://img.shields.io/badge/Spring_MVC-17A2B8?style=for-the-badge&logo=spring&logoColor=white" alt="Spring MVC" />

</div>

| Layer | Rationale |
| :-- | :-- |
| **Application** | Java and Spring Boot provide a mature, type-safe foundation suited to long-term maintenance |
| **Presentation** | Thymeleaf SSR with JavaScript and jQuery delivers fast first paint and broad device compatibility |
| **Data** | PostgreSQL enforces relational integrity across users, orders, and invoices |
| **Operations** | Heroku keeps deployment and hosting overhead low for the client |

## Product tour

<div align="center">

<strong>Data model</strong>
<br />
<sub>Relational schema underpinning users, jobs, work orders, and invoicing</sub>
<br />
<img src="images/database.png" alt="Database diagram" width="860" />

<br /><br />

<table border="0" cellspacing="24" cellpadding="0">
  <tr>
    <td align="center" valign="top">
      <strong>User administration</strong>
      <br />
      <sub>Role-based management of installers, dealers, and vendors</sub>
      <br />
      <img src="images/users.png" alt="Users management" width="440" />
    </td>
    <td align="center" valign="top">
      <strong>Field operations</strong>
      <br />
      <sub>Map view and job list for crews on the move</sub>
      <br />
      <img src="images/jobs.png" alt="Field list" width="440" />
    </td>
  </tr>
</table>

<br />

<table border="0" cellspacing="24" cellpadding="0">
  <tr>
    <td align="center" valign="top">
      <strong>Work-order detail</strong>
      <br />
      <sub>Assignment, updates, and stage tracking in one record</sub>
      <br />
      <img src="images/workorder.png" alt="Work order" width="440" />
    </td>
    <td align="center" valign="top">
      <strong>Invoice builder</strong>
      <br />
      <sub>Invoice creation and monitoring, end to end</sub>
      <br />
      <img src="images/invoice.png" alt="Invoice creator" width="440" />
    </td>
  </tr>
</table>

</div>

## Engagement

**Scope.** Sole engineer across the full delivery: requirements, data modeling, application development, deployment, and ongoing production support.

**Outcome.** The client's daily operations — user administration, job dispatch, work orders, and billing — now run through one system with role-appropriate access for every party.

**Current state.** The platform is live on Heroku; I maintain the production environment and ship updates as the client's needs evolve.

<div align="center">
  <sub><strong>Business Portal</strong> &nbsp;·&nbsp; Contract engagement &nbsp;·&nbsp; In production on Heroku</sub>
</div>
