---
name: inspo
description: "Influx Atelier Studio: references. Use when the person sends a link to a reel or a carousel (Instagram, TikTok), a video file, screenshots of stories or of an on-video caption: break it down (caption, sound, font, format) into Inspo of their Studio, and make an edit template (sample) from it. Start right away, no command needed."
---

# Inspo

A thin skill of the Influx Atelier Studio plugin. The rules are in the library on Google Drive, the person's settings are in their `Studio settings.md`. This file holds neither.

## First

1. Settings. Read the person's `Studio settings.md`: it holds everything personal (folders, tables, brands, reply language, their own rules). In Claude Code it is in the working folder (the studio folder; `CLAUDE.md` there names it). In a chat find it on Google Drive (a file titled "Studio settings" that the person owns) and download it. Use its sections "Everyone" and "Inspo". No such file: the studio is not set up yet, so run the setup skill of this plugin first.
2. Instruction. Download "ia-public-inspo — instruction.md" (Google Drive id `1EakidBoQG5DM2apHuVw2uXdbyz8tJNW7`) with the Google Drive connector's download action (download file content by id) and read the saved file. Get it again in every new session: it gets updated.
   Tools. The work needs the studio engine: at the start of the session run `studio.py ready` as the setup skill of this plugin says (a second when nothing changed) and use the python it prints. [samples tools] is the package "ia-public-inspo — samples.txt" (Google Drive id `1tCiwdyLmQACLsstDfwYpP3F_IA1Qz5lo`); the engine unpacks it into `~/.ia-studio/ia-inspo-samples`. Never open a package with a read action and never print it into the conversation: packages are code, not texts.
3. Work by the instruction. Where it says "the Settings block of the skill", that is the settings file. Where the settings and the instruction disagree, the settings win.
4. The instruction or a package does not open: say so in one line (access to the library may be missing: the person writes to Influx Atelier) and stop. Never work from memory.
5. A standing rule the person gives ("always…", "never…", "from now on…") goes into `Studio settings.md`, section "Inspo", under "My own rules", after they confirm it in a word. A remark about one video or one reply is not a rule.
