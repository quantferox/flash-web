<div align="center">

<pre>
███████╗██╗      █████╗ ███████╗██╗  ██╗   █████╗ ███████╗
██╔════╝██║     ██╔══██╗██╔════╝██║  ██║  ██╔══██╗╚══███╔╝
█████╗  ██║     ███████║███████╗███████║  ███████║  ███╔╝ 
██╔══╝  ██║     ██╔══██║╚════██║██╔══██║  ██╔══██║ ███╔╝  
██║     ███████╗██║  ██║███████║██║  ██║  ██║  ██║███████╗
╚═╝     ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝  ╚═╝  ╚═╝╚══════╝
</pre>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![i18n](https://img.shields.io/badge/i18n-AZ_EN_RU-E67E22?style=for-the-badge&logoColor=white)
![license](https://img.shields.io/badge/license-MIT-6C63FF?style=for-the-badge)
![status](https://img.shields.io/badge/status-live-00C896?style=for-the-badge)

<br>

Corporate landing page for **Flash.az** — a US-based warehouse & delivery company.<br>
Vanilla HTML/CSS/JS with locally bundled libs. No frameworks. No build tools. Just open and it works.

</div>

<br>

## Structure

```
flash.az/
├── index.html                  — single-page layout
├── assets/
│   ├── css/
│   │   ├── style.css           — main styles + CSS variables + dark mode tokens
│   │   └── responsive.css      — breakpoints & adaptive layout
│   ├── js/
│   │   ├── script.js           — core interactions & UI logic
│   │   ├── lang-module.js      — i18n dictionary & language switcher
│   │   └── typing-module.js    — typewriter animation
│   ├── img/
│   │   ├── content/            — gallery, header backgrounds, lang flags
│   │   ├── logo/               — Flash logotype
│   │   └── favicon/
│   └── plugins/
│       ├── fontawesome/        — icon set (local, no CDN)
│       └── wow/                — scroll-triggered animations
```

<br>

## Features

- **Multi-language** — full AZ / EN / RU support via a built-in dictionary, zero dependencies
- **Auto dark mode** — switches at 18:00 and reverts at 06:00 based on local time
- **Animated counters** — stats roll up when scrolled into view via `IntersectionObserver`
- **Filterable gallery** — category filter with smooth show/hide transitions + lightbox modal
- **Scroll-aware navbar** — shrinks logo and deepens background on scroll
- **Preloader** — SVG flash bolt fades out on `window.load`
- **Typewriter effect** — cycles through service keywords in the hero section
- **WOW.js animations** — entrance animations tied to scroll position
- **No build step** — pure HTML/CSS/JS, runs straight from the file system

<br>

## Quick Start

```bash
git clone https://github.com/QuantFerox/flash.az-landing.git
cd flash.az
# open index.html in your browser — that's it
```

No `npm install`. No config. No bundler.

<br>

## Sections

| Section | ID | Description |
|---|---|---|
| Header | `#Home` | Hero with typewriter, navbar, contact info |
| About Us | `#AboutUs` | Company overview with animated entrance |
| Service | `#Service` | Animated counters + warehouse/delivery cards |
| Gallery | `#Gallery` | Filterable photo grid with lightbox |
| Contact | `#Contact` | Footer with social links and contact details |

<br>

<div align="center">

---

`⚡ clone` · `🌐 open index.html` · `🚀 done`

---

*Maintained by [QuantFerox](https://github.com/QuantFerox)*

</div>
