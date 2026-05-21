# Singapore Girls Booking Mirror

This repository contains an authorized static mirror of:

https://sgcn.qc52.me/%E5%B8%B8%E8%A7%81%E9%97%AE%E7%AD%94.html

The page was first inspected with Firecrawl, then `index.html` was replaced with the source page HTML after the site owner confirmed they have the right to republish it.

## Files

- `index.html` - Authorized full-page static mirror suitable for GitHub Pages.
- `data/firecrawl-summary.json` - Structured crawl and publication metadata.
- `.nojekyll` - Keeps GitHub Pages from running Jekyll processing.

## Crawl Notes

- Firecrawl returned HTTP 200 for the target FAQ page.
- The first strict single-page crawl returned no page data.
- A later crawl with less restrictive filtering returned the FAQ page successfully.
- The deployed `index.html` is now a full mirror of the authorized source page.
