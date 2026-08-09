---
name: tnm-style-skill
description: Apply TNM visual style and vulgar straight-talk writing tone. Use when user asks for 新細明體, white background clean layout, black buttons, 髒話風格, 直球語氣, tnm style, or wants websites or text matching the FuckU series aesthetic without the original topic content.
---

# TNM Style Skill

Apply the pure visual and writing style extracted from TNM-related sites. No original topic data is included.

## When to use

- User requests 新細明體 / PMingLiU font
- White background + clean centered layout
- Black primary buttons + Discord-style secondary buttons
- 髒話直球語氣 / vulgar straight-talk tone
- Building pages that should feel like the TNM aesthetic

## Visual rules

1. Always use this font stack:
   ```css
   font-family: "PMingLiU", "新細明體", "MingLiU", "Microsoft JhengHei", serif;
   ```
2. Background must be pure white `#ffffff`.
3. Primary buttons are black (`#111`) with white text, small border-radius (6px).
4. Use `.rant` blocks (left black border + light gray background) for strong statements.
5. Use `.tag` for short characteristic labels.
6. Keep layout centered, max-width around 520–680px, generous line-height (1.6–1.7).

Full CSS is in `assets/tnm-style.css`. Copy or link it when generating HTML.

## Writing tone rules

- Be direct. No soft hedging.
- Use 髒話 as seasoning to increase emotional honesty, not as filler.
- Prefer short, punchy sentences.
- Call things what they are. If something is annoying, say it is 真的有夠煩 or 幹你娘真的煩.
- Reference `references/swear-library.md` for intensity levels and examples.
- Reference `references/style-guide.md` for colors, spacing, and component details.

## Output checklist

When generating a page or component under this skill:

- [ ] Font stack includes PMingLiU / 新細明體
- [ ] White background
- [ ] Black primary button style
- [ ] Clean section structure with optional rant/tag elements
- [ ] Tone is straight and can include 髒話 when appropriate
- [ ] No leftover topic-specific names or definitions from filtered sources
