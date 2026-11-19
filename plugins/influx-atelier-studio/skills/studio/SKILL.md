---
name: studio
description: "Influx Atelier Studio: the Studio page itself. Use to publish or update the person's Studio page, to fix how a section, a card or a tag looks, to add sounds, or when something in the Studio is missing or shows wrong."
---

# The Studio page

A thin skill of the Influx Atelier Studio plugin. The rules are in the library on Google Drive, the person's settings are in their `Studio settings.md`. This file holds neither.

## First

1. Settings. Read the person's `Studio settings.md`: it holds everything personal (folders, tables, brands, reply language, their own rules). In Claude Code it is in the working folder (the studio folder; `CLAUDE.md` there names it). In a chat find it on Google Drive (a file titled "Studio settings" that the person owns) and download it. Use its sections "Everyone" and "Studio". No such file: the studio is not set up yet, so run the setup skill of this plugin first.
2. Instruction. Download "ia-public-studio — instruction.md" (Google Drive id `1XMlD4tY0rZkbr8Aw2_5SiM_SsSoawuug`) with the Google Drive connector's download action (download file content by id) and read the saved file. Get it again in every new session: it gets updated.
3. Work by the instruction. Where it says "the Settings block of the skill", that is the settings file. Where the settings and the instruction disagree, the settings win.
4. The instruction or a package does not open: say so in one line (access to the library may be missing: the person writes to Influx Atelier) and stop. Never work from memory.
5. A standing rule the person gives ("always…", "never…", "from now on…") goes into `Studio settings.md`, section "Studio", under "My own rules", after they confirm it in a word. A remark about one video or one reply is not a rule.
