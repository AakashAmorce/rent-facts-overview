# Rent Facts project overview

**Tenant reviews from identity-verified renters**, starting with 3,379 Oakland properties. Live at [rentfacts.io](https://rentfacts.io).

> This repo describes what Rent Facts does and how it's built. The source code is private.

## What it does

Renters verify their identity and then review a property. The site has its own moderation for reviews.

## Design choices

- **Pending states.** Claims and verifications start in explicit pending states.
- **Restricted views.** Personal information sits behind restricted views, and the database uses row-level security.

## How I built it

I directed a contract engineer for seven months, from Dec 2025 to Jul 2026. Then I took over the codebase and shipped the build for an August 2026 test with real users.

I build with Claude Code. I write the requirements and review the output until it holds up.

---
[Profile](https://github.com/AakashAmorce) · [aakashdesai.com](https://aakashdesai.com)
