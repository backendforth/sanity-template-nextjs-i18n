# Submission — sanity.io/templates listing

Working doc for getting this template listed in the [Sanity templates gallery](https://www.sanity.io/templates). Not consumed by any tooling — safe to delete after approval.

## Draft copy

**Title**

> Next.js Multilingual Starter — field-level i18n, module pattern, Visual Editing

**Description**

> A production-shaped monorepo template for multi-language, CMS-driven sites: Next.js 16 (App Router, React 19) + Sanity Studio v6, managed with pnpm workspaces.
>
> Content is composed from a strict module pattern — every block is a paired Sanity object + React component, wired across schema, renderer, GROQ projection, and hand type, with a scaffolder (`pnpm gen:module`) and a CI wiring check keeping the pattern honest. Internationalisation is field-level via `sanity-plugin-internationalized-array`: languages are configured in a Studio singleton at runtime, GROQ ships full i18n arrays, and a render-time resolver applies the fallback chain — adding a locale requires zero code changes.
>
> Included: Visual Editing / Presentation with Draft Mode and stega, hardened signed-webhook revalidation, per-locale sitemap + hreflang metadata, Mux video, Tailwind CSS v4 design tokens, Biome, typed GROQ via `sanity typegen`, and AGENTS.md guardrails for AI coding assistants.

## Submission checklist

- [ ] Repo public: `https://github.com/backendforth/sanity-template-nextjs-i18n` ✓ (created public)
- [ ] `template-validate` workflow green on `main`
- [ ] Screenshot/hero image, **1200 × 750 px** (web front page or Studio + site side-by-side)
- [ ] Deployed example application (strongly recommended — Netlify config ships in the repo)
- [ ] Submit via the [Community Studio starter intent](https://community.sanity.tools/intent/create/type=contribution.starter;template=contribution.starter/): title, description, repo link, image, demo URL

## Post-approval

- Announce on LinkedIn / X / Bluesky.
- Join `#template-creators` in the Sanity community Slack.
- Keep dependencies fresh (Dependabot is configured monthly) — the validator runs on every PR, so template consumability is CI-gated.
