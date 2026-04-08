## Sport Subscription Pricing & Bundle Architecture (SPS) for ParallaxEdge

### 1. FINANCE RATING
**🟡 AMBER**
Justification: The sport-specific pricing model is viable but carries risks due to seasonality and churn windows. While the product's unique offerings in specific sports can command premium prices, the transition between seasons could lead to subscriber churn unless retention strategies are robustly implemented.

### 2. PRICING MODEL SELECTION
**Recommended Model:** Hybrid bundle with per-sport tiered pricing.
- **Rationale:** This model caters well to both user archetypes by offering sport-specific subscriptions that can be bundled for year-round coverage, thus providing flexibility while maintaining simplicity in pricing tiers.

### 3. PER-SPORT SKU STRUCTURE

| Sport               | Season Window                     | Sharp Price/mo (USD) | Pro Price/mo (USD) | Annual Sharp USD | Annual Pro USD |
|---------------------|-----------------------------------|----------------------|--------------------|------------------|---------------|
| Soccer/Football     | Year-round                        | 24.99                | 49.99              | 275.88           | 539.88        |
| NFL                 | September-February                | 19.99                | 39.99              | [MODELED — basis: first principles] 239.88      | [MODELED — basis: first principles] 479.88     |
| NBA                 | October-June                      | 20.99                | 41.99              | [MODELED — basis: first principles] 251.88      | [MODELED — basis: first principles] 503.88     |
| NHL                 | Phase 2, October-June             | [MODELED — basis: first principles] 22.99    | [MODELED — basis: first principles] 45.99       | [MODELED — basis: first principles] 263.88      | [MODELED — basis: first principles] 551.88     |
| MLB                 | Phase 2, March-October            | [MODELED — basis: first principles] 24.99    | [MODELED — basis: first principles] 49.99       | [MODELED — basis: first principles] 275.88      | [MODELED — basis: first principles] 539.88     |
| NCAA Football       | Phase 2, August-January           | [MODELED — basis: first principles] 19.99    | [MODELED — basis: first principles] 39.99       | [MODELED — basis: first principles] 239.88      | [MODELED — basis: first principles] 479.88     |
| NCAA Basketball      | Phase 2, November-April           | [MODELED — basis: first principles] 18.99    | [MODELED — basis: first principles] 37.99       | [MODELED — basis: first principles] 227.88      | [MODELED — basis: first principles] 455.88     |
| Tennis              | Year-round                        | 20.99                | 41.99              | 239.88           | 479.88        |
| Rugby Union         | Year-round                        | 18.99                | 37.99              | [MODELED — basis: first principles] 206.88      | [MODELED — basis: first principles] 455.88     |
| AFL/Australian Rules| March-September                   | [MODELED — basis: first principles] 19.99    | [MODELED — basis: first principles] 39.99       | [MODELED — basis: first principles] 239.88      | [MODELED — basis: first principles] 479.88     |
| Cricket             | Year-round                        | 19.99                | 39.99              | [MODELED — basis: first principles] 239.88      | [MODELED — basis: first principles] 479.88     |

**Note:** The prices for Phase 2 sports are modeled based on the pricing tiers of similar sports and adjusted for seasonal differences.

### 4. ELITE / ALL-SPORTS TIER
**Recommended Elite Monthly Price (USD): $149.99**
**Annual Price: $1,539.88**

**Positioning:** The Elite tier provides unlimited access to all sports at a significant discount compared to stacking individual sport subscriptions.
- **Effective Discount:** Purchasing each sport individually would cost approximately $275.88 (annual) for the least expensive Sharp subscription, totaling around $1,300+ for year-round coverage. 

### 5. BUNDLE ARCHITECTURE

| Bundle Name            | Sports Included                       | Monthly Price (USD) | Annual Price (USD)    | Discount vs Individual |
|------------------------|---------------------------------------|---------------------|----------------------|------------------------|
| US Bundle              | Soccer + NFL + NBA                    | $74.97              | $835.68              | ~20%                   |
| International Bundle   | Soccer + Cricket + Rugby Union        | $71.97              | $815.68              | ~22%                   |
| Australian Bundle      | Soccer + AFL/Australian Rules + Cricket | $63.97             | $745.68              | ~28%                   |
| Summer Fill            | Soccer + MLB                          | $45.98              | $515.88              | ~20%                   |

