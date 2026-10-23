# 14 — Website Strategy: Audience, Structure, Design, SEO and Tech

> Internal planning document for the build team. It turns the research in files 01–13 into a website plan.

---

## 1. Website goal

**Mission:** *Be India's most helpful, trustworthy and beautiful guide to 3D animation, with a Karnataka heart.*

**Primary goals**
1. **Educate**: explain 3D animation clearly to beginners.
2. **Guide**: help students and parents choose courses, colleges and careers.
3. **Inspire**: showcase Indian and Karnataka achievements (*Mahavatar Narsimha*, DNEG, GAFX).
4. **Connect**: point users to institutes, events, studios and resources.

**Success metrics (KPIs):** organic search traffic, time on page, roadmap/quiz completions, newsletter sign-ups, return visitors, resource downloads.

---

## 2. Target audience: personas

| Persona | Profile | Needs | Key pages |
|---|---|---|---|
| **1. Ananya, 17, PU student, Mysuru** | Loves drawing and anime; Kannada + English; mid-range Android phone; worried about career choice | "Is this a real career? Where do I study? How much will it cost?" | What is 3D, Careers, Courses, FAQ, Roadmap |
| **2. Ravi, 45, parent, Hubballi** | Government employee; prefers Kannada; values stability and degrees | "Is it safe? What salary? Which college is genuine?" | For Parents, Salaries, Realities, College checklist (Kannada) |
| **3. Imran, 21, B.Com graduate, Bengaluru** | Wants to switch careers; has a laptop | "Can I learn without a degree? Fastest path to a job?" | Roadmap, Free tools, Bengaluru studios |
| **4. Deepa, 26, junior compositor, Bengaluru** | Ex-Technicolor; upskilling | "What's next? AI? Houdini? Unreal?" | Trends, Careers (technical), Events |
| **5. Arjun, 14, school student** | Plays games, curious | "How are games and cartoons made?" | Pipeline scroll-story, Interactive 3D demos |
| **6. Educators / colleges / studios** | Looking for talent or visibility | Directory, events, partnerships | Directory, Contact |

**Audience realities in India (design implications)**
- **Mobile-first**: most traffic will come from Android phones, often mid/low-end, on 4G. Design for **360–414 px width first**.
- **Data sensitivity**: keep page weight low and lazy-load 3D/video. Provide a **"Lite mode"** toggle.
- **Multilingual**: **English (default) + Kannada (ಕನ್ನಡ) + Hindi (हिन्दी)**.
- **Trust matters**: parents look for credible sources, so cite them and show "last updated" dates.
- **WhatsApp sharing** is the main viral channel: add share buttons and good Open Graph previews.

---

## 3. Information architecture: sitemap

```
Home
├── Learn
│   ├── What is 3D Animation?            (01)
│   ├── How It's Made: Pipeline          (03)  ← signature scroll-story
│   ├── 12 Principles of Animation       (03)
│   ├── History & Timeline               (02)
│   └── Glossary                         (12)
├── Tools
│   ├── Software Guide                   (04)
│   └── PC / Laptop Builder (INR)        (04)
├── Courses & Colleges
│   ├── Course Types                     (07)
│   ├── College Finder (Karnataka + India) (07)
│   ├── Entrance Exams                   (07)
│   └── Scholarships & Loans             (07)
├── Careers
│   ├── Career Explorer (roles)          (08)
│   ├── Salaries in India                (08)
│   └── "Which Role Suits Me?" quiz      (08)
├── India Industry
│   ├── Industry Overview & Stats        (05)
│   ├── Studio Directory                 (05, 06)
│   └── Made in India Showcase           (09)
├── Karnataka Hub ★                      (06)
│   ├── AVGC-XR Policy Explained
│   ├── Bengaluru GAFX & Events
│   ├── Karnataka Map (studios, colleges, CoE)
│   └── Karnataka Stories in 3D
├── Start Learning                       (11)
│   ├── Roadmap (interactive)
│   ├── Your First 3D Project (tutorial)
│   └── Resource Library
├── Future & Trends / Blog               (10)
├── For Parents                          (08 realities, 13 FAQ)
├── FAQ                                  (13)
└── About / Contact / References         (15)
```

