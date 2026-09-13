---
name: data-versus-opinion
description: >-
  Classifies a product decision as data-driven or opinion-driven and stops
  fake analysis. Use when the user wants to run data-versus-opinion,
  data-not-opinions, is stuck in A/B theater, or cannot decide.
---

# Data versus opinion

Inspired by Tony Fadell's *Build* (data vs. opinion). Encode the method, not the book. Do not quote the book.

## Goal

Name the **type of decision**. Data cannot solve an opinion problem. Opinion cannot hide where data exists. Do not turn vision into a dashboard to avoid owning the call.

## Before you start

1. Read `templates/data-versus-opinion.md`.
2. Read `ideas/<slug>.md` and Gen 1 / story files if they exist.
3. Ask. Do not invent metrics.

## Interview

1. **The decision**: What ships or dies if we choose?
2. **Type**: Can we acquire facts that would make most of the team agree? → **data-driven**. Is this the shape of the product, the story, the first generation? → **opinion-driven** (vision + customer insight; data comes later).
3. **Generation**: Gen 1 is guided by **vision, then customer insight, then data**. Later generations flip: data, insight, vision. Do not run a Gen 3 process on a Gen 1 product.
4. **If data-driven**: What fact, by when, who gathers it. Vanity (downloads, likes, time-on-page) is not a fact that decides.
5. **If opinion-driven**: Whose call, why their gut is trained here, what you already heard from customers. Walk the why. This is not a vote.
6. **Analysis paralysis**: More data that will stay inconclusive? Stop collecting. Make the opinion call or kill the idea.
7. **Cover**: "We followed the data" is not an excuse to skip a vision call.

## Save

Write `ideas/<slug>-decision.md`. If the decision *is* data-driven, also fill `templates/experiment-plan.md` into `ideas/<slug>-experiments.md`.

Next: `kill-or-keep` if a miss should stop the product; `product-story` if they are using metrics because they cannot say why.
