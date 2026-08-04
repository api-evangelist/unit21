# Unit21

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

Unit21 is an agentic AI platform for fraud and AML (Anti-Money Laundering) detection and compliance operations. It provides a REST API for ingesting transaction data, managing detection rules, reviewing alerts, and filing suspicious activity reports. The platform supports real-time transaction monitoring at sub-250ms latency, case management, entity and instrument tracking, and automated regulatory filing including SARs, STRs, CTRs, and goAML reports.

## API

The Unit21 REST API uses API key authentication via the `u21-key` request header. All requests must be made over HTTPS. The API is versioned at `/v1` and supports sandbox and production environments with organization-specific base URLs.

Core API resource categories include:

- **Entities** - Create and update user and business entities
- **Instruments** - Manage payment instruments (cards, bank accounts, wallets)
- **Events/Transactions** - Ingest transaction and event data for monitoring
- **Alerts** - Create, list, and manage fraud and AML alerts
- **Cases** - Manage investigation cases
- **Rules** - Configure detection rules including real-time authorization rules
- **SARs** - Create and file Suspicious Activity Reports

**Documentation:** https://docs.unit21.ai/  
**API Reference:** https://docs.unit21.ai/reference/api-reference  

## Links

- **Website:** https://www.unit21.ai/
- **Documentation:** https://docs.unit21.ai/
- **GitHub:** https://github.com/u21
- **Blog:** https://www.unit21.ai/resources/risk-compliance-blog
- **Support:** https://support.unit21.ai/hc/en-us
- **Security:** https://www.unit21.ai/security
- **Status:** https://status.unit21.ai/
- **LinkedIn:** https://www.linkedin.com/company/unit21/
- **X:** https://twitter.com/unit21inc

## Maintainer

Kin Lane (kin@apievangelist.com)
