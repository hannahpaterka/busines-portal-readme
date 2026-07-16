<div align="center">

<img src="assets/hero.svg" alt="Business Portal — operations, invoicing, and field coordination" width="100%" />

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=800&color=22D3EE&center=true&vCenter=true&width=560&height=36&lines=Work+orders+%E2%80%94+assigned+and+tracked;Invoices+%E2%80%94+built+and+monitored;Field+teams+%E2%80%94+connected+on+the+go;Role-based+access+%E2%80%94+locked+down" alt="Work orders, invoices, field coordination, role-based access" />

<p>
  <a href="#capabilities"><img src="https://img.shields.io/badge/Features-0d1526?style=for-the-badge&logo=databricks&logoColor=22d3ee" alt="Features" /></a>
  &nbsp;
  <a href="#architecture"><img src="https://img.shields.io/badge/Technology-0d1526?style=for-the-badge&logo=springboot&logoColor=60a5fa" alt="Technology" /></a>
  &nbsp;
  <a href="#product-tour"><img src="https://img.shields.io/badge/Screenshots-0d1526?style=for-the-badge&logo=googlephotos&logoColor=818cf8" alt="Screenshots" /></a>
</p>

</div>

<img src="assets/divider.svg" alt="" width="100%" />

<br />

## Executive summary

A contract client needed to replace fragmented, manual processes with a single system connecting **vendors, dealers, contractors, and office staff**. I designed, built, and delivered a full-stack operations platform covering user administration, work-order management, invoicing, and field coordination — and I continue to operate the production environment today.

| | |
| :-- | :-- |
| **Engagement type** | Contract — design, build, deploy, maintain |
| **Status** | In production, actively maintained |
| **Platform** | Web application, responsive across desktop and mobile |
| **Infrastructure** | Heroku with managed PostgreSQL |

<br />

## Platform metrics

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/Initial_page_load-<2s-2563EB?style=for-the-badge&labelColor=1e3a8a" alt="Initial page load under 2 seconds" />
      <br /><sub>Server-rendered pages via Thymeleaf — no SPA boot cycle</sub>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Process_automation-Unified_workflows-0891B0?style=for-the-badge&labelColor=164e63" alt="Unified workflow automation" />
      <br /><sub>Work orders, invoicing, and user admin in one system</sub>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Operational_efficiency-Single_source_of_truth-059669?style=for-the-badge&labelColor=064e3b" alt="Single source of truth" />
      <br /><sub>One PostgreSQL database replaces fragmented records</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Field_access-Mobile_ready-16A34A?style=for-the-badge&labelColor=14532d" alt="Mobile-ready field access" />
      <br /><sub>Maps, tap-to-call, and job lists for crews on site</sub>
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Desktop_ops-Full_admin_suite-4F46E5?style=for-the-badge&labelColor=312e81" alt="Full desktop admin suite" />
      <br /><sub>Back-office search, batch actions, and record management</sub>
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Access_control-Role--based_permissions-7C3AED?style=for-the-badge&labelColor=4c1d95" alt="Role-based access control" />
      <br /><sub>Distinct views for installers, dealers, vendors, and staff</sub>
    </td>
  </tr>
</table>

</div>

<br />

## Capabilities

| Domain | Delivered functionality |
| :-- | :-- |
| **Access control** | Secure role-based authentication with distinct permissions for installers, dealers, vendors, and office staff |
| **Work-order management** | Full lifecycle — creation, assignment, status updates, and completion tracking |
| **Invoicing** | Dedicated invoice builder with tracking from creation through payment |
| **Field enablement** | Integrated maps, tap-to-call phone numbers, and one-tap email for teams on site |
| **Collaboration** | Shared notes connecting field crews with back-office staff |
| **Records & search** | Centralized PostgreSQL records with fast filtering and search |

<br />

## Architecture

<div align="center">

<table>
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white" alt="Thymeleaf" />
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery" />
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white" alt="Heroku" />
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring MVC" />
    </td>
  </tr>
</table>

</div>

| Layer | Rationale |
| :-- | :-- |
| **Application** | Java and Spring Boot provide a mature, type-safe foundation suited to long-term maintenance |
| **Presentation** | Thymeleaf SSR with JavaScript and jQuery delivers fast first paint and broad device compatibility |
| **Data** | PostgreSQL enforces relational integrity across users, orders, and invoices |
| **Operations** | Heroku keeps deployment and hosting overhead low for the client |

<br />

## Product tour

<table align="center">
  <tr>
    <td align="center">
      <strong>Data model</strong>
      <br /><br />
      <img src="images/database.png" alt="Database diagram" width="860" />
      <br />
      <sub>Relational schema underpinning users, jobs, work orders, and invoicing</sub>
    </td>
  </tr>
</table>

<br />

<table align="center">
  <tr>
    <td align="center" width="50%">
      <strong>User administration</strong>
      <br /><br />
      <img src="images/users.png" alt="Users management" width="440" />
      <br />
      <sub>Role-based management of installers, dealers, and vendors</sub>
    </td>
    <td align="center" width="50%">
      <strong>Field operations</strong>
      <br /><br />
      <img src="images/jobs.png" alt="Field list" width="440" />
      <br />
      <sub>Map view and job list for crews on the move</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <br />
      <strong>Work-order detail</strong>
      <br /><br />
      <img src="images/workorder.png" alt="Work order" width="440" />
      <br />
      <sub>Assignment, updates, and stage tracking in one record</sub>
    </td>
    <td align="center" width="50%">
      <br />
      <strong>Invoice builder</strong>
      <br /><br />
      <img src="images/invoice.png" alt="Invoice creator" width="440" />
      <br />
      <sub>Invoice creation and monitoring, end to end</sub>
    </td>
  </tr>
</table>

<br />

## Engagement

**Scope.** Sole engineer across the full delivery: requirements, data modeling, application development, deployment, and ongoing production support.

**Outcome.** The client's daily operations — user administration, job dispatch, work orders, and billing — now run through one system with role-appropriate access for every party.

**Current state.** The platform is live on Heroku; I maintain the production environment and ship updates as the client's needs evolve.

---

<div align="center">
  <sub><strong>Business Portal</strong> &nbsp;·&nbsp; Contract engagement &nbsp;·&nbsp; In production on Heroku</sub>
</div>
