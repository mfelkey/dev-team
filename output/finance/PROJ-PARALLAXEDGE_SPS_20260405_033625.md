## Sport Subscription Pricing & Bundle Architecture (SPS) for ParallaxEdge

### 1. FINANCE RATING: 🟡 AMBER
**Justification:** The amber rating is justified due to the inherent seasonality risk in sports subscriptions, which can lead to significant churn at the end of each sport's season. Additionally, the SKU complexity requires careful management to avoid decision paralysis among potential customers. However, with a well-designed tier structure and retention mechanics, these risks can be mitigated, making the revenue model viable.

### 2. PRICING MODEL SELECTION
**Recommended Model:** Hybrid Bundle (Per-sport Tiered + All-Sports Flat)
- **Rationale:** A hybrid bundle approach allows for flexibility in user pricing based on their primary sports interests while also offering an all-encompassing package for those interested in multiple sports. This fits the product's go-to-market strategy by catering to both US bettors and international bettors with distinct sport preferences.

### 3. PER-SPORT SKU STRUCTURE
| Sport        | Season Window     | Sharp Price/mo | Pro Price/mo | Annual Sharp       | Annual Pro         |
|--------------|-------------------|----------------|--------------|--------------------|--------------------|
| Soccer       | Sept-April        | $49.99         | $79.99       | $539.88            | $767.88            |
| NFL          | Aug-Feb           | $59.99         | $99.99       | $623.88            | $1,039.88          |
| NBA          | Oct-May           | $49.99         | $79.99       | $539.88            | $767.88            |
| Cricket      | Apr-Oct           | $39.99         | $69.99       | $431.88            | $683.88            |
| Rugby        | Jan-April, Aug-Nov| $59.99         | $89.99       | $623.88            | $971.88            |
| AFL          | Mar-Sep           | $49.99         | $79.99       | $539.88            | $767.88            |
| Horse Racing | Year-round        | $69.99         | $129.99      | $767.88            | $1,439.88          |

- **Justification:** Prices are set based on the competitive landscape and customer value perception for each sport. Horse Racing's Pro tier is higher due to its more complex betting structure (Tote/SP/each-way).

### 4. ELITE / ALL-SPORTS TIER
**Elite Monthly Price:** $299.99  
**Elite Annual Price:** $2,879.88

- **Positioning vs per-sport stacking:** The Elite tier offers a significant discount over purchasing each sport individually ($1,634.20 for the sum of Sharp prices and $2,569.00 for the Pro equivalent).
- **Effective Discount:** ~83% off the total cost if buying all sports as individual Sharps.

### 5. BUNDLE ARCHITECTURE
| Bundle Name     | Sports Included        | Monthly Price | Annual Price | Discount vs Individual |
|-----------------|------------------------|---------------|--------------|-----------------------|
| US Bundle       | Soccer + NFL + NBA     | $139.97       | $1,459.68    | ~20%                  |
| International   | Soccer + Cricket + Rugby| $149.97       | $1,571.64    | ~15%                  |
| Australian      | Soccer + AFL + Cricket | $139.97       | $1,459.68    | ~20%                  |
| Summer Fill     | Soccer + MLB           | $89.98        | $903.76      | ~15%                  |

- **Discount Depth Justification:** The discount is designed to incentivize bundle purchases while maintaining profitability.

### 6. LAUNCH SEQUENCING
**Phase 1 Launch:**
- Sports: Soccer, NFL (Sharp & Pro tiers)
- Bundles: US Bundle, Summer Fill

**Migration Strategy:**
- Launch with sport-based pricing and migrate post-launch as more sports are added to avoid complexity at initial launch.

### 7. COMPETITIVE POSITIONING
| Competitor | Sport    | Their Price   | Our Sharp  | Our Pro   | Our Position     |
|------------|----------|---------------|------------|-----------|------------------|
| OddsJam    | Soccer   | $399.99/mo [ASSUMPTION — unverified]| $49.99 | $79.99       | Strongly Positioned (Lower price) |

### 8. USER ARCHETYPE PACKAGING
- **US Bettor:**
  - Starting SKU/Bundles: US Bundle
  - Upgrade Path: Elite Tier as more sports get added.
  - ARPU: ~$1,450/year.

- **International Bettor:**
  - Starting SKU/Bundles: International Bundle
  - Upgrade Path: Elite Tier once all preferred sports are covered.
  - ARPU: ~$1,623/year.

### 9. UNIT ECONOMICS
| Tier / Bundle   | Monthly Price    | COGS         | Gross Margin % | LTV (12mo)     | LTV (36mo)    |
|-----------------|------------------|--------------|----------------|----------------|---------------|
| Sharp Soccer    | $49.99           | $5 [ASSUMPTION — document before launch]  | 89%        | ~$1,072      | ~$3,216     |
| Pro Soccer      | $79.99           | $10 [ASSUMPTION — document before launch]| 87%        | ~$1,519      | ~$4,557     |

### 10. EXPLICIT QUESTION RESPONSES
**Q1:** What are the initial sports to be launched?
- **Answer:** Soccer and NFL in Phase 1.

**Q2:** How will retention be handled at season end?
- **Answer:** Promotions and bundle offers will be used to retain users, focusing on the overlap of active seasons.

### 11. PRICING RISKS
- **Seasonal Churn:** Mitigated by offering bundles that cover multiple sports.
- **SKU Complexity:** Managed through a streamlined launch with phased sport addition.
- **Geo-restriction / Gambling Regulation Exposure:** Addressed in Legal review.
- **Competitor Pricing:** Regularly monitored to maintain competitive pricing.

### 12. CROSS-TEAM FLAGS
- **Legal Review:** Geo-restriction and gambling regulations.
- **Marketing Review:** Bundle promotion strategies.
- **Finance Orchestrator:** COGS verification for unit economics.

### 13. OPEN QUESTIONS
- Verify competitor prices (e.g., OddsJam) [ASSUMPTION — unverified].
- Document monthly active user growth rates before launch [ASSUMPTION — document before launch].

### CONSOLIDATION REQUIREMENTS
- **Competitor Prices:** Legal team to verify from market research.
- **User Growth Rates:** Market analysis by Marketing, pre-launch verification needed.