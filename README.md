# Singapore Girls Booking Firecrawl Report

This repository contains a static report generated from a Firecrawl crawl of:

https://sgcn.qc52.me/%E5%B8%B8%E8%A7%81%E9%97%AE%E7%AD%94.html

The report summarizes what Firecrawl was able to extract from the page, including metadata, crawl status, discovered links, and a neutral overview of the FAQ topics.

## Files

- `index.html` - Static HTML report suitable for GitHub Pages.
- `data/firecrawl-summary.json` - Structured crawl summary.
- `.nojekyll` - Keeps GitHub Pages from running Jekyll processing.

## Crawl Notes

- Firecrawl returned HTTP 200 for the target FAQ page.
- The first strict single-page crawl returned no page data.
- A second crawl with a depth of 1 and less restrictive main-content filtering returned the FAQ page plus an additional sitemap-derived page.
- This repository stores a summary, not a verbatim mirror of the source page.
