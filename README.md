# Dyson Replacement Battery Guide (GitHub Pages)

A pure-static, SEO-optimised topic cluster about Dyson replacement batteries for
Australian customers, produced for the `oz-packing/dyson-replacement-battery-guide`
GitHub Pages site.

## Pages
| File | Purpose | Primary keywords |
|------|---------|------------------|
| `index.html` | Pillar / complete guide hub | dyson battery replacement australia, v6 to v15, dc35 |
| `dyson-battery-compatibility-chart.html` | Model / part-number compatibility charts | dyson battery compatibility chart, dc35 type a, sv codes |
| `how-to-replace-dyson-battery.html` | Step-by-step installation tutorials | how to replace dyson battery, v6/v7/v8/v10 install |
| `dyson-battery-runtime-comparison.html` | Runtime & capacity comparison | dyson battery runtime comparison, mah, not holding charge |
| `dyson-battery-care-counterfeit.html` | Care tips + counterfeit avoidance | dyson battery care, fake dyson battery australia |
| `404.html` | Branded "Page Not Found" with guide links | (noindex) |

## Design
- Brand colours match aussiebatt.com: navy `#00366C`, CTA `#EC4A1E`, link `#0033CC`,
  light-blue borders `#B6D2FE/#BACBE0`, font `Verdana, Arial, Helvetica, sans-serif`.
- Single inline `<style>` per page, no external dependencies, mobile responsive.

## SEO
- Unique `<title>`, `<meta description>`, canonical, Open Graph, Twitter Card on every page.
- JSON-LD: `WebSite`, `Article`, `BreadcrumbList`, `FAQPage`.
- Internal linking between all 5 pages; outbound CTAs to aussiebatt.com / battaussie.com.
- `sitemap.xml` + `robots.txt` included.

## Deploy
Push this folder to the repo's `main` (or `master`) branch; enable GitHub Pages
(Settings → Pages → source = branch root). The site publishes at:
`https://oz-packing.github.io/dyson-replacement-battery-guide/`

Update the canonical/sitemap base URL if the repo owner or project name differs.

Brought to you by aussiebatt.com — trusted specialists in premium vacuum battery
replacements and cordless power solutions.
