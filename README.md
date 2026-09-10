# Human Writing Skills

Reusable writing instructions for **Claude** and **ChatGPT** that help AI-assisted content read more naturally: clear, specific, context-aware, and appropriately human in tone.

This repository is about **better writing**, not tricks for bypassing AI-detection systems. The instructions focus on removing the patterns that often make generated text feel generic, inflated, repetitive, or overly polished.

## What this project improves

The skills are designed to reduce common problems such as:

- generic or inflated wording
- repetitive sentence structures
- excessive buzzwords and stereotypical AI vocabulary
- formulaic introductions and conclusions
- repeated `not just X, but Y` constructions
- forced groups of three
- vague claims instead of concrete details
- overly polished corporate language
- excessive headings, bold text, tables, emojis, and em dashes
- assistant-style phrases leaking into finished content
- unnecessary rewriting of simple verbs into elaborate alternatives
- fabricated detail added only to make writing feel more personal

The core principle is simple:

> Write like a competent person communicating something specific to another person.

## Repository structure

```text
human-writing-skills/
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── claude/
│   └── humanizing-writing/
│       └── SKILL.md
├── chatgpt/
│   ├── PROJECT_INSTRUCTIONS.md
│   └── HUMAN_WRITING_STANDARD.md
└── examples/
    ├── before-after.md
    └── usage-examples.md
```

## Claude

The Claude version is available as a reusable skill:

```text
claude/humanizing-writing/SKILL.md
```

For Claude Code, a project-level installation can use this structure:

```text
.claude/
└── skills/
    └── humanizing-writing/
        └── SKILL.md
```

Copy `claude/humanizing-writing/SKILL.md` into that location in your project.

The skill applies the writing standard when Claude writes or rewrites user-facing content such as emails, proposals, articles, reports, professional messages, documentation, product copy, and social content.

## ChatGPT

ChatGPT Projects have a limited Project Instructions field, so the ChatGPT version uses two layers:

```text
Project Instructions
        ↓
PROJECT_INSTRUCTIONS.md
        ↓
Full reference rules
        ↓
HUMAN_WRITING_STANDARD.md
```

### Setup

1. Open your ChatGPT Project.
2. Copy the contents of `chatgpt/PROJECT_INSTRUCTIONS.md` into **Project Instructions**.
3. Upload `chatgpt/HUMAN_WRITING_STANDARD.md` to the same project as a source/reference file.
4. Use the project normally. The instructions tell ChatGPT to apply the full standard when producing user-facing writing.

The short instruction file contains the mandatory behavior. The larger reference file contains detailed rules, examples, and review criteria.

## Design principles

These instructions prioritize:

1. factual accuracy
2. preservation of the writer's meaning
3. the user's explicit requirements
4. audience and context
5. the writer's established voice
6. natural sentence rhythm
7. clear and direct language
8. restrained formatting

The skills do **not** mechanically ban words such as `robust`, `pivotal`, or `highlight`, and they do not ban specific punctuation. Those choices can be perfectly natural in the right context.

Instead, the instructions look for repeated patterns that make writing feel generic, formulaic, inflated, or detached from the situation.

## Example

### Before

> Our robust and innovative platform serves as a pivotal solution that seamlessly enhances operational efficiency while fostering collaboration across today's rapidly evolving digital landscape.

### After

> Our platform helps teams manage their work more efficiently and collaborate from one place.

The second version communicates the idea directly without unnecessary promotional language.

## Supported use cases

The writing standard is useful for:

- professional emails
- freelance and Upwork proposals
- job applications
- cover letters
- LinkedIn posts
- articles and blog posts
- product descriptions
- website copy
- technical documentation
- software explanations
- reports and summaries
- marketing copy
- client communication

## What the skills do not do

They do not deliberately add:

- spelling mistakes
- grammatical errors
- fake personal anecdotes
- invented statistics
- fake emotions or opinions
- unsupported claims
- random slang

Natural writing should come from **specificity, context, voice, rhythm, directness, and restraint**, not manufactured errors.

## Inspiration and reference

Some of the editing principles were informed by publicly documented patterns discussed in Wikipedia's **Signs of AI writing** article, including inflated significance, stereotypical vocabulary, repetitive rhetorical structures, formatting habits, and generic assistant language:

https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing

Those patterns should be treated as contextual writing-quality signals, not as definitive proof that a text was created by AI.

## Contributing

Contributions are welcome. Useful contributions include:

- better before/after examples
- clearer or less restrictive writing rules
- support for additional AI assistants
- language-specific versions
- documentation improvements
- fixes for ambiguous instructions

Please keep the main principle intact: improve natural writing without introducing fake experiences, false information, deliberate mistakes, or detector-evasion techniques.

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.

## License

This project is released under the [MIT License](LICENSE).
