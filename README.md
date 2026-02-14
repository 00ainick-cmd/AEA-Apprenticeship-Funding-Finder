# AEA Apprenticeship Funding Finder

Interactive tool for AEA member shops to discover apprenticeship funding opportunities — federal programs, state tax credits, veteran benefits, and workforce grants.

**Built by the Aircraft Electronics Association (AEA)**

## What This Is

A single-page web tool that helps Part 145 repair stations and avionics shops find money they're leaving on the table by not having a registered apprenticeship program.

Select your state → see every federal and state funding opportunity → click for details, eligibility, and how to apply → see how programs stack together.

## How It Works

- `index.html` — The funding finder tool
- `apprenticeship-guide.html` — Interactive apprenticeship requirements reference
- `data/grants.json` — Structured funding database (all entries source-verified)
- `research/` — Source research documentation with .gov citations

## Data Sources

Every funding entry is sourced from official government websites. Source URLs, statute numbers, and verification dates are included in the data and displayed in the tool.

See `research/funding-database.md` for the full research documentation with citations.

## Verification Status

Items flagged with ⚠️ need additional verification before presentation. See the `verificationNeeded` section in `grants.json` for specifics.

## Deployment

Static site — no backend required. Deploy via GitHub Pages, S3/CloudFront, or any static host.

## Context

This tool supports the AEA/Fastport registered apprenticeship program for Avionics Technicians (O*NET 49-2091.00). Fastport handles DOL compliance. AEA provides Related Technical Instruction (RTI) through CAET training. Member shops join the national program with a one-page Employer Acceptance Agreement.

## License

© 2026 Aircraft Electronics Association. All rights reserved.
