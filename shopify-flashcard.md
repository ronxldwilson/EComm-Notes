---

# 🧠 Shopify Flashcards for PMs

---

### 🟡 GENERAL CONCEPTS

**Q:** What is Shopify?
**A:** A fully-hosted, cloud-based e-commerce platform (SaaS) that allows businesses to set up, manage, and scale online stores without managing infrastructure.

---

**Q:** What type of businesses typically choose Shopify?
**A:** Small-to-medium businesses (SMBs), D2C brands, subscription startups, and companies prioritizing fast go-to-market.

---

**Q:** What are the different Shopify plans?
**A:** Starter (\$5), Basic (\$29), Shopify (\$79), Advanced (\$299), Shopify Plus (\~\$2,000+ for enterprise).

---

**Q:** What is Shopify Plus?
**A:** Shopify’s enterprise-tier offering, allowing advanced customization (e.g., checkout), automation (Shopify Flow), and dedicated support.

---

**Q:** Is Shopify open source?
**A:** No — it is a closed SaaS platform, though developers can use APIs, themes, and apps for customization.

---

### 🧩 STORE STRUCTURE & THEME

**Q:** What is a Shopify theme?
**A:** A collection of Liquid, HTML, CSS, and JS files that define the design and layout of the storefront.

---

**Q:** What language is used to build Shopify themes?
**A:** **Liquid**, Shopify’s templating language.

---

**Q:** Can you host multiple stores in one Shopify account?
**A:** No — each Shopify store is isolated. Use **Shopify Markets** for internationalization or spin up separate stores.

---

**Q:** What is Shopify Markets?
**A:** A feature for managing multi-currency, multi-language, and localized domains under a single store backend.

---

### 🧰 PRODUCTS, CHECKOUT, AND PAYMENTS

**Q:** What are product variants in Shopify?
**A:** Unique combinations of options (like size or color) under one product, each with its own price, SKU, and inventory.

---

**Q:** How does Shopify handle inventory?
**A:** Through real-time inventory tracking, locations (multi-warehouse), and third-party fulfillment app integrations.

---

**Q:** Can you customize Shopify's checkout?
**A:** Only on **Shopify Plus** using `checkout.liquid` or Checkout Extensibility APIs.

---

**Q:** What is Shopify Payments?
**A:** Shopify’s built-in payment gateway (powered by Stripe), allowing merchants to accept credit cards directly without third-party providers.

---

**Q:** What payment gateways does Shopify support?
**A:** Shopify Payments, PayPal, Apple Pay, Google Pay, and over 100 third-party gateways.

---

### 🔌 EXTENSIONS, APPS, AND APIs

**Q:** What is the Shopify App Store?
**A:** A marketplace of 8,000+ apps that extend store functionality, including marketing, SEO, loyalty, reviews, and more.

---

**Q:** What’s the difference between public and private Shopify apps?
**A:** Public apps are listed on the App Store; private apps are built for internal use by a specific merchant.

---

**Q:** What is the Shopify Admin API used for?
**A:** Managing store data — products, orders, customers, etc. Available in REST and GraphQL.

---

**Q:** What is the Storefront API?
**A:** A GraphQL API for building custom shopping experiences (e.g., headless frontends, mobile apps).

---

**Q:** What is Shopify CLI?
**A:** A command-line tool for theme/app development, versioning, and local testing.

---

**Q:** What are Shopify Webhooks?
**A:** Server-to-server callbacks that notify your app about store events (e.g., new order, customer created).

---

### 🧠 HEADLESS COMMERCE

**Q:** Does Shopify support headless architecture?
**A:** Yes, using **Storefront API** for data and **Hydrogen** (React-based framework) for the frontend.

---

**Q:** What is Hydrogen?
**A:** Shopify’s React framework for building headless storefronts.

---

**Q:** What is Oxygen?
**A:** Shopify’s hosting platform for Hydrogen apps.

---

### ⚙️ OPERATIONS, AUTOMATION & FLOW

**Q:** What is Shopify Flow?
**A:** A no-code automation tool available on Shopify Plus to automate tasks like tagging, fraud alerts, and loyalty actions.

---

**Q:** What are metafields in Shopify?
**A:** Custom data fields added to products, orders, or customers, often used for advanced content or filtering.

---

**Q:** What is Shopify’s approach to deployment?
**A:** There's no server access — all deployments happen via CLI or Admin interface. Apps and themes are sandboxed per store.

---

**Q:** What is Launchpad?
**A:** A Plus-only tool for scheduling flash sales, theme changes, and automation around marketing events.

---

### 📊 METRICS & PERFORMANCE

**Q:** What are essential Shopify KPIs for PMs?
**A:** Conversion rate, AOV, cart abandonment, LTV, subscription churn, app usage impact, bounce rate.

---

**Q:** How can Shopify stores become slow?
**A:** Too many third-party apps, unoptimized images, poorly written Liquid code, excessive DOM elements.

---

**Q:** What tools help analyze Shopify performance?
**A:** Google Lighthouse, Shopify Analyzer, and app impact reports in the Admin dashboard.

---

### 🎯 STRATEGIC DECISIONS & PM INSIGHT

**Q:** When should a business upgrade to Shopify Plus?
**A:** When they need checkout customization, high API limits, automation (Flow), B2B support, or large-scale operations.

---

**Q:** What’s a common workaround for Shopify's limitations?
**A:** Use **custom apps**, **metafields**, or **Shopify Functions** (Plus) to extend logic that’s not supported out-of-the-box.

---

**Q:** When should you choose Shopify over Magento?
**A:** When the business needs rapid deployment, low dev overhead, a reliable hosted platform, and doesn’t need heavy B2B/custom logic.

---

**Q:** What’s a major limitation of Shopify for enterprise PMs?
**A:** Inflexible backend models (limited relational logic), and locked-down checkout and hosting environment (unless on Plus).

---

**Q:** How would you launch internationally on Shopify?
**A:** Use Shopify Markets for currencies/languages, localized domains, third-party translation apps, and GeoIP tools for redirection.

---
