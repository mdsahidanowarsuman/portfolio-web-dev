# Modern Strategic & Executive Portfolio — MD SAHID ANOWAR SUMAN
**Official Student Name:** MD SAHID ANOWAR SUMAN  
**Academic Institutions:**  
- **Indian Institute of Management Bangalore (IIM Bangalore)** — BBA in Digital Business & Entrepreneurship (DBE), 2026–2029 (Expected)  
- **Brainware University** — B.Tech in Computer Science & Engineering (AI & ML), 2023–2027 (Expected) | SGPA: 8.63  

---

## 1. Executive Brand Identity & Vision
This portfolio is an executive-level, human-designed personal brand showcase engineered strictly using **HTML5** and **CSS3**. It deliberately avoids heavy third-party JavaScript frameworks, external CSS libraries (e.g. Bootstrap or Tailwind), and backend runtimes.

The visual direction draws inspiration from leading strategic business consultancies, modern technology entrepreneurs, and minimalist editorial publications. It articulates the intersection of:
1. **Business, Sales & Entrepreneurship:** Direct commercial leadership, sales strategy, pricing models, and ~₹8 Lakhs profit generated in 6 months at Sayan Electric Bikes.
2. **Technology, Computer Science & AI/ML:** Foundational computer engineering at Brainware University (8.63 SGPA), industrial training at IBM, and AI internship at Samsung Innovation Campus.
3. **Leadership, Communication & Strategic Thinking:** High-leverage client negotiation, national JEE Main 93rd percentile, International Math Olympiad rank 22, and 1.6M+ organic YouTube views.

---

## 2. Directory & File Architecture
```text
WEB DEV MIDTERM-IIMB/
│
├── index.html                    # Root launcher (opens portfolio immediately in any browser)
├── README.md                     # Comprehensive academic documentation & viva defense notes
│
└── portfolio/                    # Self-contained multi-page portfolio directory
    ├── index.html                # Page 1: Home (01 / INTRODUCTION - Hero, Stats, 3 Dimensions, CTA)
    ├── about.html                # Page 2: About (02 / ABOUT - Summary, 3 Editorial Perspectives)
    ├── education.html            # Page 3: Education (03 / EDUCATION - Prominent IIMB, Brainware, CBSE)
    ├── experience.html           # Page 4: Experience (04 / EXPERIENCE - Sayan Electric Bikes, IBM, Samsung, YouTube)
    ├── projects.html             # Page 5: Projects (05 / PROJECTS - Reventra AI, Samsung Hackathon, UI Design)
    ├── skills.html               # Page 6: Capabilities (06 / CAPABILITIES - 4 Clusters, Honors, Strengths)
    ├── contact.html              # Page 7: Contact (07 / CONTACT - Deep Evergreen, mailto, tel, location)
    │
    ├── css/
    │   └── style.css             # Shared master stylesheet (Design Tokens, Grid, Flexbox, Media Queries)
    │
    └── images/
        └── profile.jpg           # Genuine portrait photograph from CV
```

---

## 3. Evergreen, Gold & Slate Colour Palette

| Role | Colour Name | HEX Code | Proportional Distribution & Usage |
| :--- | :--- | :--- | :--- |
| **Primary** | Deep Evergreen | `#153C3A` | **20–25%** — Hero headings, dark stat strip, executive contact card, footers |
| **Main Background** | Cloud Grey | `#F4F6F3` | **55–60%** — Primary canvas, body background, clean contemporary warmth |
| **Secondary Background** | Pure White | `#FFFFFF` | **10–15%** — Content cards, timeline panels, feature blocks |
| **Primary Accent** | Champagne Gold | `#D49A45` | **5%** — Section identifiers, focal words, CTA buttons, active underlines |
| **Secondary Accent** | Slate Blue | `#5E8190` | **5%** — Supporting labels, subtitle accents, technical badges |
| **Supporting Colour** | Soft Sage | `#E5ECE8` | Alternating section containers, academic badges, strength cells |
| **Main Text** | Deep Charcoal | `#1F2D2C` | High-contrast, fatigue-free editorial body copy |
| **Secondary Text** | Muted Grey | `#64716E` | Dates, captions, metadata, subtitles |
| **Borders** | Light Grey Green | `#D8E0DC` | Hairline dividers, crisp architectural grids |

