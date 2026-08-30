# Page schema (copy this)

Use this shape for later “who takes X” pages. Page one (`paint.html`) is the example. Do not invent hours, fees, caps, addresses, or phone numbers. If an official URL disagrees with the page, prefer the official page and update the last-checked date.

## File

- One HTML file per topic (repo root, next to `index.html`).
- Shared `style.css`. Shared nav: Home, Paint, Hours, Coming.
- Do not add `noindex`. The site is live on GitHub Pages.
- The page must still be readable if someone opens the HTML file alone (facts live in the page, not in a CMS).

## Sections (in order)

1. **Header** — unofficial line, **H1** (the question, e.g. “Where to take leftover paint…”), one-line scope + last-checked date.
2. **Nav** — Home · Paint · Hours · Coming (`aria-current="page"` on the current item).
3. **Disclaimer** — `.warn`: confirm on the official page the morning you go. Not the county. Not a hauler.
4. **Decision tree** — numbered list: which kind / which case, then where that case goes.
5. **Site table** — where to go. Columns: Site | What to know. Put last-checked facts here (hours, ID, caps, Sunday entrance, phones). Link official sources in the cell.
6. **Bring this / how-to** — proof of residency, packing, any at-home method that the official page already states.
7. **Official sources** — county and (if needed) program URLs already cited in the table or a short list. Do not copy PaintCare’s site list; link their locator.
8. **Footer** — unofficial disclaimer + last-checked date.

## Last-checked

Write the date the official URLs were actually read, like `29 Aug 2026`. Same date in the header, the home directory line, and the footer. Re-read official pages before changing a fact.

## Do not

- Write pages 3–7 until each one is researched.
- Buy a custom domain, add analytics/ads/affiliate links, or sign host terms without Rene asking.
- Scrape PaintCare.
