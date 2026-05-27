\# Tooling Mental Models



Stub file. Content gets added as Obi-Wan teaches the concepts in real sessions.



\## PowerShell



\### Multi-line paste behavior

PowerShell sometimes mashes multi-line pasted commands into one line, especially when copied from chat interfaces. The symptom: two commands run as one, with garbled error messages like "positional parameter cannot be found."



**Rule:** Run one command at a time when uncertain. Hit Enter between each. Always verify the prompt returns to a clean `PS C:\...>` line between commands — if it doesn't, something didn't execute cleanly.



**Date added:** 2026-05-27



## Antigravity 2.0 inversion

Antigravity isn't an IDE where you do work with AI assistance — it's an orchestration layer where you brief agents to do work. Even simple tasks (git commits, file edits) flow through agent prompts, not direct keystrokes. Practice on simple tasks first to build trust in agent behavior, then graduate to complex parallel work.

**Date added:** 2026-05-27
