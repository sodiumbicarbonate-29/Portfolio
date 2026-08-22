# Personal Portfolio — Dinnesh Nicole Manondo

A personal portfolio website presenting the developer, showcasing completed projects, listing
certifications, and providing a way to get in touch.

## Live site

**[portfolio-theta-one-et1co7iaq0.vercel.app](https://portfolio-theta-one-et1co7iaq0.vercel.app/)** — deployed on Vercel.

## Sections

- **Home / About** — name, photo, and a short bio. The photo is presented on an ID badge suspended
  from a lanyard that can be dragged and flipped, alongside résumé and business card downloads.
- **Skills** — the tech stack laid out as a 3D mechanical keyboard. Each keycap represents a
  technology; pressing one displays its name and plays a key click.
- **Projects** — six projects (SlowMail, Schedule Maker, Theosis, Screenly, The Obscured Index, and
  VELA) arranged as icons on a desktop. Icons can be dragged, and clicking one opens a full window
  with a screenshot, description, technologies used, and a link to the live site.
- **Certifications** — expandable cards containing the certificates.
- **Contact** — email, phone, and LinkedIn, plus a message form.

## Features

- Responsive layout for mobile and desktop
- Dark mode toggle that saves the preference between visits
- Intro animation with a scrambling headline and typewriter text
- Hover effects, drag interactions, and expand animations throughout
- Contact form with client-side validation and a confirmation message

## Built with

- HTML5 and CSS3 (custom properties, Grid, Flexbox, keyframe animations)
- Vanilla JavaScript — no frameworks. Pointer events handle dragging, `requestAnimationFrame` drives
  the lanyard physics, and the Web Audio API generates the keyboard sounds.
- Google Fonts: Space Grotesk, IBM Plex Mono, Playfair Display, Jost, Roboto Condensed
- Simple Icons for the technology logos

## Access
Vercel: 
https://portfolio-theta-one-et1co7iaq0.vercel.app/

GitHub Repository:
https://github.com/sodiumbicarbonate-29/Portfolio

## Files

```
├── index.html          # the whole site — markup, styles, and scripts
├── support.js          # runtime helper
├── README.md
└── assets/             # photo, project logos and screenshots, certificates, résumé
```

## Note on the contact form

The form is front-end only. It validates that all fields are filled and that the email is
well-formed, then displays a confirmation message; no email is sent or stored.

## Contact

dinneshmanondo@gmail.com · +63 915 016 9086 · Cebu City, Philippines
[LinkedIn](https://www.linkedin.com/in/dinnesh-nicole-manondo-804982274)
