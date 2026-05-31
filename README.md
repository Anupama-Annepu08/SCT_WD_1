# 🌅 WanderLux — Luxury Travel Landing Page

A fully responsive, single-page travel website built with pure HTML, CSS, and Vanilla JavaScript. No frameworks, no dependencies — just clean, modern front-end code.


## 🚀 Live Demo

> Open `index.html` directly in any browser — no build step required.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (Custom Properties, Grid, Flexbox, Animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Playfair Display, DM Sans |
| Images | picsum.photos (placeholder), pravatar.cc (avatars) |


## 📁 Project Structure

wanderlux/
└── index.html       # Entire project — HTML + CSS + JS in one file

## ✨ Features

- **Sticky Navbar** — transparent on load, frosted glass on scroll; hamburger menu on mobile
- **Animated Hero** — search bar, CTA buttons, scroll hint, drifting cloud SVGs, parallax background
- **Destination Cards** — 8 destinations (Santorini, Bali, Maldives, Paris, Swiss Alps, Amalfi, Dubai, Kyoto) with wishlist heart toggle
- **Destination Modal** — click any card to open a full detail panel with hero image, photo grid, and highlights
- **Features Section** — 6 service cards with glassmorphism styling
- **Photo Gallery** — CSS masonry grid layout (12-column)
- **Testimonials Carousel** — infinite auto-scroll marquee, pauses on hover
- **Bucket List Experiences** — 6 experience cards with overlay badges
- **Seasonal Guide** — tabbed panel for Spring / Summer / Autumn / Winter destinations
- **Travel Style Quiz** — 4-question personality quiz with dynamic results
- **World Regions** — 6 region cards covering Europe, Asia, Africa, Americas, Oceania, Middle East
- **Newsletter Form** — email validation + toast confirmation
- **Contact Form** — name/email/destination/message with client-side validation
- **Scroll Reveal** — IntersectionObserver fade-in for all cards and sections
- **Toast Notifications** — global feedback system for all interactions

---

## 🎨 Design System

```css
--gold:        #c8860a
--gold-light:  #d99a2a
--gold-pale:   #f0c060
--amber:       #b06a05
--text-dark:   #2c1a00
--text-body:   #4a3010
--glass-bg:    rgba(255, 252, 242, 0.70)
```

**Fonts:**
- Headings → `Playfair Display` (600 / 800, italic variants)
- Body → `DM Sans` (300 – 700)

---

## 📐 Responsive Breakpoints

| Breakpoint | Layout Changes |
|------------|---------------|
| `≤ 900px` | 2-col destination grid, simplified gallery, 2-col modal photos |
| `≤ 768px` | Hamburger nav, single-col features, stacked about section |
| `≤ 560px` | Stacked hero search, single-col gallery, single-col modal highlights |

---

## 🗂️ Sections Overview

| # | Section ID | Description |
|---|-----------|-------------|
| 1 | `#home` | Hero with search |
| 2 | `#about` | Stats + brand story |
| 3 | `#destinations` | 8 destination cards + modal |
| 4 | `#features` | 6 service feature cards |
| 5 | `#gallery` | Masonry photo grid |
| 6 | `#testimonials` | Auto-scrolling reviews |
| 7 | `#experiences` | Bucket list cards |
| 8 | `#seasonal` | Seasonal travel guide tabs |
| 9 | `#quiz` | Travel personality quiz |
| 10 | `#worldmap` | 6 world region cards |
| 11 | `#newsletter` | Email subscription |
| 12 | `#contact` | Enquiry / booking form |

---

## ⚙️ How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/wanderlux.git

# Open in browser
cd wanderlux
open index.html
```

No npm, no build tools, no config — it just works.

---

## 🔧 Customisation

**Swap placeholder images** — replace all `picsum.photos` URLs with real image paths:
```html
<img src="https://picsum.photos/seed/santorini-wl/400/600" alt="Santorini"/>
<!-- becomes -->
<img src="./assets/images/santorini.jpg" alt="Santorini"/>
```

**Add a destination** — append a new entry to the `destData` object in the `<script>` block and add a matching `.dest-card` in the HTML.

**Change the colour palette** — edit the `:root` CSS variables at the top of the `<style>` block.

**Connect the contact form** — replace the `handleSubmit()` function body with a `fetch()` POST to your backend or a service like Formspree / EmailJS.

---

## 📄 License

MIT — free to use, modify, and distribute.

---

## 🙌 Credits

- Fonts — [Google Fonts](https://fonts.google.com)
- Placeholder images — [picsum.photos](https://picsum.photos)
- Avatar images — [pravatar.cc](https://pravatar.cc)
