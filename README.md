# Amazon Parser

Technical concept for structured extraction of public Amazon product-page data.
The repository is intended to become a small research/data-collection tool for
product analysis.

## Planned Stack

- Python
- requests / httpx
- BeautifulSoup or Playwright, depending on page complexity
- pandas for exports

## Planned Features

- Read product URLs from a file.
- Extract title, price, rating, reviews and availability where publicly visible.
- Normalize data into CSV/XLSX.
- Store raw snapshots for later verification.
- Respect robots, rate limits and marketplace rules.

## Project Status

Early-stage repository. It should not be presented as a finished product until
source code, usage examples and tests are added.
