---
name: marketing-method
description: >-
  Builds a messaging architecture and an activation matrix so the story is
  told in the right place, from the start. Use when the user wants to run
  marketing-method, write messaging, decide what to say where, or is leaving
  marketing until after the product is done.
---

# A method to the marketing

Inspired by Tony Fadell's *Build*. Encode the method, not the book. Do not quote the book.

## Goal

Marketing is how you tell the truth about the product, in context. It starts when the product starts. The PM owns it. It is not a coat of paint at the end, and it is not a place to say everything everywhere.

Two living documents:

1. **Messaging architecture.** The whole narrative: why they want it (heart) and why they need it (the pain, and the painkiller). Plus the honest answer to each real objection.
2. **Activation matrix.** Which piece of that story shows up at which touchpoint, so people are not flooded and not left in the dark.

Product and message change each other. If a claim cannot be said in a sentence, on a page, and on the thing itself, it is not ready.

## Before you start

1. Read `templates/marketing.md`.
2. Read `ideas/<slug>.md`, the story, and `ideas/<slug>-journey.md` if they exist.
3. If there is no sayable why, run `product-story` first.
4. If the touchpoints are blank, run `customer-journey` first, or draft the stages with them now.
5. Ask. Do not invent claims, stats, testimonials, or partnerships.

## Interview

Ask in batches of 2–3.

1. **Why I want it:** The feeling. Fear, hope, relief. One line a person would repeat.
2. **Why I need it:** Each real pain, and the painkiller in the product that meets it. If the painkiller is a feature with no pain, cut it.
3. **Not this:** What people will assume, and the true correction.
4. **Objections:** The ones a skeptical buyer actually says. How you answer without a trick. If you cannot answer, the product or the claim has to change.
5. **Where it is said:** For each journey stage (hear, consider, get it, first use, stuck, stay), the one thing they need. What you will not say there.
6. **In context:** Pick one surface (headline, box, first screen, support reply). What came before it, what comes after, who lands there.
7. **Truth:** Any claim a careful person would soften ("saves" vs "can save"). Name it. Do not ship a white lie.
8. **Generation 1:** Which lines must be true on day one. The rest wait.

## Cut

Reject: a campaign plan, a channel budget, or a slogan with no pain behind it. Reject saying the full architecture at every step.

If product and marketing disagree, fix the product or the words in this session. Do not leave two stories.

## Save

Write `ideas/<slug>-marketing.md` from the template. Mark unknown claims as `unknown`.

This is a living page. When Generation 1 changes, update the architecture before you update the ads.

Next: `customer-journey` if a stage has no home for the message, or `prototype-before-powerpoint` to walk someone from the first line to the first use.
