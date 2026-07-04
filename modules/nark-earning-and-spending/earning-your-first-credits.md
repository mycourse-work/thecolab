# Earning Your First Credits

Everyone in Watercooler starts with a balance, and from that point on your Nark Credit total moves almost entirely on its own — as a side effect of just being a normal, active member of the channel. This lesson covers the "passive" side of the economy: the ways credits accrue without you ever running a command.

## Your starting balance

When a new member is onboarded into Watercooler, Clawd performs a one-time **initial distribution** — a small starting grant so nobody begins at exactly zero. This isn't something you request; it happens automatically as part of onboarding, and it's logged in the ledger the same as every other transaction, tagged as an `initial_distribution` entry.

> **Tip:** Curious what any of this looks like in practice? `/narkledger` shows the running transaction history, and `/narks` (optionally with `@user`) shows current standings. Nothing in the Kingdom is hidden — every credit and debit is on the record.

## The two passive income streams

Once you're active in Watercooler, two things quietly add to your balance:

**1. Message karma.** Every message you send earns a flat **+1 credit**. It's not much per message, but it adds up — this is by a wide margin the single largest source of credits flowing through the entire ledger, simply because it rewards showing up and taking part in the conversation.

**2. Reactions received.** Every time someone reacts to one of your messages — a 👍, ❤️, 😂, whatever — you earn **+3 credits**. Reactions are worth three times a plain message precisely because they're a much stronger signal: someone else had to actively notice your message and respond to it. Land a genuinely funny or useful message and the reactions alone can meaningfully move your balance.

<div style="max-width: 600px; margin: 1.5em auto; font-family: sans-serif;">
  <div style="display: flex; flex-direction: column; gap: 0.6em;">
    <div style="display: flex; align-items: center; gap: 0.75em;">
      <div style="background: linear-gradient(90deg, #1d4ed8, #3b82f6); color: #fff; border-radius: 8px; padding: 0.6em 1em; min-width: 200px; text-align: center;">
        <strong>Send a message — +1</strong>
      </div>
      <span style="font-size: 0.8em; color: #64748b;">Message karma — the steady baseline income</span>
    </div>
    <div style="display: flex; align-items: center; gap: 0.75em;">
      <div style="background: linear-gradient(90deg, #166534, #22c55e); color: #fff; border-radius: 8px; padding: 0.6em 1em; min-width: 200px; text-align: center;">
        <strong>Get a reaction — +3</strong>
      </div>
      <span style="font-size: 0.8em; color: #64748b;">Reaction received — worth 3x a plain message</span>
    </div>
    <div style="display: flex; align-items: center; gap: 0.75em;">
      <div style="background: linear-gradient(90deg, #92400e, #f59e0b); color: #fff; border-radius: 8px; padding: 0.6em 1em; min-width: 200px; text-align: center;">
        <strong>Good nark, with receipts — +1 to +25</strong>
      </div>
      <span style="font-size: 0.8em; color: #64748b;">Covered in the next lesson</span>
    </div>
  </div>
</div>

## Adjustments: the manual layer

Not every ledger entry comes from the automated rules. Community owners can make manual **adjustments** — for example, topping up a member's balance after a technical hiccup, or correcting an error. These show up in the ledger as `adjustment` entries with a plain-English reason attached, exactly like every other transaction. Nothing about the ledger is opaque or off-the-books; even manual interventions leave a permanent, visible trail.

There's also **`/bailout`**, an owner-only command that resets a specific member's balance back to zero. Think of it as the Kingdom's version of a financial bailout: available, but deliberately not something anyone can trigger for themselves.

## Why the passive system is designed this way

It would have been easy to make narkcoin purely a "narking" game — credits only for reporting on people. Instead, the two biggest and most reliable income sources (message karma and reactions) reward the most ordinary form of participation there is: talking, and being interesting enough that people react. That's a deliberate design choice. It means:

- Lurkers earn very little, simply by construction — no messages, no karma.
- The chattiest members build up a baseline balance quickly, but...
- ...consistently *good* messages (the ones that earn reactions) out-earn simply spamming the channel, since reactions are weighted three times higher.

> **Warning:** Don't mistake "send lots of messages" for "the best strategy." Message karma is a slow trickle. The real balance swings in the Kingdom come from reactions, well-evidenced narks (next lesson), and the gambling suite (Module 3) — for better or worse.

## What happens to all these credits?

Once you have a balance, you have three broad options: sit on it, gamble it (Module 3 covers the full games catalogue), or lose it — either through a bad nark fine, a losing bet, or the recurring event that claws back the biggest balances in the channel. The next lesson covers the most distinctive earning-and-losing mechanic of them all: the nark itself.

## Key Takeaways

- New members receive a one-time initial distribution when onboarded into Watercooler.
- Sending a message earns a flat +1 credit (message karma) — the steadiest, most common source of credits in the ledger.
- Receiving a reaction on your message earns +3 credits — three times the value of a plain message, because it requires someone else to actively respond.
- Owners can make manual balance adjustments (logged transparently) and can `/bailout` a member's balance back to zero.
- The passive earning design deliberately rewards genuine participation over raw message volume, since reactions are worth far more than messages alone.
