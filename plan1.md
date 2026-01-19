# Room To Bloom — Website Build Spec (for Codex)
Goal: generate a fast, conversion-focused, SEO-friendly website for a Denver-metro home organizing business using **TailwindCSS**. Use the copy + brand cues pulled from the provided Facebook/Instagram screenshots.

---

## Brand + Business Info (from screenshots)
**Business name:** Room To Bloom  
**Tagline:** Joyful, Judgement-Free Home Organizing  
**Primary location:** Denver, CO (Denver metro)  
**Positioning:** warm, supportive, non-judgmental, “reset your space and your spirit.”

**Offer called out:**
- “Organizing sessions starting at **$200** (holiday special!)”
- “First-time sessions starting at **$200 for 3 hours**” (use this as an *Intro Session*)

**Contact:**
- Instagram: **@roomtobloomorganizing**
- Facebook page: **Room To Bloom** (handle shown: roomtobloomorganizing)
- Phone: **(720) 504-8042**
- Email: **roomtobloomorganizing@gmail.com**
- CTA language: “DM to book” / “Limited spots”

---

## Visual Style Cues
Pull from the banner:
- Friendly, colorful “rainbow border” vibe, but keep the site modern/clean.
- Key colors: teal/seafoam + pink accent + warm yellow/gold.
- Rounded shapes, soft shadows, lots of whitespace.
- Photography: before/after rooms + candid founder headshot (blue hair streak) to convey warmth + personality.

---

## Assets Provided (local paths)
Use these exact files in the build:
- Facebook header screenshot (brand reference):  
  `/mnt/data/CleanShot 2026-01-19 at 13.10.35@2x.jpeg`
- Instagram profile screenshot (bio reference):  
  `/mnt/data/CleanShot 2026-01-19 at 13.11.39.png`
- Founder/profile photo (use on About section + favicon/social preview if needed):  
  `/mnt/data/588720378_10162269836621958_6802481066865089935_n.jpg`
- Post screenshot w/ copy (use as “Client Story” copy source):  
  `/mnt/data/CleanShot 2026-01-19 at 13.11.10@2x.png`
- Post screenshot w/ copy (use as “Client Story” copy source):  
  `/mnt/data/CleanShot 2026-01-19 at 13.10.59@2x.png`
- Screenshot showing contact info + photos grid:  
  `/mnt/data/CleanShot 2026-01-19 at 13.10.43@2x.png`

Implementation note: copy these into the project under something like `public/images/`:
- `public/images/founder.jpg`
- `public/images/brand-header.jpg` (optional reference)
- `public/images/post-shed.jpg` (optional reference)
- `public/images/post-mold.jpg` (optional reference)

---

## Tech + Output
Build as a simple static site:
- Option A (recommended): **Vite + Vanilla HTML + Tailwind** (fastest)
- Option B: **Next.js** (if you want blog/expansion later)

Required:
- TailwindCSS
- Mobile-first
- Lighthouse-friendly (optimize images, semantic HTML, minimal JS)
- Clear CTA to book via phone/email/IG

Deliverables:
- A single-page website (scrolling sections)
- Optional secondary pages: `/services`, `/gallery`, `/contact` (only if quick)
- Basic SEO: title/meta/OG tags + LocalBusiness JSON-LD schema

---

## Sitemap (single-page)
1. Hero
2. Social proof strip (quick bullets)
3. Services
4. How it works (process)
5. Pricing (simple + transparent)
6. Before/After gallery (placeholder tiles + easy to swap)
7. Client stories (pull language from screenshots)
8. About (founder photo + philosophy)
9. FAQ
10. Final CTA + contact + footer

Sticky header with: Services, Pricing, Gallery, About, Contact.

---

## Copy (use this verbatim unless you improve clarity)

### Hero
**Headline:** Joyful, judgement-free home organizing in Denver.  
**Subhead:** If your home (or a space within it) is feeling overwhelming, cluttered, or just in need of a refresh, Room To Bloom is here to help.  
**Primary CTA button:** Book an intro session  
**Secondary CTA:** Text / Call (720) 504-8042  
**Microcopy under CTAs:** Prefer Instagram? DM **@roomtobloomorganizing**.

Add a small promo badge:
- “Intro sessions from **$200 / 3 hours**”

### Social proof strip (3–5 bullets)
- Judgment-free support (no shame, ever)
- Declutter + systems that *stick*
- Calm, functional spaces—fast
- Serving Denver & surrounding neighborhoods
- Limited monthly spots available

### Services (cards)
Create 6 service cards:
1. **Decluttering + Reset**
   - Reduce overwhelm, clear surfaces, create breathing room.
2. **Closets + Bedrooms**
   - Clothing edits, zones, simple maintenance systems.
3. **Kitchen + Pantry**
   - Category zones, container resets, labels that make sense.
4. **Garage + Storage**
   - Clear floor space, bin systems, seasonal rotation.
5. **Move / Unpack Help**
   - Unpack with intention so your new space works day one.
6. **Life Transitions**
   - Gentle organizing support during stressful seasons.

Each card: short description + “Ask about this” link to contact section.

### How it works (simple 4-step)
1. **Quick consult** (phone/text/IG DM)  
2. **Plan**: goals + priorities + what “done” looks like  
3. **Hands-on session**: sort, zone, organize, label  
4. **Maintain**: simple routines so it stays calm

