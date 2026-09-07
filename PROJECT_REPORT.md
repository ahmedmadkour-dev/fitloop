# FitLoop — Project Report

## Purpose

FitLoop was a live interactive marketplace prototype built for a Generating Genius entrepreneurship competition. The idea was to make clothing alterations easier to arrange by helping customers find local tailors, describe what needs changing, compare quotes and follow the job through to completion.

## My contribution

I personally built the website/prototype and directed the product and visual experience. I took design inspiration from major consumer marketplace apps such as Vinted and Depop, bought the domain and deployed it publicly for the competition presentation.

## Technical stack

- TypeScript / TSX
- React 19
- Next.js 16-style App Router conventions through vinext
- Vite
- Tailwind CSS
- Cloudflare tooling

## Implemented prototype flows

- responsive landing/marketplace experience
- tailor discovery and profile cards
- service/location/verification filters
- saved tailors
- multi-step alteration request flow
- image/sample selection
- simulated quote comparison and acceptance
- booking-status tracker
- customer and tailor dashboards
- local messaging simulation
- retailer alteration journey

## Important scope distinction

FitLoop was a **working interactive demonstration**, not a production marketplace. Profiles, prices, quotes and messages were demonstration data. It did not have real multi-user authentication, real payments, production messaging or a live shared marketplace database.

That distinction matters because the goal of this build was to make the business concept tangible for judges rather than launch a commercial service.

## Competition context

The project was presented at the 2026 Generating Genius Entrepreneurship Genius Business Competition. The website and presentation received positive feedback from judges and programme staff. I also received an Outstanding Individual award at the event.

## Validation of the preserved copy

During portfolio cleanup, the vinext production build succeeded. The original competition build still contains some lint/type/starter-test issues that were deliberately documented rather than silently rewritten after the fact.

## What I learned

The project taught me that a polished product demonstration can make an idea much easier to understand, but a convincing interface is not the same thing as a validated business. The competition also exposed gaps in our investor preparation — particularly valuation and the investment ask — which became an important commercial lesson.

## AI-assisted development

I used AI-assisted coding heavily while building and iterating FitLoop. I directed the product, UX, feature decisions and revisions while AI generated and modified substantial parts of the implementation. I present it as an AI-assisted product/engineering prototype rather than claiming every line was written manually.
