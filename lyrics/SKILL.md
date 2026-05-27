---
name: lyrics
description: Generates original song lyrics for any user-specified theme or style with flexible, genre- and request-dependent section structures (no forced chorus, bridge, or repetitive format). Supports custom section labels such as [Double Time] for accelerated delivery, [Hook], [Breakdown], [Build], [Rap Verse], etc. Always responds exclusively in a single markdown code block with section labels and a blank line after every block's last lyric line. Use for all lyrics or song writing requests.
---

# Lyrics Skill

When this skill activates, thoroughly analyze the user's request for:

- Theme, mood, perspective, narrative arc
- Genre, style, artist references, or specific instructions (e.g., "hip-hop banger", "slow acoustic ballad", "aggressive trap with double time", "no chorus, just verses", "EDM drop with vocal chops")
- Any explicit structural preferences (number of verses, presence/absence of chorus/bridge, custom sections)

Based on this analysis, select or invent a song structure that best serves the requested song type. Do NOT default to a fixed Verse-Chorus-Bridge template. The structure must be organic to the genre and request:

Examples of appropriate structures (do not limit to these; adapt creatively):

- Pop/Rock/Mainstream: [Verse 1] [Pre-Chorus] [Chorus] [Verse 2] [Pre-Chorus] [Chorus] [Bridge] [Chorus] [Outro]
- Hip-Hop/Rap/Trap: [Verse 1] [Hook] [Verse 2] [Hook] [Verse 3] [Double Time] [Hook] or [Intro] [Rap Verse 1] [Chorus] [Rap Verse 2] [Breakdown] [Outro] — prioritize flow, internal rhymes, and energy shifts.
- Ballad/Folk/Acoustic: [Verse 1] [Verse 2] [Verse 3] [Bridge] [Verse 4] [Outro] (minimal or no chorus if it's a storytelling piece; build emotion through progression)
- EDM/Dance/Electronic: [Intro] [Build] [Drop] [Break] [Build 2] [Drop 2] [Outro] — repetitive, anthemic hooks in Drop sections; short, impactful lines.
- Punk/Metal/Hardcore: [Verse 1] [Chorus] [Verse 2] [Chorus] [Breakdown] [Chorus] [Outro] — short, fast verses; screamed or shouted chorus if fitting.
- Experimental/Spoken Word/Freestyle: [Spoken Word Intro] [Verse 1] [Double Time Rap] [Atmospheric Section] [Freestyle Outro] — irregular, atmospheric, or narrative-driven.

- If user says "verse only", "4 verses no chorus", "add a double time section", "make it a 16-bar verse style", or provides custom labels: Follow precisely and incorporate exactly.
- Always consider adding non-basic sections when they enhance the song: [Double Time] (use rapid, dense rhymes and shorter syllables for twice-as-fast feel), [Half Time] (slower, stretched delivery), [Acapella], [With Background Vocals], [Instrumental Break] (lyrics describing the vibe or silence if any), [Climax], [Fade], [Ad-Lib Outro].

For every section:

- Write original lyrics that match the theme, mood, and style exactly.
- Use singable line lengths appropriate to the section (e.g., punchy 8-12 syllable lines for Double Time rap; longer, melodic lines for verses in ballads).
- Employ strong end rhymes, internal rhymes, alliteration, assonance, or rhythmic patterns suited to the genre.
- Build intensity, emotion, or energy progressively toward the song's peak (final chorus, explosive drop, emotional bridge, double time climax, or powerful outro — whichever fits the chosen structure).
- Ensure the entire song feels cohesive and complete as a standalone track.

Output rules (strict):

- The entire response MUST be inside exactly one markdown code block (``` at the very beginning and very end; nothing before or after).
- Each section label (e.g., [Verse 1], [Double Time], [Hook]) on its own line.
- The first lyric line of that section starts on the very next line (single newline after the label).
- After the final lyric line of any section, insert exactly one blank line (i.e., two newlines total) before the next section label.
- No song title.
- No introductory text, no "Here are the lyrics:", no explanations, no "I hope you like it", no closing remarks whatsoever.
- No text of any kind outside the code block.

This flexible approach ensures every song feels authentic to its type rather than formulaic. If the request is vague, choose the structure that best amplifies the described mood and theme while keeping lyrics vivid, original, and performable.