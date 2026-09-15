---
name: course-study-notes
description: Turn a weekly course narrative, lecture notes, or reading file into condensed study notes, flashcards, and practice exam questions. Use when the user points at class material and wants to review it, study it, or prepare for an exam.
---

# Course Study Notes

Turn raw class material into something you can actually study from.

## When to use this

The user has a file, or several, of course material — a weekly narrative, lecture
notes, a reading, a syllabus — and wants to study it. Typical asks: "help me study
this", "make flashcards from week 3", "quiz me on this", "what is likely on the exam".

## Rules

1. **Use only the source files.** Every note, card, and question must trace back to
   something written in the material the user gave you. Do not add outside facts, even
   correct ones. If something in the material is unclear or contradictory, say so
   rather than smoothing it over.
2. **Keep the course's own vocabulary.** If the material says "harness", do not
   substitute "wrapper" or "client". The exam will use the course's words.
3. **Tag everything with its source.** Every card and question gets a marker for which
   file or week it came from, so the user knows where to go back and review.

## Steps

1. Read every file the user pointed at. If they named a folder, read what is in it.
2. Build the three sections below, in this order, in a single markdown file.
3. Save it next to the source material as `study-<topic>.md` and tell the user where
   it went.

### Section 1 — Study notes

Condense the material into the points that carry weight. For each point, write one line
for the claim and one line for why it matters or what it connects to. Group by week or
topic, in the order the course presented it. Cut restatements and filler — a slide that
says "Welcome to week 3" produces no note.

### Section 2 — Flashcards

15 to 25 cards as a two-column table: **Prompt | Answer**. Mix the types:

- Definitions ("What is a harness?")
- Distinctions ("Harness vs. model — what is the difference?")
- Ordered lists ("Name the four Claude tiers, largest to smallest")
- Applications ("You need cheap, high-volume work. Which tier?")

Facts that are easy to mix up deserve their own card. Numbers, version names, and
anything the material stated twice are all worth a card.

### Section 3 — Practice exam questions

10 to 15 questions, a mix of multiple choice and true/false. For each one, give:

- The question
- The options, four of them for multiple choice
- The answer, with one sentence saying why
- The week or file it came from

Write plausible wrong options. Pull them from real terms elsewhere in the material, not
from nonsense. A question whose wrong answers are obviously silly teaches nothing.

## Finishing

Tell the user which topics the material covered thinly, so they know where to ask the
instructor rather than assuming the notes are complete.
