# Corpay / FLEETCOR (fleetcor)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Corpay is a global S&P 500 corporate payments company (NYSE: CPAY) that resulted from the March 2024 rebrand of FLEETCOR Technologies. The company serves more than 800,000 business clients across 200+ countries in 140+ currencies and processed approximately $400 billion in payments in 2024 with reported revenue of about $4.0B.

Corpay operates across five product lines built largely through acquisition — Commercial Cards, AP Automation (extended by the 2024 acquisition of Paymerang), Cross-Border Payments (built on the 2017 acquisition of Cambridge Global Payments and the 2025 acquisition of Alpha Group International), Fuel & Fleet Cards (the original FLEETCOR business plus the 2014 acquisition of Comdata), and Workforce Lodging & Travel.

Despite this scale, Corpay does not operate a public developer portal — there is no developer.corpay.com, no public OpenAPI catalog, no public GitHub presence, and no self-service API key issuance. All integration surfaces (ERP connectors, the former Cambridge cross-border payments API, AP-automation API hooks) are sales-led and gated behind enterprise contracts.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/fleetcor/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- B2B Payments, Corporate Payments, Fleet Cards, Fuel Cards, Commercial Cards, AP Automation, Accounts Payable, Cross-Border Payments, Foreign Exchange, Lodging, Expense Management, ERP Integration

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-23

## APIs

### Corpay Commercial Cards
Corpay's commercial card portfolio covers the Corpay Mastercard, Corpay World Elite Mastercard, virtual / ghost cards, and supplier-direct payment cards. Integration with ERP and expense systems is delivered through Corpay-managed connectors rather than a public REST API; there is no public developer portal, OpenAPI, or self-service issuance.

**Human URL:** [https://www.corpay.com/commercial-cards](https://www.corpay.com/commercial-cards)

#### Tags
- Commercial Cards, Virtual Cards, Mastercard, Expense Management, Spend Management

#### Properties
- [ProductPage](https://www.corpay.com/commercial-cards)
- [Website](https://www.corpay.com)

### Corpay AP Automation
Corpay's AP automation platform covers invoice capture and approval routing, payments automation across virtual card / ACH / check, purchase order automation with PO-to-invoice matching, and pre-built ERP connectors for NetSuite, Sage, Microsoft Dynamics, QuickBooks, Acumatica, CMiC, Deltek, and Trimble. The platform was extended by the 2024 acquisition of Paymerang. Integration is delivered through Corpay-managed ERP connectors — there is no public developer portal, no public OpenAPI, and no self-service API key issuance.

**Human URL:** [https://www.corpay.com/ap-automation](https://www.corpay.com/ap-automation)

#### Tags
- AP Automation, Accounts Payable, Invoice Automation, Payments Automation, Purchase Orders, ERP Integration, NetSuite, Sage, QuickBooks

#### Properties
- [ProductPage](https://www.corpay.com/ap-automation)
- [Integrations](https://www.corpay.com/ap-automation)

### Corpay Cross-Border Payments
Corpay Cross-Border (formerly Cambridge Global Payments, acquired in 2017 for $690M, and further expanded by the 2025 $2.2B acquisition of Alpha Group International) processes 4.1+ million payments annually across 200+ countries for 21,000+ customers, with currency-risk management, multi-currency accounts, global invoice automation, and an FX trading portal. Although a Cambridge-era developer / API surface historically existed for financial institutions and partners, no public developer portal or OpenAPI is currently exposed under corpay.com.

**Human URL:** [https://www.corpay.com/cross-border](https://www.corpay.com/cross-border)

#### Tags
- Cross-Border Payments, International Payments, Foreign Exchange, FX, Currency Risk, Multi-Currency, Cambridge Global Payments

#### Properties
- [ProductPage](https://www.corpay.com/cross-border)

### Corpay Fuel & Fleet Cards
The original FLEETCOR business line, covering fuel cards, fleet cards, and trucking-focused payments — including the Comdata brand (acquired 2014 for $3.45B) for the over-the-road trucking market. Card issuance, authorization controls, reporting, and fleet-management integrations are delivered through Corpay-managed channels; there is no public developer portal or OpenAPI for these products.

**Human URL:** [https://www.corpay.com/fuel-cards](https://www.corpay.com/fuel-cards)

#### Tags
- Fuel Cards, Fleet Cards, Trucking, Comdata, Fleet Management

#### Properties
- [ProductPage](https://www.corpay.com/fuel-cards)

### Corpay Workforce Lodging & Travel
Corpay's lodging and corporate travel offering for workforces with project, crew, and contractor lodging needs — booking, management, and consolidated billing. No public developer or API surface.

**Human URL:** [https://www.corpay.com/workforce-lodging](https://www.corpay.com/workforce-lodging)

#### Tags
- Lodging, Travel, Workforce, Corporate Travel

#### Properties
- [ProductPage](https://www.corpay.com/workforce-lodging)

## Common Properties

- [Website](https://www.corpay.com)
- [LegacyWebsite](https://www.fleetcor.com)
- [About](https://www.corpay.com/about)
- [InvestorRelations](https://investor.corpay.com)
- [NYSETicker](https://www.nyse.com/quote/XNYS:CPAY)
- [LinkedIn](https://www.linkedin.com/company/corpay)
- [PrivacyPolicy](https://www.corpay.com/privacy-policy)
- [TermsOfService](https://www.corpay.com/terms-of-use)
- [Contact](https://www.corpay.com/contact)
- [Wikipedia](https://en.wikipedia.org/wiki/Corpay)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
