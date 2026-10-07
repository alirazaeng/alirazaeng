<h1 align="center">Engineer Ali Raza</h1>

<p align="center">
  <strong>WordPress Developer · WooCommerce Developer · Speed Optimization · Core Web Vitals</strong>
</p>

<p align="center">
  I build and optimize production WordPress and WooCommerce systems using PHP, JavaScript,
  WooCommerce APIs, Checkout Blocks, HPOS, Core Web Vitals diagnostics, and technical SEO.
</p>

<p align="center">
  <strong>Specialties:</strong> WooCommerce performance · custom WooCommerce development · Checkout Blocks · HPOS · WordPress performance · technical SEO · GSAP frontends
</p>

<p align="center">
  <a href="https://engineeraliraza.site">Portfolio</a> ·
  <a href="https://www.upwork.com/freelancers/engineeraliraza">Upwork</a> ·
  <a href="https://www.linkedin.com/in/engineer-aliraza/">LinkedIn</a> ·
  <a href="https://alirazasolutions.com">Ali Raza Solutions</a>
</p>

---

## Flagship Open-Source Work

| Repository | Engineering focus | Proof |
| --- | --- | --- |
| **[WooCommerce Performance Toolkit](https://github.com/alirazaeng/woocommerce-performance-toolkit)** | Core Web Vitals, WooCommerce-safe caching, asset delivery, database diagnostics, regression testing | [v1.0.0](https://github.com/alirazaeng/woocommerce-performance-toolkit/releases/tag/v1.0.0) · real before/after case studies |
| **[WooCommerce Customizations](https://github.com/alirazaeng/woocommerce-customizations)** | Product, cart, classic + block checkout, account and order customizations using supported WooCommerce APIs | [v1.0.0](https://github.com/alirazaeng/woocommerce-customizations/releases/tag/v1.0.0) · installable plugin ZIP · runtime CI for Checkout Blocks + HPOS |
| **[WordPress GSAP Components](https://github.com/alirazaeng/wordpress-gsap-components)** | Reusable GSAP/ScrollTrigger components, reduced-motion support, cleanup patterns, conditional loading | [v1.0.0](https://github.com/alirazaeng/wordpress-gsap-components/releases/tag/v1.0.0) · [Live Demo](https://alirazaeng.github.io/wordpress-gsap-components/) |
| **[WordPress Technical SEO Toolkit](https://github.com/alirazaeng/wordpress-technical-seo-toolkit)** | Robots, canonicals, metadata, structured data, redirects, taxonomy and sitemap strategy | [v1.0.0](https://github.com/alirazaeng/wordpress-technical-seo-toolkit/releases/tag/v1.0.0) · installable plugin ZIP · WordPress runtime SEO CI |

All four flagship repositories use automated quality checks, Dependabot maintenance, versioned releases, and protected `main` branches. The WooCommerce Customizations and Technical SEO projects also boot disposable WordPress environments in CI for runtime validation.

---

## Upstream Open-Source Work

**WooCommerce core — [PR #69358: Fix shop page ID redirects when front page differs](https://github.com/woocommerce/woocommerce/pull/69358)**

- linked to upstream issue [#67772](https://github.com/woocommerce/woocommerce/issues/67772)
- adds a focused guard in `WC_Query::pre_get_posts()` for Shop page ID requests
- includes a regression test covering a separate static front page and Shop page
- automated review reported no actionable comments
- **status: open upstream PR; not presented as an accepted contribution until WooCommerce merges it**

---

## Measured Performance Work

### Ali Raza Solutions

A WordPress agency site optimized without stripping away its visual identity or animation-led experience.

| Metric | Before | After |
| --- | ---: | ---: |
| GTmetrix Grade | **E** | **A** |
| Performance | **33%** | **92%** |
| LCP | **7.6s** | **1.3s** |
| TBT | **543ms** | **25ms** |
| CLS | **0.04** | **0** |

*Retested 3 Oct 2026: PageSpeed 98 mobile / 100 desktop, mobile LCP 2.0s.*

[Read the engineering case study →](https://github.com/alirazaeng/woocommerce-performance-toolkit/blob/main/case-studies/ali-raza-solutions-performance.md)

### AHF Collection

WooCommerce performance engineering with measured improvements across rendering, blocking time, layout stability and page weight.

- GTmetrix: **E / 41% / 85% → A / 99% / 98%**
- GTmetrix LCP: **10.4s → 0.76s**
- GTmetrix TBT: **346–544ms → 76ms**
- PageSpeed desktop: **100**
- Shop CLS: **0.16 → 0.012**
- Homepage compressed size: **~92 KB → 49 KB**

[Read the WooCommerce case study →](https://github.com/alirazaeng/woocommerce-performance-toolkit/blob/main/case-studies/ahf-collection-performance.md)

---

## Engineering Standards

My public repositories are structured around the same principles I use for production work:

- **Measure before optimizing** — performance changes need reproducible evidence.
- **Protect commerce flows** — speed work must not break cart, checkout, accounts or payments.
- **Use supported APIs** — prefer WordPress/WooCommerce hooks, filters and CRUD APIs over brittle shortcuts.
- **Progressive enhancement** — motion and JavaScript should enhance usable HTML, not gate it.
- **Accessibility matters** — including reduced-motion behavior for animation-heavy interfaces.
- **Technical SEO should be conservative** — avoid duplicate metadata, conflicting canonicals and fabricated schema.
- **Automate quality** — CI, coding standards, dependency maintenance and versioned releases are part of the project.
- **Keep client data private** — no credentials, customer exports, proprietary client code or copied premium-plugin source.

---

## Primary Stack

**WordPress / WooCommerce:** PHP · MySQL · hooks & filters · WooCommerce CRUD · Checkout Blocks · HPOS-aware development

**Frontend:** JavaScript · GSAP · ScrollTrigger · HTML · CSS · responsive UI

**Performance:** Core Web Vitals · Lighthouse · GTmetrix · caching · asset optimization · database diagnostics

**SEO:** technical SEO · schema · canonicals · robots directives · redirects · taxonomy/indexation strategy

**Engineering:** Git · GitHub Actions · PHPCS / WordPress Coding Standards · release automation · Dependabot

---

## Current Open-Source Focus

I am currently strengthening these projects around:

- integration and regression testing
- reusable WooCommerce development patterns
- accessible animation systems for WordPress
- evidence-backed performance case studies
- technical SEO tooling that cooperates with the existing WordPress ecosystem

I prefer a small number of maintained repositories over a large collection of abandoned demos.

---

## Work With Me

I work on selected WordPress, WooCommerce, performance, frontend-animation and technical SEO projects.

**Portfolio:** https://engineeraliraza.site  
**Agency:** https://alirazasolutions.com  
**Upwork:** https://www.upwork.com/freelancers/engineeraliraza
