<p align="center">
  <a href="https://portfolio.regar.tj/en/">
    <img src="https://portfolio.regar.tj/og-en.png" alt="Navruz Qudratov — Software Engineer, Tajikistan" width="820">
  </a>
</p>

<h1 align="center">Navruz Qudratov</h1>

<p align="center">
  <b>Software engineer</b> · Tursunzoda, Tajikistan · working remotely worldwide<br>
  <sub>Customer acquisition and business process automation</sub>
</p>

<p align="center">
  <a href="https://portfolio.regar.tj/en/"><img src="https://img.shields.io/badge/portfolio-regar.tj-E9B949?style=flat-square&labelColor=08080A" alt="Portfolio"></a>
  <a href="https://t.me/qudratovnk"><img src="https://img.shields.io/badge/Telegram-@qudratovnk-8A8A97?style=flat-square&labelColor=08080A" alt="Telegram"></a>
  <a href="mailto:qudratovnk@gmail.com"><img src="https://img.shields.io/badge/email-qudratovnk@gmail.com-8A8A97?style=flat-square&labelColor=08080A" alt="Email"></a>
  <img src="https://img.shields.io/badge/status-open%20for%20work-3DDC97?style=flat-square&labelColor=08080A" alt="Open for work">
</p>

---

I design and ship the systems small businesses actually run on — storefronts that take
orders overnight, tills that keep working when the connection drops, and back offices
that report net profit instead of guessing at it.

I work alone and end to end: architecture, code, infrastructure, deployment and support.
No account manager in between — you talk to the person writing the code.

---

## Currently building

### 🟢 [SAMEGA](https://samega.tj) — in production

An e-commerce platform for clothing and footwear with delivery across Tajikistan.
Customers order without a phone call, the order reaches the manager's Telegram in
seconds, stock deducts itself, and the owner sees **net profit per item** rather than
raw turnover.

`Next.js 15` `React 19` `TypeScript` `PostgreSQL` `Redis` `Prisma` `Docker` `Nginx`

- Bilingual storefront (Russian / Tajik) with a locale-aware catalogue
- Full admin: order pipeline, inventory with landed cost, reporting, Excel export
- Multi-level referral programme with non-cashable store credit
- Telegram bot — order notifications, product publishing, two-factor login
- PWA with web push and an offline page
- Per-request CSP nonce, CSRF protection, JWT with refresh-token rotation

### 🟡 REGAR CRM — in development

A point-of-sale and bookkeeping system for small businesses: retail, cafés, delivery,
services. The design goal is that **it does not stop when the connection drops** — shifts,
receipts, stock and customer debts are written on the device and reconcile themselves once
connectivity returns, without losing or double-counting money.

`Yjs CRDT` `y-websocket` `Next.js` `Prisma` `PostgreSQL RLS` `Docker`

- Offline-first on CRDTs: edits from several devices merge without conflicts
- A business-rule gate in front of the write model — stock never goes negative, debt
  limits hold, and state transitions are validated before projection
- Multi-tenant, with isolation enforced twice: Prisma middleware and Postgres RLS
- Stock is stored as a movement log rather than a single number, so merges stay
  commutative and no quantity is ever silently overwritten

---

## What I can help with

| | |
|---|---|
| **Lead-generating sites** | Property developers with a live unit-availability grid and payment calculator; enquiries delivered to Telegram instantly |
| **Online stores** | Catalogue, checkout, inventory, cost tracking, profit reporting |
| **Custom CRM / ERP** | Orders, stock, customers, debts, payroll — offline-capable where it matters |
| **Automation** | Telegram bots, scheduled reports, Excel imports, service integrations |
| **Performance & SEO** | Core Web Vitals, structured data, multilingual `hreflang`, technical audits |

---

## Stack

**Core** — TypeScript · Next.js (App Router) · React · Node.js
**Data** — PostgreSQL · Prisma · Redis · Yjs CRDT
**Infra** — Docker Compose · Nginx · Hetzner · Cloudflare · GitHub Actions
**Also** — Python · WebSockets · Web Push · schema.org · sharp

I care most about the parts nobody notices when they work: data integrity, predictable
failure modes, and pages that open fast on a weak mobile connection.

---

## Working together

- Scope, price and deadline fixed in writing before anything starts
- 50% deposit, 50% on acceptance — the same rule in both directions
- Source code, domain and every credential transfer to you on final payment
- Languages: Tajik (native), Russian (fluent), English (fluent)

**[portfolio.regar.tj](https://portfolio.regar.tj/en/)** · **[Telegram @qudratovnk](https://t.me/qudratovnk)** · **[qudratovnk@gmail.com](mailto:qudratovnk@gmail.com)**

---

<details>
<summary><b>🇷🇺 По-русски</b></summary>

<br>

Я **программист-инженер** из Турсунзаде. Строю системы, на которых реально работает
малый бизнес: магазины, принимающие заказы ночью; кассы, которые не встают без интернета;
учёт, который показывает чистую прибыль, а не догадки.

Работаю один и целиком: архитектура, код, инфраструктура, деплой, поддержка.
Между вами и человеком, который пишет код, нет менеджера.

**Что уже работает**

- **[SAMEGA](https://samega.tj)** — интернет-магазин в продакшне. Заказ доходит до
  менеджера в Telegram за секунды, склад и себестоимость считаются сами, владелец видит
  маржу по каждому товару. Next.js 15, PostgreSQL, Redis, Docker.
- **REGAR CRM** — касса и учёт для малого бизнеса. Главное: не останавливается, когда
  пропадает связь. Чеки, склад и долги пишутся на устройстве и сходятся сами.
  Yjs CRDT, мультитенантность с изоляцией на уровне базы данных.

**Чем могу помочь** — сайты, которые приводят заявки; интернет-магазины; CRM и учёт;
автоматизация рутины через Telegram-ботов и отчёты; скорость загрузки и позиции в поиске.

**Условия** — состав работ, цена и срок фиксируются письменно до начала. Оплата пополам:
половина в начале, половина после приёмки. Исходный код, домен и все доступы переходят
к вам после полной оплаты.

**[portfolio.regar.tj](https://portfolio.regar.tj/ru/)** · **[Telegram @qudratovnk](https://t.me/qudratovnk)** · **[qudratovnk@gmail.com](mailto:qudratovnk@gmail.com)**

</details>
