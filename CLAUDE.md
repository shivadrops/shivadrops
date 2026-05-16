# ShivaDrops — Project Brief

## Target Audience — CRITICAL FRAMING
**The website is for retreat facilitators and event organizers who want to HIRE Pedro.**
- Primary visitors: yoga teachers, wellness center operators, retreat organizers, event planners — people who run their own retreats and are looking for a holistic chef/facilitator to bring in
- Secondary visitors: private individuals wanting a personalized session or bespoke event (e.g., private yoga, breathwork, or nutrition coaching)
- NOT for retreat participants looking to attend a retreat where Pedro happens to work
- Tone must speak to the decision-maker who is evaluating Pedro as a professional service provider — position him as an expert they bring in, not as a retreat host they sign up with
- Think: "hire a caterer / specialist for your event" not "join our retreat"

---

## The Person
**Pedro Miguel Ormaechea Riera** — founder of ShivaDrops.
- Natural and holistic cook, conscious nutrition coach, yoga teacher, and breathwork facilitator
- Based in **Punta del Este, Uruguay** — available for retreats and events worldwide
- Describes his work as "vibrational alchemy" rooted in genuine goodness
- Philosophy: food as medicine, body-mind-spirit connection, Ayurvedic science, connection to Pachamama (Mother Earth)
- Tagline: *"al andar se hace el camino"* — the path is made by walking
- Contact: shivadropsu@gmail.com | Instagram: @shivadrops | Facebook: pormariera

## The Brand
- **Name**: ShivaDrops
- **Logo**: Water drop containing the Flower of Life (sacred geometry) — represents purity, spiritual nourishment, the sacred in the everyday
- **Colors**: Deep navy blue, warm gold/amber, cream/off-white
- **Language**: Bilingual — Spanish default, English toggle via flag icons in corner
- **Tone**: Spiritual, grounded, holistic wellness — warm and personal, but also professional enough to win trust from a retreat organizer or event planner evaluating Pedro as a hire

## Site Structure

### Pages / Files
| File | Page | Description |
|------|------|-------------|
| `index.html` | **Landing (Splash)** | Entry page — logo, brand description, "Ingresar" button → goes to `home.html` |
| `home.html` | **Home** | What ShivaDrops is — brand intro, Pedro's story, philosophy; speaks to facilitators/organizers considering him as a hire |
| `servicios.html` | **Servicios** | The 4 services Pedro offers to retreats/events — framed as "what I bring to your retreat" |
| `recetas.html` | **Menús** | Sample menus for different retreat types — positions Pedro as a top culinary expert that organizers want for their event |
| `reservas.html` | **Reservas** | Booking system — calendar, service selector, form → WhatsApp; used by organizers or private clients to request Pedro |
| `productos.html` | **Productos** | Shop — recipe books, courses, physical products |
| `descargas.html` | **Descargas** | Free digital downloads |
| `contacto.html` | **Contacto** | Pedro's contact information |

### Navigation Menu (all pages except landing)
Home · Servicios · Menús · Reservas · Productos · Descargas · Contacto
+ Language toggle flag (ES / EN) in corner

---

## Services (Servicios page)
Four services Pedro offers — framed as what he brings TO a retreat or event, or to a private client:

1. **Cocinero Holístico** — Holistic chef for private retreats and events (the primary service; most retreat organizers hire him for this)
2. **Coach de Alimentación Consciente** — Conscious nutrition coaching (can be a standalone session or integrated into a retreat program)
3. **Facilitador de Breathwork** — Rebirthing Breathwork sessions (offered as an add-on to retreats or standalone for private clients)
4. **Instructor de Yoga** — Yoga sessions, individual and group (can be included in a retreat program or booked privately)

Pedro can be hired for ONE service or a combination — make this flexibility clear on the site.

---

## Reservas (Booking) — Full Flow
The booking page is used by retreat organizers or private clients who want to hire Pedro. Copy should acknowledge this — e.g., "¿Querés sumar a Pedro a tu retiro o evento?" (Want to bring Pedro into your retreat or event?).

1. **Description** — short text explaining how the booking process works; written for someone hiring a professional, not signing up for a class
2. **Calendar** — shows already-booked days as unavailable; user picks a start date and end date (system shows how many days it lasts)
3. **Service selector** — dropdown or cards to choose one or more of the 4 services above
4. **Personal data form** — name, contact info, event/retreat details (type of event, expected number of participants, location, etc.)
5. **"Consultar / Reservar" button** — sends the entire form to Pedro via **WhatsApp** (wa.me link with pre-filled message); Pedro closes the sale manually

---

## Productos Page
Sells:
- Recetarios (recipe books — digital or physical)
- Cursos (online courses)
- Productos físicos (physical products — TBD)
- Other digital products

---

## Descargas Page
Free digital content available for download (PDFs, guides, recipes, etc.)

---

## Logo Assets (`/assets/`)
| File | Description |
|------|-------------|
| `logo.jpg` | **Primary logo** — polished navy + gold on cream |
| `logonew.png` | Clean version, good for light/dark backgrounds |
| `logo_final.png` | Similar to logonew |
| `logov3.jpg` / `logov3.png` | Earlier iteration |
| `final_2.png` | Blue/silver variant |
| `final0.1.png` | Rough hand-drawn sketch version |

**Use `logo.jpg` or `logonew.png` as the canonical logo.**

---

## Design Direction
- Palette: deep navy blue + warm gold/amber + cream/off-white (matches the logo)
- Elegant serif display font + clean body font
- Smooth scroll, subtle reveal animations on scroll
- Fully mobile responsive
- Bilingual: Spanish default, English via flag toggle (JS swaps all text strings)
- Hand-crafted, premium feel — NOT generic wellness template

---

## Tech Stack
- Pure HTML + CSS + vanilla JS
- One `.html` file per page (multi-page site)
- No framework, no build step
- Google Fonts only (no other external CDN)
- WhatsApp integration via `wa.me` pre-filled URL for booking
- Language switching via JS (data attributes storing ES/EN strings)

---

## Build Order
1. [ ] `index.html` — Landing/splash page (logo + description + "Ingresar" button)
2. [ ] `home.html` — Main home page with nav
3. [ ] `servicios.html` — Services page
4. [ ] `reservas.html` — Booking page (calendar + WhatsApp form)
5. [ ] `productos.html` — Shop page
6. [ ] `descargas.html` — Downloads page
7. [ ] `contacto.html` — Contact page
8. [ ] Shared CSS / nav component (duplicated or extracted to `style.css`)
