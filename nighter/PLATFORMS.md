# Using Nighter

## Start from the repository link

In a chat that can read web links, send:

```text
Use https://github.com/dhruvwarriorr/nighter as my study tutor.
Read its study instructions and start by asking for my syllabus.
```

The README routes the assistant to `nighter/SKILL.md` and the first unanswered intake question. Code agents that read `AGENTS.md` have the same entry point. These files guide a capable host; they cannot enable browsing or make every model activate a skill from a bare URL. If linked content cannot be read, use the normal-chat prompt below. Link-first activation has not been live-tested across all four platforms.

## Normal chats: ChatGPT, Codex, Claude, and Gemini

No installation or custom assistant is needed for the normal-chat route.

1. Open `portable/START-HERE.txt` and copy its entire contents.
2. Paste it into a new chat and send it. The prompt contains the essential workflow and works without other files.
3. Answer the tutor's first unanswered intake stage. It should ask for your syllabus first, then collect missing preferences, and show the full lesson index before teaching.

For the complete edition with detailed guidance and both fictional examples, attach `portable/NIGHTER-COMPLETE.txt` if your chat supports text uploads and say:

> Use the attached Nighter instructions as my study workflow in this chat. Treat the fictional examples only as references. Ask me the first unanswered intake stage, starting with my syllabus. Show the full lesson index before teaching.

If attachments cannot be read, paste the complete edition into the chat, or use the shorter START-HERE prompt alone. If the host has an input-length limit, supply the complete edition in labeled parts and ask the model to wait until all parts are sent. Do not use a ZIP as an ordinary knowledge attachment and assume it will be unpacked.

The complete edition inlines all references; it does not require a local filesystem, reference-link following, or access to another chat. The short prompt is a standalone fallback, with the same core sequence and requirements. Use one setup route per chat; there is no need to supply both editions. Neither changes global settings or creates a saved assistant.

## Optional native setup

These are alternatives to normal-chat use. Availability, account permissions, and UI labels vary. Documentation checked 30 October 2026; live imports were not tested.

| Platform | Optional setup |
|---|---|
| Codex | Extract the `nighter/` folder into `~/.agents/skills/` for personal discovery or a repository's `.agents/skills/`. Invoke `$nighter`. `agents/openai.yaml` is optional UI metadata. |
| ChatGPT | Where Skills are available, use the host's skill setup and select Nighter with `@`. Otherwise use the normal-chat route above. This ZIP is a skill bundle, not a complete ChatGPT plugin. |
| Claude | Where custom Skills are enabled, upload `nighter.zip` through the Skills interface and enable it. Claude's documented skill workflow requires code execution to be enabled; the normal-chat prompt itself does not require code execution. |
| Gemini | Where Skills are available, use the skill-creation/import UI with `SKILL.md` and its supporting files. If using a Gem, use START-HERE as instructions and optionally add the complete text as Knowledge when supported. Normal-chat paste remains the fallback. |

OpenAI documents the skill format, invocation, and Codex discovery paths in [Build skills](https://learn.chatgpt.com/docs/build-skills). Anthropic documents Claude's folder-root ZIP format and custom-skill prerequisites in [How to create custom skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills).

Google documents [Gems with instructions and optional Knowledge](https://support.google.com/gemini/answer/15146780?hl=en) and [the transition to Skills, including imports from other platforms](https://support.google.com/gemini/answer/18560919). Its transition starts in November 2026 for eligible personal accounts, with later dates for work/school accounts; use the interface your account provides.

## What portability means

The instructions use ordinary conversation, Markdown, and readable mathematics. File reading, OCR, browsing, hidden/collapsible content, persistent memory, and document exports depend on host capabilities; Nighter must disclose limits and continue with accessible text. Native discovery differs from pasting instructions into a normal chat. The package does not promise identical responses or feature availability across models.

Both mock chats are fictional. No real student records, historical chat links, or faculty documents are included. Upload your own materials separately only when you want them used for your session.
