# Crypto exchange licence status by country

By [ExchangeCatalogue](https://exchangecatalogue.com/crypto-exchange-licences/). Version 1, checked 29 September 2026. Licence: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Which of 27 crypto exchanges may serve people in 32 countries: the 27 EU countries, Iceland, Liechtenstein, Norway, the UK and India. Each row is one exchange in one country, with the status, the company you would deal with, the regulator, the licence ID or LEI, the date we checked and a link to the source.

- Canonical page, always the latest: https://exchangecatalogue.com/crypto-exchange-licences/
- File: `ec-crypto-licence-status-v1-2026-09-29.csv` (864 rows, 16 columns, UTF-8, comma separated)
- SHA-256: `5ccb431ff2631eb6279d80f4813625bc140ffaf74a2fab7d65c3c6465cc5f692`
- DOI: https://doi.org/10.5281/zenodo.23195567 (version 1.0.0). All versions: https://doi.org/10.5281/zenodo.23195566

## What the statuses mean

- **licensed**: the exchange's EU company holds a MiCA licence from this country's regulator.
- **passported**: it holds a MiCA licence from another EU or EEA country and may serve people here.
- **registered**: it is on the national register (the FCA register of cryptoasset firms in the UK, FIU-IND in India).
- **not_passported**: it holds a MiCA licence, but this country is not on its list of host countries.
- **restricted_by_exchange**: its own terms leave this country out, or it closed accounts here.
- **warning**: a regulator has published a warning about it.
- **blocked**: a regulator asked for its websites or apps to be blocked.
- **not_on_register**: we did not find it on the register we checked.
- **unclear**: we could not confirm either way.

Counts in version 1: passported 442, not_on_register 307, restricted_by_exchange 42, not_passported 22, licensed 16, unclear 10, registered 9, blocked 9, warning 7.

## Columns

| Column | Meaning | Example |
|---|---|---|
| country_code | ISO 3166-1 two-letter code (GB for the UK, GR for Greece). | AT |
| country | Country name. | Austria |
| exchange | Exchange brand name. | Kraken |
| exchange_review_url | Our review of the exchange. | https://exchangecatalogue.com/exchange/kraken/ |
| status | licensed, passported, registered, not_passported, restricted_by_exchange, warning, blocked, not_on_register or unclear. See the list above. | passported |
| legal_entity | The company that holds the licence or registration. For EU rows, the EU company you would deal with. | Payward Europe Solutions Limited |
| regulator | The regulator that granted it, with its country. | Central Bank of Ireland |
| licence_id | The LEI (EU) or the FCA firm reference number (UK), when there is one. | 254900641D8KNHUZYX24 |
| licence_id_type | LEI or FRN. Empty when there is no ID. | LEI |
| home_country | For MiCA licences, the EU or EEA country that granted the licence. | Ireland |
| mica_services | MiCA service codes from the ESMA register, a to j (see below). | a c d e j |
| effective_date | Date the licence or registration took effect (YYYY-MM-DD). | 2025-06-25 |
| source_name | The record we used. | ESMA interim MiCA register (CASPS), update of 24 Sep 2026 |
| source_url | Link to that record. | https://www.esma.europa.eu/sites/default/files/2024-12/CASPS.csv |
| checked_on | Date we checked (YYYY-MM-DD). | 2026-09-29 |
| note | Plain-English explanation of the row. | Licensed in Ireland and notified to serve Austria. |

## MiCA service codes

- **a**: custody and administration of crypto-assets for clients
- **b**: operating a trading platform for crypto-assets
- **c**: exchanging crypto-assets for funds
- **d**: exchanging crypto-assets for other crypto-assets
- **e**: executing orders for clients
- **f**: placing crypto-assets
- **g**: receiving and passing on orders for clients
- **h**: advice on crypto-assets
- **i**: portfolio management
- **j**: transfer services for clients

## Sources and method

We read the registers ourselves. For the EU we use the ESMA interim MiCA register (CASPS.csv, with the host countries of each licence) and ESMA's list of firms that serve EU clients without a licence (NCASP.csv). For the UK we use the FCA register of cryptoasset firms and the FCA warning list. India publishes no list of registered platforms, so we use FIU-IND orders, government press releases and news reports, each one linked. When an exchange's own terms leave a country out, we use its terms and link them.

## How often it changes

We check the EU register every week and the UK and India sources at least once a month. Each change is logged on the canonical page. New versions here get a new file name and a line in CHANGELOG.md.

## How to cite

ExchangeCatalogue (2026). *Crypto exchange licence status by country*, version 1 (29 September 2026) [Data set]. https://exchangecatalogue.com/crypto-exchange-licences/ . DOI: 10.5281/zenodo.23195567

## Licence

CC BY 4.0. Please credit "ExchangeCatalogue" and link to https://exchangecatalogue.com/crypto-exchange-licences/. Copyright 2026 Catalinq LLC.

## Limits

Information only, not legal or investment advice. A licence is not a promise that an exchange is safe. It means a regulator lets the firm offer that service. Before you use an exchange, check the regulator's own register and match the company name and the website.

## Who publishes this

ExchangeCatalogue is run by Catalinq LLC. We earn commissions from some exchanges through links on other pages of our site. This dataset has no such links, and no exchange can pay to change it. Corrections: info@exchangecatalogue.com, with a link to the record.
