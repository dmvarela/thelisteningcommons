# The Listening Commons — MVP Build Plan

## Goal

Build the smallest usable version of The Listening Commons: a living platform where people can submit AI-assisted research with disclosure, human explanation, and community validation.

## Phase 0 — Concept Validation

Deliverables:
- Charter
- Submission form
- Paper page template
- Validation rubric
- Contribution modes
- 3–5 sample paper pages

Purpose:
Test the idea with trusted readers before writing code.

## Phase 1 — Manual Prototype

Tools:
- Simple website
- Submission form using Tally, Typeform, Google Forms, or custom form
- Manual moderation
- Static paper pages
- Embedded comments or moderated review form

Features:
- Homepage
- About/Charter page
- Submit page
- Browse page
- Paper pages
- Manual validation status updates

Why manual first:
The community norm matters more than the software. Manual moderation prevents early pollution and helps refine the submission process.

## Phase 2 — Platform MVP

Suggested stack:
- Astro or Next.js for frontend
- Supabase for database, auth, and storage metadata
- Cloudflare Pages for hosting
- Cloudflare R2 or Supabase Storage for PDFs
- GitHub for code and governance

Core database tables:
- users
- papers
- paper_versions
- ai_disclosures
- reviews
- validation_votes
- comments
- status_history
- tags

Core features:
- user accounts
- submit paper
- upload PDF
- paper page
- contribution mode labels
- AI-use disclosure
- review form
- Listening Scale vote
- comments
- version history
- moderation queue

## Phase 3 — Community Validation

Features:
- reviewer profiles
- expertise tags
- reference-check badges
- expert review labels
- status changes
- public review history
- report/correction workflows
- challenged/superseded/retracted statuses

## Phase 4 — Scholarly Infrastructure

Features:
- ORCID login
- citation export
- DOI links through Zenodo or other services
- GitHub/code integration
- version DOI strategy
- institutional advisory board
- moderation guidelines
- ethics policy
- license options

## First Seed Papers

Possible launch papers:
- Covenant and Vessel
- Triadic Regulation in Intelligent Agents
- FTLτA
- Conformal Disclosure
- Urgency as Attack Surface

## Success Criteria for Pilot

The pilot works if:

1. Submitters can explain their ideas in their own words.
2. AI use is disclosed honestly.
3. Readers can distinguish promising ideas from weak output.
4. Reviews improve papers.
5. The site does not become a slop repository.
6. The community understands that posting is not validation.
