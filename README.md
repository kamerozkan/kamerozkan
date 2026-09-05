# Kamer Ozkan

I build production-oriented Apify Actors for hiring intelligence, travel and
retail pricing, reputation monitoring, and European e-invoice automation.
Each product is designed around structured outputs, explicit failure states,
and evidence that can be audited downstream.

[Browse all Actors on Apify](https://apify.com/kamerozkan) | [LinkedIn](https://www.linkedin.com/in/kamer-ozkan/) | [X](https://x.com/kamerozkan)

## Commercial focus

| Actor | Practical use | Evidence |
| --- | --- | --- |
| [LinkedIn Jobs Scraper — Keyword & Location (No Login)](https://apify.com/kamerozkan/linkedin-jobs-scraper) | Scrape public LinkedIn job postings by keyword, location, and company without login or cookies. Automatic boolean conversion for broken guest filters. | [Inputs and schema](https://github.com/kamerozkan/linkedin-jobs-scraper-sample) |
| [Facebook Ad Library Scraper & Competitor Monitor](https://apify.com/kamerozkan/facebook-ad-library-change-monitor) | Monitor competitor ad creatives, copy changes, and active status on Meta Ad Library with canonical asset hashing and lifecycle feeds. | [Inputs and schema](https://github.com/kamerozkan/facebook-ad-library-scraper-sample) |
| [LinkedIn Company Jobs Scraper and Hiring Signals](https://apify.com/kamerozkan/linkedin-hiring-signals) | Monitor public company job pages for new, changed, reopened, and safely confirmed closed roles without a LinkedIn login or cookies. | [Inputs and schema](https://github.com/kamerozkan/linkedin-hiring-signals-sample) |
| [ATS Jobs Scraper API](https://apify.com/kamerozkan/ats-job-change-feed) | Normalize public jobs from Greenhouse, Workday, Lever, Ashby, Workable, Personio, Recruitee, and Teamtailor into a job feed or change feed. | [Inputs and schema](https://github.com/kamerozkan/ats-job-change-feed-sample) |
| [DACH Package Holiday Price Comparison API](https://apify.com/kamerozkan/dach-package-holiday-price-api) | Compare normalized package-holiday offers across TUI, DERTOUR, weg.de, ab-in-den-urlaub.de, and alltours. | [Inputs and schema](https://github.com/kamerozkan/dach-package-holiday-price-api-sample) |

## Hiring, lead quality, and market signals

| Actor | Practical use |
| --- | --- |
| [LinkedIn Ghost Job Detector and Apply Link Verifier](https://apify.com/kamerozkan/linkedin-job-apply-link-verifier) | Recover official application routes and block expired, mismatched, or unproven job listings. |
| [B2B Lead List Cleaner and Email Validator](https://apify.com/kamerozkan/b2b-lead-cleaner) | Deduplicate B2B lead lists, check domain-level email signals, apply ICP rules, and return explained `ACCEPT`, `REVIEW`, or `REJECT` decisions. |
| [Google Ads Transparency Creative Monitor](https://apify.com/kamerozkan/google-ads-verified-change-monitor) | Collect public competitor ad creatives and emit verified new, stopped, resumed, and asset-change events. |
| [SEC EDGAR Form D and ADV Fundraising Signals](https://apify.com/kamerozkan/sec-form-d-fundraising-signals) | Turn official Form D filings and Form ADV matches into evidence-backed startup, VC, and PE fundraising signals. |
| [Solar Rooftop Lead Scorer](https://apify.com/kamerozkan/solar-rooftop-lead-scorer) | Pre-screen solar leads with PVGIS yield estimates, uncertainty ranges, and explainable scores, with optional Google Solar API enrichment. |

## Commerce, local inventory, and operations

| Actor | Practical use |
| --- | --- |
| [Walmart Price Tracker and Stock Checker by ZIP](https://apify.com/kamerozkan/walmart-multi-zip-monitor) | Monitor exact products across US ZIP codes for local price, stock, seller, pickup, delivery, and shipping changes. |
| [Home Depot Inventory and Price Scraper by ZIP](https://apify.com/kamerozkan/home-depot-bulk-inventory-by-zip) | Compare store-local price, inventory, pickup, and curbside evidence for products and multi-item baskets. |
| [Lieferando Menu and Restaurant Price Scraper](https://apify.com/kamerozkan/german-delivery-menu-price-intelligence) | Collect postcode-specific restaurant menus, dish prices, fees, availability, and repeat-run changes in Germany. |
| [Trusted Shops and ProvenExpert Reviews Scraper](https://apify.com/kamerozkan/provenexpert-reviews-scraper) | Compare public business ratings and reviews across ProvenExpert, Trusted Shops, eKomi, and Google Maps. |
| [Europe Truck Dispatch Guard](https://apify.com/kamerozkan/europe-truck-dispatch-guard) | Evaluate dated truck-restriction rules for Germany, Switzerland, France, and cross-border journeys with official-source evidence. |

## E-invoice validators

These tools perform pinned technical or offline preflight checks. They do not
claim tax authority, Peppol network, platform, recipient, or legal acceptance.

- [XRechnung and ZUGFeRD Invoice Validator API](https://apify.com/kamerozkan/xrechnung-xml-batch-validator-api)
- [France E-Invoice Validator for Factur-X, UBL, and CII](https://apify.com/kamerozkan/france-einvoice-validator)
- [Italy FatturaPA and SdI Preflight Validator](https://apify.com/kamerozkan/italy-fatturapa-validator)
- [Romania e-Factura and CIUS-RO Validator](https://apify.com/kamerozkan/romania-efactura-validator)
- [Peppol BIS Billing and EN 16931 Preflight Validator](https://apify.com/kamerozkan/peppol-bis-preflight-validator)
- [Poland KSeF FA(3) Preflight Validator](https://apify.com/kamerozkan/poland-ksef-preflight-validator)

## E-invoice generators

- [XRechnung 3.0.2 Invoice Generator](https://apify.com/kamerozkan/xrechnung-invoice-generator)
- [Peppol BIS Billing UBL Invoice Generator](https://apify.com/kamerozkan/peppol-ubl-invoice-generator)
- [ZUGFeRD and Factur-X PDF/A-3 Invoice Generator](https://apify.com/kamerozkan/zugferd-facturx-pdf-generator)
- [Italy FatturaPA FPR12 and FPA12 Invoice Generator](https://apify.com/kamerozkan/fatturapa-invoice-generator)
- [Poland KSeF FA(3) Invoice Generator](https://apify.com/kamerozkan/ksef-fa-invoice-generator)

## E-invoice parsers and converters

- [ZUGFeRD and Factur-X PDF to JSON Parser](https://apify.com/kamerozkan/zugferd-facturx-pdf-to-json)
- [XRechnung UBL and CII to JSON Parser](https://apify.com/kamerozkan/xrechnung-to-json-parser)
- [Peppol UBL Invoice and Credit Note to JSON Parser](https://apify.com/kamerozkan/peppol-ubl-to-json-parser)
- [ZUGFeRD to XRechnung Converter](https://apify.com/kamerozkan/zugferd-to-xrechnung-converter)

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
