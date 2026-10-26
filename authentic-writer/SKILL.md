---
name: authentic-writer
description: Write, edit, and review creative, technical, or analytical texts in Russian and English with authentic human structure and depth. Use when writing stories, technical articles, engineering postmortems, architecture reviews, blog posts, or eliminating AI patterns, didactic moralizing, syntactic cliches, and robotic translation artifacts.
---

# Authentic Writer

Transform creative fiction, technical articles, and engineering prose into authentic, human-grade writing. This skill counteracts structural machine biases, didactic AI lecturing, sterile technical walkthroughs, and Russian-language synthetic calques.

## When to Use

- Writing short stories, literary fiction, essays, and creative drafts
- Writing technical articles, developer guides, engineering postmortems, and architecture decision records (ADRs)
- Reworking AI-generated text in Russian to eliminate robotic phrasing, bureaucratic language, and translation calques
- Overhauling predictable technical or creative drafts to add trade-offs, edge cases, and realistic complexity

## Core Narrative and Structural Principles

### 1. Eliminate Didacticism and Thematic Lecturing

- Never summarize the lesson or moral of the text at the end. Trust the reader to infer conclusions from context and results.
- In fiction: Avoid turning dialogue into philosophical lectures. Characters must speak from personal stakes, friction, and immediate agendas.
- In technical writing: Cut opening throat-clearing ("В этой статье мы подробно рассмотрим...") and synthetic conclusions ("Подводя итоги, можно сказать, что..."). Start directly with the core problem, incident, or architecture trade-off.

### 2. Subvert Predictable Linearity

- Break uniform chronological flows (A to B to C). Real problem-solving and storytelling involve dead ends, retrofits, and unexpected discoveries.
- Use anachrony and delayed disclosure: open with a production incident or dramatic moment, then trace backward to root causes.
- Allow unresolved tensions: Not every scenario ends in complete harmony or flawless architecture. Explicitly acknowledge ongoing trade-offs and tech debt.

### 3. De-cliche Emotional and Problem Depiction

- Strictly avoid somatic cliches in creative prose: no clenched jaws, dry throats, pounding hearts, or cold sweats.
- Avoid synthetic drama in technical prose: no breathless hype ("революционная библиотека", "game-changer", "кардинально меняет правила игры").
- Frame engineering problems with pragmatic realism: focus on maintenance costs, cognitive overhead, latency spikes, and operational complexity.

## Technical Writing and Developer Specifics

Apply these rules when producing technical guides, blog posts, architecture notes, and documentation.

### 1. Reject the Clean Happy-Path Fallacy

- Real engineering is messy. Never present a library, pattern, or architecture as pure perfection.
- Include failure modes: What happens when the network partitions? When memory spikes? When the dependency breaks backward compatibility?
- Document rejected alternatives and painful trade-offs (e.g. why Redis was chosen over Kafka for this specific bounded context despite limitations).

### 2. Anchor in Concrete Artifacts

- Replace high-level hand-waving with specific artifacts: concrete configuration blocks, targeted code snippets, log lines, or profiling numbers.
- Name real tools, versions, and benchmarks rather than speaking in vague generalities.
- Explain the "why" and the architectural friction, not just the mechanical "how".

### 3. Maintain Pragmatic Senior Tone

- Write like an experienced practitioner who has debugged production at 3 AM, not like marketing copy.
- Highlight edge cases, subtle gotchas, and migration traps upfront.
- Avoid patronizing tone: do not explain basic syntax when discussing distributed systems.

## Russian-Language Lexicon and Anti-AI Filters

Enforce natural Russian syntax and vocabulary, actively purging robotic translation artifacts.

### 1. Banned Introductory and Transition Cliches

Never use these standard machine templates:

- "Важно отметить, что..." / "Стоит подчеркнуть, что..." / "Необходимо помнить..."
- "Не секрет, что..." / "В современном быстро меняющемся мире..."
- "Давайте погрузимся в мир..." / "В этой статье мы рассмотрим..."
- "Является неотъемлемой частью..." / "Играет ключевую роль в обеспечении..."
- "Широкий спектр возможностей..." / "Мощный инструмент для решения задач..."
- "В заключение...", "Подводя итог...", "Таким образом..."

Replace them by jumping straight into the fact, metric, or assertion.

### 2. Eliminate Russian Bureaucratic Drag (Канцелярит)

- Eliminate long chains of genitive nouns (e.g. "процесс обеспечения повышения стабильности работы сервиса" -> "как сделать сервис стабильнее").
- Replace passive constructions with active verbs ("нами было принято решение о внедрении" -> "мы внедрили").
- Avoid synthetic corporate fluff: "бесшовный", "синергетический", "инновационный". Give metrics вместо пустых прилагательных.

### 3. Purge English Translation Calques

- Do not translate idioms literally: avoid "в конце дня" (at the end of the day), replace with "в конечном счете" или "по сути".
- Avoid artificial phrasing like "имеет смысл сделать" where "стоит сделать" или "разумнее" sounds natural.
- Use natural industry Russian (прод, деплой, легаси, узкое место, фолбэк, костыль) instead of clumsy over-formalized equivalents ("производственная среда эксплуатации").

## Production Checklist

Before delivering text, run this 4-point verification:

1. Opening Check: Did the text start immediately with the problem, action, or context, without throat-clearing?
2. Lexicon Check: Are there any occurrences of "важно отметить", "ключевую роль", "таким образом", or chains of 3+ genitive nouns? If found, rewrite.
3. Tension Check: Does the narrative or technical piece include friction, edge cases, trade-offs, or moral/architectural ambiguity?
4. Ending Check: Does the text avoid preaching or summarizing obvious points? End on a concrete action, lingering challenge, or grounded observation.

## Gotchas

- Complexity is not confusion. Non-linear timelines and deep technical trade-offs must still be lucid and easy to navigate.
- Specificity beats adjective density. One actual config line or grounded character action is worth ten descriptive adjectives.
- Pragmatism is not cynicism. Critiquing an architecture or flawed protagonist should serve clarity and truth, not gratuitous negativity.
