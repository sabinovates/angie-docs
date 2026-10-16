# Angie Docs

User-facing documentation for **Angie** — a multi-tenant SaaS platform that lets alumni associations, professional groups, and community networks run their entire operation online: membership, dues, events, communication, and finance, each on its own branded subdomain.

This repo holds the public documentation site, built with [Mintlify](https://mintlify.com) and published automatically to production on every push to `main`.

## What's covered

The docs walk through every feature available to an association's members and its tenant administrators:

- **Getting Started** — signing up a new association, choosing a pricing plan, first login.
- **Member Guide** — dashboard, profile and privacy, membership card, directory, notifications, account settings (password, 2FA, notification channels), bank accounts, wallet (deposit, withdraw, send), dues and payments, invoices and receipts, donations, events, announcements, meetings, and the photo gallery.
- **Admin Guide** — dashboard, subscription and billing, member management (list, import/export, applications, bulk actions), membership types, groups and committees, events and attendance, gallery management, finance (dues, donations, projects, payments, invoices, refunds), communication (announcements, log, meetings), reports and audit log, users and roles, and every settings page (general, branding, membership, finance, communication, integrations, privacy, security, site management, leadership).
- **Pricing & Plans** — the tiered, member-count-based pricing structure.
- **What's New** — a running log of platform changes, written for association staff and members, not developers.
- **FAQ** — answers to common questions.

Angie Control, the internal operations back-office used by the Angie team to manage associations across the platform, is deliberately out of scope — it's staff-only, not a feature an association or its members need documentation for.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Run from the repo root, where `docs.json` lives:

```bash
mint dev
```

Preview at `http://localhost:3000`.

## Publishing changes

This repo is connected to Mintlify's GitHub app. Pushing to `main` deploys to production automatically — no separate build or deploy step.
