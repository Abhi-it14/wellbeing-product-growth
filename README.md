# Wellbeing Nutrition — Korean Marine Collagen PDP: CRO Case Study

A product/growth assignment demonstrating how I identify customer friction, turn insights into prioritized experiments, translate strategy into design, and define measurable business outcomes.

---

## 1. Project Title and Overview

**Korean Marine Collagen PDP: A Conversion Rate Optimization Proposal**

This project analyzes the Wellbeing Nutrition [Korean Marine Collagen Peptides](https://wellbeingnutrition.com/products/korean-marine-collagen-peptides?variant=40790) product detail page (PDP) through a CRO lens — identifying where the existing page loses buyer confidence, proposing experiments to improve conversion, and delivering an enhanced version of the shopping experience as a working HTML prototype.

**Brand:** [Wellbeing Nutrition](https://wellbeingnutrition.com) — a D2C wellness and supplements brand based in India.  
**Product:** Korean Marine Collagen Peptides (200g, Unflavored) — a daily supplement for skin, hair, and joint health.  
**Deliverables:** A CRO case study document (`index.html`), a redesigned product page prototype (`enhanced-pdp.html`), and this README.

---

## 2. Assignment Brief

The task was to:

1. Analyze the Wellbeing Nutrition Korean Marine Collagen product page.
2. Prepare a CRO proposal identifying friction points, experiments, and prioritized recommendations.
3. Create an enhanced HTML version of the product page demonstrating proposed design improvements.

The assignment is designed to evaluate: CRO and funnel thinking, strategic analysis, friction-point identification, experiment prioritization, UI/UX design judgment, and the ability to connect design decisions to business outcomes.

---

## 3. Business Problem

At ~₹1,529 for 200g, the Korean Marine Collagen supplement sits in the "considered purchase" category — not an impulse buy. The typical buyer has done some research, is comparing alternatives (OZiva, HK Vitals, Kapiva), and arrives at the PDP to make a final evaluation.

The product page is the primary decision environment. Its job is to:
- Immediately communicate what the product does for the buyer.
- Answer the most common objections (timeline, safety, sourcing) before the buyer bounces.
- Provide enough trust and reassurance to reduce the perceived risk of purchase.

Based on a qualitative review of the live page, several structural gaps in information hierarchy, trust placement, and outcome communication create unnecessary friction in this decision process.

---

## 4. Objectives

**Analytical objectives:**
- Identify the highest-impact friction points on the existing PDP.
- Map observed issues to specific stages in the buyer's decision journey.
- Prioritize interventions by impact, effort, and confidence.

**Business objectives:**
- Improve Add-to-Cart rate from the PDP.
- Improve the ATC-to-checkout conversion rate.
- Reduce buyer uncertainty to lower return and refund rates.
- Identify a path toward subscription-based repeat orders (LTV improvement).

**UX and design objectives:**
- Redesign the information hierarchy to surface the most important content first.
- Create a premium, trustworthy visual experience appropriate for a wellness brand.
- Build a functional mobile-first prototype with working interactive elements.

**Technical objectives:**
- Deliver clean, responsive HTML/CSS without external dependencies.
- Implement all interactive features (gallery, quantity selector, FAQ accordion, sticky mobile CTA) using vanilla JavaScript.

---

## 5. Approach and Methodology

### Product page review
I reviewed the live WBN Korean Marine Collagen PDP as a potential buyer would — reading the page top-to-bottom, noting where I had to work to find information, and identifying what I would have needed to know to confidently purchase.

### Customer and purchase journey analysis
I mapped a typical consideration journey for this product category: awareness → PDP landing → consideration (reviews, ingredients, FAQ) → purchase intent → conversion. I identified three specific friction moments in this journey where the current page creates unnecessary hesitation.

### Friction-point identification
Six friction points were identified from the qualitative audit (see `index.html`, Section 02). These include: a keyword-heavy headline, a results timeline buried in FAQ, no trust signals near the CTA, absence of a repeat-purchase option, mobile CTA accessibility, and delayed social proof loading.

### Hypothesis generation and prioritization
Each friction point was converted into a testable hypothesis with a proposed intervention, behavioral rationale, primary metric, and guardrail metric. Hypotheses were prioritized on an effort vs. impact matrix.

### Redesigned page development
The enhanced PDP (`enhanced-pdp.html`) was developed to demonstrate the proposed design improvements as a working prototype. It uses actual product imagery from the WBN CDN, implements the proposed information hierarchy, and includes all interactive elements.

### Proposed experimentation and measurement
Three concrete A/B experiments are specified in `index.html` (Section 05) with control vs. treatment descriptions, primary metrics, guardrails, and decision criteria. No experiments were conducted — all are proposed future tests.

> **Important:** No actual analytics, heatmaps, A/B test results, or customer research data were available for this analysis. All funnel estimates, benchmark ranges, and segment descriptions are based on general D2C supplement category knowledge and are illustrative. All recommendations are hypotheses to be validated through testing.

---

## 6. Key Findings

| Finding | Observation | Type |
|---|---|---|
| Keyword headline | Product title reads as an SEO string, not a benefit statement | Observed |
| Results timeline buried | "4–8 weeks" answer is accurate but requires FAQ scroll to access | Observed |
| No trust signals at CTA | Price + buy button area has no surrounding reassurance | Observed |
| No subscription option | Daily-use supplement with no repeat-order pathway visible | Observed |
| Mobile CTA distance | Significant scroll required to reach ATC on mobile | Observed |
| Good ingredient story | Deep-sea sourcing, nano-hydrolysis, mercury testing are real differentiators | Observed |
| Strong FAQ content | Detailed, honest answers to key buyer questions — placement is the issue | Observed |

---

## 7. CRO Recommendations

| # | Opportunity | User Problem | Proposed Change | Rationale | Success Metric | Priority |
|---|---|---|---|---|---|---|
| H1 | Headline rewrite | Buyers don't immediately understand the benefit | Outcome-first headline: "Firmer Skin & Stronger Hair. In 8 Weeks." | Processing fluency — clear benefit = faster decision | Add-to-Cart rate | High / Quick Win |
| H2 | Trust signals near CTA | No reassurance at the purchase decision point | Add 4 trust indicators below the price and ATC button | Risk reduction at point of maximum anxiety | ATC-to-checkout rate | High / Quick Win |
| H3 | Results timeline prominence | Top buyer question buried in FAQ | Visual 4-step timeline section in the hero area | Reduces uncertainty before buyer opens competing tabs | PDP conversion rate | High / Medium effort |
| H4 | Mobile sticky CTA | ATC requires scroll to reach on mobile | Sticky bottom bar appearing after hero scroll | Reduces friction for mobile buyers with purchase intent | Mobile ATC rate | Medium / Quick Win |
| H5 | Subscribe & Save option | No repeat-purchase pathway for a daily supplement | Two-option purchase selector (one-time vs. subscribe) | Subscription aligns with product usage cycle; improves LTV | Subscription adoption, 90-day RPV | Medium-Low / Structural |

---

## 8. Redesigned PDP

### Design principles
- **Outcome-first hierarchy:** Buyer benefit is communicated in the headline before any technical specification.
- **Trust at decision points:** Key reassurances (lab-tested, sourced, returns) are placed near the price and CTA, not only in the hero.
- **Early answers to top questions:** Results timeline is a dedicated visual section, not a FAQ accordion item.
- **Mobile-first:** Sticky ATC bar, optimized font scaling, single-column mobile layout.
- **Honest qualification:** Unverifiable claims are softened (e.g., "higher bioavailability" instead of "4x absorption"). All illustrative content is clearly labeled.

### Major improvements over the original
- Real product imagery from the WBN CDN with graceful fallback.
- Outcome-first product headline with technical specs as subtitle.
- Trust pill row directly below the product name.
- Visual results timeline (Weeks 2/4/8/12) as a dedicated dark-background section.
- Subscribe & Save option presented as a CRO proposal with explicit "illustrative" labeling.
- Sticky mobile Add-to-Cart bar.
- Demo disclaimer banner at the top — clearly distinguishing this as a design prototype.
- Gallery with functional thumbnail switching.
- Working FAQ accordion, quantity selector, and ATC feedback.

---

## 9. Experimentation and Measurement

### Testing strategy
Three A/B experiments are specified (see `index.html`, Section 05):

1. **Exp 01 — Headline rewrite** (current title vs. outcome-first variant) → Primary: ATC rate.
2. **Exp 02 — Trust badges near price** (absent vs. present) → Primary: ATC-to-checkout rate.
3. **Exp 03 — Results timeline placement** (FAQ only vs. dedicated section) → Primary: PDP conversion rate.

### Primary KPIs
- Add-to-Cart click rate (ATC%)
- ATC-to-checkout initiation rate
- PDP conversion rate (session → purchase)
- Revenue per visitor (RPV)

### Guardrail metrics
- Return and refund rate (copy changes must not increase returns)
- Page load time / Core Web Vitals
- Customer review rating (if publicly tracked)

### Decision criteria
All experiments should run for a minimum of 2 weeks and reach 95% statistical confidence before declaring a winner. No experiment should be run without a confirmed 2-week baseline of tracking data.

---

## 10. Project Structure

```
wellbeing-nutrition-cro/
├── README.md                  ← This file
├── index.html                 ← CRO case study document (9 sections)
├── enhanced-pdp.html          ← Redesigned product page prototype
└── assets/
    ├── images/                ← Reserved for any local image assets
    └── screenshots/           ← Reserved for QA / documentation screenshots
```

---

## 11. How to Run

No build step or server required. Both files are self-contained HTML documents with all CSS and JavaScript inline.

**Option 1 — Open directly:**
1. Download or clone this repository.
2. Double-click `index.html` to open the CRO case study.
3. Double-click `enhanced-pdp.html` to view the redesigned product page.

**Option 2 — Lightweight local server (recommended for image loading):**

Using Python:
```bash
cd wellbeing-nutrition-cro
python -m http.server 8080
# Open http://localhost:8080/index.html
# Open http://localhost:8080/enhanced-pdp.html
```

Using Node.js (npx):
```bash
cd wellbeing-nutrition-cro
npx serve .
```

> The gallery images in `enhanced-pdp.html` are loaded directly from the Wellbeing Nutrition CDN. An active internet connection is required to see them. A tasteful fallback is shown if the CDN is unreachable.

---

## 12. Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic markup |
| Vanilla CSS | All styling, layout (Grid + Flexbox), animations, responsive design |
| Vanilla JavaScript | Interactive elements: gallery, FAQ accordion, quantity selector, sticky CTA, ATC feedback |
| Google Fonts (Inter, DM Serif Display) | Typography — consistent across both files |
| Google Fonts (Playfair Display) | Display typography in enhanced-pdp.html |
| Inline SVG | Customer journey diagram and effort/impact matrix in index.html |
| WBN CDN | Real product imagery in enhanced-pdp.html |

No external JS libraries, CSS frameworks, or build tools were used.

---

## 13. Assumptions and Limitations

- **No analytics access.** Real GA4 data, heatmaps, session recordings, or funnel reports were not available. All funnel estimates are illustrative benchmarks based on D2C supplement category norms.
- **No customer research.** Buyer segments and purchase objections are constructed assumptions, not validated personas.
- **No A/B test results.** All experiments are proposed — none were conducted. Impact ranges cited in the strategy section are directional hypotheses, not measured outcomes.
- **No conversion lift was claimed.** The final deliverable does not assert a specific CVR improvement or revenue outcome.
- **Review data is illustrative.** Review content, ratings, and counts in `enhanced-pdp.html` are explicitly labeled as sample content for design illustration. They do not represent verified customer data.
- **Subscription model unvalidated.** The "Subscribe & Save" option is a design proposal. Feasibility, pricing structure, and operational requirements would need product/finance team input before implementation.
- **Prices may differ.** The prices shown are based on the product page at time of review and are subject to change.

---

## 14. Future Improvements

1. **Analytics validation first.** Before running any experiments, confirm GA4 event tracking is clean and establish a 2-week baseline.
2. **Customer interviews.** Even 5 interviews with recent buyers would sharpen hypothesis prioritization significantly.
3. **Mobile usability testing.** Check the live page on Android and iOS devices at actual dimensions — not just desktop browser emulation.
4. **Heatmap analysis.** Install Microsoft Clarity (free) and review 2 weeks of session recordings and click maps before ranking experiments.
5. **Experiment execution.** Run the three proposed A/B tests in sequence (headline → trust badges → timeline), evaluating each before moving to the next.
6. **Subscription model exploration.** If business model supports it, the subscribe-and-save UI is a high-LTV opportunity worth validating with a simple test.
7. **Rich media.** Add a product video (demo or testimonial format) — well-known to improve conversion rates on supplement PDPs.

---

## 15. Deliverables and Source

| Deliverable | Link |
|---|---|
| CRO Case Study | [index.html](./index.html) |
| Redesigned Product Page | [enhanced-pdp.html](./enhanced-pdp.html) |
| Original Product Page | [wellbeingnutrition.com/products/korean-marine-collagen-peptides](https://wellbeingnutrition.com/products/korean-marine-collagen-peptides?variant=40790) |

---

*This project was created as a portfolio submission for a product/growth role. All analysis is based on a qualitative review of the publicly accessible product page without access to proprietary analytics or customer data.*
