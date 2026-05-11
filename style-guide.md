# Connected — Style Guide
*Extracted from Babylist design inspiration, adapted for Connected's memory care context*

---

## 1. Design Philosophy

**The guiding idea:** This app should feel like a trusted friend who happens to be really organized — warm, clear, and never overwhelming. Babylist achieves this by pairing a clean white canvas with a single rich accent color (deep plum/purple) and letting colorful photography and illustration do the emotional lifting. Everything else steps back.

For Connected, we adapt this principle: the interface itself should be calm and uncluttered. The warmth lives in the photos, the updates, the stories — not in the chrome around them. The app holds space for emotion without manufacturing it.

**The north star feeling:** A family member opens the app between meetings and sees a photo of their mom doing watercolor painting. The interface disappears. All they notice is their mom.

---

## 2. Target User & Jobs to Be Done

**Primary user — Sarah (the adult daughter):**
- Checks the app in short windows: between meetings, during school pickup, before bed
- Needs to get an emotional snapshot in under 10 seconds
- Doesn't want to feel like she's using software; wants to feel like she's checking in on her mom
- Job to be done: *Feel present in my loved one's day, even when I'm not there*

**Secondary user — Care Staff:**
- Posting quick updates throughout a shift
- Needs the posting flow to feel fast and encouraging, not like filing paperwork
- Job to be done: *Share a moment that will mean something to a family*

**Design implication:** Every screen should pass the "10-second test" — the most important thing should be immediately visible, no hunting required.

---

## 3. Spatial System (Layout)

**Overall structure — clean and wide:**
- Babylist uses a bright white background with generous breathing room between elements. Copy this: white space is not wasted space, it's emotional relief.
- Top navigation: flat, no shadows, just the logo and a few key links. Nothing decorative.
- Content lives in clearly bounded sections, but the sections themselves don't have heavy borders — they're separated by space, not lines.

**Card grid:**
- Content cards sit in a 2- or 4-column grid on wider screens, stacking to a single column on mobile.
- Cards have softly rounded corners (not sharp, not pill-shaped — just slightly rounded, like a piece of paper).
- No card borders. Cards sit on the white background without a box around them.

