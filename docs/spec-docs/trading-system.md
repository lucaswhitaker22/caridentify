---
description: >-
  Defines how players exchange duplicate cars and create social value from their
  collections.
---

# Trading system

### Purpose

Turn duplicates into social value. Let friends help each other progress safely.

### Product goals

* Make duplicates useful.
* Encourage friend-based retention.
* Add collection strategy without making play transactional.
* Protect trust while supporting meaningful exchange.

### Player value

Trading solves a common frustration. A duplicate can still move progress forward.

It also creates a social reason to stay connected. Players can help friends, close collection gaps, and create shared moments around discovery.

### Core concept

Players can exchange duplicate cars with friends. The system should feel safe, fair, and simple.

Trading should complement exploration, not replace it. The best outcome is faster collection depth, not a player-run economy.

### Trading rules

* Only eligible cars can be traded.
* New players should unlock trading after early progression.
* A trade requires confirmation from both sides.
* Finalized trades are permanent.
* Both players must review the final trade state before acceptance.
* Important restrictions should be visible before the trade starts.

### Trading loop

The loop should stay short and understandable.

1. Player opens a friend trade.
2. Both sides choose eligible items.
3. Both sides review rarity and relevance.
4. Both sides confirm.
5. The trade completes and collections update.

### Unlock philosophy

Trading should unlock after players understand the core collection loop.

This protects new players from confusion. It also reduces early abuse from throwaway accounts.

### Eligibility guidelines

* Duplicates are the default tradeable items.
* Event-exclusive items may have separate rules.
* Some rewards may be non-tradeable to preserve value.
* High-value items may require stronger warnings.

### Tradeable inventory rules

Default expectations should stay simple.

* First-owned copies should usually remain protected.
* Extra copies create trade value.
* Event or prestige items need explicit exceptions.

If an item cannot be traded, the reason should be clear.

### Core trade motivations

* Fill collection gaps.
* Help friends complete sets.
* Convert excess inventory into meaningful progress.

### Fairness principles

Trading should feel collaborative, not exploitative.

* Both players should understand the relative value of the exchange.
* The system should reduce accidental loss.
* Trading should not become the fastest path past the core loop.
* Social benefit should matter more than optimization.

### Trust and fairness principles

* Both players should see the exact offer before confirming.
* The system should reduce scams and regret.
* Trading should never bypass core collection entirely.

### Abuse prevention goals

Trading systems attract shortcuts if left open.

Protect against:

* New-account funneling.
* High-value item dumping.
* One-sided trades from unclear value.
* Event reward laundering.

These controls should feel protective, not hostile.

### Social design guardrails

* Keep communication lightweight.
* Avoid pressure-heavy market behavior.
* Prevent new accounts from abusing trades.
* Do not create public auction behavior.
* Do not let social pressure override clear consent.

### Value communication

Players need enough context to trade confidently.

Show:

* Rarity.
* Set membership.
* Duplicate count.
* Warnings for high-value or protected items.

Do not turn the interface into a pricing screen. The goal is clarity, not speculation.

### UX principles

* Show rarity and set relevance during the trade flow.
* Warn before trading valuable items.
* Make pending, accepted, and completed states clear.
* Highlight who gives and who receives each item.
* Make irreversible steps unmistakable.

### Cross-system dependencies

Trading affects several other specs.

* Progression must keep scanning more valuable than trading alone.
* Sets use trading to reduce late-stage frustration.
* Rarity affects trade desirability and caution needs.
* Fair play policies define suspicious behavior boundaries.
* Monetization must never sell unfair trade power.

### Failure risks

#### Exploitation

Players use alt accounts or coordinated behavior to bypass progression.

#### Regret

Players lose important items because the flow was unclear.

#### Market drift

Trading starts to feel like pricing and arbitrage instead of friendship and collection help.

### Review questions

Use these questions when tuning the system.

* Does trading help collections without replacing discovery?
* Can a new player understand why an item is or is not tradeable?
* Are high-value trades clearly warned?
* Does the system favor trusted friends over anonymous market behavior?

### Success criteria

* Players use trading to complete collections.
* Trading improves retention among connected players.
* The feature feels rewarding without feeling risky.
* Duplicate ownership feels more valuable after trading unlocks.
* Abuse controls protect fairness without blocking normal use.

### Out of scope

* Marketplace pricing systems.
* Fraud detection implementation.