### Pricing (keep simple)
**Intro Session (most popular)**  
- **$200 / 3 hours**  
- Perfect for one problem area (closet, pantry, bedroom reset)

**Half-Day Reset**  
- 4–5 hours (price: “Custom quote” unless you know it)

**Full-Day Bloom**  
- 6–8+ hours (price: “Custom quote”)

Pricing note:
- Add: “Need help estimating time? Send photos—happy to suggest a plan.”

CTA: “Get a quote” anchors to contact.

### Gallery (before/after)
Make a responsive grid (2 columns mobile, 3 desktop).
Use placeholders now; allow easy swap with real photos later.
Include captions:
- “Bedroom reset”
- “Pantry zones”
- “Office paper system”
- “Garage storage”
- “Closet edit”
- “Move-in setup”

### Client stories (based on post screenshots)
Create two story blocks (not “testimonials,” more like narratives).

**Story 1: The shed that caused anxiety**
- “This shed had been haunting my client for months… clutter halts motivation and kills inspiration.”
- “If there’s a space weighing on you… treat yourself and call in some help.”
- End line: “Start the year with one less thing on your shoulders.”

**Story 2: After mold remediation**
- “Everything was packed quickly—mostly in trash bags—piled in the garage. Overwhelming.”
- “We spent nearly 9 hours sorting, folding, labeling, and restoring clarity.”
- Mention a helpful deliverable: “A catalog of labeled bins with descriptions and photos.”

Add CTA after stories: “Want this kind of reset? Let’s talk.”

### About
Section headline: **Hi, I’m the face behind Room To Bloom.**  
Tone: warm, supportive, grounded.

Include:
- “It can be a vulnerable process letting someone organize your home.”
- “I hold it with the highest honor.”
- “I want you to feel more grounded and in control again.”

Use founder photo as a circle/rounded card.

### FAQ (6 items)
1. **Do you judge messy homes?**  
   Never. This is judgment-free support.
2. **Do I need to buy containers first?**  
   No—start with decluttering. Containers come after.
3. **How long will it take?**  
   Depends on volume + decisions. Send photos for a time estimate.
4. **Can you help me decide what to keep?**  
   Yes—gentle, practical guidance.
5. **Do you take donations/trash away?**  
   Add a neutral answer: “We’ll stage donations + trash for easy drop-off.”
6. **Where do you work?**  
   Denver metro (add neighborhoods later).

### Contact
Headline: **Ready to clear the chaos?**  
Buttons:
- Call/Text: **(720) 504-8042** (`tel:+17205048042`)
- Email: **roomtobloomorganizing@gmail.com** (`mailto:`)
- Instagram DM: link to Instagram profile

Also include a simple contact form (optional) that sends to email (use Formspree or Netlify Forms if hosting supports it). If you include a form, keep it minimal: name, email/phone, neighborhood, what space, optional photo links.

---

## SEO Requirements
### Metadata
- Title: `Room To Bloom | Judgment-Free Home Organizing in Denver`
- Meta description (155–160 chars):
  `Room To Bloom offers joyful, judgment-free home organizing across Denver. Declutter, reset your space, and build simple systems that last.`
- Add OG tags using founder image if possible.

### Headings
- One H1 only (hero headline)
- H2 for each section

### LocalBusiness Schema (JSON-LD)
Include:
- name: Room To Bloom
- areaServed: Denver, CO
- telephone: +1-720-504-8042
- email: roomtobloomorganizing@gmail.com
- sameAs: Instagram + Facebook URLs (if you have them; otherwise omit)

### Target keyword themes
- “Denver home organizer”
- “professional organizer Denver”
- “decluttering Denver”
- “home organizing services Denver”

---

## Tailwind Theme Notes
Implement a small design system:
- Background: warm white (`#fffaf7` style)
- Primary text: slate/charcoal
- Accent 1 (teal): seafoam/teal
- Accent 2 (pink): rosy pink
- Accent 3 (gold): warm yellow

Use:
- Rounded-2xl cards
- Soft shadow
- Colorful “rainbow border” component used sparingly (hero + CTA card)

---

## UI Components to Build
- Sticky header with anchors + “Book” button
- Hero with promo badge + 2 CTAs
- Service cards grid
- Process steps with icons
- Pricing cards
- Gallery grid
- Story blocks (large quote + short narrative)
- About card with photo
- FAQ accordion (optional JS; can be simple details/summary)
- Contact CTA section + footer

---

## Implementation Checklist (Codex)
Build the project and include:
- Tailwind configured
- Responsive layout
- Smooth scroll to anchors
- Accessible color contrast + focus states
- Optimized images (use `loading="lazy"` where appropriate)
- No heavy dependencies

If making Vite + HTML:
- `index.html` with sections
- `main.css` importing Tailwind
- `tailwind.config.js`
- Put images in `public/images/`

If making Next.js:
- `app/page.tsx` with sections
- `globals.css` with Tailwind
- `next-seo` optional (not required)

---

## Final Notes
- Keep the voice: warm, human, supportive. Avoid corporate language.
- Make the booking path obvious from every major section.
- Make it easy to swap gallery photos later.

END
