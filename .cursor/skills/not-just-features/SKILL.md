---
name: not-just-features
description: >-
  Turns a feature list into a why and a filter: keep, later, or ego. Use
  when the user wants to run not-just-features, is listing capabilities, or
  a roadmap is a pile of features.
---

# Not just features

Inspired by Tony Fadell's *Build*. Encode the method, not the book. Do not quote the book.

## Goal

Replace a feature pile with **why someone should care**, then keep only what serves that why. The path around the product is `customer-journey`. This skill is the object: what you are tempted to build.

## Before you start

1. Read `templates/feature-filter.md`.
2. Read `ideas/<slug>.md` if it exists.
3. Ask. Do not invent the person.

## Interview

Ask in batches of 2–3.

1. **Feature pile**: Get it all out.
2. **Named person**: Life context. What they already use.
3. **Why should they care / buy / use / stick**: Four answers. If any is "because of this feature," keep asking why.
4. **Filter**: Each feature: required for the why / later generation / ego.

## Cut

Reject: admin, settings, and extra surfaces unless they *are* why someone sticks.

If they cannot answer "why should I care?" without a feature, run `product-story`.
If they have never mapped discover through leave, run `customer-journey`.

## Save

Write `ideas/<slug>-features.md`.

Offer `customer-journey` for touchpoints, `version-zero` to lock Generation 1, or `design-the-feeling` to script first use.
