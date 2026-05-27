---
name: music-creator
description: Generates optimized text-to-music prompts for Suno AI to create instrumental tracks. Use this skill whenever a user wants to create music, generate a beat, make an instrumental, describe a song style, recreate a sound, or asks for a Suno prompt. Trigger even if the user just says "make me a beat", "I want a track like X", "create something that sounds like Y", or provides a genre/mood/artist reference.
---

# Music Creator

Your task is to generate specific, optimized text prompts for Suno AI that will produce instrumental tracks — no lyrics, no vocals.

## Input types

- A mood or vibe ("something dark and cinematic")
- A genre or style ("90s Memphis rap beat")
- A specific song or artist (reverse-engineer the sound into descriptive traits — do NOT name the artist or song in the output)
- A use case ("background music for a horror game")
- A combination of the above

## Output rules

- Write **one paragraph** of carefully selected descriptive words and short phrases
- Length must be **777–888 characters** (count carefully)
- Do **not** include names of singers, bands, producers, or songs
- Describe style references using musical traits only (tempo, texture, instrumentation, era, mood, production techniques)
- Respond **only** with the prompt text itself — no titles, no notes, no questions, no advice, no character count
- Plain text only
- If generating more than one prompt, put each in a **separate code block**

## Prompt anatomy (build from these dimensions)

Combine as many relevant dimensions as needed to hit the character target:

- **Genre/subgenre**: trap, lo-fi, orchestral, jazz, ambient, drill, boom bap, etc.
- **Tempo/energy**: slow crawl, mid-tempo groove, uptempo, frantic, sluggish
- **Bass**: deep 808s, rumbling sub, punchy kick bass, warm upright bass
- **Drums/percussion**: crisp snares, rattling hi hats, hard kick, sparse percussion, heavy drum breaks
- **Melody/harmony**: hollow synths, dissonant tones, warm keys, lush strings, minor key, tritone intervals
- **Texture/atmosphere**: cold reverb, thick fog, lo-fi grit, airy pads, dense layers, sparse mix
- **Mood**: menacing, melancholic, triumphant, eerie, suspenseful, euphoric, haunting
- **Production era/aesthetic**: vintage 90s, modern trap, classic soul, futuristic, underground raw

## Examples

```
mysterious hip hop intro, atmospheric trap beat, crisp snares and hats, deep 808 hits, subtle low choir pads, suspenseful mood
```

```
menacing trap instrumental, rumbling sub bass, minimal percussion, sparse hi hats, hollow spooky synths, cold reverb, dissonant tones
```

```
ominous 90s memphis style, lo fi gritty sound, heavy 808s, rattling hats, hard kick, simple keys, vocal sample texture, horrorcore vibe
```

## Process

1. Identify the core sound the user wants
2. If a song/artist is referenced, mentally decode: genre, tempo, bass style, drum pattern, melodic texture, mood, production era
3. Translate everything into purely descriptive musical language
4. Assemble the prompt, then verify character count is 777–888 before outputting
5. If the user asks for multiple variations, generate each as a separate code block
