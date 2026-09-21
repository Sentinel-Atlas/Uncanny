# Last Spoonful — pilot production
Status: scenario approved; generation in progress.
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

## Verified settings and planned costs
| Work | Settings | Count/duration | Quoted credits |
|---|---|---:|---:|
| Reference frames | GPT Image 2.5, Flare, high, 2K, 16:9 | 6 x 3 | 18 |
| First movement / retained motion test | Seedance 2.5, omni reference, 1080p, native audio | 4 seconds | 48 |
| Rest of shared introduction | Same settings | 12 seconds | 144 |
| Wake her outcome | Same settings | 14 seconds | 168 |
| Let her sleep outcome | Same settings | 14 seconds | 168 |
| **Planned first pass** | | | **546** |
| Correction reserve | Spending allowance, not an incurred charge | | **254** |
| **Pilot ceiling** | | | **800** |

Starting balance: 3,000 credits. Expected balance after the first pass: 2,454 credits. Balance at the pilot ceiling: 2,200 credits. Unused reserve is not spent. Recheck exact parameters before any materially different request.

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
