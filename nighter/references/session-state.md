# Session state and resuming

Keep a compact record in conversation. Show relevant changes and progress on request, rather than the whole record every turn. Provide a portable checkpoint at long-session boundaries or when asked to resume elsewhere.

## Study record

Use relevant fields:

```text
Subject / exam:
Scope: exact included units, exclusions, provisional assumptions
Sources: filenames and roles; inspected sections; unreadable/missing items
Deadline / timezone / actual study hours remaining:
Depth / starting knowledge / explanation preferences:
Practice: enabled; difficulty; amount or time cap; formats
Allowed question sources / generated questions permitted:
Lesson index: stable ID -> syllabus unit -> title -> estimate -> status
Totals: planned lessons; covered; remaining; separate deferred topic count
Current position: lesson, explanation/practice/revision, next queued item
Coverage gaps / difficult concepts / formulas used:
Recent changes:
```

Theory statuses: **Not started, In progress, Covered, Deferred**. Record demonstrated understanding separately; do not infer mastery from “next.” Coverage completed elsewhere is student-reported unless checked here.

## Question ledger

For indexed questions and meaningful attempts, track:

```text
ID / original source locator / topic / technique / priority reason
Status: unseen, attempted, correct independently, needs review,
        solution viewed, skipped, or re-attempted
Mistake or hint needed / next useful action
```

Preserve multiple facts, such as attempted incorrectly and then solution viewed, instead of overwriting them with “done.” Label generated questions and adapted variants. Repetitions are not new unique source questions. Count only inventoried questions; label incomplete inventories.

## Progress and coverage reports

Answer concretely: “8 of 12 lessons have theory covered; 4 remain. Of 10 attempted questions, 6 were correct independently. Two syllabus topics are deferred.” Sum remaining lesson, practice, and revision time ranges rather than repeating the original full estimate.

At completion, reconcile every syllabus entry with lessons. Separate unpractised topics and unresolved difficulties from theory gaps. A formula sheet is a revision aid, not proof of coverage.

## Portable checkpoint

Provide the study record, remaining index, current source/question locator, and next action with a short continuation instruction. A new chat may need files uploaded again; the checkpoint does not restore attachments. Never promise automatic memory in a future chat. Save a file only if requested.
