# Awesome-Payments

## Top Payments Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Payment Processing, Gateways, Acquiring, Checkout & Global Payment Acceptance*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Payments**. These systems enable businesses to accept, process, and manage card, wallet, bank, and alternative payments online and in-person across global markets.



**Examples** include Stripe, Adyen, Checkout.com, PayPal, Braintree, Square, Razorpay, Mollie, Rapyd, and Worldpay (the category leaders).



**Open-source emphasis**: Full acquiring and global payment processing remain dominated by commercial providers. Strong open options exist for orchestration (**Hyperswitch**), Bitcoin/crypto payments (**BTCPay Server**), and lower-level financial messaging. This section prioritizes practical open alternatives and building blocks.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Stripe](https://stripe.com/)**  

  Developer-first global payments platform offering powerful APIs, Checkout, Billing, Connect, Radar fraud tools, and extensive payment method support.



- **[Adyen](https://www.adyen.com/)**  

  Enterprise payment platform providing unified acquiring across online, mobile, and in-person channels with strong global coverage and optimization.



- **[Checkout.com](https://www.checkout.com/)**  

  Modern global payments provider focused on performance, local acquiring, and flexible integration for digital businesses.



- **[PayPal](https://www.paypal.com/)**  

  Widely recognized wallet and payments platform offering familiar checkout experiences, PayPal, Venmo, and card processing options.



- **[Braintree](https://www.braintreepayments.com/)**  

  PayPal-owned full-stack payment platform popular for marketplaces and mobile apps, with strong SDK and vault capabilities.



- **[Square](https://squareup.com/)**  

  Omnichannel payments and commerce platform combining online payments with in-person POS hardware and software.



- **[Razorpay](https://razorpay.com/)**  

  Leading payments platform in India and expanding markets, offering comprehensive payment gateway, payouts, and banking tools.



- **[Mollie](https://www.mollie.com/)**  

  European payment service provider known for simple integration, local payment methods, and transparent pricing.



- **[Rapyd](https://www.rapyd.net/)**  

  Fintech-as-a-service platform enabling global payments, payouts, and local acquiring through a unified API.



- **[Worldpay](https://www.worldpay.com/)**  

  Large-scale global payment processor (part of Global Payments) serving mid-market and enterprise merchants worldwide.



## Open-Source GitHub Projects

- **[Hyperswitch](https://github.com/juspay/hyperswitch)**  

  Leading open-source, composable payments platform and orchestration layer. Connects to 100+ processors (including Stripe, Adyen, etc.) via a single API, with routing, vaulting, and self-host options.



- **[BTCPay Server](https://github.com/btcpayserver/btcpayserver)**  

  Free, open-source, self-hosted Bitcoin payment processor. Non-custodial, supports Lightning Network, invoices, POS apps, and direct peer-to-peer payments without intermediaries.



- **[jPOS](https://jpos.org/)**  

  Mature open-source Java framework for financial messaging and transaction processing (ISO-8583 and related standards), used to build gateways, switches, and custom payment systems.



- **[Open payment gateway and connector libraries](https://github.com/)**  

  Community SDKs and adapters that simplify integration with individual processors and can form the basis of custom stacks.



- **[Self-hosted checkout and payment page projects](https://github.com/)**  

  Open front-end and backend components for building custom payment experiences on top of processors or open orchestration.



- **[Crypto and alternative payment open processors](https://github.com/)**  

  Additional self-hosted solutions for accepting cryptocurrencies and other non-traditional payment rails.



- **[Reconciliation and payment operations open tools](https://github.com/)**  

  Projects focused on matching transactions, settlements, and operational reporting across payment providers.



- **[Fraud and risk open modules](https://github.com/)**  

  Complementary open components for basic risk scoring that can sit alongside payment flows.



- **[E-commerce payment plugin open ecosystems](https://github.com/)**  

  Open plugins and modules for platforms like WooCommerce, Magento, or others that integrate various payment methods.



- **[Standards and messaging open toolkits](https://github.com/)**  

  Lower-level infrastructure for building compliant payment message handling and routing.



### Additional Strong Open-Source Options

- Using **Hyperswitch** as an open orchestration and unified payments layer on top of commercial processors.

- Deploying **BTCPay Server** for fee-minimized, self-custodied Bitcoin and Lightning acceptance.

- Leveraging **jPOS** when building deeper acquiring, switching, or institutional payment infrastructure.

- Combining open connectors with a commercial primary processor for hybrid control.

- Accepting that global acquiring licenses, local payment method coverage, chargeback management, and enterprise-grade uptime still require commercial platforms (Stripe, Adyen, Checkout.com, PayPal, etc.).



**Frameworks for building custom systems**: Integrate Hyperswitch (self-hosted or managed) → connect multiple commercial processors → define routing and retry rules → add BTCPay for crypto rails if needed → handle reconciliation and monitoring with open or custom tools. This reduces lock-in while still relying on licensed acquirers for card payments. Pure commercial platforms remain the simplest path for most businesses that want rapid global coverage and full support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Payment systems involve money movement, cardholder data, and strict regulatory requirements (PCI DSS, local licensing, AML, etc.). Open-source components must be deployed with proper security, compliance, and operational controls. Errors can lead to financial loss, fraud, or legal issues. This list is not financial, legal, or compliance advice.



---

**Made for developers, merchants, and fintech teams who want flexible and reliable payment acceptance.**

Let's keep payments accessible, interoperable, and as open as practical.
