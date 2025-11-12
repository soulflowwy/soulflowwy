---

4+ years of experience ensuring quality across **backend**, **web**, and **mobile** layers.  
Worked on **FinTech**, **AI-driven Compliance**, **Telemedicine**, and **high-load B2C** platforms —  
where correctness, data integrity, and user experience directly impact business results.

<!-- subtle divider -->
<img src="https://github.com/saadeghi/saadeghi/blob/master/dots.svg" width="100%" alt="divider" />

<!-- QUICK METRICS -->
<p align="center">
  <img src="https://img.shields.io/badge/Experience-4%2B%20years-00FF99?style=flat" />
  <img src="https://img.shields.io/badge/English-C2-00FF99?style=flat" />
  <img src="https://img.shields.io/badge/US%20Work%20Authorization-Green%20Card-00FF99?style=flat" />
  <img src="https://img.shields.io/badge/Remote-Ready-00FF99?style=flat" />
</p>

---

## 🧩 Focus Areas & 🎛 Toolbox

<table>
<tr>
<td width="50%" valign="top">

### Focus Areas
- ✅ Backend & API validation (REST/SOAP)  
- ✅ Web & Mobile testing (iOS/Android)  
- ✅ Microservice integrations, async flows, data consistency  
- ✅ Regression & end-to-end testing  
- ✅ CI/CD QA integration and release control  

</td>
<td width="50%" valign="top">

### Toolbox (Core)
**API:** Postman · Swagger · SoapUI  
**Async:** Kafka · Camunda BPM · RabbitMQ  
**DB:** PostgreSQL (SELECT/JOIN/agg) · DBeaver  
**Web/Mobile:** DevTools · Firebase App · TestFlight  
**Observability:** Kibana · Sentry · Charles  
**Process:** GitLab CI/CD · Docker · Zephyr · Jira · Confluence · Allure Test Ops  
**Automation (in progress):** Python + Pytest

</td>
</tr>
</table>

<details>
  <summary><b>Why this stack?</b> (коротко)</summary>
  <br>
  • Kafka/Camunda покрывают события и оркестрации, <i>где баги живут между сервисами</i>.<br>
  • Kibana/Sentry/Charles дают трассировку причин → меньше “симптомных” фиксов.<br>
  • Pytest закрывает быстрый smoke/regression на API-уровне прямо в CI.
</details>

<!-- divider -->
<img src="https://github.com/saadeghi/saadeghi/blob/master/dots.svg" width="100%" alt="divider" />

## 🧠 Work Approach (Terminal view)

```bash
$ qa run --suite=regression \
         --services=auth,profile,scoring \
         --async --ci --env=pre-release

✓ APIs (REST/SOAP): schemas, models, contracts       [pass]
✓ Async chains (Kafka/Camunda): keys, correlation     [pass]
✓ Data checks (PostgreSQL): joins, aggregates         [pass]
✓ Logs & traces (Kibana/Sentry): root cause           [found & fixed]
→ build status: stable | ready for UAT
