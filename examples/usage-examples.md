# Usage Examples

These examples show how to invoke the writing standards in practical tasks.

## Claude

If the skill is installed in your Claude project, you can ask naturally:

```text
Rewrite this email so it sounds professional and natural without becoming overly formal:

[paste email]
```

```text
Write an Upwork proposal for this backend Django job. Keep it direct, specific to the job, and avoid generic enthusiasm.

[paste job post]
```

```text
Improve this technical explanation. Preserve all technical details and make the wording clearer and less robotic.

[paste text]
```

The skill should apply automatically when the task is clearly a writing or rewriting task.

## ChatGPT

After adding `PROJECT_INSTRUCTIONS.md` to Project Instructions and uploading `HUMAN_WRITING_STANDARD.md` as a project source, use the project normally.

Examples:

```text
Write a short reply to this client email. Keep it professional, clear, and natural.

[paste email]
```

```text
Humanize this profile overview without removing the technical details or making it sound casual.

[paste profile]
```

```text
Rewrite this LinkedIn post so it sounds like an experienced developer sharing a real observation rather than generic AI-written advice.

[paste post]
```

## Optional explicit trigger

If you want to make the intent explicit for an important request, use:

```text
Apply the Human Writing Standard.

Write a concise cover letter for this role:
[paste role]
```

or:

```text
Apply the Human Writing Standard and preserve every factual detail.

Rewrite:
[paste content]
```

## Professional email example

Prompt:

```text
Write a reply to the recruiter. I received the assignment, but the required tech stack is not specified. I applied for a Senior Backend Developer role, while the assignment looks UI/UX-focused. Ask for clarification in a concise and professional way.
```

Desired characteristics:

- direct opening
- no exaggerated gratitude
- clear question
- no generic "excited for the opportunity" language unless the user requests it
- natural professional closing

## Freelance proposal example

Prompt:

```text
Write an Upwork proposal for a Django REST Framework project that needs PostgreSQL, Celery, Redis, and Docker. Mention only experience supported by the information I provide. Keep it concise and specific to the client's requirements.
```

Desired characteristics:

- lead with relevance
- mention concrete matching experience
- avoid copying the job description back to the client
- avoid "I am the perfect candidate"
- no unnecessary conclusion

## Technical documentation example

Prompt:

```text
Rewrite this deployment note for developers. Keep commands and environment variable names unchanged. Explain the root cause directly and avoid marketing language.

[paste note]
```

Desired characteristics:

- technical accuracy first
- direct explanation of cause and fix
- preserve code, commands, paths, and variable names
- no vague phrases like "robust solution" or "seamless integration"

## Article example

Prompt:

```text
Rewrite this article introduction. Remove the generic opening and start with the actual issue being discussed. Keep the tone professional and readable.

[paste introduction]
```

## Marketing example

Prompt:

```text
Rewrite this SaaS landing-page copy. Keep it persuasive, but replace unsupported superlatives with concrete product capabilities and outcomes.

[paste copy]
```

## What not to ask for

The project is not designed around prompts such as:

```text
Make this undetectable by AI detectors.
```

or:

```text
Add mistakes so it looks human.
```

A better request is:

```text
Rewrite this so it is clear, specific, natural, and appropriate for the intended reader while preserving the meaning.
```

That keeps the focus on writing quality rather than detector scores.
