# KNOT Visual Asset Pack — Batch 2

## Contents
- `individual_emojis/`: 12 isolated PNG crops from the transparent icon atlas; use as floating decorative elements. Crops are from generated art, not manually traced vectors; some edges may need refinement.
- `visual_boards/`: seven full-size visual reference boards, including branding, iconography, animation, palettes and website applications. These boards are references and are *not* directly editable UI components.

## Where to use
- Hero: one or two oversized chrome objects (sparkle, paper airplane, camera) positioned around — not over — the primary goal input.
- Profile cards / goal categories: small chrome camera, headphones, palette, basketball, laptop and puzzle icon; if 24px or smaller, swap for a simple flat SVG.
- Discovery and group flows: decorative puzzle and heart-chat; show teal ONLY after match/group confirmation.
- Avoid saturating every section with chrome; 1–3 floating icons in a major section are enough.

## Exact palette
- Warm paper #F7F4ED — page canvas
- Ink #211E28 — typography and outlines
- Thread violet #5938B5 — active/connect primary action
- Deep teal #176457 — confirmed match / group formed
- Ochre #805400 — needs review or warning
- Brick #A3323D — destructive/error state

## Visual and motion notes
- Prefer polished, stylized liquid-chrome silver with violet reflective highlights, not rope fibers, scratched metal, gritty photorealism, or neon sci-fi.
- Float individual emoji icons at low amplitude with gentle parallax; honor prefers-reduced-motion.
- Do NOT use these static sheets to simulate interactive knot physics. Rebuild the knot as independently movable strands (WebGL/SVG/3D), then animate untying when clicked or dragged.
- Keep text as HTML, not baked into art.
