# 💳 Awesome Payments &nbsp;[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)

![Awesome Payments Banner](assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Payments"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Payments?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Payments/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Payments?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Payments/stargazers"><img src="https://img.shields.io/github/watchers/ishandutta2007/Awesome-Payments?style=social" alt="GitHub Watchers"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

## 🚀 Top Payments Platforms Ecosystem

> **Curated List of Payment Processing SaaS Products, Payment Gateways & Open-Source Fintech Infrastructure**  
> *Focused on Payment Processing, Gateways, Acquiring, Orchestration, Checkout & Global Payment Acceptance.*  
> **Last updated: September 2026** 📅

---

This repository tracks notable **SaaS platforms** and **open-source projects** for **Payments infrastructure**. These systems enable software applications, e-commerce platforms, and digital enterprises to accept, process, route, and manage credit card, digital wallet, ACH/bank transfer, and cryptocurrency payments online and in-person across global markets.

Whether you are looking for developer-friendly payment gateway APIs (like Stripe or Razorpay), enterprise acquiring solutions (such as Adyen or Worldpay), usage-based billing engines, or self-hosted open-source payment orchestrators (such as Hyperswitch and BTCPay Server), this list provides an authoritative reference.

---

## 📌 Table of Contents

- [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## ☁️ SaaS/Hosted Platforms

> [!NOTE]
> **Global Payment Gateway & Acquiring Market Overview**  
> The global payment processing market size is estimated at **$120+ Billion** (growing at a CAGR of ~14.5% toward $200B+ by 2030). The market is **moderately fragmented**: while tier-1 giants (Stripe, Adyen, Block/Square, PayPal) capture massive volume in digital checkout and enterprise acquiring, geographic payment preferences, localized rails (UPI, iDEAL, Pix), and specialized verticals sustain a competitive ecosystem of regional leaders (Razorpay, Mollie, Rapyd) and enterprise legacy acquirers.

| Product | Company Scale (Valuation / Revenue) | Description | Starting Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Stripe](https://stripe.com/)** | **$159.0B** valuation / $6.8B revenue (2025) 📈 | Developer-first global payments platform offering APIs, Checkout, Billing, Connect marketplaces, Radar fraud tools, and multi-currency support. | 2.9% + $0.30 per successful US card charge | No monthly fee free tier; pay-per-transaction with no free processing volume credit |
| **[Block / Square](https://squareup.com/)** | **$48.5B** market cap / $24.19B revenue (2025) 🏢 | Omnichannel payment processing and POS commerce ecosystem uniting in-person reader hardware with online payment solutions. | 2.6% + 15¢ (in-person tap/swipe) or 3.3% + 30¢ (online card checkout) | Free tier available ($0/mo subscription) with unlimited transaction volume (standard per-transaction fees apply); restricted to Square branding and default subdomains |
| **[PayPal](https://www.paypal.com/)** | **$45.5B** market cap / $33.2B revenue (2025) 🌐 | Global digital wallet and payments provider offering buyer/seller protected checkout, Venmo integration, and merchant card processing. | 3.49% + $0.49 per transaction (PayPal Checkout); 2.99% + $0.49 (standard card payments) | No monthly fee free tier; charges standard transaction fees with no free processing allowance |
| **[Adyen](https://www.adyen.com/)** | **$31.0B** market cap (€2.36B net rev) 🏦 | Enterprise end-to-end payment platform providing unified acquiring across online, mobile, and point-of-sale channels worldwide. | Interchange++ pricing model (approx. 0.48%–0.60% + €0.10–€0.15 Adyen markup per transaction) | No free tier or free trial; requires minimum monthly processing volume threshold |
| **[Worldpay](https://www.worldpay.com/)** | **$24.25B** valuation / $5.48B revenue 💳 | Large-scale global payment processor and acquirer serving mid-market enterprises and multi-channel global merchants. | Custom Interchange++ pricing (typically 0.30%–0.60% + $0.10–$0.25 markup plus gateway fees) | No free tier or trial; requires monthly account/PCI compliance service fees ($10–$25/mo) |
| **[Checkout.com](https://www.checkout.com/)** | **$12.0B** valuation / $300B+ TPV (2025) ⚡ | Enterprise cloud payments provider offering flexible payment APIs, high approval optimization, and direct local acquiring. | Custom Interchange++ pricing (negotiated starting markups typically ~0.10%–0.40% over interchange) | No public free tier or self-serve free trial; account onboarded via enterprise sales |
| **[Razorpay](https://razorpay.com/)** | **$9.2B** valuation / ₹3,783 Cr revenue (2025) 🇮🇳 | India's premier payments ecosystem providing payment gateway, UPI auto-pay, corporate banking, and neo-banking suites. | 2.0% per transaction for Indian domestic cards, UPI, net banking & wallets (+18% GST) | No fixed platform fee (₹0 setup fee, ₹0 AMC); 0% platform fee for first 90 days for new merchants |
| **[Rapyd](https://www.rapyd.net/)** | **$4.5B** valuation / $1.1B projected revenue 🌐 | Global Fintech-as-a-Service API integrating local payment collection, cross-border payouts, and multi-currency e-wallets. | Custom Interchange++ pricing (plus optional regional account platform fee ~ $99/mo) | Free unlimited Sandbox developer testing environment; live transaction fees apply |
| **[Mollie](https://www.mollie.com/)** | **$1.5B** valuation / €100M+ revenue 🇪🇺 | European payment provider focused on seamless merchant onboarding, developer APIs, and popular local payment methods like iDEAL. | €0.29 flat per iDEAL transaction; 1.8% + €0.25 for EEA consumer credit cards | Standard pay-as-you-go tier with €0/mo fixed subscription commitment; pay-per-transaction only |
| **[Braintree](https://www.braintreepayments.com/)** | **Sub-unit of PayPal** (included in PYPL) 🔒 | Full-stack payment platform popular for app developers, marketplaces, and subscription services with advanced vaulting capabilities. | 2.89% + $0.29 per transaction for standard US domestic credit & debit cards | No monthly subscription fee tier; standard processing fees apply to all volume without trial credits |

---

## 🔓 Open-Source GitHub Projects

> [!TIP]
> **Open-Source Payment Infrastructure**  
> Self-hosted payment orchestrators, billing systems, and payment server modules offer control over card vaulting, multi-processor routing, fee minimization (e.g., crypto/Lightning), and data sovereignty.

| Project / Repository | Github_Stars | Description | Core Use Cases |
| :--- | :--- | :--- | :--- |
| **[juspay/hyperswitch](https://github.com/juspay/hyperswitch)** | [![Stars](https://img.shields.io/github/stars/juspay/hyperswitch?style=social&color=white)](https://github.com/juspay/hyperswitch/stargazers) | High-performance, open-source payment orchestration layer written in Rust. Connects to 100+ payment processors via a single unified API. | Smart routing, payment vaulting, checkout UI, processor fallback, fee optimization |
| **[getlago/lago](https://github.com/getlago/lago)** | [![Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers) | Open-source metering and usage-based billing architecture. Serves as an open alternative to Stripe Billing and Chargebee. | Usage-based pricing, subscription billing, metering, invoicing, customer portal |
| **[btcpayserver/btcpayserver](https://github.com/btcpayserver/btcpayserver)** | [![Stars](https://img.shields.io/github/stars/btcpayserver/btcpayserver?style=social&color=white)](https://github.com/btcpayserver/btcpayserver/stargazers) | Free, self-hosted, non-custodial Bitcoin & Lightning Network payment processor. Eliminates middleman fees and third-party custody risks. | Peer-to-peer crypto payments, Lightning Network, e-commerce checkout, POS apps |
| **[killbill/killbill](https://github.com/killbill/killbill)** | [![Stars](https://img.shields.io/github/stars/killbill/killbill?style=social&color=white)](https://github.com/killbill/killbill/stargazers) | Enterprise-grade open-source subscription billing and payment management platform with plugin architecture. | Complex recurring billing, multi-tenancy, custom payment gateway plugins |
| **[activemerchant/active_merchant](https://github.com/activemerchant/active_merchant)** | [![Stars](https://img.shields.io/github/stars/activemerchant/active_merchant?style=social&color=white)](https://github.com/activemerchant/active_merchant/stargazers) | Simple, unified Ruby extraction library by Shopify for interacting with dozens of payment gateways. | Ruby/Rails payment gateway integration, abstraction layer |
| **[FOSSBilling/FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)** | [![Stars](https://img.shields.io/github/stars/FOSSBilling/FOSSBilling?style=social&color=white)](https://github.com/FOSSBilling/FOSSBilling/stargazers) | Free and open-source billing, client management, and automated invoicing software for web hosts and SaaS providers. | Hosting billing, invoice management, client portal, payment plugin ecosystem |
| **[jpos/jPOS](https://github.com/jpos/jPOS)** | [![Stars](https://img.shields.io/github/stars/jpos/jPOS?style=social&color=white)](https://github.com/jpos/jPOS/stargazers) | Mature Java ISO-8583 financial messaging framework for building transaction switches, acquiring systems, and payment gateways. | ISO-8583 message parsing, financial switching, terminal host integration |

---

## 🤝 How to Contribute

We welcome community contributions! To add a new payment gateway, acquiring service, or open-source payment tool:

1. Fork this repository.
2. Edit `README.md` adding your tool in alphabetical or relevant tabular format.
3. Ensure description includes key features, starting price, and project URL.
4. Open a Pull Request detailing your additions.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Payments&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Payments&type=date&legend=top-left)

---

## ⚠️ Disclaimer

- This list is **community-curated** for educational and architectural reference — not an official endorsement.
- Handling payment card data requires strict adherence to PCI-DSS standards, local licensing regulations, and AML/KYC laws. Always verify regulatory compliance before deploying financial software into production.
