# Development Habits

## Problem
Too many devs (and even leaders) write code in a vacuum. They chase clever solutions, forget the team, or ship without considering adoption. That’s how you end up with broken pipelines, angry users, and tech debt nobody wants to touch.

## Habits I Push
- **Code Reviews Matter** – Don’t skip them. Most of my commits are reviews and clarifications, not raw features. Catching the “why” and “how” early prevents cleanup later.
- **Clarity Over Clever** – Write code your team can pick up tomorrow without you. If you’re the only one who understands it, you failed.
- **Incremental > Massive** – Small PRs win every time. Easier to test, easier to roll back.
- **Document As You Go** – Doesn’t have to be novels. A one-liner in the repo explaining context beats silence.
- **Think Like Ops** – Your code runs in production. Don’t leave deployment, monitoring, and rollback as afterthoughts.

## Example
At CHR, zPortal wasn’t about me hammering out new features every day. It was about reviewing others’ code, fixing where things drifted, and making sure changes actually aligned with the business. That clarity kept the system stable even with a small team.

## Lessons
- Code isn’t art. It’s a tool.
- Habits compound. Good reviews, small PRs, and clear notes save months of pain.
- If your code makes you look smart but slows down the team, you’re doing it wrong.
