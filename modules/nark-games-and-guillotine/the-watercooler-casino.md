# The Watercooler Casino

Earning credits through messages, reactions, and narks is only half the fun. The other half is losing them again, as fast and as entertainingly as possible, through a full suite of gambling commands. None of this is subtle about its house edge — the games exist purely for entertainment, and the ledger keeps every win and loss on permanent record.

## The daily staples

**`/gamble`** is the simplest game in the Kingdom: once per NZ day, it mutates only your own balance, with a randomised outcome. It's the equivalent of a quick flutter — low ceremony, immediate result.

**`/scratch`** is a daily scratch card with a wider prize table: **0, +10, +25, +50, +100, +250, or +500** — plus one specific cursed outcome, a flat **-250** "trapdoor" prize that exists purely to catch the overconfident. Like `/gamble`, it's limited to once per day, which keeps it a small daily ritual rather than a way to grind credits.

> **Tip:** `/gamblestats` shows your personal gambling record across every game — a running scoreboard of exactly how the house has treated you over time. It's worth checking before you decide you're "due" for a win.

## The set-piece games

Beyond the daily staples, Watercooler runs a rotating cast of bigger, more theatrical games:

| Game | How it works |
|---|---|
| **`/holy-lottery`** | A nightly draw at 9pm NZ time. Every entrant gets exactly one ticket, and fixed prizes pay out to places 1 through 5 — the more entrants, the longer the odds, but the prize table never changes. |
| **`/horse-race`** | Opens a 60-second betting window on 8 deterministic horses, then posts live, phone-friendly race commentary every 5 seconds — progress rails, attached bets and all — before paying displayed odds. Maximum stake is 1000 credits per person. |
| **`/trivia`** | Starts a pre-seeded trivia bounty; the first correct answer wins. There's also a 10% "boobytrap" chance baked in — instead of winning, you're fined 500 credits, so a fast answer isn't automatically a safe one. |
| **`/higher-lower`** | A Woolworths grocery-price guessing game: guess correctly whether a real item's price is higher or lower than shown, and win 1000; guess wrong and lose 2000. The asymmetry is the whole game. |
| **`/gambling-trivia <credits>`** | Stake up to 250 credits on a banked trivia question — you only win if you answer first, and you lose your stake if anyone beats you to it. Capped at three attempts per person per NZ day. |

<div style="max-width: 700px; margin: 1.5em auto; font-family: sans-serif;">
  <h4 style="text-align: center; margin-bottom: 0.75em; color: #1e293b;">Risk Profile of the Watercooler Casino</h4>
  <div style="display: grid; grid-template-columns: 1fr 1fr; border: 2px solid #e2e8f0; border-radius: 12px; overflow: hidden;">
    <div style="background: #dbeafe; padding: 1em; border-right: 1px solid #e2e8f0; border-bottom: 1px solid #e2e8f0;">
      <strong style="color: #1d4ed8;">Low stakes, low ceremony</strong>
      <ul style="margin: 0.5em 0 0; padding-left: 1.2em; font-size: 0.9em;">
        <li>/gamble</li>
        <li>/scratch</li>
      </ul>
    </div>
    <div style="background: #fef3c7; padding: 1em; border-bottom: 1px solid #e2e8f0;">
      <strong style="color: #92400e;">Bigger prizes, more theatre</strong>
      <ul style="margin: 0.5em 0 0; padding-left: 1.2em; font-size: 0.9em;">
        <li>/holy-lottery</li>
        <li>/horse-race</li>
      </ul>
    </div>
    <div style="background: #f1f5f9; padding: 1em; border-right: 1px solid #e2e8f0;">
      <strong style="color: #64748b;">Skill-adjacent (speed &amp; knowledge)</strong>
      <ul style="margin: 0.5em 0 0; padding-left: 1.2em; font-size: 0.9em;">
        <li>/trivia</li>
        <li>/gambling-trivia</li>
      </ul>
    </div>
    <div style="background: #fef2f2; padding: 1em;">
      <strong style="color: #991b1b;">Highest single-round downside</strong>
      <ul style="margin: 0.5em 0 0; padding-left: 1.2em; font-size: 0.9em;">
        <li>/higher-lower (−2000 on a wrong guess)</li>
      </ul>
    </div>
  </div>
</div>

## Narkstreetbets: the meme stock market

The newest and most elaborate addition to the casino is **narkstreetbets** — a full paper-trading stock market simulator, built directly on top of the ledger. It supports opening trades, taking a small rake on each one, and — for the truly committed degenerates — margin and short positions. It's the closest thing the Kingdom has to "advanced" gameplay: instead of a single randomised roll, you're holding a position that can move for or against you over time, exactly like a real (very small, entirely fictional) trading desk.

> **Warning:** Narkstreetbets carries the same zero-real-value disclaimer as everything else in the Kingdom, but it's also the easiest game to lose a large balance in quickly, precisely because positions can move against you before you get a chance to close them. Treat it as the "advanced difficulty" option, not the place to start.

## Why the house always wins (on purpose)

Clawd itself has been admirably honest about the economics here, once laying out the "bull case" for narkcoin investment as a joke pitch: no earnings, no utility, no liquidity — "fully backed by the chat being mildly amused." That's not a bug in the design, it's the entire design. The games exist to give the ledger movement and drama, not to let anyone reliably compound a fortune. Even the deterministic horse races and fixed lottery prizes are structured so that, over enough rounds, the house edge asserts itself — which is exactly the point of a satire on gambling and crypto speculation.

The one thing the casino *can't* do is let anyone escape the next lesson's mechanic — no matter how well you're doing.

## Key Takeaways

- `/gamble` and `/scratch` are once-a-day, low-ceremony games with fixed prize tables (including a cursed -250 outcome on `/scratch`).
- `/holy-lottery`, `/horse-race`, `/trivia`, `/higher-lower`, and `/gambling-trivia` are bigger set-piece games with fixed prizes, betting windows, live commentary, or risk/reward asymmetries.
- Narkstreetbets is a full paper-trading stock market simulator with margin and shorting — the most "advanced" and riskiest game in the Kingdom.
- Every game is designed with a deliberate house edge — the point is entertainment and ledger drama, not sustainable profit.
- `/gamblestats` gives you a personal record across every game, useful for keeping perspective on your actual track record.
