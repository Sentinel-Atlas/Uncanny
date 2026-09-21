# Last Spoonful — pilot production
Status: first-pass media pilot generated, assembled, and uploaded.
Budget checked through Higgsfield on 2026-09-21.

## Deliverable
A fixed-camera horror scene with 16 seconds of shared footage, an untimed decision hold, and one selected 14-second ending. Each playthrough contains 30 seconds of authored video, plus the time spent choosing. Both branches require 44 seconds of unique generated footage.

Options: **Wake her** / **Let her sleep**.
Wake her preserves the living mother and returns the child to an inert mannequin.
Let her sleep restores the child to life while his mother becomes a mannequin; he begins feeding her.

## Visual source and continuity
Source: repository image 5, `From Klickpin.com- Creepy Uncanny-board-image-5-pin-id-760686193359797989.jpg`.
The original photo was passed directly to Higgsfield as a reference image; import was confirmed.
Generated mother and child are fictional. The source guides mannequin material and red/blue clothing.
Continuity anchors: mother left in red cardigan, child right in blue sweatshirt, yellow bowl, striped napkin, black window, fixed seated eye-level camera.

## Verified settings and actual first-pass costs
| Work | Settings | Count/duration | Credits charged |
|---|---|---:|---:|
| Reference frames | GPT Image 2.5, Flare, high, 2K, 16:9 | 6 x 3 | 18 |
| First movement / retained motion test | Seedance 2.5, omni reference, 1080p, native audio | 4 seconds | 48 |
| Rest of shared introduction | Same settings | 12 seconds | 144 |
| Wake her outcome | Same settings | 14 seconds | 168 |
| Let her sleep outcome | Same settings | 14 seconds | 168 |
| **Actual first pass** | | | **546** |
| Correction reserve | Spending allowance, not an incurred charge | | **254** |
| **Pilot ceiling** | | | **800** |

Starting balance: 3,000 credits. Confirmed final balance: 2,454 credits. Balance at the pilot ceiling: 2,200 credits. Unused reserve is not spent. Recheck exact parameters before any materially different request.

Native video audio supplies room tone, spoon/bowl sounds, breathing, and brief dialogue. There is no separate voice-cloning or music-generation charge in this plan. No paid upscale is planned.

## Frame states
1. Human mother feeding the inert mannequin child (master frame).
2. Mother asleep; plastic child has made his first small movement.
3. Mother awake; child rigid again; small soup drop on his chin.
4. Mother asleep; her supporting left hand has turned plastic; the child gently removes it (decision state).
5. Mother human, awake, patiently feeding the rigid child again (Wake her).
6. Mother mannequin, child human, feeding her (Let her sleep).

All later frames reference the generated master, keeping the chosen identities and room. Minor character posture differences will be judged before motion generation.

## Screen-time plan
- 0–4 seconds: establish ordinary care; mother closes her eyes and the mannequin makes a small swallowing movement.
- 4–10 seconds: mother wakes; movement stops. She notices the soup and quietly tends to him.
- 10–16 seconds: she dozes off; her supporting hand becomes plastic. The child gently lifts it away.
- Decision hold: still/quiet image, with **Wake her** and **Let her sleep** rendered by the game.
- 16–30 seconds, Wake her: a quiet off-camera call wakes her; her hand returns to flesh; the child freezes. She offers another spoonful.
- 16–30 seconds, Let her sleep: the exchange completes. The now-human child feeds the motionless mother.

No explanatory monster speech, jump-scare overlay, or new supernatural rule in the ending.

## Execution order
1. Inspect the selected repository reference and obtain live cost estimates.
2. Generate and inspect the master frame.
3. Generate the five matching states; inspect hands, identities, materials, and positions.
4. Generate the four-second opening test; check eye-closure timing, restrained movement, and continuity.
5. Generate the remaining introduction and two branch clips using matching reference frames.
6. Inspect results. Correct specific failed shots within the pilot ceiling; retain successful material.
7. Assemble the shared introduction in Higgsfield's media workspace and export source clips.
8. Record result URLs, prompts, durations, and actual credit balance. Supply a simple branching manifest so a browser player can preload and select the correct ending.

The generation models create audiovisual assets. The game must render the buttons and choose clips; the generated movie itself is not clickable. No live generation is needed during gameplay.

## Completed outputs

- [intro.mp4](https://d2ol7oe51mr4n9.cloudfront.net/user_3HsJrX229RSJ25rMqKfb7m4UHJI/fda7bf64-ba56-4285-a6c3-927c00044bb8.mp4) — 16 seconds, H264/AAC, 1920×1080, 24 fps.
- [wake.mp4](https://d2ol7oe51mr4n9.cloudfront.net/user_3HsJrX229RSJ25rMqKfb7m4UHJI/a15ce196-93c6-4b95-acb2-1ecfbdac35a2.mp4) — 14 seconds, H264/AAC, 1920×1080, 24 fps.
- [sleep.mp4](https://d2ol7oe51mr4n9.cloudfront.net/user_3HsJrX229RSJ25rMqKfb7m4UHJI/3a3a833a-8b48-45ff-80ab-7215c2d44bd4.mp4) — 14 seconds, H264/AAC, 1920×1080, 24 fps.

The introduction and either ending provide exactly 30 seconds of authored footage. The decision hold adds the player's thinking time. See `production/last-spoonful/scene.json` for the branch graph and `generation-plan.json` for every exact generation request, reference ID, source URL, and result.

## Validation and remaining polish

Sampled frame sheets: 2fps for the four-second test and 1fps for the other clips; ffprobe inspection of raw and assembled media.

Trimmed the first two pieces to 4 and 12 seconds and joined them. Trimmed both outcomes to 14 seconds. Encoded H264/AAC inside Higgsfield sandbox and confirmed HTTP 200 uploads.

Sampled images show the mother becoming plastic and the child human in the sleep ending, and the mother human with the mannequin child in the wake ending.

- Small generated eye and hand movements remain; the rule that the boy is perfectly still while the mother is awake is not frame-perfect.
- Sampled frames do not establish uninterrupted motion quality. Audio streams are present, but dialogue wording, timing, voice consistency, and perceptual audio quality have not been verified by listening.
- An abrupt visual or audio seam may be noticeable between separately generated pieces. This is a first-pass media pilot, not a polished final game.
- The game runtime and clickable choices are specified in scene.json but not implemented in this deliverable.

All six images and all four source videos were generated in Higgsfield. Assembly was also performed in Higgsfield. No correction generations, standalone music, separate narration, or paid upscales were used. Total balance reduction: **546 credits**; **2,454 remain**. The **254-credit correction reserve remains unspent**.
