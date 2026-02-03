# AI-Powered Social Commerce Platform (MVP)

## Overview
This project is an early-stage MVP of a **mobile-first social commerce platform** designed for **growing social sellers** who have outgrown manual order tracking.

The platform helps sellers convert **unstructured social conversations** (Instagram DMs, WhatsApp, Facebook, TikTok, etc.) into **structured orders, payments, and income visibility** — without the complexity of traditional e-commerce or accounting tools.

This repository represents an **MVP focused on core workflows**, not a finished product.

---

## Problem Statement
Social sellers often receive orders through messages and DMs. As order volume increases:
- Orders get lost across platforms
- Manual notes and spreadsheets stop working
- Payment follow-ups become messy
- There is no clear, real-time view of money coming in

Existing tools focus on websites or accounting, but not on **message-first selling workflows**.

---

## Target Users
- Solo sellers and micro-business owners
- Social-first sellers using Instagram, WhatsApp, TikTok, Facebook, or simple websites
- Growing sellers (not beginners, not large enterprises)
- Mobile-first, time-constrained users

---

## Core MVP Features

### ✅ Implemented
- **Unified Social Order Inbox**
  - Centralised order management
  - Converts conversations into structured orders
  - Order status tracking
  - Secure per-user data isolation

- **Payment Tracking**
  - Paid / unpaid / partial payment states
  - Amount received vs pending
  - Simple, order-level payment updates

- **Income Tracker**
  - Daily / weekly income visibility
  - Paid vs pending amounts
  - Order-level contribution to income
  - Designed to evolve into profit insights later

---

### 🔜 Planned (Post-MVP)
- Inventory tracking linked to orders
- Lightweight supplier notes
- Simple public order page (mini-storefront)
- AI-assisted reply suggestions
- AI product description generation
- Multi-language support

---

## Product Philosophy
- **Workflow first, automation later**
- **Simple before powerful**
- **Mobile-first by default**
- Designed for real-world social selling, not enterprise operations

---

## Tech Stack (Current)
- Frontend: Next.js
- Backend: API routes / server-side logic
- Database: PostgreSQL (via Supabase)
- Auth & Security: Supabase Auth + RLS
- AI (planned): OpenAI (assistive use only)

---

## Project Status
This is an **early MVP** built for:
- Learning
- Validation
- Mentor feedback
- Iterative improvement

Not production-ready.

---

## Local Development

```bash
# install dependencies
npm install

# run locally
npm run dev

## Disclaimer

This project is an early-stage MVP built for learning, validation, and mentor feedback.

It is not production-ready. Features, structure, and implementation details may change based on user research and iteration.

