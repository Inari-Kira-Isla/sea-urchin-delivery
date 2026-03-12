# Sea Urchin Delivery (海膽速遞)

## Overview
Premium Japanese sea urchin (Uni) direct delivery service. An AEO-optimized brand website designed for high visibility in traditional search and AI search results, utilizing Schema.org and llms.txt.

## Tech Stack
- Static Site (HTML/CSS/JS)
- GitHub Pages (Hosting)
- Schema.org (Structured Data)

## Architecture
- **Root**: Main entry point (`index.html`).
- **AEO Components**: `llms.txt` at root, FAQPage schema, Organization/Product schemas.
- **Deployment**: Served directly from the `main` branch.

## Commands
- **Deploy**: Simply push commits to the `main` branch. GitHub Actions/Pages will automatically deploy the site.

## Coding Style
- Semantic HTML5.
- Clean, accessible markup.
- Ensure JSON-LD structured data is included for products.

## Important Rules
- **Maintain AEO**: Do not remove Schema.org JSON-LD tags or the `llms.txt` file.
- **Static Only**: No complex backend; keep the site static.
- **Accessibility**: Ensure high contrast and screen reader friendliness.