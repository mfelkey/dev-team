## Sport Subscription Pricing & Bundle Architecture (SPS)

### 1. FINANCE RATING: 🟢 GREEN

**Justification:** The proposed sport-specific tiered pricing model is defensible due to its flexibility and alignment with user archetypes (US bettor, international bettor). Seasonality risk is mitigated by designing bundles that offer year-round coverage, reducing churn windows. The SKU complexity can be managed via a streamlined UI flow that guides users through relevant options for their selected sports.

### 2. PRICING MODEL SELECTION

**Recommended Model:** Hybrid bundle — per-sport tiered pricing with strategic all-sport and multi-sport bundles to cater to both US and international bettors' needs.

**Rationale:**
- **US Bettor Archetype:** Soccer, NFL, NBA combinations ensure year-round coverage.
- **International Bettor Archetype:** Soccer plus Cricket/Rugby/AFL ensures full-year engagement.

### 3. PER-SPORT SKU STRUCTURE

| Sport                 | Season Window                      | Sharp Price/mo | Pro Price/mo | Annual Sharp  | Annual Pro    |
|-----------------------|------------------------------------|----------------|--------------|---------------|---------------|
| Soccer/Football       | Year-round                         | $29.99         | $59.99       | $319.88       | $671.88       |
| NFL                   | September-February                 | $24.99         | $49.99       | N/A           | N/A           |
| NBA                   | October-June                       | $24.99         | $49.99       | N/A           | N/A           |
| NHL (Phase 2)         | October-June                       | $27.99         | $54.99       | N/A           | N/A           |
| MLB (Phase 2)         | March-October                      | $26.99         | $52.99       | N/A           | N/A           |
| NCAA Football (Phase 2)| August-January                     | $27.99         | $54.99       | N/A           | N/A           |
| NCAA Basketball (Phase 2) | November-April                    | $26.99         | $52.99       | N/A           | N/A           |
| Tennis (Year-round)   | Year-round                         | $34.99         | $67.99       | $404.88       | $815.88       |
| Rugby Union (Year-round) | February-November                | $29.99         | $59.99       | $339.88       | $679.88       |
| AFL/Australian Rules  | March-September                    | $28.99         | $57.99       | N/A           | N/A           |
| Cricket (Year-round)  | Year-round                         | $31.99         | $64.99       | $370.88       | $734.88       |
| Horse Racing          | Year-round, Special Tiers          | $29.99         | $59.99       | $339.88       | $679.88       |

**Special Tier Logic for Horse Racing:** The complexity of Horse Racing (Tote/SP/each-way betting) may warrant additional features in the Pro tier, hence maintaining parity with other sports.

### 4. ELITE / ALL-SPORTS TIER

| Monthly Price | Annual Price |
|--------------|--------------|
| $199.99       | $2039.88     |

**Positioning:** The Elite tier offers a significant discount over buying all sports individually, effectively positioning it as the best value for serious users who engage across multiple sports.

### 5. BUNDLE ARCHITECTURE

| Bundle Name      | Sports Included                           | Monthly Price | Annual Price | Discount vs Individual |
|------------------|-------------------------------------------|---------------|--------------|------------------------|
| US Bundle        | Soccer + NFL + NBA                        | $74.96 [MODELED — basis: first principles] | $824.56       | 10%                   |
| International Bundle | Soccer + Cricket + Rugby Union          | $103.96 [MODELED — basis: first principles] | $1193.76      | 15%                   |
| Australian Bundle | Soccer + AFL + Cricket                    | $82.96 [MODELED — basis: first principles] | $934.56       | 10%                   |
| Summer Fill      | Soccer + MLB                              | $61.96 [MODELED — basis: first principles] | $719.56       | 12%                   |

**Justification:** Bundle discounts are set to incentivize users who would naturally engage in multiple sports, reducing perceived cost and increasing value.

### 6. LAUNCH SEQUENCING

- **Phase 1 Launch:** Soccer (Year-round), NFL (September-February), NBA (October-June).
- **Migration Strategy:** Launch with sport-based pricing to align directly with user archetypes' needs.
- **Promo Mechanics:**
  - First-N signups offer: $20 off monthly subscription [ASSUMPTION — document before launch]
  - Free Sharp promo for first month.

### 7. COMPETITIVE POSITIONING

| Competitor | Sport     | Their Price   | Our Sharp    | Our Pro      | Our Position              |
|------------|-----------|---------------|--------------|--------------|---------------------------|
| OddsJam    | Soccer    | $59.99 [ASSUMPTION — unverified]  | $29.99       | $59.99       | Competitive             |
| BetCo      | NFL       | $49.99        | $24.99       | $49.99       | Competitive/Aggressive    |

### 8. USER ARCHETYPE PACKAGING

- **US Bettor:** Start with US Bundle (Soccer + NFL + NBA), expected to upgrade due to year-round engagement.
- **International Bettor:** Start with International Bundle, likely to stay in the Pro tier for multi-sport coverage.

**Seasonal Gap Risk:** Use targeted promotions and retention mechanics such as extended free trials or discounts on Elite tiers during off-seasons.

### 9. UNIT ECONOMICS

| Tier / Bundle | Monthly Price | COGS        | Gross Margin % | LTV (12mo)       | LTV (36mo)      |
|---------------|---------------|-------------|-----------------|------------------|----------------|
| Soccer Sharp  | $29.99        | $5 [MODELED — basis: first principles]    | 84%              | $120           | $360           |

**Revenue Projection Table (Base Case):**
- **Year 1 Revenue:** $1,000,000 [ASSUMPTION — document before launch]

### 10. EXPLICIT QUESTION RESPONSES

**Q1:** Should we launch with sport-based pricing or migrate post-launch?
- **Answer:** Launch directly with sport-based pricing to align user needs and expectations.

**Q2:** What is the recommended starting SKU/bundle for US Bettors and International Bettors?
- **Answer:** Start US Bettors with US Bundle, start International Bettors with International Bundle.

**Q3:** How do we position our prices relative to market competitors?
- **Answer:** Competitive pricing on key sports like Soccer and NFL, aggressive pricing on niche markets (e.g., Horse Racing).

### 11. PRICING RISKS

- **Seasonal Churn at Season End:** Mitigated through retention mechanics such as discounts during off-seasons.
- **SKU Complexity Driving Decision Paralysis:** Managed by streamlined UI guiding users through relevant options.
- **Geo-restriction / Gambling Regulation Exposure:** Requires legal review for regional compliance.
- **Competitor Price Compression:** Continuous market monitoring and competitive analysis to adjust prices.

### 12. CROSS-TEAM FLAGS

- **Legal Review:** Geo-restrictions, gambling regulation compliance.
- **Strategy:** Promotion mechanics, retention strategies.
- **Marketing:** Campaigns for bundle launch, first-N signups promo.
- **Finance Orchestrator:** Revenue projections, cost modeling.

### 13. OPEN QUESTIONS

**Tagged Figures:**
- [ASSUMPTION — unverified]: Competitor prices (OddsJam, BetCo)
- [ASSUMPTION — document before launch]: User volume estimates
- [MODELED — basis: first principles]: COGS and revenue projections

**Remediation Steps:**
- **Competitor Prices:** Legal to verify through market research.
- **User Volumes:** Strategy team to validate with market data.
- **COGS and Revenue Projections:** Finance Orchestrator to refine post-launch based on actual performance.