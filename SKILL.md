---
name: white-yellow-red-handdrawn-blackboard
description: "Apply a Traditional Chinese 16:9 presentation style with a deep green blackboard background, white primary linework, and yellow/red hand-drawn accents. Use when the user requests the 白黃紅手繪黑板風格 or this specific visual template; before generation, confirm the page count, obtain approval for the page-by-page outline, and get approval on one sample page before batch generation. This skill supplies visual direction only, not article content or a fixed page count."
---

# 白黃紅手繪黑板風格

Use this skill as a style lock for a Traditional Chinese educational or explanatory presentation. It is derived only from the final hand-drawn green-background template; do not import the earlier JDN editorial, academic clean, Japanese picture-book, or other style systems.

## 生成前核准流程

這是生成前的必要閘門，不得跳過：

1. 在開始任何圖片、投影片背景、簡報頁面或其他成品生成前，先向使用者確認要產生的頁數；不得自行猜測、沿用來源頁數或以固定頁數代替。若使用者已提供頁數，也要明確覆述並請使用者確認。
2. 依確認的頁數提出逐頁大綱供核准。每頁至少列出：頁碼、頁面標題、教學／敘事功能、預計放置的核准文字重點，以及符合本風格的插畫或版面方向。大綱階段只規劃，不生成圖片或簡報。
3. 必須取得使用者對每一頁大綱的明確核准後，才可進入生成階段。未核准的頁面不得先做背景、插畫、排版或批次生成；若使用者只核准部分頁面，僅可繼續處理已核准頁面，除非使用者要求等待全部核准。
4. 大綱核准後，先只生成一頁樣張；預設使用第 1 頁，除非使用者指定其他代表頁。樣張必須完整呈現該頁的文字層級、版面、插畫比例、色彩與粉筆質感，然後停下來請使用者確認風格與版型。未取得樣張明確核准前，不得批次生成其餘頁面。
5. 使用者對樣張提出修改時，先修改並重新生成樣張，再次取得明確核准後才能繼續。樣張核准後，將其視為全套頁面的視覺基準；若後續頁面需要改變整體字體、構圖語言、插畫比例或色彩規則，先停下來請使用者重新核准。
6. 使用者提出頁面內容修改時，先更新受影響頁面的大綱並再次請核准；核准後的頁數、頁序、標題、文字重點與頁面功能視為製作鎖定內容。生成過程中若發現必須改動這些項目，先停下來請使用者重新核准。

這項流程只控制製作時序與使用者核准，不限制使用者自行指定的輸出格式、素材來源或後續修改方式。

## Reference example

- The canonical visual example is `examples/ChatGPT_chalkboard_reference.png`.
- Inspect the canonical image before creating a sample or presentation. It is a binding visual reference for character treatment, line density, chalk texture, typography, and color hierarchy, not merely a palette reference.
- Do not extract the example's words as source content. New page composition may change when the source content requires it, but the resulting work must preserve the example's visual grammar and production quality.
- Do not replace the reference's detailed human chalk portraits with simplified round-head icons, generic cartoon figures, stick figures, or sparse symbol-only characters when people are requested.
- The example demonstrates the target combination of textured deep-green board, detailed white chalk portrait and object linework, green negative-space skin, broad slightly irregular hand-drawn white chalk lettering with broken scrape marks inside the glyphs, and restrained yellow/red hand-drawn accents.

## Visual system

