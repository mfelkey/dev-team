## Sport Subscription Pricing & Bundle Architecture (SPS) for PROJ-PARALLAXEDGE

### 1. FINANCE RATING
**Finance Rating: 🟢 GREEN**
The green rating reflects a solid revenue model viability, taking into account the seasonality risk and churn windows typical in sports subscriptions. ParallaxEdge has structured its pricing tiers and bundles to mitigate seasonal drop-offs by offering annual options with significant discounts and bundling multi-sport packages that span multiple seasons or provide year-round content.

### 2. PRICING MODEL SELECTION
**Recommended Model: Hybrid Bundle**
The hybrid bundle model combines per-sport tiered offerings with all-sport flat pricing, allowing flexibility for customers to subscribe to individual sports or a comprehensive package. This approach is well-suited to the two user archetypes — US bettor and international bettor — by offering personalized options that cater to specific interests while minimizing churn risks associated with single-sport subscriptions.

### 3. PER-SPORT SKU STRUCTURE
| Sport       | Season Window   | Sharp Price/mo ($) | Pro Price/mo ($) | Annual Sharp ($) | Annual Pro ($) |
|-------------|-----------------|--------------------|------------------|------------------|----------------|
| Soccer      | Sep - Jun       | 19.99              | 29.99            | 175.00           | 265.00         |
| NFL         | Aug - Feb       | 34.99              | 49.99            | 285.00           | 405.00         |
| NBA         | Oct - Apr       | 19.99              | 29.99            | 175.00           | 265.00         |
| Cricket     | Jan - Jun, Sep-Oct| 39.99             | 49.99            | 335.00           | 395.00         |
| Rugby       | Jan - May, Aug-Sep| 24.99             | 34.99            | 215.00           | 285.00         |
| AFL         | Mar - Sep       | 39.99              | 49.99            | 335.00           | 395.00         |
| MLB         | Apr - Oct       | 19.99              | 29.99            | 175.00           | 265.00         |

**Justification:**
- Prices are set to reflect competitive positioning against benchmarks like OddsJam and Betegy.
- Annual pricing offers a significant discount (approximately 10%) over monthly subscription to encourage long-term commitment.

### 4. ELITE / ALL-SPORTS TIER
| Tier       | Monthly Price ($) | Annual Price ($) |
|------------|-------------------|------------------|
| Elite      | 299.99            | 2,650.00         |

**Positioning vs per-sport stacking:**
The Elite tier is positioned as an all-encompassing package offering the best value at a significant discount compared to subscribing individually to each sport.

**Effective Discount Calculation:**
Assuming 7 sports:
- Individual Monthly Subscription Total = (19.99 + 34.99 + 19.99 + 39.99 + 24.99 + 39.99 + 19.99) * 12 ≈ $1,670
- Elite Annual Price = $2,650 (effective monthly: $220.83)
- Discount vs Individual Subscription = ($1,670 - $2,650) / $1,670 ≈ 15% annual discount.

### 5. BUNDLE ARCHITECTURE
| Bundle Name       | Sports Included                  | Monthly Price ($) | Annual Price ($) | Discount vs Individual (%) |
|-------------------|----------------------------------|-------------------|------------------|----------------------------|
| US Bundle         | Soccer, NFL, NBA                 | 84.97             | 705.00           | 10                         |
| International     | Soccer, Cricket, Rugby           | 103.96            | 865.00           | 12                         |
| Australian        | Soccer, AFL, Cricket             | 94.97             | 835.00           | 11                         |
| Summer Fill       | Soccer, MLB                      | 39.98             | 340.00           | 12                         |

**Justification:**
Discounts are designed to incentivize multi-sport subscriptions while maintaining a competitive edge over individual sport prices.

### 6. LAUNCH SEQUENCING
- **Phase 1 Launch:** Soccer, NFL, and NBA Sharp & Pro tiers; US Bundle.
- **Migration Strategy:** Start with sport-based pricing; migrate post-launch by introducing more bundles and all-sport Elite tier as user base grows.
- **Promo Mechanics:** First N signups offer a free month of the Sharp tier. Sunsetting the flat model to focus on per-tier subscriptions.

### 7. COMPETITIVE POSITIONING
| Competitor | Sport   | Their Price ($) | Our Sharp ($) | Our Pro ($) | Positioning          |
|------------|---------|-----------------|---------------|-------------|----------------------|
| OddsJam    | Soccer  | $399.99/mo      | $175/yr       | $265/yr     | More affordable      |
| Betegy     | NFL     | $400/mo         | $285/yr       | $405/yr     | Cost-effective Pro   |

### 8. USER ARCHETYPE PACKAGING
- **US Bettor:** Recommended starting SKU is the US Bundle; expected upgrade path to Elite tier.
- **International Bettor:** Starting with International or Australian Bundles, upgrading based on sport interest.
- **Seasonal Gap Risk Mitigation:** Year-round bundles and promotional offers at season end to retain users.

### 9. UNIT ECONOMICS
| Tier / Bundle | Monthly Price ($) | COGS ($/mo) | Gross Margin (%) | LTV (12mo) ($)   | LTV (36mo) ($) |
|---------------|-------------------|-------------|------------------|-----------------|----------------|
| Sharp         | 19.99             | 7           | 65               | 140             | 420            |
| Pro           | 29.99             | 10          | 67               | 230             | 690            |
| Elite         | 299.99            | 80          | 73               | 1,750           | 5,250          |

### 10. BRIEF QUESTIONS ANSWERED
- **Q:** What is the pricing model?
  - A: Hybrid Bundle
- **Q:** How are discounts structured?
  - A: Significant annual discount (~10%) over monthly subscription.
  
### 11. CROSS-TEAM FLAGS
- Product: Verify final competitor prices and market positioning.
- Sales & Marketing: Document promotional strategies for season-end retention.
- Operations: Confirm cost of goods sold (COGS) before launch.

### 12. OPEN QUESTIONS
- **[ASSUMPTION — unverified]** Competitor pricing data needs verification from industry reports.
- **[MODELED — basis: first principles]** COGS figures are modeled and should be verified with actual operational costs post-launch for refinement.