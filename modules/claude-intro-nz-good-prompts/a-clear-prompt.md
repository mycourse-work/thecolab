# Build a prompt with useful context

Allow 4 minutes.

A prompt is your instruction to Claude. Start with a clear task. Then give the information it needs to do that task.

## Use this six-part pattern

| Part | Example |
| --- | --- |
| Task | Draft a customer email. |
| Context | We are an invented Christchurch building firm. |
| Role | Act as an office administrator drafting for manager review. |
| Audience | A homeowner waiting for a quote. |
| Inputs | The site visit is complete. The quote is still being reviewed. |
| Output and limits | Under 100 words. No promised delivery date. NZ English. |

A role helps describe the kind of output you want. It does not give Claude professional qualifications. Supply the actual facts separately.

## Before and after

**Before:** “Write something about a quote.”

**After:**

```text
Act as an office administrator drafting for manager review.
For an invented Christchurch builder, draft a homeowner email.
Facts: the site visit is complete; the quote is under review.
Thank them and explain that we will contact them when it is ready.
Give a subject line and a body under 100 words in NZ English.
Do not invent a price, due date or guarantee.
```

## Try it: make one improvement

Run the “before” prompt, then the “after” prompt in a fresh chat. Spend two minutes comparing them. Which result made fewer assumptions? Keep the instruction that caused the improvement.

You can also ask Claude to list missing information before it drafts. Answer with invented facts for practice.
