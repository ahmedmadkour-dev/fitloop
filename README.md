# FitLoop — Local Clothing Alterations Marketplace Prototype

FitLoop is a marketplace prototype designed to make clothing alterations easier to arrange and to reduce unnecessary clothing returns.

The idea is simple: instead of returning clothes that are almost right, customers can find trusted local tailors, describe what needs changing, compare quotes and follow the alteration through to completion.

I built the interactive website for a **Generating Genius Entrepreneurship Genius** competition and deployed the domain publicly for the presentation.

## Problem

A lot of clothes are returned because the fit is slightly wrong rather than because the customer dislikes the item.

FitLoop explored whether a local alteration marketplace could make fixing that problem easier by bringing discovery, requests, quotes and booking progress into one experience.

## What I built

- responsive marketplace landing experience
- tailor discovery and profile cards
- filters for area, service, verification and collection options
- saved tailors
- multi-step alteration request flow
- sample/photo selection
- simulated quote comparison
- quote acceptance
- booking status tracker
- customer and tailor demo dashboards
- local messaging simulation
- retailer-supported alteration demo flow

## Product / design approach

I took inspiration from marketplace products such as **Vinted** and **Depop**, particularly their simple discovery patterns and consumer-friendly presentation, while designing FitLoop around the specific problem of local alterations.

The demo used realistic-looking profiles, prices, messages and booking states so that the full customer journey could be presented rather than just showing static slides.

## Competition context

FitLoop was presented at the 2026 Generating Genius Entrepreneurship Genius Business Competition. The website and presentation received positive feedback from judges and programme staff, and I received an Outstanding Individual award at the event.

## Important prototype limitation

FitLoop was built as a **live interactive demo**, not as a production marketplace.

The repository does **not** contain real multi-user authentication, real payments, real quote delivery, production messaging or a live marketplace database. Demo state was stored locally in the browser and profiles/quotes were demonstration data.

That distinction is intentional: the project was built to test and communicate the product idea for an entrepreneurship competition.

## Main technologies

TypeScript · React 19 · Next.js 16-style App Router via vinext · Vite · Tailwind CSS · Cloudflare tooling

## Current portfolio format

This public repository currently documents the project as a portfolio case study. The cleaned source export is being kept separately rather than automatically publishing the entire competition codebase.

See [`PROJECT_REPORT.md`](PROJECT_REPORT.md) for the technical/project report.

## AI-assisted development

I used AI-assisted coding heavily to build and iterate FitLoop quickly. I directed the product, UX, feature decisions and repeated revisions, while AI tools generated and modified substantial parts of the implementation.

The project is therefore best understood as a product/engineering prototype showing how I used AI tools to turn an idea into a working interactive experience — not as a claim that every line was written manually.
