# Alcohol and Tobacco Tax and Trade Bureau (alcohol-and-tobacco-tax-and-trade-bureau)

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

The Alcohol and Tobacco Tax and Trade Bureau (TTB), statutorily named the Tax and Trade Bureau, is a bureau of the United States Department of the Treasury. TTB regulates and collects federal excise taxes on alcohol, tobacco, firearms, and ammunition. The bureau enforces Federal laws and regulations related to alcohol and tobacco products, issues permits for producers, importers, and wholesalers, approves label applications for alcohol beverages, and provides open data on tax collections, permit holders, and approved product labels. TTB administers approximately $20 billion in annual federal excise tax collections from the alcohol and tobacco industries.

**URL:** [https://raw.githubusercontent.com/api-evangelist/alcohol-and-tobacco-tax-and-trade-bureau/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/alcohol-and-tobacco-tax-and-trade-bureau/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Alcohol, Tobacco, Federal Government, Excise Tax, Regulation, Treasury

## Timestamps

- **Created:** 2024-11-21T00:00:00.000Z
- **Modified:** 2026-04-19

## APIs

### TTB Open Data API
The TTB Open Data API provides programmatic access to TTB statistical and regulatory datasets via the Socrata Open Data API (SODA). Available datasets include alcohol beverage tax collections by commodity and state, federal basic permit holders, approved Certificate of Label Approval (COLA) records, and brewery/winery/distillery permit data. The SODA API supports filtering, sorting, pagination, and JSON/CSV output formats.

**Human URL:** [https://www.ttb.gov/open-government/open-data](https://www.ttb.gov/open-government/open-data)

#### Tags:

 - Open Data, Socrata, Excise Tax

#### Properties

- [DataAPI](https://data.ttb.gov/resource/)

### TTB COLA Registry
The TTB Public COLA (Certificate of Label Approval) Registry provides access to approved alcohol beverage labels. Users and industry members can search for approved labels by product type, brand name, filer name, and approval date. The registry covers wine, distilled spirits, and malt beverage label approvals required before commercial sale in interstate or foreign commerce.

**Human URL:** [https://www.ttb.gov/labeling/cola-registry](https://www.ttb.gov/labeling/cola-registry)

#### Tags:

 - Alcohol Beverage Labels, COLA, Open Data

#### Properties

- [DataAPI](https://www.ttb.gov/labeling/cola-registry)

### TTB Permits Online
TTB Permits Online is the electronic portal for applying for and managing federal basic permits, brewer's notices, distilled spirits plant permits, and tobacco permits. The system allows industry members to submit permit applications, file operational reports, and pay federal excise taxes electronically. Permit status and holder data are published as open data.

**Human URL:** [https://www.ttb.gov/permitting/permits-online](https://www.ttb.gov/permitting/permits-online)

#### Tags:

 - Permits, Licensing, Alcohol, Tobacco

#### Properties

- [GovernmentAPI](https://www.ttb.gov/permitting/permits-online)

## Common Properties

- [Website](https://www.ttb.gov)
- [Portal](https://www.ttb.gov/open-government/open-data)
- [DataPortal](https://data.ttb.gov)
- [Documentation](https://www.ttb.gov/about-ttb/laws-and-regulations)
- [Contact](https://www.ttb.gov/contact)
- [PrivacyPolicy](https://www.ttb.gov/about-ttb/privacy-policy)
- [FOIA](https://www.ttb.gov/about-ttb/foia)
- [GitHubOrganization](https://github.com/ttb-gov)

## Features

| Name | Description |
|------|-------------|
| Excise Tax Data | Annual and monthly federal excise tax collections broken down by alcohol and tobacco commodity type and by state. |
| COLA Registry | Public searchable database of all approved Certificate of Label Approval (COLA) records for wine, spirits, and malt beverages. |
| Permit Holder Data | Open data on federal basic permit holders including producers, importers, wholesalers, and retailers of alcohol beverages. |
| Socrata SODA API | TTB datasets are published on the Socrata platform, accessible via the standard Socrata Open Data API (SODA) with JSON and CSV output. |
| Statistical Reports | Annual statistical reports on alcohol and tobacco tax collections, industry production volumes, and commodity statistics. |
| eFOIA Portal | Electronic Freedom of Information Act (eFOIA) request submission and tracking for TTB records not available through open data. |

## Use Cases

| Name | Description |
|------|-------------|
| Alcohol Industry Compliance Research | Producers, importers, and retailers use TTB permit and label data to verify compliance status and competitive market intelligence. |
| Tax Revenue Analysis | Policy researchers and economists analyze TTB excise tax collection data to study alcohol and tobacco market trends. |
| Label Approval Tracking | Alcohol beverage companies track COLA approval status and research competitor label approvals in the public registry. |
| Market Research | Industry analysts use production volume statistics and permit holder counts to assess market size and industry structure. |
| Academic Research | Public health researchers use TTB consumption proxy data (tax collection volumes) to study alcohol consumption patterns. |
| Journalism and FOIA Research | Journalists and public interest groups use TTB open data and FOIA to investigate regulatory compliance and enforcement actions. |

## Integrations

| Name | Description |
|------|-------------|
| api.data.gov | TTB datasets are accessible through api.data.gov, the government-wide API management platform hosted by GSA. |
| Data.gov Catalog | TTB open datasets are cataloged on data.gov, the federal open data portal managed by GSA. |
| Socrata Open Data Platform | TTB uses the Socrata platform (data.ttb.gov) to publish and provide API access to regulatory datasets. |
| IRS | TTB coordinates with the Internal Revenue Service on excise tax administration and data sharing. |
| CBP (US Customs) | TTB coordinates with U.S. Customs and Border Protection on alcohol and tobacco import regulation and taxation. |
| ATF | TTB works with the Bureau of Alcohol, Tobacco, Firearms and Explosives on shared jurisdiction over alcohol and tobacco regulation. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
