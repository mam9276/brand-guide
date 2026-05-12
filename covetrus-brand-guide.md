# Covetrus Brand Guide
> This file is designed to be used as a reference for AI tools (Claude, Copilot, etc.), developers, designers, and anyone creating Covetrus-branded content. Attach it to a Claude Project, paste it into a system prompt, or reference it in any AI tool to ensure brand-consistent outputs.

---

## 1. Brand Identity

**Company Name:** Covetrus  
**Industry:** Veterinary health technology and services  
**Mission:** To advance the world of veterinary medicine by empowering practitioners with the technology, products, and solutions they need to thrive.  
**Tone:** Professional, trustworthy, forward-thinking, warm, and science-backed. Covetrus speaks with confidence but never arrogance. We are a partner to veterinary professionals, not a vendor.

---

## 2. Logo

### Logo Variants
| Variant | File | Usage |
|---|---|---|
| Full Wordmark – RGB | `Covetrus_RGB.svg` | Primary use on white/light backgrounds |
| Full Wordmark – Knockout (KO) | `Covetrus_RGB_KO.svg` | Use on dark or colored backgrounds |
| Full Wordmark – Black | `Covetrus_Black.svg` | Single-color print, dark backgrounds not available |
| Full Wordmark – White | `Covetrus_White.svg` | Use on dark backgrounds, single-color white contexts |
| Icon/Bug – RGB | `Covetrus_Bug_RGB.svg` | Small spaces, app icons, favicons, social avatars |
| Icon/Bug – Knockout (KO) | `Covetrus_Bug_RGB_KO.svg` | Icon use on dark backgrounds |

### Logo Rules
- **Do not** recolor, distort, rotate, or recreate the logo in any way.
- **Do not** place the RGB logo on dark or busy backgrounds — use the KO (knockout) version instead.
- **Do not** use the wordmark at sizes smaller than 120px wide in digital contexts.
- **Do not** add drop shadows, outlines, or effects to the logo.
- Always maintain clear space around the logo equal to the height of the "C" in "Covetrus" on all sides.
- The icon/bug may be used independently of the wordmark only in contexts where the Covetrus brand is already established (e.g., within a product UI, social media profile picture).

---

## 3. Color Palette

### Primary Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Vet Blue | `#021660` | rgb(2, 22, 96) | Primary brand color. Use for headings, primary text, buttons, nav, and dominant UI elements. |
| Care Red | `#ED3030` | rgb(237, 48, 48) | Use for alerts, badges, emphasis, and energy/urgency. |
| Tech Teal | `#27BDBE` | rgb(39, 189, 190) | Use for highlights, links, CTAs, icons, and progress indicators. |
| White | `#FFFFFF` | rgb(255, 255, 255) | Primary background. |

### Accent Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Action Blue | `#0055E7` | rgb(0, 85, 231) | Interactive accent. Use for links, hover states, and digital call-to-action elements. |
| Medium Blue | `#75C1FF` | rgb(117, 193, 255) | Secondary blue accent. Use for icons, highlights, and supporting UI elements. |
| Greatpet Green | `#008556` | rgb(0, 133, 86) | Brand extension accent. Use for Greatpet-related content, success states, and positive indicators. |

### Neutral Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Near Black | `#191919` | rgb(25, 25, 25) | Body text on light backgrounds, black logo variant. |
| Light Gray | `#F7F7F7` | — | Page backgrounds, card surfaces, section dividers. |
| Mid Gray | `#6B7280` | — | Secondary/supporting text, placeholders, disabled states. |

### Color Usage Rules
- **Vet Blue** should be the dominant color in any layout. It conveys trust and authority.
- **Tech Teal** is the primary action color. Use it for buttons, links, and interactive highlights.
- **Care Red** is an accent only — never use it as a background color or for large areas.
- **Action Blue** is for digital-first contexts — links, hover states, and interactive UI elements.
- **Greatpet Green** is reserved for Greatpet brand contexts and positive/success states.
- Never use Care Red and Tech Teal together without Vet Blue as a mediating color.
- Ensure all text meets WCAG AA contrast ratios (4.5:1 for body text, 3:1 for large text).

