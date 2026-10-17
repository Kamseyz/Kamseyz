# Dike Ebuka Christopher — Backend Developer

I build and deploy backend systems in Python/Django and PostgreSQL, and I teach
Django part-time. I care most about systems that stay correct: clean schemas,
queries that reconcile, and invoices that match.

**Currently:** building Tenantly, a multi-tenant e-commerce platform.

---

## What I've built

**[Tenantly](https://tenantly.shop)** — multi-tenant e-commerce platform, live.
Django · PostgreSQL · Redis · Docker · Nginx
Merchants get a branded storefront on their own subdomain; customers check out
straight into WhatsApp instead of a payment gateway. Multi-tenant data isolation,
Paystack subscription billing with HMAC-verified webhooks, store analytics.
*Early stage, pre-launch.*

**Misty Farms** — e-commerce platform, deployed on a VPS.
Django · HTMX · PostgreSQL · GitHub Actions
Full checkout via Paystack, CI/CD deploying on every push to main, load-tested
with Locust, instrumented with Redis/Celery/Sentry.

**Student fee reconciliation** — a data exercise on deliberately messy records.
PostgreSQL · SQL · Excel
Found 16 duplicate student records (216 rows, 200 students), 41 payment amounts
stored as text and silently skipped by totals, and 12 duplicated payment records.
Two errors pulling in opposite directions left the reported total wrong by only
NGN 97,200 — which is why nobody had noticed it.

---

## Tools

**Backend:** Python, Django, Django REST Framework, Celery, REST APIs
**Data:** SQL, PostgreSQL, Excel (PivotTables, lookups, reconciliation)
**Infra:** Linux VPS, Nginx, Gunicorn, Docker, GitHub Actions, Cloudflare
**Frontend:** HTMX, Alpine.js, Tailwind CSS
**Learning:** Go

---

## Work with me

Backend builds, deployments and VPS setup, and data cleaning and reporting.
Open to full-time roles and contract work.

[LinkedIn](https://www.linkedin.com/in/ebuka-dike-99213b241/) · [tenantly.shop](https://tenantly.shop)
