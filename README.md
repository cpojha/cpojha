# Chandra Prakash Ojha

**Product engineer and fractional tech partner. I build, run and scale production software — backends that move money, private on-device AI, and the apps on top.**

[![Website](https://img.shields.io/badge/cpojha.com-000?style=for-the-badge&logo=safari&logoColor=white)](https://cpojha.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cpojha)
[![Email](https://img.shields.io/badge/hello@cpojha.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@cpojha.com)
[![Book a call](https://img.shields.io/badge/Book_a_call-006BFF?style=for-the-badge&logo=calendly&logoColor=white)](https://calendly.com/cpojha17/30min)

I started writing code on a phone, before I owned a computer. Today I own products end to end — architecture, code, infrastructure, and staying on call after launch — for startups in the UK, Switzerland, the US and Australia. Based in Bhopal, India.

Most of my work lives in private repositories because it runs real businesses. The write-ups below explain what each system does and how it's built.

---

## What I've built

### 🏦 [RentFB Agency](https://rentfb.agency) — the platform behind an ad-account rental business
*Lead engineer · built for the client · live at [app.rentfb.agency](https://app.rentfb.agency)*

Wallet ledger in exact integer cents, live Meta Marketing API sync with spend caps and auto top-ups, Stripe + bank + UPI payment rails with reconciliation, and an invariant harness that checks 16 financial-correctness rules. A client portal and a ~40-section admin console on one backend.
**2,180+ commits · 149 SQL migrations · 585 test files · 17 background jobs**

`Node.js` `TypeScript` `PostgreSQL` `Redis` `BullMQ` `Stripe` `Meta Marketing API` `Next.js` `Docker`
→ [Architecture](https://github.com/cpojha/rentfb-platform) · [Case study](https://cpojha.com/case-study/rentfb)

### 🔒 [AqVault](https://aqvault.ch) — private document AI that runs on your own computer
*Founder & sole engineer · early access with Swiss law firms*

A desktop app that answers questions about confidential case files with the exact passage behind every point. OCR, hybrid retrieval and the language model all run locally — no cloud AI, no telemetry. Precision mode checks every statement against the source, recomputing figures and dates in code, and can issue an Ed25519-signed certificate.

`Rust` `Tauri 2` `llama.cpp` `SQLCipher` `SQLite FTS5` `React`
→ [Architecture](https://github.com/cpojha/aqvault) · [Case study](https://cpojha.com/case-study/aqvault)

### ✍️ AutoQuill — autonomous content SaaS for WordPress
*Founder · launching soon*

Multi-tenant pipelines that research, write, illustrate and publish 35+ articles per day per site in 12 languages, with a per-tenant circuit breaker and a bring-your-own-key credit system.

`Node.js` `BullMQ` `Redis` `Supabase` `Gemini` `WordPress`
→ [Architecture](https://github.com/cpojha/autoquill) · [Case study](https://cpojha.com/case-study/autoquill)

### 🎟️ BookitSocial — social booking marketplace (Australia)
*Founding engineer · Social ARC Pty Ltd · live on iOS and Android*

The complete backend from scratch: race-condition-safe bookings with PostgreSQL advisory locks, Stripe Connect C2C payouts with a check-in guard, real-time Socket.IO, and a zero-downtime AWS migration (EC2, RDS, SES).

`Node.js` `PostgreSQL` `Stripe Connect` `Socket.IO` `AWS` `React Native`
→ [Case study](https://cpojha.com/case-study/bookitsocial)

### 🎵 Aqua Music — where it started
A Discord music bot I built from a phone that grew to 50,000+ servers.

---

## How I work

- **Ownership, not handoffs.** The same engineer designs it, ships it and keeps it running.
- **Correctness where it matters.** Money is integers, every number has one definition, and invariants are checked continuously.
- **Honest claims.** Figures on this page come from the repositories themselves.

**Stack I reach for:** TypeScript · Node.js · PostgreSQL · Redis/BullMQ · AWS · Stripe · Next.js · React Native · Rust/Tauri · llama.cpp

---

**Working on something that needs a long-term technical owner?** I take one or two partners at a time → [cpojha.com](https://cpojha.com) · [hello@cpojha.com](mailto:hello@cpojha.com)