**Hierarchy of information:**
- One dominant element per section (the hero card, the featured photo, the day's top update)
- Supporting content below, smaller and less prominent
- One call-to-action per screen — never two competing buttons

**Mobile-first rule:**
- Everything should be finger-friendly. Tap targets are generous.
- Content scrolls vertically. No horizontal scrolling inside a card.

---

## 4. Typography

**Babylist's approach:** Two weights do all the work. Headlines are bold and confident. Body text is regular weight and relaxed. There are no decorative fonts anywhere.

**For Connected:**

| Role | Style | Feel |
|------|-------|-------|
| App name / logo text | Bold, slightly larger | Confident but friendly |
| Section headers | Bold, dark, medium-large | Clear wayfinding |
| Card titles / update headlines | Bold, dark | Easy to scan |
| Body text / update descriptions | Regular weight, dark gray | Readable, calm |
| Labels / timestamps / metadata | Smaller, medium gray | Recedes without disappearing |
| Buttons | Bold or medium, all-caps optional | Action-forward |

**What to avoid:**
- Script or handwritten fonts (too cute, reads as greeting card)
- Light/thin font weights (hard to read for older eyes visiting in low light)
- More than two font sizes in a single card

---

## 5. Color Palette

**Babylist's lesson:** Pick one strong brand color and use it only for things that matter — the logo, the primary button, the active state. Everything else is white, near-black, or soft neutral. This makes the brand color feel meaningful every time it appears.

**Connected's palette (adapted from Babylist with warmer tones):**

| Color | Description | When to use |
|-------|-------------|-------------|
| Warm white | The background. Not pure white — just slightly warm, like good paper. | Every screen background |
| Soft peach / blush | A barely-there tint for section backgrounds, photo containers | Secondary backgrounds, cards |
| Sage green | Muted, natural green | Success states, activity markers, "attended" indicators |
| Warm plum / dusty violet | The brand's one strong color — rich but not cold | Primary buttons, active nav, logo accent, links |
| Near-black charcoal | Very dark gray, not true black | All headlines and body text |
| Medium warm gray | Mid-tone gray | Timestamps, labels, secondary text |
| Light warm gray | Almost-white gray | Dividers, disabled states, empty states |

**Color states:**
- **Primary button:** Plum background, white text. On hover/press: slightly darker plum.
- **Active nav item:** Plum underline or plum text — the only color that appears in navigation.
- **Success / completed:** Sage green dot or badge.
- **Alert / urgent:** Warm amber — never red (red reads as medical emergency).

**What to avoid:**
- Clinical blues or hospital greens
- True red for anything (reads as alarm)
- More than 2 accent colors visible on the same screen

---

## 6. Component Variants

**Navigation bar (top):**
- Logo left. Primary navigation center or right. Clean white bar, no shadow.
- One CTA button (e.g., "Send a Message") in plum, pill-shaped.
- Active page underlined in plum.

**Cards — three types:**

*Feature card (large):*
- Image or illustration left (takes up roughly half the card)
- Headline and description right
- Rounded corners, soft cream background
- Used for: today's featured moment, the day's highlight update

*Feed card (medium):*
- Full-width image on top, text below
- Timestamp in gray, small
- Title in bold charcoal
- Used for: activity updates, meal notes, staff photos

*List item (compact):*
- Icon or small image left, text right
- One line title, one line metadata
- Used for: calendar entries, resource links, message queue

**Buttons — two types:**
- *Primary:* Plum pill, white text, bold. One per screen.
- *Secondary:* White pill with plum outline, plum text. For less critical actions.

**Floating action button:**
- Babylist uses a rounded pill ("Chat") in the bottom right corner.
- Connected equivalent: "Send a Moment" — a plum pill, bottom right, visible from the feed.

**Tab bar (secondary navigation):**
- Light background strip with tab labels
- Active tab has a plum underline
- Inactive tabs are gray text

**Empty states:**
- Warm, illustrated (not a sad gray message)
- Example: "No updates yet today — check back after breakfast"
- Tone is reassuring, not clinical

---

## 7. Content Voice Guidelines

**Babylist's voice:** Knowledgeable but not clinical. Helpful like a friend who's been through it. Uses real sentences, not jargon. Titles are direct and practical ("What to Replace, When & Why It Matters").

**Connected's voice — adapted for emotional stakes:**

| Situation | Babylist equivalent | Connected adaptation |
|-----------|--------------------|--------------------|
| Activity update | "Here's what you need to know" | "Judy joined watercolor painting this morning" |
| Empty feed | — | "No updates yet — the morning is just getting started" |
| Staff prompt | Article category label | "What's one thing from today worth sharing?" |
| Button labels | "Sign Up", "Shop" | "Send a Moment", "See Today's Calendar" |
| Error message | — | "Something didn't load — try pulling down to refresh" |

**Rules:**
- Write to a person, not a user.
- Judy is never "the resident" or "Patient 412." She's Judy.
- No passive voice in updates ("Judy enjoyed lunch" not "Lunch was served.")
- Never use medical or clinical terminology in family-facing copy.
- Staff-facing prompts should feel encouraging, not like a checklist.

---

## 8. Accessibility Standards

**Babylist gets this right by keeping contrast high and layouts simple. For Connected, go further — families may be reading while emotional, distracted, or on a small screen in bad lighting.**

- Text on white backgrounds: charcoal or near-black only. No light gray text on white.
- Text on photos: always has a dark overlay or text shadow so it's legible regardless of photo content.
- Tap targets are large — thumbs, not fingertips.
- Font sizes never go below comfortable reading size (especially for the secondary user: families may include older adults).
- Never rely on color alone to communicate meaning (e.g., a "completed" activity has a checkmark AND a green dot, not just green).
- The app works in both light and dark mode without any special configuration.

---

## 9. Do / Don't Examples

**Layout:**
```
DO:                                    DON'T:
┌─────────────────────────┐           ┌──────────────────────────┐
│  [Big photo]            │           │ [tiny icon] Update 1     │
│                         │           │ [tiny icon] Update 2     │
│  Judy joined painting   │           │ [tiny icon] Update 3     │
│  this morning           │           │ [tiny icon] Update 4     │
│  9:15 AM                │           │ [tiny icon] Update 5     │
└─────────────────────────┘           └──────────────────────────┘
One featured moment, room to breathe   List of items, no hierarchy
```

**Color:**
```
DO: One plum button. White screen. Photo does the work.
DON'T: Peach header + green badge + plum button + amber alert = visual noise.
```

**Copy:**
```
DO:   "Judy danced to Patsy Cline during music hour."
DON'T: "Resident attended music therapy session. Status: compliant."
```

**Cards:**
```
DO:                          DON'T:
┌──────────────────┐        ┌──────────────────────────────────┐
│ [Photo]          │        │ ╔════════════════════════════╗   │
│ Watercolor class │        │ ║ ACTIVITY LOG — 10:30 AM    ║   │
│ 10:30 AM         │        │ ║ Resident: Judy M.          ║   │
└──────────────────┘        │ ║ Activity: Watercolor       ║   │
Warm, human, scannable      │ ╚════════════════════════════╝   │
                            └──────────────────────────────────┘
                            Clinical, boxed, cold
```

---

*This guide is a living document. When you find a new design that resonates — a card component, a color combo, a way of handling empty states — add it here.*
