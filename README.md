## SYD ICT Solutions – Corporate Website

A modern, premium-quality multi-page corporate website for **SYD ICT Solutions**, designed to feel comparable to leading tech brands. Built as a static, responsive site using **HTML5**, **Tailwind CSS (CDN)**, and lightweight **vanilla JavaScript** for subtle interactions.

### Tech Stack
- **HTML5** semantic markup
- **Tailwind CSS (via CDN)** + a small `assets/css/custom.css` layer for reusable components
- **Font Awesome** icons
- **Vanilla JavaScript** (`assets/js/main.js`) for:
  - Animated impact counters on the home page
  - Mobile navigation toggle
  - Simple scroll-reveal effects
  - Front-end-only validation for the contact form

### Pages
- `index.html` – Home (hero, who we are, what we do, impact, why we stand out, CTA)
- `about.html` – About (background, purpose, mission, vision, values, timeline)
- `services.html` – Services (detailed service cards, process, CTA)
- `projects.html` – Projects & Portfolio (Bidhaamiye, Haqabtire, Kobciye, Mobile & Web Apps)
- `team.html` – Team (profile cards with roles and bios)
- `blog.html` – Blog & Insights (SEO-ready blog cards)
- `contact.html` – Contact (location, contact details, modern form with validation)

### Running the Site
No build step is required:

1. Open any of the HTML files directly in your browser (e.g. `index.html`).
2. For best results with navigation and relative paths, serve via a simple local server (for example in PowerShell):

```powershell
cd C:\Users\hp\Desktop\myweb
python -m http.server 8000
```

Then visit `http://localhost:8000/index.html` in your browser.

### Customization
- Update content directly in the respective HTML pages.
- Adjust design tokens and component styles in `assets/css/custom.css`.
- Extend or tweak behavior (animations, validation, etc.) in `assets/js/main.js`.


