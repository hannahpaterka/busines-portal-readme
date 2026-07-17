<div align="center">

<img src="assets/hero.svg" alt="Business Portal — operations, invoicing, and field coordination" width="100%" />

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=800&color=17A2B8&center=true&vCenter=true&width=560&height=36&lines=Work+orders+%E2%80%94+assigned+and+tracked;Invoices+%E2%80%94+built+and+monitored;Field+teams+%E2%80%94+connected+on+the+go;Role-based+access+%E2%80%94+locked+down" alt="Work orders, invoices, field coordination, role-based access" />

<p>
  <a href="#capabilities"><img src="https://img.shields.io/badge/Features-212529?style=for-the-badge&logo=databricks&logoColor=17a2b8" alt="Features" /></a>
  &nbsp;
  <a href="#architecture"><img src="https://img.shields.io/badge/Technology-212529?style=for-the-badge&logo=springboot&logoColor=007bff" alt="Technology" /></a>
  &nbsp;
  <a href="#product-tour"><img src="https://img.shields.io/badge/Screenshots-212529?style=for-the-badge&logo=googlephotos&logoColor=17a2b8" alt="Screenshots" /></a>
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
      <img src="https://img.shields.io/badge/Initial_page_load-<2s-007BFF?style=for-the-badge&labelColor=212529" alt="Initial page load under 2 seconds" />
      <br /><sub>Server-rendered pages via Thymeleaf — no SPA boot cycle</sub>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Process_automation-Unified_workflows-17A2B8?style=for-the-badge&labelColor=212529" alt="Unified workflow automation" />
      <br /><sub>Work orders, invoicing, and user admin in one system</sub>
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Operational_efficiency-Single_source_of_truth-0069C0?style=for-the-badge&labelColor=212529" alt="Single source of truth" />
      <br /><sub>One PostgreSQL database replaces fragmented records</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Field_access-Mobile_ready-17A2B8?style=for-the-badge&labelColor=212529" alt="Mobile-ready field access" />
      <br /><sub>Maps, tap-to-call, and job lists for crews on site</sub>
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Desktop_ops-Full_admin_suite-007BFF?style=for-the-badge&labelColor=212529" alt="Full desktop admin suite" />
      <br /><sub>Back-office search, batch actions, and record management</sub>
    </td>
    <td align="center">
      <br />
      <img src="https://img.shields.io/badge/Access_control-Role--based_permissions-138496?style=for-the-badge&labelColor=212529" alt="Role-based access control" />
      <br /><sub>Distinct views for installers, dealers, vendors, and staff</sub>
    </td>
  </tr>
</table>

</div>

<br />

<img src="assets/divider.svg" alt="" width="100%" />

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

<img src="assets/divider.svg" alt="" width="100%" />

<br />

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

<br />

<img src="assets/divider.svg" alt="" width="100%" />

<br />

## Product tour

<table align="center">
  <tr>
    <td align="center">
      <img src="https://img.shields.io/badge/Data_model-17A2B8?style=for-the-badge&labelColor=212529" alt="Data model" />
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
      <img src="https://img.shields.io/badge/User_administration-007BFF?style=for-the-badge&labelColor=212529" alt="User administration" />
      <br /><br />
      <img src="images/users.png" alt="Users management" width="440" />
      <br />
      <sub>Role-based management of installers, dealers, and vendors</sub>
    </td>
    <td align="center" width="50%">
      <img src="https://img.shields.io/badge/Field_operations-17A2B8?style=for-the-badge&labelColor=212529" alt="Field operations" />
      <br /><br />
      <img src="images/jobs.png" alt="Field list" width="440" />
      <br />
      <sub>Map view and job list for crews on the move</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <br />
      <img src="https://img.shields.io/badge/Work_order_detail-007BFF?style=for-the-badge&labelColor=212529" alt="Work order detail" />
      <br /><br />
      <img src="images/workorder.png" alt="Work order" width="440" />
      <br />
      <sub>Assignment, updates, and stage tracking in one record</sub>
    </td>
    <td align="center" width="50%">
      <br />
      <img src="https://img.shields.io/badge/Invoice_builder-17A2B8?style=for-the-badge&labelColor=212529" alt="Invoice builder" />
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

<img src="assets/divider.svg" alt="" width="100%" />

<div align="center">

**Business Portal**<br />
<sub>Contract engagement &nbsp;·&nbsp; In production on Heroku</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:212529,50:007bff,100:17a2b8&height=100&section=footer" alt="" width="100%" />

</div>