### CSS Variables (for software/UI use)
```css
:root {
  --color-vet-blue: #021660;
  --color-tech-teal: #27BDBE;
  --color-care-red: #ED3030;
  --color-action-blue: #0055E7;
  --color-medium-blue: #75C1FF;
  --color-greatpet-green: #008556;
  --color-black: #191919;
  --color-white: #FFFFFF;
  --color-gray-light: #F4F5F7;
  --color-gray-mid: #6B7280;
  --color-gray-dark: #374151;
}
```

---

## 4. Typography

### Font Stack
| Role | Font | File | Weight(s) |
|---|---|---|---|
| All text | `Mulish` (variable) | `Mulish-VariableFont_wght.ttf` | 200–900 (full range) |
| Monospace / Code | System monospace | — | 400, 500 |

Mulish is a geometric sans-serif variable font. Use a single file for all weights — no need for separate bold/light files.

### Type Scale (Desktop)
| Level | Size | Weight | Line Height | Usage |
|---|---|---|---|---|
| H1 | 48px / 3rem | 900 | 1.1 | Page heroes, major section titles |
| H2 | 36px / 2.25rem | 800 | 1.2 | Section headings |
| H3 | 24px / 1.5rem | 700 | 1.3 | Card titles, subsections |
| H4 | 18px / 1.125rem | 700 | 1.4 | Labels, minor headings |
| Body | 16px / 1rem | 400 | 1.6 | All paragraph text |
| Small | 14px / 0.875rem | 400 | 1.5 | Captions, footnotes, metadata |
| Label / Tag | 12px / 0.75rem | 800 | 1.4 | Uppercase tags, eyebrow text |

### Typography Rules
- **All text** uses Mulish. There is no secondary typeface — use weight variation to create hierarchy.
- **Headlines** should be set in Vet Blue (`#021660`) on light backgrounds, or White on dark backgrounds.
- **Body text** should be Near Black (`#191919`) on light backgrounds for maximum readability.
- **Never** use Tech Teal or Care Red for body text — reserve them for interactive elements or very short emphasis.
- Line length (measure) should be kept between 60–80 characters for body text.
- Do not justify body text. Use left-align for all body copy.
- Use uppercase + weight 800 for labels, tags, and eyebrow text only. Never uppercase body copy.

---

## 5. Voice & Tone

### Brand Voice Attributes
- **Confident** — We are experts. Speak with authority, not hedging.
- **Clear** — Avoid jargon. If a technical term is necessary, define it.
- **Warm** — We are partners to veterinary professionals. Use "you" and "we" freely.
- **Forward-looking** — Emphasize progress, innovation, and what's possible.
- **Grounded** — Back claims with substance. No empty marketing speak.

### Tone by Context
| Context | Tone | Notes |
|---|---|---|
| Marketing / external | Inspiring, energetic, clear | Lead with impact, not features |
| Product / UI | Concise, helpful, reassuring | Microcopy should guide, not overwhelm |
| Internal docs | Professional, direct, friendly | Can be more casual; avoid bureaucratic language |
| Social media | Conversational, warm, expert | Share perspectives, not just promotions |
| Error messages | Calm, helpful, solution-focused | Never blame the user |
| Legal / compliance | Precise, neutral, factual | Follow legal review guidelines |

### Writing Rules
- Use active voice. "We ship globally" not "Products are shipped globally."
- Prefer short sentences (under 25 words) for key messages.
- Use Oxford commas.
- Capitalize "Covetrus" always — never "covetrus" or "COVETRUS."
- Refer to the company as "Covetrus" (not "the company," "we" alone in first reference, or abbreviations).
- Avoid: *leverage, synergy, paradigm shift, best-in-class, seamlessly, game-changing, robust*.
- Preferred alternatives: *use, advantage, shift, leading, smoothly, transformative, reliable*.

---

## 6. Iconography & Imagery

### Icon Style
- Use **line icons** (stroke-based) at 1.5–2px stroke weight.
- Icons should be **Navy** on light backgrounds, **White** or **Teal** on dark backgrounds.
- Preferred icon library: Lucide Icons or Heroicons (outline variant).
- Do not mix filled and outline icons in the same UI context.

### Photography Style
- Imagery should feature real veterinary professionals in authentic working environments.
- Avoid overly staged or stock-photo aesthetics.
- Color grade should be warm-neutral — avoid cold blue tones.
- Animals (pets and livestock) should appear healthy and well cared for.
- People of diverse backgrounds, ages, and specialties should be represented.

