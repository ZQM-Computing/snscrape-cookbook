# snscrape Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **snscrape cookbook** — social media scraping from Python and CLI. Install remaining on Node-1 and Node-3 from wave-8. Patterns are planned, not yet run on the fleet. Scrape only sources you are allowed to scrape, and respect platform terms. It is intended for Researchers who collect public social posts for analysis. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** snscrape patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Researchers who collect public social posts for analysis.

## Prerequisites

- snscrape in the fleet Python environment
- Python 3.11+
- A public search query for the first scrape

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-scrape` | A first scrape: search queries and result fields |
| 02 | `02-user-timelines` | User timelines and thread collection |
| 03 | `03-export` | Exporting results to JSON and tables |
| 04 | `04-analysis-pairing` | Pairing scraped posts with DuckDB analysis (see duckdb-spatial-cookbook) |

## Repository layout

```text
snscrape-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [scrapy-cookbook](https://github.com/ZQM-Computing/scrapy-cookbook) — Polite web scraping spiders, pipelines, and exports
- [duckdb-spatial-cookbook](https://github.com/ZQM-Computing/duckdb-spatial-cookbook) — Analytical geospatial SQL with DuckDB Spatial
- [theharvester-cookbook](https://github.com/ZQM-Computing/theharvester-cookbook) — Passive reconnaissance: domains, emails, and hosts from public sources
