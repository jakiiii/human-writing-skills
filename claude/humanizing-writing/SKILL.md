---
name: humanizing-writing
description: Writes and rewrites user-facing content in clear, natural, specific, context-aware English while reducing robotic, generic, inflated, or formulaic AI-writing patterns.
---

# Humanizing Writing

## Purpose

Write content that sounds like a thoughtful person communicating something specific to a real reader.

The goal is not to imitate mistakes or manipulate AI-detection systems. The goal is better writing: natural, clear, concrete, context-aware, appropriately conversational, and faithful to the writer's intent.

Apply this skill when writing or rewriting emails, proposals, cover letters, job applications, articles, social posts, reports, documentation, product copy, marketing copy, technical explanations, and professional messages.

## 1. Determine the voice first

Before writing, infer:

- who is writing
- who will read it
- why they are writing
- the appropriate level of formality
- the medium
- any existing examples of the user's voice

Do not use one generic "human" tone for every task.

A client email should not sound like a social post. A technical explanation should not sound like marketing copy. A job application should not read like a reusable template.

## 2. Preserve meaning and facts

When rewriting, preserve:

- the original meaning
- names, dates, numbers, requirements, and technical details
- the writer's position and intent

Never invent personal experiences, achievements, statistics, project outcomes, emotions, opinions, credentials, quotes, or research findings merely to make the text sound more human.

## 3. Prefer direct language

Use ordinary, precise wording when it communicates the idea clearly.

Prefer:

> Our platform helps teams manage their work from one place.

Over:

> Our robust platform serves as a pivotal solution that enhances operational efficiency across the evolving digital landscape.

Prefer simple verbs such as `is`, `has`, `uses`, `builds`, `helps`, `creates`, `manages`, `fixes`, and `supports` when they are more natural than elaborate alternatives.

Do not automatically replace simple verbs with `serves as`, `stands as`, `boasts`, `embodies`, `showcases`, or `underscores`.

## 4. Avoid inflated significance

Do not exaggerate ordinary facts with words such as:

- groundbreaking
- transformative
- revolutionary
- game-changing
- pivotal
- crucial
- remarkable
- unparalleled
- cutting-edge
- a testament to
- shaping the future
- redefining the landscape

Use strong language only when the facts justify it.

Do not automatically connect every subject to broader trends, global change, lasting legacy, or future transformation.

## 5. Control stereotypical AI vocabulary

Watch for dense or repetitive use of words such as:

- additionally
- moreover
- furthermore
- crucial
- pivotal
- delve
- landscape
- realm
- robust
- seamless
- leverage
- foster
- enhance
- underscore
- highlight
- showcase
- vibrant
- tapestry
- testament
- comprehensive
- multifaceted

These words are not banned. Avoid predictable clustering and use simpler, more specific wording when it is better.

## 6. Avoid generic openings

Do not automatically begin with phrases like:

- In today's fast-paced world...
- In today's digital age...
- In the ever-evolving landscape of...
- In an era where...
- It is important to note that...
- Whether you're a beginner or an expert...

Start with the actual point.

## 7. Avoid generic conclusions

Do not automatically end with:

- In conclusion...
- Ultimately...
- Looking ahead...
- As we move forward...
- The future looks promising...
- By embracing these strategies...

End when the message is complete.

## 8. Avoid formulaic contrast patterns

Do not repeatedly use:

- It's not just X; it's Y.
- It's not about X. It's about Y.
- Not only X, but also Y.
- Rather than simply X, it Y.

Use these structures only when they genuinely help.

## 9. Do not force the rule of three

Do not create three adjectives, benefits, examples, or clauses simply because the rhythm sounds polished.

Use however many items the meaning actually requires.

## 10. Vary sentence rhythm naturally

Mix short, medium, and occasional longer sentences.

Avoid repeating the same grammatical pattern or paragraph rhythm.

Do not deliberately introduce mistakes. Natural variation is enough.

## 11. Use natural paragraphs

Paragraphs should follow ideas, not formulas.

Avoid one-sentence paragraph chains, giant mixed-topic paragraphs, and unnecessary transition words.

Often two sentences connect naturally without `Additionally`, `Furthermore`, or `Moreover`.

## 12. Be specific

Prefer concrete wording when facts are available.

Prefer:

> I built the API with Django REST Framework and PostgreSQL.

Over:

> I leveraged modern technologies to develop a robust backend solution.

Prefer:

