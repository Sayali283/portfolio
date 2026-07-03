# Sayali Ingole — Portfolio

My personal portfolio website — built to showcase my projects, internship experience, and skills as I look for entry-level roles in AI/ML engineering, Python development, and full-stack development.

🔗 **Live site:** _add your deployed URL here once live_

---

## About

I'm a final-year BCA student at Sant Gadge Baba Amravati University (graduating May 2026), with hands-on experience across AI/ML, full-stack Java, and UI/UX through three internships. My flagship project, **SmartHire**, is a recruitment platform that automates resume screening using Python and NLP, cutting manual screening time by roughly 70%.

## Features

- **Single-page app feel, zero build tools** — pure HTML/CSS/JS with client-side hash routing across Home, About, Experience, Projects, Skills, and Contact
- **Animated neural-network canvas background** — subtle, on-theme for an AI/ML portfolio
- **Terminal-style hero animation** — typewriter effect introducing my stack
- **Glassmorphism UI** with a dark, techy cyan/violet color palette
- **Working contact form** — submits via [Formspree](https://formspree.io), with an automatic `mailto:` fallback if Formspree isn't configured yet
- **Downloadable resume** — linked directly from the nav and hero
- Fully responsive, with a mobile nav drawer and `prefers-reduced-motion` support

## Tech Stack

- HTML5 / CSS3 (custom properties, no framework)
- Vanilla JavaScript (routing, canvas animation, form handling)
- [Formspree](https://formspree.io) for contact form email delivery
- Fonts: Space Grotesk, Inter, JetBrains Mono (Google Fonts)

## Project Structure

```
portfolio/
├── index.html                  # Main site (rename from portfolio.html)
└── Sayali_Ingole_Resume.pdf    # Downloadable resume
```

## Running Locally

No build step needed — just open `index.html` in a browser, or serve it locally:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Deployed as a static site. Any static host works — GitHub Pages, Netlify, or Vercel.

**GitHub Pages:**
1. Push `index.html` and `Sayali_Ingole_Resume.pdf` to this repo
2. Settings → Pages → Deploy from branch `main`, folder `/root`
3. Live at `https://sayali283.github.io/portfolio/`

## Contact Form Setup

The form posts to Formspree. To enable email delivery:
1. Create a free form at [formspree.io](https://formspree.io)
2. Replace `YOUR_FORM_ID` in the `<script>` section of `index.html` with your Formspree form ID

If Formspree isn't configured, the form still saves the message and falls back to opening the visitor's email client, addressed to me directly.

## Sections

| Section | Highlights |
|---|---|
| **About** | Education, certifications, soft skills |
| **Experience** | Full Stack Java Intern (Upskill Campus), AI/ML Intern (Interns Studio), UI/UX Intern (Tamizhan Skills) |
| **Projects** | SmartHire, Face Recognition System, Banking Information System, CafeClick |
| **Skills** | Python, Java, Flask, MySQL/SQLite, OpenCV, NumPy, Pandas, Git |

## Contact

- Email: ingolesayali283@gmail.com
- LinkedIn: [linkedin.com/in/sayali-ingole-bb0ab3295](https://www.linkedin.com/in/sayali-ingole-bb0ab3295)
- GitHub: [github.com/Sayali283](https://github.com/Sayali283)

---

© 2026 Sayali Ingole