- Canvas: 16:9; for image-first production use 1920×1080.
- Background: deep forest green / chalkboard green with the visible but restrained paper, pencil, or crayon grain shown in the reference. Keep the central text field calmer than the edges; white speckles and bright noise must be sparse.
- Linework: white is the primary hand-drawn line. Match the reference's layered, slightly uneven chalk/pencil strokes, contour variation, small scratch marks, and selective hatching. Yellow and red are reserved for small emphasis marks, outlines, arrows, underlines, warning marks, and limited fills. Do not use polished vector geometry as the dominant visual language.
- Illustrations: use detailed chalk line drawings for people, objects, and explanatory scenes. Symbolic diagrams are allowed, but they must still carry the reference's chalk texture and line density. Do not substitute glossy cartoon rendering, flat UI icons, or low-detail pictograms for the reference style.
- Illustration-area limit: the combined visual area of concrete background illustrations—people, objects, scene linework, film frames, and process drawings—must not exceed one third of the page. Treat separated illustration fragments as one combined total; do not bypass the limit by scattering many small drawings. The remaining area must protect the text-safe zone and readable instructional content. The full-page blackboard texture is not counted as an illustration.
- Human figures: when people appear, use the reference's expressive adult half-body / portrait-like chalk vocabulary with readable hair, facial contour, clothing, gesture, and selective interior hatching. Exposed skin areas—face, ears, neck, hands, and forearms—must remain the same deep green as the board, with no white or gray fill, no bright white facial planes, and no saturated white facial mass. Treat the face as green negative space: keep only a few low-density white contour strokes for the eyebrows, eyes, nose, mouth, jaw, fingers, and essential joints. Reserve denser hatching for hair, clothing, props, and non-skin areas. Do not add a decorative horizontal baseline beneath the figure unless the user explicitly requests one.

## Typography and composition lock

- Traditional Chinese only unless the source requires otherwise. Preserve approved source strings exactly, including punctuation, slashes, symbols, and numeric expressions.
- Every visible text tier—title, subtitle, body row, label, metric, checklist item, caption, and note—must use the same broad, slightly irregular, hand-drawn white chalk lettering as the reference. The strokes should feel manually written and chalk-drawn, with uneven edges and broken scrape / grain marks inside the glyphs. Do not use a clean digital/UI font for body text while only the title is hand-drawn. Do not use a thin calligraphic, book-style, rigid geometric, or generic digital font as a substitute.
- Main headings should have the reference's heavier stroke weight, irregular hand-drawn edges, and restrained broken interior chalk marks. They may be larger and heavier than body text, but must not become a perfectly regular square block font. Smaller text must remain in the same chalk family and may use lighter texture only when necessary for readability.
- Accurate Chinese description of the reference lettering: 「粗筆畫、略帶不規則手寫感的白色粉筆字；字內保留斷續刮擦與細微顆粒紋理；大標筆畫較厚，但不是規整的幾何方塊黑體。」
- Genuine human-handwritten stroke: every visible text tier must carry natural variation in chalk pressure, stroke width, turns, spacing, tilt, and baseline, as if written by a person with a thick piece of chalk. Preserve legibility; do not imitate handwriting only by applying a digital-font filter or random warping. Avoid thin calligraphy, printed book type, and rigid geometric regularity.
- Baseline and tracking lock: within each page, keep each text tier's left anchor, baseline, line spacing, and reading rhythm stable. Confine human variation to individual chalk strokes and interior texture; do not introduce random whole-line displacement or floating text. Use slightly lighter solid strokes for body text when needed, never hollow gray outlines.
- Text must be high-resolution, crisp, and readable at 1920×1080. Keep the chalk texture inside the glyphs; do not scatter white dust, white dots, or chalk noise around the text.
- Use large white text as the default. Use yellow/red only for hierarchy and emphasis, never as a substitute for missing text contrast.
- Protect a clean text zone. Illustration strokes, arrows, film frames, characters, icons, and background motifs must not cross or visually compete with text.
- Page-layout order: every page first establishes a protected text-safe zone, then places chalk icons and process diagrams around it. 每頁會先排文字安全區，再配置粉筆圖示與流程圖，避免插畫穿字或留下過多空白。
- Illustration placement: keep the total background-illustration footprint within one third of the page, preferably in a single side or lower-corner cluster; never enlarge an illustration until it competes with the title, body text, or safe zone.
- Final production lock: all visible text must use genuine human-handwritten white chalk strokes; every page must establish the protected text-safe zone first, then place a single-side or lower-corner concrete illustration cluster whose combined footprint is no more than one third of the page. Illustration strokes must never cross, cover, or visually compete with text.
- Use underlines as intentional hand-drawn hierarchy marks. Each underline must sit directly beneath its own heading or row, remain visually separate from glyphs, and never drift into an unrelated illustration or empty area.
- When a page has repeated rows, align the markers, text baselines, and underlines to one clear rhythm. Keep symbols and metrics in the same card or lane as their associated text.
- Page number: small hand-written white or yellow number at the bottom-right when page numbers are requested. Do not invent labels, facts, or decorative English text.

