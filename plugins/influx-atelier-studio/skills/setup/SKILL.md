---
name: setup
description: "Influx Atelier Studio: set up, check or update the studio on this computer or in this chat. Use for «установи студию», «set up my studio», «проверь студию», «обнови студию», the first message of a person who just got the studio, or when another studio skill finds no settings file or no engine."
---

# Studio setup

A thin skill of the Influx Atelier Studio plugin. The rules are in the library on Google Drive, the person's settings are in their `Studio settings.md`. This file holds neither.

## First

1. Settings. Read the person's `Studio settings.md`: it holds everything personal (folders, tables, brands, reply language, their own rules). In Claude Code it is in the working folder (the studio folder; `CLAUDE.md` there names it). In a chat find it on Google Drive (a file titled "Studio settings" that the person owns) and download it. Use its sections "Everyone" and "Everyone". No such file: the studio is not set up yet, so run the setup skill of this plugin first.
2. Instruction. Download "ia-public-setup — instruction.md" (Google Drive id `1JO8mDIOtJKKuOs4_0_6a2khCHrneyuMg`) with the Google Drive connector's download action (download file content by id) and read the saved file. Get it again in every new session: it gets updated.
   Library files for the setup (Google Drive ids): [engine] "ia-public-studio — engine.txt" `1ZAfpvRunLgsMy-I2iWgCigGeiybigcL7`; [packages]: "ia-public-editing — base.txt" `1vyP1Q9wu3eLgsZh7N1CTRdaAs-Vul3Go`, "ia-public-editing — emoji animations.txt" `1uH_7gyyNG3GpTsA1fkpW6SOO98sU9Zex`, "ia-public-editing — graphics and text.txt" `1VzTFO8iqC8kvjox1jXxrKqGneSqhTXjb`, "ia-public-inspo — samples.txt" `1tCiwdyLmQACLsstDfwYpP3F_IA1Qz5lo`. Never open them with a read action and never print them: they are packages.
3. Work by the instruction. Where it says "the Settings block of the skill", that is the settings file. Where the settings and the instruction disagree, the settings win.
4. The instruction or a package does not open: say so in one line (access to the library may be missing: the person writes to Influx Atelier) and stop. Never work from memory.
5. A standing rule the person gives ("always…", "never…", "from now on…") goes into `Studio settings.md`, section "Everyone", under "My own rules", after they confirm it in a word. A remark about one video or one reply is not a rule.

No `Studio settings.md` yet is the normal start for this skill: the setup creates it (`studio.py folder`).