---

## 4. Typography System (Three Google Fonts)

1. **Sora (`var(--font-heading)`):**
   - *Weights:* 600 (Semi-Bold), 700 (Bold)
   - *Application:* Main headlines, page titles, important strategic statements.
   - *Aesthetic:* Confident, modern, intelligent, sans-serif authority without excessive decoration.
2. **Source Sans 3 (`var(--font-body)`):**
   - *Weights:* 400 (Regular), 500 (Medium), 600 (Semi-Bold)
   - *Application:* Body paragraphs, narrative descriptions, experience bullets, general copy.
   - *Aesthetic:* Humanist legibility, comfortable reading rhythm for long-form career text.
3. **IBM Plex Mono (`var(--font-mono)`):**
   - *Weights:* 500 (Medium), 600 (Semi-Bold)
   - *Application:* Brand name (`MD SAHID ANOWAR SUMAN`), section numbers (`01 / INTRODUCTION`), dates, statistics, skill tags, and technical coordinates.
   - *Aesthetic:* High technical precision, reminiscent of architectural blueprints and executive dossiers.

---

## 5. Educational Branding & Prominence
- **Header:** Exclusively features the complete personal brand: **`MD SAHID ANOWAR SUMAN`**. Institutional names have been removed from beneath the name in the header to ensure personal identity leads.
- **IIM Bangalore Primary Prominence:** As this website was designed for an IIM Bangalore evaluation, the **BBA in Digital Business & Entrepreneurship (DBE)** receives top visual prominence on both the Homepage (hero badge) and the Education page (highlighted border, gold distinction pill, and primary card placement).
- **Brainware University Parallel Track:** Displayed accurately as the parallel technical degree (B.Tech CSE AI/ML, SGPA 8.63) with clean, readable secondary hierarchy.

---

## 6. Ten Fundamental Design Principles Implemented
1. **Contrast:** High visual contrast between Deep Evergreen (`#153C3A`), Pure White (`#FFFFFF`), and Cloud Grey (`#F4F6F3`), with Champagne Gold (`#D49A45`) guiding the eye to primary CTAs.
2. **Repetition:** Unified compact navigation bar, IBM Plex Mono section IDs (`01 / INTRODUCTION`, etc.), button styles, and 4-column footer across all 7 pages.
3. **Alignment:** Precise 12-column CSS Grid and Flexbox alignment ensuring all headings, content grids, and timeline nodes align cleanly.
4. **Proximity:** Related metadata (e.g. date badges, role tags) are grouped tightly, while distinct sections maintain ample vertical separation (`var(--space-3xl)`).
5. **Visual Hierarchy:** Scaled typography via CSS `clamp()` ensures primary headlines dominate visual weight, followed by uppercase mono subheaders and comfortable body text.
6. **Balance:** Asymmetrical executive split on the hero (copy on the left balanced by the CSS-only convergence architecture matrix on the right).
7. **White Space:** Generous vertical breathing room preventing visual fatigue and establishing an executive feel.
8. **Consistency:** Centralized CSS custom properties in `style.css` govern all measurements, colors, and transitions uniformly.
9. **Gestalt Principles:** Grouping by proximity and similarity (e.g. skill pills, statistics cells, and timeline nodes form coherent perceptual units).
10. **Accessibility (a11y):** Native semantic landmarks, visible keyboard focus rings, WCAG AAA/AA text contrast ratios, and `@media (prefers-reduced-motion)` support.

---

## 7. How to Open and Run Locally
1. Navigate to the project directory in your file explorer or terminal:
   ```bash
   cd "/Users/user/Desktop/WEB DEV MIDTERM-IIMB"
   ```
2. Double-click `portfolio/index.html` (or `index.html`).
3. Open in any modern web browser (Google Chrome, Safari, Firefox, Edge).
4. **No Server Needed:** All paths are relative (`css/style.css`, `about.html`, etc.) and work directly via the local `file://` protocol.
