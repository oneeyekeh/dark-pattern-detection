# dark-pattern-detection

My master's thesis, in code.

The question: can a large language model spot dark patterns, the sneaky UI tricks that nudge you into buying, subscribing, or staying, on e-commerce sites? Not just in the copy, but in how the page looks.

Short answer: yes, surprisingly well. I ran GPT-4o-mini over text and screenshots from 146 e-commerce websites, scored what it found, and built a Chrome extension so anyone can flag dark patterns while they browse.

## What's in here

- `Analysis/` — the experiments. URL lists, screenshot processing, and the scoring runs: business features, "overall darkness", and the boxplots that came out of them.
- `docs/thesis.md` — the full write-up. Problem context, research questions, and what it means for designers.
- `Logos/` — assets.
- `Extension/` and `Vercel/` — pointers to the Chrome extension and its small backend, which live in their own repos. You don't need them to read the analysis.

## Why I care

I started in design before product. Dark patterns are what happens when growth targets meet a room with no designer in it. This was my attempt to put a detector in users' hands instead of another paper on a shelf.

## Who made this

Onee Yekeh. Technical PM at HeyGen. More at [oneeyekeh/personal-site](https://github.com/oneeyekeh/personal-site).
