<h1 align="center">Dike Ebuka Christopher</h1>
<p align="center"><b>Backend developer</b> · Python · Django · PostgreSQL</p>

<p align="center"><i>Anyone can get an app to run. Getting it to reconcile is the job.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DD0031?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

## What I build

Backend systems that have to be right: multi-tenant data models, payment
integrations, and the reporting layer that sits on top of them. I care about the
boring parts — scoped queries, idempotent webhooks, and a number that comes back
the same the second time you ask.

## Currently building

### [Tenantly](https://tenantly.shop) — multi-tenant e-commerce platform
**Live.** Django · PostgreSQL · Redis · Docker · Nginx

Merchants get a branded storefront on their own subdomain. Customers check out
straight into WhatsApp instead of fighting a payment gateway.

- Multi-tenant data isolation — every query scoped to its merchant
- Paystack subscriptions with HMAC-verified webhooks
- Store analytics: visits, checkouts, product views

*Early stage, pre-launch.*

---

## Proof I'm not bluffing

I took a file of student fee records that was deliberately dirty — the kind of
thing a bursary actually emails you. What I found:

| What was wrong | Effect |
|---|---|
| **216 rows**, but only **200 students** | counted 16 people twice |
| **41 amounts stored as text** (`NGN42,000`) | silently skipped by every total |
| **12 duplicated payment records** | counted the same payment twice |

The text amounts understated the total. The duplicates overstated it. They pulled
in opposite directions, so the reported figure was wrong by only **NGN 97,200** —
small enough that nobody had questioned it.

**That's the dangerous kind of wrong: the number looked right.**

---

## Tools

| | |
|---|---|
| **Backend** | Python · Django · DRF · Celery · REST APIs |
| **Data** | SQL · PostgreSQL · Excel (PivotTables, lookups, reconciliation) |
| **Infra** | Linux VPS · Nginx · Gunicorn · Docker · GitHub Actions · Cloudflare |
| **Frontend** | HTMX · Alpine.js · Tailwind CSS |
| **Learning** | Go |

---

## What I'm good at

- **Backend architecture** — Django + DRF, multi-tenant models, clean schemas
- **Deployment** — VPS, Nginx, Docker, CI/CD that actually deploys on push
- **Data you can trust** — cleaning, reconciling, and reporting figures that survive a second look

---

<p align="center">
  <a href="https://tenantly.shop">tenantly.shop</a> ·
  <a href="https://www.linkedin.com/in/ebuka-dike-99213b241/">LinkedIn</a> ·
  <a href="https://github.com/Kamseyz">GitHub</a>
</p>
