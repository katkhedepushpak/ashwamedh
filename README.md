# ASHWAMEDH'19

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**A Blend of Sport and Cultural Events** — official website for ASHWAMEDH'19, an annual inter-collegiate fest featuring a curated lineup of cultural performances, competitive sports, and miscellaneous events.

## Overview

ASHWAMEDH'19 is a fully static, front-end event website built to serve as the public face of the fest. It provides attendees with a live countdown to the event, a browsable catalogue of competitions across three categories, per-event rule books and contact details surfaced via popup overlays, and a direct link to the external registration platform (eventbeep.com). The site uses particle-based preloader animations and a responsive navigation drawer to deliver an engaging first impression on both desktop and mobile.

## Features

- Animated preloader with particle effects on page entry
- Hero section with event logo, call-to-action register button, and live countdown timer
- Full navigation: Home, Events, Rule Book, Register, Schedule, Sponsors, Team, About
- Three event categories with dedicated popup overlays:
  - **Alive (Cultural):** Hit The Floor (dance), DJ War, Sur Sargam (singing), Treasure Hunt
  - **Sportacus (Sports):** Body Building, Box Cricket, Chess, Football 5-a-side, Kabaddi, Volleyball
  - **Eventive (Miscellaneous):** Pen-it Down (creative writing), Poetry, PUBG Squad
- Per-event details: rules, coordinator contact information, and entry fees
- External registration flow via eventbeep.com

## Tech Stack

- **HTML5** — semantic page structure and popup overlay markup
- **CSS3** — layout, transitions, and responsive styling
- **JavaScript** — countdown timer logic, particle animation, navigation drawer, and overlay interactions

## Getting Started

This is a purely static website with no build step or server-side dependencies.

1. Clone the repository:
   ```bash
   git clone https://github.com/katkhedepushpak/ashwamedh.git
   cd ashwamedh
   ```

2. Open `index.html` directly in any modern browser:
   ```bash
   # macOS
   open index.html

   # Linux
   xdg-open index.html

   # Windows
   start index.html
   ```

   Alternatively, serve the files with any static file server to avoid potential CORS restrictions on local assets:
   ```bash
   # Python 3
   python -m http.server 8080
   # then visit http://localhost:8080
   ```

## Usage

- **index.html** — entry point and landing page; hosts the countdown timer and main navigation
- **event.html** — event catalogue; click any event card to open its rule/contact overlay

No compilation, package installation, or environment variables are required.

## Screenshots

> _Add screenshots of the landing page, event catalogue, and a popup overlay here._

| Landing Page | Event Catalogue | Event Popup |
|---|---|---|
| _(screenshot)_ | _(screenshot)_ | _(screenshot)_ |

## Author

Built by [Pushpak Vijay Katkhede](https://katkhedepushpak.github.io)
