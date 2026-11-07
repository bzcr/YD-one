# Ref2VA Prompt Template

Replace every bracketed placeholder and remove any instruction that does not apply. Keep the six sections in order.

```text
subject_definitions:
<Picture 1> defines [identity/product/scene/style truth] for [the applicable subject or shots].
<Video 1> provides [motion/camera/timing reference]. It does not provide [elements that must not transfer].
<Subject 1> is [stable identity and visible attributes].

summary:
[One concise sentence identifying reference generation or editing, duration, aspect ratio, main action, and ending state.]

retention_analysis:
<Picture 1> ([time or shots]): [fully_preserved / partially_preserved] - [specific elements].
<Video 1> ([time or shots]): [fully_preserved / partially_preserved] - [specific elements and exclusions].
<Subject 1> ([time or shots]): [identity and continuity requirements].

detailed_description:
[Style, aspect ratio, and global camera constraints.]
[00:00–00:XX]: [framing, subject position, action, expression, camera, lighting, and active references].
[00:XX–end]: [next visible state, action, camera, lighting, and active references].
Avoid: [short list of likely failure modes and prohibited transitions].

overall_soundscape: [sound design, or N/A only when fully silent]

non_diegetic_music: [music, or N/A]
```

Do not leave placeholder labels unresolved in a final prompt. Verify exact field requirements against the official MiniMax H3 documentation.
