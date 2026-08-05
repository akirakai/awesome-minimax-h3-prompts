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

## Reusable patterns

- Assign an explicit role to every image, video, and audio reference.
- Use timecoded beats when a clip contains more than one action.
- Describe visible change and the desired end state, not only a static subject.
- Direct dialogue, ambience, foley, and non-diegetic music separately.
- Add continuity constraints and negative constraints where exact identity, text, logos, or geometry matter.
- For reference workflows, distinguish source footage, reused audio, and voice-timbre references.

## Files

- [Official MiniMax cases](cases/official-huggingface-2026-08-05.md)
- [fal.ai selected cases](cases/fal-ai-2026-08-05.md)
- [Morphic selected cases](cases/morphic-2026-08-05.md)
- [Reddit / ComfyUI partial reference](cases/reddit-comfyui-2026-08-05.md)

Collected: 2026-08-05
