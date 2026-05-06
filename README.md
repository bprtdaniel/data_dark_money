# Dark Money and Competitive Districts

This project shows a short interactive story about campaign finance, outside spending, and competitive U.S. House districts.

It uses a single HTML page to guide readers through two published visualizations and provide context on which races use dark money.

The campaign finance data was scraped from [OpenSecrets](https://www.opensecrets.org/dark-money/top-elections), while the [Cook Political Report 2024 House ratings via 270toWin](https://www.270towin.com/2024-house-election/table/cook-political-report-2024-house-ratings) from October 31, 2024 were used to classify competitive districts.

Shapefiles and geodata were downloaded from the [U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/cartographic-boundary.2024.html).

## Project Structure

```text
.
├── index.html
├── README.md
├── Data
│   ├── openSecrets
│   ├── Full Dark Money + all states GEOJSON
│   └── Dark Money + 2024 Competitive House Districts GEOJSON
└── Scripts
    ├── Scraper
    └── Creating DW Upload Files
