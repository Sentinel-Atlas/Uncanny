# YOU CAN WATCH
## 30-second branching horror scene — draft for approval

Status: STORY DRAFT. No Higgsfield generation or game implementation authorised by this document.
Scope: one unseen protagonist, one doorway entity, two choices, two distinct outcomes. The seven-character cast is deferred.
Duration: 30 seconds of authored presentation per route, plus player decision time.
Structure: 16-second shared opening + one 14-second ending. Total unique authored footage: 44 seconds, plus a reusable decision hold.

## Core fear
You remain conscious while something else takes control of your body. The entity asks permission to enter but never names what it wants to enter.

## Source and visual direction
Primary source: repository image #49:
`From Klickpin.com- Creepy Uncanny-board-image-49-pin-id-760686193359797836.jpg`

Preserve the bed-level viewpoint, warm light beyond the doorway, dark bedroom and pale smiling head. The entity's face remains consistent. No full-body reveal, exaggerated teeth, sudden charge or new creature. Its manner is gently patient, like somebody asking to borrow a chair.

One simple first-person hand insert is needed for Outcome A. No protagonist face or likeness is required. Any additional original visual media will be created in Higgsfield after script approval.

## Shared opening — 00:00 to 00:16

### 00:00–00:05
First-person view from bed. The bedroom is still.
The head is already peering around the doorway when the scene starts.
Quiet room tone and the protagonist's breathing.
The figure is watching the bed, not directly meeting the camera.

### 00:05–00:10
Its eyes settle on the camera.
From the hallway, softly and politely:
“Can I come in?”

No music cue. Hold long enough for the question to feel uncomfortably sincere.

### 00:10–00:16
The head advances only a few centimetres. The smile does not change.
It adds:
“I need you to say it.”

The protagonist takes a nervous breath. The figure's shoulders are not visible, so nothing confirms whether it is breathing.

## Decision — hold at 00:16
Two clearly readable options:
1. “Come in.”
2. “Stay outside.”

Hold on the approved still or a reviewed subtle idle loop. Room tone continues.
The authored timeline pauses while the player chooses. No invisible timer, automatic answer, microphone capture or real-name input.
The chosen line is spoken by the fictional protagonist, using a predetermined voice.

## Outcome A — “Come in.” — 00:16 to 00:30
Result: POSSESSED. The protagonist remains conscious; the entity controls the body.

### 00:16–00:20
The protagonist says, “Come in.”
The head slowly withdraws behind the doorframe.
No footsteps follow.
The bedroom remains visually empty.

### 00:20–00:26
The protagonist's right hand rises into the foreground and gives the empty doorway a small, relaxed wave.
The protagonist's frightened breathing catches.
The entity's voice is now close and dry, apparently coming from the protagonist's own mouth:
“You can watch.”

### 00:26–00:30
The hand settles back onto the blanket, unhurried.
The same voice finishes:
“Just don't speak.”

The protagonist tries to make a sound. Only a small breath escapes.
Cut to black while the entity takes one calm breath.

## Outcome B — “Stay outside.” — 00:16 to 00:30
Result: SELF-POSSESSED. The boundary holds. The entity remains outside; the protagonist must face the possibility of its return during sleep.

### 00:16–00:21
The protagonist says, “Stay outside.”
The head stops advancing.
Its smile remains exactly as it was.
A long, uncomfortable pause: it appears to accept the answer.

### 00:21–00:26
The head slowly retreats from view.
The warm hallway light switches off.
Nothing crosses the doorway.
The protagonist exhales in relief.

### 00:26–00:30
From the same place beyond the door, in that unchanged courteous voice:
“Then don't fall asleep.”

Hold on the empty black doorway.
Cut to black. The protagonist's breathing remains quick and awake.

## Why the choice matters
- A trades bodily agency for an apparent end to the encounter. The empty doorway becomes relief that the ending overturns.
- B successfully preserves agency and keeps the entity outside. The remaining fear is anticipation, not a hidden override of the player's refusal.
- Both outcomes share a location and entity, but establish different persistent story states.
- The opening question acquires a second meaning through Outcome A without requiring exposition.

## Minimal later implementation
Persistent branch value: `visitorState = "inside" | "outside"`.
Player input is locked as soon as a choice commits.
Play the selected response once and save the resulting branch at the ending checkpoint.
Real pause, settings and save controls remain reliable.

## Proposed Higgsfield shot breakdown — not submitted
- Shared opening: two short shots totalling 16 seconds, built from one approved room/face reference.
- Shared hold: one accepted still; an idle loop is optional.
- Outcome A: 4-second withdrawal, 6-second hand insert, 4-second final hold/dialogue.
- Outcome B: 5-second pause, 5-second withdrawal/light change, 4-second final hold/dialogue.
- Reuse the same withdrawal source if matching direction and timing make that viable.
- Dialogue and ambience remain separate from imagery for revision flexibility.
- Generate only constrained actions; timing may be set during editing. Review for identity drift and accidental camera movement.

## Sound direction
A single fixed entity voice, quiet and conversational.
Hallway dialogue is distant and lightly reverberant. Outcome A moves that voice to a close, dry, central position.
The protagonist's breath gives the last moments of the branches contrasting ownership.
No loud stinger is necessary.

## Approval boundary
Approve or revise this script before selecting final voices, quoting exact production jobs, generating images/video/audio, or building the playable scene.
The previously discussed 3,000-credit project ceiling remains in place. The first prototype's 150-credit allowance is a cap to assess with exact quotes, not a guarantee that every proposed shot and retake fits.
