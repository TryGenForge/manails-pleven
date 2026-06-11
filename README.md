# M&A Nails — manails-pleven.com

Статичен сайт-визитка за салон M&A Nails (Миглена Атанасова, Плевен).

## Структура
- `public/index.html` — целият сайт (HTML + CSS + JS в един файл)
- `public/img/` — оптимизирани снимки
- `public/favicon.png`, `public/og.jpg` — иконка и social preview
- `public/sitemap.xml`, `public/robots.txt` — за Google
- `vercel.json` — кеширане на снимки + security headers

## Deploy
Vercel auto-det: framework = "Other", output dir = `public`.
Просто import-ни GitHub repo-то във Vercel → deploy.
