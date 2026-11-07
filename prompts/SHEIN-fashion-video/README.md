# SHEIN Fashion-Video Prompts

Prompts for product-led ecommerce fashion video. The goal is clear product inspection, not literal imitation of a reference clip.

## Workflow

1. Map the garment's customer-relevant selling points.
2. Assign product images to identity, garment details, front view, and back view.
3. Use a motion reference only for the intended camera, pacing, shot order, and performance; explicitly exclude its person, clothing, background, text, and audio when they must not transfer.
4. Give each shot one primary product point and at most one main subject action or camera move.
5. Test shot order and garment consistency at a lower resolution first, then test delivery-level clarity separately.
6. Record observed results and timing drift. Do not treat prompt timestamps as frame-accurate edit points without sample evidence.

## Example and review

- [Black lace gown v3 prompt](black-lace-gown-v3-partial.md): partially validated; source video and private workflow are not included.
- [Text-only sample review](../../cases/SHEIN-fashion-video/black-lace-gown-v3-review.md): summarizes what worked, what remained weak, and why the sample is not final delivery quality.
