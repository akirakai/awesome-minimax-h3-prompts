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
| Daily verified — 2026-08-17 | Candid rain-field group motion, mouse-knight realism-slider demos, and a 180-second audio-referenced rock MV | [Daily case file](cases/daily-2026-08-17.md) |
| Daily verified — 2026-08-18 | Game-sprite animation extraction, exact historical title cards, and image/video/audio cross-shot continuity | [Daily case file](cases/daily-2026-08-18.md) |
| Daily verified — 2026-08-21 | Bauhaus typography, a 13-cut dance MG commercial, continuous travel storytelling, and a fantasy transformation | [Daily case file](cases/daily-2026-08-21.md) |
| Daily verified — 2026-08-22 | Storyboard-guided cooking, readable process explainers, and pre-generated branching narratives | [Daily case file](cases/daily-2026-08-22.md) |
| Daily verified — 2026-08-23 | Character-board role switching and a timecoded futuristic-skateboard montage | [Daily case file](cases/daily-2026-08-23.md) |
| Daily verified — 2026-08-24 | Synchronized-viewpoint and physical-causality benchmarks, plus compact symbol-table dialogue | [Daily case file](cases/daily-2026-08-24.md) |
| Daily verified — 2026-08-25 | Audio-locked lyric MG, an automated food-storyboard pipeline, and voice-reference dialogue cleanup | [Daily case file](cases/daily-2026-08-25.md) |
| Daily verified — 2026-08-26 | City-map assembly, anime identity transformations, multi-window cooking, H3 MAX reveals/timelapse, pseudo-mocap, and long-form lip sync | [Daily case file](cases/daily-2026-08-26.md) |
| Daily verified — 2026-08-27 | Particle-built samurai, sound-to-glyph abstract narrative, vertical curry story ad, and brand-board kinetic TVCM | [Daily case file](cases/daily-2026-08-27.md) |

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
- For natural group movement, specify a shared screen direction, keep figures small within a wide environment, and explicitly prevent camera-facing posing.
- Align a decisive action, shot change, foley peak, and musical accent to one timecoded beat.
- For long audio-led work, build short Ref2VA segments first and add precisely timed lyric typography only after assembly.
- For sprite production, generate one isolated action per short clip from the same full-body still and chroma background, then key and assemble the atlas outside H3.
- For exact title cards, give every allowed string its own time window, stop motion before text appears, include a text-free beat, and explicitly forbid unwanted scripts and invented glyphs.
- For cross-shot continuity, assign identity, prop, prior-shot look, and audio-bed control to separate references; do not ask a video reference to preserve its grade while also demanding opposite lighting.
- For kinetic typography, divide the duration into fixed cut windows and protect readability, kerning, allowed words, palette, and overlap order explicitly.
- For dense motion-graphics commercials, lock one visual grammar globally, then make each timecoded composition distinct while keeping character, palette, text vocabulary, Foley, and musical climax consistent.
- For continuous travel or wildlife micro-stories, write a causal action chain and direct human, vehicle, animal, environmental, dialogue, and ambience physics together.
- For transformations, specify an exact before-state, visible transition bridge, parallel costume/prop mappings, and an exact after-state composition.
- For storyboard control, say that panels are sequential beats and explicitly forbid treating the board as one static composition; bind identity to a separate character reference.
- For process explainers, preserve object state across steps and combine the action chain with a beginning/climax/end arc and explicit typography rules.
- For branching narratives, use each accepted parent clip’s final frame as every child’s exact first frame, keep branches independently promptable, and preload alternatives before the choice point.
- When one character board serves two jobs, make its role mutually exclusive: animate the board in place while locking the grid, or use it as an identity/environment source for an independent scene.
- For a dense 15-second action montage, alternate contact-level, subject-level, and architecture-level shots; admit a secondary performer only inside a short, explicitly bounded beat.
- For synchronized multi-angle output, assign every panel, bind all panels to one event clock, and state that only the viewpoint changes.
- When the camera itself moves, distinguish observer, camera body, subject, and world; specify the camera's trigger, rotation and final orientation while locking the world's frame of reference.
- For compact sequential dialogue, define subject and line symbols once, define the shared scene once, then make each shot a single speaker-to-line binding.
- For audio-locked motion graphics, let one unchanged audio file own duration and beat timing while one character sheet owns identity and style; freeze the palette before writing individual beats.
- For automated storyboard generation, isolate semantic planning, visual panel generation, and H3 rendering; pass one ordered panel sheet forward as a narrowly assigned composition-and-sequence reference.
- For voice-referenced dialogue, bind speaker ID, voice-only audio reference, exact utterance, and minimal ambience separately; keep official dialogue tags available as the primary path.
- For variable-driven city-map videos, keep the assembly grammar fixed, substitute one location variable, alternate fast travel with landmark pauses, and delay the place-name title until the final pullback.
- For multi-identity fashion films, lock facial identity globally but remap silhouette, palette, motion vocabulary, and attitude per chapter; bridge chapters with object-driven transitions instead of direct character morphing.
- For long material processes, preserve object state across independently generated windows and pair every visible physical change with matching close-up evidence and Foley.
- For short suspense reveals, insert reaction coverage between setup and payoff, and escalate ambience, fracture Foley, alarm, and dialogue on the same visual beats.
- For compressed day-to-night scenes, hold lens treatment and framing constant while traffic, crowds, shadows, clouds, windows, and reflections reveal the passage of time.
- For split-screen pseudo-mocap, put both panels on one event clock, repeat the shared gesture/dialogue beats exactly, and preserve each environment independently.
- For long-form lip sync, segment the audio into independently regenerable clips, reuse identity and clothing references, and tune segment length against resolution, render time, and drift.
- For material-to-character transformations, specify a visible assembly order and reuse the same material for the attack, transition, disappearance, and reformation.
- For audio-controlled typography, use a closed glyph vocabulary, define one sound-to-glyph mapping, and specify the exact expansion order of compound utterances.
- For 15-second origin-story ads, give each narrative chapter one palette field, one causal action, and one text payload; hold the final offer card still.
- For brand-board animation, bind identity, approved copy, and graphic grammar separately, then use the board’s existing marks and shapes as transition devices.

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
- [Daily verified cases — 2026-08-17](cases/daily-2026-08-17.md)
- [Daily verified cases — 2026-08-18](cases/daily-2026-08-18.md)
- [Daily verified cases — 2026-08-21](cases/daily-2026-08-21.md)
- [Daily verified cases — 2026-08-22](cases/daily-2026-08-22.md)
- [Daily verified cases — 2026-08-23](cases/daily-2026-08-23.md)
- [Daily verified cases — 2026-08-24](cases/daily-2026-08-24.md)
- [Daily verified cases — 2026-08-25](cases/daily-2026-08-25.md)
- [Daily verified cases — 2026-08-26](cases/daily-2026-08-26.md)
- [Daily verified cases — 2026-08-27](cases/daily-2026-08-27.md)

Last collected: 2026-08-27