**Main navigation (mobile):** Learn · Courses · Careers · Karnataka · Start. Use a hamburger menu for the rest.

---

## 4. Home page wireframe (top to bottom)

1. **Hero:** an interactive 3D model (a **Channapatna-toy-style character** or a **Yakshagana head** that rotates on drag), with the headline *"Bring Stories to Life in 3D"* and Kannada/Hindi sub-headlines. CTAs: **Start Learning (Free)** | **Explore Careers**.
2. **"What is 3D animation?"**: a 3-line explanation plus a 20-second looping pipeline video.
3. **Stats strip:** ₹2.78 trillion M&E (2025) · ₹326 crore *Mahavatar Narsimha* · First state AVGC policy: Karnataka (2012) · ₹0 to start with Blender.
4. **Where is 3D used?**: icon grid.
5. **Pipeline teaser**: links to the scroll-story.
6. **Made in India**: carousel (*Mahavatar Narsimha*, *Chhota Bheem*, *The Legend of Hanuman*, *Baahubali* VFX).
7. **Karnataka Hub teaser**: map illustration plus GAFX next dates.
8. **Careers and salaries teaser**: role cards.
9. **Find a course**: quick filter (city + budget).
10. **FAQ preview** (5 questions).
11. **Newsletter / WhatsApp channel** sign-up (DPDP-compliant consent).
12. **Footer**: sitemap, language switch, references, last updated.

---

## 5. Visual design direction

### Concept: *"Karnataka Craft meets Digital 3D"*
Blend **traditional Karnataka visual heritage** with **modern 3D/tech aesthetics**.

### Colour palette (inspired by Channapatna lacquer toys, Mysuru silk and gold)
| Role | Colour | Hex (proposal) |
|---|---|---|
| Primary | Channapatna Red | `#C8102E` |
| Secondary | Mysuru Silk Gold / Turmeric | `#E0A526` |
| Accent | Lacquer Green | `#1E8C5A` |
| Accent 2 | Peacock / Royal Blue | `#1F4E9C` |
| Dark background | Deep Ink (for 3D showcase sections) | `#0E1116` |
| Light background | Warm ivory (sandalwood) | `#FBF7F0` |
| Text | Charcoal | `#1D1D1F` |

*Karnataka's flag colours are red and yellow (ಕೆಂಪು–ಹಳದಿ). Using red + gold as the primary pair creates a subtle local identity.* Check contrast (WCAG AA) on all combinations.

### Typography
- **Headings (Latin):** a geometric/grotesk display face, e.g. *Poppins* (designed by Indian Type Foundry) or *Space Grotesk*.
- **Body (Latin):** *Inter* or *Noto Sans*.
- **Kannada:** **Noto Sans Kannada**, *Baloo Tamma 2* (friendly, from Ek Type, an Indian foundry) or *Hind* family support.
- **Hindi (Devanagari):** *Noto Sans Devanagari*, *Mukta* or *Baloo 2*.
- All are available on Google Fonts. Subset fonts to reduce load.

### Imagery and motifs
- Low-poly / stylised 3D renders of **Channapatna toys, Yakshagana crowns, Mysuru Dasara elephants, the Hampi stone chariot, auto-rickshaws, filter-coffee tumblers**
- **Wireframe → render** transitions as a recurring visual motif
- Subtle **rangoli / kolam geometric patterns** as section dividers
- Real photos of Indian students and studios (licensed / original)

### Tone of voice
- Friendly, encouraging, honest. Talk like a helpful senior ("anna/akka") rather than a salesman.
- Simple English (Class 8–10 reading level); avoid unexplained jargon and link terms to the glossary.
- Never promise jobs or salaries; always say "approximately" and cite sources.

---

## 6. Key interactive features

