# awesome-minimax-h3-prompts

A curated collection of verified MiniMax H3 video cases and reusable prompting patterns.

## Inclusion criteria

A case is included in the main collection only when:

1. The source explicitly identifies MiniMax H3 / MiniMax-H3.
2. A video, video asset, or example clip is available.
3. The original post, official repository, or source page is traceable.
4. The prompt is available as an original prompt or an accurate structured summary.
5. Generic MiniMax, Hailuo, or unversioned examples are not treated as MiniMax H3.

## Cases

| Group | Contents | Source |
|---|---|---|
| Official MiniMax / Hugging Face | T2VA, I2VA/FL2VA, and Ref2VA reproducible cases | [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3) |
| fal.ai | Selected cases from a guide containing 44 H3 video examples | [Prompting Guide + 44 Video Examples](https://fal.ai/learn/devs/minimax-h3-prompting-guide) |
| Morphic | Selected copy-ready H3 prompt briefs with example clips | [MiniMax H3 Prompt Library](https://morphic.com/resources/how-to/minimax-h3-prompts) |
| Reddit / ComfyUI | H3 video reference with incomplete prompt disclosure | [Original Reddit post](https://www.reddit.com/r/StableDiffusion/comments/1vd9o0r/minimax_h3_1080p_25_seconds_text_to_video_in/) |
| Daily verified — 2026-08-09 | Player-stats UI, self-drawing field guide, seamless continuation, and full-reference music video | [Daily case file](cases/daily-2026-08-09.md) |
| Daily verified — 2026-08-10 | Character introduction, two-racer hover-bike chase, and audio-driven beat-synced showcase | [Daily case file](cases/daily-2026-08-10.md) |
| Daily verified — 2026-08-13 | Sensory beverage ad, concise genre-remix prompt, and folder-driven long-form workflow | [Daily case file](cases/daily-2026-08-13.md) |
| Daily verified — 2026-08-14 | Parameterized character reveal, directional stereo audio, surface-specific text reveal, and chained narrative continuity | [Daily case file](cases/daily-2026-08-14.md) |
| Daily verified — 2026-08-15 | Ref2VA performance replacement, timed two-reference handoff, and local multilingual T2VA | [Daily case file](cases/daily-2026-08-15.md) |
| Daily verified — 2026-08-16 | Reference-still prompt reconstruction and timed farmers-market micro-vlog | [Daily case file](cases/daily-2026-08-16.md) |

## Reusable patterns

- Assign an explicit role to every image, video, and audio reference.
- Use timecoded beats when a clip contains more than one action.
- Describe visible change and the desired end state, not only a static subject.
- Direct dialogue, ambience, foley, and non-diegetic music separately.
- Add continuity constraints and negative constraints where exact identity, text, logos, or geometry matter.
- For reference workflows, distinguish source footage, reused audio, and voice-timbre references.
- For UI and design animation, enumerate every locked element and name the reference the sole visual authority.
- For long-form continuation, combine a short temporal overlap with explicit first-frame continuity wording.
- For character introductions, reveal information progressively: signature detail, partial silhouette, face, then full-body design.
- For multi-vehicle action, bind each rider to a named vehicle with distinct color, silhouette, and spatial role.
- For music-driven generation, let the image own identity while the audio owns timing, rhythm, performance, and edit cadence.
- For sensory product ads, pair every timed visual action with a close-mic material sound cue.
- A concise premise works best when it specifies a source-world grammar, a contrasting presentation format, and one concrete conflict.
- For long-form work, treat each short scene as an addressable unit with fixed reference IDs, an explicit ending state, and selective regeneration.
- For reusable trailers, separate editable text parameters from a locked directing grammar for cuts, transitions, and reveal order.
- For stereo-first scenes, establish a neutral acoustic baseline and direct sound-source position, distance, and movement before visual escalation.
- When opposite surfaces need different text, bind each label to a surface and place a full occlusion between reveals.
- For chained clips, preserve screen position, travel axis, hand/prop ownership, unfinished secondary actions, end composition, and continuing audio as explicit state.
- For performance replacement, let the source video own motion, camera, timing, and environment while the image owns the replacement identity; re-light the subject and replace contact sounds.
- When multiple reference characters enter at different times, bind each identity to a named input and use a timed hard cut as the handoff boundary.
- For multilingual T2VA, place language-tagged dialogue inside its shot block, then direct ambience and non-diegetic music as separate sound layers.
- When deriving prompts from a found still, lock composition, lens feeling, lighting, palette, and atmosphere while explicitly replacing identity, action, and incidental text.
- For 15-second lifestyle scenes, use five three-second blocks that alternate object interaction, camera-facing dialogue, a transaction, relocation, and a closing payoff.

## Files

- [Official MiniMax cases](cases/official-huggingface-2026-08-05.md)
- [fal.ai selected cases](cases/fal-ai-2026-08-05.md)
- [Morphic selected cases](cases/morphic-2026-08-05.md)
- [Reddit / ComfyUI partial reference](cases/reddit-comfyui-2026-08-05.md)
- [Daily verified cases — 2026-08-09](cases/daily-2026-08-09.md)
- [Daily verified cases — 2026-08-10](cases/daily-2026-08-10.md)
- [Daily verified cases — 2026-08-13](cases/daily-2026-08-13.md)
- [Daily verified cases — 2026-08-14](cases/daily-2026-08-14.md)
- [Daily verified cases — 2026-08-15](cases/daily-2026-08-15.md)
- [Daily verified cases — 2026-08-16](cases/daily-2026-08-16.md)

Last collected: 2026-08-16
