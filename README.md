# Nighter

A syllabus-first study skill that turns a course into manageable lessons and guides a student through them one topic at a time.

## How it works

1. Collect the syllabus and exact exam coverage, including partial modules.
2. Invite optional faculty notes and explicitly ask for past papers, special question banks, and important-question lists.
3. Ask about actual study time, desired depth, and starting knowledge.
4. Ask whether practice is wanted; separately set difficulty, amount, and allowed question sources.
5. **Show the complete lesson index before teaching:** every lesson grouped by module, total lessons, estimated time, and status.
6. Teach, check answers when requested, track coverage, and build focused revision notes.

Students can choose substantial mathematics practice, light practice with theory, or no practice. Difficulty is independent of quantity. Preferences can change during a session. Faculty-source-only practice is supported without silently introducing generated questions.

## Use and share

Download the distributable: [nighter.zip](dist/nighter.zip). It contains the `nighter/` skill folder, four references (including two fictional mock chats), optional Codex UI metadata, normal-chat editions, a platform guide, and an MIT license.

**Normal ChatGPT, Codex, Claude, or Gemini chat:** paste the contents of [START-HERE.txt](nighter/portable/START-HERE.txt) as your first message. No installation, special command, or custom assistant is needed. The prompt works on its own.

For the full guidance and fictional examples, attach [NIGHTER-COMPLETE.txt](nighter/portable/NIGHTER-COMPLETE.txt) and ask the model to use it as your study workflow, or paste its contents. All references are inlined. See [the platform guide](nighter/PLATFORMS.md) for setup routes, official documentation, and capability limits.

Optional invocation in a skill-aware Codex setup:

> Use $nighter to help me study for my exam. Start by asking for my syllabus.

Native skill setup differs by platform; the package does not assume every chat product supports ZIP skill imports. Normal-chat use and native import are separate routes. Package checks have passed; live imports and tutoring sessions on all four hosts have not been run.

No account connection, scripts, or runtime dependencies are required. Reading attachments and exporting notes depend on host tools. Pasted syllabus text works without attachments. The skill is self-contained and starts from each student’s own syllabus and preferences.

## Privacy and validation

The public package contains reusable instructions and two explicitly fictional demonstrations: quantitative methods with substantial practice, and museum visitor services with light practice. They use invented courses, numbers, dialogue, and questions. Real conversations, shared-chat URLs, faculty material, and student progress are excluded. The MIT license covers the skill's original instructions, not materials later uploaded by students.

Private development notes are stored outside this project and excluded from the archive. Local analysis, validation environments, and agent helper files remain Git-ignored. The repository includes the skill source, fictional examples, normal-chat editions, platform guide, and distributable ZIP.
