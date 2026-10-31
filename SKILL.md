---
name: white-yellow-red-handdrawn-blackboard
description: "Apply a Traditional Chinese 16:9 presentation style with a deep green blackboard background, white primary linework, and yellow/red hand-drawn accents. Use when the user requests the 白黃紅手繪黑板風格 or this specific visual template; this skill supplies visual direction only, not article content or a fixed page count."
---

# 白黃紅手繪黑板風格

Use this skill as a style lock for a Traditional Chinese educational or explanatory presentation. It is derived only from the final hand-drawn green-background template; do not import the earlier JDN editorial, academic clean, Japanese picture-book, or other style systems.

## Reference example

- The canonical visual example is `examples/ChatGPT_chalkboard_reference.png`.
- Treat the example as a style reference only. Do not extract its words as source content and do not copy its page-specific composition when another layout better serves the source.
- The example demonstrates the target combination of deep green board, sparse chalk texture, white hand-drawn linework, rough white block lettering, and restrained yellow/red accents.

## Visual system

- Canvas: 16:9; for image-first production use 1920×1080.
- Background: deep forest green / chalkboard green with restrained paper, pencil, or crayon grain. Keep the field mostly flat and calm so text remains readable; white speckles and bright noise must be sparse.
- Linework: white is the primary hand-drawn line; yellow and red are reserved for small emphasis marks, outlines, arrows, underlines, warning marks, and limited fills. Use slightly uneven chalk/pencil strokes rather than polished vector geometry.
- Illustrations: simple symbolic scenes, gestures, objects, and diagrams. Prefer white/red/yellow line drawings with limited fill. Do not aim for photorealism or glossy cartoon rendering.
- Human figures: render the figure as a white chalk line drawing. Exposed skin areas—face, ears, neck, hands, and forearms—must remain the same deep green as the board, with no white or gray fill. Keep only a few minimal white interior strokes for facial features, fingers, and essential contours; avoid dense hatching or realistic shading. Hair, glasses, pen, clothing outlines, and a few key clothing folds may use white chalk strokes. Do not add a decorative horizontal baseline beneath the figure unless the user explicitly requests one.

## Typography and composition lock

- Traditional Chinese only unless the source requires otherwise. Preserve approved source strings exactly, including punctuation, slashes, symbols, and numeric expressions.
- Every visible text tier—title, subtitle, body row, label, metric, checklist item, caption, and note—must use the same rough, high-contrast hand-drawn chalk character as the reference title. Do not use a clean digital/UI font for body text while only the title is hand-drawn.
- Text must be high-resolution, crisp, and readable at 1920×1080. Keep the chalk texture inside the glyphs; do not scatter white dust, white dots, or chalk noise around the text.
- Use large white text as the default. Use yellow/red only for hierarchy and emphasis, never as a substitute for missing text contrast.
- Protect a clean text zone. Illustration strokes, arrows, film frames, characters, icons, and background motifs must not cross or visually compete with text.
- Use underlines as intentional hand-drawn hierarchy marks. Each underline must sit directly beneath its own heading or row, remain visually separate from glyphs, and never drift into an unrelated illustration or empty area.
- When a page has repeated rows, align the markers, text baselines, and underlines to one clear rhythm. Keep symbols and metrics in the same card or lane as their associated text.
- Page number: small hand-written white or yellow number at the bottom-right when page numbers are requested. Do not invent labels, facts, or decorative English text.

## Layout recipes

Choose the recipe that matches the requested content; do not force the source into a fixed page count.

- Cover / closing page: full-bleed hand-drawn scene with a protected title area and sparse text.
- Story map: central symbol with four directional concept nodes and hand-drawn connectors.
- Teaching/content page: title and concise text on the left, illustration or visual explanation on the right; use a triptych or process visual only when the content needs it.
- Summary page: two clear cards or a bridge/relationship diagram with generous spacing.
- Worksheet / exam page: readable cards, clean margins, and enough open space to write. In this template, each question keeps an outer border but the inside of the question box stays plain green—do not draw horizontal ruling lines inside it unless the user explicitly requests writing lines.
- Answer page: compact but legible answer list, with a small supporting visual kept away from the text.

## Image-generation direction

When generating backgrounds or illustrations, describe the scene, layout, and protected text zones explicitly. Use wording such as “deep green chalkboard background with very subtle dark texture and almost no white speckles, white primary hand-drawn chalk linework, sparse yellow and red accent strokes, exposed skin areas showing the green board through, minimal facial and finger strokes, no embedded text.” Keep generated imagery free of logos, watermarks, fake glyphs, random English, and unapproved labels; add exact Traditional Chinese text in the presentation layer when possible. For a full-page image slide, if text is generated in-image, repeat the typography lock above and inspect every string for fidelity.

## Quality gate

Before delivery, inspect representative pages and the final rendered output:

1. Confirm the green/white/yellow/red style is consistent across all pages and the board does not have excessive white speckles.
2. Confirm every approved Traditional Chinese string is legible, exact, high-resolution, and not covered by illustration.
3. Confirm every text tier uses the same hand-drawn chalk treatment; do not leave body text in a clean digital font.
4. Confirm chalk texture stays inside glyphs and there are no white dots or dust halos around text.
5. Confirm underlines and colored accents sit in the intended hierarchy position and do not cross text or collide with background art.
6. Confirm repeated rows, markers, metrics, cards, and lanes are aligned and have adequate breathing room.
7. Confirm human-figure skin is green negative space with only minimal interior chalk strokes; the main text and graphics remain primarily white.
8. Confirm worksheets and tests retain writing room; question boxes have no interior ruling by default.
9. Confirm there are no accidental style substitutions, random text, simplified Chinese, logos, watermarks, or invented source claims.
10. Confirm the requested output format, page count, and file set separately; this style skill does not silently change those requirements.

This skill is intentionally visual-only. For source extraction, page architecture, assessment design, or PDF/PPTX production, use the relevant document or presentation workflow in addition to this style lock.
