# Prompt Engineering Essentials

Here's the truth about AI: it's only as good as what you ask it. Give it a vague instruction and you'll get a vague answer. Give it a clear, well-structured prompt and you'll get something genuinely useful.

The good news? You don't need a computer science degree to write great prompts. You just need a simple framework and a bit of practice. This lesson will give you both.

## The Role-Task-Format (RTF) Framework

The single most effective technique for getting great AI output is **RTF** — giving the AI three things:

- **Role** — Who should the AI pretend to be?
- **Task** — What exactly do you want it to do?
- **Format** — How should the output look?

Here's the difference RTF makes:

**Weak prompt:**
```text
Write me a social media post about my business.
```

**Strong prompt using RTF:**
```text
Act as a marketing copywriter for a NZ landscaping business.
Write a Facebook post promoting our spring garden tidy-up service.
Keep it under 150 words, include a call to action, and use a
friendly, professional tone suitable for Kiwi homeowners.
```

See the difference? The second prompt gives the AI context, a clear job, and specific constraints. The result will be dramatically better.

> **Tip:** In studies, using structured prompting frameworks like RTF has reduced resolution times by 37% compared to unstructured requests. Structure pays off.

## The LEGO Approach: Goal + Constraint + Context

Think of prompt building like assembling LEGO blocks. Every great prompt has three building blocks you can mix and match:

- **Goal** — What do you want to achieve? ("Write a customer email", "Analyse this data", "Create a weekly plan")
- **Constraint** — What are the boundaries? ("Under 200 words", "In bullet points", "For a NZ audience", "In plain English")
- **Context** — What background does the AI need? ("I run a cafe in Hamilton", "The customer complained about delivery times", "These are last quarter's sales figures")

You don't always need all three, but the more you provide, the better your results.

## Few-Shot Prompting: Show, Don't Just Tell

One of the most powerful techniques is **few-shot prompting** — giving the AI an example of what you want before asking it to produce something new.

```text
I need to write product descriptions for my online store.
Here's an example of the style I want:

"The Kaimai Blend — Our signature dark roast sourced from
ethical farms in Central America. Bold, smooth, and perfect
for those who take their morning coffee seriously. 250g bag."

Now write similar descriptions for these three products:
1. A light roast called "Harbour Breeze"
2. A decaf blend called "After Hours"
3. A cold brew concentrate called "Chillers"
```

By showing the AI your style, tone, and format in an example, it mirrors that in its output. This is especially useful for maintaining your brand voice.

## Ready-to-Use Prompt Templates

Here are practical templates you can copy and adapt right now:

### Customer Email Response
```text
I'm going to paste a customer complaint email below. Summarise the
key issues in bullet points, then draft a professional response
that acknowledges their concern, explains what we'll do about it,
and maintains a warm, helpful tone. Use NZ English spelling.

[Paste email here]
```

### Meeting Summary
```text
Here are my rough notes from a team meeting. Turn them into a
structured summary with:
- Key decisions made
- Action items (with who's responsible)
- Items for follow-up
Keep it concise and professional.

[Paste notes here]
```

### Social Media Content Batch
```text
Act as a social media manager for a NZ [your industry] business
called [your business name]. Create 5 social media posts for
the coming week. Mix promotional, educational, and engagement
posts. Each post should be under 150 words, include a suggested
image description, and use a [friendly/professional/casual] tone.
Our target audience is [describe your customers].
```

### Job Description
```text
Write a job description for a [job title] at a small NZ
[industry] business based in [city]. Include:
- A brief company overview (we are: [2 sentences about your business])
- Key responsibilities (around 6-8 points)
- Required skills and experience
- What we offer
Keep the tone [professional but approachable]. Salary range is
[range]. This is a [full-time/part-time/contract] position.
```

### Spreadsheet Analysis
```text
I'm going to paste data from a spreadsheet. Please:
1. Identify the three most important trends
2. Flag any anomalies or concerns
3. Suggest two actions I should consider
Present your findings in plain language — I'm a business owner,
not a data analyst.

[Paste data here]
```

### Business Strategy Brainstorm
```text
I run a [type of business] in [city/region], NZ. My main
customers are [describe]. I'm looking to [grow revenue / reduce
costs / expand into a new market]. Give me 10 practical ideas
I could implement in the next 3 months with minimal budget.
Prioritise ideas that a small team of [number] could realistically
execute.
```

## Common Mistakes to Avoid

**Being too vague.** "Help me with marketing" gives you generic advice. "Write three Instagram captions for my Auckland dog grooming business targeting busy pet owners" gives you something you can actually use.

**Not providing context.** AI doesn't know your business, your customers, or your industry unless you tell it. The more relevant context you provide, the better the output.

**Accepting the first output.** AI is a conversation, not a vending machine. If the first response isn't quite right, tell it what to change: "Make it more casual", "Shorten it by half", "Add a specific example about [topic]."

**Forgetting to specify your audience.** A post written for enterprise clients sounds very different from one written for local families. Always tell the AI who you're writing for.

**Using American English.** Most AI tools default to US spelling and cultural references. Add "Use NZ English" or "Write this for a New Zealand audience" to your prompts.

> **Warning:** Never paste sensitive personal information, financial details, or confidential business data into a free AI tool without understanding that provider's data policy. Paid plans typically offer better privacy protections.

## The Iteration Mindset

The best prompt engineers aren't people who write perfect prompts on the first try. They're people who iterate. Think of it as a conversation:

1. Start with a reasonable prompt
2. Review the output
3. Tell the AI what to change ("More concise", "Different tone", "Add NZ examples")
4. Repeat until you're happy

Each round of feedback makes the output better. Most people give up after the first response — that's where you can get ahead.

## Key Takeaways

- Use the **RTF framework** (Role, Task, Format) to structure every prompt — it dramatically improves output quality
- Build prompts like LEGO: combine Goal, Constraint, and Context blocks
- **Few-shot prompting** (giving examples) is the fastest way to get AI to match your style and tone
- Always specify "NZ English" and your target audience
- Never accept the first output — iterate and refine through conversation
- Keep the prompt templates from this lesson handy — adapt them to your business and reuse them daily

## Further Reading

[Prompt Engineering Guide — OpenAI](https://platform.openai.com/docs/guides/prompt-engineering)

[Prompt Engineering Overview — Anthropic](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)

[Introduction to Prompt Design — Google AI](https://ai.google.dev/gemini-api/docs/prompting-intro)

[Privacy Commissioner — AI Guidance](https://www.privacy.org.nz/)

[The Co Lab — AI Training for NZ Businesses](https://thecolab.ai)
