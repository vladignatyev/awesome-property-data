# Awesome Property Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of real-estate / property data sources — open government data, listing portals, APIs, datasets and tools — for analysts, PropTech, valuers and investors.

Contributions welcome (PRs). Links marked 🟢 are **free / open data**, 🔵 **API**, 🟠 **scraper/tool**.

## Contents
- [Open government & sold-price data](#open-government--sold-price-data)
- [Listing portals by country](#listing-portals-by-country)
- [APIs & datasets](#apis--datasets)
- [Tools & scrapers](#tools--scrapers)

## Open government & sold-price data
- 🟢 **UK — HM Land Registry Price Paid Data** — every recorded sale in England & Wales (~28M txns). Bulk CSV + SPARQL. OGL v3. https://www.gov.uk/guidance/about-the-price-paid-data
- 🟢 **UK — Land Registry UK House Price Index (UKHPI)** — official price index. https://landregistry.data.gov.uk/app/ukhpi
- 🟢 **UK — Registers of Scotland** — Scottish sold prices (gated). https://www.ros.gov.uk/
- 🟢 **Netherlands — WOZ Waardeloket** — official property valuations. https://www.wozwaardeloket.nl/
- 🟢 **USA — county assessor / recorder offices** — sold prices & assessments (per-county, fragmented).
- 🟢 **Sweden — SCB / Norway — SSB / etc.** — national statistics offices publish house-price indices.

## Listing portals by country
| Country | Portal(s) |
|---|---|
| Ireland | daft.ie, myhome.ie |
| UK | rightmove.co.uk, zoopla.co.uk, onthemarket.com |
| Canada | realtor.ca, remax.ca, centris.ca |
| South Africa | property24.com, privateproperty.co.za, seeff.com |
| New Zealand | trademe.co.nz, realestate.co.nz, oneroof.co.nz |
| Australia | realestate.com.au, domain.com.au, realcommercial.com.au |
| Turkey | sahibinden.com, emlakjet.com, hepsiemlak.com |
| Albania | merrjep.al, njoftime.com |
| India | magicbricks.com, 99acres.com, housing.com, squareyards.com |
| Spain | idealista.com, fotocasa.es, pisos.com |
| UAE | bayut.com, propertyfinder.ae, dubizzle.com |

## APIs & datasets
- 🔵 **[BatchData](https://batchdata.io)** — U.S. property data API covering 169 million+ U.S. parcels (property search, skip tracing, valuations, address verification), plus a hosted MCP server.
- 🔵 **PropertyData (UK)**, **PriceHubble**, **Quintos** — commercial property-data APIs.
- 🟢 **Kaggle** — search "house prices" / "real estate" for community datasets.
- 🔵 **OpenStreetMap / ONS / data.gov.uk** — geo + area context to join with sales.

## Tools & scrapers
- 🟠🟢 **[UK Land Registry Price Paid](https://github.com/vladignatyev/uk-land-registry-price-paid)** — open-source, uncapped sold-price exporter (CSV/JSON), monthly monitor. *(this repo's sibling)*
- 🟠 **[uk-land-registry-price-mcp](https://github.com/vladignatyev/uk-land-registry-price-mcp)** — MCP server exposing UK sold prices as an AI-agent tool ([npm](https://www.npmjs.com/package/uk-land-registry-price-mcp)).
- 🟠 **Apify property-data actors** — hosted, no-setup scrapers ([all actors](https://apify.com/vladignatyev)):
  - [UK sold prices — Land Registry](https://apify.com/vladignatyev/uk-land-registry-scraper) — uncapped, monthly monitor
  - [Daft.ie (Ireland)](https://apify.com/vladignatyev/daft-ie-scraper)
  - [RE/MAX Canada](https://apify.com/vladignatyev/remax-ca-scraper)
  - [Emlakjet (Turkey)](https://apify.com/vladignatyev/emlakjet-scraper)
  - [Square Yards (India)](https://apify.com/vladignatyev/squareyards-scraper)
  - [PrivateProperty (South Africa)](https://apify.com/vladignatyev/privateproperty-co-za-scraper)
  - [Seeff (South Africa)](https://apify.com/vladignatyev/seeff-scraper)
  - [Merrjep (Albania)](https://apify.com/vladignatyev/merrjep-al-scraper)
  - [Aqar.fm (Saudi Arabia)](https://apify.com/vladignatyev/aqar-sa-scraper)
- 🟠 **Crawlee** — the scraping framework behind most of the above. https://crawlee.dev

---
*Maintained by [Vladimir Ignatev](https://www.linkedin.com/in/vignatyev/). Run the scrapers hosted at **[apify.com/vladignatyev](https://apify.com/vladignatyev)** · managed feeds: [get in touch](https://forms.gle/CPmQGP6bsmtA7woe6).*
