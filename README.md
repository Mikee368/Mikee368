# Mikee368

I build Apify Actors and Python scripts for data and automation. Based in Amsterdam, Europe.

[Apify store](https://apify.com/mikee368) · [X @Mikee368](https://x.com/Mikee368)

## What I build

- Apify Actors that look up companies, VAT numbers, beneficial owners, and Impressum pages
- Apify Actors that watch public sources and return new filings, tenders, permits, or status changes
- Python data and automation scripts

Small, no-contact freelance gigs: a custom Apify Actor, or a Python data or automation script.

## Public Apify Actors

25 public Actors. Titles and descriptions are copied from the store `description` field at `https://api.apify.com/v2/store?username=mikee368` on 5 November 2026 (`total` 25, one page). Links use each Actor's store name: `https://apify.com/mikee368/<name>`. Rows are sorted by title.

| Actor | Description |
| --- | --- |
| [Business Creditworthiness Check](https://apify.com/mikee368/business-creditworthiness-check) | One company per row. An open-data risk indicator from public registers, plus optional Creditsafe and Dun & Bradstreet lookups using your own API credentials. The indicator is not a credit rating. No bureau account is included. Duplicate companies in one input are checked and charged once. |
| [Chrome Web Store Extension Watch: Version, Users, and Rating](https://apify.com/mikee368/chrome-web-store-extension-watch) | Watch Chrome Web Store extensions by ID for changes in version, users, rating, last updated, or permissions. Paste IDs and schedule it. The first check of each ID is a free baseline row; each later change is $0.003. Up to 500 IDs a run. |
| [Cybercab DMV Watch](https://apify.com/mikee368/cybercab-dmv-watch) | Daily US DMV and AV-permit tracking of Tesla Cybercab (TX, CA, WA, NY, CO, NM, MN, OR, VT, CT) plus Tesla Robotaxi permits (NV; AZ best-effort, often blocked). NM, MN, OR, VT, and CT are monthly or quarterly counts only. No owner or personal data (DPPA). |
| [Domain RDAP Lookup & Expiry Watch](https://apify.com/mikee368/domain-rdap-watch) | Look up RDAP registrar, dates, status, and nameservers for domains you operate. An HTTP 200 or 404 answer is $0.0015. A later watch alert is $0.003. The first look stores state and does not alert. Hard cap 5,000 names. Not a lead list. |
| [Domain to Company Resolver](https://apify.com/mikee368/domain-company-resolver) | Resolve a domain to a legal entity: RDAP, Impressum, company register and VAT, in one profile. Runs the lookups in one container. |
| [EU & UK Tender Monitor](https://apify.com/mikee368/eu-tender-monitor) | New public tenders from TED (EU), TenderNed (NL), BOAMP (FR) and Doffin (NO) in one English feed. One keyword, 5 languages, no duplicates. |
| [EU Company Register: UK, FR, NO, FI, PL, CZ, SK, IE, RO, CH](https://apify.com/mikee368/eu-company-register-lookup) | Look up companies by name or registration number in official registers (UK, France, Norway, Finland, Poland, Czechia, Slovakia, Ireland, Romania, Switzerland, GLEIF) and confirm an EU VAT number on VIES when a state has no free register. Company data only. |
| [EU Company Status Watch](https://apify.com/mikee368/eu-company-status-watch) | Watch French BODACC notices and UK Companies House for dissolution and insolvency-style status changes. Screening / public-register aid, not legal advice. |
| [EU Impressum Lookup](https://apify.com/mikee368/eu-impressum-lookup) | Extract company details from EU websites' Impressum, Imprint, legal notice, Mentions légales or Colofon pages. Returns company data only by default. |
| [EU TIN & VAT Validator](https://apify.com/mikee368/eu-tin-vat-validator) | Check VAT numbers for every EU country, Northern Ireland, Norway and Switzerland. Personal numbers are format-checked only and are never sent to a register. Existence checks use VIES, Brønnøysund, the Swiss UID register, the Polish VAT white list and the French recherche-entreprises API. |
| [EU UBO Lookup](https://apify.com/mikee368/eu-ubo-lookup) | Beneficial owners from sources that can be reused commercially, and a not-available row with the official route where a register is closed. |
| [FCC ECFS Filings Watch: New Filings by Docket or Filer](https://apify.com/mikee368/fcc-filings-watch) | Watch FCC ECFS filings by docket number or filer name. The first run for a Monitor ID is a free baseline. Later runs return filings received since the newest one already seen, at $0.002 per new filing. Schedule it and export the dataset. Equipment authorization is not included. |
| [FMCSA Carrier Lookup & Authority Watch](https://apify.com/mikee368/fmcsa-carrier-watch) | Look up a US motor carrier by USDOT, MC/MX/FF docket, or name, or watch authority and insurance changes. A carrier row is $0.002. A watch change is $0.004. The first watch stores a baseline and pushes no rows. Default cap 25 carriers a run. |
| [GDPR & ePrivacy Consent Scanner](https://apify.com/mikee368/gdpr-consent-scan) | One row per site with status, score, findings, the cookie banner, cookies and trackers before consent, and privacy-policy / imprint signals. An indicator, not legal advice. Only a row with status ok is charged. |
| [Insolvency & Bankruptcy Watch](https://apify.com/mikee368/insolvency-bankruptcy-watch) | Watch official insolvency publications for companies and sole traders in NL, the UK, France and the US, and return only new matches. Personal insolvencies are excluded. |
| [ISO Certificate Check](https://apify.com/mikee368/iso-certificate-check) | Check an ISO 9001, 14001, 27001, or 45001 certificate number against a local shape check and the official manual pages. A live result is returned only when you supply your own IAF CertSearch API key. Accreditation registers are not scraped. |
| [S&P 500 Quarterly Reports from SEC EDGAR XBRL](https://apify.com/mikee368/sp500-quarterly-reports) | Quarterly and annual financials for S&P 500 companies from SEC EDGAR companyfacts XBRL: revenue, profit, EPS, balance sheet, cash flow, and derived free cash flow. One row per company per fiscal period. |
| [SEC EDGAR Filings Watch: Form 4, 8-K, 10-K, and Full Text](https://apify.com/mikee368/sec-edgar-filings-watch) | Watch SEC EDGAR filings by ticker, CIK, or full-text keyword, with Form 4 insider trades parsed. $0.001 per stored filing. Use New since last run on a schedule to get only filings not seen before; Latest mode returns and charges the newest filings every run. Not investment advice. |
| [Supplier Risk Monitor](https://apify.com/mikee368/supplier-risk-monitor) | Re-check a saved supplier list. Register, VAT, sanctions, ownership, domain expiry and US SAM exclusions are billed per supplier. A change alert is billed only when the risk changes. A failed source is never clear. |
| [Tender Supplier Due Diligence](https://apify.com/mikee368/tender-supplier-due-diligence) | Build one supplier profile from a tender award: company register, VAT check and Impressum, with warning flags. Runs the lookups in one container. |
| [US Building Permits Watch: Eight City Portals](https://apify.com/mikee368/us-building-permits-watch) | Search or watch building permits from eight US city open-data portals (NYC, Chicago, LA, Austin, Seattle, SF, Cincinnati, Baton Rouge). $0.0015 per stored permit. Schedule a watch for newly issued permits; the first run looks back 3 days (LA 14) and is charged. |
| [US Business Entity Status: SOS Good Standing Check](https://apify.com/mikee368/us-business-entity-status) | Check a US business by name or file number in NY, CO, CT, OR, and PA open data, plus the Texas Comptroller franchise file. Returns legal name, type, file number, status, and a business registered agent. Other states return not supported and the official lookup URL. |
| [US Federal Contractor Profile](https://apify.com/mikee368/us-contractor-profile) | Look up a US federal contractor by company name, UEI, or CAGE code. Returns the USAspending recipient and award-history summary. SAM.gov registration and exclusion checks are coming later (no key yet). |
| [US Federal Tender Monitor (SAM.gov)](https://apify.com/mikee368/us-federal-tender-monitor) | New US federal contract opportunities from SAM.gov by keyword and NAICS code: only new notices since the last run, award notices excluded, set-asides and an alert digest. Bring your own free SAM.gov API key. |
| [US Weather Station Data: METAR + NWS Climate (Kalshi stations)](https://apify.com/mikee368/us-weather-station-data) | Latest METAR observations plus the official NWS Daily Climate Report (CLI) max/min temperature for US stations, with a preset for common Kalshi settlement stations (KNYC, KMDW, KLAX, KAUS, KMIA, KDEN, KPHL). Source: NOAA/National Weather Service (public domain). |

## Tech

Apify Actors, Python
