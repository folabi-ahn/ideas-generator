# Tech Stack — WhatsApp Business Automation Service

## Overview

You are running a SERVICE business, not a SaaS. Your job is to configure and manage tools that already exist — not build from scratch. Total monthly tool cost per client: €40–€110.

---

## Core Stack

### 1. WhatsApp API Access — 360dialog
**What:** Meta-approved Business Solution Provider (BSP), EU-hosted
**Why:** GDPR compliant (data stays in EU), agency/reseller program available, good support
**Cost:** ~€10/month base + Meta conversation fees (~€0.05–€0.15 per conversation)
**Agency deal:** Apply for their reseller program — buy at ~50% discount, charge clients retail

**Alternatives if 360dialog waitlist:**
- WATI (faster to start, slightly pricier)
- Respond.io (more features, more expensive)

### 2. Automation / Flow Builder — Make (Integromat) or n8n
**What:** Visual workflow automation tool
**Why:** Connects WhatsApp API to Google Sheets, Calendly, Stripe, CRMs without code
**Cost:**
- Make: €9–€29/month (enough for 5-10 clients on one account)
- n8n cloud: €20/month | n8n self-hosted: free (needs a server ~€5/month)

**Use for:**
- "If customer sends 'book a table' → ask for date/time → add to Google Sheet → send confirmation"
- "Every Tuesday → send broadcast to all contacts in list"
- "If no reply in 24h → send follow-up message"

### 3. Contact Management — Airtable or Google Sheets
**What:** Where the client's customer data lives
**Why:** Simple for clients to understand, easy to update
**Cost:** Free tier covers most small clients

### 4. Chatbot Templates — WATI or Landbot (optional)
If you want a drag-and-drop interface for building flows visually, WATI has a good interface even if you use 360dialog for the API connection.

---

## Your Internal Operations Stack (free/cheap)

| Tool | Purpose | Cost |
|------|---------|------|
| Notion | Client SOPs, project tracking | Free |
| Google Workspace | Email, Sheets, Docs for client delivery | €6/month |
| Loom | Record video walkthroughs for clients | Free tier |
| Calendly | Book onboarding and monthly calls | €8/month |
| Stripe | Payment processing | 1.4% + €0.25 per transaction |
| Airtable | Master client dashboard | Free tier |

**Total your ops cost: ~€15/month**

---

## Per-Client Setup Checklist

**Day 1–2: API Setup**
- [ ] Register client on 360dialog (or your BSP)
- [ ] Submit WhatsApp Business verification (takes 1–3 days)
- [ ] Get client to verify their Facebook Business Manager
- [ ] Set up phone number in BSP dashboard

**Day 3–4: Flow Build**
- [ ] Create welcome/greeting flow
- [ ] Create FAQ auto-reply (collect top 5 questions from client)
- [ ] Build appointment reminder flow (if applicable)
- [ ] Set up broadcast list with existing contacts
- [ ] Connect to Airtable/Google Sheets

**Day 5: Testing + Handoff**
- [ ] Test all flows end-to-end
- [ ] Record a Loom walkthrough for the client
- [ ] 30-min Zoom handoff call
- [ ] Send "go live" confirmation

**Ongoing Monthly (2–3 hours per client):**
- [ ] Send 2–4 broadcast campaigns
- [ ] Review analytics (open rate, response rate)
- [ ] Update FAQ flows if new questions emerging
- [ ] Monthly 15-min check-in call

---

## Time Per Client

| Activity | Time |
|----------|------|
| Initial setup | 4–6 hours |
| Monthly management | 2–3 hours |
| Monthly capacity (solo) | ~50 hours → 15–20 clients |

At 15 clients (€449/month average): **€6,735/month recurring**
At 20 clients: **€8,980/month recurring**

You hit capacity at 20 clients solo. At that point, hire a part-time VA (€15–€20/hour) for setup work and scale further.
