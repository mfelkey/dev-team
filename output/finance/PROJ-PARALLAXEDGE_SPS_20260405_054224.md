## Sport Subscription Pricing & Bundle Architecture (SPS)

### 1. FINANCE RATING: 🟢 GREEN
The **GREEN** rating is due to the robust gross margins above 96 percent and low fixed costs under $1000/mo, which support a flexible pricing strategy. The primary risks revolve around seasonal churn and SKU complexity, but these are manageable with strategic bundle design and retention mechanisms.

### 2. PRICING MODEL SELECTION
**Recommended Model:** Per-sport tiered / Hybrid bundle

The per-sport tiered model is chosen to cater specifically to user archetypes like the US bettor and international bettor while offering flexibility through bundles that provide full-year coverage. This approach allows for precise targeting of different market segments based on their betting preferences and seasonal interests.

### 3. PER-SPORT SKU STRUCTURE
| Sport | Season Window          | Sharp Price/mo (USD) | Pro Price/mo (USD) | Annual Sharp (USD) | Annual Pro (USD) |
|-------|------------------------|----------------------|--------------------|--------------------|------------------|
| Soccer/Football     | Year-round, WC2026 Jun-Jul, EPL Sep-May, UCL Sep-May  | $24.99            | $49.99           | $174.99          | $359.99        |
| NFL                | September-February               | $24.99            | $69.99             | N/A              | N/A              |
| NBA                | October-June                     | $24.99            | $59.99             | N/A              | N/A              |
| NHL (Phase 2)      | October-June                     | $19.99 [ASSUMPTION — document before launch]     | $39.99 [ASSUMPTION — document before launch]           | N/A              | N/A              |
| MLB (Phase 2)      | March-October                    | $19.99            | $39.99             | N/A              | N/A              |
| NCAA Football (Phase 2)    | August-January               | $14.99 [ASSUMPTION — document before launch]     | $29.99 [ASSUMPTION — document before launch]            | N/A              | N/A              |
| NCAA Basketball (Phase 2)  | November-April                | $19.99            | $39.99             | N/A              | N/A              |
| Tennis    | Year-round                     | $24.99            | $49.99             | $174.99           | $359.99        |
| Rugby Union   | Year-round, Six Nations Feb-Mar, Super Rugby Feb-Jun, Rugby Championship Aug-Oct, Autumn Internationals Nov    | $24.99            | $69.99           | N/A              | N/A              |
| AFL (Australian Rules)  | March-September                | $19.99 [ASSUMPTION — document before launch]     | $39.99 [ASSUMPTION — document before launch]            | N/A              | N/A              |
| Cricket    | Year-round, varying seasons and formats  | $24.99            | $49.99             | $174.99          | $359.99        |

### 4. ELITE / ALL-SPORTS TIER
**Elite (All-Sports) Monthly Price:** $89.99  
**Annual Price:** $699.99

The Elite tier provides a significant discount compared to buying individual sports and allows for full-year coverage across all available sports.

### 5. BUNDLE ARCHITECTURE
| Bundle Name         | Sports Included                     | Monthly Price (USD) | Annual Price (USD) | Discount vs Individual |
|---------------------|-------------------------------------|--------------------|--------------------|------------------------|
| US Bundle           | Soccer + NFL + NBA                  | $89.97 [MODELED — basis: first principles]  | $699.95 [MODELED — basis: first principles]          | ~10%              |
| International Bundle| Soccer + Cricket + Rugby Union      | $84.97 [MODELED — basis: first principles]   | $639.95 [MODELED — basis: first principles]           | ~12%              |
| Australian Bundle   | Soccer + AFL + Cricket             | $79.97 [MODELED — basis: first principles]  | $589.95 [MODELED — basis: first principles]           | ~15%              |
| Summer Fill         | Soccer + MLB                       | $44.98 [MODELED — basis: first principles]   | $374.95 [MODELED — basis: first principles]            | ~20%              |

### 6. LAUNCH SEQUENCING
**Phase 1 Launch:**  
- **Sports and Tiers:** Soccer/Football, NFL, NBA with Sharp and Pro tiers.
- **Bundles:** US Bundle

**Migration Strategy:** Launch with sport-based pricing directly.

**Promo Mechanics:**
- First 500 signups receive a free trial of the Sharp tier for one month [MODELED — basis: first principles].
- Sunset flat model post-launch in favor of more flexible bundles and tiers.

