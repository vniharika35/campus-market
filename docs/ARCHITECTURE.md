# Architecture (High Level)
Web (React) → API (Node/Express) → Postgres; S3 for images; Redis for chat/pubsub.

Endpoints (first pass):
- Auth: POST /api/auth/login, GET /api/auth/me
- Listings: CRUD + mark-sold
- Uploads: POST /api/uploads/sign (S3 pre-signed URL)
- Chat: WS /ws
- Admin: reports

ADRs live in docs/adr/ADR-00X.md (short: context, decision, consequences).
