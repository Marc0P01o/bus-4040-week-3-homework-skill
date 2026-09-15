# BUS 4040 — Week 3 Homework, Part 1: Claude Skill

**Skill:** `course-study-notes`
**File:** [`course-study-notes/SKILL.md`](course-study-notes/SKILL.md)

## What the skill does

`course-study-notes` takes the raw material from a week of this course — the weekly
narrative, the homework file, any setup guides — and turns it into three things I can
actually study from: condensed notes, flashcards, and practice exam questions. Every
card and question is tagged with the week it came from, so when I miss one I know
exactly which file to go reread.

## How the skill works

A skill is a markdown file with two parts. The top is YAML frontmatter holding a `name`
and a `description`. The description is the important half, because that is what Claude
reads to decide whether the skill applies to what I just asked. A vague description
means the skill never triggers.

Everything under the frontmatter is the instruction set Claude follows once the skill
loads. Mine sets three rules up front — use only the source files, keep the course's own
vocabulary, tag everything with its source — and then walks through building the three
sections in a fixed order.

The part that surprised me is that a skill is not code. There is nothing to install and
nothing to run. It is written instructions that get pulled into the conversation at the
moment they become relevant. That lines up with what the Week 3 narrative said about the
harness being where features like Skills, Agents, and slash commands live, separate from
the model itself.

## Why I created it

This class has a final exam and the material is spread across a lot of separate .md
files. Before this, reviewing meant opening each file and rereading it, which is slow and
does not tell me what I actually do not know. I wanted something that turns those files
into questions I can fail, because failing a question is the fastest way to find the gap.

I also picked a study skill over something flashier because I will actually use this one.
The rules in it exist for a reason. "Use only the source files" is there because the
thing I most want to avoid is studying facts that are true in general but are not what
this course taught.

## How it can be useful later

Nothing in the skill is specific to BUS 4040. It takes course material in and produces
study material out, so it works for any class with readings and an exam. The same pattern
transfers past school too: point it at onboarding docs, a policy manual, or product
documentation and the output has the same shape — notes, cards, and questions that tell
you whether you actually absorbed the thing.

The broader lesson was that the real work was writing down a process I already do, badly
and inconsistently, in my head. Once it is written down it runs the same way every time.
