# Covetrus Brand Guide
> This file is designed to be used as a reference for AI tools (Claude, Copilot, etc.), developers, designers, and anyone creating Covetrus-branded content. Attach it to a Claude Project, paste it into a system prompt, or reference it in any AI tool to ensure brand-consistent outputs.

---

## 1. Brand Identity

**Company Name:** Covetrus  
**Industry:** Veterinary health technology and services  
**Mission:** To advance the world of veterinary medicine by empowering practitioners with the technology, products, and solutions they need to thrive.  
**Tone:** Professional, trustworthy, forward-thinking, warm, and science-backed. Covetrus speaks with confidence but never arrogance. We are a partner to veterinary professionals, not a vendor.

**Brand Philosophy:** Our brand is one of the most valuable assets we have. Every time someone encounters our name, our work, or our content, whether in a product, a proposal, a social post, or an AI-generated output, they form an impression of who we are. Consistency is what turns those individual moments into a recognizable, trustworthy identity.

**Sub-brands:** Covetrus operates a family of brands including VetSuite, vRxPro, GreatPet Care, Pulse, and Prop Brands. Each has its own identity but operates within the Covetrus brand system.

---

## 2. Logo

The Covetrus master brand logo is the foundation, but our portfolio includes a family of point solution logos that extend the brand across our products and services. Each point solution logo has been designed to work within the Covetrus brand system while carrying its own identity.

All logo versions are stored in our central asset library on SharePoint. Always pull logo files from this source to ensure you are using the most current, approved version. Do not recreate, alter, or source logos from anywhere else.

### Logo Variants
| Variant | File | Usage |
|---|---|---|
| Full Wordmark – RGB | `Covetrus_RGB.svg` | Primary use on white/light backgrounds |
| Full Wordmark – Knockout (KO) | `Covetrus_RGB_KO.svg` | Use on dark or colored backgrounds |
| Full Wordmark – Black | `Covetrus_Black.svg` | Single-color print, light backgrounds |
| Full Wordmark – White | `Covetrus_White.svg` | Use on dark backgrounds, single-color white contexts |
| Icon/Bug – RGB | `Covetrus_Bug_RGB.svg` | Small spaces, app icons, favicons, social avatars |
| Icon/Bug – Knockout (KO) | `Covetrus_Bug_RGB_KO.svg` | Icon use on dark backgrounds |
| Icon/Bug – Black | `Covetrus_Bug_Black.svg` | Single-color print, light backgrounds |
| Icon/Bug – White | `Covetrus_Bug_White.svg` | Icon use on dark backgrounds, single-color white |

### Logo Do's
- Use SVG for all web, app, and screen contexts
- Use PNG when transparency is needed (presentations, overlays)
- Use JPG for PowerPoint slides and email signatures
- Use the KO/White variants on dark or colored backgrounds
- Maintain clear space equal to the height of the "C" on all sides

### Logo Don'ts
- Do not modify colors, rotate, skew or distort elements
- Do not add shadows, outlines, gradients or effects
- Do not move or modify the ® or ™ symbols
- Do not move or rearrange elements
- Do not create new logos without involving the creative team

---

## 3. Color Palette

Color is one of the most immediate and powerful expressions of our brand. Used consistently, our palette builds recognition over time. Primary colors carry the weight of the brand and should do the most work across our touchpoints. Secondary and accent colors exist to support, not compete.

All color combinations used for text, UI elements, and critical information must meet WCAG 2.1 AA contrast standards at minimum.

### Primary Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Vet Blue | `#021660` | rgb(2, 22, 96) | Primary brand color. Use for headings, primary text, buttons, nav, and dominant UI elements. |
| Care Red | `#ED3030` | rgb(237, 48, 48) | Use for alerts, badges, emphasis, and energy/urgency. |
| Tech Teal | `#27BDBE` | rgb(39, 189, 190) | Use for highlights, links, CTAs, icons, and progress indicators. |

### Accent Colors
| Name | Hex | RGB | Usage |
|---|---|---|---|
| Action Blue | `#0055E7` | rgb(0, 85, 231) | Interactive accent. Use for links, hover states, and digital call-to-action elements. |
| Medium Blue | `#75C1FF` | rgb(117, 193, 255) | Secondary blue accent. Use for icons, highlights, and supporting UI elements. |
| Greatpet Green | `#008556` | rgb(0, 133, 86) | Brand extension accent. Use for Greatpet-related content, success states, and positive indicators. |

### Color Spectrums (Full Tint-to-Shade Ranges)

**Greatpet Green:** `#EAF6F3`, `#CCF2D9`, `#96E6B2`, `#6ED299`, `#41B87F`, `#159F6C`, **`#008556`**, `#015C43`, `#133A33`

**Tech Teal:** `#ECFCFC`, `#D7F5F2`, `#B1ECE6`, `#7CDCD9`, **`#27BDBE`**, `#05A5A5`, `#0F7785`, `#0B4A53`, `#0C3238`

