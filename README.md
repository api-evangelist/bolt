# Bolt

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
