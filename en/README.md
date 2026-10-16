# 48h Before the Meeting — English

[日本語](../ja/README.md) | [简体中文](../cn/README.md) | [Top](../README.md)

These are instructions for talking through your research with an AI before a progress meeting, so that you can explain your research algorithm and code in your own words.

## List of instructions

Choose the one written by your supervisor. If your supervisor has not written one, you may use any of them. Please tell your supervisor which one you used.

| Instructions | Author |
|---|---|
| [before-mtanaka](before-mtanaka.md) | [Masayuki Tanaka](https://www.vip.sc.eng.isct.ac.jp/mtanaka/) |


If you would like to add your own instructions, see [CONTRIBUTING.md](CONTRIBUTING.md).

## When to do it

Do this session **at least 48 hours before the meeting, and no later than 24 hours before**. Have your materials ready by then.
If you do it right before the meeting, you will not have time to make the necessary fixes or to deepen your understanding.
The AI will find the places where your understanding is shallow. The time after the session is what you need to deepen it.

## What you need

- An account for Claude, ChatGPT, or a similar service
- Your research progress materials (slides, notes)
- (If needed) your code

## How to use it with Claude

1. Create a new **Project** in Claude.
2. Open the project's **Instructions** and paste the contents of the instructions file. Do not include the code block fence (```); paste the text itself.
3. Start a new chat inside the project and attach your materials and code.
4. Send a message such as "Please begin," and answer the questions.

## How to use it with ChatGPT

1. Create a new **Project** in ChatGPT.
2. Paste the contents of the instructions file into the project's **Instructions** (without the code block fence).
3. Start a new chat inside the project and attach your materials and code.
4. Send a message such as "Please begin," and answer the questions.

## If you cannot use Projects

At the start of a new chat, paste the full text of the instructions, and attach your materials and code in the same message.

## How to provide your code

**Chat (Claude, ChatGPT):** Attach the main files.

**Coding tools (Codex, VS Code extensions, Claude Code, etc.):** Open the repository and paste the instructions as the first message of a new session. The AI reads the code itself, so you do not need to attach it. Tell the AI where your materials are (e.g., "The slides are in docs/progress.pdf"). Do not put the instructions in `AGENTS.md` or `CLAUDE.md`. Every ordinary development session would then turn into a sparring session.

**In this session, the code is not modified.** The AI only reads and asks questions. If the tool proposes editing a file, decline.

## Tips

- Answer in your own words, without looking at your materials and without asking another AI. The goal is not to answer correctly, but to find out what you do not yet understand.
- It is fine to say "I don't know." The AI will give you hints.
- When you want to finish, tell the AI "I'd like to wrap up." It will summarize what you understood, what is still vague, and what would be good to ask your supervisor. Take this to the meeting.
- Follow your lab's rules on whether unpublished data and code may be given to external AI services.
- Menu names in Claude and ChatGPT may change. If the display differs, look for the project's instructions (custom instructions) setting.