**Vet Blue:** `#F3FBFF`, `#E8F7FF`, `#B3E0FF`, `#75C1FF`, `#46A2FB`, `#1474E5`, `#0055E7`, `#11338A`, **`#021660`**, `#02114B`

**Neutral:** `#FFFFFF`, `#F7F7F7`, `#F1F1F1`, `#E8E8E8`, `#D9D9D9`, `#CACACA`, `#A9A9A9`, `#919090`, `#6E6E6E`, `#484848`, `#2C2C2C`, `#191919`

**Care Red:** `#FFF5F5`, `#FCD9D9`, `#F9ABAB`, `#FF8585`, **`#ED3030`**, `#C01E2C`, `#A40E20`, `#750A17`, `#4F0615`

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
  --color-gray-light: #F7F7F7;
  --color-gray-mid: #6B7280;
}
```

---

## 4. Typography

Our primary typeface is Mulish. We made a deliberate shift to Mulish because it is purpose-built for digital environments, optimized for screen rendering, highly legible at small sizes, and designed with accessibility in mind. Its clean, open letterforms perform consistently across interfaces, documents, and AI-generated content.

For environments where Mulish cannot be rendered, most notably Microsoft Outlook and email clients, use Arial as the standard fallback. Arial shares Mulish's clean, sans-serif character and maintains a professional, readable appearance across all platforms and devices.

Do not substitute decorative, serif, or system-default fonts like Calibri or Times New Roman, as these are inconsistent with our brand aesthetic.

### Font Stack
| Role | Font | File | Weight(s) |
|---|---|---|---|
| All text | `Mulish` (variable) | `Mulish-VariableFont_wght.ttf` | 200–900 (full range) |
| Fallback | `Arial` | System font | Regular, Bold |
| Monospace / Code | System monospace | — | 400, 500 |

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
- Typography applied well creates clarity. Applied poorly, it creates friction. Respect the type hierarchy, use weights intentionally, and never sacrifice legibility for style.

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
- Icons use two-color combinations: a primary color and an accent color.
- Four approved icon colorways:
  1. Black (`#191919`) + Medium Blue (`#75C1FF`) — light backgrounds
  2. Black (`#191919`) + Tech Teal (`#27BDBE`) — light backgrounds
  3. White (`#FFFFFF`) + Medium Blue (`#75C1FF`) — dark backgrounds
  4. White (`#FFFFFF`) + Tech Teal (`#27BDBE`) — dark backgrounds
- Do not mix filled and outline icons in the same UI context.

### Photography Style
- Imagery should feature real veterinary professionals in authentic working environments.
- Avoid overly staged or stock-photo aesthetics.
- Color grade should be warm-neutral — avoid cold blue tones.
- Animals (pets and livestock) should appear healthy and well cared for.
- People of diverse backgrounds, ages, and specialties should be represented.
- Photography is organized by sub-brand: Covetrus, VetSuite, vRxPro, GreatPet Care, Prop Brands, and Pulse.

### Illustration Style
- Flat, geometric, and modern — consistent with the geometric diamond motif in the logo.
- Use the brand color palette only.
- Avoid photorealistic illustration or clip-art aesthetics.

---

## 7. Social Media Guidelines

### Platform Tone
| Platform | Tone | Content Focus |
|---|---|---|
| LinkedIn | Professional, thought leadership | Industry insights, company news, careers |
| Instagram | Visual, warm, community-focused | Behind-the-scenes, team, pet-forward content |
| X / Twitter | Concise, timely, conversational | Industry news, quick tips, event coverage |
| Facebook | Informative, community | Product updates, educational content |

### Post Formatting
- Always include the Covetrus logo or watermark on owned creative assets.
- Use Tech Teal (`#27BDBE`) as the primary accent color in social graphics.
- Hashtags: use 3–5 maximum. Always include `#Covetrus` on owned posts.
- Emojis: acceptable on Instagram and X; use sparingly on LinkedIn (1–2 max).

---

## 8. Internal Document Standards

### Document Header
All internal documents should include:
- Document title (H1, Vet Blue)
- Author name, department, date
- Version number (e.g., v1.0)
- Status tag: `Draft`, `In Review`, or `Approved`

### Formatting Rules
- Use Mulish for all text. If unavailable, use Arial as fallback.
- Section headings in Vet Blue, body text in Near Black.
- Use tables for comparative data; avoid dense prose lists when a table is clearer.
- All internal docs should be stored in the approved document management system with proper naming conventions: `YYYY-MM-DD_Department_DocumentTitle_v1.0`.

---

## 9. Using This Guide With AI Tools

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
- *"Vet Blue (#021660) as primary color, Tech Teal (#27BDBE) for CTAs"*
- *"Tone: professional, warm, and forward-looking"*
- *"Font: Mulish for all text, Arial as fallback for email"*

---

*Last updated: May 2026 | Maintained by: Creative Team*  
*Any assets intended for external release should be reviewed and approved by Creative before going out.*  
*Materials that represent the company publicly should be reviewed by Legal.*  
*For questions, contact the Creative team.*
