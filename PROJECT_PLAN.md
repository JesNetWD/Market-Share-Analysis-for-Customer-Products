# 📊 Market Share Analysis – Problem Definition & Scope

## 1. Business Context

In the fast-moving consumer goods (FMCG) industry, companies must continuously monitor their market position to remain competitive. Changes in customer preferences, pricing strategies, and distribution channels can significantly impact performance.

This project simulates a consulting-style market intelligence report to evaluate market share trends and provide strategic recommendations.

---

## 2. Business Problem

The company lacks a structured view of its competitive position across product categories and time.

Specifically:

- It is unclear whether the company is gaining or losing market share.
- There is no visibility into how competitors are affecting performance.
- Strategic decisions regarding product investment, pricing, and expansion are not data-driven.

Without market share intelligence, the company risks misallocating resources and losing competitive advantage.

---

## 3. Project Objective

**Primary Objective:**
Evaluate market share trends for a consumer goods company, identify competitive threats, and recommend actionable growth strategies — mimicking a consulting firm’s market intelligence report.

---

## 4. Business Questions

### Primary Business Question

How is the company’s competitive position evolving across product categories and over time, and what strategic adjustments are required to protect or grow market share?

---

### Supporting Business Questions

### 1. Market Share Clarity

- What is the company’s current market share in each product category?
- Is the company gaining or losing share over time?
- Are changes consistent across categories or concentrated in specific segments?

### 2. Competitive Impact Assessment

- Who are the key competitors in each category?
- How do competitor shares compare to the company’s position?
- Are competitors gaining share at the company’s expense or due to overall market growth?
- Which competitor poses the most significant threat in each category?

### 3. Market Dynamics Evaluation

- Is overall market size expanding or contracting?
- Is the company underperforming relative to total market growth?
- Are certain categories structurally more competitive than others?

### 4. Strategic Decision Guidance

- Which categories warrant increased investment?
- Which categories require defensive strategies (pricing, promotion, distribution)?
- Are there low-performing categories where capital should be reallocated?
- What actions are most likely to improve competitive positioning?

---

## 5. Dataset Overview

**Dataset Name:** `[Insert Dataset Name]`
**Time Period Covered:** `[e.g., Jan 2022 – Dec 2024]`
**Granularity:** `[Monthly / Quarterly / Yearly]`
**Product Categories:** `[List categories]`
**Key Columns:**

- `Product`
- `Category`
- `Time Period`
- `Company Sales`
- `[Any other relevant columns]`

---

## 6. Assumptions & Simulated Data

Since the dataset does not include competitor sales data, the following assumptions are introduced:

- The market consists of:

  - The company
  - 3 simulated competitors (`Competitor_A`, `Competitor_B`, `Competitor_C`)

- Competitor sales are estimated using assumed market share distributions.
- Market share percentages will sum to 100% for each product × time period.
- Random variation (via Excel `RAND()`) may be used to simulate realistic market fluctuations.

> Note: Competitor data in this project are simulated for analytical practice purposes.

---

## 7. Scope of Analysis

### Included in Scope:

- Market size estimation
- Market share calculation
- Trend analysis over time
- Category-level competitive comparison
- Identification of growth and decline areas
- Strategic recommendations

### Excluded from Scope:

- Real external competitor financial validation
- Consumer-level behavioral analysis
- Pricing elasticity modeling
- Supply chain analysis

---

## 8. Key Metrics

The following metrics will be calculated:

- **Total Market Size**

  ```
  Company Sales ÷ Assumed Company Market Share
  ```

- **Company Market Share (%)**

  ```
  Company Sales ÷ Total Market
  ```

- **Competitor Market Share (%)**

  ```
  Competitor Sales ÷ Total Market
  ```

- **Market Share Growth Rate**

  ```
  (Current Period Share - Previous Period Share) ÷ Previous Period Share
  ```

Additional metrics may include:

- Revenue Growth Rate
- Category Contribution %
- Competitive Gap Analysis

---

## 9. Analytical Framework & Measurable Steps

To solve the business problem, the analysis will follow a structured, measurable approach:

---

### Phase 1: Data Preparation & Structuring

Objective: Ensure dataset is analysis-ready.

Steps:

- Clean missing or inconsistent values.
- Standardize time periods (monthly/quarterly/yearly).
- Validate product categories and sales fields.
- Add simulated competitor sales columns.
- Create Total Market column.

Deliverables:

- Cleaned dataset.
- Structured table: Product × Time × Company Sales × Competitor Sales × Total Market.

---

### Phase 2: Market Size Estimation

Objective: Quantify total addressable market.

Metrics:

- Total Market = Company Sales + Competitor Sales
- Market Growth Rate (%) = (Current Period Market - Previous Period Market) / Previous Period Market

Analysis:

- Identify expanding vs contracting markets.
- Rank categories by total market size.

Deliverables:

- Market size trend chart.
- Market growth rate table by category.

---

### Phase 3: Market Share Calculation

Objective: Quantify competitive position.

Metrics:

- Company Market Share (%) = Company Sales / Total Market
- Competitor Market Share (%) = Competitor Sales / Total Market
- Market Share Change (%) = Current Share - Previous Share

Analysis:

- Trend analysis of share over time.
- Rank company position within each category.
- Identify share leaders and challengers.

Deliverables:

- Market share trend line chart.
- Competitive ranking table.

---

### Phase 4: Competitive Threat Assessment

Objective: Identify risk areas.

Metrics:

- Share Gap = Leader Share - Company Share
- Share Loss Rate = % decrease in share over time
- Competitor Growth Rate

Analysis:

- Identify categories where:
  - Company share is declining.
  - Competitor growth outpaces company growth.
  - Share gap is widening.

Deliverables:

- Threat heatmap (conditional formatting).
- Top 3 risk categories list.

---

### Phase 5: Opportunity Identification

Objective: Detect growth potential.

Metrics:

- High Market Growth + Low Company Share
- Stable Leadership (High Share + Growing Market)
- Contribution to Total Revenue (%)

Analysis:

- Identify underpenetrated high-growth segments.
- Highlight defendable strongholds.

Deliverables:

- Opportunity matrix (Growth vs Share).
- Investment priority ranking.

---

### Phase 6: Strategic Recommendation Development

Objective: Translate insights into action.

Decision Framework:

- Invest → High Growth + Low/Medium Share
- Defend → High Share + Competitive Pressure
- Optimize → Stable but slow growth
- Deprioritize → Low Growth + Declining Share

Deliverables:

- Category-level strategy table.
- Executive summary recommendations.

---

## 10. Expected Deliverables

- Cleaned dataset
- Market share dashboard (Excel)
- Visual trend analysis
- Competitive threat assessment
- Consulting-style strategic recommendations
