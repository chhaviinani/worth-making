---
name: customer-journey
description: >-
  Maps every customer touchpoint from first hearing about it through use,
  help, staying, and leaving. Use when the user wants to run customer-journey,
  map touchpoints, find gaps outside the product, or asks about the full
  customer experience.
---

# Customer journey and touchpoints

Inspired by Tony Fadell's *Build* (make the intangible tangible). Encode the method, not the book. Do not quote the book.

## Goal

Map the **whole trip**, not the object. People discover, consider, buy, start, use, get stuck, stay, and leave. If a step is missing or ugly, they trip, even if the product is beautiful.

Makers stare at the thing they are shipping. Customers walk the path around it. This skill writes that path down, step by step, for one named person.

You do not have to *build* every touchpoint in Generation 1. You do have to *see* them. Name what is real, what is a gap, and what waits.

## Before you start

1. Read `templates/customer-journey.md`.
2. Read `ideas/<slug>.md` and story / Gen 1 files if they exist.
3. Need a named person. If missing, ask, or run `product-story`.
4. Ask. Do not invent ads, support, or a website they do not have.

## Interview

Ask in batches of 2–3. For each step: what they experience, what they feel, what is missing.

1. **Person**: Named, with a life. Not "users."
2. **Why should I care / buy / use / stick**: Four answers, still.
3. **Hear about it**: Search, a friend, press, social, an ad, a store. How do they first meet the story?
4. **Consider**: Site, listing, demo, review, email, a salesperson. Why should they buy?
5. **Get it**: Pay, unbox, download, install, create an account. Where do they hesitate?
6. **First use**: The first minutes. Quick guide, setup, empty state.
7. **Live with it**: Daily use, reliability, updates. Why they stick.
8. **Get stuck**: Error, how-to, support, community. What happens without shame?
9. **Stay or leave**: Renewal, loyalty, return, cancel, a review. The last impression.
10. **Generation 1**: Which touchpoints must be true for the promise to hold? Which are later? Which will you not own?

## Cut

Reject: a map that is only in-app screens. Packaging, the receipt, the hold music, the return, the first Google result all count.

If they cannot answer why someone should care, run `product-story` first.

## Save

Write `ideas/<slug>-journey.md` from the template. Fill every row. Use `unknown` or `gap` rather than fiction.

End with the three trip-ups most likely to kill the story, and which ones Generation 1 must fix.

Next: `design-the-feeling` to script the beats that must feel true, `prototype-before-powerpoint` to make the path walkable, or `version-zero` if the map just exploded the scope.
