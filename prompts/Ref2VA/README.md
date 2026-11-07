# Ref2VA: Reference-Guided Video Prompts

Use Ref2VA when images, video, or audio provide identity, product, scene, style, motion, camera, editing, or sound references, but are not required to act as an exact first or last frame. Use another H3 mode when an exact keyframe is required.

## Six-section structure

Write the sections in this order:

1. `subject_definitions`
2. `summary`
3. `retention_analysis`
4. `detailed_description`
5. `overall_soundscape`
6. `non_diegetic_music`

Consult the [official MiniMax H3 documentation](https://github.com/MiniMax-AI/MiniMax-H3) for current syntax and constraints.

## Reference responsibilities

- Assign each reference one primary job, such as identity, garment/product truth, room layout, motion, camera path, or sound.
- State what must be preserved and what must not transfer. For example, a motion reference may provide timing and camera movement without transferring its subject or clothing.
- Keep reference labels consistent across all sections.
- Describe the visible timeline shot by shot: framing, subject position, action, expression, camera, light, and when each reference applies.
- Treat timestamps as pacing guidance unless a sample confirms tighter timing control.

## Preflight checks

- Confirm the mode matches the assets' actual roles.
- Check all six sections and their order.
- Check reference labels, duration, timeline coverage, and sound fields.
- Avoid conflicting demands, such as complex camera movement plus exact background preservation.
- Generate a sample and record both successes and failures before calling a prompt verified.

## Blank template

See [template.md](template.md).

## Example

[Fan-assisted outfit change, v8](fan-outfit-change-v8.md) is a user-confirmed usable example. It depends on the listed reference assets and is not a guarantee of identical results elsewhere.
