# Last Spoonful — media pilot

30 seconds per playthrough, plus an untimed choice.

## Watch

Open the exported URLs in `scene.json` for the introduction (16 seconds) and either ending (14 seconds). The `clips/`, `raw/`, and `frames/` directories described below are included in the downloadable media kit; this repository stores the manifest and production records. These are separate clips for a branching game; the video files themselves do not contain clickable buttons.

- **Wake her:** the mother remains human; her son remains a mannequin.
- **Let her sleep:** the son becomes human; his mother becomes a mannequin, and he feeds her.

## Make it interactive

`scene.json` is the scene data, not an implemented player. In your React/TypeScript game, load this data and keep the runtime small:

1. A Start button begins the intro with sound. Preload both endings during it.
2. On the intro's ended event, keep its last decoded frame visible. Overlay two real HTML buttons, **Wake her** and **Let her sleep**. Use keyboard focus and normal button semantics. There is no timer.
3. On selection, lock both buttons, store the choice, and play that ending. Keep the held intro visible until the selected video has a decoded frame ready, then switch visibility. Display a retry control if the file fails to load.
4. On the ending's ended event, record the corresponding character states from scene.json and offer Replay.
5. Test each branch, keyboard selection, slow loading, and replay. No model request is made during gameplay.

For a straightforward implementation, use one visible intro video and two preloaded ending video elements. Keep controls outside the media pixels so copy, placement, and accessibility remain editable. Retain the paused final intro frame at the choice; `frames/04-decision.png` is only a fallback because it may differ slightly from the final generated frame.

The 16-second intro plus the 14-second ending is 30 seconds of authored footage. Time spent reading and choosing is extra. Clip-local native audio ends with each clip; a later audio pass can supply continuous room tone for the decision hold.

## Contents

- `clips/`: assembled H264/AAC MP4s at 1080p, 24 fps.
- `raw/`: four original Seedance 2.5 videos, including the retained four-second motion test.
- `frames/`: six full-resolution GPT Image 2.5 frames generated in Higgsfield.
- `generation-plan.json`: exact prompts, settings, reference imports, generation job IDs, output URLs, and actual credits.
- `production.md`: the scenario, timing, production steps, and known limitations.
- `scene.json`: branching data and outcome states.

## Reference provenance

The original input was GitHub image 5, `From Klickpin.com- Creepy Uncanny-board-image-5-pin-id-760686193359797989.jpg`, from Sentinel-Atlas/Uncanny. Higgsfield imported that image directly (media ID `3ddabdfd-3cd1-4249-800b-57b1228d1881`). The master used that import; the five other state frames referenced the master; the videos referenced those generated states. We did not supply all repository images to every generation.

## Cost and review status

Six frames: 18 credits. Four seconds of video: 48. Twelve seconds: 144. Two fourteen-second endings: 336. Total confirmed balance reduction: **546 credits**. Balance: **2,454**. Pilot correction allowance: **254 still unspent**.

This is a first-pass media pilot. Sampled frames and media metadata were inspected; minor eye/hand movements remain. The boy's stillness rule is not frame-perfect. Audio exists but has not been verified by listening; assess the generated dialogue, sound, and joins before treating this as a final release.
