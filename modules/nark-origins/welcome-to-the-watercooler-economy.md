# Welcome to the Watercooler Economy

Every community needs a place to blow off steam. For TheColab.ai — a New Zealand community of AI builders, founders, and tinkerers who organise most of their day-to-day chat on WhatsApp — that place is **Watercooler**.

Watercooler sits apart from the serious channels. Over in Business, Technical, Legal, Finance, Security, and the rest, people are shipping products, debating architecture, and asking for advice. Watercooler is where the same people go to bicker, joke, gossip, and generally act like humans instead of professionals. It's also home to something no other channel has: its own currency, its own economy, its own tiny fictional kingdom of in-jokes. That currency is called **Nark Credits** — but almost nobody calls it that. Everyone just says **narkcoin**.

> **Important:** Narkcoin is not a cryptocurrency, it has no real-world value, and it cannot be cashed out. It exists purely as a bit — a running gag that got so elaborate it now has a ledger, a leaderboard, gambling games, a court system, and a recurring apocalypse. This entire course treats it exactly as seriously as it deserves: seriously enough to explain the rules properly, not seriously enough to forget it's a joke.

## How a joke became an economy

The Colab Clawd — the community's AI bot, built on the Claude Agent SDK and running quietly inside the WhatsApp group — was originally there to do sensible things: moderate messages against community guidelines, answer questions, transcribe voice notes, generate the odd PDF or image on request, and make sure new members got a friendly welcome. All useful, all fairly ordinary bot duties.

Then someone asked, mostly as a bit, whether Clawd could "create the narkcoins." Clawd — being an AI agent with a personality, a sense of comic timing, and apparently strong opinions about community guideline #3 ("no crypto schemes") — refused to create anything resembling a real coin, then immediately turned around and built the joke version anyway: a fictional currency with zero backing, infinite supply, and a tokenomics model based entirely on how often people report on each other.

That bit didn't stay a bit for long. Within days it had:

- A running balance for every member, stored in an actual database
- Rules for earning and losing credits
- A gambling wing with half a dozen different games
- A appeals court, presided over by a persona named Karen
- A recurring "wealth redistribution" event that nobody asked for and everyone now expects

In other words: Watercooler now runs its own tiny command economy, administered entirely by an AI that also happens to moderate the group, and it's one of the most active parts of the whole community.

<div style="max-width: 700px; margin: 1.5em auto; font-family: sans-serif;">
  <h4 style="text-align: center; margin-bottom: 0.75em; color: #1e293b;">From Bot Duty to Kingdom</h4>
  <div style="display: flex; align-items: center; gap: 0.35em; flex-wrap: wrap; justify-content: center;">
    <div style="background: #1d4ed8; color: #fff; border-radius: 10px; padding: 0.6em 0.8em; text-align: center; min-width: 110px; font-size: 0.8em;">
      <strong>1.</strong><br>Clawd moderates &amp; assists
    </div>
    <span style="color: #94a3b8; font-size: 1.2em;">→</span>
    <div style="background: #2563eb; color: #fff; border-radius: 10px; padding: 0.6em 0.8em; text-align: center; min-width: 110px; font-size: 0.8em;">
      <strong>2.</strong><br>"Make us a coin" (as a joke)
    </div>
    <span style="color: #94a3b8; font-size: 1.2em;">→</span>
    <div style="background: #3b82f6; color: #fff; border-radius: 10px; padding: 0.6em 0.8em; text-align: center; min-width: 110px; font-size: 0.8em;">
      <strong>3.</strong><br>Fictional $NARK, zero value
    </div>
    <span style="color: #94a3b8; font-size: 1.2em;">→</span>
    <div style="background: #6d28d9; color: #fff; border-radius: 10px; padding: 0.6em 0.8em; text-align: center; min-width: 110px; font-size: 0.8em;">
      <strong>4.</strong><br>Ledger, games, court, guillotine
    </div>
  </div>
</div>

## Why it only lives in Watercooler

This is a deliberate design choice, not an accident. The comedy narking, the gambling commands, the guillotine — all of it is scoped to Watercooler only. The serious channels stay serious. Watercooler is a sandbox: a clearly bounded space where the bot is allowed to run an absurd little economy without it leaking into channels where people are trying to close deals or debug production incidents.

That boundary matters for a course like this one too. Everything you're about to learn — narking, fining, gambling, appeals, the guillotine — is Watercooler-only behaviour. It's not how the wider community operates, and it's not a model for how any *real* system should treat money, moderation, or justice. It's satire, and good satire needs rules that are followed precisely, which is exactly what makes it fun to study.

> **Tip:** If you're new to TheColab.ai, the fastest way to understand Watercooler's culture is to read a few days of `/narkledger` output before you say anything. You'll pick up the tone (dry, self-aware, very Kiwi) much faster than by reading a rulebook.

## What narkcoin actually rewards

Strip away the jokes and narkcoin is, underneath, a lightweight participation-and-accountability game layered on top of ordinary chat activity. It rewards:

- **Being active** — every message and every reaction you receive nudges your balance
- **Catching real things** — a well-evidenced call-out ("nark") earns real credits
- **Not crying wolf** — a weak or evidence-free call-out gets fined
- **Playing along** — the gambling commands exist purely for entertainment, with house-edge economics baked in on purpose
- **Not hoarding** — the single biggest mechanic in the whole system exists specifically to stop anyone's balance from running away unchecked

The rest of this module introduces the cast running the show. The next two modules cover exactly how credits are earned and lost, and the full catalogue of games — including the event every Watercooler regular watches for at midnight.

## Key Takeaways

- Narkcoin (formally "Nark Credits") is a fictional, zero-value in-joke currency run entirely inside TheColab.ai's Watercooler WhatsApp channel.
- It emerged from a joking request for the community bot, Clawd, to "make a coin" — Clawd refused a real crypto scheme and built a satirical one instead.
- The system now includes a persistent ledger, earning and fining rules, a gambling suite, an appeals process, and a recurring wealth-redistribution event.
- All of it is scoped to Watercooler only — it never affects the serious, professional channels of the community.
- At its core, narkcoin rewards genuine participation and well-evidenced accountability, and actively punishes hoarding and weak call-outs.
