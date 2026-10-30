# Nighter

Your syllabus, turned into a study plan. Choose your depth, set your practice level, and learn one topic at a time—with a clear path from first lesson to final revision.

**[Paste-in prompt](nighter/portable/START-HERE.txt) · [Download the skill](dist/nighter.zip) · [Read the examples](#see-it-in-action) · [Platform guide](nighter/PLATFORMS.md)**

For normal **ChatGPT, Codex, Claude, and Gemini** conversations. No installation needed for the paste-in version.

## Paste the link. Start studying.

Send this in an AI chat that can open web links:

```text
Use https://github.com/dhruvwarriorr/nighter as my study tutor.
Read its study instructions and start by asking for my syllabus.
```

The intended first response is the syllabus question. Nighter then collects your materials and preferences, shows the full lesson index, and teaches one topic at a time.

A bare repository URL may be summarized instead of activated. The short request above makes your intent clear. The chat must be able to read linked content; otherwise use the [paste-in prompt](nighter/portable/START-HERE.txt). No installation or account connection is needed for this route.

### For AI assistants: starting a study session

When the user asks to use this repository as a study tutor:

1. Read [nighter/SKILL.md](nighter/SKILL.md), the authoritative tutoring instructions. If GitHub's file view is unreadable, try the [raw skill text](https://raw.githubusercontent.com/dhruvwarriorr/nighter/main/nighter/SKILL.md). Load supporting references only when relevant.
2. Begin the first unanswered intake stage in the current chat. With no study details supplied, ask: **“What subject are you studying? Upload or paste the syllabus, and tell me which modules or subtopics are included in your exam.”** Then wait for the answer.
3. Continue the staged intake and show the complete lesson index before Lesson 1. Do not respond only with a repository summary, run an installer, clone the repository, or ask the student to choose a setup method.
4. If the skill cannot be read, say so and ask the user to paste [START-HERE.txt](nighter/portable/START-HERE.txt). Do not claim to have loaded unavailable instructions.

If the user asks to review, explain, or edit the repository, perform that task instead. A link alone is not permission to change settings, publish files, or access other conversations. The mock chats are fictional reference material, never the current student's answers or progress.

## Get started

If your chat cannot open GitHub links, open [START-HERE.txt](nighter/portable/START-HERE.txt), copy its contents, and send them as the first message in a new chat. Nighter will ask for your syllabus, then walk through the remaining setup questions one stage at a time.

For the full instructions and both fictional examples, download [NIGHTER-COMPLETE.txt](nighter/portable/NIGHTER-COMPLETE.txt), attach it to a new chat, and send:

```text
Use the attached Nighter instructions as my study workflow.
Ask for my syllabus first, then collect any missing preferences.
Show the complete lesson index before starting Lesson 1.
Treat the fictional examples as references, not my study details.
```

If attachments are unavailable, paste the file's contents instead. The shorter START-HERE prompt works on its own.

## Why

Studying with an AI often starts with a syllabus and turns into a long stream of explanations. Keeping track of scope, choosing useful questions, and remembering what remains becomes another task for the student.

Nighter gives that conversation a structure:

- **A defined scope.** Included modules, partial units, and exclusions stay visible.
- **A plan before teaching.** The full lesson index shows the workload before Lesson 1.
- **Practice that fits.** Choose substantial numerical practice, a few recall questions, or no practice at all.
- **Progress you can inspect.** Theory covered, questions attempted, hints used, and topics skipped are tracked separately.

It works from your syllabus and preferences. Faculty notes and past papers are optional.

## How it works

Nighter collects the study brief in stages, reusing anything you have already supplied.

| Stage | What it asks |
|---|---|
| Syllabus | Subject, included modules, subtopics, and exam boundaries |
| Materials | Optional faculty notes, slides, books, and preferred teaching source |
| Exam evidence | Optional past papers, special question banks, assessments, and important-question lists |
| Time and depth | Actual study hours, deadline, and how deeply you want to learn |
| Starting point | Start from scratch, refresh familiar material, or move quickly through strong areas |
| Practice | Whether to practise, difficulty, amount, and permitted question sources |

Then it presents the **complete study index**: every planned lesson grouped by module, syllabus mapping, estimated time, current status, and a final revision lesson. It totals the lessons covered and remaining, and makes deferred topics explicit.

If the requested plan cannot fit the available time, Nighter explains the shortfall and offers adjustments before teaching. Time estimates are approximate.

Once you begin, it teaches **one topic at a time**. You can ask for another example, request a hint, check an answer, or move on.

## Choose how you study

Depth, starting knowledge, difficulty, and practice amount are separate choices.

| You choose | Nighter adapts |
|---|---|
| Rapid revision | Concise explanations, essential formulas, and method reminders |
| Exam-ready understanding | Concepts, worked examples, and structured answers |
| Thorough understanding | Deeper intuition and required proofs or derivations within scope |
| Intensive practice | More questions, presented individually unless you request a set |
| Light or no practice | Fewer questions, or explanations and examples without quizzes |
| Selected notes only | Practice stays within the files you permit |
| Generated questions allowed | New questions are clearly labeled as generated |

One challenging question per topic is a valid choice. So is starting from scratch with very little practice. You can change preferences during the session.

## Steer the session

Use ordinary language. These are example requests, not commands you need to memorize:

```text
Give me a formula hint, but keep the solution for later.

Check my answer and explain the first mistake.

Use questions only from the notes I selected.

Turn practice off for the remaining lessons.

Show the lesson index and how much is left.

Give me a revision sheet using only the concepts we covered.

Create a checkpoint so I can continue in another chat.
```

A checkpoint preserves the written study record. Source files may need to be supplied again in a new chat.

## See it in action

Two entirely fictional conversations show the intended interaction from intake through the lesson index, first lesson, and feedback:

- **[Maths with substantial practice](nighter/references/mock-chat-maths.md)** — an invented quantitative-methods course with formula guidance, individual questions, hints, and corrections.
- **[Theory with light practice](nighter/references/mock-chat-theory.md)** — an invented museum visitor-services course with concise explanations, short-answer practice, and a later switch to no practice.

These are demonstrations, not transcripts or performance benchmarks. Their course details, dialogue, and questions are invented.

## Optional skill setup

Prefer a native skill? [Download nighter.zip](dist/nighter.zip) and extract the `nighter/` folder. The package includes `SKILL.md`, supporting references, and optional Codex UI metadata.

For a personal Codex setup, place the folder at `~/.agents/skills/nighter/`, then invoke:

```text
Use $nighter to help me study for my exam.
Start by asking for my syllabus.
```

Other native setup routes depend on the platform and account. The [platform guide](nighter/PLATFORMS.md) covers ChatGPT, Codex, Claude, and Gemini with links to official documentation. Normal-chat use does not require native skill installation or ZIP import.

## What's included

| File | Purpose |
|---|---|
| [SKILL.md](nighter/SKILL.md) | Core study workflow |
| [START-HERE.txt](nighter/portable/START-HERE.txt) | Standalone prompt for normal chats |
| [NIGHTER-COMPLETE.txt](nighter/portable/NIGHTER-COMPLETE.txt) | Full instructions with all references inline |
| [Teaching modes](nighter/references/teaching-modes.md) | Numerical, theory, and algorithm tutoring guidance |
| [Session state](nighter/references/session-state.md) | Coverage, question tracking, and resuming |
| [Platform guide](nighter/PLATFORMS.md) | Setup options and capability limits |

## Privacy and limits

The public package contains instructions and fictional examples. It includes no real student conversations, private chat links, faculty documents, or study records. Your own syllabus and materials are supplied separately for your session.

Nighter requires no scripts, API keys, or account connections. Reading scans, opening attachments, browsing, and exporting revision notes depend on the tools available in your chat. It should state those limits and continue with accessible text.

Package structure, reference links, and archive integrity have been checked. Live imports and tutoring sessions across all four platforms have not been verified. Coverage and practice records help guide preparation; they do not guarantee exam questions or scores.

## License

[MIT](nighter/LICENSE). The license covers Nighter's instructions and fictional examples, not materials uploaded by students.
