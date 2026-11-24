---
name: morning-brief
description: Write my morning brief in under 120 words: today's meetings, the 3 emails to act on, and one protected focus block. Use when I ask for my morning brief or my day.
---

# Morning Brief

Follow `CLAUDE.md` and `about-me.md`. This skill is read-only: no sending, no deleting, no calendar changes.

## Step 1: Read today's calendar
List all events for today (midnight to midnight, Europe/Vienna). Note each meeting's title and start and end time.

## Step 2: Triage today's unread emails
Hand today's unread emails to the `inbox-triager` agent. Use its **Do now** list as the 3 emails to act on. Do not pick them yourself.

## Step 3: Write the brief
Under 120 words, plain words, in this order:
- **Meetings:** today's meetings with times.
- **Act on (3):** the 3 emails from the Do now list, one short line each.
- **Focus block:** one focus block, taken from my protected focus time in `about-me.md` (15:30 to 17:00). If a meeting overlaps it, pick the largest free part of that window and say it was shortened. If nothing is free, say so and suggest the nearest free slot. Only suggest it. Do not create the event.

Count the words before you answer. If over 120, cut.

## Never
- Never send or delete anything.
- Never create, change or cancel calendar events.
- If unsure, ask me first.
