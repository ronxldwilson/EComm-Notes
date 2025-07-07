## 🧠 Magento Flashcards for PMs

---

### 🟡 GENERAL CONCEPTS

**Q:** What is Magento?
**A:** An open-source e-commerce platform owned by Adobe, known for its flexibility, modular architecture, and support for complex, enterprise-level e-commerce use cases.

---

**Q:** What are the two main versions of Magento?
**A:** Magento Open Source (free) and Adobe Commerce (paid, includes cloud hosting and advanced features).

---

**Q:** Which programming language is Magento built in?
**A:** PHP.

---

**Q:** What architecture does Magento use?
**A:** Modular MVC (Model-View-Controller) with MVVM patterns and Dependency Injection (DI).

---

**Q:** Who should use Magento over Shopify?
**A:** Businesses with complex needs like B2B workflows, multi-store management, or deeply customized catalogs and checkout flows.

---

### 🧩 MODULAR ARCHITECTURE

**Q:** What is a Magento module?
**A:** A package of related code that adds or customizes a specific feature (e.g., cart, checkout).

---

**Q:** What are Magento themes built with?
**A:** PHTML (PHP HTML), XML layout files, LESS/CSS, and JavaScript (Knockout.js for frontend interactivity).

---

**Q:** What are service contracts in Magento?
**A:** Interfaces (APIs) that expose Magento’s core logic in a stable, decoupled way for safe integration and extension.

---

### 🔧 PRODUCT & CATALOG

**Q:** What is an attribute set in Magento?
**A:** A group of product attributes (e.g., color, size, material) that define the structure of a product type.

---

**Q:** What types of products can you create in Magento?
**A:** Simple, Configurable, Virtual, Bundle, Grouped, Downloadable.

---

**Q:** What is layered navigation?
**A:** Filter-based navigation (faceted search) that allows users to refine product listings by attributes like price, color, size, etc.

---

**Q:** What is a configurable product?
**A:** A parent product with selectable variations (e.g., a T-shirt with different sizes/colors), each being a simple product.

---

### 🌍 MULTI-STORE & INTERNATIONAL

**Q:** What is Magento's multi-store hierarchy?
**A:** Website → Store → Store View.

---

**Q:** What's the difference between a store and a store view?
**A:** A store has its own catalog; a store view is typically used for translations or theme variations.

---

**Q:** How does Magento support international selling?
**A:** Multi-language, multi-currency, localized tax and shipping configurations.

---

### 📦 CHECKOUT & CART

**Q:** What JavaScript framework powers Magento’s checkout?
**A:** Knockout.js.

---

**Q:** Can the Magento checkout be fully customized?
**A:** Yes, including adding/removing steps, fields, and integrating third-party services.

---

**Q:** What is Magento’s one-page checkout?
**A:** A simplified, all-in-one checkout screen that improves conversion.

---

**Q:** How can a business support B2B quoting in Magento?
**A:** By using the **Adobe Commerce B2B module**, which includes Request for Quote functionality.

---

### 🔌 INTEGRATIONS & EXTENSIONS

**Q:** How do Magento extensions work?
**A:** They plug into core modules via events, observers, and DI, adding or overriding functionality.

---

**Q:** What is Composer used for in Magento?
**A:** Dependency management and installing/updating modules and extensions.

---

**Q:** Which search engine does Magento use by default?
**A:** Elasticsearch.

---

**Q:** How can Magento integrate with external systems like ERP/CRM?
**A:** Through REST or GraphQL APIs, or via middleware and message queues (RabbitMQ).

---

### 📊 PERFORMANCE & DEVOPS

**Q:** What is full-page cache in Magento?
**A:** A caching mechanism that stores entire page HTML to reduce server processing time. Powered by Varnish or built-in cache.

---

**Q:** What CLI tool does Magento provide?
**A:** `bin/magento` for running commands like cache flush, module enable/disable, and indexer updates.

---

**Q:** How does Magento handle asynchronous tasks?
**A:** Using its **Message Queue Framework**, often powered by RabbitMQ.

---

**Q:** What tools are commonly used for profiling Magento performance?
**A:** New Relic, Blackfire, Magento Profiler, Xdebug.

---

**Q:** What is indexing in Magento?
**A:** The process of transforming data (like product attributes) into optimized formats for faster query performance.

---

### 📈 KPIs & STRATEGY

**Q:** What Magento KPI measures success of B2B quoting?
**A:** Quote-to-order conversion rate.

---

**Q:** What DevOps KPI is crucial for Magento deployments?
**A:** Deployment frequency and rollback time.

---

**Q:** What metric shows catalog performance health?
**A:** Indexing success rate.

---

**Q:** Which performance metric is affected by app bloat and theme inefficiencies?
**A:** Time to First Byte (TTFB) and page load time.

---

### 🛠️ PM PRACTICE & DECISIONS

**Q:** How would you prioritize a Magento extension vs custom module?
**A:** Evaluate based on time to value, long-term maintenance cost, flexibility, and security. Use extension for common needs, custom module for edge cases.

---

**Q:** What factors influence choosing Adobe Commerce over Open Source Magento?
**A:** Need for B2B suite, advanced content staging, cloud hosting, scalability, support, and Adobe integrations (e.g., Sensei, Analytics).

---

**Q:** What is the biggest trade-off when using Magento?
**A:** Flexibility vs speed-to-market and development complexity.

---

**Q:** What’s a typical Magento PM task during a migration?
**A:** Overseeing data migration planning, theme and extension compatibility mapping, stakeholder communication, and go-live readiness.

---

### 🤖 HEADLESS MAGENTO

**Q:** Does Magento support headless architecture?
**A:** Yes, via GraphQL APIs and PWA Studio.

---

**Q:** What is Magento PWA Studio?
**A:** A front-end framework built using React to create Progressive Web Apps that interact with Magento via APIs.

---