## Layout recipes

Choose the recipe that matches the requested content; do not force the source into a fixed page count.

- Cover / closing page: deep-green textured board with a hand-drawn illustration cluster limited to one third of the page, plus a dominant protected title area and sparse text.
- Story map: central symbol with four directional concept nodes and hand-drawn connectors.
- Teaching/content page: title and concise text on the left, illustration or visual explanation on the right; use a triptych or process visual only when the content needs it.
- Summary page: two clear cards or a bridge/relationship diagram with generous spacing.
- Worksheet / exam page: readable cards, clean margins, and enough open space to write. In this template, each question keeps an outer border but the inside of the question box stays plain green—do not draw horizontal ruling lines inside it unless the user explicitly requests writing lines.
- Answer page: compact but legible answer list, with a small supporting visual kept away from the text.

## Image-generation direction

When generating backgrounds or illustrations, use the canonical reference image as a visual reference whenever the tool supports reference images. Describe the scene, layout, and protected text zones explicitly. For people, explicitly state that white facial saturation is removed: faces, ears, necks, hands, and forearms remain deep green negative space with only minimal low-density white contour strokes; white chalk density belongs in hair, clothing, props, and objects, not in facial planes. Use wording such as “match the supplied chalkboard reference's detailed adult chalk portraits, deep green textured board, green negative-space skin, layered white contour and hatch strokes in hair/clothing/objects, broad slightly irregular hand-drawn white chalk lettering with broken interior scrape marks, sparse yellow and red accents, and a clean central text zone.” Keep generated imagery free of logos, watermarks, fake glyphs, random English, and unapproved labels; add exact Traditional Chinese text in the presentation layer whenever possible.
- For image-first pages, prefer generating the detailed illustration/background without embedded text, then add exact Traditional Chinese strings in the presentation layer. Do not accept a result merely because it has the right green color: reject and regenerate outputs that use simplified icon characters, flat vector figures, clean sans-serif title lettering, filled skin, excessive white speckles, or weak chalk texture.
- If a user supplies a copy of the canonical reference image, treat it as the same visual reference only after inspecting it; do not treat any words visible in the reference as source content.

## Quality gate

Before delivery, inspect representative pages and the final rendered output:

1. Compare representative pages against the canonical reference for overall visual grammar: textured deep-green board, detailed chalk linework, character detail, green negative-space skin, rough block-chalk text, and restrained accents. Confirm the green/white/yellow/red style is consistent across all pages and the board does not have excessive white speckles.
2. Confirm every approved Traditional Chinese string is legible, exact, high-resolution, and not covered by illustration.
3. Confirm every text tier uses the same hand-drawn chalk treatment; do not leave body text in a clean digital font.
4. Confirm chalk texture stays inside glyphs and there are no white dots or dust halos around text.
5. Confirm underlines and colored accents sit in the intended hierarchy position and do not cross text or collide with background art.
6. Confirm repeated rows, markers, metrics, cards, and lanes are aligned and have adequate breathing room.
7. Confirm human figures use the reference's detailed chalk portrait / gesture language rather than simplified icons; confirm exposed skin is green negative space with no bright white facial planes, no saturated white facial mass, and only minimal low-density contour strokes, while hair, clothing, and props may carry selective chalk hatching.
8. Confirm each page establishes the text-safe zone before placing chalk icons or process diagrams; confirm illustrations do not cross text and the page does not leave excessive empty space without a purposeful visual role.
9. Measure the combined footprint of concrete background illustrations on every page; confirm it is no more than one third of the page, excluding only the full-page blackboard texture.
10. Confirm worksheets and tests retain writing room; question boxes have no interior ruling by default.
11. Confirm there are no accidental style substitutions, random text, simplified Chinese, logos, watermarks, or invented source claims.
12. Confirm the requested output format, page count, and file set separately; this style skill does not silently change those requirements.

This skill is intentionally visual-only. For source extraction, page architecture, assessment design, or PDF/PPTX production, use the relevant document or presentation workflow in addition to this style lock.

