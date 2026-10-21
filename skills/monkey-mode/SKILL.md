---
name: monkey-mode
description: Explain a long or heavy topic visually, one layer at a time, as a "ladder" of stacked HTML pages — pictures first, words as captions, advancing only when the user says "next". Use when the user says "monkey mode", "explain like I'm a monkey", "explain like I'm a dumb person", "make me a ladder", or is clearly tired and stuck on a big concept. Also offer it (don't force it) when one concept has taken several rounds of back-and-forth and still isn't landing.
---

# 🐒 Monkey Mode

Explain one topic visually, one layer at a time.

**Assume the user is running on empty** — end of day, fried, sleepy, or sick — and is asking for this *because the topic is long and heavy*. Rule #1 is **minimum reading, maximum intuition.**

## The shape

- **Visual-first, always.** Pictures, emojis, diagrams, flows and color do the explaining. Words are captions, not paragraphs. The user should "get it" from the drawing **before** reading anything.
- **Output format:** an HTML page per rung that works in both light and dark themes. Use whatever your environment offers for rendering HTML (an artifact, a canvas, a local file the user opens in a browser).
- **Plan the whole thing FIRST, then chunk it.** Build the COMPLETE final picture in your head → decide how many levels it genuinely needs (few or many — the topic decides) → split the ideas across levels → hand them over **one level at a time**, advancing only when the user says **"next"**.
- **Each level builds on the one before it** — same story, one layer deeper. Never restart; always extend.
- **The ramp:** Level 1 is almost pure picture with tiny words (a fried brain can follow it half-asleep). As levels climb, get more technical — more words and real detail become acceptable, because understanding has been built underneath. The last level lands on real expert detail (for code: actual file / function / class names).
- **Stack the rungs, don't just link them.** Each new level is its own page that contains the **full content of every earlier level below it**, newest at the top, oldest at the bottom. The user scrolls down to re-read instead of opening another page. The whole thing reads as one connected climb.

## The cast of emojis

- **One emoji per recurring term, fixed for the whole climb.** Bind an emoji to each recurring noun while planning, and reuse that exact emoji every time the term appears on every later rung. Never reassign.
- **Keep the cast small (~8).** Only nouns that *do* something. Abstract ideas and one-off terms stay plain, or it becomes noise.
- **The emoji NEVER replaces the word.** Write the term and put the emoji beside it — "the temp box 📦", never a bare "📦". A bare emoji standing in for a noun forces the reader to decode, which defeats the point.
- **Show a legend of the cast met SO FAR on each rung** — not the whole cast. Mark new faces as new.

## Rules that are easy to get wrong

- **Every rung is self-contained at its own level.** Never name a thing on rung N and explain it on rung N+1. The user must never wait for a later rung to understand an earlier one.
- **Define a metaphor word at first use, in plain terms.** A friendly invented label ("the slip", "the address book") is not self-explanatory. Say what it actually is in one sentence the first time it appears, and never put it in a heading before that sentence.
- **Verify before writing, not after.** Wrong claims cost the user a rebuild. Read the source (code, docs) first; say "unclear" rather than guessing.
- **No unexplained jargon, including your own.** Words like "branch", "mode", "payload" can be read differently than you mean ("branch" can read as a git branch). If you mean an `if` in the code, say so.

## When to offer a ladder unprompted

If a concept has eaten a lot of back-and-forth and the user still isn't getting it — they've asked about the same thing three or more times, said "you lost me" / "I don't get it", or your replies keep needing corrections — **stop explaining in chat and offer to spin that one concept out into its own ladder.** A side concept that blocks them gets its **own** ladder, separate from any ladder already running. Offer it, don't force it.
