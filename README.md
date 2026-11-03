# SEC Form 4 Insider Trades: examples

Insider buys and sells from official SEC EDGAR Form 4 filings, one row per trade.

This repo shows how to call the [SEC Form 4 Insider Trades](https://apify.com/clearfeedlabs/form4-insider-trades) Apify Actor from JavaScript or Python and what the output looks like.

## Use cases
- Investors and researchers screening insider buying
- Newsletters and fintech apps that publish insider activity
- Compliance and governance research
- Quant and backtesting datasets built from primary filings

## Quick start
1. Create a free Apify account and copy your API token from Settings > Integrations.
2. Set it as an environment variable: `export APIFY_TOKEN=...` (never commit it).
3. Edit `input.json`, then run one of:
   - JavaScript: `npm i apify-client && node run.mjs`
   - Python: `pip install apify-client && python run.py`

## Files
- `input.json`: a working example input
- `run.mjs` / `run.py`: run the Actor and print the first results
- `sample-output.json`: one trimmed example record (long fields shortened)

## Pricing
Pay per result on Apify. See the current price list on the [Store page](https://apify.com/clearfeedlabs/form4-insider-trades).

## Related Clearfeed Labs Actors
- [SEC Form D Scraper: Startup Funding Leads Feed (EDGAR)](https://apify.com/clearfeedlabs/form-d-funding-feed): newly funded companies from SEC Form D
- [USAspending Scraper: Federal Contract & Grant Award Alerts](https://apify.com/clearfeedlabs/money-trail-federal-awards): federal contract and grant awards with recompete details
- [Company Contact Scraper: Domain to Email, Phone & Socials](https://apify.com/clearfeedlabs/company-contact-enrichment): emails, phones and socials for a list of domains
- [All Clearfeed Labs Actors](https://apify.com/clearfeedlabs)

## Links
- Actor on the Apify Store: https://apify.com/clearfeedlabs/form4-insider-trades
- Guide: https://clearfeedlabs.com/guides/form4-insider-trades/
- Clearfeed Labs: https://clearfeedlabs.com
- Bugs or questions: open an issue on the Actor's Issues tab on Apify.

Data comes from public sources and is provided as-is. Check the original source before relying on it. Not legal, financial or investment advice.

License: MIT
