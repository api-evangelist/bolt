# Bolt

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

Bolt is a checkout experience platform that provides a REST API for one-click checkout, managing shopper accounts, processing payments, and accessing shopper network data across merchants. Bolt enables mid-market and enterprise eCommerce merchants to integrate optimized, frictionless checkout across platforms including Adobe Commerce, BigCommerce, Shopify, WooCommerce, and Salesforce Commerce Cloud.

The Bolt Shopper Network allows returning shoppers to complete purchases with stored credentials across all Bolt-powered merchants, reducing friction and improving conversion rates.

**Website:** https://www.bolt.com/  
**Developer Docs:** https://help.bolt.com/  
**API Reference:** https://help.bolt.com/api-bolt/  
**GitHub:** https://github.com/BoltApp  
**Status:** https://status.bolt.com/  
**Blog:** https://www.bolt.com/blog  
**X:** https://x.com/bolt  
**LinkedIn:** https://www.linkedin.com/company/bolt-com  

## APIs

| API | Description |
|-----|-------------|
| [Bolt API](https://help.bolt.com/api-bolt/) | Core API for order tokens, transactions, and financial statements |
| [Embeddable Checkout v3 API](https://help.bolt.com/api-embedded-v3/) | Embed checkout and shopper account management into storefronts |
| [Merchant Callback API](https://help.bolt.com/developers/apis/) | Handle discounts, cart updates, shipping, tax, and transaction events |
| [Subscriptions API](https://help.bolt.com/developers/apis/) | Create and manage recurring billing subscriptions |
| [Tokenizer API](https://help.bolt.com/developers/apis/) | Custom back-office payment processing and card tokenization |
| [Bolt Connect Merchant Onboarding API](https://help.bolt.com/developers/apis/) | Programmatic merchant onboarding for platforms |
| [Checkout Everywhere API (Beta)](https://help.bolt.com/products/checkout-everywhere/checkout-links/) | Checkout links for social commerce and off-site channels |

## Authentication

Bolt APIs use API key authentication via the `X-Api-Key` header. Each request also requires a unique `X-Nonce` value. Merchants can maintain up to five active API keys simultaneously for zero-downtime key rotation.

- **Sandbox:** `https://api-sandbox.bolt.com`
- **Production:** `https://api.bolt.com`

## Resources

- [API Keys](https://help.bolt.com/developers/tools/api-keys/)
- [Pricing & Fees](https://help.bolt.com/dashboard/billing/fees/)
- [Changelog](https://help.bolt.com/releases/)
- [Support](https://support.bolt.com)
- [Merchant Dashboard](https://merchant.bolt.com)

---

*APIs.json profile maintained by [Kin Lane](mailto:kin@apievangelist.com)*
