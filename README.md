# Hood Boss Team Lead OS

A professional, offline-capable Team Lead selection + readiness + field execution system built from the uploaded Hood Boss Team Leads source packet.

## What works now
- Create and manage Team Lead candidates
- Qualification/readiness gate checklist
- Source-grounded structured interview
- Evidence notes and 1–5 interview scoring
- Team Lead field execution checklist
- Work-order state flow
- Control Tower check-in / approval outcomes
- automatic readiness summary
- candidate print view
- JSON backup/export + restore/import
- local audit history
- browser localStorage persistence
- installable PWA shell
- responsive mobile/desktop layout
- custom NEXUS Core icon as a subtle system signature

## Run
Open `index.html` in a modern browser.

For full PWA/offline install behavior, serve the folder over HTTP:
- Python: `python -m http.server 8080`
- then open `http://localhost:8080`

## Product identity
The product-facing identity is **Hood Boss Team Lead OS**.
NEXUS is intentionally treated as the underlying system signature, not as a replacement for Hood Boss branding.

## Production evolution
Recommended next architecture:
- React/TypeScript or Next.js
- Supabase/Postgres
- SSO/auth + role-based access
- append-only audit log
- manager approval workflow
- encrypted attachments
- integration adapters for MyTechPix / FieldPulse / Teams
- signed interview and promotion packets
- analytics for candidate pipeline and post-promotion outcomes

## Source integrity
See `SOURCE-MAP.md`.
