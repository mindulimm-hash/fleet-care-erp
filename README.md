# Fleet Care ERP — AI-built management system for a truck-care company

Production ERP built by **orchestrating AI coding agents** for *Premium Estética de Caminhões*, a B2B company that cleans, polishes and maintains heavy trucks for logistics carriers in Brazil.

**In daily use since Sep 2026 · 152 merged pull requests · 200+ versioned releases**

## Results
- Billing cycle cut from **3 days to 1 hour** (~95% less manual work)
- Serves **41 corporate fleet clients**, ~**260 trucks/month**, team of **12 technicians**
- Payments reconcile automatically against bank statements

## Features
- **Government e-invoicing (NFS-e):** XML generation, X.509 digital signature, cancellation events, hourly sync with the national API, multiple issuers
- **Banking & payments:** Santander bank-slip API, Pix, Getnet card reconciliation, OFX bank-statement parser with automatic matching, split payments
- **Automated billing:** report + invoice + bank slip in one PDF, sent by WhatsApp and email
- **Commissions:** PostgreSQL triggers recalculate staff commissions automatically; staff earnings portal
- **AI owner assistant:** LLM with tool calling over business data
- **SaaS mode:** guided bank onboarding (Itaú, Bradesco, BTG, C6, Cora, Efí), subscriptions, demo mode with in-memory database
- **Security:** Row Level Security, encrypted vault for certificates, PWA push notifications

## Stack
React · Vite · TypeScript · Supabase (PostgreSQL, Edge Functions/Deno, RLS, cron) · Vercel · Cloudflare · Render

## How it was built
Planned and shipped with an agentic workflow: specs → plans → parallel AI subagents in git worktrees → automated tests and code-review agents → human review → deploy.

> Source code is private (real client, tax and banking data). Live demo available on request.
