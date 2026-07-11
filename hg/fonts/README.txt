Fonts are loaded via Google Fonts CDN (see @import at the top of style.css):
- Arabic: Almarai (display) + Cairo (body)
- English: Big Shoulders Display (display) + Inter (body)
- Data/mono: IBM Plex Mono

No local font files are required. If you prefer self-hosted fonts for
performance/offline use, download the .woff2 files for the families above
from fonts.google.com and place them in this folder, then update the
@import rules in /style.css with local @font-face declarations.