| Feature | Description | Tech |
|---|---|---|
| **3D hero model** | Rotatable, lightweight (<2 MB GLB, Draco/Meshopt compressed) | `<model-viewer>` or Three.js / React Three Fiber |
| **Pipeline scroll-story** | One model morphs through wireframe → clay → textured → rigged → lit → final | GSAP ScrollTrigger + Three.js, or pre-rendered image sequence for low-end devices |
| **12 Principles demos** | Short looping clips per principle | WebM/MP4 (muted, lazy-loaded) or Lottie |
| **College finder** | Filter by city, type, fees, course | JSON data + client-side filtering |
| **Career quiz** | 8–10 questions → suggested roles | Simple JS logic |
| **PC builder** | Choose budget → recommended specs | JSON + UI |
| **Interactive roadmap** | Checklist with progress saved in localStorage | JS |
| **Karnataka map** | Clickable SVG map of Karnataka with pins | SVG + JS |
| **Timeline** | Horizontal, World vs India tracks | CSS scroll-snap + JS |
| **Language switch** | EN / ಕನ್ನಡ / हिन्दी | i18n JSON files; `lang` attribute per page |
| **Lite mode** | Disables 3D and video for slow networks | `prefers-reduced-motion`, `navigator.connection` and a manual toggle |

---

## 7. SEO strategy (India-focused)

### Target keywords (examples)
| Intent | English keywords | Kannada / Hindi keywords |
|---|---|---|
| Informational | what is 3D animation, 3D animation pipeline, 12 principles of animation, 2D vs 3D animation | 3D ಅನಿಮೇಷನ್ ಎಂದರೇನು, 3D एनिमेशन क्या है |
| Education | 3D animation course in Bangalore, animation colleges in Karnataka, animation course fees in India, animation course after 12th, best animation institute in Bangalore, NID DAT preparation, UCEED animation | ಅನಿಮೇಷನ್ ಕೋರ್ಸ್ ಬೆಂಗಳೂರು, एनिमेशन कोर्स फीस |
| Career | 3D animator salary in India, animation jobs in Bangalore, VFX jobs for freshers, is animation a good career in India | ಅನಿಮೇಷನ್ ಉದ್ಯೋಗ, एनिमेशन में करियर |
| Tools | Blender tutorial for beginners, best laptop for 3D animation under 1 lakh, Maya vs Blender | Blender ಕಲಿಯಿರಿ, Blender सीखें |
| News / trend | Mahavatar Narsimha box office, Indian animated movies list, Karnataka AVGC policy, Bengaluru GAFX 2027 | — |

### On-page and technical SEO
- One topic per page; descriptive URLs (`/courses/animation-colleges-karnataka`)
- Unique `<title>` and meta description per page; Open Graph and Twitter cards (for WhatsApp previews)
- **Structured data (JSON-LD):** `FAQPage`, `Course`, `EducationalOrganization`, `Event` (GAFX), `Article`, `BreadcrumbList`, `Movie` (showcase)
- **hreflang** tags for `en-IN`, `kn-IN` and `hi-IN`
- XML sitemap and robots.txt; Google Search Console setup
- **Core Web Vitals:** LCP < 2.5s on 4G, CLS < 0.1, INP < 200ms
- Image formats: **AVIF/WebP** with responsive `srcset`; lazy-loading
- Internal linking between related pages and the glossary
- Fresh content: monthly blog posts (trends, events, new Indian releases)

### Content marketing
- YouTube Shorts / Instagram Reels showing the "wireframe to final" transformations
- WhatsApp Channel for updates (exam dates, GAFX, scholarships)
- Partnerships with Karnataka colleges and student clubs

---

## 8. Technical recommendations