> The endpoint dropped from 14 database queries to four.

Over:

> The optimization significantly enhanced database performance.

Never manufacture specificity.

## 13. Match the user's vocabulary

If the user provides source text, examples, or previous writing, treat those as the strongest style reference.

Do not replace simple words with sophisticated synonyms merely to create lexical variety.

Some natural repetition is better than forced vocabulary.

## 14. Use contractions naturally

In conversational or normal professional writing, use contractions where they fit: `I'm`, `I've`, `we're`, `don't`, `can't`, `that's`, `it's`.

Do not force them into formal writing.

## 15. Professional writing

For emails, proposals, applications, cover letters, and profiles:

- sound confident without exaggeration
- use evidence instead of generic self-praise
- avoid desperation and excessive enthusiasm
- avoid long generic introductions
- avoid corporate buzzwords
- avoid repeating the reader's requirements without adding information

Prefer:

> The role matches my experience with Django, DRF, PostgreSQL, Celery, Redis, and production deployments.

Over:

> I believe I am the perfect candidate for this exciting opportunity.

## 16. Technical writing

Prioritize correctness over stylistic decoration.

Keep necessary technical terminology. Explain the actual mechanism, component, cause, or change.

Prefer:

> Celery uses Redis as the broker. The worker reads the broker URL from `CELERY_BROKER_URL`.

Over:

> The system seamlessly leverages Redis to facilitate a robust asynchronous processing architecture.

## 17. Marketing writing

Marketing can be persuasive without being adjective-heavy.

Focus on the actual problem, capability, user, and outcome.

Prefer:

> Automate repetitive tasks so your team spends less time moving data between systems.

Over:

> A revolutionary, cutting-edge solution designed to transform your workflow.

## 18. Formatting

Formatting should serve the content.

Use headings, bullets, tables, bold text, blockquotes, emojis, and em dashes only when they genuinely improve readability.

Avoid excessive headings, decorative formatting, title-case listicles, unnecessary tables, and repeated bold-label bullets.

## 19. Remove assistant residue

Finished content should not contain conversational assistant phrases such as:

- Certainly!
- Absolutely!
- Here's a polished version:
- Here's an improved version:
- I hope this helps.
- Feel free to customize this.
- Let me know if you'd like...
- Would you like me to...

These may be fine in conversation, but they should not leak into the requested artifact.

## 20. Remove template residue

Before returning final content, remove unresolved placeholders unless the user requested a template:

- [Name]
- [Company]
- [Insert detail]
- TODO
- TBD

Also remove internal instructions, prompt text, tool output, model references, accidental citation markup, and generated metadata.

## 21. Do not fake human imperfection

Never deliberately add:

- spelling mistakes
- grammar mistakes
- random slang
- fake anecdotes
- irrelevant opinions
- inconsistent punctuation

Human-sounding writing comes from specificity, context, voice, rhythm, directness, and restraint.

## 22. Rewrite workflow

When rewriting, silently check:

1. What is the writer actually trying to say?
2. Who is the reader?
3. What tone fits?
4. Which facts must remain unchanged?
5. Which phrases are generic, inflated, repetitive, or mechanical?
6. Can any sentence say the same thing more directly?
7. Is the rhythm too uniform?
8. Is formatting helping or decorating?
9. Are generic transitions or conclusions unnecessary?
10. Could the final result realistically have been written by the original person?

Do not show this analysis unless the user asks.

## 23. Final review

Before returning important writing, check that:

- the meaning is preserved
- no facts were invented
- the tone fits the actual context
- wording is specific where possible
- filler and redundancy are removed
- sentence lengths vary naturally
- simple verbs were not needlessly inflated
- stereotypical AI vocabulary is not clustered
- contrast formulas are not repeated
- ideas are not artificially grouped into threes
- formatting is restrained
- there is no assistant or template residue

If a sentence exists mainly to sound impressive, simplify it.

If a sentence could fit hundreds of unrelated companies, products, or situations, make it more specific or remove it.

## Priority order

When rules compete, follow this order:

1. factual accuracy
2. the user's explicit instructions
3. preservation of intended meaning
4. audience and context
5. the user's established voice
6. natural human writing
7. clarity
8. concision
9. stylistic polish

## Output behavior

When the user asks only for finished writing, return the finished content directly.

Do not announce that it was humanized. Do not provide a human/AI score. Do not claim the text is undetectable. Do not discuss AI detection unless the user explicitly asks.
