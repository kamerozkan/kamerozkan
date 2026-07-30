# Kamer Ozkan

I build production-oriented data products and automation APIs on Apify,
focused on hiring signals, lead quality, price intelligence, reputation,
invoice validation, and auditable public-web change detection.

[Apify profile](https://apify.com/kamerozkan) ·
[LinkedIn](https://www.linkedin.com/in/kamer-ozkan/) ·
[X](https://x.com/kamerozkan)

## Featured work

| Project | What it does |
| --- | --- |
| [ATS Job Change Feed](https://apify.com/kamerozkan/ats-job-change-feed) | Normalizes public jobs across eight ATS formats and emits reliable `CREATED`, `UPDATED`, and `CLOSED` events. [Examples and schema](https://github.com/kamerozkan/ats-job-change-feed-sample). |
| [LinkedIn Job Apply Link Verifier](https://apify.com/kamerozkan/linkedin-job-apply-link-verifier) | Verifies job rows against public employer and ATS evidence, returns safe apply routes, and blocks expired or unproven listings. [Examples and schema](https://github.com/kamerozkan/linkedin-job-apply-link-verifier-sample). |
| [LinkedIn Hiring Signals](https://apify.com/kamerozkan/linkedin-hiring-signals) | Monitors public LinkedIn company job pages and emits `new`, `changed`, `reopened`, and safely confirmed `closed` events. [Examples and schema](https://github.com/kamerozkan/linkedin-hiring-signals-sample). |
| [HolidayCheck Review Intelligence](https://apify.com/kamerozkan/holidaycheck-review-intelligence) | Collects public hotel review data and produces aspect sentiment, monthly trends, anomaly alerts, and reputation analytics. [Examples and schema](https://github.com/kamerozkan/holidaycheck-review-intelligence-sample). |
| [Walmart Multi-ZIP Monitor](https://apify.com/kamerozkan/walmart-multi-zip-monitor) | Collects ZIP-specific price, availability, seller, pickup, delivery, and shipping evidence for exact Walmart products. [Examples and schema](https://github.com/kamerozkan/walmart-multi-zip-monitor-sample). |
| [ProvenExpert Reviews Scraper](https://apify.com/kamerozkan/provenexpert-reviews-scraper) | Collects public ProvenExpert and Trusted Shops reviews, ratings, and source evidence for reputation analysis. [Examples and schema](https://github.com/kamerozkan/provenexpert-reviews-scraper-sample). |
| [German Delivery Menu Price Intelligence](https://apify.com/kamerozkan/german-delivery-menu-price-intelligence) | Collects postcode-specific Lieferando restaurant menus, dish prices, fees, availability, and repeat-run change evidence. [Examples and schema](https://github.com/kamerozkan/german-delivery-menu-price-intelligence-sample). |
| [DACH Package Holiday Price API](https://apify.com/kamerozkan/dach-package-holiday-price-api) | Normalizes package-holiday offers across five German travel sources for hotel, airport, price-history, and comparison workflows. [Examples and schema](https://github.com/kamerozkan/dach-package-holiday-price-api-sample). |
| [Home Depot Bulk Inventory by ZIP](https://apify.com/kamerozkan/home-depot-bulk-inventory-by-zip) | Returns point-in-time ZIP and nearby-store price, inventory, pickup, and curbside evidence for exact products. [Examples and schema](https://github.com/kamerozkan/home-depot-bulk-inventory-by-zip-sample). |
| [SEC Form D Fundraising Signals](https://apify.com/kamerozkan/sec-form-d-fundraising-signals) | Normalizes official SEC EDGAR Form D filings into offering, amount-sold, fund, manager, and evidence-backed monitoring fields. [Examples and schema](https://github.com/kamerozkan/sec-form-d-fundraising-signals-sample). |
| [XRechnung & ZUGFeRD Invoice Validator API](https://apify.com/kamerozkan/xrechnung-xml-batch-validator-api) | Validates XRechnung XML and ZUGFeRD or Factur-X invoices with pinned rule versions, structured findings, PDF/A-3 checks, and SHA-256 evidence. [Examples and schema](https://github.com/kamerozkan/xrechnung-xml-batch-validator-api-sample). |
| [Europe Truck Dispatch Guard](https://apify.com/kamerozkan/europe-truck-dispatch-guard) | Evaluates scheduled truck journeys against dated rule sets for Germany, Switzerland, and France, with official-source evidence and explicit manual-review flags. [Examples and schema](https://github.com/kamerozkan/europe-truck-dispatch-guard-sample). |
| [Solar Rooftop Lead Scorer](https://apify.com/kamerozkan/solar-rooftop-lead-scorer) | Produces PVGIS-based solar pre-screen scenarios with explainable lead scores, uncertainty ranges, provenance, and site-survey warnings. [Examples and schema](https://github.com/kamerozkan/solar-rooftop-lead-scorer-sample). |
| [B2B Lead Cleaner](https://apify.com/kamerozkan/b2b-lead-cleaner) | Produces explained `ACCEPT`, `REVIEW`, or `REJECT` decisions before CRM import. [Examples and schema](https://github.com/kamerozkan/b2b-lead-cleaner-email-validation-sample). |
| [Google Ads Change Monitor](https://apify.com/kamerozkan/google-ads-verified-change-monitor) | Tracks public ad creatives and separates current scans from verified lifecycle changes. [Examples and schema](https://github.com/kamerozkan/google-ads-verified-change-monitor-sample). |

## E-Invoice Automation Suite

The portfolio includes 16 invoice validation, generation, parsing, and format-conversion Actors. Public Actor links are runnable Store listings. Private labels are release-state disclosures, not public availability claims.

- Public validators: [`xrechnung-xml-batch-validator-api`](https://apify.com/kamerozkan/xrechnung-xml-batch-validator-api) ([`xrechnung-xml-batch-validator-api-sample`](https://github.com/kamerozkan/xrechnung-xml-batch-validator-api-sample)), [`france-einvoice-validator`](https://apify.com/kamerozkan/france-einvoice-validator) ([`france-einvoice-validator-sample`](https://github.com/kamerozkan/france-einvoice-validator-sample)), [`italy-fatturapa-validator`](https://apify.com/kamerozkan/italy-fatturapa-validator) ([`italy-fatturapa-validator-sample`](https://github.com/kamerozkan/italy-fatturapa-validator-sample)), [`peppol-bis-preflight-validator`](https://apify.com/kamerozkan/peppol-bis-preflight-validator) ([`peppol-bis-preflight-validator-sample`](https://github.com/kamerozkan/peppol-bis-preflight-validator-sample)), and [`poland-ksef-preflight-validator`](https://apify.com/kamerozkan/poland-ksef-preflight-validator) ([`poland-ksef-preflight-validator-sample`](https://github.com/kamerozkan/poland-ksef-preflight-validator-sample)).
- Private validator preview: `romania-efactura-validator` ([`romania-efactura-validator-sample`](https://github.com/kamerozkan/romania-efactura-validator-sample)), private release preview with a successful hosted build.
- Private generators with successful hosted builds: `xrechnung-invoice-generator` ([`xrechnung-invoice-generator-sample`](https://github.com/kamerozkan/xrechnung-invoice-generator-sample)), `peppol-ubl-invoice-generator` ([`peppol-ubl-invoice-generator-sample`](https://github.com/kamerozkan/peppol-ubl-invoice-generator-sample)), `zugferd-facturx-pdf-generator` ([`zugferd-facturx-pdf-generator-sample`](https://github.com/kamerozkan/zugferd-facturx-pdf-generator-sample)), `fatturapa-invoice-generator` ([`fatturapa-invoice-generator-sample`](https://github.com/kamerozkan/fatturapa-invoice-generator-sample)), and `ksef-fa-invoice-generator` ([`ksef-fa-invoice-generator-sample`](https://github.com/kamerozkan/ksef-fa-invoice-generator-sample)).
- Parsers and converters: public [`zugferd-facturx-pdf-to-json`](https://apify.com/kamerozkan/zugferd-facturx-pdf-to-json) ([`zugferd-facturx-pdf-to-json-sample`](https://github.com/kamerozkan/zugferd-facturx-pdf-to-json-sample)); private release-ready `xrechnung-to-json-parser` ([`xrechnung-to-json-parser-sample`](https://github.com/kamerozkan/xrechnung-to-json-parser-sample)); private hosted-build-ready `peppol-ubl-to-json-parser` ([`peppol-ubl-to-json-parser-sample`](https://github.com/kamerozkan/peppol-ubl-to-json-parser-sample)), `zugferd-to-xrechnung-converter` ([`zugferd-to-xrechnung-converter-sample`](https://github.com/kamerozkan/zugferd-to-xrechnung-converter-sample)), and `ubl-cii-format-converter` ([`ubl-cii-format-converter-sample`](https://github.com/kamerozkan/ubl-cii-format-converter-sample)).

## Engineering approach

- Machine-readable contracts and stable identifiers
- Stateful change detection with explicit failure behavior
- Provenance, confidence, and reason codes for auditable decisions
- Public-data workflows with clear limits and responsible-use notes

The ATS release benchmark validated 500 of 500 selected live boards and
normalized 15,923 open jobs across eight adapters.
[Read the method and limits](https://apify.com/kamerozkan/ats-job-change-feed).

## Work with me

I am available for custom Apify Actors and focused public-web data workflows.
For project inquiries, contact me through
[LinkedIn](https://www.linkedin.com/in/kamer-ozkan/) or my
[Apify profile](https://apify.com/kamerozkan).
