# Astha Jain — Portfolio

Personal portfolio website for Data Analyst, Business Analyst, BI Analyst, and Product Analyst roles.

## Structure

portfolio_v3/
├── index.html ← Main page (all content)
├── assets/
│ ├── css/
│ │ └── styles.css ← All styles, tokens, responsive rules
│ ├── js/
│ │ └── script.js ← Scroll, parallax, reveal animations
│ └── images/
│ ├── hero.png ← Hero section photo
│ ├── about.png ← About section photo
│ ├── polaroid_palace.png ← Polaroid 1
│ ├── polaroid_stairs.png ← Polaroid 2
│ ├── polaroid_chandelier.png ← Polaroid 3
│ ├── polaroid_night.png ← Polaroid 4
│ ├── project_booknook_dash.png
│ ├── project_booknook_library.png
│ ├── project_bingebling_main.png
│ ├── project_bingebling_universe.png
│ ├── project_brew_sales.png
│ ├── project_brew_mgmt.png
│ ├── work_market_intel.png
│ ├── work_business_case.png
│ ├── work_consumer.png
│ └── work_leo_pharma.png
└── README.md

## Deploy on Netlify

**Option A — Drag & Drop (no account needed, 2 min)**
1. Go to [drop.netlify.com](https://drop.netlify.com)
2. Drag the entire `portfolio_v3/` folder onto the page
3. Get a live URL instantly (e.g. `random-name.netlify.app`)
4. Rename it: Site settings → Change site name → `asthajain`

**Option B — Netlify account (recommended for long term)**
1. Sign up free at [netlify.com](https://netlify.com)
2. Sites → Add new site → Deploy manually
3. Drag the `portfolio_v3/` folder in
4. Update anytime by re-dragging a new folder

**Option C — GitHub + Netlify (best for maintenance)**
1. Push this folder to a GitHub repo
2. Connect the repo on Netlify → auto-deploys on every push

## Add your resume

Drop your resume PDF into the root folder as `resume.pdf`, then update the Download Resume button in `index.html`:

```html
<a href="resume.pdf" download class="btn btn-ghost">Download Resume</a>
```

## Updating content

| What to change | File | What to look for |
|---|---|---|
| Hero text / tagline | `index.html` | `#hero` section |
| About copy | `index.html` | `#about` section |
| Add a new project | `index.html` | Copy a `.project-featured` block |
| Add experience | `index.html` | Copy an `.exp-card` block |
| Add a certification | `index.html` | Copy a `.cert-card` block |
| Replace a photo | `assets/images/` | Swap the file, keep same filename |
| Colors / fonts | `assets/css/styles.css` | `:root` variables at the top |
| Animations | `assets/js/script.js` | Scroll handler and IntersectionObserver |
| Update project links | `index.html` | `href` on `.proj-link` buttons |

## Design tokens (styles.css)

```css
:root {
  --navy:  #0a0e1a;   /* dark backgrounds */
  --navy2: #111827;   /* footer */
  --cream: #f5f0e8;   /* page background */
  --accent:#4a7fb5;   /* blue accent */
  --gold:  #c4a882;   /* gold highlight */
  --text:  #1a1a2e;
  --muted: #6b7280;
  --border:#e2ddd5;
}
```

## Tech stack

Vanilla HTML · CSS · JavaScript — no build step, no dependencies, no Node required.
Fonts load from Google Fonts CDN (requires internet connection for visitors).

## Contact

- Email: asthajain2092@gmail.com
- LinkedIn: [linkedin.com/in/astha-jain-284127282](https://www.linkedin.com/in/astha-jain-284127282)
- GitHub: [github.com/Astha20902](https://github.com/Astha20902)
- Instagram: [@astha_jain_20](https://www.instagram.com/astha_jain_20)