**Note:** Discounts are estimated based on the individual sport prices.

### 6. LAUNCH SEQUENCING
- **Phase 1 Launch (June):** 
  - Sports: Soccer, NFL, NBA.
  - Tiers: Sharp and Pro for each sport.
  - Bundles: US Bundle, Summer Fill.
  
- **Migration Strategy:** Launch with sport-based pricing to allow users flexibility; migrate towards bundled offerings as more sports are added.

- **Promo Mechanics:**
  - First-N-Signups Offer: Free Sharp tier access for the first month.
  - Sunset of Flat Model: Transition period until end of June, then sunset flat model and promote new bundles.

### 7. COMPETITIVE POSITIONING
| Competitor | Sport     | Their Price (USD) | Our Sharp (USD) | Our Pro (USD) | Our Position       |
|------------|-----------|-------------------|-----------------|---------------|--------------------|
| OddsJam    | Soccer    | [ASSUMPTION — unverified] $200        | 24.99         | 49.99              | Strong Value      |

### 8. USER ARCHETYPE PACKAGING
**US Bettor:**
- **Starting SKU/Bundle:** US Bundle.
- **Upgrade Path:** Start with Sharp, upgrade to Pro for individual sports of interest, then potentially Elite tier.

**International Bettor:**
- **Starting SKU/Bundle:** International Bundle.
- **Upgrade Path:** Similar to US Bettor, start with Sharp in bundle, graduate to Pro and possibly Elite.

### 9. UNIT ECONOMICS
| Tier / Bundle   | Monthly Price (USD) | COGS ($/mo)       | Gross Margin % | LTV (12mo, USD)    |
|-----------------|---------------------|-------------------|---------------|--------------------|
| Sharp           | $24.99              | 0                 | 100%          | [MODELED — basis: first principles] $275.88      |
| Pro             | $49.99              | 0                 | 100%          | [MODELED — basis: first principles] $539.88      |

### 10. EXPLICIT QUESTION RESPONSES
**Q1:** Launch with sport-based pricing to allow users flexibility; migrate towards bundled offerings as more sports are added.
**Q2:** First-N-Signups Offer: Free Sharp tier access for the first month, sunset of flat model by end of June.
**Q3:** Recommend discount percentages for bundles: 20-28% based on individual sport prices.
**Q4:** Phase 1 launch includes Soccer, NFL, NBA with US Bundle and Summer Fill; migrate post-launch towards bundled offerings.
**Q5:** Benchmark against named competitors like OddsJam. Price relative to market signals strong value.

### 11. PRICING RISKS
- **Seasonal Churn at Season End:** Implement retention mechanics such as offers for next season, loyalty programs.
- **SKU Complexity Driving Decision Paralysis:** Clear and simple communication of benefits and pricing across different tiers.
- **Geo-Restriction / Gambling Regulation Exposure:** Legal review to ensure compliance with gambling laws in all markets.
- **Competitor Price Compression:** Monitor competitor prices; adjust pricing strategy based on market dynamics.

### 12. CROSS-TEAM FLAGS
- **Legal:** Verify legal compliance for gambling regulations across different regions.
- **Strategy:** Review retention mechanics and migration strategy post-launch.
- **Marketing:** Develop clear communication strategies for product positioning and discount structures.
- **Finance Orchestrator:** Monitor gross margins and ensure cost structures align with projected revenues.

### 13. OPEN QUESTIONS
**[ASSUMPTION — unverified]**: Verify competitor prices, especially OddsJam's pricing for Soccer.
**[MODELED — basis: first principles]**: Refine costs of goods sold (COGS) for specific sports or bundles post-launch to ensure accurate gross margin calculations.

### CONSOLIDATION REQUIREMENT:
- **Who should verify it:** Competitor Pricing - Market Research Team; COGS - Finance Team
- **What source or method would resolve it:** Competitor Pricing - Market Analysis Reports; COGS - Actual operating cost data
- **Launch-blocking or can be refined post-launch:** Not launch-blocking, but crucial for accurate financial projections.