| Area | Recommendation |
|---|---|
| **Framework** | **Astro** (static, fast, partial hydration, ideal for content sites) or **Next.js** (if dynamic features grow). For a simple first version, plain **HTML + CSS + vanilla JS** is fine |
| **Styling** | Tailwind CSS or modern CSS (custom properties, container queries) |
| **3D** | `<model-viewer>` (simplest, AR-ready on Android) and/or **Three.js / React Three Fiber** for custom scenes |
| **Animation** | GSAP (ScrollTrigger), CSS animations, Lottie |
| **3D assets** | **glTF/GLB**, Draco or Meshopt compressed, KTX2/Basis textures, < 2–3 MB per model |
| **Content** | Markdown/MDX files (these Docs can be the source) or a headless CMS (Decap, Sanity, Strapi) for non-developers to update fees and events |
| **Data** | JSON files for colleges, studios, events and software (easy to update) |
| **i18n** | Astro i18n routing / next-intl; translations reviewed by native Kannada and Hindi speakers (not just machine-translated) |
| **Hosting** | Vercel / Netlify / Cloudflare Pages (with Indian edge locations: Mumbai, Chennai, Bengaluru, Delhi) |
| **Analytics** | Privacy-friendly (Plausible / Umami) or GA4 with consent |
| **Forms** | Newsletter / contact with explicit consent |
| **Search** | Pagefind (static search) or Algolia |

### Performance budget (mobile, 4G)
| Asset | Budget |
|---|---|
| Initial HTML + CSS + JS | < 200 KB (gzipped) |
| Hero image / poster | < 150 KB |
| 3D model (lazy) | < 2.5 MB, loaded after first paint / on interaction |
| Fonts | < 100 KB (subset, `font-display: swap`) |
| Videos | Lazy, poster image first, no autoplay on cellular in Lite mode |

### Accessibility (WCAG 2.2 AA)
- Colour contrast ≥ 4.5:1 for text
- Keyboard navigable; visible focus states
- Alt text for all images; captions/transcripts for videos
- Respect `prefers-reduced-motion` (disable scroll-jacking and auto-rotation)
- Provide text alternatives for 3D content
- Proper `lang` attributes for Kannada and Hindi text

---

## 9. Legal and compliance (India)

| Area | Requirement |
|---|---|
| **DPDP Act, 2023** (Digital Personal Data Protection) | Clear consent notice for any personal data (newsletter, forms); purpose limitation; easy withdrawal; privacy policy |
| **IT Act, 2000 / IT Rules 2021** | Grievance officer contact if user-generated content is allowed |
| **Copyright** | Use only licensed images and posters; embed official trailers; credit studios; don't host copyrighted film clips |
| **Trademarks** | Software and studio names are trademarks; use them descriptively, without implying endorsement |
| **Accuracy disclaimers** | "Fees/salaries are indicative; verify with official sources"; show "last updated" dates |
| **Cookie consent** | Required if using non-essential cookies / tracking |
| **Affiliate disclosures** | If linking to paid courses with affiliate codes |

---

## 10. Content maintenance plan

| Content | Update frequency | Owner |
|---|---|---|
| Fees, entrance exam dates | Every admission cycle (Oct–Jan) | Content team |
| Salaries | Annually | Content team |
| Software versions and prices | Every 6 months | Tech content |
| Studio directory | Quarterly (verify status) | Research |
| Events (GAFX, Tech Summit, WAVES) | As announced | Content |
| Industry stats (FICCI-EY) | Annually (report released ~March) | Research |
| Blog / trends | Monthly | Writers |
| Showcase (new Indian releases) | As released | Content |

---

## 11. Phased build plan (suggested)

| Phase | Scope |
|---|---|
| **Phase 1: MVP** | Home, What is 3D, Pipeline (simple version), Careers & Salaries, Courses (static list), Karnataka Hub, FAQ, Glossary. English only. Responsive and fast |
| **Phase 2** | Interactive 3D hero, scroll-story, college finder with filters, career quiz, Kannada version |
| **Phase 3** | Hindi version, blog, roadmap tracker, PC builder, Karnataka map, newsletter |
| **Phase 4** | Community features (student showcase gallery), partnerships, event calendar integration, AR heritage demos |

---

## 12. Content gaps to fill with original work (differentiators)

1. **Kannada-language explainer content**: very little exists today.
2. **Honest, sourced salary and fee data** for Karnataka specifically.
3. **Karnataka heritage in 3D**: original 3D models (Channapatna toys, the Hampi chariot) as interactive showcases.
4. **"How Mahavatar Narsimha was made"**: a case study (with permission/interviews if possible).
5. **Student success stories** from Karnataka colleges.
6. **Parent-focused guide** in Kannada.
