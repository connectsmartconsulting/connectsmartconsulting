# Connect Smart Consulting Inc. — Website

Official marketing website for **Connect Smart Consulting Inc.**, a Canadian consultancy delivering integrated AI governance, cybersecurity validation, and quality engineering assurance for SMEs.

🌐 **Live site:** [www.connectsmartconsulting.com](https://www.connectsmartconsulting.com)

---

## About the Company

Connect Smart Consulting Inc. helps Canadian SMEs operationalize AI governance with fixed-price, audit-ready frameworks aligned to:

- Ontario Bill 194 (Responsible AI and Data Act)
- EU AI Act
- NIST AI Risk Management Framework
- ISO/IEC 42001

Founded in 2023 by Safiuddin Mohammed Ahmed, drawing on 18+ years of QA, DevSecOps, and cybersecurity leadership experience.

📍 25 Bayshore Drive, Nepean, Ontario, Canada K2B 6M7
✉️ safiuddin@connectsmartconsulting.com
📞 +1 (343) 988-2427
🔗 [LinkedIn](https://www.linkedin.com/company/connect-smart-consulting)

---

## Tech Stack

This is a static, single-page website — intentionally lightweight and fast.

- **HTML5** with semantic markup (`<main>`, `<nav>`, `<section>`, `<footer>`)
- **CSS3** custom properties (palette derived from logo)
- **Vanilla JavaScript** (no framework dependencies)
- **Fonts:** Syne (display) + DM Sans (body), loaded from Google Fonts
- **SEO:** Open Graph, Twitter Cards, JSON-LD (Organization, ProfessionalService, Person, WebSite schema)

---

## Repository Structure

```
.
├── index.html              # Main site (single-file, all CSS/JS inline)
├── sitemap.xml             # XML sitemap for search engines
├── robots.txt              # Crawler directives
├── site.webmanifest        # PWA manifest
├── favicon.ico             # Multi-size favicon
├── favicon-16.png          # 16x16 favicon
├── favicon-32.png          # 32x32 favicon
├── apple-touch-icon.png    # 180x180 iOS home-screen icon
├── android-chrome-192.png  # 192x192 Android icon
├── android-chrome-512.png  # 512x512 Android icon
├── logo.png                # 300x300 brand logo (used in JSON-LD)
├── og-image.png            # 1200x630 social preview image
├── CNAME                   # GitHub Pages custom domain config
└── README.md               # This file
```

---

## Deployment

Hosted on **GitHub Pages** with a custom domain managed through Squarespace Domains.

### DNS Configuration

| Type | Host | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | `connectsmartconsulting.github.io` |

Email (Google Workspace) is routed via separate MX records and is unaffected by website hosting.

### Local Preview

To view the site locally:

```bash
# Clone the repo
git clone https://github.com/connectsmartconsulting/connectsmartconsulting.git
cd connectsmartconsulting

# Open directly in a browser
open index.html

# Or run a simple local server (Python 3)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

## License & Usage

© 2023–2026 Connect Smart Consulting Inc. All rights reserved.

Source code and brand assets in this repository are proprietary to Connect Smart Consulting Inc. The repository is public for transparency and deployment purposes only. Reuse, redistribution, or adaptation of the design, copy, or branding requires written permission.

---

## Contact

For business inquiries, partnership opportunities, or AI governance consultations:

- **Email:** safiuddin@connectsmartconsulting.com
- **Phone:** +1 (343) 988-2427
- **LinkedIn:** [connect-smart-consulting](https://www.linkedin.com/company/connect-smart-consulting)
