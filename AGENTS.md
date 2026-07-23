# Documentation project instructions

## About this project

- Mintlify docs for **Proprietas** (UK estate management)
- Pages are MDX with YAML frontmatter
- Config: `docs.json`
- Local preview: `npx mintlify dev` (from this folder)
- Broken links: `npx mintlify broken-links`

## Product framing

- Audience: UK estates teams (MATs, care, healthcare, managing agents, campuses)
- Pillars: statutory compliance · lease intelligence · facilities
- Pricing is published (£199 / £699 / £2,499+/mo) — never "contact sales"
- Product app: `my.proprietas.app` · marketing: `proprietas.app`

## IA

Navigation is **flat product groups** in `docs.json` (not Overview / Guides / Interface tabs):

1. Get started
2. Compliance
3. Files & AI (app sidebar label is **Files**)
4. Leases & rent
5. Facilities
6. Using the product (shell: search, assistant, desktop, MCP, calendar sync, …)
7. Members & access
8. Billing
9. Security
10. Roadmap — three buckets only: **What's live** · **Working on now** · **Further out**. Never claim live what is still planned; flip items only when shipped.

Put feature how-tos under the pillar they belong to. Put shell/UX surfaces under **Using the product**. Match app names where they differ from pillar names (Files, Properties, Work Orders).

## Style

- Active voice, second person ("you")
- Sentence case headings
- Bold UI labels: open **Settings → Members**
- Prefer short pages over encyclopedias
- Keep roadmap honest: live vs coming next
