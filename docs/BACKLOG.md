# Product Backlog (Campus Market)

> Source-of-truth index of planned work. Each row links to a GitHub Issue.
> Format: ID, Title, Type, Priority, Story Points, Sprint, Status, Issue

| ID   | Title                                           | Type   | Priority | SP | Sprint    | Status    | Issue |
|------|--------------------------------------------------|--------|----------|----|-----------|-----------|-------|
| CM-1 | API scaffold + `/healthz`                        | Story  | Must     | 2  | Sprint 1  | Planned   | #<issue-number> |
| CM-2 | Local Postgres (Docker) + DB schema v1          | Story  | Must     | 3  | Sprint 1  | Planned   | #<issue-number> |
| CM-3 | Auth skeleton (campus email + JWT)              | Story  | Must     | 3  | Sprint 1  | Planned   | #<issue-number> |
| CM-4 | Listings CRUD (create/read/update/mark-sold)    | Story  | Must     | 5  | Sprint 1  | Planned   | #<issue-number> |
| CM-5 | Wireframes: Home, Detail, Create                | Task   | Should   | 2  | Sprint 1  | Planned   | #<issue-number> |

## Conventions
- **Priority** uses MoSCoW: Must / Should / Could / Won’t (this sprint)
- **Type**: Story (user-facing capability) or Task (supporting work)
- **SP**: Story Points (1–5 simple scale)
- **Status**: Planned → In Progress → In Review → Done (match board columns)
- **Issue**: link to GitHub issue number (e.g., `#12`). Update after issues exist.

## Backlog (Later Sprints)
| ID   | Title                                           | Type  | Priority | SP | Sprint | Status  | Issue |
|------|--------------------------------------------------|-------|----------|----|--------|---------|-------|
| CM-6 | Image upload via S3 pre-signed URLs             | Story | Should   | 3  | TBD    | Planned | #<issue> |
| CM-7 | Search & filters (keyword, category, price)     | Story | Must     | 3  | TBD    | Planned | #<issue> |
| CM-8 | Chat MVP (WebSocket)                            | Story | Should   | 5  | TBD    | Planned | #<issue> |
| CM-9 | Report listing + Admin moderation queue         | Story | Should   | 3  | TBD    | Planned | #<issue> |
| CM-10| CI pipeline (GitHub Actions)                    | Task  | Could    | 2  | TBD    | Planned | #<issue> |
| CM-11| Deploy API+DB on AWS (ALB + Auto Scaling)       | Story | Could    | 5  | TBD    | Planned | #<issue> |

## Notes
- This file is the **index**. The **details live in GitHub Issues** (acceptance criteria, discussion, PR links).
- Update the **Issue** column with the real numbers after you create/convert issues.
- Keep a copy of the original PDF in `docs/backlog/` for reference (next step).

