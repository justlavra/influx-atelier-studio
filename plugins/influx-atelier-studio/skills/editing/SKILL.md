---
name: editing
description: "Influx Atelier Studio: making a video. Use for a reel from a sample or from a reference, a slideshow cut to music, a talking head: «смонтируй», «сделай ролик», «make a video», «go» on a video in the Studio, notes on a draft. Never starts with the video: options first, the video after the person's go."
---

# Editing

A thin skill of the Influx Atelier Studio plugin. The rules are in the library on Google Drive, the person's settings are in their `Studio settings.md`. This file holds neither.

## First

1. Settings. Read the person's `Studio settings.md`: it holds everything personal (folders, brands, reply language, their own rules). In Claude Code it is in the working folder (the studio folder; `CLAUDE.md` there names it). In a chat find it on Google Drive (a file titled "Studio settings" that the person owns) and download it. Use its sections "Everyone" and "Editing". No such file: the studio is not set up yet, so run the setup skill of this plugin first.
2. Library. The editing library is three packages on Google Drive: base, required, "ia-public-editing — base.txt" `1vyP1Q9wu3eLgsZh7N1CTRdaAs-Vul3Go`; "ia-public-editing — emoji animations.txt" `1uH_7gyyNG3GpTsA1fkpW6SOO98sU9Zex`; "ia-public-editing — graphics and text.txt" `1VzTFO8iqC8kvjox1jXxrKqGneSqhTXjb`. At the start of the session run the studio engine, `studio.py ready`, as the setup skill of this plugin says (a second when nothing changed): it unpacks them into `~/.ia-studio/ia-editing` and prints the python to use for every command. Never open a package with a read action and never print it into the conversation.
3. Read `~/.ia-studio/ia-editing/README.md` and work by it. Where it says "the Settings block of the skill", that is the settings file. Where the settings and the README disagree, the settings win.
4. The order of work is fixed: never the video first. Options and choices in the Studio, then the video, each step after the person's go.
5. A package does not download or unpack: say so in one line (access to the library may be missing: the person writes to Influx Atelier) and stop. Never work from memory.
6. A standing rule the person gives ("always…", "never…", "from now on…") goes into `Studio settings.md`, section "Editing", under "My own rules", after they confirm it in a word. A note on one video is not a rule.
7. A reel from a sample is editing; making the sample itself is the inspo skill of this plugin.
