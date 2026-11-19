# TudoCalcula

**Free Brazilian labour calculators** — net salary, 13th salary, vacation pay, severance (rescisão), FGTS and more, calculated with verified accuracy against the official Brazilian tables.

🌐 **Live site:** [tudocalcula.com](https://tudocalcula.com)

## About

TudoCalcula is a free, Portuguese-language web app for Brazilian workers and employers. Every calculator is checked against the official INSS, IRRF and FGTS rules, including the current deduction tables and caps, so the numbers people plan their money around are numbers they can trust.

This repository holds the static-site codebase (v1 line). The production site (v2.0) serves from Hostinger at [tudocalcula.com](https://tudocalcula.com).

## Calculators

- Salário Líquido (net salary)
- Décimo Terceiro Salário (13th salary)
- Férias (vacation pay)
- Rescisão (severance / termination)
- FGTS balance and withdrawal estimates
- Seguro-Desemprego (unemployment benefit)
- PIS/PASEP and additional labour calculations

## Tech Stack

- Pure HTML, CSS and JavaScript — no build step, no framework
- Static hosting (production: Hostinger; this repo's line: GitHub/Cloudflare-compatible)
- SEO-first structure: semantic pages per calculator, sitemap, canonical URLs, Open Graph tags

## Structure

- `index.html` — home page
- One folder per calculator (e.g. `calculadora-salario-liquido/`, `calculadora-decimo-terceiro-salario/`)
- `sobre/`, `contato/`, `privacidade/`, `termos/`, `aviso-legal/` — institutional pages
- `sitemap.xml`, `robots.txt`

## Running Locally

No build is required. Serve the folder with any static server, for example:

```bash
npx serve .
```

## Author

Built and maintained by [Irfan Ullah](https://github.com/irfancodez) — WordPress & WooCommerce Developer; web products for businesses and agencies.
