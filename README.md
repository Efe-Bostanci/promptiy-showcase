# Promptiy

> **AI prompt marketplace and output library** — a platform for discovering, sharing, and monetizing high-quality prompts and their outputs.

---

## Concept

Promptiy started as a prompt marketplace — a place to buy and sell engineered prompts for LLMs. Through iteration, the model evolved toward an **Output Library**: instead of selling prompts, the platform sells the *outputs* themselves (generated images, documents, analyses, templates) as ready-to-use digital products.

The insight: most users don't want to learn prompt engineering — they want the result.

---

## Product Evolution

| Phase | Model | What was sold |
|-------|-------|---------------|
| v1 | Prompt Marketplace | The prompt itself |
| v2 | Output Library | The AI-generated output (image, doc, template) |

This pivot was driven by user behavior observation: prompt quality is hard to evaluate before purchase, but output quality is immediately visible.

---

## Stack

**Frontend:** Next.js 14 · TypeScript · Tailwind CSS  
**Backend:** Supabase (Postgres + Auth + Storage)  
**Payments:** Lemon Squeezy  
**Deployment:** Vercel  

---

## What I Built

- Prompt/output listing and browse experience
- Creator upload flow (prompt + generated output pairing)
- Storefront with category filtering
- Lemon Squeezy checkout integration
- Supabase auth + storage pipeline for output files

---

## Key Learnings

- Digital product marketplaces have a severe cold-start problem on both sides (creators and buyers)
- Output-first framing converts better than prompt-first framing in user testing
- The pivot from "sell prompts" to "sell outputs" is a fundamentally different product — requires a different creator onboarding flow

---

## Status

⚪ **Built · Pivoted · Codebase private**

> Development paused in favor of [Councily.ai](https://github.com/Efe-Bostanci/councily-showcase). Promptiy's architecture and learnings directly informed Councily's monetization model.
