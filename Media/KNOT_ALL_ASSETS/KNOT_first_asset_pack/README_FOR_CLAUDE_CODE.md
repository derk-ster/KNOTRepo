# KNOT — First Visual Asset Pack

Original images, concept crops, one preview animation, and a simplified transparent SVG mark. This is a **visual concept pack**, not final editable 3D geometry or production animation source. The original generated boards may have small lettering inaccuracies; overlay all live website text in HTML/CSS.

## Art direction
- Reference form: recognizable overhand knot, similar to the submitted rope image.
- Material: brushed silver/chrome with narrow violet reflections; premium but approachable, not sci-fi neon.
- Primary background: **paper `#F7F4ED`**.
- Main UI text: **ink `#211E28`**.
- Interactive thread, primary CTA, potential connections: **violet `#5938B5`**.
- Confirmed, successfully formed group: **teal `#176457`**.
- Needs review: **ochre `#805400`**; only when caution is warranted.
- Error: **brick `#A3323D`**; only actual failures.
- Chrome is an *asset material*, not an extra semantic UI color.

## Files
- `01_brand_identity_board.png` — strong primary identity / brand board.
- `02_logo_variations.png` — different symbol and lockup options, visual reference.
- `03_brand_applications.png` — proposed app icons and scale treatments.
- `04_knot_states_color_system.png` — different knot states / semantic variations; the background is not guaranteed transparent.
- `05_six_frame_untie_storyboard.png` — loose-to-separated reference.
- `06_five_frame_motion_palette.png` — alternate step timing reference.
- `07_untie_motion_preview.gif` — 12 frames / 120ms per frame (~1.44s), automatically loops; motion reference, not interactive.
- `08_logo_lockup_concept.png` — cropped example logo; cream backdrop, not transparent.
- `09_app_icon_dark_concept.png` / `10_app_icon_light_concept.png` — cropped concept tiles; not suitable as accessibility labels.
- `11_metallic_hero_knot.png` — wide knot hero decoration; don't place input text inside the raster.
- `12_simple_transparent_knot.svg` — lightweight vector companion, simplified; ideal for replacing with a production SVG if visual style is approved.

## Suggested website behavior for Claude Code
1. Hero: large KNOT heading and editable text goal input anchored in the open center or beneath a decorative knot; keep the input visible. Use generated hero image as art only, not as UI.
2. Knot interaction: when pointer or touch drags either end, control a *real scene state* `t` from 0 (fully tied) to 1 (separated). Animate two vector paths/3D curves and their over-under ordering; don't stretch a single bitmap, and don't use the GIF as the interactive object.
3. On release: if drag passes a threshold, finish untying; reveal compatible-person cards with a gentle stagger. Otherwise spring back. Provide click/tap 'Untie' equivalent for keyboard and touch users.
4. On group creation: reverse the strands into a knot in ~700–1100ms, then change accent from violet to teal **only after success**; brief soft reflection sweep, not a bright explosion.
5. Respect `prefers-reduced-motion`, 60fps goal on ordinary laptops, and use progressive enhancement. Load the main form without awaiting WebGL/large art.
6. Demo sequence: user types a filmmaking goal, receives explainable complementary matches, creates group chat, and sees assistant first-step suggestions. Keep demo names/avatars fictional and interface text editable.

## Important production notes
This asset pack is a starting reference. Generated raster boards and GIFs cannot supply manipulable strand geometry. For the actual interaction, create authored SVG paths, Canvas animation, or 3D mesh curves in the website implementation. Don't claim the GIF is interactive.
