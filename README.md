# FitLoop — Local Clothing Alterations Marketplace Prototype

FitLoop is a marketplace prototype designed to make clothing alterations easier to arrange and to reduce unnecessary clothing returns.

The idea is simple: instead of returning clothes that are almost right, customers can find trusted local tailors, describe what needs changing, compare quotes and follow the alteration through to completion.

I built the interactive website for a **Generating Genius Entrepreneurship Genius** competition and deployed the domain publicly for the presentation.

![FitLoop homepage](docs/screenshots/home.png)

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

![How FitLoop works](docs/screenshots/how-it-works.png)

## Product / design approach

I took inspiration from marketplace products such as **Vinted** and **Depop**, particularly their simple discovery patterns and consumer-friendly presentation, while designing FitLoop around the specific problem of local alterations.

The demo used realistic-looking profiles, prices, messages and booking states so that the full customer journey could be presented rather than just showing static slides.

## Important prototype limitation

FitLoop was built as a **live interactive demo**, not as a production marketplace.

The repository does **not** contain real multi-user authentication, real payments, real quote delivery, production messaging or a live marketplace database. Demo state is stored locally in the browser and profiles/quotes are demonstration data.

That distinction is intentional: the project was built to test and communicate the product idea for an entrepreneurship competition.

## Main technologies

TypeScript · React 19 · Next.js 16-style App Router via vinext · Vite · Tailwind CSS · Cloudflare tooling

## Run locally

Node 22.13+ is recommended.

```powershell
npm ci
$env:WRANGLER_LOG_PATH = '.wrangler/wrangler.log'
npx vinext dev
```

Then open the local URL printed by the development server (normally `http://localhost:3000`).

## Known issues

The preserved project intentionally still contains some issues from the original competition build, including lint errors, missing standalone Cloudflare types and stale starter tests. The production vinext build itself was successfully validated in the cleaned export.

See [`PROJECT_REPORT.md`](PROJECT_REPORT.md) for the full inspection report.

## AI-assisted development

I used AI-assisted coding heavily to build and iterate FitLoop quickly. I directed the product, UX, feature decisions and repeated revisions, while AI tools generated and modified substantial parts of the implementation.

The project is therefore best understood as a product/engineering prototype showing how I used AI tools to turn an idea into a working interactive experience — not as a claim that every line was written manually.
