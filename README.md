# launch-signal

A Claude Code skill that generates a complete X social playbook for newly submitted hackathon projects. Grounded in real breakout patterns from past Colosseum winners, not generic advice.

**[Live preview](https://lilacchio.github.io/launch-signal/)**

![launch-signal hero](https://lilacchio.github.io/launch-signal/screenshots/hero.png)

## Install

```bash
npx skills add sagapad/launch-signal
```

## What it does

Most hackathon projects ship great products and get buried. The teams that break out don't just build. They attach to conversations already happening and make their project the answer.

`launch-signal` analyzes your project, searches for live Solana ecosystem momentum, pattern-matches to past breakout projects (Pyth, Tensor, Drift, MagicBlock, Orca), and produces a personalized playbook you can execute from day one.

**Output includes:**
- Core story angle and origin hook: the one line you use for the next 30 days
- 4-week content plan with specific post types per day
- X Spaces, AMAs, and Solana community events to attend
- Engagement strategy: who to follow, how to reply, which keywords to monitor
- 5 fully written, ready-to-post tweets (no editing required)

![terminal output](https://lilacchio.github.io/launch-signal/screenshots/terminal-section.png)

## How to use

After installing, trigger the skill in Claude Code:

```
/launch-signal
```

Claude will ask for:
- Project name
- What the project does (1-2 sentences)
- Who it's for
- Tech stack
- Team background (optional)

Then it searches for live Solana ecosystem momentum, selects the closest breakout pattern, and generates your full playbook.

## Example output

![output examples](https://lilacchio.github.io/launch-signal/screenshots/output-section.png)

![generated posts](https://lilacchio.github.io/launch-signal/screenshots/tweets-section.png)

**Input:**
```
Project: zkFi
What it does: ZK-proof privacy layer for Solana DeFi. Shields swap amounts
from MEV bots, compatible with any existing DEX.
Who it's for: DeFi traders losing money to front-running
Tech stack: Anchor, Groth16 circuits, Light Protocol
Team: ex-Aztec Protocol, ex-Solana Labs
```

**Output (excerpt):**

> **Origin Hook:** "Every DeFi trader on Solana is getting front-run. zkFi is the first shield that actually works without switching DEXs."
>
> **Post 1:**
> A Solana MEV bot made more money last week than most DeFi traders.
> It didn't build anything. It just watched your swaps and cut in line.
> We built the fix. And it works with the DEXs you're already using. 🧵

## What makes it different

Generic social tools give generic advice. `launch-signal` has a research library of 5 real Colosseum breakout narratives baked in, a live ecosystem search step that finds what Solana Twitter is actually talking about this week, and a Momentum Attachment Framework that connects your project to a conversation already at temperature, not one you have to start from scratch.

## Built for

Colosseum Hackathon | SagaPad Skill Marketplace | Superteam Frontier Track
