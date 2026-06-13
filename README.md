# Unit21

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
