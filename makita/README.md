# Makita Power Tool Battery Replacement Guide (Australia)

A 5-page static HTML micro-site for GitHub Pages, built to sit alongside the
Dyson guide under `dyson-replacement-battery-guide/makita/`.

## Purpose
1. **Topical authority content** in the style of bestcordlessvacuumguide.com —
   deeply informative, structured guides that answer real buyer questions.
2. **Conversion** — funnel Australian searchers to the relevant replacement
   batteries on **aussiebatt.com** and **battaussie.com**.

## Pages
| File | Topic | Funnel anchor |
|------|-------|---------------|
| `index.html` | Complete Makita battery replacement guide (pillar) | All 4 packs + 6319D/6391D |
| `makita-battery-compatibility-chart.html` | PA12 / PA14 / 1420 / PA18 part-number & model cross-reference (incl. 6319D, 6391D) | Exact product pages |
| `how-to-replace-makita-battery.html` | Pod swap, Ni-MH commissioning, reviving dead packs, troubleshooting | Product pages |
| `makita-battery-runtime-comparison.html` | Ni-Cd 2,000 mAh vs Ni-MH 3,000 mAh across 12V/14.4V/18V | Product pages |
| `makita-battery-care-counterfeit.html` | Memory-effect care, Australian heat storage, spotting fakes | Product pages |

## SEO
- All pages target Australian search intent: `makita battery replacement australia`,
  `makita pa18 / pa14 / pa12 battery`, `makita 6319d / 6391d battery`,
  `ni-mh vs ni-cd makita`, etc. (Bing + Google).
- Each page carries unique `<title>`, `<meta description>`, Open Graph,
  canonical URL, `BreadcrumbList` + `WebSite` JSON-LD, and FAQ schema where relevant.
- Internal links between all 5 pages; every CTA links to a verified, live
  AussieBatt product/category URL (no invented links).

## Brand styling
Colours and typography match aussiebatt.com:
- Navy `#00366C`, secondary `#3B4582`, link `#0033CC`, CTA `#EC4A1E`,
  price red `#FF0000`, light-blue borders `#B6D2FE` / `#BACBE0` / `#ACD6FF`.
- Font: Verdana / Arial.

## Deploy
Copy the folder contents into `makita/` under the repo root and push.
The site URL becomes:
`https://oz-packing.github.io/dyson-replacement-battery-guide/makita/`

## Files
```
makita/
├── index.html
├── makita-battery-compatibility-chart.html
├── how-to-replace-makita-battery.html
├── makita-battery-runtime-comparison.html
├── makita-battery-care-counterfeit.html
├── sitemap.xml
├── robots.txt
└── README.md
```

*Independent informational resource by AussieBatt. Not affiliated with or
endorsed by Makita Corporation.*
