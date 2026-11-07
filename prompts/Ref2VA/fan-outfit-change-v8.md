# Fan-Assisted Outfit Change: Ref2VA v8

- Status: user-confirmed usable in the source project; results are reference- and seed-dependent.
- Duration and format: 15 seconds, 9:16, 24 fps output (362 generated frames in the source workflow).
- References: five outfit/pose images; one motion video. The images define the woman, outfits, and room. The video defines the fixed overhead camera, roll timing, fan direction/speed, and cover moments. Its subject, clothes, and audio are excluded.
- Generation note: use a randomized seed and compare multiple samples; this prompt's precise timing is not guaranteed by the model.

Replace the five pictures and motion video with your own assets serving the same roles. Do not publish or assume the source assets are included.

```text
subject_definitions:
<Picture 1> anchors the opening frame: an adult woman in the first outfit on a sofa, a remote on the carpet, a ceiling fan near the top of frame, and a fixed straight-down overhead composition.
<Picture 2> anchors the first outfit on the carpet and the pose with the remote raised.
<Picture 3> anchors the second outfit and its pose on the carpet.
<Picture 4> anchors the third outfit and its pose on the carpet.
<Picture 5> anchors the fourth outfit, its pose, and any outfit-specific prop.
<Video 1> is the motion and timing reference: the fixed overhead camera, the roll from sofa to carpet, the fan direction and slow speed, and the moments when a blade covers the woman. The woman, outfits, and audio of <Video 1> are not used.
<Subject 1> is the same adult woman in all five pictures; her appearance comes from the pictures and her roll and lying rhythm come from <Video 1>. Preserve her face, slim tanned body, long legs, light makeup, small earrings, and long voluminous dark curly hair fanned out on the carpet. Calm face, lips closed, eyes up toward the camera; she does not smile.
<Subject 2> is the red one-piece mini dress: thin straps, V neckline, large round red paillette sequins, hem at upper thigh, black pointed heels.
<Subject 3> is the burgundy one-piece mini dress: thin straps, V neckline, large round burgundy paillette sequins, a short beaded fringe along the hem at upper thigh, black leather knee-high boots.
<Subject 4> is the dark chocolate-brown one-piece strapless mini dress: straight neckline, soft gathered waist, small dense brown sequins, hem at upper thigh, taupe suede slouch knee boots.
<Subject 5> is the black one-piece halter mini dress: thin halter straps, V neckline, black base with silver bead swirls and short silver bead fringe lines, sheer black hem at upper thigh, black patent pointed pumps.
<Subject 6> is the same room in every frame: seen straight down from the ceiling, a brushed-nickel three-blade ceiling fan at the top close to the camera, a long cream sofa along the left edge, a cream shag carpet, a strip of light wood floor at the very top, one soft window light patch at the upper right.
<Subject 7> is the fan motion from <Video 1>: completely still until she presses the remote at 00:03.5, then turning in the same direction and at the same slow speed as in <Video 1>, about one third of a turn every 3.75 seconds, starting directly at that slow speed with no fast spin-up. A blade fully covers her body only at 00:06, 00:09.75 and 00:13.5.

summary:
[reference generation] A 15-second, 9:16 overhead outfit-change video following the camera, roll, fan speed, and pacing of <Video 1>. <Subject 1> in <Subject 2> slides from the sofa onto the carpet, settles on her back, and presses the remote to switch on the fan. Each time a blade fully covers her, she is revealed in the next outfit: <Subject 3>, then <Subject 4>, then <Subject 5>. One continuous fixed shot.

retention_analysis:
<Picture 1> (00:00–00:01): fully_preserved - opening sofa position, first outfit, room, and composition.
<Picture 2> (00:02.5–00:06): fully_preserved - first outfit, lying position, and remote.
<Picture 3> (00:06–00:09.75): fully_preserved - second outfit and pose.
<Picture 4> (00:09.75–00:13.5): fully_preserved - third outfit and pose.
<Picture 5> (00:13.5–00:15): fully_preserved - fourth outfit, pose, and its prop.
<Video 1> (camera, roll, fan motion, pacing): partially_preserved - camera position, roll rhythm, fan direction and slow speed, and blade-cover timing; not its subject, outfits, or audio.
<Subject 1> (all frames): fully_preserved - one stable adult woman with consistent identity and appearance.
<Subject 2>–<Subject 5> (each outfit segment): fully_preserved - each complete outfit remains distinct and does not mix with another.
<Subject 6> (all frames): fully_preserved - fixed room layout and overhead composition.
<Subject 7> (00:00–00:15): fully_preserved - still until the remote press, then one direction at one slow speed, with three cover moments.

detailed_description:
Realistic phone footage, casual TikTok outfit-change video, photorealistic, natural skin texture, warm soft daylight, vertical 9:16. The ceiling camera never moves, as in <Video 1>. Fan blades are solid and sharply shaped, never merging with her body.
00:00–00:01: the fan is still. <Subject 1> in <Subject 2> lies on the sofa as in <Picture 1>, turns onto her side, and lets her legs and hips slide off the sofa edge first at the same relaxed pace as in <Video 1>.
00:01–00:01.5: her body follows down and she lands softly on the carpet on her side.
00:01.5–00:02.5: she rolls onto her back, settles her shoulders, hair fanned out, arms and legs placed as in <Picture 2>.
00:02.5–00:03.5: the fan is still. She picks up the remote, points it at the fan, and presses it once at 00:03.5.
00:03.5–00:06: the fan starts turning directly at the slow speed of <Video 1>, no fast spin-up. She lowers the remote and rests one hand on her stomach.
00:06: a blade moves over her and fully covers her body; exactly at that moment the dress changes, and as the blade moves on she is revealed in <Subject 3> as in <Picture 3>.
00:06.5–00:09.75: in <Subject 3>, she rests one hand on her collarbone, then slowly bends one knee and lowers it.
00:09.75: the next blade fully covers her; exactly then the dress changes, and she is revealed in <Subject 4> as in <Picture 4>.
00:10.25–00:13.5: in <Subject 4>, arms spread, she crosses her ankles, then turns her head slightly and back.
00:13.5: the next blade fully covers her; exactly then the dress changes, and she is revealed in <Subject 5> as in <Picture 5>, black bag beside her shoulder, remote gone.
00:14–00:15: she lies still, breathes and blinks once, mouth closed. The fan keeps the same slow speed.
The dress never changes while she is visible; it changes only while a blade fully covers her. Never a fade or blend. Each dress is one complete one-piece dress, never mixing colors, fringe, or shoes. No sparkle stars.
Avoid: fan moving before the press, fast spin-up, fan faster than in <Video 1>, more than three blade covers, dress changing while visible, direction changes, blur discs, a jumping roll, camera movement, zoom, cuts, outfits from <Video 1> such as the yellow top or camo pants, second person, distorted hands, morphing, text, logos, smiling, airbrushed skin.

overall_soundscape: N/A

non_diegetic_music: N/A
```

## Limits observed

The source project records this version as usable after the earlier v2/v3/v4/v7 attempts failed to hold fan speed and align outfit changes reliably. The v8 result was confirmed usable by the user, but its behavior depends on the reference video and generation run. Retest it with your own assets; the timestamps are not a hard frame-accurate guarantee.
