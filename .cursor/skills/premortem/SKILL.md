---
name: premortem
description: >-
  Looks up from the work: if this failed in 18 months, why, and what stop
  rules you need now. Use when the user wants to run premortem, fears
  silent failure, or the mission may no longer make sense.
---

# Look up

Inspired by Tony Fadell's *Build* (don't only look down). Encode the method, not the book. Do not quote the book.

## Goal

Look **up** at the mission and **around** at other functions, not only at this week's tasks. Imagine it is 18 months later and this failed. Specific causes. Early signals. Stop rules you can act on now.

If the mission no longer makes sense, or the path is not achievable, that is a product decision.

## Before you start

1. Read `templates/premortem.md`.
2. Read one-pager, Gen 1, decision files if they exist.
3. Ask. Do not write generic "market risk."

## Interview

1. **Mission**: Why you started. Does it still make sense.
2. **Failure headline**: What the team would say later.
3. **Causes**: Story, distribution, customer, team, timing, trust. Specific (the named person never did the first action, not "low engagement").
4. **Look around**: What other functions would have seen first.
5. **Early signals**: 30/90 days.
6. **Stop rule**: Dated criterion per serious cause.

## Cut

If every mitigation is "hire more" or "raise," the look-up failed. Change Gen 1 or KILL.

## Save

Write `ideas/<slug>-premortem.md`. Offer `kill-or-keep` to formalize criteria.
