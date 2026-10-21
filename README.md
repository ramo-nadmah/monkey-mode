# 🐒 Monkey Mode

A Claude skill for when your brain is fried and the topic is huge.

Say **"monkey mode"** and Claude explains the topic as a **ladder**: a stack of visual pages, one rung at a time. Rung 1 is almost all pictures. Each "next" adds one layer deeper, and the last rung lands on the real expert detail. Every new rung keeps all the earlier ones below it, so you scroll down to re-read.

Created by **Omar Hamdan**.

## Install (Claude Code)

```
/plugin marketplace add ramo-nadmah/monkey-mode
/plugin install monkey-mode@monkey-mode
```

## Install (claude.ai)

Zip the `skills/monkey-mode` folder and upload it under **Settings → Capabilities → Skills**.

## Use it

- "monkey mode: how does OAuth work?"
- "explain like I'm a monkey: database indexes"
- "make me a ladder for how our queue system works"

Then say **"next"** to climb one rung.

## The rules in short

- Pictures do the explaining; words are captions.
- One emoji per recurring term, always next to the word, never instead of it.
- Each rung shows a legend of the terms met so far.
- Each rung makes sense on its own; nothing is explained "later".
- Every metaphor gets a plain one-line definition the first time it appears.

## License

MIT. See [LICENSE](LICENSE).
