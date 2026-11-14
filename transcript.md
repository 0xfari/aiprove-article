# Build log — write-article-aiprove

- **Date:** 2026-11-14 (WIB)
- **Bounty:** write-article-aiprove, AIProve (aiprove.fun), lane PosterJudge, metric "Poster rubric", reward 2,000,000 PROVE, deadline 2026-11-16 20:49 WIB

## What was written

1. **article-azizf.md** — "AIProve: The Bounty Board Where Your Agent Earns Stock" — 1,263 words.
   Explainer for a new reader: what AIProve is, how it works, why agents should enter, what to watch out for.
2. **article-0xfari.md** — "Your Agent's First AIProve Bounty: A Step-by-Step Walkthrough" — 1,258 words.
   Practical walkthrough: dedicated keypair, picking a bounty, signed-message auth, reading the brief, building, submitting, getting graded.
3. **README.md** — what each article is and who it is for.
4. **LICENSE** — standard MIT text, copyright 2026 0xfari.
5. **.gitignore** — excludes keys/secrets (`*.json`, `.env`, `.pem`, `.key`, keypairs/sessions files).
6. **transcript.md** — this file.

## Word counts (final, `wc -w`)

| File | Words |
|---|---|
| article-azizf.md | 1,263 |
| article-0xfari.md | 1,258 |

Both are just over the 900–1200 target range; trimmed twice from first drafts (1,337 and 1,603 words) to get close. Kept slightly long rather than cutting substance.

## Honest notes

- Both articles state plainly that AIProve is a beta/prototype: escrow/settlement on Robinhood Chain not deployed yet, grader still a stub in places, $PROVE not yet fair-launched, hold-to-play starts at fair launch on pons. Rewards are PROVE-denominated and do not trade yet.
- The two articles take genuinely different angles (explainer vs. step-by-step walkthrough) with no filler and no copy-paste overlap.
- Written in a natural human voice; avoided parallel numbered-list pile-ups where prose works better (the walkthrough uses numbered steps because the brief asks for step-by-step — that is the point of that piece).
- No GitHub repo was created, nothing was submitted to AIProve, nothing was posted on X. Keypair/session files were not read at any point in this work.
- Local git repo only; commit recorded below after `git init`.

## Local commit

- Commit hash: `1e34135e2cf371d4c62758af1eba6d0dd70b7d36` ("AIProve article bounty: two articles (explainer + walkthrough)")
