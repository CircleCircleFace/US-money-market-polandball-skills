---
name: finance-polandball-style
description: Apply the established classic Finance Polandball visual, dialogue, composition, and quality rules. Use when creating, editing, reviewing, or prompting a Finance Polandball comic, money-market explainer, character lineup, or related PNG illustration, especially when the user invokes Finance Poland ball style rules or asks for a Polandball-style financial explanation.
---

# Finance Polandball Style

Create financially clear comics that feel like old, handmade Polandball posts rather than polished modern illustrations.

## Visual References

When image inputs are supported, use the bundled files in `assets/` as style references:

- `classic-sparse-comic.png` for white space, sparse props, and panel pacing.
- `classic-expression-comic.png` for eye acting and rough hand-drawn construction.
- `classic-tutorial.png` for hard Polandball prohibitions and exceptions.
- `dialogue-font-anchor.png` for the required common dialogue typeface.

## Workflow

1. State the financial mechanism in one causal sentence before drawing.
2. Select only the actors needed. When canonical Finance characters are involved, also use `$finance-polandball-members` and follow its roster.
3. Write one story beat per panel. Give each beat a setup, emotional reaction, or punchline.
4. Draft dialogue before generating the image. Apply the dialogue rules below.
5. Use the `imagegen` skill for raster generation or editing.
6. Inspect the complete output for identity, text, layout, and every hard prohibition. Iterate on one targeted defect at a time.
7. Save the accepted image as PNG without overwriting an earlier version unless explicitly requested.

## Hard Visual Rules

- Give every Polandball absolutely no limbs: no arms, hands, fingers, legs, feet, or limb-like strokes. Props sit, lean, or float beside characters.
- Use rough old MS Paint pencil construction: thick uneven black outlines, lumpy silhouettes, imperfect panel borders, flat fills, and visibly hand-drawn geometry.
- Keep backgrounds almost entirely white. Include only props that carry the mechanism or joke.
- Never add cinematic scenery, detailed rooms, decorative clutter, gradients, shadows, reflections, glossy highlights, 3D volume, or polished textures.
- Use plain white eyes with rough black outlines and no pupils. Convey expression through eye shape, angle, spacing, and direction.
- Add no mouths, noses, hair, ears, moustaches, beards, eyelashes, or realistic anatomy.
- Use only minimal black-and-white stress marks or plain outline tears. Never use glossy blue sweat drops.
- Do not draw black divider lines between flag colors. Do not use perfect circle or line tools.
- Keep identity accessories only when they are established and necessary. Accessories never justify limbs.

## Dialogue Rules

Make every line clear enough to teach the key financial fact, but conversational and emotional enough to sound like characters talking.

- Prefer short reactions and spoken phrasing over textbook narration.
- Let character personality carry information: a rule-setting Fed may sound curt or smug; a rejected GSE may sound hurt; a bank seeing arbitrage may sound delighted; a scheming borrower may sound evasive.
- Use compact emotional words when natural, such as `Nooope`, `Sweet!`, `Deal!`, `Heh heh...`, or `Promise?`; vary them rather than repeating a stock phrase.
- Slight broken-English Polandball phrasing is welcome when still immediately understandable.
- Avoid obscure foreign-language fillers that do not match the speaker. Do not use `Da` for the Fed.
- Keep vocabulary simple and lines short enough to fit comfortably inside the panel.
- Do not print speaker labels or quotation marks. Point a crude speech-tail line toward the speaker.
- Avoid exposition such as `X is not eligible because...` when the same fact can be dramatized as `Nooope. You are out of my list.`
- Preserve exact financial labels such as `IORB`, `EFFR`, `ON RRP`, `SOFR`, `SRF`, and `FHLB`.
- Use captions only for compact anchors, definitions, or ironic asides that dialogue cannot carry cleanly.

## Typography Rules

- Use one dialogue typeface family throughout the entire comic. Never mix dialogue fonts between panels or speakers.
- Default to a plain compact bold sans-serif resembling Arial Bold or Helvetica Bold, matching `assets/dialogue-font-anchor.png` and the bundled classic comic references.
- Keep ordinary letter shapes, even stroke weight, zero decorative flair, and consistent width, x-height, and line spacing.
- Vary dialogue size only modestly when required for fit. Do not solve fit by switching to a narrow or condensed novelty face.
- Never use Comic Sans, rounded display fonts, serif fonts, polished comic-book lettering, or handwritten lettering for ordinary dialogue.
- Keep explanatory captions in the same sans-serif family, using regular or italic weight when needed.
- Allow hand lettering for a comic title or bonus-strip title only. Make it slightly uneven in baseline, letter height, and spacing, like mouse-written MS Paint text, while keeping it readable.
- Allow crude hand lettering on physical props and signs such as rate placards, boxes, or ledgers.
- Keep dialogue black on white and use simple speech-tail lines rather than polished speech bubbles.

## Character Acting

- Build emotion with eyes only. Happy eyes may be upward-curving white crescents; sad eyes may droop; refusal may be shown by looking away.
- Keep tears to one or two tiny black-outline droplets with white interiors.
- Show physical attitude by relative placement and eye direction, not limbs.
- In a joke about misconduct or diversion, use small scheming squint eyes and an understated aside rather than adding a mouth or villain props.

## Composition

- Prefer 2-4 main panels with rough dividers and large white margins.
- Use one clear causal step per panel.
- For a bonus strip, use one wide bottom rectangle with fewer and smaller characters than the main panels.
- Keep props diagrammatic: one cash stack, rate sign, ledger, box, note pile, or arrow is usually enough.
- Ensure all text stays within its panel and never overlaps characters, borders, or later dialogue.

## Finance Accuracy

- Keep humor subordinate to the causal mechanism.
- Distinguish an operational floor or soft ceiling from an absolute legal bound.
- Show eligibility restrictions explicitly when they create the spread or arbitrage.
- When a statement is time-sensitive or high stakes, verify it with primary official sources before drawing.

## Final Check

Reject or revise the image if any answer is yes:

- Does any ball have a limb or a mouth?
- Does a prop or accessory look like an extra eye or body part?
- Is the background richer than the joke requires?
- Does any dialogue read like a textbook sentence rather than speech?
- Is the emotional beat unclear from the eyes?
- Did a small character lose its eyes or identity markers?
- Do dialogue lines use more than one typeface family, width, or visual weight?
- Is a title too polished, or is ordinary dialogue too handwritten?
- Is any key financial label misspelled or any causal step misleading?
