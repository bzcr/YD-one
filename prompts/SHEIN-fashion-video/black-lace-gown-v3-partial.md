# H3 Ref2VA | SHEIN Black Lace Gown, 15s, Four Images + Motion Reference, v3

## 工作流设置

- Mode: Ref2VA, four image references plus one motion reference.
- `Float (Duration)`：15
- H3长度由公式自动计算为362帧；当前一小时内安全档将参考视频读取上限固定为288帧（前12秒、24fps）
- 画幅：3:4
- 音频：忽略
- Status: partially validated. A 15.083-second, 640x832, 3:4, 24fps silent sample confirmed the five-shot order, removal of the crossed-arm gesture, front-view pullback, and hard cut to the back view. The approach in Shot 1 and lateral slide in Shot 2 were weak; the back view appeared about 1.17 seconds early. The 0.53MP sample is for structural testing only.

```text
subject_definitions:
<Picture 1> anchors [Shot 1] and [Shot 4], defining the exact woman, front dress, handbag, accessories, tattoo, terrace, daylight, perspective, and full-body composition.
<Picture 2> anchors [Shot 2], defining the halter neckline, floral lace, nude lining, fitted waist and hips, black skirt transition, bracelets, and handbag chain.
<Picture 3> anchors [Shot 3], defining the face, dark center-parted updo, makeup, earrings, gaze, neckline, and upper lace; both forearms stay below the target crop.
<Picture 4> anchors [Shot 5], defining the open back, rear lace and ruching, hip fit, rear skirt, handbag pose, over-shoulder angle, terrace, daylight, and final composition.
<Subject 1> is the same adult woman across <Picture 1>, <Picture 3>, and <Picture 4>. Preserve her identity, face, complexion, hairstyle, makeup, body proportions, and poised presence.
<Subject 2> is the same black floor-length gown across all pictures. Preserve its floral lace over nude lining, halter neckline, fitted front, low open back, rear ruching, black skirt, flared hem, seams, and pattern scale.
<Subject 3> is the same terrace: stone column, dark wood, glass doors, concrete floor, tropical planters, structures, perspective, and daylight direction.
<Subject 4> is the same brown shell handbag, chain, earrings, bracelets, rings, and tattoo. Preserve their scale, placement, and attachment in each referenced view.
<Video 1> provides only the restrained approach, cut rhythm, detail timing, eye and chin performance, framing progression, and camera pace. Do not transfer its person, navy dress, studio, shadow, text, audio, or arm-crossing gesture.

summary:
[reference generation] A 15-second, 3:4 realistic ecommerce fashion video shows <Subject 1> modeling <Subject 2> in <Subject 3>. Pictures 1–4 respectively anchor the front full-body, garment detail, unobstructed portrait, and separate back-view ending; <Video 1> supplies only pacing, cuts, expressions, framing, and camera behavior.

retention_analysis:
<Picture 1> ([Shot 1], [Shot 4]): fully_preserved - retain its front identity, dress, accessories, terrace, light, perspective, and composition.
<Picture 2> ([Shot 2]): fully_preserved - retain its neckline, lace, lining, waist, hips, bracelets, and chain.
<Picture 3> ([Shot 3]): fully_preserved - retain its face, hair, makeup, neckline, and lace; hands and forearms stay outside the crop.
<Picture 4> ([Shot 5]): fully_preserved - retain its open back, rear construction, skirt, handbag pose, over-shoulder look, terrace, and composition.
<Subject 1> (all shots): fully_preserved - one stable woman, face, body, and hairstyle.
<Subject 2> (all shots): fully_preserved - one unchanged dress with stable front, back, lace, lining, fit, material, and hem.
<Subject 3> (all shots): fully_preserved - stable terrace geometry, plants, perspective, and light; no studio from <Video 1>.
<Subject 4> (applicable shots): fully_preserved - one handbag and accessory set without duplication; [Shot 5] directly follows <Picture 4> without a hand change.
<Video 1> (pacing, cuts, expressions, framing, camera): partially_preserved - retain its display grammar, excluding arm motion, source appearance, text, and audio.

detailed_description:
Clean live-action premium ecommerce fashion cinematography, vertical 3:4, with stable identity, readable black lace, natural skin, smooth highlights, clean shadows, realistic 24fps motion, and no noise, flicker, text, logo, price, watermark, collage, or duplicate person. Preserve the pictured woman, dress, accessories, terrace, plants, perspective, and warm daylight.

[Shot 1] Begin from <Picture 1>. <Subject 1> stands slightly right of center in <Subject 3>, wearing <Subject 2> and holding the handbag low beside her thigh. The camera is locked. After a brief hold, she shifts weight and takes one small step toward the camera. Her free hand stays near her hip; her gaze moves from screen-right closer to the lens after one blink. The hem glides over the floor; skirt, handbag, and chain follow with slight delay and settle. Her lips stay closed and expression calm.

[Shot 2] At 00:03.200, hard cut to the neck-to-hip framing of <Picture 2>. Keep the neckline, lace, lining, waist, hips, skirt transition, bracelets, and chain visible. The camera makes a clearly visible smooth short lateral slide while keeping the bodice and waist centered. A minimal shoulder and waist adjustment moves daylight across the lace; pattern, lining, hands, and chain stay stable.

[Shot 3] At 00:04.500, hard cut to a head-to-bust portrait based on <Picture 3>. Both arms stay lowered outside the bottom edge; no hand or forearm enters the lace area. Reference only <Video 1>'s eye, blink, chin, expression, and camera timing. She looks screen-left, shifts her eyes near the lens, blinks once, and lifts her chin slightly. Shoulders stay still, mouth closed, and the camera makes a minimal slow push-in.

[Shot 4] At 00:06.000, hard cut to a centered waist-up front shot based on <Picture 1>. A steady visible zoom out reaches a complete head-to-hem view by 00:09.500. She keeps the handbag low, adjusts her free hand near her hip without covering the bodice, and shifts weight onto one leg. The dress responds naturally without redesign. Hold the full front silhouette until 00:11.500 with only a slight head turn and breathing.

[Shot 5] At 00:11.500, hard cut to <Picture 4>'s back full-body composition. Do not show a turn or handbag hand change. Preserve the open back, rear lace and ruching, hip fit, skirt, handbag pose, terrace, plants, perspective, and daylight. She shifts weight slightly, keeps her torso away, looks back over her shoulder, blinks once, and holds. A minimal slow pullback settles on the complete back view through the final frame.

Maintain one woman, one dress, one handbag, and one environment. Avoid arm crossing, extra limbs or fingers, chain disconnection, handbag duplication, lace flicker, lining drift, fabric melting, identity drift, background warping, plant motion, lighting changes, and cross-shot garment redesign.

overall_soundscape:
N/A

non_diegetic_music:
N/A
```

## 本版最少修改

1. 保持V2已验证成功的3.2/4.5/6.0/11.5秒切点和背面硬切。
2. Shot 3用正向构图排除抱臂，并声明Video 1不提供手臂动作。
3. 增强Shot 2横移、Shot 4拉远和Shot 1一步走近。

## 样片验证结果

- The source sample and source review are not included in this public repository; see the text-only review in `cases/SHEIN-fashion-video/`.
- 已验证：人物/服装/背景保持、五镜头顺序、Shot 3 去抱臂、Shot 4 拉远、Picture 4 背面硬切。
- 未充分验证：Shot 1 一小步走近、Shot 2 可见横向视差、11.50 秒精确背面切点、0.9MP 以上最终交付清晰度。
