# First Class Advanced Co. — Website Package

Bilingual (Arabic RTL + English LTR) one-page corporate site built from the
company catalog and original product photography.

## Structure
- `index.html` — Arabic homepage (default, RTL)
- `en/index.html` — English homepage (LTR)
- `style.css` — shared stylesheet (design tokens, layout, components)
- `script.js` — shared interactions (nav, scroll reveal, FAQ accordion, ticker)
- `images/` — original photos (optimized JPG kept) + WebP versions used on the page
- `icons/` — logo & favicon (SVG)
- `fonts/` — see README.txt (Google Fonts CDN, no local files needed)
- `assets/` — reserved for future brand assets
- `seo/sitemap.xml`, `sitemap.xml` — XML sitemap with hreflang alternates
- `robots.txt` — crawler directives
- `schema/organization.json`, `schema/product-service.json` — standalone copies
  of the JSON-LD also embedded inline in each page's `<head>`

## Notes
- All 5 original product photos you supplied are used as-is (only resized/
  compressed/converted to WebP for performance) in the relevant sections.
- The tall collage image was cropped into secondary supporting shots
  (coil, rebar mesh, etc.) used as smaller in-context images; nothing was
  redrawn or altered in look.
- Update the placeholder social links (`#`) and Google Map embed with your
  real profile URLs / exact coordinates before publishing.
- To publish at the URLs used in the SEO tags (https://1stclass.com.sa/ar/home/
  and /en/home/), upload `index.html` to `/ar/home/` and `en/index.html` to
  `/en/home/` on your server, or adjust the canonical/hreflang URLs to match
  your actual folder structure.