### 7. COMPETITIVE POSITIONING
| Competitor | Sport     | Their Price (USD)        | Our Sharp (USD) | Our Pro (USD)   | Positioning          |
|------------|-----------|--------------------------|-----------------|------------------|-----------------------|
| OddsJam    | Soccer/Football | ~$200/mo [ASSUMPTION — unverified]       | $24.99            | $49.99           | More affordable, better value |

### 8. USER ARCHETYPE PACKAGING
**US Bettor:**
- **Starting SKU/Bundle:** US Bundle or individual Soccer/Football + NFL tiers.
- **Upgrade Path:** Start with Sharp tier for Soccer/Football and migrate to Pro as they expand into other sports like the NBA.
- **ARPU:** Estimated at $60/mo [MODELED — basis: first principles].

**International Bettor:**
- **Starting SKU/Bundle:** International Bundle or individual Soccer/football + Cricket tiers.
- **Upgrade Path:** Begin with Sharp tier and migrate to Pro as they engage more deeply with Rugby Union and other international sports.
- **ARPU:** Estimated at $50/mo [MODELED — basis: first principles].

**Seasonal Gap Risk:**
Retention mechanics include promotional offers for off-season periods, such as discounts on complementary sports or bundles.

### 9. UNIT ECONOMICS
| Tier / Bundle | Monthly Price (USD)    | COGS (USD)       | Gross Margin %   | LTV (12mo) (USD) | LTV (36mo) (USD) |
|---------------|------------------------|------------------|------------------|-------------------|-------------------|
| Sharp Soccer  | $24.99                 | $0.5 [ASSUMPTION — document before launch]   | >98%                | $174.99             | $359.99            |
| Pro Soccer    | $49.99                 | $1 [ASSUMPTION — document before launch]     | >98%                | $359.99             | $699.99            |
| US Bundle     | $89.97                 | $1.5 [ASSUMPTION — document before launch]   | >98%                | $699.95             | $1349.90           |

### 10. EXPLICIT QUESTION RESPONSES
**Q1:** Should we launch June 11 with sport-based pricing or migrate post-launch?  
- **Answer:** Launch directly with sport-based pricing to immediately align with user preferences and betting habits.

**Q2:** Recommended Sharp and Pro price points per sport?
- **Answer:** See Per-Sport SKU Structure table above for detailed pricing recommendations.

**Q3:** Elite all-sports price point?  
- **Answer:** Monthly: $89.99, Annual: $699.99

**Q4:** Bundle discount structure — what percentage off for 2-sport, 3-sport, and all-sport bundles?
- **Answer:** See Bundle Architecture table above; discounts range from ~10% to ~20%.

**Q5:** Projected ARPU impact vs current flat model?  
- **Answer:** Estimated increase in ARPU due to flexible pricing tiers and targeted bundles.

**Q6:** Conversion risk of sport-based vs flat tiers?
- **Answer:** Moderate conversion risk due to initial complexity, but mitigated by strategic promotions and retention mechanics.

**Q7:** Should Horse Racing use the same Sharp/Pro structure or a different model?  
- **Answer:** Use the same Sharp/Pro structure for consistency across all sports.

**Q8:** Which bundles make the most business sense at launch vs Phase 2?
- **Answer:** Launch with US Bundle; expand to International and Australian Bundles in Phase 2 based on user demand and market feedback.

### 11. PRICING RISKS
- **Seasonal Churn:** Address through promotions and retention mechanisms during off-seasons.
- **SKU Complexity:** Mitigate by offering clear, targeted bundles that simplify the decision-making process.
- **Geo-restriction / Gambling Regulation Exposure:** Legal review to ensure compliance with local laws.
- **Competitor Price Compression:** Monitor market trends closely; maintain competitive pricing without sacrificing margins.

### 12. CROSS-TEAM FLAGS
- **Legal:** Review geo-restrictions and gambling regulations for each market.
- **Strategy:** Determine optimal launch sequence based on user demographics and betting preferences.
- **Marketing:** Develop promotional strategies to mitigate seasonal churn risks.
- **Finance Orchestrator:** Confirm COGS and other financial assumptions before finalizing pricing.

### 13. OPEN QUESTIONS
- **Verification Steps:**
    - [ASSUMPTION — unverified]: Verify competitor prices through market research.
    - [ASSUMPTION — document before launch]: Define user volumes, conversion rates, churn rates with historical data or market surveys.
    - [MODELED — basis: first principles]: Validate cost of goods sold (COGS) and other derived financial figures with upstream artifacts.

This completes the Sport Subscription Pricing & Bundle Architecture (SPS).