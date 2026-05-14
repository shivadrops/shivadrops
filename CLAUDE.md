# ShivaDrops — Project Brief

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
- **Tone**: Spiritual, grounded, holistic wellness — not clinical, warm and personal

## Site Structure

### Pages / Files
| File | Page | Description |
|------|------|-------------|
| `index.html` | **Landing (Splash)** | Entry page — logo, brand description, "Ingresar" button → goes to `home.html` |
| `home.html` | **Home** | What ShivaDrops is — brand intro, Pedro's story, philosophy |
| `servicios.html` | **Servicios** | The 4 services Pedro offers |
| `recetas.html` | **Menús** | Sample menus for different retreat types — positions Pedro as top culinary expert |
| `reservas.html` | **Reservas** | Booking system — calendar, service selector, form → WhatsApp |
| `productos.html` | **Productos** | Shop — recipe books, courses, physical products |
| `descargas.html` | **Descargas** | Free digital downloads |
| `contacto.html` | **Contacto** | Pedro's contact information |

### Navigation Menu (all pages except landing)
Home · Servicios · Menús · Reservas · Productos · Descargas · Contacto
+ Language toggle flag (ES / EN) in corner

---

## Services (Servicios page)
Four services Pedro sells:

1. **Cocinero Holístico** — Retiros y Eventos Privados o Particulares
2. **Coach de Alimentación Consciente** — conscious nutrition coaching
3. **Facilitador de Breathwork** — Rebirthing Breathwork sessions
4. **Instructor de Yoga** — yoga sessions (individual and group)

---

## Reservas (Booking) — Full Flow
1. **Description** — short text explaining how the booking process works
2. **Calendar** — shows already-booked days as unavailable; user picks a start date and end date (system shows how many days it lasts)
3. **Service selector** — dropdown or cards to choose one of the 4 services above
4. **Personal data form** — name, contact info, etc.
5. **"Reservar" button** — sends the entire form to Pedro via **WhatsApp** (wa.me link with pre-filled message); Pedro closes the sale manually

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
