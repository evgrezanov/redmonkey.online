# redmonkey.online

Personal portfolio & CV site for Evgenii Rezanov — Senior WordPress Developer & Team Lead.

## Live

<https://redmonkey.online>

## Tech Stack

- **HTML** — single-page application (`index.html`)
- **Tailwind CSS** — utility-first styling (CDN)
- **DaisyUI 3.9** — component library with dark/light theme support
- **Devicon** — technology brand icons in the Skills section
- **Google Fonts** — Inter typeface

No build step required — static HTML served as-is.

## Sections

| Section | Description |
|---------|-------------|
| Hero | Introduction with CTA buttons (Telegram, Upwork) |
| About | Expertise and work approach |
| Cases | 6 project case studies with results |
| Skills | Tech stack icons grouped by category (WordPress, Dev, DB, DevOps, Tools) |
| Reviews | Client testimonials carousel |
| Contact | Contact form, social links, and info cards |

## Features

- Dark / Light theme toggle
- RU / EN language switch with full i18n
- Responsive layout (mobile-first)
- Animated elements and hover effects
- SEO meta tags, Open Graph, Twitter Cards

## Local Development

Open `index.html` in a browser, or serve with any static server:

```bash
python3 -m http.server 8080
```

## Project Structure

```
├── index.html              # Main SPA file (HTML + CSS + JS)
├── services/
│   └── remixed-1a47784b.html
└── README.md
```

## Author

**Evgenii Rezanov**
- Telegram: [@ERedmonkey](https://t.me/ERedmonkey)
- GitHub: [evgrezanov](https://github.com/evgrezanov)
