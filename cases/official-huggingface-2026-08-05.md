# Official MiniMax H3 cases

Source: [MiniMaxAI/MiniMax-H3 on Hugging Face](https://huggingface.co/MiniMaxAI/MiniMax-H3)

The official repository lists reproducible T2VA, FL2VA/I2VA, and Ref2VA video-audio generation cases. The request payloads explicitly use MiniMax-H3, and the repository provides both scripts and result videos.

## 1. T2VA — Starship bridge and hyperspace jump

- **Task:** Text-to-audio-video (T2VA)
- **Video:** 10 seconds
- **Aspect ratio:** 16:9
- **Resolution:** 768p reproducible result; the repository also documents a 2K workflow
- **Video:** [t2va.mp4](https://huggingface.co/MiniMaxAI/MiniMax-H3/blob/main/assets/t2va.mp4)
- **Prompt script:** [reproducible-768p-t2va-request.sh](https://huggingface.co/MiniMaxAI/MiniMax-H3/blob/main/scripts/readme/reproducible-768p-t2va-request.sh)

### Prompt summary

A cinematic medium-wide shot slowly pushes into a dim starship bridge. A female captain stands before a curved observation window while a fleet of dreadnoughts gathers outside. At 4.5 seconds, cut to a close-up and let the fleet jump to hyperspace in a blinding flash. The bridge shakes, the captain braces herself, the light fades, and she closes her eyes in the suddenly empty space.

Sound is specified separately: life-support hum, rising electronic whine, bass-heavy impact, metallic bridge vibration, then an empty room tone. Music is a slow space-opera orchestral score with a mournful French horn and sustained string dissonance that stops immediately after the jump.

### Reusable pattern

Use a short timeline with an explicit cut point, physical cause-and-effect, and a three-layer audio plan:

- `integrated_multimodal_description`: camera, action, and visible state change
- `overall_soundscape`: diegetic ambience and effects
- `non_diegetic_music`: score, tempo, instruments, and cue timing

## 2. I2VA / FL2VA — Ramen foreground and Japanese family dinner

- **Task:** First-frame image-to-audio-video / FL2VA-style case
- **Video:** 8 seconds
- **Aspect ratio:** Adaptive in the official case; the reproduced example is commonly presented as a landscape family-dinner shot
- **Resolution:** 768p
- **Video:** [fl2va.mp4](https://huggingface.co/MiniMaxAI/MiniMax-H3/blob/main/assets/fl2va.mp4)
- **Prompt script:** [reproducible-768p-fl2va-request.sh](https://huggingface.co/MiniMaxAI/MiniMax-H3/blob/main/scripts/readme/reproducible-768p-fl2va-request.sh)

### Prompt summary

Start with a static, shallow-depth-of-field live-action shot. A detailed bowl of ramen fills the sharp foreground while a family of seven remains softly blurred in a traditional Japanese dining room. Steam rises continuously. During the middle of the clip, smoothly rack focus from the ramen to the family, revealing their smiles, gestures, chopsticks, dishes, and lively interaction while the steam becomes a translucent foreground veil.

The sound design calls for quiet room tone, broth hiss and bubbling, ceramic and chopstick impacts, clothing movement, gentle acoustic guitar, and a subtle koto layer.

### Reusable pattern

A strong single-shot progression can be built from:

1. A visually dominant foreground anchor.
2. A continuous physical effect such as steam.
3. A controlled focus transition.
4. Background interaction revealed only after the focus shift.
5. Sound changes that follow the visual focus.

## 3. Ref2VA — Pink-suited man, black lamb, reused music, and voice reference

- **Task:** Multimodal reference-to-audio-video (Ref2VA)
- **Video:** 5 seconds
- **Aspect ratio:** Adaptive
- **Resolution:** 768p
- **Video:** [ref2va.mp4](https://huggingface.co/MiniMaxAI/MiniMax-H3/blob/main/assets/ref2va.mp4)
- **Prompt script:** [reproducible-768p-ref2va-request.sh](https://huggingface.co/MiniMaxAI/MiniMax-H3/blob/main/scripts/readme/reproducible-768p-ref2va-request.sh)

### Prompt summary

Define the roles explicitly:

- Video 1: source footage of a young man in a bright pink suit holding a black lamb.
- Audio 1: the source video's synchronized background music, reused in the target.
- Audio 2: a calm male voice-timbre reference.

Preserve the original identity, clothing, lamb, pasture, golden-hour lighting, framing, and white lambs in the background. Animate the man's mouth to speak two short English lines, then have him smile, look toward the horizon, stroke the lamb, and hold the peaceful final state. Keep Audio 1 under the new dialogue.

### Reusable pattern

For multimodal editing, define each input's job before describing the shot. Separate:

- identity and appearance preservation,
- source video retention,
- reused music,
- voice timbre,
- new dialogue,
- the exact moment speech ends and mouth motion stops.

## Verification

The official repository identifies the model as MiniMax H3 / MiniMax-H3 and labels these reproducible workflows as T2VA, FL2VA, and Ref2VA. See the [official model card](https://huggingface.co/MiniMaxAI/MiniMax-H3).