### Illustration Style
- Flat, geometric, and modern — consistent with the geometric diamond motif in the logo.
- Use the brand color palette only.
- Avoid photorealistic illustration or clip-art aesthetics.

---

## 7. UI & Software Guidelines

### Component Patterns
- **Primary Button:** Background `#27BDBE` (Teal), white text, border-radius `6px`, font-weight 600.
- **Secondary Button:** Border `#021660` (Navy), Navy text, transparent background.
- **Destructive/Alert Button:** Background `#ED3030` (Red), white text.
- **Input Fields:** Border `#D1D5DB`, focus ring `#27BDBE` (2px), border-radius `6px`.
- **Links:** Color `#27BDBE`, underline on hover only.
- **Cards:** White background, `1px solid #E5E7EB` border, `8px` border-radius, subtle shadow `0 1px 3px rgba(0,0,0,0.08)`.
- **Navigation:** Navy background with white text. Active state uses Teal underline or left border.

### Spacing System (8px base)
| Token | Value | Usage |
|---|---|---|
| `--space-1` | 4px | Tight inline spacing |
| `--space-2` | 8px | Component internal padding |
| `--space-3` | 16px | Between related elements |
| `--space-4` | 24px | Section subdivisions |
| `--space-5` | 32px | Between sections |
| `--space-6` | 48px | Major layout gaps |
| `--space-7` | 64px | Hero/page-level spacing |

### Accessibility
- All interactive elements must have visible focus states using the Teal (`#27BDBE`) outline.
- Use `aria-label` on all icon-only buttons.
- Minimum touch target size: 44×44px.
- All images must have meaningful `alt` text.

---

## 8. Social Media Guidelines

### Platform Tone
| Platform | Tone | Content Focus |
|---|---|---|
| LinkedIn | Professional, thought leadership | Industry insights, company news, careers |
| Instagram | Visual, warm, community-focused | Behind-the-scenes, team, pet-forward content |
| X / Twitter | Concise, timely, conversational | Industry news, quick tips, event coverage |
| Facebook | Informative, community | Product updates, educational content |

### Post Formatting
- Always include the Covetrus logo or watermark on owned creative assets.
- Use Teal (`#27BDBE`) as the primary accent color in social graphics.
- Hashtags: use 3–5 maximum. Always include `#Covetrus` on owned posts.
- Emojis: acceptable on Instagram and X; use sparingly on LinkedIn (1–2 max).

---

## 9. Internal Document Standards

### Document Header
All internal documents should include:
- Document title (H1, Navy)
- Author name, department, date
- Version number (e.g., v1.0)
- Status tag: `Draft`, `In Review`, or `Approved`

### Formatting Rules
- Use Montserrat for headings, Source Sans 3 for body (or system equivalents: Georgia/Helvetica Neue if custom fonts unavailable).
- Section headings in Navy, body text in Near Black.
- Use tables for comparative data; avoid dense prose lists when a table is clearer.
- All internal docs should be stored in the approved document management system with proper naming conventions: `YYYY-MM-DD_Department_DocumentTitle_v1.0`.

---

## 10. Using This Guide With AI Tools

### Claude Projects (Recommended)
1. Go to [claude.ai](https://claude.ai) and create a new **Project**.
2. In the Project knowledge section, upload this file (`covetrus-brand-guide.md`).
3. Every conversation in that Project will now have full brand context.
4. Suggested system prompt addition: *"Always follow the Covetrus brand guide when generating content, UI code, or copy."*

### Other AI Tools
- **Cursor / GitHub Copilot:** Add this file to your `.cursorrules` or reference it in your system prompt for brand-consistent UI code.
- **ChatGPT:** Attach this file to a Custom GPT or paste relevant sections into the system prompt.
- **Any LLM API:** Include this file as a `system` message document block.

### Prompting Tips
When using AI to generate Covetrus content, include phrases like:
- *"Use the Covetrus brand guide"*
- *"Navy (#021660) as primary color, Teal (#27BDBE) for CTAs"*
- *"Tone: professional, warm, and forward-looking"*
- *"Font: Montserrat for headings, Source Sans 3 for body"*

---

*Last updated: May 2026 | Maintained by: Brand & Marketing*  
*For questions, contact the Brand team.*
